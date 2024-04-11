---
unique-page-id: 2953384
description: Enable Sync for a Custom Entity - Marketo Docs - Product Documentation
title: Enable Sync for a Custom Entity
exl-id: 4b075bf3-f10b-4725-8c8e-a6ecee63d756
feature: Microsoft Dynamics
---
# Enable Sync for a Custom Entity {#enable-sync-for-a-custom-entity}

If you need custom entity data from Dynamics to be available in Marketo Engage, here's how to enable the sync for it.

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>* When you enable the sync for a custom entity, Marketo performs an initial sync to bring in all the data for the Custom Object.
>* Marketing List and Marketing List Members are _not supported_ at this time.

>[!IMPORTANT]
>
>The Marketo Sync User needs read access to the custom object to list it and perform a sync on it.

1. Go to the **[!UICONTROL Admin]** section.

   ![](assets/enable-sync-for-a-custom-entity-1.png)

1. Select **[!UICONTROL Microsoft Dynamics]** and click **[!UICONTROL Disable Sync]**.

   ![](assets/enable-sync-for-a-custom-entity-2.png)

   >[!NOTE]
   >
   >You must disable the global sync temporarily in order to enable or disable a custom entity.

1. Under Database Management, click **[!UICONTROL Dynamics Entities Sync]**.

   ![](assets/enable-sync-for-a-custom-entity-3.png)

1. Click **[!UICONTROL Sync schema]**.

   ![](assets/enable-sync-for-a-custom-entity-4.png)

1. Select the entity you want to sync and click **[!UICONTROL Enable Sync]**.

   ![](assets/enable-sync-for-a-custom-entity-5.png)

1. Select the fields you want to sync or use as [constraints](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md) and/or triggers (for records added, _not_ updated) in Smart Lists. When done, click **[!UICONTROL Enable Sync]**.

   ![](assets/enable-sync-for-a-custom-entity-6.png)

   >[!NOTE]
   >
   >During the sync process, you may notice that the "[!UICONTROL Dynamic Entities Sync]" item disappears from the navigational tree. This is expected behavior, and it will reappear after the sync is complete.

1. The entity now has a green checkmark.

   ![](assets/enable-sync-for-a-custom-entity-7.png)

1. Don't forget to re-enable the global sync!

   ![](assets/enable-sync-for-a-custom-entity-8.png)
