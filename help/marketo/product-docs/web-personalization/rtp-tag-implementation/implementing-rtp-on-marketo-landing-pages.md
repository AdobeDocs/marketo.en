---
unique-page-id: 4720151
description: Learn about implementing rtp on marketo landing pages in Marketo Engage, including implementing rtp on marketo. Use this guide to complete your next step.
title: Implementing RTP on Marketo Landing Pages
exl-id: fd19c3ad-d3f6-44a3-9f7a-d518e2d3f02a
feature: Web Personalization
TQID: https://experienceleague.adobe.com/scyZfbFBloPu8JRfJiMjm62AFCHM7WCxaats3qssq2A
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
    internal-label: Implementation
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Implementing RTP on Marketo Landing Pages {#implementing-rtp-on-marketo-landing-pages}

To implement your [!UICONTROL RTP tag] please follow the installation instructions below:

1. Go to the **[!UICONTROL Design Studio].** Open the item you want to edit. Select **[!UICONTROL Template Actions]**, select **[!UICONTROL Edit Draft]**.

   ![](assets/image2015-4-26-18-3a27-3a4.png)

1. Make your template changes on the **HTML Source** tab.

   ![](assets/image2015-4-26-18-3a28-3a17.png)

1. In your RTP account, go to **[!UICONTROL Account Settings]**.

   a. If you have already received your JavaScript tag from Support - continue to step 5.

   ![](assets/image2014-11-30-15-3a19-3a21-2.png)

1. Under [!UICONTROL Domain], locate the relevant domain and click **[!UICONTROL Generate Tag]**.

   ![](assets/image2015-4-26-18-3a27-3a35.png)

   ![](assets/image2014-11-30-15-3a20-3a17-2.png)

1. Copy the RTP JavaScript tag and paste it to all your landing page templates between the **`<head> </head>`** tags.

1. Click **[!UICONTROL Save]** and **[!UICONTROL Close]** the window.

1. Back in the **[!UICONTROL Design Studio]**, approve the landing page from **[!UICONTROL Template Actions]**, click **[!UICONTROL Approve]**.

   ![](assets/image2015-4-26-18-3a28-3a30.png)

1. Finally, you’ll need to **re-approve** any landing pages using that template for the template changes to take effect. You can re-approve them all at once from the main [!UICONTROL Landing Pages] section.

   ![](assets/image2015-4-26-18-3a28-3a49.png)

1. Verify that it appears on all pages including landing pages and sub-domains.

   You can do this by right-clicking on you website’s page. Go to **[!UICONTROL View Page Source].** Search for **[!UICONTROL RTP]** to locate the tag.
