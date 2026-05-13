---
description: Learn how to set up custom object sync from Veeva CRM to Marketo Engage. Enable custom objects in Admin and use them in Smart Lists and triggers.
title: Custom Object Sync
hide: true
exl-id: 68bc14e7-dfc9-4dce-b159-24d734ee3c6f
feature: Veeva CRM
TQID: https://experienceleague.adobe.com/RmyCIMm3TKbcO3nPcqyZqbWZl1dnJ6Au4HsuURJjcKU
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
subfeature_v2:
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
    internal-label: Smart Lists
---
# Custom Object Sync {#custom-object-sync}

Custom Objects created in your [!DNL Veeva] CRM instance can be part of Marketo Engage, too. Here's how to set it up.

>[!NOTE]
>
>**Admin permissions required**

>[!PREREQUISITES]
>
>To use a custom object, it must be associated to a contact or account object in [!DNL Veeva] CRM.

## Enable Custom Object {#enable-custom-object}

1. In Marketo, click **[!UICONTROL Admin]**, then **[!UICONTROL Veeva Objects Sync]**.

   ![](assets/custom-object-sync-1.png)

1. If this is your first Custom Object, click **[!UICONTROL Sync Schema]**.

   ![](assets/custom-object-sync-2.png)

1. Click **[!UICONTROL Disable Global Sync]**.

   ![](assets/custom-object-sync-3.png)

   >[!NOTE]
   >
   >The initial sync of the [!DNL Veeva] custom object schema may take a few minutes.

1. Drag the custom object you wish to sync into the canvas.

   ![](assets/custom-object-sync-4.png)

   >[!NOTE]
   >
   >Custom objects must have unique names. Marketo does not support two different custom objects with the same name.

1. Click **[!UICONTROL Enable Sync]**.

   ![](assets/custom-object-sync-5.png)

1. Click **[!UICONTROL Enable Sync]** again.

   ![](assets/custom-object-sync-6.png)

1. Go back to the **[!UICONTROL Veeva]** tab.

   ![](assets/custom-object-sync-7.png)

1. Click **[!UICONTROL Enable Sync]**.

   ![](assets/custom-object-sync-8.png)

1. To view all of your [!DNL Veeva] custom objects, click **[!UICONTROL Admin]** and  **[!UICONTROL Veeva Objects Sync]**.

   ![](assets/custom-object-sync-9.png)

   >[!NOTE]
   >
   >Marketo only supports custom entities that are linked to standard entities one to two levels deep.

Excellent! You can now use data from this custom object in Smart Campaigns and Smart Lists.

>[!MORELIKETHIS]
>
>* [Syncing Call and Call Key Messages](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
>* [Add/Remove Custom Object Field as Smart List/Trigger Constraints](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"}
