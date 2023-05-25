---
unique-page-id: 2360245
description: Remove Unsubscribe Text From the Admin Email Section - Marketo Docs - Product Documentation
title: Remove Unsubscribe Text From the Admin Email Section
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
---
# Remove Unsubscribe Text From the Admin Email Section {#remove-unsubscribe-text-from-the-admin-email-section}

The only reason why you should ever completely remove the unsubscribe content from the **[!UICONTROL Admin]** > **[!UICONTROL Email]** area is if you're choosing to build the unsubscribe link into the email templates themselves. The text box has validation that does not allow you to save with no content. You can get around this by adding a small HTML comment. The HTML comment will not show up in the email client, because it is rendering the email in HTML and the comments are omitted. Here's how to do it.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-1.png)

1. Click **[!UICONTROL Email]**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-2.png)

1. Select all of the text and press the **[!UICONTROL Delete]** key.

   >[!CAUTION]
   >
   >Before deleting, copy/paste this into a text document as a backup.

1. Type in `<!--This is a comment -->`.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-3.png)

1. Click **[!UICONTROL Save Changes]**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-4.png)

>[!NOTE]
>
>For the **Unsubscribe Text** you have to add a single character. Use a dash or a period.
