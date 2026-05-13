---
unique-page-id: 2359500
description: Learn about segmentation order priority and how it determines which segment a person belongs to. Edit segment order in Database to control evaluation of segments.
title: Segmentation Order Priority
exl-id: c20d07c8-5e53-4f54-a7a3-2e1aa4fb0cdd
feature: Segmentation
TQID: https://experienceleague.adobe.com/wDvufJzxu0BFCSov4etUpEMxaol3-R5CePqllYyDeSc
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
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
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Segmentation Order Priority {#segmentation-order-priority}

It is important to understand how **order** sets the priority for evaluation of your people in a segmentation.

>[!PREREQUISITES]
>
>[Create a Segmentation](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)
>[Define Segment Rules](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/define-segment-rules.md)

>[!NOTE]
>
>You can only edit a segmentation in draft mode.

1. Go to the **Database**.

   ![](assets/segmentation-order-priority-1.png)

1. Select your **Segmentation**. In **[!UICONTROL Segmentation Actions]**, click **[!UICONTROL Edit Segments]**.

   ![](assets/segmentation-order-priority-2.png)

   You can check or edit the order of your segments from this screen.

   ![](assets/segmentation-order-priority-3.png)

>[!NOTE]
>
>* The segments are mutually exclusive. A person can be a member of only one Segment at a time.
>* When a person qualifies for two segments, they will belong only to the first one in the list.
>* If a person does not qualify for any Segment, they will become a member of the Default Segment.
