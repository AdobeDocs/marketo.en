---
unique-page-id: 10095644
description: Learn how to approve a snippet with No-Draft options. Choose Update all or Create drafts when approving to control how assets using the snippet are updated.
title: Approve a Snippet with No-Draft
exl-id: a06aa77a-68f1-41a4-b2bd-bf1882b81578
feature: Snippets
TQID: https://experienceleague.adobe.com/3vwVKLZIr-z7I22-WaEc4I75rb6luv2n8s1xP6v-q8A
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
subfeature_v2:
  - id: a1d50dda-6d94-4e16-8c30-5eb7181c4650
    internal-label: Segmentation
  - id: df8eb12b-4f82-491f-acbb-d74012ca5654
    internal-label: Snippets
topic_v2:
  - id: c1579802-ddd4-4214-8a91-97b2066abe11
    internal-label: Troubleshooting
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Approve a Snippet with No-Draft {#approve-a-snippet-with-no-draft}

## Approve the Snippet {#approve-the-snippet}

No-Draft is triggered each time a snippet is approved. This includes a snippet that is shared or referenced by assets in other workspaces.

1. Go to the **[!UICONTROL Design Studio]**.

   ![](assets/approve-the-snippet-1.png)

1. Find and select the desired snippet.

   ![](assets/approve-the-snippet-2.png)

1. In the **[!UICONTROL Snippet actions]** drop-down, choose **[!UICONTROL Approve draft]**.

   ![](assets/approve-the-snippet-3.png)

1. Select an option in the Approve snippet dialog box and click **[!UICONTROL Approve]**:

    * **[!UICONTROL Update all]**: This option will not create drafts of the approved assets using the snippet. All assets get the updates and maintain their prior statuses. A progress module appears on the top right side of the screen; it can be closed at any time. To restore it, right-click the snippet name and select Show Approval Status.
    * **[!UICONTROL Create drafts]**: This option will create drafts of the approved assets using the snippet. Select this option if snippet changes need to be reviewed first. All drafts must be approved manually.

   ![](assets/approve-the-snippet-4.png)

   >[!NOTE]
   >
   >For a new snippet that's not used yet, this Approve Draft screen doesn't appear. It shows up when the snippet is used in one or more assets.

>[!CAUTION]
>
>This feature is designed to save time with the snippet approval workflow. However, there are a few limitations to be aware of. Please see [this article](https://nation.marketo.com/t5/knowledgebase/no-draft-snippet-limitations-and-troubleshooting/ta-p/300799){target="_blank"} for details.

>[!MORELIKETHIS]
>
>[Enable No-Draft for Snippets](/help/marketo/product-docs/administration/users-and-roles/enable-no-draft-for-snippets.md){target="_blank"}
