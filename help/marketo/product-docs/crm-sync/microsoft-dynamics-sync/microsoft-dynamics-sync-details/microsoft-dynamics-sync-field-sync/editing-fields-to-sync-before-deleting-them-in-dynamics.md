---
description: Editing Fields to Sync Before Deleting Them in Dynamics - Marketo Docs - Product Documentation
title: Editing Fields to Sync Before Deleting Them in Dynamics
---

# Editing Fields to Sync Before Deleting Them in Dynamics {#editing-fields-to-sync-before-deleting-them-in-dynamics}

Sometimes you may want to delete fields in Dynamics. Marketo keeps the field list as a reference to base the sync on. If a field is deleted in Dynamics while the sync is on, the sync might encounter errors. Before deleting any fields, follow the steps below.

1. In Marketo, click **Admin**.

   ![](assets/sync-before-deleting-them-in-dynamics-1.png)

1. Under Integration, click **Microsoft Dynamics**.

   ![](assets/sync-before-deleting-them-in-dynamics-2.png)

1. Click **Disable Sync**.

   ![](assets/sync-before-deleting-them-in-dynamics-3.png)

1. In a new tab in your browser, log in to Dynamics and delete your desired fields.

1. Back in Marketo, under Microsoft Dynamics, click **Edit** next to "Step 2: Select Fields to Sync."

   ![](assets/sync-before-deleting-them-in-dynamics-4.png)

1. Review the fields and click **Save**.

   ![](assets/sync-before-deleting-them-in-dynamics-5.png)

>[!CAUTION]
>
>Clicking **Save** is required to save the updated schema for the sync, even if no changes were made.

>[!NOTE]
>
>If the Sync is not stopped before deleting a field in Dynamics, the sync may encounter errors. If it does, the sync will stop. Before resuming, the Marketo Admin would need to review “Select Fields to Sync” (discussed above) and click **Save** in order for the sync to accept the schema changes.

Remember to enable the sync after the changes are saved!
