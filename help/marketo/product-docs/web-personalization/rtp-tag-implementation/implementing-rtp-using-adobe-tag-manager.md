---
unique-page-id: 4720218
description: Implementing RTP using Adobe Tag Manager - Marketo Docs - Product Documentation
title: Implementing RTP using Adobe Tag Manager
exl-id: 5a938d02-6b09-45d5-94b0-dbb50b5d62b6
---
# Implementing RTP using Adobe Tag Manager {#implementing-rtp-using-adobe-tag-manager}

To implement your [!UICONTROL RTP tag] please follow the installation instructions below:

1. Log in to your RTP account.

1. Go to **[!UICONTROL Account Settings]**.

   a. If you have already received your JavaScript tag from Support - continue to step 4.

   ![](assets/image2014-11-30-15-3a19-3a21-4.png)

1. Under [!UICONTROL Domain], locate the relevant domain and click **[!UICONTROL Generate Tag]**.  

   ![](assets/image2014-11-30-15-3a20-3a17-4.png)

1. Login to your [!DNL Dynamic Tag Manager] account ([https://dtm.adobe.com/sign_in](https://dtm.adobe.com/sign_in)).

1. Go to **[!UICONTROL Dashboard].** Click on the relevant web property.

   ![](assets/image2014-12-3-17-3a58-3a17.png)

1. Go to **[!UICONTROL Rules]**, click **[!UICONTROL Create New Rule]**.

1. Fill out the following

    1. [!UICONTROL Name]: **Marketo RTP**
    1. [!UICONTROL Conditions] (collapse) : Trigger rule at  - **[!UICONTROL Top of Page]**
    1. [!UICONTROL Javascript] (collapse): click **[!UICONTROL Add New Script]**

   ![](assets/image2014-12-3-17-3a59-3a40.png)

1. Call the new tag: **Marketo RTP Tag**

1. Remove the following code from the [!UICONTROL RTP tag]

   * `<script type='text/javascript'>`
   * `</script>`

1. Paste the RTP JavaScript tag.

   ![](assets/image2014-12-3-18-3a3-3a45.png)

   >[!CAUTION]
   >
   >Make sure you remove all tags and leave only the script itself (no `<script type='text/javascript'>` , `</script>` )

1. Click **[!UICONTROL Save Code]** in the script editor and **[!UICONTROL Save Rule]** in the rule editor.

1. In the Rules panel, locate the Marketo RTP page load rule and within the **[!UICONTROL Actions]** dropdown select **[!UICONTROL Activate Rules]**.

   ![](assets/image2014-12-3-18-3a4-3a14.png)

1. **[!UICONTROL Verify]** that it appears on all pages including landing pages and sub-domains.

    You can do it by right-clicking on your website’s pages. Go to **[!UICONTROL Inspect Element]**, click on **[!UICONTROL Network]**, Search: **RTP**.
