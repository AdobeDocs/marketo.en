---
unique-page-id: 2952636
description: Learn how to find duplicate people with custom logic. Build a Smart List to identify duplicates by your criteria.
title: Find Duplicate People with Custom Logic
exl-id: e268ca34-03a3-403a-8869-4e2b60bba05c
feature: Smart Lists
TQID: 'https://experienceleague.adobe.com/-NvWt-eEzngL0QY7Kyl6lfjd75WcoQmcq3IiN7Uc6-w'
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
subfeature_v2:
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
    internal-label: Smart lists
---
# Find Duplicate People with Custom Logic {#find-duplicate-people-with-custom-logic}

Marketo Engage has a System Smart List that finds duplicate people by matching their email addresses. If you want to use another field to find duplicates with, follow the steps below.

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

    * [!UICONTROL Email Address]
    * [!UICONTROL Full Name]
    * [!UICONTROL Last Name]
    * [!UICONTROL Updated At]

    >[!NOTE]
    >
    >All fields, with the exception of Email Address, are case-sensitive. So using "john doe" in the Full Name field would _not_ return results for John Doe.

   ![](assets/four-2.png)

   Run the Smart List to find people with the same value in the previously selected field.
