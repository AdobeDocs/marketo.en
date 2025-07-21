---
unique-page-id: 11372054
description: Edit the Text Version of an Email - Marketo Docs - Product Documentation
title: Edit the Text Version of an Email
exl-id: 6973ccdd-6ae1-4051-ab7e-ff7da40baf97
feature: Email Editor
---
# Edit the Text Version of an Email {#edit-the-text-version-of-an-email}

When you create an email, you may want its text version to be worded differently than the HTML version. By default, Marketo automatically copies the text content of any rich text element that's in your email over to the Text version. Here's how to edit it.

>[!NOTE]
>
>This is not an article on creating a text-only email. For information on that, see [Create a Text-Only Email](/help/marketo/product-docs/email-marketing/general/creating-an-email/create-a-text-only-email.md).

1. In the email editor, click the **[!UICONTROL Text]** tab at the bottom of the email.

   ![](assets/one-5.png)

1. Uncheck **[!UICONTROL Automatically copy from HTML]** to make changes.

   ![](assets/two-5.png)

1. Double-click the text area.

   ![](assets/three-4.png)

1. Make your edits. After you're done simply close the editor, or go back to the HTML version. The changes will auto-save.

   ![](assets/four-4.png)

   If you only have static content, text will be editable in one big block (seen in Step 3). If you have dynamic content, the text will be broken up into different editable sections, as seen below.

   ![](assets/five-3.png)

>[!CAUTION]
>
>Selecting **Copy from HTML**, or reselecting **Automatically copy from HTML** in emails that contain dynamic content will set the Reviewed flag to _true_ for all segments (producing the green check mark that indicates it's been reviewed) in both the HTML and Text versions of the email. If you perform either action above, be sure to double-check your content before sending. 
