---
solution: Marketo Engage
product: marketo
title: Conditional content
description: Use conditional content in your emails to dynamicly display content depending on the recipient.
level: Beginner, Intermediate
feature: Email Designer
hide: yes
hidefromtoc: yes
---
# Conditional content {#conditional-content}

Conditional content allows you dynamically control what content is seen by which audience. Use existing Segmentations to determine what a recipient sees based on predefined criteria.

>[!PREREQUISITES]
>
>Have at least one Segmentation [created](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md) and [approved](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/approve-a-segmentation.md).

## Add conditional content {#add-conditional-content}

1. Open the desired email and click **Edit email content**.

   ![](assets/conditional-content-1.png)

1. Select the content you want to be conditional (in this example, we're choosing the header image). Click the _Enable conditional content_ icon.

   ![](assets/conditional-content-2.png)

1. The box becomes orange. On the left, click the _Select condition_ icon to define your variant.

   ![](assets/conditional-content-3.png){width="700" zoomable="yes"}

1. Choose the desired segment and click **Select**.

   ![](assets/conditional-content-4.png)

1. Click the _Edit image_ icon to replace the existing image for the variant. Choose the source of your new image. In this example, we're choosing the _Images & Files_ library in our Marketo Engage subscription.

   ![](assets/conditional-content-5.png)

1. Choose the applicable image and click **Select**.

   ![](assets/conditional-content-6.png){width="600" zoomable="yes"}

1. The new image appears. It is a good idea to rename your variant to make it easier to identify.

   ![](assets/conditional-content-7.png){width="600" zoomable="yes"}

1. To add additional variants (optional), click **Add variant** and follow the same steps.

   ![](assets/conditional-content-8.png)

1. When you're done, each variant displays the content you selected.

   ![](assets/conditional-content-9.gif)

1. Recipients see content based on the rules defined in each segment. In the example above, everyone who has "football" listed in your Marketo Engage field _Favorite Sport_ will see the football image. 

>[!MORELIKETHIS]
>
>* [Define Segment Rules](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/define-segment-rules.md)
>* [Create a Custom Field in Marketo](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)
