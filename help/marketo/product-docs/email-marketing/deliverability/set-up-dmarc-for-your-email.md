---
unique-page-id: set-up-dmarc
description: "Learn how to set up DMARC for your sending domain. DMARC completes the SPF/DKIM authentication triad and is required by Gmail and Yahoo for bulk senders."
title: Set up DMARC for your Email
exl-id: dmarc-setup-guide
feature: Deliverability
---
# Set up DMARC for your Email {#set-up-dmarc-for-your-email}

DMARC (Domain-based Message Authentication, Reporting and Conformance) is an email authentication protocol that works alongside [SPF and DKIM](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md){target="_blank"}. It tells receiving mail servers what to do when an email claiming to be from your domain fails SPF or DKIM checks.

>[!IMPORTANT]
>
>As of February 2024, Gmail and Yahoo require all bulk senders (5,000+ messages/day) to have a DMARC record published. If you send marketing emails through Marketo and don't have DMARC set up, your deliverability may be affected.

## How DMARC Works {#how-dmarc-works}

SPF and DKIM verify that an email was actually sent from an authorized server. DMARC adds two things on top:

1. **A policy** — tells the receiving server whether to deliver, quarantine, or reject messages that fail authentication.
2. **Reporting** — sends you daily reports about which messages passed or failed, so you can see if anyone is forging your domain.

DMARC checks for **alignment** between the visible "From:" domain and the domains authenticated by SPF or DKIM. If neither aligns with the "From:" domain, DMARC fails.

## Prerequisites {#prerequisites}

Before setting up DMARC, make sure you have:

* [SPF configured](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md){target="_blank"} with `include:mktomail.com`
* [Custom DKIM signing](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"} set up for your sending domain (not the shared Marketo signature)

>[!CAUTION]
>
>If you're still using Marketo's shared DKIM signature (signing with `d=mktomail.com`), DKIM alignment will fail because the signing domain doesn't match your "From:" domain. Set up custom DKIM before enabling a DMARC enforcement policy.

## Create Your DMARC Record {#create-your-dmarc-record}

A DMARC record is a DNS TXT record published at `_dmarc.yourdomain.com`. Here is the basic structure:

`_dmarc.yourdomain.com. TXT "v=DMARC1; p=none; rua=mailto:dmarc-reports@yourdomain.com"`

**Tags explained:**

<table>
<thead>
  <tr>
    <th width="20%">Tag</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><code>v=DMARC1</code></td>
    <td>Version identifier. Always <code>DMARC1</code>.</td>
  </tr>
  <tr>
    <td><code>p=</code></td>
    <td><b>Policy.</b> What to do with messages that fail. Options: <code>none</code>, <code>quarantine</code>, or <code>reject</code>.</td>
  </tr>
  <tr>
    <td><code>sp=</code></td>
    <td><b>Subdomain policy.</b> Applies to subdomains. Inherits from <code>p=</code> if omitted.</td>
  </tr>
  <tr>
    <td><code>rua=</code></td>
    <td>Email address to receive <b>aggregate reports</b> (daily summaries of pass/fail results).</td>
  </tr>
  <tr>
    <td><code>ruf=</code></td>
    <td>Email address to receive <b>forensic reports</b> (per-failure detail). Optional — not all ISPs send these.</td>
  </tr>
  <tr>
    <td><code>adkim=</code></td>
    <td>DKIM alignment mode: <code>r</code> (relaxed, default) or <code>s</code> (strict).</td>
  </tr>
  <tr>
    <td><code>aspf=</code></td>
    <td>SPF alignment mode: <code>r</code> (relaxed, default) or <code>s</code> (strict).</td>
  </tr>
  <tr>
    <td><code>pct=</code></td>
    <td>Percentage of failing messages to apply the policy to (1-100). Default is 100.</td>
  </tr>
</tbody>
</table>

## Policy Options {#policy-options}

DMARC has three policy levels. Start with monitoring and work your way up:

* **`p=none`** — Monitor only. Messages are delivered normally, but you receive reports on authentication results. This is the starting point.
* **`p=quarantine`** — Messages that fail authentication are sent to the recipient's spam/junk folder.
* **`p=reject`** — Messages that fail authentication are rejected outright. The recipient never sees them.

>[!CAUTION]
>
>Do not set your policy to `quarantine` or `reject` until you've confirmed that all legitimate email sources (including Marketo) are passing DKIM and SPF alignment. Setting a strict policy too early can cause your own emails to be blocked.

## Recommended Rollout Steps {#recommended-rollout-steps}

DMARC should be rolled out gradually. Rushing to enforcement can cause legitimate mail to be rejected.

1. **Publish with `p=none`** — Start by adding a DMARC record with a monitoring-only policy. This lets you collect reports without affecting delivery.

   `_dmarc.yourdomain.com. TXT "v=DMARC1; p=none; rua=mailto:dmarc-reports@yourdomain.com"`

1. **Monitor reports for 2-4 weeks** — Review aggregate reports to identify all legitimate sources sending as your domain. Verify that Marketo emails are passing both SPF and DKIM alignment.

   >[!TIP]
   >
   >Aggregate reports are XML files that can be difficult to read. Free tools like [MXToolbox DMARC Report Analyzer](https://mxtoolbox.com/DmarcReportAnalyzer.aspx){target="_blank"} can parse them into a readable format.

1. **Fix any authentication failures** — If Marketo emails are failing alignment, verify your [custom DKIM setup](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"} and [SPF record](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md){target="_blank"}. Also check for any other services sending email as your domain (e.g., CRM, support ticketing, transactional email providers).

1. **Move to `p=quarantine` at a low percentage** — Once reports show clean results, move to enforcement gradually.

   `_dmarc.yourdomain.com. TXT "v=DMARC1; p=quarantine; pct=10; rua=mailto:dmarc-reports@yourdomain.com"`

1. **Increase percentage over time** — Raise `pct=` from 10 to 25, then 50, then 100 as confidence grows.

1. **Consider `p=reject`** — Once all legitimate senders are fully authenticated and you've been at `p=quarantine; pct=100` for several weeks with no issues, move to reject for the strongest protection.

## DMARC Alignment with Marketo {#dmarc-alignment-with-marketo}

DMARC checks alignment in two ways. At least one must pass for DMARC to pass:

**DKIM alignment** (recommended for Marketo):

The domain in the DKIM signature (`d=` tag) must match the domain in the "From:" header. When you set up [custom DKIM](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}, Marketo signs with `d=yourdomain.com`, which aligns with your "From:" address.

**SPF alignment**:

The domain in the Return-Path (envelope sender) must match the "From:" domain. Marketo's default Return-Path uses `mktomail.com`, which does not align with your domain. Most Marketo customers rely on DKIM alignment instead.

>[!NOTE]
>
>You can verify alignment by sending a test email to a Gmail address. Click the three-dot menu on the message and select **Show Original**. Look for `dmarc=pass` in the authentication results. If you see `dmarc=fail`, check the `DKIM-Signature` header — if it shows `d=mktomail.com` instead of your domain, your custom DKIM is not configured correctly.

## Subdomain Considerations {#subdomain-considerations}

If you send Marketo emails from a subdomain (e.g., `email.yourdomain.com` or `go.yourdomain.com`), be aware of how DMARC policies inherit.

When a subdomain does not have its own DMARC record, it inherits the parent domain's `sp=` (subdomain policy) tag. If the parent has `sp=reject` or `sp=quarantine`, the subdomain's emails will be subject to that policy.

>[!IMPORTANT]
>
>If your organization's root domain has a strict DMARC policy (`sp=reject` or `sp=quarantine`) and you're sending Marketo emails from a subdomain, you may need to publish a separate DMARC record for that subdomain with a more permissive policy during initial setup.
>
>Example: `_dmarc.go.yourdomain.com. TXT "v=DMARC1; p=none; rua=mailto:dmarc-reports@yourdomain.com"`

## Verifying Your DMARC Record {#verifying-your-dmarc-record}

After publishing your DMARC record, verify it's live:

1. Wait for DNS propagation (typically 15 minutes to 1 hour, depending on your DNS provider's TTL settings).

1. Use a DMARC lookup tool such as [MXToolbox](https://mxtoolbox.com/dmarc.aspx){target="_blank"} to confirm the record is published correctly.

1. Send a test email from Marketo to a Gmail address. In the **Show Original** view, verify that all three lines show `PASS`:

   * `SPF: PASS`
   * `DKIM: PASS`
   * `DMARC: PASS`

## Troubleshooting {#troubleshooting}

**DMARC shows `fail` in email headers**

* Check that [custom DKIM](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"} is set up and verified in Marketo Admin. If the DKIM signature shows `d=mktomail.com`, alignment will fail.
* Verify your SPF record includes `include:mktomail.com`.
* Make sure the domain in your "From:" address matches the domain you configured DKIM for.

**Not receiving aggregate reports**

* Confirm `rua=` contains a valid `mailto:` address.
* Some DNS providers require the `rua=` value to be within the same domain as the DMARC record. If reporting to a different domain, you may need to add a DNS authorization record. See [DMARC.org's FAQ](https://dmarc.org/wiki/FAQ){target="_blank"} for details.

**Emails going to spam after enabling `p=quarantine` or `p=reject`**

* Roll back to `p=none` and review your aggregate reports to identify which messages are failing.
* Verify every service that sends email as your domain has proper SPF/DKIM configuration before re-enabling enforcement.

>[!MORELIKETHIS]
>
>* [Set up SPF and DKIM for your Email Deliverability](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md){target="_blank"}
>* [Set up a Custom DKIM Signature](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}
>* [Shared and Dedicated IP Addresses](/help/marketo/product-docs/email-marketing/deliverability/shared-and-dedicated-ip-addresses.md){target="_blank"}
