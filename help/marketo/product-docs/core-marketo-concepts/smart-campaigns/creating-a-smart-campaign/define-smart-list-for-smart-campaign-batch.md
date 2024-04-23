---
unique-page-id: 1146940
description: Define Smart List for Smart Campaign | Batch - Marketo Docs - Product Documentation
title: Define Smart List for Smart Campaign | Batch
exl-id: 0e0061a9-df24-4cf6-8f1e-09ff0ee62efa
feature: Smart Campaigns
---
# Define Smart List for Smart Campaign | Batch {#define-smart-list-for-smart-campaign-batch}

Smart Lists are the mechanism throughout Marketo Engage to define "who" (which people) to include, whether it's a report, a list, or a Smart Campaign. Here's how to define a Smart List for a batch campaign.

>[!CAUTION]
>
>Making Smart List or Flow Step edits to an active campaign can potentially break its functionality. If you choose to do so, proceed with caution. 

1. Choose a Smart Campaign, then click **[!UICONTROL Smart List]**.

   ![](assets/define-smart-list-for-smart-campaign-batch-1.png)

1. Type to search for a filter and drag and drop it to the canvas. Repeat for multiple filters.

   ![](assets/define-smart-list-for-smart-campaign-batch-2.png)

   >[!NOTE]
   >
   >A Smart Campaign with only filters runs in _Batch_ mode. It finds people in the database that qualify based on the filters and runs all of them through the flow at once.

   >[!NOTE]
   >
   >You can make a Smart Campaign run on one person at a time based on live events by adding triggers, which puts the Smart Campaign in _Trigger_ mode.

1. Click the drop-down and choose a filter operator for the filter you chose.

   ![](assets/define-smart-list-for-smart-campaign-batch-3.png)

   >[!CAUTION]
   >
   >Red squiggly lines indicate errors or missing information. If not corrected, the campaign will be invalid and won't run.

1. Enter the filter value.

   ![](assets/define-smart-list-for-smart-campaign-batch-4.png)

   >[!NOTE]
   >
   >By default, people who satisfy ALL the Smart List rules are qualified. This can be modified to suit your campaign needs. Check out  [Smart List Rules for Complex Logic](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md){target="_blank"} to learn more.

   To trigger on live events one person at a time, learn how to [Define Smart List for Smart Campaign | Trigger](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"}.

   >[!MORELIKETHIS]
   >
   >* [Define Smart List for Smart Campaign | Trigger](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"}
   >* [Add a Flow Step to a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}
