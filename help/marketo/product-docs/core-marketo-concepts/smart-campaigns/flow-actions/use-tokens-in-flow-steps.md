---
unique-page-id: 1146995
description: Learn how to use tokens in flow steps. Insert dynamic values into flow step content and emails.
title: Use Tokens in Flow Steps
exl-id: 9b4c3d57-5906-4d7c-8215-4ba2271be3f8
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/0b1iseuF-rKtBcS2qPRdwnPPRYJxUNG9hzlJQxNJQdI
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
---
# Use Tokens in Flow Steps {#use-tokens-in-flow-steps}

>[!PREREQUISITES]
>
>[Add a Flow Step to a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}

A token is a variable. You use it in emails, Landing Pages, and Smart Campaigns to make your life easier. You can use [My Tokens](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md){target="_blank"} (custom tokens) in flow steps, webhooks, emails, and landing pages. You can use tokens to include variable content in these flow steps:

* Change Data Value
* Change Program Member Data
* Interesting Moment
* [!DNL Salesforce] Campaign Steps (add, remove, change status)
* Create Task
* Send Alert (in Trigger Campaigns only)

1. In the flow step, start typing `{{` to get token categories.

   ![](assets/use-tokens-in-flow-steps-1.png)

   >[!NOTE]
   >
   >Check out [Tokens Overview](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"} for a list of several available tokens.

1. Keep typing until you find the token you want and click to select.

   ![](assets/use-tokens-in-flow-steps-2.png)

   >[!TIP]
   >
   >Multiple tokens can be used in Interesting Moment, Create Task, and Send Alert flow steps.

   >[!NOTE]
   >
   >Program Member Custom Field Tokens can be used in: Create Task, Create Task in Microsoft, Interesting Moments, Change Data Value Flow Actions, and Webhooks.

   The data will be pulled from the token when the Smart Campaign runs.

   >[!MORELIKETHIS]
   >
   >* [Managing My Tokens](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"}
   >* [Understanding My Tokens in a Program](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md){target="_blank"}
