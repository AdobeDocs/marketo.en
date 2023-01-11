---
unique-page-id: 4720810
description: Personalized Remarketing in Google - Marketo Docs - Product Documentation
title: Personalized Remarketing in Google
exl-id: cc733f43-161d-41e4-afdf-8b5217700810
---
# Personalized Remarketing in Google {#personalized-remarketing-in-google}

Personalized Remarketing lets you re-engage with your users using RTP data and the power of Google Analytics with the reach of the Google Display Network.

>[!PREREQUISITES]
>
>* Complete the [Retargeting with [!DNL Web Personalization] Data](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md) configuration
>* Review [Remarketing with Google Analytics Help](https://support.google.com/analytics/topic/2611283?hl=en&ref_topic=3413645) documentation.

## Creating a Remarketing Audience in Google {#creating-a-remarketing-audience-in-google}

1. Log in to your Google Analytics. Click **[!UICONTROL Admin]**, **[!UICONTROL Account]**, **[!UICONTROL Property]**. Click on **[!UICONTROL Audience Definitions]** and **[!UICONTROL Audiences]**.

   ![](assets/remarketing-ga-screenshots.jpg)

1. Click **[!UICONTROL +New Audience]**.

   ![](assets/image2015-1-15-17-3a26-3a40.png)

1. **[!UICONTROL Link Configuration]**: Link to your [!DNL Google Adwords] account. **[!UICONTROL Define Audience]**: Click **[!UICONTROL Create New]**.

   ![](assets/image2015-1-15-17-3a32-3a4.png)

1. In the Audience Builder, Click on **[!UICONTROL Sequences]** and **[!UICONTROL Find the RTP Data]** under [!UICONTROL Custom Dimensions], [!UICONTROL [!]UICONTROL Custom Variables], [!UICONTROL Events].

>[!TIP]
>
>How to find the RTP data in Analytics to build your audience?
>
>In Google Analytics:
>
>* Custom Variables: Organization, Industry
>* Event Category: Segment, Insightera-CTA, RTP-Remarketing
>* Event Label: Segment Name, Campaign Name, Segmented Audience Name  
>
>In Google Universal Analytics:
>
>* Custom Dimensions: Organization, Industry, Category (Fortune 500,1000, Global 2000), Group (Enterprise, SMB), ABM List (Named Account List)
>* Event Category: RTP-Segment, RTP-Campaign RTP-Remarketing
>* Event Label: Segment Name, Campaign Name, Segmented Audience Name

**Example of Remarketing Audience from RTP Segmented Audience Data**

1. Click **[!UICONTROL Sequences].**
1. Select **[!UICONTROL Event Label].**
1. Enter **[!UICONTROL Name of Segmented Audience]** (as it appears in RTP).
1. Click **[!UICONTROL Apply]**.

![](assets/image2015-2-10-14-3a51-3a43.png)   

**Example of Audience from RTP Industry Data** 

![](assets/image2015-1-15-17-3a36-3a5.png)

1. Click **[!UICONTROL Sequences]**.
1. Select **[!UICONTROL RTP-Industry]**.
1. Enter **Name of Industry** (eg. [!UICONTROL Financial Services], [!UICONTROL Education]...).
1. Click **[!UICONTROL Apply]**.
1. Enter an **[!UICONTROL Audience Name]**. Click **[!UICONTROL Save]**.

![](assets/image2015-1-15-18-3a29-3a16.png)

## Create a Remarketing Ad Campaign in [!DNL Google Adwords] {#create-a-remarketing-ad-campaign-in-google-adwords}

1. Login to **[!DNL Google Adwords]**. Click on **[!UICONTROL Campaigns]**, select **[!UICONTROL Display Network only]**.

   ![](assets/image2015-1-15-18-3a31-3a58.png)

1. Enter **[!UICONTROL Campaign Name]**, Select **[!UICONTROL Type Remarketing].**

   ![](assets/image2015-1-15-18-3a35-3a7.png)

1. Enter **[!UICONTROL Ad Group Name],** enter **[!UICONTROL Enhanced CPC]**, Select **[!UICONTROL Remarketing List]**.

   ![](assets/image2015-1-15-18-3a51-3a57.png)

1. Click **[!UICONTROL Save]** and continue.
1. Add your Image or Text Ad and start your remarketing campaign.

   ![](assets/image2015-1-15-18-3a47-3a21.png)

>[!MORELIKETHIS]
>
>* [Retargeting with [!DNL Web Personalization] Data](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [Personalized Remarketing in [!DNL Facebook]](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)
