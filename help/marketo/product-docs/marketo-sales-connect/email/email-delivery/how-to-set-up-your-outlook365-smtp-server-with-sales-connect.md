---
unique-page-id: 14352600
description: How to Set up Your Outlook365 SMTP Server with Sales Connect - Marketo Docs - Product Documentation
title: How to Set up Your Outlook365 SMTP Server with Sales Connect
---

# How to Set up Your Outlook365 SMTP Server with Sales Connect {#how-to-set-up-your-outlook-smtp-server-with-sales-connect}

How to Set up Your Outlook365 SMTP Server with Sales Connect - Marketo Docs - Product Documentation

>[!NOTE]
>
>If your organization uses Outlook and you're trying to set up an email delivery channel with Marketo Sales Connect, we recommend connecting to your Exchange server [using our email connection feature](http://docs.marketo.com/x/Z4AOAQ).

In order to set up a custom [SMTP](http://docs.marketo.com/x/zYTS) server as an alternate delivery channel, ToutApp does require that you utilize some form of authentication for security purposes. You can set up any SMTP server on your [SMTP configuration page](http://toutapp.com/next#settings/email-servers/smtp/configure). To set up an Office365 SMTP server, Microsoft recommends the following configuration:    
**SMTP Server**: smtp.office365.com  
**Server Port**: Port 587 - Secured  
**Authentication Method**: Login (SSL/TLS)  
**Username or Login**: your Office365 email address  
**Password**: your Office365 email password  
**Your Domain**: your company's domain

If you're still having issues setting up your SMTP server, partner with your Exchange Admin to ensure the right credentials are being used.

>[!NOTE]
>
>When sending through your Office365 SMTP, Microsoft imposes a `limit of 30 messages sent per minute`, and a limit of 10,000 recipients per day. Additionally, `each member` of your team who wishes to send emails through their Office365 SMTP server will need to set this up with their own email address and password in their Sales Connect settings. Checking the box for the setting " `Make this deliverability channel to all my team members` `" will not work` for this configuration, in accordance with Microsoft's Office365 account policies.

