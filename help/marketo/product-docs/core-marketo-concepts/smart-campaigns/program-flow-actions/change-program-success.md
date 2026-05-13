---
unique-page-id: 1147009
description: Learn how to change program success in a flow step. Mark people as success in a program when they complete an action.
title: Change Program Success
exl-id: 5b45b6d0-0c3d-4677-8b9a-8bbf03b1209e
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/0sVuHDmklNwn9JQRJuHW7QkXsiANYSRldt9ZRegC-6k
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
---
# Change Program Success {#change-program-success}

If you ever have a group of people that are marked with Program Success incorrectly, you can use this flow step to set success to true or false.

![](assets/change-program-success-1.png)

1. When you drag in this flow step, the program will automatically be set to the program that contains the smart campaign you are editing.

   >[!NOTE]
   >
   >Only members of the program will be affected.

   ![](assets/change-program-success-2.png)

1. Select **[!UICONTROL Success]** or **[!UICONTROL Success Date]** as the Attribute.

   ![](assets/change-program-success-3.png)

   >[!NOTE]
   >
   >Setting [!UICONTROL Success Date] to anything automatically sets Success to true. Setting [!UICONTROL Success] to true automatically sets the Success Date to the current date.

1. Set the **[!UICONTROL New Value]** to **[!UICONTROL True]** or **[!UICONTROL False]**.

   ![](assets/change-program-success-4.png)

   >[!TIP]
   >
   >You can use the flow step twice to set both the Success flag as well as the date.

Now you know how to undo and force success.
