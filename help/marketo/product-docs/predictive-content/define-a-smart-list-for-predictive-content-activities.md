---
unique-page-id: 10097873
description: Define a Smart List for Predictive Content Activities - Marketo Docs - Product Documentation
title: Define a Smart List for Predictive Content Activities
---

# Define a Smart List for Predictive Content Activities {#define-a-smart-list-for-predictive-content-activities}

Define a Smart List for Predictive Content Activities - Marketo Docs - Product Documentation

>[!NOTE]
>
>Depending on the purchase date, your Marketo subscription may include either Marketo Predictive Content or Content`<sup>AI</sup>`. For those using Predictive Content, Marketo is enabling Content`<sup>AI</sup>` Analytics features until April 30, 2018. To keep these features beyond that date, please contact your Marketo Customer Success Manager to upgrade to Marketo Content`<sup>AI</sup>`.

You can use predictive content activities in triggers and filters when you define a smart list in a smart campaign. You can trigger an action for anyone who clicks predictive content via the [Rich Media template](enabling-predictive-content/enable-predictive-content-for-web-rich-media.md), the [Content Recommendation Bar](enabling-predictive-content/enable-the-content-recommendation-bar.md), or in an email.

1. In your smart campaign, navigate to the **Smart List**&nbsp;tab.

   ![](assets/smart-list-1.png)

   >[!NOTE]
   >
   >**Deep Dive**
   >
   >
   >Smart lists can do amazing things. Learn more in the [smart list deep dive](../../product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md).

1. Search for the trigger and then drag and drop it onto the canvas.

   ![](assets/smart-list-drag-trigger-hands.png)

   >[!NOTE]
   >
   >A smart campaign with triggers runs in Trigger mode. It runs on one person at a time based on events triggered and the filters added.

1. Click the **Name** drop-down and select an operator.

   ![](assets/smart-list-dropdown-hands.png)

1. Define the trigger.

   ![](assets/smart-lislt-select-content-hands.png)

1. Add the **Type** constraint.

   ![](assets/clicks-predictive-content-add-constraint-hands.png)

1. Select the source you need for your smart list.

   ![](assets/pc-add-constraint.png)

1. If you're using the email source for your predictive content, add the **Clicks Link in Email **trigger. Select your email and add the **Is Predictive** constraint, defined as **true**.

   ![](assets/clicks-link-in-email-trigger-hands.png)

1. Add any other filters as needed.

   ![](assets/clicked-predictive-content-filter.png)

   >[!TIP]
   >
   >In a smart campaign with both triggers and filters, the triggers go at the top. When triggered, only people who satisfy the filter criteria go through the flow.

   >[!NOTE]
   >
   >With multiple triggers, a person goes through to the flow if ANY one of the triggers get activated.

   [define a smart list for a batch smart campaign](../../product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-|-batch.md)

   >[!NOTE]
   >
   >**Related Articles**
   >
   >    
   >    
   >    * [Define Smart List for Smart Campaign | Batch](../../product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-|-batch.md)
   >    * [Add a Flow Step to a Smart Campaign](../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
   >    * [Define a Smart List for Web Personalization Activities](../../product-docs/web-personalization/working-with-web-campaigns/define-a-smart-list-for-web-personalization-activities.md)
   >    * [Enable Predictive Content for Web Rich Media](enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
   >    * [Enable the Content Recommendation Bar](enabling-predictive-content/enable-the-content-recommendation-bar.md)
   >    
   >

To run the campaign on a set of people all at the same time, learn how to . 