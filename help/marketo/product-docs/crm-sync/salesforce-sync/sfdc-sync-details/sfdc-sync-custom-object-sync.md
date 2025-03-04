---
unique-page-id: 2953471
description: SFDC Sync - Custom Object Sync - Marketo Docs - Product Documentation
title: SFDC Sync - Custom Object Sync
exl-id: e491e0bc-04a9-4e78-97c3-a25b945d546a
feature: Salesforce Integration
---
# SFDC Sync: Custom Object Sync {#sfdc-sync-custom-object-sync}

Custom Objects created in your Salesforce instance can be part of Marketo Engage, too. Here's how to set it up.

>[!NOTE]
>
>**Admin Permissions Required**

>[!PREREQUISITES]
>
>To use a custom object, it must be associated to a [lead](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync.md){target="_blank"}, [contact](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md){target="_blank"}, or [account](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md){target="_blank"} object in Salesforce.

>[!IMPORTANT]
>
>The Marketo Sync User needs read access to the custom object to list it and perform a sync on it.

## Enable Custom Object  {#enable-custom-object}

1. Click **[!UICONTROL Admin]** and the **[!UICONTROL Salesforce Objects Sync]** link.

   ![](assets/image2015-11-19-10-3a28-3a5.png).

1. If this is your first Custom Object, click **[!UICONTROL Sync Schema]**.

   ![](assets/rtaimage-2.png)

1. Click **[!UICONTROL Disable Global Sync]**.

   ![](assets/image2015-4-22-10-3a45-3a0.png)

   >[!NOTE]
   >
   >An initial sync of the Salesforce custom object schema may take a few minutes.

   ![](assets/image2015-4-22-10-3a45-3a18.png)

1. Drag the custom object you wish to sync into the canvas.

   ![](assets/image2015-4-22-10-3a45-3a30.png)

   >[!NOTE]
   >
   >Custom objects must have unique names. Marketo does not support two different custom objects with the same name.

1. Click **[!UICONTROL Enable Sync]**.

   ![](assets/image2015-4-22-10-3a45-3a50.png)

1. Click **[!UICONTROL Enable Sync]** again.

   ![](assets/image2015-4-22-10-3a46-3a10.png)

   >[!NOTE]
   >
   >Don't forget to re-enable your global sync!

1. Go back to the **Salesforce** tab.

   ![](assets/image2015-4-22-10-3a46-3a25.png)

1. Click **[!UICONTROL Enable Sync]**.

   ![](assets/image2015-4-22-10-3a50-3a26.png)

1. To view all of your Salesforce custom objects, click **[!UICONTROL Admin]** and the **[!UICONTROL Salesforce Objects Sync]** link (same as step 1 above).

   ![](assets/image2016-6-23-9-3a28-3a23.png)

   >[!NOTE]
   >
   >* Marketo only supports custom entities that are linked to standard entities one or two levels deep.
   >
   >* The custom object tree may show the same object more than once, because of its direct connections with one of the main objects (e.g., leads, contacts, or accounts or indirect connections through an intermediary objects). In such cases, choose the object that is nearest to the main object and choose only one. Choosing the same object multiple times may hamper the sync of that custom object.

### What's Next: {#whats-next}

   [Add/Remove Custom Object Field as Smart List/Trigger Constraints](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"}

Excellent! You can now use data from this custom object in smart campaigns and smart lists.
