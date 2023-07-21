---
unique-page-id: 1146942
description: Define Smart List for Smart Campaign | Trigger - Marketo Docs - Product Documentation
title: Define Smart List for Smart Campaign | Trigger
exl-id: 14d9b15e-864a-47ef-8f39-3d65e6036a82
feature: Smart Campaigns
---
# Define Smart List for Smart Campaign | Trigger {#define-smart-list-for-smart-campaign-trigger}

Make a Smart Campaign run on one person at a time based on live events by adding triggers.

1. In your Smart Campaign, click the **Smart List** tab.

   ![](assets/define-smart-list-for-smart-campaign-trigger-1.png)

1. Search for the desired trigger and drag and drop it to the canvas.

   ![](assets/define-smart-list-for-smart-campaign-trigger-2.png)

   >[!NOTE]
   >
   >A Smart Campaign with triggers runs in **Trigger** mode. It runs on one person at a time based on events triggered and any additional filters.

   >[!IMPORTANT]
   >
   >When using a Boolean field in a trigger campaign smart list, you must explicitly set it to 'false' in order for the field to evaluate properly during execution of the campaign.

1. Click the drop-down and choose an operator.

   ![](assets/define-smart-list-for-smart-campaign-trigger-3.png)

   >[!CAUTION]
   >
   >Red squiggly lines indicate errors or missing information. If not corrected, the campaign will be invalid and won't run.

   >[!TIP]
   >
   >In a Smart Campaign with both triggers and filters, the triggers go at the top and when triggered, only people who satisfy the filter criteria go through the flow.

1. Define the trigger.

   ![](assets/define-smart-list-for-smart-campaign-trigger-4.png)

   >[!NOTE]
   >
   >With multiple triggers, a person goes through the flow if **ANY** one of the triggers gets activated.

To run the campaign on a set of people all at the same time, learn how to [Define Smart List for Smart Campaign | Batch](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md).

>[!MORELIKETHIS]
>
>[Add a Flow Step to a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
