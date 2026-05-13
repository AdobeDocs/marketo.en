---
unique-page-id: 11385053
description: Learn how to generate and place the RTP Web Personalization tag for Predictive Content. Copy it into your page head, verify coverage, and confirm the toggle stays on.
title: Deploy the JavaScript for Content-AI
exl-id: d48bfd1b-73e8-4013-88d6-8750e4ef532b
feature: Predictive Content
TQID: https://experienceleague.adobe.com/LHzl0KuIoJvZ99eFWGFE6RdDW1xRxBS4LG3XU9ujj4U
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
    internal-label: Implementation
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Deploy the JavaScript for Content-AI {#deploy-the-javascript-for-content-ai}

To use Predictive Content, you need to generate and set up your the RTP (Web Personalization) tag.

## Generate Tag {#generate-tag}

1. Login to your Predictive Content account. Go to **[!UICONTROL Account Settings]**.

   ![](assets/settings-dropdown-account-hands.png)

1. In **[!UICONTROL Domain Configuration]**, locate the relevant domain and click **[!UICONTROL Generate Tag]**.

   ![](assets/generate-tag.png)

1. Copy and paste the Web Personalization tag into the HTML of your website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Copy the Web Personalization JavaScript tag and paste it as the first script in the header of your pages, between the `<head> </head>` tags. See more detailed [implementation instructions here](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md).

1. Verify the tag appears on all pages, including landing pages and sub-domains. Check this by right-clicking on your website’s page. Go to **[!UICONTROL View Page Source]** in a web browser. Search: ‘RTP’.

1. Confirm that the Tag toggle set to **[!UICONTROL ON]**.
