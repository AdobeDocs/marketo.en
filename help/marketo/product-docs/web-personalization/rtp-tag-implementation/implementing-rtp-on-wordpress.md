---
unique-page-id: 4720149
description: Learn about implementing rtp on wordpress in Marketo Engage, including implementing rtp on dnl wordpress. Use this guide to complete your next step.
title: Implementing RTP on Wordpress
exl-id: f010942b-02bb-447b-a272-c4237782b2d7
feature: Web Personalization
TQID: https://experienceleague.adobe.com/5V3CEgasEJi4zrYoezh8Tt340VGHNNHaliF2wdbBLwY
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
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
# Implementing RTP on [!DNL Wordpress] {#implementing-rtp-on-wordpress}

To implement your [!UICONTROL RTP tag] please follow the installation instructions below:

1. Open up the **header.php** file of your **[!DNL WordPress] theme**.

   You can either use an FTP client to access your server or edit your theme files directly from the [!DNL WordPress] dashboard. Your file editor is located under the **[!UICONTROL Appearance]** tab in the sidebar menu.

   ![](assets/image2014-11-30-15-3a35-3a30.png)

1. In the list of template files to the right of the text editor, find **header.php** and open it.

1. Go to **[!UICONTROL Account Settings]**.

   a. If you have already received your JavaScript tag from Support - continue to step 5.

   ![](assets/image2014-11-30-15-3a19-3a21-1.png)

1. Under [!UICONTROL Domain], locate the relevant domain and click **[!UICONTROL Generate Tag]**.

   ![](assets/image2014-11-30-15-3a20-3a17-1.png)

1. Copy the RTP JavaScript tag and paste it to your website templates.

   a. Make sure it’s the first script at the header of the page - between the **`<head> </head>`** tags.

   ![](assets/image2014-11-30-15-3a36-3a31.png)

1. Click on **[!UICONTROL Update File]** for the header.php file.

1. Verify that it appears on all pages including landing pages and sub-domains.

   a. You can do this by right-clicking on you website’s page. Go to **[!UICONTROL View Page Source].** Search for **RTP** to locate the tag.
