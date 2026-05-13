---
unique-page-id: 2359447
description: Learn how to create a segmentation to group people for reporting and dynamic content. Add segments in Database, set order, then define segment rules.
title: Create a Segmentation
exl-id: a7907f1d-bc78-4b63-9875-044e96609755
feature: Segmentation
TQID: https://experienceleague.adobe.com/Xp4uo4aDMkK9Di3Dp0ufHnxgg8ci7YDD2qOO6rZwI7M
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
subfeature_v2:
  - id: a1d50dda-6d94-4e16-8c30-5eb7181c4650
    internal-label: Segmentation
  - id: cdd4e0f6-e87e-453f-88ee-2ee54a7de272
    internal-label: Dynamic content
  - id: df8eb12b-4f82-491f-acbb-d74012ca5654
    internal-label: Snippets
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Create a Segmentation {#create-a-segmentation}

Segmentation allows you to group people into distinct profiles for reporting and dynamic content. Here's how to create them.

1. Go to your **[!UICONTROL Database]**.

   ![](assets/create-a-segmentation-1.png)

1. Click **[!UICONTROL New]** and then **[!UICONTROL New Segmentation]**.

   ![](assets/create-a-segmentation-2.png)

   >[!TIP]
   >
   >You can create up to 20 segmentations.

1. Enter a **[!UICONTROL Name]**, click **[!UICONTROL Add Segment]** and name it.

   ![](assets/create-a-segmentation-3.png)

   >[!NOTE]
   >
   >Default cannot be moved, edited, or deleted.

1. Add as many segments as you want (up to 100).

   ![](assets/create-a-segmentation-4.png)

   >[!CAUTION]
   >
   >The total number of segments you can create in a segmentation depends on the number and type of filters used and also on how complex the logic of your segments is. While you can create up to 100 segments using standard fields, using other types of filters can increase the complexity, and your segmentation might fail to approve. Some examples are: custom fields, member of list, lead owner fields, and revenue stages.
   >
   >If you get an error message during approval and require assistance in reducing the complexity of your segmentation, please contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Drag and drop the Segments around to change their order. Once done, click on **[!UICONTROL Create]**.

   ![](assets/create-a-segmentation-5.png)

   >[!NOTE]
   >
   >A person will qualify for the first matching segment in the [order](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/segmentation-order-priority.md) defined.

   >[!NOTE]
   >
   >You need to define segment rules before you can use your Segmentation.

   Congratulations! You are one step closer to using Dynamic Content.

   >[!MORELIKETHIS]
   >
   >[Define Segment Rules](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/define-segment-rules.md)
