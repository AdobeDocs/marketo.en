---
unique-page-id: 12981145
description: Learn how to set up Performance Insights by configuring opportunity setup, program costs, analytics behavior, and success criteria. Ensure proper attribution and data flow for accurate reporting.
title: Setting Up Performance Insights
exl-id: f87bbaba-c2c1-4b83-9e07-f8a5d1f1738b
feature: Reporting
TQID: https://experienceleague.adobe.com/xH9HG3hKoUFG3428IngBYFG6n4W3k1Bd-baVI7WTMrE
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
subfeature_v2:
  - id: b9f06cb0-cdf7-4b83-a9d1-a701d132779b
    internal-label: Program analysis
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
---
# Setting Up [!UICONTROL Performance Insights] {#setting-up-performance-insights}

Follow the steps below to set up MPI.

## Opportunity Setup {#opportunity-setup}

1. Click **[!UICONTROL Admin]**.

   ![](assets/admin.png)

1. Click **[!UICONTROL Revenue Cycle Analytics]**.

   ![](assets/two-2.png)

   >[!NOTE]
   >
   >If you do not have RCA, you'll need to select **[!UICONTROL Program Analysis]** for Step 2.

1. Under Attribution, click **[!UICONTROL Edit]**.

   ![](assets/three-1.png)

1. Attribution Settings displays.

   ![](assets/four-2.png)

   If Attribution is explicit, ensure the Opportunity Contact Role has been populated (either via the Opportunity Role endpoint or via CRM integration).

   If Attribution is implicit, ensure the company field on the lead/contact is the same as the Account Name of the opportunity.

   >[!NOTE]
   >
   >Ensure all of the opportunities have the appropriate fields populated:
   >
   >* [!UICONTROL Opportunity Amount]
   >* [!UICONTROL Is Closed]
   >* [!UICONTROL Is Won]
   >* [!UICONTROL Creation Date] (this may not be set in your case)
   >* [!UICONTROL Closed Date] (this may not be set in your case)
   >* [!UICONTROL Opportunity Type]

## Program Setup {#program-setup}

Update the program costs for at least 12 months. You can do this manually or using the program API. In this example we do it manually.

1. Click **[!UICONTROL Marketing Activities]**.

   ![](assets/ma.png)

1. Find and select your program.

   ![](assets/select-program.png)

1. Click the **[!UICONTROL Setup]** tab.

   ![](assets/setup-tab.png)

1. Drag **[!UICONTROL Period Cost]** onto the canvas.

   ![](assets/period-cost.png)

1. Set the Program Month for at least 12 months ago and click **[!UICONTROL Ok]**.

   ![](assets/set-period.png)

1. Set the period cost and click **[!UICONTROL Save]**.

   ![](assets/set-cost.png)

Next, review the analytics behavior to indicate whether particular channel should be included in analytics. Set the Analytics Behavior (Normal, Inclusive, Operational).

1. Click **[!UICONTROL Admin]**.

   ![](assets/admin.png)

1. Click **[!UICONTROL Tags]**.

   ![](assets/tags.png)

1. Click the **+** to expand the Channel list.

   ![](assets/channel.png)

1. Double-click the desired channel.

   ![](assets/channel-click.png)

1. Click the **[!UICONTROL Analytics Behavior]** drop-down and select the desired behavior.

   ![](assets/edit-channel.png)

1. Set the success criteria.

   ![](assets/success.png)

1. Click **[!UICONTROL Save]**.

   ![](assets/save.png)

## Tie the Program to the Person {#tie-the-program-to-the-person}

1. Make sure Acquisition Program and Acquisition Date have been set for each person in your database in order for First Touch Attribution to work.
1. Ensure your programs are setting success states for your people.

>[!NOTE]
>
>Changes made are not instantaneous. An overnight period is required before changes go into effect.
