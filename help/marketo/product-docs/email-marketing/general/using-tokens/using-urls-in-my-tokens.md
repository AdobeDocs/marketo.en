---
unique-page-id: 11382535
description: "Using URLs in My Tokens - Marketo Docs - Product Documentation"
title: Using URLs in My Tokens
exl-id: 6830c621-4d94-4f31-a608-2f7b2aced88c
feature: Tokens
---
# Using URLs in My Tokens {#using-urls-in-my-tokens}

Follow the steps below to use [!UICONTROL My Tokens] to insert URLs into your emails.

1. Select your program and click **[!UICONTROL My Tokens]**.

   ![](assets/one-4.png)

1. Select the **[!UICONTROL Text]** My Token, drag and drop it onto the canvas.

   ![](assets/two-4.png)

1. Give the token a unique name, enter a URL (without the https://) and click **[!UICONTROL Save]**.

   ![](assets/three-4.png)

   >[!CAUTION]
   >
   >**Using http/https...**
   >
   >* To make sure clicks are tracked in your email, do **not** enter https:// _inside_ the token's value. Use it outside of the token, as shown in Step 7.
   >
   >* We highly recommend not leaving out the http/https. Doing so could cause the [web version](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} of your email to render incorrectly.

1. Select the email in your program.

   ![](assets/four-3.png)

1. Click **[!UICONTROL Edit Draft]**.

   ![](assets/five-3.png)

1. Double-click in the text area to edit.

   ![](assets/six-1.png)

1. Anywhere in your email, type `https://` (without leaving a space after) and click the Insert Token icon.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >You of course also have the option of entering `http://` if your site doesn't use https.

1. Locate your My Token, select it, and click **[!UICONTROL Insert]**.

   ![](assets/eight.png)

1. Highlight the https:// and token, then press Ctrl/Cmd+X (Ctrl = Windows/Cmd = Mac) to cut the text.

   ![](assets/nine.png)

1. Highlight the text you want the link to display and click the [!UICONTROL Insert/Edit Link] icon.

   ![](assets/ten.png)

1. Press Ctrl/Cmd+V to paste the content into the **[!UICONTROL URL]** box and click **[!UICONTROL Insert]**.

   ![](assets/eleven.png)

1. Click **[!UICONTROL Save]**.

   ![](assets/twelve.png)

   And you're done! Your URL will populate after sending, and thanks to you putting https:// in front of the token, it will produce a trackable link.
