---
unique-page-id: 2360327
description: Assigning Person Partitions with Assignment Rules - Marketo Docs - Product Documentation
title: Assigning Person Partitions with Assignment Rules
exl-id: 6b54dcb7-8da9-466b-b153-099ebcb96424
---
# Assigning Person Partitions with Assignment Rules {#assigning-person-partitions-with-assignment-rules}

>[!NOTE]
>
>**Admin Permissions Required**

>[!PREREQUISITES]
>
>[Create a Person Partition](/help/marketo/product-docs/administration/workspaces-and-person-partitions/create-a-person-partition.md)

When using person partitions, set up assignment rules to route people created from your CRM to their respective partitions.

>[!NOTE]
>
>Only people created in Marketo from your CRM and via the SOAP API will have assignment rules applied to them.

1. Go to the **Admin** area. 

   ![](assets/assigning-person-partitions-with-assignment-rules-1.png)

1. Click **Workspaces & Partitions**.

   ![](assets/assigning-person-partitions-with-assignment-rules-2.png)

1. Under the **People Partitions** tab, click **Assignment Rules**.

   ![](assets/assigning-person-partitions-with-assignment-rules-3.png)

1. Click **Add Choice** to add conditions for routing people into person partitions.

   ![](assets/assigning-person-partitions-with-assignment-rules-4.png)

1. Select the field the condition should be built on.  

   ![](assets/assigning-person-partitions-with-assignment-rules-5.png)

1. Choose the choice operator and enter a value.

   ![](assets/assigning-person-partitions-with-assignment-rules-6.png)

1. Select the People Partition you want the people that meet the conditions to fall into.

   ![](assets/assigning-person-partitions-with-assignment-rules-7.png)

   >[!NOTE]
   >
   >You can add as many choices as you like.

1. Click **Save**.

   ![](assets/assigning-person-partitions-with-assignment-rules-8.png)

And there you have it! You have assigned rules for filling your person partitions with people!

>[!NOTE]
>
>The Default Choice will be applied if none of the previous conditions are met.
