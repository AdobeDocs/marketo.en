---
unique-page-id: 1146980
description: Use Add Choice in a Flow Step - Marketo Docs - Product Documentation
title: Use Add Choice in a Flow Step
exl-id: 50ffcd60-48ee-4341-94d8-170c63bc9ecb
feature: Smart Campaigns
---
# Use Add Choice in a Flow Step {#use-add-choice-in-a-flow-step}

>[!PREREQUISITES]
>
>[Add a Flow Step to a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}

"Add Choice" lets you use a flow step and say 'it depends' when you're choosing the details.

1. Under the **[!UICONTROL Flow]** tab of the Smart Campaign, add any flow step and then click on **[!UICONTROL Add Choice]**.

   ![](assets/image2014-9-22-11-3a58-3a20.png)

1. Select the choice condition.

   ![](assets/image2014-9-22-11-3a58-3a50.png)

1. Choose the choice operator and enter a choice value. This sets your criteria or choice.

   ![](assets/image2014-9-22-11-3a58-3a54.png)

1. Enter a flow step value for the choice.

   ![](assets/image2014-9-22-11-3a58-3a57.png)

   >[!CAUTION]
   >
   >Tokens will _not_ work in the condition part of a choice flow step.

1. Repeat the above steps to add multiple choices, and then add/adjust the default value.

   ![](assets/image2014-9-22-11-3a58-3a59.png)

   >[!TIP]
   >
   >You can set any of your flow steps to --Do Nothing--, in which case no action will be taken on that choice.

   >[!CAUTION]
   >
   >Only the first matching choice is applied to the flow step. Learn how to [reorder "Add Choice" in a flow action](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/reorder-add-choice-in-a-flow-step.md){target="_blank"}.

   Great! You can now create a single Smart Campaign with flow step choices instead of creating multiple Smart Campaigns for each choice.

   >[!MORELIKETHIS]
   >
   >[Reorder Add Choice in a Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/reorder-add-choice-in-a-flow-step.md){target="_blank"}
