---
unique-page-id: 7514898
description: "Learn how to set up a trigger Smart Campaign for sales using Campaign is Requested. Let sales request campaigns for leads from the CRM."
title: Setting Up a Trigger Smart Campaign for Sales Using "Campaign is Requested"
exl-id: ed6d7c27-d54b-48e3-af67-19503da4ef56
feature: Smart Campaigns
---
# Setting Up a Trigger Smart Campaign for Sales Using "Campaign is Requested" {#setting-up-a-trigger-smart-campaign-for-sales-using-campaign-is-requested}

One of the coolest features of Marketo is the ability to let sales people participate in the marketing effort. They're on the front lines, interacting with people. Sales reps should have the ability to steer marketing in the right direction.

>[!NOTE]
>
>Examples of Smart Campaigns to request:
>
>1. **Long term nurture** - when they do not have a budget this year and you want to stay on the radar
>1. **Active sales cycle** - when the sales person does not want any messages to the person except their own. (use the marketing suspended flag to temporarily unsubscribe them)
>
>Ask the sales team what they would like to automate and set it up.

1. Create a Smart Campaign.

   ![](assets/setting-up-a-trigger-smart-campaign-for-sales-1.png)

1. Find and drag the **[!UICONTROL Campaign is Requested]** trigger to the canvas.

   ![](assets/setting-up-a-trigger-smart-campaign-for-sales-2.png)

1. The source choices indicate what kind of request will be honored. For Salesforce functionality, choose **[!UICONTROL Sales Insight]**.

   >[!TIP]
   >
   >The source operators are for security. You can restrict the campaign to requests made only by specific sources, like other Smart Campaigns or developers. Choose **[!UICONTROL Is Any]** in the first box if you want to allow requests from all sources.
   >
   >_Remember_, by choosing Sales Insight, it will magically show up in the box for sales. Avoid adding too many, as they will get ignored.

   ![](assets/setting-up-a-trigger-smart-campaign-for-sales-3.png)

This is a great way to extend your marketing reach into other departments. Set up all kinds of campaigns to automate.

>[!TIP]
>
>Name your Smart Campaigns clearly. They will show up in Sales Insight exactly how you name them.
