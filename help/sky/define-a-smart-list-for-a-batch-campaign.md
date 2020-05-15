---
Title: define-a-smart-list-for-a-batch-campaign
Description: Define a Smart List for a Batch Campaign
---

# Define a Smart List for a Batch Campaign

Smart lists are the mechanism throughout Marketo to define "who" (which people) to include, whether it's a report, a list, or a smart campaign. Here's how to define a smart list for a batch campaign.

1. Choose a smart campaign, then click **Smart List**.

   ![Image One](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-1.png)

1. Type to search for a filter and then drag and drop it to the canvas. Repeat for multiple filters.

   ![Image Two](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-2.png)

   >[!NOTE]
   >
   >A smart campaign with only filters runs in Batch mode. It
   >finds people in the database that qualify based on the
   >filters and runs all of them through the flow at once.

   **Reminder**

   You can make a smart campaign run on one person at a time based on live events by adding triggers, which puts the smart campaign in Trigger mode.

1. Click the drop-down and choose a filter operator (e.g. **is**, **is not**, etc.,) for the filter you chose.

   ![Image Three](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-3.png)

   >[!CAUTION]
   >
   >Red lines indicate errors or missing information. If not
   >corrected, the campaign will be invalid and won't run.

1. Enter the filter value.

   ![Image Four](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-4.png)

>[!NOTE]
>
>By default, people who satisfy ALL the smart list rules are
>qualified. This can be modified to suit your campaign needs.
>Check out [Smart List Rules for Complex Logic](https://docs.marketo.com/display/DOCS/Using+Advanced+Smart+List+Rule+Logic) to learn more.
>
>To trigger on live events one person at a time, learn how to
>[Define Smart List for Smart Campaign | Trigger](https://docs.marketo.com/display/DOCS/Define+Smart+List+for+Smart+Campaign+%7C+Trigger).
