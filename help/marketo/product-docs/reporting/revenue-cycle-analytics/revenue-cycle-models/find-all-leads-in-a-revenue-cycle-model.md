---
unique-page-id: 2360423
description: Find all Leads in a Revenue Cycle Model - Marketo Docs - Product Documentation
title: Find all Leads in a Revenue Cycle Model
---

# Find all Leads in a Revenue Cycle Model {#find-all-leads-in-a-revenue-cycle-model}

By using smart lists, you can easily find all members of revenue cycle model.

>[!NOTE]
>
>**Prerequisites**
>
>[Create a Smart List](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)

1. With the smart listed selected, click on the **Smart List** tab.

   ![](assets/image2015-4-29-14-3a6-3a36.png)

1. Find the **Member of Revenue Model** filter and drag it into the canvas.

   ![](assets/image2015-4-29-14-3a12-3a33.png)

1. Select a **Model**.

   ![](assets/image2015-5-13-18-3a2-3a23.png)

   This would get you all the leads in that model, regardless of stage. Usually you will want a specific stage. Use the following filter instead.

1. Find the **Revenue Stage **filter and drag it into the canvas.

   ![](assets/image2015-5-13-17-3a27-3a0.png)

1. Select a **Stage.**

   ![](assets/image2015-5-13-17-3a31-3a9.png)

1. Go to the **Leads** tab to view the results.

   ![](assets/2.png)

   >[!TIP]
   >
   >You don't need both filters, just choose the one you need. We are just showing you both to be thorough. ![(smile)](assets/smile.svg)   >
   >

   >[!CAUTION]
   >
   >If the stage of a lead is changed by an external campaign during the initial creation of the lead, then an activity is not logged in the database. This means that the lead won’t be included by the smart list filter.

