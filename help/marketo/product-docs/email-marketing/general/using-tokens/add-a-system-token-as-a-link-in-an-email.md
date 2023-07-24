---
unique-page-id: 1900573
description: Add a System Token as a Link in an Email - Marketo Docs - Product Documentation
title: Add a System Token as a Link in an Email
exl-id: 9156be24-18ae-44ea-96e5-a6257ff29b46
feature: Tokens
---
# Add a System Token as a Link in an Email {#add-a-system-token-as-a-link-in-an-email}

You can use these system tokens to customize the position of special links in your emails.

The following tokens can be used as links in an email or email template:

* `{{system.forwardToFriendLink}}`
* `{{system.unsubscribeLink}}`
* `{{system.viewAsWebpageLink}}`

>[!NOTE]
>
>These tokens will **not** be clickable unless inside an anchor link. Also, they can **not** be embedded into a My Token.

Here's how to add them to an email:

1. Find and select your email, then click **Edit Draft**.

   ![](assets/one-1.png)

1. Double-click in an editable area.

   ![](assets/two-1.png)

1. Highlight the text you want to convert to a link which will have the token and click the **Insert/Edit Link** button.

   ![](assets/three-1.png)

1. Enter the token in Link URL and click **Insert**.

   ![](assets/four-1.png)

   >[!TIP]
   >
   >Copy/Paste the token you want: **`{{system.forwardToFriendLink}}`** or **`{{system.unsubscribeLink}}`** or **`{{system.viewAsWebpageLink}}`**

1. Click **Save**.

   ![](assets/image2014-9-17-22-3a12-3a17.png)

>[!IMPORTANT]
>
>If you're using this approach to add the “viewAsWebpageLink” system token, you can **not** override it using tokens. Instead, use [Add a View as Web Page Link to an Email](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) approach which allows you to override "viewAsWebPageLink" using tokens.

>[!NOTE]
>
>Don't forget to [approve your email](/help/marketo/product-docs/email-marketing/general/creating-an-email/approve-an-email.md) when done.

Nicely done! Now you know how to add a system token as a link in an email.
