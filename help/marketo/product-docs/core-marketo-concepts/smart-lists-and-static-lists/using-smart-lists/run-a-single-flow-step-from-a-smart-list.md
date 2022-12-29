---
unique-page-id: 557322
description: Run a Single Flow Step from a Smart List - Marketo Docs - Product Documentation
title: Run a Single Flow Step from a Smart List
exl-id: 1ac5795b-1906-4f94-bd0a-570d55c9357b
---
# Run a Single Flow Step from a Smart List {#run-a-single-flow-step-from-a-smart-list}

If you want to run a one-time only flow step, you can use a single flow step within a smart list instead of creating an entire smart campaign.

>[!PREREQUISITES]
>
>[Create a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/login-marketing-activities-1.png)

1. Select a list or smart list with people in it, then go to the **[!UICONTROL People]** tab.

   ![](assets/smartlistpeopletab-hands.png)

   >[!TIP]
   >
   >Both static lists as well as smart lists have this functionality.

1. Click **[!UICONTROL Select All]**. You can also use **Ctrl/Cmd** and click to select a few records manually.

   ![](assets/smartlist-selectallhand.png)

   >[!NOTE]
   >
   >If the results span over multiple pages, clicking **[!UICONTROL Select All]** will select all people across all pages.

1. Under **Person** **Actions**, select the flow step of your choice. In this example we will use [Change Data Value](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md).

   ![](assets/personactions-hands.png)

1. Find and select an **[!UICONTROL Attribute]**. In this example we will take all people who have state "California" and change it to "CA."

   ![](assets/runaction-hands.png)

1. Enter a new value. Click **[!UICONTROL Run Now]**.

   ![](assets/runactionnewvalue-hands.png)

1. If you're changing data values for a large number of people, you may need to confirm the change by typing in the number. Click **[!UICONTROL Go For It]**.

   ![](assets/changedatavalue.jpg)

Awesome work! You will see the status of the single flow step in the top right hand corner.

![](assets/completesingleflowaction.jpg)

When it's finished, refresh the list and you will see the updated info.
