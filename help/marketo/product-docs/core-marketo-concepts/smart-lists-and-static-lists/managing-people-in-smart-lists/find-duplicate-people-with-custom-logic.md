---
unique-page-id: 2952636
description: Find Duplicate People with Custom Logic - Marketo Docs - Product Documentation
title: Find Duplicate People with Custom Logic
exl-id: e268ca34-03a3-403a-8869-4e2b60bba05c
feature: Smart Lists
---
# Find Duplicate People with Custom Logic {#find-duplicate-people-with-custom-logic}

Marketo Engage has a System Smart List that finds duplicate people by matching their email addresses. If you want to use another field to find duplicates with, here's how.

>[!PREREQUISITES]
>
>[Create a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}

1. Go to the **[!UICONTROL Marketing Activities]** area.

![](assets/ma-2.png)

1. Select your Smart List, click on the **[!UICONTROL Smart List]** tab.

   ![](assets/two-4.png)

1. Find and drag the **[!UICONTROL Duplicate Fields]** filter onto the canvas.

   ![](assets/three-4.png)

1. Choose one of four available options:

    * Email Address
    * Full Name
    * Last Name
    * Updated At

    >[!NOTE]
    >
    >All fields, with the exception of Email Address, are case-sensitive. So using "john doe" in the Full Name field would _not_ return results for John Doe.

   ![](assets/four-2.png)

   Done! Run the Smart List to find people with the same value in the previously selected field.
