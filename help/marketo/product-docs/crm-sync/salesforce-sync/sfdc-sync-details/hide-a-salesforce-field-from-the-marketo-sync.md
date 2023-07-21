---
unique-page-id: 4719306
description: Hide a Salesforce Field From the Marketo Sync - Marketo Docs - Product Documentation
title: Hide a Salesforce Field From the Marketo Sync
exl-id: 5d7229f0-43b0-4232-93ed-a9ca52ace401
feature: Salesforce Integration
---
# Hide a Salesforce Field From the Marketo Sync {#hide-a-salesforce-field-from-the-marketo-sync}

>[!NOTE]
>
>**Admin Permissions Required**

Not every field in Salesforce is useful for Marketing. You can optimize the sync performance by including only fields that you need. Here's how you can hide a field from Marketo.

1. Click your name menu and select **Setup**.

   ![](assets/image2015-6-30-15-3a11-3a23.png)

1. Enter **profiles** in the search bar and click **Profiles** under **Manage Users**.

   ![](assets/image2015-6-30-15-3a12-3a46.png)

1. Click the sync user's profile.

   ![](assets/image2015-6-30-15-3a17-3a38.png)

1. Under the **Field-Level Security** section, click **View** next the object that contains the target field.

   ![](assets/image2015-6-30-15-3a24-3a32.png)

1. Click **Edit**.

   ![](assets/image2015-6-30-15-3a25-3a42.png)

1. Uncheck the **Visible** checkbox next the field you'd like to hide. Click **Save**.

   ![](assets/image2015-6-30-15-3a27-3a16.png)

   >[!NOTE]
   >
   >If the field you hide in Salesforce has already been synced with Marketo, you'll need to hide it in Marketo, too if you don't want to use it.

   That's it! You will no longer see this field in Marketo after the next sync is finished.

   >[!MORELIKETHIS]
   >
   >[Hide and Unhide a Field](/help/marketo/product-docs/administration/field-management/hide-and-unhide-a-field.md)
