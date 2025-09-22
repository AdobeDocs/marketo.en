---
unique-page-id: 1146958
description: "Send Alert - Marketo Docs - Product Documentation"
title: Send Alert
exl-id: 2016e2e7-0361-4bb2-8740-819e21fbd15b
feature: Smart Campaigns
---
# Send Alert {#send-alert}

Marketo Engage can send an email alert with person information to anyone - the sales owner, a partner, or someone else. Use the "[!UICONTROL Send Alert]" flow step.

![](assets/send-alert-1.png)

1. Find and select the email you want to send.

    ![](assets/send-alert-2.png)

    >[!NOTE]
    >
    >Your email alert must contain all of the header info and be in the **[!UICONTROL Approved]** state.

1. You can click the preview icon to ensure that you've selected the correct email.

    ![](assets/send-alert-3.png)

    >[!NOTE]
    >
    >Be sure to use the "[!UICONTROL Send Alert Info]" token in your email.

1. Select the alert recipient. You can pick [!UICONTROL Sales Owner] or [!UICONTROL Account Owner].

    ![](assets/send-alert-4.png)

1. Optionally, add any other email addresses you want (separated by either a comma or a semicolon).

    ![](assets/send-alert-5.png)

    >[!TIP]
    >
    >In trigger campaigns, you can use tokens in **[!UICONTROL To Other Emails]** such as `{{lead.Territory Owner}}` or `{{my.Alert Recipient}}` as long as the values are valid email addresses. Tokens in **[!UICONTROL To Other Emails]** will not work in a Batch Campaign.

>[!MORELIKETHIS]
>
>[Create an Email](/help/marketo/product-docs/email-marketing/general/creating-an-email/create-an-email.md){target="_blank"}
