---
unique-page-id: 4720215
description: Learn about implementing rtp on wordpress enterprise in Marketo Engage, including implementing rtp on wordpress. Use this guide to complete your next step.
title: Implementing RTP on Wordpress Enterprise
exl-id: 61cfd3f8-0811-4352-9752-0081ce19257b
feature: Web Personalization
TQID: https://experienceleague.adobe.com/S0LvRrD1V6hkWN5L5TlnoaIqcDvXLjfm5do2-1WQTNw
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
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
# Implementing RTP on Wordpress Enterprise {#implementing-rtp-on-wordpress-enterprise}

To implement your [!UICONTROL RTP tag] please follow the installation instructions below:

1. Go to **[!UICONTROL Account Settings]**.

   a. If you have already received your JavaScript tag from Support - continue to step 3.

   ![](assets/image2014-11-30-15-3a19-3a21-3.png)

1. Under [!UICONTROL Domain], locate the relevant domain and click **[!UICONTROL Generate Tag]**.

   ![](assets/image2014-11-30-15-3a20-3a17-3.png)

1. Copy the RTP JavaScript tag.

1. Log in to your [!DNL WordPress] account as Admin User

   a. Under **[!UICONTROL Appearance]**, go to **[!UICONTROL Custom JavaScript]**.
   b. Paste the RTP Javascript tag right after the existing code.

      ![](assets/image2014-12-3-17-3a51-3a46.png)

   >[!CAUTION]
   >
   >When you paste the code EXCLUDE the following tags:
   >
   >* `<!-- RTP tag -->`
   >* `<script type='text/javascript'>`
   >* `</script>`
   >* `<!-- End of RTP tag -->`
   >
   >Insert the script itself ONLY.

1. Click **[!UICONTROL Update]**.
