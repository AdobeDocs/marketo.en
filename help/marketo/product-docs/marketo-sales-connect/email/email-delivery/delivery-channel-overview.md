---
unique-page-id: 14352407
description: Delivery Channel Overview - Marketo Docs - Product Documentation
title: Delivery Channel Overview
---

# Delivery Channel Overview {#delivery-channel-overview}

We’ll break down the three different channels you can leverage, how to select them, when to pick one over another, and the nuances around them.

>[!NOTE]
>
>This information is only relevant if you are sending your emails from the [web application](http://toutapp.com/login). If you are using Sales Connect in Gmail or Outlook, your emails will be delivered via those email servers.

## MSC Email Servers (default) {#msc-email-servers-default}

By default, this method will be selected for the delivery of your emails. MSC email servers are a great option for users who don’t use Gmail or Outlook. Additionally, because they are our servers, we have the ability to take any error messages regarding bounces or failed deliveries and surface them up to you in the “Failed Deliveries” section of the Conversations tab.   
  
Another benefit of using the MSC servers is, when using an [Email Identity](https://help.toutapp.com/hc/en-us/articles/215371427), the recipient will see the email address of the identity you've created.

When using MSC servers, your recipients may see a "via toutapp.com" tag. This is their&nbsp;email client letting them know the email was sent using Sales Connect.

For more details, check out this [Gmail Help article](https://support.google.com/mail/answer/1311182?hl=en).

>[!NOTE]
>
>Our MSC servers do not have a [DMARC record](https://dmarc.org/) that is made available. They cannot be whitelisted on your own servers.

## Gmail&nbsp;Server {#gmail-server}

If your company's email provider is Gmail, you can leverage your existing account to send your Sales Connect emails. This is a great option if you want to avoid the "via toutapp.com" information, and if you'd prefer to rely on the reputation of your company's domain and deliverability. An additional benefit of using a Gmail server is that anything you send out of the web application will automatically be added to your Gmail sent folder.

We can only properly connect with a single Gmail account (one email address) that will deliver your Sales Connect emails. This means if you use multiple Email identities, only the address of the account that we're connected to will appear when looking at the details.

In the web application, your identity will appear as you have created it (above). However, sending through Gmail servers will show the address of the connected account.

>[!NOTE]
>
>Since Sales Connect does not directly manage your Gmail servers, we do not record bounced email events in the web application.

## Custom SMTP Server&nbsp; {#custom-smtp-server}

Pay for your own server? Use a Microsoft Exchange environment? This is an option for you. Check out [these instructions](http://docs.marketo.com/x/zYTS) on getting set up. Like Gmail Servers,&nbsp;since Sales Connect does not directly manage your server, we do not record bounced email events in the web application.

