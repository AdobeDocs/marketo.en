---
unique-page-id: 4720433
description: Configure Protocols for Marketo - Marketo Docs - Product Documentation
title: Configure Protocols for Marketo
exl-id: cf2fd4ac-9229-4e52-bb68-5732b44920ef
feature: Getting Started
---
# Configure Protocols for Marketo {#configure-protocols-for-marketo}

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

Your marketing team should have also sent you DKIM information to be added to your DNS resource record (also listed below). Follow the steps to successfully configure DKIM and SPF, then notify your marketing team that this has been updated.

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

## Step 4: Set up MX Records for Your Domain {#step-set-up-mx-records-for-your-domain}

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

