---
unique-page-id: 9437340
description: Implementing RTP using Tealium Tag Manager - Marketo Docs - Product Documentation
title: Implementing RTP using Tealium Tag Manager
exl-id: 7a099184-625c-46b2-a741-3bcdad0a238e
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
