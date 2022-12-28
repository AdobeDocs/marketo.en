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

1. Under **[!UICONTROL Admin]**, click **[!UICONTROL Workspaces & Partitions]**.

   ![](assets/image2014-9-17-10-3a32-3a55.png)

1. Under the **[!UICONTROL Person Partitions]** tab, click on **[!UICONTROL Assignment Rules]**.

   ![](assets/two-6.png)

1. Click **[!UICONTROL Add Choice]** to add conditions for routing people into person partitions.

   ![](assets/three-6.png)

1. Select the field the condition should be built on.  

   ![](assets/four-5.png)

1. Choose the choice operator and enter a value.

   ![](assets/five-1.png)

1. Select the People Partition you want the people that meet the conditions to fall into.

   ![](assets/six-1.png)

   >[!NOTE]
   >
   >You can add as many choices as you like.

1. Click **[!UICONTROL Save]**.

   ![](assets/seven.png)

And there you have it! You have assigned rules for filling your person partitions with people!

>[!NOTE]
>
>The Default Choice will be applied if none of the previous conditions are met.
