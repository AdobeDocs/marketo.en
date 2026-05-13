---
unique-page-id: 4719332
description: Learn about deploy the rtp javascript in Marketo Engage, including deploy the rtp javascript. Use this guide to complete your next step.
title: Deploy the RTP JavaScript
exl-id: ef96a7f4-3942-4325-bb0f-7647ff2b33b6
feature: Web Personalization
TQID: https://experienceleague.adobe.com/XUylNa8clUib-aMhpAR8fjeu4pHRA8KSQydSH1AVxF8
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
# Deploy the RTP JavaScript {#deploy-the-rtp-javascript}

To generate and set up your RTP tag please follow the installation instructions below

## [!UICONTROL Generate Tag] {#generate-tag}

1. Log in to your RTP account. Go to **[!UICONTROL Account Settings]**.

   ![](assets/image2014-12-1-23-3a3-3a12.png)

1. In **[!UICONTROL Domain]** and **[!UICONTROL Domain Configuration]**, locate the relevant domain and click **[!UICONTROL Generate Tag]**.

   ![](assets/image2014-12-1-23-3a5-3a35.png)

1. Copy and paste the Web Personalization (RTP) tag into your website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Copy the RTP JavaScript tag and paste it as the first script in the header of your pages - between the `<head> </head>` tags.

   Make sure the tag appears on all pages including landing pages and sub-domains. Check this by right-clicking on your website’s page. Go to View Page Source in a web browser. Search: ‘RTP’.

1. [!UICONTROL Tag] toggle set to **[!UICONTROL ON]**.

   Confirm that the [!UICONTROL Tag] toggle is set to [!UICONTROL ON]. You should start seeing data flow into the Organization's tab.

   You are now set up with the RTP tag and ready to start [creating segments](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md) and real-time campaigns!

1. Verify tag is on all pages.
