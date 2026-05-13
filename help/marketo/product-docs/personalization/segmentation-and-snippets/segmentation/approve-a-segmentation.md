---
unique-page-id: 2359457
description: Learn how to approve a segmentation so it can be used for dynamic content and reporting. Use Database and Segmentation Actions to approve after defining segment rules.
title: Approve a Segmentation
exl-id: c8b0fbe9-012c-47bf-8769-0167156b43d3
feature: Segmentation
TQID: https://experienceleague.adobe.com/hvFKybwLh1INYx2YWtOmdebJVYXOzhNMMncqeOoV8EU
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
  - id: df8eb12b-4f82-491f-acbb-d74012ca5654
    internal-label: Snippets
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Approve a Segmentation {#approve-a-segmentation}

A segmentation needs to be approved before it can be used.

>[!PREREQUISITES]
>
>* [Create a Segmentation](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)
>* [Define Segment Rules](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/define-segment-rules.md)

>[!NOTE]
>
>A maximum of 20 Segmentations can be approved at a time.

1. Go to the **[!UICONTROL Database]**.

   ![](assets/approve-a-segmentation-1.png)

1. In the Segmentation click **[!UICONTROL Segmentation Actions]**, and then **[!UICONTROL Approve]**.

   ![](assets/approve-a-segmentation-2.png)

   >[!NOTE]
   >
   >The status changes to _Approving_ while the approval is in process.

   >[!CAUTION]
   >
   >Approval can take from a few minutes to a day or two to complete, depending on the size of the database.

1. Once approved, the [!UICONTROL Status] changes from [!UICONTROL Approving] to [!UICONTROL Approved].
   
   ![](assets/approve-a-segmentation-3.png)

   >[!TIP]
   >
   >The number of people in each segment is shown in brackets next to the segment name.

1. The **[!UICONTROL People]** tab in the **[!UICONTROL Segment]** now shows the final list of people for the segment.

   ![](assets/approve-a-segmentation-4.png)

>[!CAUTION]
>
>The total number of segments you can create in a segmentation depends on the number and type of filters used and also on how complex the logic of your segments is. While you can create up to 100 segments using standard fields, using other types of filters can increase the complexity, and your segmentation might fail to approve. Some examples are: custom fields, member of list, lead owner fields, and revenue stages.
>
>If you get an error message during approval and require assistance in reducing the complexity of your segmentation, please contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support).

>[!MORELIKETHIS]
>
>[Use Segment Filters in a Smart List](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/use-segment-filters-in-a-smart-list.md)
