---
unique-page-id: 4720433
description: Configure Protocols for Marketo - Marketo Docs - Product Documentation
title: Configure Protocols for Marketo
---

# Configure Protocols for Marketo {#configure-protocols-for-marketo}

Your marketing group is using Marketo to create branded campaign landing pages and emails. To ensure that those landing pages and emails work, they need a little help from IT. Please set up the following protocols, with the information that your marketing group should have sent you in email.

This article should be shared with the IT department of the company wishing to implement these protocols.

>[!NOTE]
>
>If your IT team restricts web access using an allowlist, ask them to add the following domains (including the asterisk) to allow all Marketo resources and websockets:

* `*.marketo.com`

* `*.marketodesigner.com`

* `*.mktoweb.com`

## Step 1: Create DNS Records for Landing Pages and Email {#step-create-dns-records-for-landing-pages-and-email}

**Tracking Link CNAMEs**

Your marketing team should have sent you two requests for new CNAME records. The first is for landing page URLs, so that the landing pages appear in URLs that reflect your domain and not Marketo (the actual host). The second is for the tracking links that are included in the emails they send from Marketo.

`1` **Add CNAME for Landing Pages**

Add the landing page CNAME they sent you to your DNS record, so that `[YourLandingPageCNAME]` points to the unique Account String that is assigned to your Marketo landing pages. Log in to your domain registrar’s site and enter the landing page CNAME and Account String. Typically, this involves three fields:

* Alias: Enter `[YourLandingPageCNAME]` (provided by marketing)
* Type: CNAME  
* Point to: Enter `[MarketoAccountString].mktoweb.com` (provided by marketing)

`2` **Add CNAME for Email Tracking Links**

Add the email CNAME marketing sent you, so that `[YourEmailCNAME]` points to [MktoTrackingLink], the default tracking link that Marketo assigned, in the format:  
`[YourEmailCNAME].[YourDomain].com` IN CNAME `[MktoTrackingLink]`

For example:  

`pages.abc.com IN CNAME mkto-a0244.com`

`3` **Notify Your Marketing Team**

Notify your marketing team when you’ve completed this process.

## Step 2: Allowlist Marketo IPs {#step-allowlist-marketo-ips}

When your Marketing group uses Marketo to send test emails (a best practice before sending out email blasts), the test emails are sometimes blocked by anti-spam systems that rely on sender IP addresses to verify that the email is valid. To ensure that those test emails arrive, add Marketo to your allowlist.

Add these IP addresses to your corporate allowlist:

199.15.212.0/22  
192.28.144.0/20
192.28.160.0/19  
185.28.196.0/22  
130.248.172.0/24  
130.248.173.0/24  
103.237.104.0/22  
94.236.119.0/26

Some anti-spam systems use the email Return-Path field instead of the IP address for allowisting. In those cases, the best approach is to allowlist ‘&#42;.mktomail.com’, as Marketo uses several mailbox subdomains. Other anti-spam systems allowlist based on the From address. In these situations, be sure to include all the sending (‘From’) domains that your Marketing group uses to communicate with people/leads.

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

1. For DKIM, create DNS Resource Records for each domain we'd like to setup. Below are the Host Records and TXT Values for each domain we'll be signing for:

   `[DKIMDomain1]`: Host Record is `[HostRecord1]` and the TXT Value is `[TXTValue1]`.

   `[DKIMDomain2]`: Host Record is `[HostRecord2]` and the TXT Value is `[TXTValue2]`.

   Copy the HostRecord and TXTValue for each DKIMDomain you've setup after following the [instructions here](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md). Don't forget to verify each domain in Admin > Email > DKIM after your IT staff has completed this step.

## Step 4: Set up MX Records for Your Domain {#step-set-up-mx-records-for-your-domain}

An MX record allows you to receive mail to the domain that you're sending email from to process replies and auto-responders. If you’re sending from your corporate domain, you likely already have this configured. If not, you can usually set it up to map to your corporate domain’s MX record.
