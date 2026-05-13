---
unique-page-id: 1146980
description: Learn how to use Add Choice in a flow step. Branch your campaign flow based on conditions with choice logic.
title: Use Add Choice in a Flow Step
exl-id: 50ffcd60-48ee-4341-94d8-170c63bc9ecb
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/2zIMDjJx0-Hm1NlgnGrQrnJuBwzMh0B2dq-tnJ34bZo
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
---
# Use Add Choice in a Flow Step {#use-add-choice-in-a-flow-step}

>[!PREREQUISITES]
>
>[Add a Flow Step to a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}

"Add Choice" lets you use a flow step and say 'it depends' when you are choosing the details.

1. Under the **[!UICONTROL Flow]** tab of the Smart Campaign, add any flow step and then click on **[!UICONTROL Add Choice]**.

   ![](assets/use-add-choice-in-a-flow-step-1.png)

1. Select the choice condition.

   ![](assets/use-add-choice-in-a-flow-step-2.png)

1. Choose the choice operator and enter a choice value. This sets your criteria or choice.

   ![](assets/use-add-choice-in-a-flow-step-3.png)

1. Enter a flow step value for the choice.

   ![](assets/use-add-choice-in-a-flow-step-4.png)

   >[!CAUTION]
   >
   >Tokens will _not_ work in the condition part of a choice flow step.

1. Repeat the above steps to add multiple choices, and then add/adjust the default value.

   ![](assets/use-add-choice-in-a-flow-step-5.png)

   >[!TIP]
   >
   >You can set any of your flow steps to --Do Nothing--, in which case no action will be taken on that choice.

   >[!CAUTION]
   >
   >Only the first matching choice is applied to the flow step. Learn how to [reorder "Add Choice" in a flow action](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/reorder-add-choice-in-a-flow-step.md){target="_blank"}.

   You can now create a single Smart Campaign with flow step choices instead of creating multiple Smart Campaigns for each choice.

   >[!MORELIKETHIS]
   >
   >[Reorder Add Choice in a Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/reorder-add-choice-in-a-flow-step.md){target="_blank"}
