---
unique-page-id: 1900579
description: Disable Tracking for an Email Link - Marketo Docs - Product Documentation
title: Disable Tracking for an Email Link
exl-id: 841ef605-1664-4457-bc83-50bbe5d44853
feature: Email Editor
---
# Disable Tracking for an Email Link {#disable-tracking-for-an-email-link}

Sometimes you don't want to enable the **Marketo Tracking URL** on a link in an email. This is useful when the destination page does not support URL parameters and may result in a broken link. 

Also, if an email was sent over 365 days ago **and** no one has clicked on any of its links in the last 180 days, Marketo Engage prunes the route to the URL from our database, which will cause the link to break. So, if you need the link to be permanent, you should disable tracking.

1. Select your email and click **Edit Draft**.

   ![](assets/one-7.png)

1. Double-click the editable section that contains the link.

   ![](assets/two-6.png)

1. Click the link in question, then click the **Insert/Edit Link** button.

   ![](assets/three-6.png)

1. In the Edit Link pop-up, uncheck the **Track Link** checkbox.

   ![](assets/four-4.png)

1. You'll notice the **Include mkt_tok box** disappears. Click **Apply**.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >Unchecking just **Include mkt_tok** will still allow the link to be tracked, but after redirect, the destination URL will not include the mkt_tok query string parameter. This parameter is used by Marketo Landing Pages and Munchkin to ensure proper tracking of person activities (like when a person unsubscribes from an email). You should avoid using this feature unless you're seeing weird behavior on your website due to the parameter being present.

1. Click **Save**.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!CAUTION]
   >
   >If you want to disable click-tracking for a link in an Email Template, or the [text version](/help/marketo/product-docs/email-marketing/general/creating-an-email/edit-the-text-version-of-an-email.md){target="_blank"} of an email, add the `mktNoTrack` at the *beginning* of the string, not the end, like in this example: `<a class="mktNoTrack" href="https://www.mywebsite.com">This link does not have tracking</a>`. Otherwise, it could cause the link to disappear. If you need help implementing the above code, please consult your web developer.
