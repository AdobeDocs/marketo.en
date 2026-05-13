---
unique-page-id: 2360309
description: Learn how workspaces organize marketing assets and how person partitions act as separate databases.
title: Understanding Workspaces and Person Partitions
exl-id: 27d00a0d-ebf1-4dff-b41e-1644ec9dbd28
feature: Partitions, Workspaces
TQID: https://experienceleague.adobe.com/Ex-WBSNYTFvevcwryuO4CzUsg79nOmjkVx4WMUx9nqA
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
    internal-label: Smart Lists
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Understanding Workspaces and Person Partitions {#understanding-workspaces-and-person-partitions}

## Workspaces {#workspaces}

>[!CAUTION]
>
>Workspaces can be complex to set up. Contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support) to find out if they are right for you.

Workspaces are separate areas in Marketo that hold marketing assets like programs, landing pages, emails and more. They can be used by multiple people. Each user has access to one or more workspaces.

>[!NOTE]
>
>**Example**
>
>Some reasons you might use a workspace:
>
>* Geography: Europe, Asia and North America marketing departments each get a workspace
>* Business Unit: [!DNL Quicken], [!DNL Quickbooks] and [!DNL TurboTax] each get a workspace
>
>In each case, the separation is because the marketing assets are completely different. If they share marketing assets, then workspaces may not be the right tool for you.

>[!NOTE]
>
>Learn how to [create a new workspace](/help/marketo/product-docs/administration/workspaces-and-person-partitions/create-a-new-workspace.md).

## Sharing across Workspaces {#sharing-across-workspaces}

The following steps explain how to share assets across workspaces. It works the same for anything you want to share; this example shows segmentations.

>[!NOTE]
>
>The parent folder containing your assets is the only folder that can be shared, not the children folders.

1. Click **[!UICONTROL Database]**.

   ![](assets/understanding-workspaces-and-person-partitions-1.png)

1. Right-click on the Segmentation folder and click **[!UICONTROL New Folder]**.

   ![](assets/understanding-workspaces-and-person-partitions-2.png)

1. Name your folder and click **[!UICONTROL Create]**.

   ![](assets/understanding-workspaces-and-person-partitions-3.png)

1. Move the asset(s) you want to share into the folder.

   ![](assets/understanding-workspaces-and-person-partitions-4.png)

1. Right-click the folder and select **[!UICONTROL Share Folder]**.

   ![](assets/understanding-workspaces-and-person-partitions-5.png)

1. Select the workspace(s) you want to share the folder with and click **[!UICONTROL Save]**. The Share Folder dialog box will only display workspaces you have permission to view.

   ![](assets/understanding-workspaces-and-person-partitions-6.png)

   >[!NOTE]
   >
   >The originating folder will now have a small green arrow, indicating it was shared. In the workspace shared, the folder will have a padlock, indicating read-only.

You can share these items across workspaces.

* Email templates
* Landing page templates
* Models
* Smart campaigns
* [Smart lists](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/reference-a-list-or-smart-list-across-workspaces.md)
* [Segmentations](/help/marketo/product-docs/administration/workspaces-and-person-partitions/share-segmentations-across-workspaces-and-partitions.md)
* Snippets

## Cloning across Workspaces {#cloning-across-workspaces}

For assets that are not templates, cloning them as local assets inside a program is recommended. With the proper access level, you can drag and drop these assets into another workspace:

* Programs
* Emails
* Landing Pages
* Forms

>[!IMPORTANT]
>
>While all of the items listed above can be cloned across Workspaces, emails, forms, and Landing Pages _must be inside a program_ at the time of cloning.

>[!NOTE]
>
>When cloning assets that have templates, those templates must be shared with the destination workspace.

## Moving Assets to other Workspaces {#moving-assets-to-other-workspaces}

To move assets to a new workspace, put them into a folder and drag the folder over to the other workspace.

>[!NOTE]
>
>A program that contains members cannot be moved from one workspace to another.

## Person Partitions {#person-partitions}

Person partitions act like separate databases. Each partition has its own people that do not de-dupe or mix with other partitions. If your business use case requires duplicate records with the same email address, contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support).

You can assign person partitions to  [workspaces](create-a-new-workspace.md) in the following configurations:

* one workspace to one person partition (1:1)
* one workspace to many person partitions (1:x)
* many workspaces to one person partition (x:1)

>[!NOTE]
>
>Reasons you would use a person partition:
>
>* Your workspaces not only have different assets, but also do not share any people
>* You want duplicates for other business reasons

>[!CAUTION]
>
>Person partitions do not interact with each other, so be careful when setting them up.

>[!NOTE]
>
>Learn how to [create a person partition](/help/marketo/product-docs/administration/workspaces-and-person-partitions/create-a-person-partition.md).
