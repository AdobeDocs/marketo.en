---
unique-page-id: 9438139
description: Add Person to Blocklist - Marketo Docs - Product Documentation
title: Add Person to Blocklist
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
feature: Smart Lists
---
# Add Person to Blocklist {#add-person-to-blocklist}

Adding people to your Blocklist prevents them from receiving your correspondence.

>[!NOTE]
>
>Marketo is in the process of changing terms such as Blacklist and Whitelist to Blocklist and Allowlist in our product. During this update, you may see the old terms in our UI and documentation screenshots, and the new terms in our documentation text. We apologize for any confusion.

1. [Create a new default program](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) and name it **Add to Blocklist**.

1. Click **New** and select **New Local Asset**.

   ![](assets/image2015-8-14-11-3a0-3a46.png)

1. Name your list and click **Create**.

   ![](assets/image2015-8-14-11-3a2-3a26.png)

1. Add all the people to your **Smart List** you want added to your Blocklist.

   >[!NOTE]
   >
   >People on your Blocklist will not receive operational emails.

   ![](assets/three-6.png)

1. Click **New** and select **New Smart Campaign**.

   ![](assets/image2015-8-14-11-3a12-3a35.png)

1. Name the **New Smart Campaign**. Click **Create**.

   ![](assets/image2015-8-14-11-3a13-3a36.png)

1. Drag and drop **Member of Smart List**.

   ![](assets/image2015-8-14-11-3a16-3a34.png)

1. Select the smart list you just created.

   ![](assets/image2015-8-14-11-3a17-3a5.png)

1. Drag and drop **Change Data Value**.

   ![](assets/image2015-8-14-11-3a18-3a41.png)

1. For the **Flow**, enter **Block Listed** for the **Attribute** and set **New Value** to **true**.

   ![](assets/image2015-8-14-11-3a21-3a1.png)

1. On the **Schedule** tab, select **Run Once**.

   ![](assets/ten.png)

1. Select **Run now** and click **Run**.

   ![](assets/image2015-8-14-11-3a24-3a50.png)

   YAY! These people will no longer receive emails.

   >[!TIP]
   >
   >Create a [trigger smart campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) using **Change Data Value** with **Block Listed is true** for all people in the future that have blocklist-able attributes.
