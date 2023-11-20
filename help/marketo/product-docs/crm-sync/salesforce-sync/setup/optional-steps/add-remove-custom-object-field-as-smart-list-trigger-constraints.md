---
unique-page-id: 4719300
description: Add/Remove Custom Object Field as Smart List/Trigger Constraints - Marketo Docs - Product Documentation
title: Add/Remove Custom Object Field as Smart List/Trigger Constraints
exl-id: 639e73eb-9a8c-4b10-8e97-892abf5c5db0
feature: Salesforce Integration
---
# Add/Remove Custom Object Field as Smart List/Trigger Constraints {#add-remove-custom-object-field-as-smart-list-trigger-constraints}

Marketo Engage provides fine-grain control over the Salesforce custom object sync. This allows you to select the fields available as constraints in custom object filters and to use them as triggers in Smart Campaigns.

>[!NOTE]
>
>**Admin Permissions Required**

1. Click **[!UICONTROL Admin]**.

   ![](assets/image2014-12-10-13-3a9-3a47.png)

1. Click **[!UICONTROL Admin]** and then **[!UICONTROL Salesforce Objects Sync]**.

   ![](assets/image2015-12-11-15-3a11-3a41.png)

1. **[!UICONTROL Salesforce Objects Sync]** appears in the left column.

   ![](assets/image2015-12-11-15-3a15-3a15.png)

1. Select the object you wish to modify.

   ![](assets/image2014-12-10-13-3a10-3a11.png)

1. Click **[!UICONTROL Edit Visible Fields]**.

   >[!TIP]
   >
   >If the **[!UICONTROL Edit Visible Fields]** button is grayed out, the object is currently in use in a Smart List or Smart Campaign. Remove all associations to proceed.

   ![](assets/image2014-12-10-13-3a10-3a25.png)

1. If your global sync is enabled, click **[!UICONTROL Disable Global Sync]**.

   ![](assets/image2014-12-10-13-3a10-3a36.png)

1. Check the boxes next to the filter/trigger constraints needed and click **[!UICONTROL Save]**.

   ![](assets/image2014-12-10-13-3a10-3a47.png)

   >[!NOTE]
   >
   >All fields are selected by default to be constraints on filters.

1. Click on the **[!UICONTROL Fields]** tab to confirm your changes.

   ![](assets/image2014-12-10-13-3a10-3a56.png)

   >[!NOTE]
   >
   >Don't forget to re-enable your global sync!

Now your Smart Lists and Smart Campaigns have even more power.

>[!MORELIKETHIS]
>
>[Enable/Disable Custom Object Sync](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-custom-object-sync.md){target="_blank"}
