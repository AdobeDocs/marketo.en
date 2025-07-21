---
unique-page-id: 2949413
description: Add a Constraint to a Smart List Filter - Marketo Docs - Product Documentation
title: Add a Constraint to a Smart List Filter
exl-id: 5345019c-55e7-4afd-b583-90f1a687a71c
feature: Smart Lists
---
# Add a Constraint to a Smart List Filter {#add-a-constraint-to-a-smart-list-filter}

When creating a Smart List, some filters have advanced options called "constraints." These are extra conditions that you can add to filters and triggers to help narrow your search even further.

In this example, let's add some constraints to a **[Data Value Changed](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md){target="_blank"}** filter to find people that had a Status change from MQL to SQL.

>[!PREREQUISITES]
>
>* [Create a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}
>* [Use the "Data Value Changed" Filter in a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-the-data-value-changed-filter-in-a-smart-list.md){target="_blank"}

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/add-a-constraint-to-a-smart-list-filter-1.png)

1. Select the Smart List with a filter you'll be adding a constraint to and click the **[!UICONTROL Smart List]** tab.

   ![](assets/add-a-constraint-to-a-smart-list-filter-2.png)

1. Under **[!UICONTROL Add Constraint]**, select **[!UICONTROL Previous Value]**.

   ![](assets/add-a-constraint-to-a-smart-list-filter-3.png)

1. Enter the **[!UICONTROL Previous Value]**. In this example, we're using MQL.

   ![](assets/add-a-constraint-to-a-smart-list-filter-4.png)

1. Under **[!UICONTROL Add Constraint]**, select **[!UICONTROL New Value]**.

   ![](assets/add-a-constraint-to-a-smart-list-filter-5.png)

1. Enter the new value. In this example, we're using SQL.

   ![](assets/add-a-constraint-to-a-smart-list-filter-6.png)

1. Nicely done! Click the **[!UICONTROL People]** tab to see all people who had a Status change from "MQL" to "SQL" in the past 30 days.
