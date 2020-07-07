---
unique-page-id: 4719308
description: Add an Existing Salesforce Field to the Marketo Sync - Marketo Docs - Product Documentation
title: Add an Existing Salesforce Field to the Marketo Sync
---

# Add an Existing Salesforce Field to the Marketo Sync {#add-an-existing-salesforce-field-to-the-marketo-sync}

Add an Existing Salesforce Field to the Marketo Sync - Marketo Docs - Product Documentation

>[!NOTE]
>
>**Admin Permissions Required**

Usually, new custom fields in Salesforce sync over to Marketo automatically. If not, the fields may not be visible to the Marketo Sync user. Here's how you can fix this.

1. Click your name and then select **Setup**.

   ![](assets/image2015-6-30-14-3a20-3a6.png)

1. Enter **profile** in the left search bar and click **Profiles** under **Manage Users**.

   ![](assets/image2015-6-30-14-3a20-3a52.png)

1. Click the sync user's profile.

   ![](assets/image2015-6-30-14-3a23-3a41.png)

1. Under the **Field-Level Security** section, click **View** next to the object that contains the field.

   ![](assets/image2015-6-30-14-3a23-3a59.png)

1. Click **Edit**.

   ![](assets/image2015-6-30-14-3a24-3a28.png)

1. Check the **Visible** checkbox for the field you want to add to the sync and click **Save**.

   ![](assets/image2015-6-30-14-3a24-3a49.png)

   Sweet! On the next sync cycle, Marketo will see the field and start the magic.

   >[!NOTE]
   >
   >&nbsp;If the field already has values in Salesforce, those values don't sync over to Marketo until the next record update.

