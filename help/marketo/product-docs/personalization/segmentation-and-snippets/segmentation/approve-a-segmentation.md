---
unique-page-id: 2359457
description: Approve a Segmentation - Marketo Docs - Product Documentation
title: Approve a Segmentation
exl-id: c8b0fbe9-012c-47bf-8769-0167156b43d3
feature: Segmentation
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

1. Go to the **Database**.

   ![](assets/image2017-3-28-14-3a25-3a49.png)

1. In the Segmentation click **Segmentation Actions**, and then **Approve**.

   ![](assets/image2017-3-28-14-3a46-3a22.png)

   >[!NOTE]
   >
   >The Status changes to Approving with a spinning wheel ( ![](assets/image2014-9-15-15-3a31-3a43.png)) while the approval is in process.

   >[!CAUTION]
   >
   >Approval can take a few minutes to more than a day to complete, depending on the size of the database.

   Once approved, the Status changes from Approving to Approved.
   ![](assets/image2017-3-28-14-3a46-3a44.png)

   >[!TIP]
   >
   >The number of people in each segment is shown in brackets next to the segment name.

1. The **People** tab in the **Segment** now shows the final list of people for the segment.

   ![](assets/image2017-3-28-14-3a47-3a10.png)

>[!CAUTION]
>
>The total number of segments you can create in a segmentation depends on the number and type of filters used and also on how complex the logic of your segments is. While you can create up to 100 segments using standard fields, using other types of filters can increase the complexity, and your segmentation might fail to approve. Some examples are: custom fields, member of list, lead owner fields, and revenue stages.
>
>If you get an error message during approval and require assistance in reducing the complexity of your segmentation, please contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support).

>[!MORELIKETHIS]
>
>[Use Segment Filters in a Smart List](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/use-segment-filters-in-a-smart-list.md)
