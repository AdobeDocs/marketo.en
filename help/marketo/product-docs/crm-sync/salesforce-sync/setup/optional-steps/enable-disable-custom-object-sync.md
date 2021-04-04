---
unique-page-id: 4719297
description: Enable/Disable Custom Object Sync - Marketo Docs - Product Documentation
title: Enable/Disable Custom Object Sync
exl-id: f17d9135-b33e-48c0-9220-131fb437e9e5
---
# Enable/Disable Custom Object Sync {#enable-disable-custom-object-sync}

Custom Objects created in your Salesforce instance can be part of Marketo too. Here's how to set it up.

## Enable/Disable Custom Object Sync {#enable-disable-custom-object-sync-1}

>[!NOTE]
>
>Admin rights required.

1. Click **Admin**.

   ![](assets/one.png)

1. In the Database Management menu, click **Salesforce Objects Sync**.

   ![](assets/two-2.png)

1. If this is your first Custom Object, click **Sync schema.** Otherwise click **Refresh Schema** to ensure you have the latest.

   ![](assets/image2014-12-10-10-3a14-3a44.png)

1. If your global sync is running you will have to disable it by clicking **Disable Global Sync.**

   ![](assets/image2014-12-10-10-3a14-3a54.png)

   >[!NOTE]
   >
   >A sync of the Salesforce custom object schema may take a few minutes.

1. Click **Refresh Schema**.

   ![](assets/image2014-12-10-10-3a15-3a7.png)

1. Select the object you wish to sync and click **Enable Sync**.

   >[!TIP]
   >
   >Marketo can only sync a custom object if it has a direct relationship with the Lead, Contact or Account object in Salesforce.

   ![](assets/image2014-12-10-10-3a15-3a30.png)

1. Click **Enable Sync** again.

   ![](assets/image2014-12-10-10-3a15-3a40.png)

1. Go back to the **Salesforce** tab and click **Enable Sync**.

   ![](assets/image2014-12-10-10-3a15-3a49.png)

## Using Your Custom Objects {#using-your-custom-objects}

>[!NOTE]
>
>You cannot use custom objects in smart campaigns with triggers.

1. In your smart list, drag over the **Has Opportunity** filter and set to **true**.

   ![](assets/image2015-8-26-9-3a39-3a28.png)

1. Then, use filter constraints to narrow the focus.

   ![](assets/image2015-8-24-14-3a18-3a53.png)

   Excellent! You can now use this custom object's data in smart campaigns and smart lists.

>[!MORELIKETHIS]
>
>[Add/Remove Custom Object Field as Smart List/Trigger Constraints](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md)
