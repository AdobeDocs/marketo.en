---
unique-page-id: 4718683
description: Approving Stages and Assigning Leads to a Revenue Model - Marketo Docs - Product Documentation
title: Approving Stages and Assigning Leads to a Revenue Model
exl-id: 0c93dfe4-8950-444c-a65b-080620816ba2
feature: "Reporting, Revenue Cycle Analytics"
---
# Approving Stages and Assigning Leads to a Revenue Model {#approving-stages-and-assigning-leads-to-a-revenue-model}

Get your **Revenue Model** up and running by adding existing leads, creating assignment rules for any new leads.  

## Approving Stages {#approving-stages}

Let's approve the stages of your model before you add any leads.

1. Go to the **Analytics** area.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. Select the model whose stages you'd like to approve.

   ![](assets/image2015-4-28-17-3a10-3a3.png)

1. Under **Model Actions**, select **Approve Stages**.

   ![](assets/image2015-4-28-17-3a12-3a37.png)

1. You'll be greeted with an alert; click **Assign Leads**.

   ![](assets/image2015-4-28-17-3a5-3a39.png)

Excellent! Let's move on and assign those leads.

## Assigning Existing Leads {#assigning-existing-leads}

[Create a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) to identify the leads for one stage of your model in your Lead Database.

1. Once you've [created your Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md), click the **Leads** tab.

   ![](assets/image2015-4-29-11-3a37-3a30.png)

1. Click **Select All** to select the leads.

   ![](assets/image2015-4-29-11-3a39-3a39.png)

1. Open the **Lead Actions** drop-down and select **Special**. Click **Change Revenue Stage**.

   ![](assets/image2015-4-29-11-3a40-3a38.png)

1. Select the correct **Model** and the correct **Stage**. Click **Run Now**.

   ![](assets/image2015-4-29-11-3a43-3a41.png)

1. Repeat until all your leads are assigned to the various stages of your model.

Great! To specify how new leads are assigned to stages, create assignment rules.

>[!NOTE]
>
>If your model is in the Approved Stages state, you will not see any Change Revenue Stage events in the leads' activity logs. If your model is fully approved, this flow step will be skipped if you move a lead into the same stage it's currently in.

## New Leads: Create Assignment Rules  {#new-leads-create-assignment-rules}

1. Click **Marketo Home** again, then select **Analytics**.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. Click your model in the tree, then the **Model Actions** menu, selecting **Assignment Rules**.

   ![](assets/image2015-4-29-11-3a52-3a17.png)

1. If your assignment rules contain more than just one default choice click **Stage**, make your selection, then click **Add Choice**.

   ![](assets/image2015-4-29-12-3a5-3a46.png)

## Example Assignment Rule {#example-assignment-rule}

Create a Lead Score rule to assign the new leads with a minimum score to an appropriate step.

1. Under **If**, select **Lead Score**. Then choose **at least**.

   ![](assets/image2015-4-29-13-3a27-3a8.png)

1. Enter **40** in the field and select **Sales Lead** as a Stage. Click **Save** to complete.

   ![](assets/image2015-4-29-14-3a4-3a23.png)

>[!MORELIKETHIS]
>
>To approve your model, read our help page on **[Approving and Unapproving a Revenue Model](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/approve-unapprove-a-revenue-model.md)**.
