---
unique-page-id: 1146958
description: Send Alert - Marketo Docs - Product Documentation
title: Send Alert
---

# Send Alert {#send-alert}

## Overview {#overview}

Marketo can send an email alert with person information to anyone - the sales owner, a partner, or someone else. Use the **Send Alert** flow step.

![](assets/one-1.png)

## Usage {#usage}

1. Find and select the email you want to send.

    ![](assets/two-1.png)

    >[!NOTE]
    >
    >Your email alert must contain all of the header info and be in the **Approved** state.

1. You can click the preview icon to ensure that you've selected the correct email.

    ![](assets/three-1.png)

    >[!NOTE]
    >
    >Be sure to use the **Send Alert Info** token in your email.

1. Select the alert recipient. You can pick Sales Owner or Account Owner.

    ![](assets/four-2.png)

1. Optionally, add any other email addresses you want (separated by either a comma or a semicolon).

    ![](assets/five.png)

    >[!TIP]
    >
    >In trigger campaigns, you can use tokens in **To Other Emails** such as `{{lead.Territory Owner}}` or `{{my.Alert Recipient}}` as long as the values are valid email addresses. Tokens in **To Other Emails** will not work in a batch campaign.

That's it! Now you know how to use the **Send Alert** flow step.

>[!MORELIKETHIS]
>
>[Create an Email](/help/marketo/product-docs/email-marketing/general/creating-an-email/create-an-email.md)
