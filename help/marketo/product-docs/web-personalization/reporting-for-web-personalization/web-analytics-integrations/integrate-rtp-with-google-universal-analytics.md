---
unique-page-id: 4720125
description: Integrate RTP with Google Universal Analytics - Marketo Docs - Product Documentation
title: Integrate RTP with Google Universal Analytics
exl-id: e8fc8730-c91d-44ad-8843-aa5b38f1ebd1
---
# Integrate RTP with [!DNL Google Universal Analytics] {#integrate-rtp-with-google-universal-analytics}

## Intro {#intro}

Leverage [!DNL Google Universal Analytics] (GUA) with Marketo Real-Time Personalization's (RTP) firmographic and personalization data to better measure and analyze your online marketing efforts.

This post explains how to set up and integrate the Marketo Real-Time Personalization (RTP) platform with [!DNL Google Universal Analytics] (GUA) accounts. RTP data can be appended to your GUA account allowing you to view and see the performance of organizations, industries, firmographics and RTP segments visiting your website.

**[!DNL Google Universal Analytics]**

[!DNL Google Universal Analytics] with RTP’s data provides you a better understanding of how B2B users interact with your online content and help measure and get better results from your personalization campaigns. [Read more about [!DNL Google Universal Analytics]](https://support.google.com/analytics/answer/2790010/?hl=en&authuser=1).

>[!NOTE]
>
>**For Google Tag Manager Users Only**
>
>No coding or special configuration needs to be done. Make sure you complete the following checklist:
>
>* RTP dimensions are created in [!DNL Google Universal Analytics]
>* [RTP tag is properly installed in Google Tag Manager](https://docs.marketo.com/display/public/DOCS/Implementing+RTP+using+Google+Tag+Manager)
>* [!DNL Google Universal Analytics] Integration is enabled in the RTP's Account Settings
>* [[!DNL Google Universal Analytics] tag is properly configured in Google Tag Manager](https://support.google.com/tagmanager/answer/6107124?hl=en)
>* [Google Tag Manager tag is properly installed your website](https://developers.google.com/tag-manager/quickstart)

## Set up Custom Dimensions in GUA {#set-up-custom-dimensions-in-gua}

1. In Google Analytics,

    1. Go to **[!UICONTROL Admin]**
    1. Select the **[!UICONTROL Account].**
    1. Select the **[!UICONTROL Property].**
    1. Select **[!UICONTROL Custom Definitions]** and **[!UICONTROL Custom Dimensions]**.
       ![](assets/image2014-11-29-11-3a2-3a32.png)

1. Add a new custom dimension. Click **[!UICONTROL +New Custom Dimension]**

   ![](assets/image2014-11-29-11-3a8-3a16.png)

1. Add the following **[!UICONTROL Custom Dimensions]:**

<table> 
 <tbody> 
  <tr> 
   <td><p><strong>Custom Dimension Name</strong></p></td> 
   <td><p><strong>Scope</strong></p></td> 
   <td><p><strong>Active</strong></p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-Organization</strong></p></td> 
   <td><p>Session</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-Industry</strong></p></td> 
   <td><p>Session</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-Category</strong></p></td> 
   <td><p>Session</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-Group</strong></p></td> 
   <td><p>Session</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
 </tbody> 
</table>

   >[!NOTE]
   >
   >**Custom Dimension Names** must be exactly as defined in the table above (otherwise custom RTP dashboards and reports in GUA won’t display correctly)

1. Add the **[!UICONTROL Name]**. Select the Scope as **[!UICONTROL Session]**. Click **[!UICONTROL Create]**.

   ![](assets/image2014-11-29-11-3a12-3a51.png)

Your Custom Dimension list should look like this.

![](assets/image2014-11-29-11-36-50-version-2.png)

Once you've activated the Custom Dimensions in GUA, go to the RTP platform to enable these dimensions within RTP.

## Activate the GUA integration in your RTP account {#activate-the-gua-integration-in-your-rtp-account}

1. In the RTP platform, go to **[!UICONTROL Account Settings].**

   ![](assets/image2014-11-29-11-3a27-3a7.png)

1. Under **[!UICONTROL Account Settings]**, click **[!UICONTROL Domain]**.
1. Under **[!UICONTROL Analytics]**, click **[!UICONTROL Google Universal Analytics]**.
1. Turn **[!UICONTROL On]** the relevant Custom Dimensions and Events to append this data from RTP to [!DNL Google Universal Analytics].
1. Enter the **[!UICONTROL Index number]** of the dimension aligned with the index number in GUA.
1. Click **[!UICONTROL Save]**.

![](assets/image2014-11-29-11-31-23-version-2.png)

>[!NOTE]
>
>The Index Number for the Custom Dimension can be found in GUA under Custom Dimensions.
>
>Example: RTP-Industry Index Number equals 1, RTP-Organization Index Number equals 2.

## Remove Old Dashboards in Google Analytics {#remove-old-dashboards-in-google-analytics}

1. In Google Analytics. Go to **[!UICONTROL Reporting].**
1. Click on **[!UICONTROL Dashboards].**
1. Select a **[!UICONTROL Dashboard]** (RTP B2B or RTP Performance)
1. Click **[!UICONTROL Delete Dashboard]**.

![](assets/image2014-11-29-11-3a42-3a55.png)
