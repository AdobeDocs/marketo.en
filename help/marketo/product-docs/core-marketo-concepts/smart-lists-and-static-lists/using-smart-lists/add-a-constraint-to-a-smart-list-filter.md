---
unique-page-id: 2949413
description: Add a Constraint to a Smart List Filter - Marketo Docs - Product Documentation
title: Add a Constraint to a Smart List Filter
---

# Add a Constraint to a Smart List Filter {#add-a-constraint-to-a-smart-list-filter}

When creating smart lists, some filters have advanced options called *constraints. *These are extra conditions that you can add to filters and triggers to help narrow your search even further.

In this example, let's add some constraints to a ** [Data Value Changed](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)** filter to find people that had a Status change from MQL to SQL.

>[!PREREQUISITES]
>
>* [Create a Smart List](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)
>* [Use the "Data Value Changed" Filter in a Smart List](use-the-data-value-changed-filter-in-a-smart-list.md)
>

1. Go to **Marketing Activities**.

   ![](assets/ma-1.png)

1. Select the smart list with a filter you'll be adding a constraint to, and click the **Smart List** tab.

   ![](assets/two-3.png)

1. Under **Add Constraint**, select **Previous Value**.

   ![](assets/three-3.png)

1. Enter the **Previous Value**. In this example we're using MQL.

   ![](assets/four-2.png)

1. Under **Add Constraint**, select **New Value**.

   ![](assets/five.png)

1. Enter the **New Value**. In this example we're using SQL.

   ![](assets/six.png)

1. Nicely done! Click the **People** tab to see all people who had a **Status** change from **MQL** to **SQL** in the past 30 days.

