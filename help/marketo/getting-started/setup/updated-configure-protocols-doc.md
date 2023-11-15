---
description: Updated Configure Protocols Doc - Marketo Docs - Product Documentation
title: Updated Configure Protocols Doc
hide: yes
hidefromtoc: yes
feature: Getting Started
---
# Updated Configure Protocols Doc {#updated-configure-protocols-doc}

If you or your organization use restrictive firewall or proxy server settings, you or your network administrator may need to allowlist certain domains and IP address ranges to ensure Adobe Marketo Engage works as expected.

For help implementing the protocols below, please share this article with your IT department. If they restrict web access using an allowlist, make sure they add the following domains (including the asterisk) to allow all Marketo resources and websockets:

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`
* `*.experience.adobe.com`
* `*.adobe.net`

## Step 1: Create DNS Records for Landing Pages and Email {#step-create-dns-records-for-landing-pages-and-email}

**Tracking Link CNAMEs**

Your marketing team should have sent you two requests for new CNAME records. The first is for landing page URLs, so that the landing pages appear in URLs that reflect your domain and not Marketo (the actual host). The second is for the tracking links that are included in the emails they send from Marketo.

`1` **Add CNAME for Landing Pages**

Add the landing page CNAME they sent you to your DNS record, so that `[YourLandingPageCNAME]` points to the unique Account String that is assigned to your Marketo landing pages. Log in to your domain registrar's site and enter the landing page CNAME and Account String. Typically, this involves three fields:

* Alias: Enter `[YourLandingPageCNAME]` (provided by marketing)
* Type: CNAME  
* Point to: Enter `[MunchkinID].mktoweb.com` (provided by marketing)

`2` **Add CNAME for Email Tracking Links**

Add the email CNAME marketing sent you, so that `[YourEmailCNAME]` points to [MktoTrackingLink], the default tracking link that Marketo assigned, in the format:  
`[YourEmailCNAME].[YourDomain].com` IN CNAME `[MktoTrackingLink]`

For example:  

`pages.abc.com IN CNAME mkto-a0244.com`

>[!NOTE]
>
>`[MktoTrackingLink]` must be the Default Branding Domain.

`3` **Notify Your Marketing Team**

Notify your marketing team when you've completed this process.

`4` **Contact [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} to start the process of provisioning an SSL Certificate.**

This process can take up to 3 business days to complete.

## Step 2: Allowlist Marketo IPs {#step-allowlist-marketo-ips}

When your Marketing group uses Marketo to send test emails (a best practice before sending out email blasts), the test emails are sometimes blocked by anti-spam systems that rely on sender IP addresses to verify that the email is valid. To ensure that those test emails arrive, add Marketo to your allowlist.

Add these IP addresses to your corporate allowlist:

94.236.119.0/26

103.237.104.0/22

130.248.172.0/24

130.248.173.0/24

130.248.244.88/29

185.28.196.0/22

192.28.144.0/20

192.28.160.0/19

199.15.212.0/22

Some anti-spam systems use the email Return-Path field instead of the IP address for allowisting. In those cases, the best approach is to allowlist '&#42;.mktomail.com', as Marketo uses several mailbox subdomains. Other anti-spam systems allowlist based on the From address. In these situations, be sure to include all the sending ('From') domains that your Marketing group uses to communicate with people/leads.

>[!NOTE]
>
>Postini employs a unique technology and requires allowlisting IP ranges. See [Allowlisting with Postini](https://nation.marketo.com/docs/DOC-1066).

## Step 3: Set up SPF and DKIM {#step-set-up-spf-and-dkim}

Your marketing team should have also sent you DKIM (Domain Keys Identified Mail) information to be added to your DNS resource record (also listed below). Follow the steps to successfully configure DKIM and SPF (Sender Policy Framework), then notify your marketing team that this has been updated.

1. To set up SPF, add the following line to our DNS entries:

   `[CompanyDomain]` IN TXT v=spf1 mx ip4:`[CorpIP]`  
   include: mktomail.com ~all
  
   If we already have an existing SPF record in our DNS entry, simply add the following to it:  
   include: mktomail.com

   Replace CompanyDomain with the main domain of your website (ex: "`(company.com/)`") and CorpIP with the IP address of your corporate email server (ex. "255.255.255.255"). If you are going to be sending email from multiple domains through Marketo, you should have your IT staff add this line for each domain (on one line).

1. For DKIM, create DNS Resource Records for each domain we'd like to set up. Below are the Host Records and TXT Values for each domain we'll be signing for:

   `[DKIMDomain1]`: Host Record is `[HostRecord1]` and the TXT Value is `[TXTValue1]`.

   `[DKIMDomain2]`: Host Record is `[HostRecord2]` and the TXT Value is `[TXTValue2]`.

   Copy the HostRecord and TXTValue for each DKIMDomain you've set up after following the [instructions here](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}. Don't forget to verify each domain in Admin > Email > DKIM after your IT staff has completed this step.

## Step 4: Set up DMARC (Domain-based Message Authentication, Reporting & Conformance) {#set-up-dmarc}

DMARC is an authentication protocol used to help organizations protect their domain from unauthorized use. DMARC extends the existing authentication protocols, such as SPF and DKIM, to inform recipient servers on what actions they should take if a failure in authentication occurs on their domain. Although DMARC is currently optional, it is strongly recommended as it will better protect your organization's brand and reputation. Major providers such as Google and Yahoo will require the use of DMARC for bulk senders beginning February 2024.

For DMARC to function, you must have at least one of the following DNS TXT records:

* A Valid SPF
* A Valid DKIM Record for your FROM: Domain (recommended for Marketo Engage)

In addition, you must have a DMARC-specific DNS TXT record for your FROM: Domain. Optionally, an email address of your choosing can be defined to indicate where DMARC reports should go within your organization, so you can monitor reports.

As a best practice, it's recommended to slowly roll out DMARC implementation by escalating your DMARC policy from p=none, to p=quarantine, to p=reject as you gain understanding of DMARC's potential impact, and set your DMARC policy to relaxed alignment on SPF and DKIM.

### DMARC Example Workflow {#dmarc-example-workflow}

1. If you're configured to receive DMARC reports, you should do the following...

   I. Analyze the feedback and reports you receive and use (p=none), which tells the receiver to perform no actions against messages that fail authentication, but still send email reports to the sender.

   II. Review and fix issues with SPF/DKIM if legitimate messages are failing authentication.

   III. Determine if SPF or DKIM are aligned and passing authentication for all legitimate email.

   IV. Review reports to ensure the results are what you expect based on your SPF/DKIM policies.

1. Proceed to adjust the policy to (p=quarantine), which tells the receiving email server to quarantine email that fails authentication (this typically means placing those messages in the spam folder).

   I. Review reports to ensure that the results are what you expect.

1. If you're satisfied with the behavior of messages at the p=quarantine level, you can adjust policy to (p=reject). The p=reject policy tells the receiver to completely deny (bounce) any email for the domain that fails authentication. With this policy enabled, only email that's verified as 100% authenticated by your domain will even have a chance at inbox placement.

>[!CAUTION]
>
>Use this policy with caution and determine if it's appropriate for your organization.

### DMARC Reporting {#dmarc-reporting}

DMARC offers the ability to receive reports regarding emails that fail SPF/DKIM. There are two different reports generated by ISP servicers as part of the authentication process that senders can receive through the RUA/RUF tags in their DMARC policy.

* Aggregate Reports (RUA): Does not contain any PII (Personally Identifiable Information) that would be GDPR (General Data Protection Regulation) sensitive.

* Forensic Reports (RUF): Contains email addresses which are GDPR sensitive. Before utilizing, it's best to check internally how to deal with information that needs to be GDPR compliant.

The main use of these reports is to receive an overview of emails that are attempted spoofing. These are highly technical reports that are best digested through a third-party tool.

### Example DMARC Records {#example-dmarc-records}

* Bare Minimum Record: `v=DMARC1; p=none`

* Record directing to an email address to receive reports: `v=DMARC1; p=none;  rua=mailto:emaill@domain.com;     ruf=mailto:email@domain.com`

### DMARC Tags and What They Do {#dmarc-tags-and-what-they-do}

DMARC records have multiple components called DMARC tags. Each tag has a value that specifies a certain aspect of DMARC.

<table>
<thead>
  <tr>
    <th>Tag Name </th>
    <th>Required/Optional </th>
    <th>Function </th>
    <th>Example </th>
    <th>Default value </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>v</td>
    <td>Required</td>
    <td>This DMARC tag specifies the version. There is only one version as of now, so this will have a fixed value of v=DMARC1</td>
    <td>V=DMARC1 DMARC1</td>
    <td>DMARC1</td>
  </tr>
  <tr>
    <td>p</td>
    <td>Required</td>
    <td>Shows the DMARC policy selected and directs the receiver to report, quarantine, or reject mail that fails authentication checks.</td>
    <td>p=none, quarantine, or reject</td>
    <td>-</td>
  </tr>
  <tr>
    <td>fo</td>
    <td>Optional</td>
    <td>Allows the domain owner to specify reporting options.</td>
    <td>0: Generate report if everything fails 
    <br>1: Generate report if anything fails 
    <br>d: Generate report if DKIM fails 
    <br>s: Generate report if SPF fails</td>
    <td>1 (recommended for DMARC reports)</td>
  </tr>
  <tr>
    <td>pct</td>
    <td>Optional</td>
    <td>Tells the percentage of messages subjected to filtering.</td>
    <td>pct=20</td>
    <td>100</td>
  </tr>
  <tr>
    <td>rua</td>
    <td>Optional (recommended)</td>
    <td>Identifies where aggregate reports will be delivered.</td>
    <td>rua=mailto:aggrep@example.com</td>
    <td>-</td>
  </tr>
  <tr>
    <td>ruf</td>
    <td>Optional (recommended)</td>
    <td>Identifies where forensic reports will be delivered.</td>
    <td>ruf=mailto:authfail@example.com</td>
    <td>-</td>
  </tr>
  <tr>
    <td>sp</td>
    <td>Optional</td>
    <td>Specifies DMARC policy for subdomains of the parent domain.</td>
    <td>sp=reject</td>
    <td>-</td>
  </tr>
  <tr>
    <td>adkim</td>
    <td>Optional</td>
    <td>Can either be Strict (s) or Relaxed &reg;. Relaxed alignment means the domain used in the DKIM signature can be a subdomain of the "From" address. Strict alignment means the domain used in the DKIM signature must be an exact match of the domain used in the From address.</td>
    <td>adkim=r </td>
    <td>r</td>
  </tr>
  <tr>
    <td>aspf</td>
    <td>Optional</td>
    <td>Can either be Strict (s) or Relaxed &reg;. Relaxed alignment means that the ReturnPath Domain can be a subdomain of the From Address. Strict alignment means the Return-Path domain must be an exact match with the From address.</td>
    <td>aspf=r</td>
    <td>r</td>
  </tr>
</tbody>
</table>

For full details around DMARC and all its options, please visit [https://dmarc.org/](https://dmarc.org/){target="_blank"}.

### DMARC and Marketo Engage {#dmarc-and-marketo-engage}

There are two types of alignment for DMARC&mdash;DKIM alignment and SPF alignment.

>[!NOTE]
>
>It's recommended to do DMARC alignment on DKIM vs SPF for Marketo.

* DKIM-aligned DMARC&mdash;To set up DKIM aligned DMARC you must:
   
   * Set up DKIM for the FROM: Domain of your message. Use the instructions [in this article](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}.
   * Configure DMARC for the FROM:/DKIM Domain that was configured earlier

* DMARC-aligned SPF&mdash;To set up DMARC aligned SPF via branded return-path, you must:

   * Set up Branded Return-Path Domain
      * Configure the appropriate SPF record
      * Change the MX record to point back to the default MX for the datacenter your mail will be sent out of

   * Configure DMARC for the Branded Return-Path Domain

* If you're sending mail from Marketo through a dedicated IP and have not already implemented branded return-path, or aren't sure if you have, please open a ticket with [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

* If you're sending mail from Marketo through a shared pool of IPs, you can see if you qualify for Trusted IPs by [applying here](http://na-sjg.marketo.com/lp/marketoprivacydemo/Trusted-IP-Sending-Range-Program.html){target="_blank"}. Branded return-path is offered for free to those sending from Marketo's Trusted IPs. If approved for this program, reach out to Marketo Support to set up branded return-path.

   * Trusted IPs: A shared pool of IPs reserved for lower volume users sending <75K/month who do not qualify for a dedicated IP. These users must also meet best practice requirements as well.

* If you're sending mail from Marketo through shared IPs and you do not qualify for Trusted IPs and send more than 100,000 messages per month, you'll need to contact the Adobe Account Team (your account manager) to purchase a dedicated IP.

* Strict SPF alignment is not supported nor recommended within Marketo.

## Step 5: Set up MX Records for Your Domain {#step-set-up-mx-records-for-your-domain}

An MX record allows you to receive mail to the domain that you're sending email from to process replies and auto-responders. If you're sending from your corporate domain, you likely already have this configured. If not, you can usually set it up to map to your corporate domain's MX record.

## Outbound IP Addresses {#outbound-ip-addresses}

An outbound connection is one made by Marketo Engage to a server on the internet on your behalf. Some partners/vendors you work with, or your own IT organization, may use allowlists to restrict access to servers. If so, you must provide them with Marketo Engage outbound IP address blocks to add to their allowlists.

**Webhooks**

Marketo Engage [Webhooks](/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md){target="_blank"} are an outbound integration mechanism. When a [Call Webhook](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/call-webhook.md){target="_blank"} flow action is executed as part of a smart campaign, an HTTP request is made to an external web service. If the web service publisher uses an allowlist on the firewall of the network where the external web service is located, then the publisher must add the IP address blocks listed below to their allowlist.

**CRM Sync**

Marketo Engage [Salesforce CRM Sync](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/add-an-existing-salesforce-field-to-the-marketo-sync.md){target="_blank"} and [Microsoft Dynamics Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md){target="_blank"} are integration mechanisms that make outbound HTTP requests to APIs published by your CRM vendor. You must ensure that your IT organization does not block any of the IP address blocks below from accessing your CRM vendor APIs.

**Marketo Engage Outbound IP Address Blocks**

The following tables cover all Marketo Engage servers that make outbound calls. Use the lists below if you're configuring any IP allowlist, server, firewall, access control list, security group, or third-party service to receive outgoing connections from Marketo Engage.

<table>
 <tbody>
  <tr>
   <th>IP Block (CIDR Notation)</th>
  </tr>
  <tr>
   <td>94.236.119.0/26</td>
  </tr>
  <tr>
   <td>103.237.104.0/22</td>
  </tr>
   <tr>
   <td>130.248.172.0/24</td>
  </tr>
   <tr>
   <td>130.248.173.0/24</td>
  </tr>
  <tr>
   <td>130.248.244.88/29</td>
  </tr>
  <tr>
   <td>185.28.196.0/22</td>
  </tr>
  <tr>
   <td>192.28.144.0/20</td>
  </tr>
  <tr>
   <td>192.28.160.0/19</td>
  </tr>
  <tr>
   <td>199.15.212.0/22</td>
  </tr>
 </tbody>
</table>

<table>
 <tbody>
  <tr>
   <th>Individual IP address</th>
  </tr>
  <tr>
   <td>13.237.155.207</td>
  </tr>
   <tr>
   <td>13.55.192.247</td>
  </tr>
  <tr>
   <td>18.200.201.81</td>
  </tr>
  <tr>
   <td>34.247.24.245</td>
  </tr>
  <tr>
   <td>35.165.244.220</td>
  </tr>
  <tr>
   <td>44.235.171.179</td>
  </tr>
  <tr>
   <td>52.20.211.99</td>
  </tr>
  <tr>
   <td>52.64.109.86</td>
  </tr>
  <tr>
   <td>54.160.246.246</td>
  </tr>
  <tr>
   <td>54.212.167.17</td>
  </tr>
  <tr>
   <td>54.220.138.65</td>
  </tr>
   <tr>
   <td>54.237.141.197</td>
  </tr>
  </tr>
   <tr>
   <td>130.248.168.16</td>
  </tr>
  </tr>
   <tr>
   <td>130.248.168.17</td>
  </tr>
 </tbody>
</table>
