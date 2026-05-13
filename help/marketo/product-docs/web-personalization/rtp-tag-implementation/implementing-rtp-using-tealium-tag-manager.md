---
unique-page-id: 9437340
description: Learn about implementing rtp using tealium tag manager in Marketo Engage, including implementing rtp using dnl. Use this guide to complete your next step.
title: Implementing RTP using Tealium Tag Manager
exl-id: 7a099184-625c-46b2-a741-3bcdad0a238e
feature: Web Personalization
TQID: https://experienceleague.adobe.com/zMs2Dii5RERdH8tKb86a6EhxXUx2IpbZkDOCklUvvY4
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
    internal-label: Implementation
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Implementing RTP using [!DNL Tealium] Tag Manager {#implementing-rtp-using-tealium-tag-manager}

To implement your RTP tag please follow the installation instructions below.

1. Log in to your [!DNL Tealium] Tag Manager account.

1. Navigate to the [!UICONTROL Tags] tab and add the [!UICONTROL Tealium Custom Container Tag], located under the [!UICONTROL Misc] tab of the Tags marketplace.

1. In the [!UICONTROL Title field], enter **Marketo RTP** and click **[!UICONTROL Finish]**.

1. Save your changes.

   >[!NOTE]
   >
   >There's no need to publish the new container yet.

1. After the profile is saved, click your name/email address in the upper right corner of the Tealium iQ console.

1. On the [!UICONTROL Admin] menu, click **[!UICONTROL Manage Templates]** under [!UICONTROL Account Admin].

1. Select **[!UICONTROL Tealium Custom Container]: Marketo RTP** from the drop-down list to open the Tag template.

1. Log in to your RTP account.

1. Go to [!UICONTROL Account Settings].

   >[!NOTE]
   >
   >If you've already received your JavaScript tag from Support, continue to Step 11.

1. Under Domain, locate the relevant domain and click **[!UICONTROL Generate Tag]**.

1. Copy the RTP JavaScript tag and paste it between [!UICONTROL Start Tag Library Code] and [!UICONTROL End Tag Library Code] in your Tealium Profile Template.

   >[!NOTE]
   >
   >**Important Steps**
   >
   >Remove the `<!-- RTP tag -->` and `<!-- End of RTP tag -->` tags from the code you place in this file.
   >
   >Remove any `<script type='text/javascript'>` and `</script>` tags from the code you place in this file.

1. Click **[!UICONTROL Save Profile Template]** and publish your new profile.
