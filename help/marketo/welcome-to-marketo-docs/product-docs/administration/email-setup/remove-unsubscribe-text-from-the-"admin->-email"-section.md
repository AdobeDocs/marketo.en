---
unique-page-id: 2360245
description: Remove Unsubscribe Text From the "Admin -> Email" Section - Marketo Docs - Product Documentation
title: Remove Unsubscribe Text From the "Admin -> Email" Section
---

# Remove Unsubscribe Text From the "Admin -> Email" Section {#remove-unsubscribe-text-from-the-admin-email-section}

Remove Unsubscribe Text From the "Admin -> Email" Section - Marketo Docs - Product Documentation

`The only reason why you should ever completely remove the unsubscribe content from the “Admin > Email” area is if you're choosing to build the unsubscribe link into the email templates themselves.` The text box has validation that does not allow you to save with no content. You can get around this by adding a small HTML comment. The HTML comment will not show up in the email client, because it is rendering the email in HTML and the comments are omitted. Here's how to do it.

1. Go to **Admin** and click **Email**.

   ![](assets/image2016-8-26-13-3a57-3a9.png)

1. Select all of the text and press the **Delete **key.

   >[!CAUTION]
   >
   >Before deleting, copy/paste this into a text document as a backup.

1. Type in **<!--This is a comment -->**.

   ![](assets/image2016-8-26-13-3a53-3a15.png)

1. Click **Save Changes**.

   ![](assets/image2016-8-26-13-3a59-3a40.png)

>[!NOTE]
>
>For the **Unsubscribe Text **you have to add a single character. Use a dash or a period.

