---
unique-page-id: 1146995
description: Use Tokens in Flow Steps - Marketo Docs - Product Documentation
title: Use Tokens in Flow Steps
---

# Use Tokens in Flow Steps {#use-tokens-in-flow-steps}

>[!PREREQUISITES]
>
>* [Add a Flow Step to a Smart Campaign](add-a-flow-step-to-a-smart-campaign.md)

A token is a variable. You use it in  [emails](https://docs.marketo.com/pages/viewpage.action?pageId=557076),  [landing pages](https://docs.marketo.com/pages/viewpage.action?pageId=2359689), and  [smart campaigns](https://docs.marketo.com/display/DOCS/Smart+Lists+and+Lists) to make your life easier. You can use  [My Tokens](../../../../product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md) (custom tokens) in flow steps, webhooks, emails, and landing pages.  You can use tokens to include variable content in these flow steps:

* Change Data Value
* Interesting Moment
* Salesforce Campaign Steps (add, remove, change status)
* Create Task
* Send Alert (in trigger campaigns only)

>[!NOTE]
>
>**Availability**
>
>Not all customers have purchased this functionality. Contact your sales rep for details. 

1. In the flow step, start typing `{{` to get token categories. ![](assets/image2014-9-22-14-3a3-3a17.png)>

   >[!NOTE]
   >
   >**Deep Dive**
   >
   >Check out [Tokens Overview](../../../../product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) for a list of several available tokens.

1. Keep typing until you find the token you want and click to select.

   ![](assets/image2014-9-22-14-3a3-3a48.png)

   >[!TIP]
   >
   >Multiple tokens can be used in Interesting Moment, Create Task, and Send Alert flow steps.

   >[!NOTE]
   >
   >**Related Articles**
   >
   >* [Managing My Tokens](../../../../product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md)
   >* [Understanding My Tokens in a Program](../../../../product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md)

Cool! The data will be pulled from the token when the smart campaign runs. 