---
unique-page-id: 1147328
description: "Learn about hard and soft bounces and how Marketo classifies them. Use Email Suspended and Email Invalid fields to manage troubled delivery."
title: Hard and Soft Bounces in Email
exl-id: 53298562-76b6-473a-bf9f-2bec682f4d35
feature: Deliverability
---
# Hard and Soft Bounces in Email {#hard-and-soft-bounces-in-email}

A hard bounce can render a person's email address invalid when a mail server tells Marketo that the person's email can't be delivered. A soft bounce means something went wrong in delivering the email to the person; this automatically gets resolved and can sometimes takes days. Both hard and soft bounces consist of [multiple categories](https://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838).

## Bounce Classification {#bounce-classification}

There are 5 person strings in Marketo that are related to troubled email delivery.

1. **Email Suspended** - Set to True when a certain type of hard bounce occurs.
1. **Email Suspended Cause** - There can be many reasons. This field tries to explain the cause.
1. **Email Suspended At** - When the offending bounce occurs, Marketo will suspend mailing to the person for 24 hours from this timestamp.
1. **Email Invalid** - Set to True when a certain type of hard bounce occurs.
1. **Email Invalid Cause** - The reason for the hard bounce.

>[!NOTE]
>
>After a person reaches **email suspended** status, there is no way to clear the email suspended checkbox. However, the person will still become mailable 24 hours after the initial suspension.
>
>When a person is marked as **email invalid**, they can only be reset manually (which we recommend you only do if you know for certain their email is valid) by unchecking the "Email Invalid" box in the Person Info tab of their record.

>[!PREREQUISITES]
>
>Follow [these steps](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md) to create an Email Performance Report, which will generate bounce data.

After creating your Email Performance Report, your screen should look something like this:

![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>Spam filters sometimes create hard bounces. These "false-positives" are not an indication of the true validity of the person's email address.

## Bounce Categories {#bounce-categories}

Bounce codes follow SMTP conventions. Understanding which category a bounce falls into helps you diagnose delivery issues and predict how Marketo will respond.

<table>
<tr>
<td width="25%"><b>Category</b></td>
<td width="35%"><b>Example Codes</b></td>
<td width="40%"><b>Marketo Behavior</b></td>
</tr>
<tr>
<td><b>Hard Bounce (5xx)</b></td>
<td>550 — Invalid address<br>551 — User not local<br>553 — Domain does not exist<br>550 — Recipient rejected</td>
<td>Sets <b>Email Invalid</b> = true. The person is permanently blocked from receiving emails until the field is manually reset.</td>
</tr>
<tr>
<td><b>Soft Bounce (4xx)</b></td>
<td>452 — Mailbox full<br>421 — Server temporarily unavailable<br>452 — Too many connections<br>554 — Message too large or content rejected</td>
<td>Sets <b>Email Suspended</b> = true for 24 hours. The person automatically becomes mailable again once the suspension period expires.</td>
</tr>
</table>

>[!IMPORTANT]
>
>Not every 5xx code results in a hard bounce, and not every 4xx code results in a soft bounce. Marketo uses its own classification logic on top of raw SMTP codes, which is why the **Email Suspended Cause** and **Email Invalid Cause** fields are your best source of truth for what actually happened.

## How Marketo Handles Bounces {#how-marketo-handles-bounces}

Marketo processes hard and soft bounces differently, and each type triggers a distinct set of field updates on the person record.

**Hard bounces** set the **Email Invalid** field to `true` and populate **Email Invalid Cause** with the reason. This is a permanent flag — the person will not receive any further marketing emails from Marketo until you manually uncheck the **Email Invalid** field on their Person Info tab. Only do this if you have independently verified that the address is valid (for example, the person contacted you from that address).

**Soft bounces** set the **Email Suspended** field to `true` and record the timestamp in **Email Suspended At**. For the next 24 hours, Marketo will skip the person during email sends. After 24 hours, the person automatically becomes mailable again — no manual intervention is required.

**Repeated soft bounces** can escalate. If Marketo sees a pattern of consecutive soft bounces to the same address, it may eventually treat the address as a hard bounce and set **Email Invalid** to `true`. The exact threshold depends on the bounce type and Marketo's internal classification rules.

>[!CAUTION]
>
>Re-importing contacts whose addresses were previously marked as Email Invalid — without first verifying the addresses are deliverable — can cause additional bounces that damage your sender reputation and may trigger IP blacklisting.

## List Hygiene Best Practices {#list-hygiene-best-practices}

>[!TIP]
>
>**Keep your database clean to protect your sender reputation.**
>
>- **Review Email Invalid records regularly.** Create a Smart List with the filter _Email Invalid = true_ and review it monthly. Decide whether each address should be corrected, verified, or removed from your database.
>- **Implement a sunset policy.** If a person hasn't opened or clicked any email in 6 or more months, consider suppressing them from active sends. High volumes of sends to unengaged contacts signal poor list quality to mailbox providers and can land your emails in spam.
>- **Never re-import hard-bounced addresses without verification.** Running previously bounced addresses through a third-party email verification service before re-importing them prevents unnecessary bounces and protects your IP reputation.
>- **Monitor bounce activity with Smart Lists.** Use the _Email Bounced_ and _Email Bounced Soft_ activity filters to build Smart Lists that track bounce rates over time. A sudden spike in bounces often indicates a list quality issue or a deliverability problem that needs immediate attention.
