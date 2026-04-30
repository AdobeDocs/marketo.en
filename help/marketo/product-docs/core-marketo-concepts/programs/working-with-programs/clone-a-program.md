---
unique-page-id: 1147110
description: "Learn how to clone a program and all its assets. Create a copy in a campaign folder or workspace without rebuilding manually."
title: Clone a Program
exl-id: 5597007c-8f58-4306-ab78-3e65d6369fbf
feature: Programs
---
# Clone a Program {#clone-a-program}

Clone an entire program and all its assets instead of manually rebuilding everything.

1. Find and select the program you want to clone. In the **[!UICONTROL Program Actions]** drop-down, click **[!UICONTROL Clone]**.

   ![](assets/image2014-9-5-14-3a31-3a49.png)

1. Select where you want to clone your program to.

   >[!NOTE]
   >
   >Programs can be cloned into [campaign](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/create-new-campaign-folder.md) [folders](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/create-new-campaign-folder.md) or [workspaces](/help/marketo/product-docs/administration/workspaces-and-person-partitions/create-a-new-workspace.md). Ensure all underlying dependent assets (emails, snippets, landing page templates, etc.) are shared with the destination workspace before cloning.

   ![](assets/cloneto.png)

   >[!NOTE]
   >
   >See that [!UICONTROL NOTE] in the screenshot above? It means if you clone a program with 1000 or more people in a list, the list itself will get cloned, but it will be empty. If you clone a program with a list that contains 999 people or less, that list, along with all of its members, will show up in the cloned program.

1. Enter a **[!UICONTROL Name]**.

   ![](assets/cloneprogramname.png)

1. Choose the destination folder.

   ![](assets/choosefolderclone.png)

1. Add an optional description, then click **[!UICONTROL Create]**.

   ![](assets/createclone.png)

   >[!TIP]
   >
   >Use this technique along with tokens to make new program creation faster.

   >[!CAUTION]
   >
   >Period costs will not transfer over, so ensure that is added to the cloned program if one was set in the original.
