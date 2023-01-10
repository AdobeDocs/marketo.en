---
unique-page-id: 2949716
description: Send and Track an Email with the Email Add-In for [!DNL Outlook] - Marketo Docs - Product Documentation
title: "Send and Track an Email with the Email Add-In for [!DNL Outlook]"
exl-id: 81c2ce86-1528-48ad-8848-ee5a828f9ff7
---
# Send and Track an Email with the Email Add-In for [!DNL Outlook] {#send-and-track-an-email-with-the-email-add-in-for-outlook}

You can send and track emails with Marketo directly from [!DNL Outlook].

>[!PREREQUISITES]
>
>If you haven't yet, install the [Marketo email add-in for [!DNL Outlook]](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/install-the-marketo-email-add-in-for-outlook-with-a-registration-code.md).

1. Open [!DNL Microsoft Outlook] and create a new email.

   ![](assets/image2014-9-23-16-3a6-3a46.png)

   >[!CAUTION]
   >
   >If you include multiple recipients in the email, all activity will be tracked under the first recipient.

1. Compose your email as you normally would, then click **[!UICONTROL Send and Track]**.

   ![](assets/image2014-9-23-16-3a7-3a1.png)

   >[!NOTE]
   >
   >If you send an email to someone who doesn't exist in your Marketo instance, a Person Record will automatically be created for them. Their last name will always be 'mktUnknown' so that you can easily find them.

   >[!TIP]
   >
   >If you want to use a Marketo template, see [Send and Track from [!DNL Outlook] Using a Template](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md).

1. Take a look at the preview and click **[!UICONTROL Send]**.

   ![](assets/image2014-9-23-16-3a7-3a13.png)

   >[!CAUTION]
   >
   >Anti-spam technology often rejects opens and clicks that happen within 20 seconds of sending the email, so please wait at least that long to open/click while testing.

   In order to see who has received your emails sent through [!DNL Outlook], create a smart list using the "[!UICONTROL Was Sent Sales Email]" filter.

   ![](assets/was-sent-sales-email.png)

It's that easy! Even though this email was sent by a salesperson's [!DNL Outlook], it will be tracked in Marketo.

>[!MORELIKETHIS]
>
>[Log Inbound Mail From Your Leads in Marketo](/help/marketo/product-docs/marketo-sales-insight/using-msi/log-inbound-mail-from-your-leads-in-marketo.md)
