---
unique-page-id: 2359449
description: Define Segment Rules - Marketo Docs - Product Documentation
title: Define Segment Rules
---

# Define Segment Rules {#define-segment-rules}

Defining Segment Rules allows you to categorize your people into different mutually exclusive groups.

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

>[!PREREQUISITES]
>
>[Create a Segmentation](create-a-segmentation.md)

1. Go to the **Database.**

   ![](assets/image2017-3-28-14-3a7-3a42.png)

1. Click on the **Segmentation **from the tree, then click a particular **Segment**.

   ![](assets/image2017-3-28-14-3a11-3a15.png)

1. Click on **Smart List** and add filters.

   ![](assets/image2017-3-28-14-3a18-3a19.png)

   >[!CAUTION]
   >
   >Segments currently do not support *In Past* and *In Timeframe *operators on filters. That's because segmentations only check for updates when a change data value is logged. These values are *not* logged for things that change automatically, such as formula fields and dates. Additionally, date operators with relative date ranges are not supported as they are calculated at the time of segmentation approval, not at the time of a Change Data Value activity.

   >[!NOTE]
   >
   >The "SFDC Type" and "Microsoft Type" filters are currently not supported in segmentation smart lists.

1. Fill appropriate values for the filters.

   ![](assets/image2017-3-28-14-3a18-3a33.png)

   >[!NOTE]
   >
   >**Deep Dive**
   >
   >
   >Smart Lists are awesome. Learn all you can do with [Smart Lists and Static Lists](http://docs.marketo.com/display/docs/smart+lists+and+static+lists).

1. Click on the **People (Draft)** tab to view the people that may qualify to be a member of this segment.

   ![](assets/image2017-3-28-14-3a20-3a15.png)

1. Go to **Segmentation Actions**. Click **Approve**.

   ![](assets/image2014-9-15-11-3a36-3a7.png)

   >[!CAUTION]
   >
   >The total number of segments you can create in a segmentation depends on the number and type of filters used and also on how complex the logic of your segments is. While you can create up to 100 segments using standard fields, using other types of filters can increase the complexity, and your segmentation might fail to approve. Some examples are: custom fields, member of list, lead owner fields, and revenue stages.
   >
   >
   >If you get an error message during approval and require assistance in reducing the complexity of your segmentation, please contact [Marketo Support](http://nation.marketo.com/t5/Support/ct-p/Support).

1. Check out the dashboard for a quick overview of your segments in a pie chart, as well as the rules applied.

   ![](assets/image2014-9-15-11-3a36-3a19.png)

Good work! These segments are going to come in handy in lots of places in Marketo.

>[!NOTE]
>
>A person might qualify for different segments, but eventually belongs to just one which depends on the [priority order of the segments](segmentation-order-priority.md).

>[!NOTE]
>
>**Reminder**
>
>The People (Draft) screen shows all people that qualify to be a member and is not always the final list of people. Approve your segment to see the final list.

>[!NOTE]
>
>**Related Articles**
>
>* [Approve a Segmentation](approve-a-segmentation.md)
>

