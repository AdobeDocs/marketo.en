---
unique-page-id: 2950617
description: Learn how to use dynamic content in an email. Show different content to different segments based on rules and attributes.
title: Using Dynamic Content in an Email
exl-id: a1178f76-6760-4a4a-9510-f129ee6a9032
feature: Email Editor
TQID: https://experienceleague.adobe.com/NzTat-p-dgq9wtHv-hyJJzAwud27aOBvVTIS1Tn0lnc
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
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
# Using Dynamic Content in an Email {#using-dynamic-content-in-an-email}

>[!PREREQUISITES]
>
>[Create a Segmentation](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)

Use Dynamic Content in Emails to send your leads targeted information.

>[!NOTE]
>
>The use of variables within dynamic content in an email is only supported when using Trigger Campaigns. It is **not** supported when using Batch Campaigns.

## Add Segmentation {#add-segmentation}

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/login-marketing-activities.png)

1. Select your email and click **[!UICONTROL Edit Draft]**.

   ![](assets/1.2.png)

1. In this example we're making the Subject Line dynamic. Click in the [!UICONTROL Subject] field, then click the **Make Dynamic** button.

   ![](assets/1.3.png)

   >[!NOTE]
   >
   >You can also make an element inside the email dynamic. To do this, select the area, click the gear icon, and select **Make Dynamic** (or [Replace with Snippet](/help/marketo/product-docs/personalization/segmentation-and-snippets/snippets/create-a-snippet.md), depending on what you are doing).

1. Enter the Segmentation name, select it, and click **[!UICONTROL Save]**.

   ![](assets/1.4.png)

   Your segmentation and its segments appear under the [!UICONTROL Dynamic] tab on the right.

   ![](assets/1.5.png)

## Apply Dynamic Content {#apply-dynamic-content}

>[!CAUTION]
>
>The number of dynamic content elements allowed is not unlimited. While there is no specific number limit (it can vary based on the combination of content), overusing dynamic content can negatively affect the email's performance. We recommend keeping the amount of dynamic content elements used to under 20 per email.

1. Click your segments and add your subject line.

![](assets/2.1.png)

1. Repeat for each segment.

   ![](assets/2.2.png)

>[!TIP]
>
>Create a default email before applying content to the various segments.

>[!CAUTION]
>
>Changes to Default segment content block gets applied to all segments.

Sweet! Now you can send flexible emails to your target audience.

>[!MORELIKETHIS]
>
>* [Preview an Email with Dynamic Content](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/preview-an-email-with-dynamic-content.md)
>* [Use Dynamic Content in a Landing Page](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/use-dynamic-content-in-a-free-form-landing-page.md)
