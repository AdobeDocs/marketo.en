---
unique-page-id: 2949716
description: Send and Track an Email with the Email Add-In for Outlook - Marketo Docs - Product Documentation
title: Send and Track an Email with the Email Add-In for Outlook
exl-id: 81c2ce86-1528-48ad-8848-ee5a828f9ff7
feature: Marketo Sales Insights
---
# Send and Track an Email with the Email Add-In for Outlook {#send-and-track-an-email-with-the-email-add-in-for-outlook}

You can send and track emails with Marketo directly from Outlook.

>[!PREREQUISITES]
>
>If you haven't yet, install the [Marketo email add-in for Outlook](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/install-the-marketo-email-add-in-for-outlook-with-a-registration-code.md).

>[!NOTE]
>
>Sales Insight Actions capabilities, including Send Sales Email, Add to Sales Campaign, and Tasks, are not available in the Sales Insight email plugins for Gmail and Outlook. At this time, users only have the ability to send a trackable email with or without a Marketo email template from their email client when using the Sales Insight email plugins.

1. Open Microsoft Outlook and create a new email.

   ![](assets/image2014-9-23-16-3a6-3a46.png)

   >[!CAUTION]
   >
   >If you include multiple recipients in the email, all activity will be tracked under the first recipient.

1. Compose your email as you normally would, then click **Send and Track**.

   ![](assets/image2014-9-23-16-3a7-3a1.png)

   >[!NOTE]
   >
   >If you send an email to someone who doesn't exist in your Marketo instance, a Person Record will automatically be created for them. Their last name will always be 'mktUnknown' so that you can easily find them.

   >[!TIP]
   >
   >If you want to use a Marketo template, see [Send and Track from Outlook Using a Template](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md).

1. Take a look at the preview and click **Send**.

   ![](assets/image2014-9-23-16-3a7-3a13.png)

   >[!CAUTION]
   >
   >Anti-spam technology often rejects opens and clicks that happen within 20 seconds of sending the email, so please wait at least that long to open/click while testing.

   In order to see who has received your emails sent through Outlook, create a smart list using the "Was Sent Sales Email" filter.

   ![](assets/was-sent-sales-email.png)

It's that easy! Even though this email was sent by a salesperson's Outlook, it will be tracked in Marketo.

>[!MORELIKETHIS]
>
>[Log Inbound Mail From Your Leads in Marketo](/help/marketo/product-docs/marketo-sales-insight/using-msi/log-inbound-mail-from-your-leads-in-marketo.md)
