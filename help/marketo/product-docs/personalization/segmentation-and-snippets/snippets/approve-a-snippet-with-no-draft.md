---
unique-page-id: 10095644
description: Approve a Snippet with No-Draft - Marketo Docs - Product Documentation
title: Approve a Snippet with No-Draft
exl-id: a06aa77a-68f1-41a4-b2bd-bf1882b81578
---
# Approve a Snippet with No-Draft {#approve-a-snippet-with-no-draft}

## Approve the Snippet {#approve-the-snippet}

No-Draft is triggered each time a snippet is approved. This includes a snippet that is shared or referenced by assets in other workspaces.

1. Go to **[!UICONTROL Design Studio]**.

   ![](assets/go-to-design-studio.png)

1. Select a snippet and in the **[!UICONTROL Snippet Actions]** drop-down, choose **[!UICONTROL Approve]**.

   ![](assets/approve-snippet.png)

1. Select an option in the **[!UICONTROL Approve Snippet]** dialog box and click **[!UICONTROL Approve]**:

    * **[!UICONTROL Update all]**: This option will not create drafts of the approved assets using the snippet. All assets get the updates and maintain their prior statuses. A progress module appears on the top right side of the screen; it can be closed at any time. To restore it, right-click the snippet name and select [!UICONTROL Show Approval Status].
    * **[!UICONTROL Create drafts]**: This option will create drafts of the approved assets using the snippet. Select this option if snippet changes need to be reviewed first. All drafts must be approved manually.

   ![](assets/snippet-dialog-box.png)

   >[!NOTE]
   >
   >For a new snippet that's not used yet, this Approve Draft screen doesn't appear. It shows up when the snippet is used in one or more assets.

>[!CAUTION]
>
>This feature is designed to save time with the snippet approval workflow. However, there are a few limitations to be aware of. Please see [this document](https://nation.marketo.com/docs/DOC-4415) for details. The document also contains error handling and troubleshooting information.

>[!MORELIKETHIS]
>
>[Enable No-Draft for Snippets](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions/enable-no-draft-for-snippets.md)
