---
unique-page-id: 2949158
description: Integrate RTP with Google Analytics - Marketo Docs - Product Documentation
title: Integrate RTP with Google Analytics
---

# Integrate RTP with Google Analytics {#integrate-rtp-with-google-analytics}

Integrate RTP with Google Analytics - Marketo Docs - Product Documentation

### What's in this article? {#what-s-in-this-article}

[Introduction](#integratertpwithgoogleanalytics-introduction)  
[Channel Report](#integratertpwithgoogleanalytics-channelreport)  
[Behavioral Flow](#integratertpwithgoogleanalytics-behavioralflow)  
[RTP Performance](#integratertpwithgoogleanalytics-rtpperformance)  
[Setting up RTP with Google Analytics](#integratertpwithgoogleanalytics-settinguprtpwithgoogleanalytics)  
[Setting up Google Analytics Reports with RTP Data](#integratertpwithgoogleanalytics-settingupgoogleanalyticsreportswithrtpdata)

>[!NOTE]
>
>Universal Analytics is now the operating standard and all properties in Google have been upgraded to Universal Analytics.
>
>This article shows how to use the old Google Standard Analytics, but we recommend that you switch over to Universal Analytics.
>
>If you’re not already using the [analytics.js tracking code](https://developers.google.com/analytics/devguides/collection/analyticsjs/), Google strongly recommends you retag your site to use it. The following are being deprecated by Google:
>
>* ga.js
>* urchin.js
>* WAP/server-side snippets
>* YT / MO
>* Custom variables
>* User defined variables
>
>`See how to integrate` [Web Personalization with Universal Analytics](integrate-rtp-with-google-universal-analytics.md)

#### Introduction {#integratertpwithgoogleanalytics-introduction}

Analyze your web analytics from a new angle using direct data flow from Marketo Real-Time Personalization (RTP) to your Google Analytics (GA) account. Measure your web visits in GA according to organizations, industries and RTP campaigns. View metrics such as the types of industries or RTP segments in GA and how they perform and generate leads according to different traffic sources (social, paid, organic), analyzing click through rates on campaigns, and measuring the impact personalization campaigns have on your website. Leverage this ability to gain the maximum benefit from your RTP account

**RTP Audience Analytics**

With the integration, you have a new dimension in your GA account. RTP automatically enhances your dashboards with:

1. Organizations and industries
1. Customized segments in RTP
1. Account-Based Marketing lists  

Focus on your key B2B prospects. Analyze channels by targeted industries and segments.

#### Channel Report {#integratertpwithgoogleanalytics-channelreport}

![](assets/image2014-11-28-16-3a39-3a28.png)

The RTP B2B Dashboard helps you understand the breakdown of your visitors according to verticals and RTP segmentation. You can see your visitor performance according to the finance industry and according to different marketing campaigns (paid, organic, social). The dashboard also provides a high-level overview of how your RTP segments are performing and drills down to show the top organizations visiting your site.

#### Behavioral Flow {#integratertpwithgoogleanalytics-behavioralflow}

![](assets/image2014-11-28-16-3a40-3a43.png)

The Behavior flow report (see image) visualizes the path visitors travel from one Page or Event to the next. The image example shows the path of all visitors from the financial sector. This report can help you discover what content keeps visitors engaged with your site.

#### RTP Performance {#integratertpwithgoogleanalytics-rtpperformance}

Measure your RTP campaigns and correlate them with your overall site average. Learn how these campaigns affect your website metrics and use this data to focus your personalization efforts on the right targets. Generate customized reports to better understand how your personalization campaigns are performing.

![](assets/image2014-11-28-16-3a47-3a0.png)

#### Setting up RTP with Google Analytics {#integratertpwithgoogleanalytics-settinguprtpwithgoogleanalytics}

1. Add the email [ `[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#700204005e171142301d11021b15041f5e131f1d) `, as a Read & Analyze user to your GA account. For more details, see [here](https://support.google.com/analytics/answer/2884495?hl=en).`
1. In your RTP account. Go to **Account Settings**.

   ![](assets/image2014-11-28-16-3a54-3a40.png)

1. Under **Account Settings**, **Domain** and **Analytics**
1. Click on** Google Analytics.**
1. Turn on the relevant **Custom Variables** and **Events** to append this data from RTP to Google Analytics.
1. Enter the **Slot** number to send custom variable data (default is 1,2).

![](assets/image2014-11-28-17-3a0-3a17.png)

Click **SAVE**.

>[!NOTE]
>
>In order to send segment data to GA, under the [Edit Segment page](../../../../../welcome-to-marketo-docs/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md) in the RTP platform, select the checkbox **Send Event to Google Analytics on Segment Match**.

#### Setting up Google Analytics Reports with RTP Data {#integratertpwithgoogleanalytics-settingupgoogleanalyticsreportswithrtpdata}

In Google Analytics you can use dashboards, GA segmentation, and reporting to view your RTP data:

* [Dashboards](https://support.google.com/analytics/answer/1068216?hl=en) provide an overview of the website performance.
* `A GA Segment is intended to filter visitors in the GA interface and view the traffic per segment. See how to build a segment` [here](https://support.google.com/analytics/answer/3124493?hl=en) `.`

* `Creating` [customized reports](https://support.google.com/analytics/answer/1033013?hl=en) `to view and/or setup scheduled emails. See under Customization > New Custom Report.`

