---
unique-page-id: 4720145
description: Learn about implementing rtp using google tag manager in Marketo Engage, including implementing rtp using dnl google. Use this guide to complete your next step.
title: Implementing RTP using Google Tag Manager
exl-id: f7f06779-8abe-4c8c-9197-9d0c6bcfed49
feature: Web Personalization
TQID: https://experienceleague.adobe.com/XesXGBf2aDsnsbS2Ro1RLdd1EVrj-mBdCiv8C0dj8NU
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
# Implementing RTP using [!DNL Google Tag Manager] {#implementing-rtp-using-google-tag-manager}

To implement your RTP tag please follow the installation instructions below.

1. Log in to your [!DNL Google Tag Manager] account.

1. Add a new **[!UICONTROL Tag]** > **[!UICONTROL Tag Configurations]** > **[!UICONTROL Custom HTML Tag].** Call it **RTP**.

1. Log in to your **RTP account**.

1. Go to **[!UICONTROL Account Settings]**.

   a. If you've already received your JavaScript tag from Support, continue to Step 6.

   ![](assets/image2014-11-30-15-3a19-3a21.png)

1. Under [!UICONTROL Domain], locate the relevant domain and click **[!UICONTROL Generate Tag]**.

   ![](assets/image2014-11-30-15-3a20-3a17.png)

1. Copy the RTP JavaScript tag and paste it to the new **Custom HTML Tag** you created (Step 1).

1. Click **[!UICONTROL Add Rule to Fire Tag]**. Select **[!UICONTROL All Pages]**.

1. Click **[!UICONTROL Save]** and [publish the new version](https://support.google.com/tagmanager/answer/2699097?hl=en).

1. Verify that it appears on all pages, including landing pages and sub-domains.

   a. You can do this by right-clicking on your website’s page. Go to **[!UICONTROL Inspect Element]**, Search for **RTP** to locate the tag.
