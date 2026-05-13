---
description: Learn about predictive filters for targeting audiences with AI. Use filters in Smart Lists and campaigns to reach the right people.
title: Predictive Filters
exl-id: 27736b80-cd8b-455d-9d73-c17d492d0906
feature: Predictive Audiences
TQID: https://experienceleague.adobe.com/-P6jjTHT-YDpoEE6yg23rd48s3YYN4kzABbJwZp4rig
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
subfeature_v2:
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
    internal-label: Smart Lists
  - id: ffdd6159-0e10-4a57-8021-94e93bab8183
    internal-label: Event programs
topic_v2:
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
---
# Predictive Filters {#predictive-filters}

As part of Predictive Audiences, Marketo offers a group of AI/ML-based filters in Smart Lists within Smart Campaigns.

   ![Image One](assets/predictive-filters-1.png)

>[!NOTE]
>
>The "Likely to Attend" and "Likely to Register" filters are only be able to be used in Event Programs. "Likelihood to Unsubscribe," "Lookalike of Program Members," and "Lookalike of Smart List Members" can be used in all program types.

## Likelihood to Attend {#likelihood-to-attend}

This filter is used to effectively narrow down your audience. This helps you target and invite leads who have a higher likelihood of **attending** your webinar or event. Note that your "Likelihood to Attend program" will be your current event program.

   ![Image Two](assets/predictive-filters-2.png)

## Likelihood to Register {#likelihood-to-register}

Similar to the _Likelihood to Attend_ filter, use this filter to narrow your audience and target leads who have a higher likelihood of **registering** for your webinar or event.

   ![Image Three](assets/predictive-filters-3.png)

## Likelihood to Unsubscribe {#likelihood-to-unsubscribe}

This filters the audience by whether they have a high or low likelihood of unsubscribing in the next two weeks. You can use this to target high-fatigue leads differently and more effectively. The unsubscribe threshold is dynamic and driven by an AI model that considers several attributes, including lead time in the database and lead activities.

   ![Image Four](assets/predictive-filters-4.png)

>[!NOTE]
>
>The Likelihood to Attend/Register/Unsubscribe filters must be used in conjunction with other standard filters.

## Lookalike of Program Members/Lookalike of Smart List Members {#lookalike-of-members}

These two filters help you expand your current audience by targeting additional leads that are similar to members of another program or Smart List. The Lookalike filters consider 50+ factors, including lead attributes, email activity, web activity, and engagement.

Click **[!UICONTROL Add Constraint]** to choose success criteria for members of the selected program(s).

Click the **+** icon to add multiple programs/Smart Lists to one filter.

   ![Image Five](assets/predictive-filters-5.png)

## Things to Note {#things-to-note}

* You can apply predictive filters to a Smart Campaign even if the parent program is created before predictive filters are enabled.
* Predictive filters are not available for Trigger Campaigns.
* Cloning or moving campaigns that contain predictive filters is not supported.
* You can use up to 5 predictive filters in a Smart List.
* If Marketo Engage encounters an error in the evaluation of predictive filters, the campaign run will automatically abort and a notification will be sent to the Marketo notification center.
* Predictive filters currently have an input limit of 1 million qualified people.
* You can have up to 50 active programs with predictive filters.
