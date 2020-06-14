---
unique-page-id: 7515767
description: Share Segmentations Across Workspaces and Partitions - Marketo Docs - Product Documentation
title: Share Segmentations Across Workspaces and Partitions
---

# Share Segmentations Across Workspaces and Partitions {#share-segmentations-across-workspaces-and-partitions}

Share Segmentations Across Workspaces and Partitions - Marketo Docs - Product Documentation

>[!NOTE]
>
>**Prerequisites**
>
>This article is only for customers who have Workspaces and Partitions

#### What's a segmentation? {#sharesegmentationsacrossworkspacesandpartitions-what'sasegmentation?}

Marketo is great at picking out just the right people for a program or smart campaign. However, for more permanent personas, you should use segmentations. They are needed to use advanced dynamic content in Marketo.

>[!NOTE]
>
>**Deep Dive**
>
>Learn [how to create segmentations](../../../../welcome-to-marketo-docs/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md).

Once you have these personas set up (**and** you use workspaces), you will want to share them across your workspaces. Here are some good things to know:  

#### Rules & Tips {#sharesegmentationsacrossworkspacesandpartitions-rules&tips}

* Each Marketo subscription can contain up to 20 Segmentations "total" across multiple workspaces (**not 20 per workspace**).
* You can only share a Segmentation with workspaces that you have access to.
* Make sure to create and utilize a **Default workspace that has visibility into all partitions**.

* `Segmentation processing only runs on the people in the workspace where the Segmentation is created.`

    * Create the Segmentation you want to share inside the Default Workspace.

        * Approve the Segmentation
        * The shared workspace sees a locked folder and the Segmentation is read-only.
        * The shared version cannot be edited. You can only edit the original Segmentation where it was created.

    * When you click on a Segment (e.g. Healthcare) within a shared Segmentation, the people you see will only be people in the partition associated with the workspace you are viewing.

        * If you create a Segmentation in Workspace 1 (WS1) and share it with WS2 and WS1 doesn’t have access to the partition for WS2, it WILL NOT recalculate the Segmentation.
        * If you create a Segmentation in a workspace that has limited partitions, and then share it with another workspace, that workspace that received the shared Segmentation will only see people if they have overlap.

>[!NOTE]
>
>Some of these rules are a little complex. The easiest way to get started is to test with specific people. You can always make new segmentations and get rid of the old ones.

#### Example Scenarios {#sharesegmentationsacrossworkspacesandpartitions-examplescenarios}

![](assets/image2015-5-27-16-3a26-3a25.png)

#### ![](assets/image2015-5-27-16-3a26-3a48.png)

{#sharesegmentationsacrossworkspacesandpartitions-}

#### Share a Segmentation {#sharesegmentationsacrossworkspacesandpartitions-shareasegmentation}

##### 1. Go to the Database. {#sharesegmentationsacrossworkspacesandpartitions-gotothedatabase.}

![](assets/image2017-3-29-8-3a15-3a40.png)

##### 2. Right-click Segmentations and select New Folders. {#sharesegmentationsacrossworkspacesandpartitions-right-clicksegmentationsandselectnewfolders.}

![](assets/image2017-3-29-8-3a40-3a31.png)

##### 3. Name the folder you are going to share across workspaces (example: Share Segmentations.) {#sharesegmentationsacrossworkspacesandpartitions-namethefolderyouaregoingtoshareacrossworkspaces(example-sharesegmentations.)}

![](assets/image2017-3-29-8-3a40-3a45.png)

##### 4. Move the Segmentation(s) you want to share into the folder. {#sharesegmentationsacrossworkspacesandpartitions-movethesegmentation(s)youwanttoshareintothefolder.}

![](assets/image2017-3-29-8-3a41-3a3.png)

##### 5. Right-click the folder and select Share Folder. {#sharesegmentationsacrossworkspacesandpartitions-right-clickthefolderandselectsharefolder.}

![](assets/image2017-3-29-8-3a41-3a19.png)

##### 6. Select the workspace(s) you want to share the folder with. Click Save. {#sharesegmentationsacrossworkspacesandpartitions-selecttheworkspace(s)youwanttosharethefolderwith.clicksave.}

![](assets/image2015-5-27-11-3a6-3a40.png)

>[!NOTE]
>
>The dialog displays the workspaces you have permission to view, which is why Marketo recommends creating and sharing Segmentations from the Default workspace that has visibility into all workspaces and partitions.

The originating folder displays in the Database tree with an arrow indicating that it is shared with other workspaces. From within the shared workspace, the folder displays with a lock to indicate that the contents of the folder have been shared from another workspace and are read-only. 

>[!NOTE]
>
>**Related Articles**
>
>[Segmentation and Snippets](../../../../welcome-to-marketo-docs/product-docs/personalization/segmentation-and-snippets.md)

