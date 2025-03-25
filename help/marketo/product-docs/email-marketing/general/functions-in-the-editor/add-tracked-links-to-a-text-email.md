---
unique-page-id: 1900589
description: Add Tracked Links to a Text Email - Marketo Docs - Product Documentation
title: Add Tracked Links to a Text Email
exl-id: 10b4e029-de23-4054-83f7-b68fea68c838
feature: Email Editor
---
# Add Tracked Links to a Text Email {#add-tracked-links-to-a-text-email}

>[!PREREQUISITES]
>
>* [Create a Text Only Email](/help/marketo/product-docs/email-marketing/general/creating-an-email/create-a-text-only-email.md)
>* [Edit Elements in an Email](/help/marketo/product-docs/email-marketing/general/email-editor-2/edit-elements-in-an-email.md)

Text email links can be tracked in Marketo. Let's see how it works.

1. Select your email and click **Edit Draft**.

![](assets/one-9.png)

1. Double-click the editable area you want to add the link to.

   ![](assets/two-8.png)

1. Enter the URL with double brackets, like this: `[[www.domain.com/path/page.html]]`.

   ![](assets/three-8.png)

   >[!CAUTION]
   >
   >If an email was sent over 365 days ago **and** no one has clicked on any of its links in the last 180 days, Marketo Engage prunes the route to the URL from our database, which will cause the link to break. If you need the link to be permanent, do not use tracking. 

1. Close out of the editor, and don't forget to approve the draft.

   ![](assets/four-6.png)

>[!NOTE]
>
>The mktNoTok class functionality does not work with trackable links in text emails. Only for HTML emails.
