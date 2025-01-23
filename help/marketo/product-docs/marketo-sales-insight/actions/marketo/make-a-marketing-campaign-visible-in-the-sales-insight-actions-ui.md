---
description: Make a Marketing Campaign Visible in the Sales Insight Actions UI - Marketo Docs - Product Documentation
title: Make a Marketing Campaign Visible in the Sales Insight Actions UI
exl-id: 223baca3-159e-4f0d-b26f-f4c924a39fc3
feature: Sales Insight Actions
---
# Make a Marketing Campaign Visible in the Sales Insight Actions UI {#make-a-marketing-campaign-visible-in-the-sales-insight-actions-ui}

Campaigns can only be shared if they're made visible.

With Sales Insight Actions, users will have access to a new sales app called toutapp.com. This app gives them a new set of action capabilities, but also inherits the _Add to Marketing Campaign_ feature available in the core version of Sales Insights. This is important to keep in mind, because depending on where you you want users to access the Add to Marketing Campaign feature (toutapp.com or the MSI SFDC package experience), your Marketo campaigns will need to be configured differently. See the note in Step 4 to learn more.

1. Select (or create) the Campaign you want shared.

   ![](assets/make-a-marketing-campaign-visible-sia-1.png)

1. Click the **Smart List** tab.

   ![](assets/make-a-marketing-campaign-visible-sia-2.png)

1. Add the Campaign is Requested trigger.

   ![](assets/make-a-marketing-campaign-visible-sia-3.png)

1. For source, choose "is" **Web Service API**.

   ![](assets/make-a-marketing-campaign-visible-sia-4.png)

   >[!NOTE]
   >
   >If you want to show the marketing campaign to users who are utilizing _Add to Marketing Campaign_ from the toutapp.com web app (this also includes if you have the web app embedded into the CRM via the Marketo Sales Outbox object), set it to "Web Service API." If you want the marketing campaign to show up when a user uses the actions on the MSI panel in Salesforce on the lead, contact, account page, or the bulk action buttons on the lead and contact list views, update it to "Sales Insight"

1. Click the **Flow** tab.

   ![](assets/make-a-marketing-campaign-visible-sia-5.png)

1. Add the Interesting Moment flow action.

   ![](assets/make-a-marketing-campaign-visible-sia-6.png)

1. For Type, select **Web**.

   ![](assets/make-a-marketing-campaign-visible-sia-7.png)

1. In the Description box, write a message to your sales team. In this example we're using tokens to specify the form that was filled out.

   ![](assets/make-a-marketing-campaign-visible-sia-8.png)

1. Click the **Schedule** tab and **Activate** the campaign.

   ![](assets/make-a-marketing-campaign-visible-sia-9.png)
