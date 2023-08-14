---
unique-page-id: 9438139
description: Add Person to Blocklist - Marketo Docs - Product Documentation
title: Add Person to Blocklist
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
feature: Smart Lists
---
# Add Person to Blocklist {#add-person-to-blocklist}

Adding people to your Blocklist prevents them from receiving your correspondence.

1. [Create a new default program](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) and name it **Add to Blocklist**.

1. Click **New** and select **New Local Asset**.

   ![](assets/add-person-to-blocklist-1.png)

1. Select **Smart List**.

   ![](assets/add-person-to-blocklist-2.png)

1. Name your list and click **Create**.

   ![](assets/add-person-to-blocklist-3.png)

1. Add all the people to your **Smart List** you want added to your Blocklist.

   ![](assets/add-person-to-blocklist-4.png)

   >[!NOTE]
   >
   >People on your Blocklist will not receive operational emails.

1. Go back to your program.

   ![](assets/add-person-to-blocklist-5.png)

1. Click **New** and select **New Smart Campaign**.

   ![](assets/add-person-to-blocklist-6.png)

1. Name the **New Smart Campaign**. Click **Create**.

   ![](assets/add-person-to-blocklist-7.png)

1. Drag and drop **Member of Smart List**.

   ![](assets/add-person-to-blocklist-8.png)

1. Select the smart list you just created.

   ![](assets/add-person-to-blocklist-9.png)

1. Click the **Flow** tab. Drag and drop the **Change Data Value** Flow Action.

   ![](assets/add-person-to-blocklist-10.png)

1. In the **Attribute** drop-down select **Block Listed** and set **New Value** to **true**.

   ![](assets/add-person-to-blocklist-11.png)

1. Click the **Schedule** tab and select **Run Once**.

   ![](assets/add-person-to-blocklist-12.png)

1. Select **Run Now** and click **Run**.

   ![](assets/add-person-to-blocklist-13.png)

1. Click **Run** again.
   
   ![](assets/add-person-to-blocklist-14.png)
   
These people will no longer receive emails.

   >[!TIP]
   >
   >Create a [trigger smart campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) using **Change Data Value** with **Block Listed is true** for all people in the future that have blocklist-able attributes.
