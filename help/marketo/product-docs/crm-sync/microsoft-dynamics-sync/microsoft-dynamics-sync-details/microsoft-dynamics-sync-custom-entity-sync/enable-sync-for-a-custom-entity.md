---
unique-page-id: 2953384
description: Enable Sync for a Custom Entity - Marketo Docs - Product Documentation
title: Enable Sync for a Custom Entity
exl-id: 4b075bf3-f10b-4725-8c8e-a6ecee63d756
---
# Enable Sync for a Custom Entity {#enable-sync-for-a-custom-entity}

If you need custom entity data from Dynamics to be available in Marketo, here's how to enable the sync for it:

>[!NOTE]
>
>**Admin Permissions Required**

1. Go to the **Admin** section.

   ![](assets/image2014-10-20-14-3a32-3a16.png)

1. Select **Microsoft Dynamics** and click **Disable Sync**.

   You must disable the global sync temporarily in order to enable or disable a custom entity.

   ![](assets/image2015-11-10-9-3a0-3a6.png)

1. Under Database Management, click the **Dynamics Entities Sync** link.

   ![](assets/image2015-11-10-9-3a6-3a55.png)

1. Click the **Sync schema** link.

   ![](assets/image2015-11-10-9-3a41-3a37.png)

1. Select the entity you want to sync and click **Enable Sync**.

   ![](assets/image2015-11-10-9-3a44-3a35.png)

1. Select the fields you want to sync or use as [constraints](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md) and/or triggers in smart lists. When done, click **Enable Sync**.

   ![](assets/image2014-10-20-14-3a32-3a55.png)

   >[!NOTE]
   >
   >During the sync process, you may notice that the "Dynamic Entities Sync" item disappears from the navigational tree. This is expected behavior, and it will reappear after the sync is complete.

1. The entity now has a green checkmark on it.

   ![](assets/image2014-10-20-14-3a33-3a4.png)

1. Don't forget to re-enable the global sync!

   ![](assets/image2015-11-10-9-3a48-3a35.png)

Oh yeah! Powerful stuff.
