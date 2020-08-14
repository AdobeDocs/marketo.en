---
unique-page-id: 7504238
description: Custom RTP Dashboards in Google Universal Analytics - Marketo Docs - Product Documentation
title: Custom RTP Dashboards in Google Universal Analytics
---

# Custom RTP Dashboards in Google Universal Analytics {#custom-rtp-dashboards-in-google-universal-analytics}

>[!NOTE]
>
>**Prerequisites**
>
>[Integrate RTP with Google Universal Analytics](integrate-rtp-with-google-universal-analytics.md)

This post explains how to setup RTP dashboards in Google Universal Analytics (GUA).  The data sent from RTP to GUA can be set up as two separate custom dashboards called:

* RTP B2B
* RTP Engagement

## Setting up a Custom Dashboard {#setting-up-a-custom-dashboard}

1. Login to Google Analytics. Click on **Reporting **in the top menu. Click **Dashboards **and **+New Custom Dashboard.** 
   ![](assets/image2015-3-22-16-3a41-3a29.png)

1. Select **Blank Canvas**, add a **Dashboard Name** and click **Create Dashboard**.

1. Click **Add Widget** to create a new widget.  
   ![](assets/image2015-3-22-16-3a46-3a48.png)

## RTP B2B Dashboard {#rtp-b-b-dashboard}

This dashboard allows users to analyze their website performance from a B2B perspective.

It provides information like visit source and onsite behavior by industry, revenue, size, Account-Based lists, and target segments.

The dashboard consists of 3 columns

* Traffic source
* Segmentation
* Firmographic drill down

1. Create a new dashboard called **RTP B2B Dashboard **and define the following widgets:

![](assets/image2015-3-22-16-3a50-3a3.png)

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Column 1 - Traffic Sources 
    </div></th> 
   <th> 
    <div> <strong>Column 2 - Segmentation</strong> 
    </div></th> 
   <th> 
    <div> <strong>Column 3 - Firmographic Drill down</strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul> 
     <li>Name: Sessions by Segments and Channels</li> 
     <li>Widget type:&nbsp;Bar<br></li> 
     <li>Create a bar chart showing:&nbsp;Session</li> 
     <li>Grouped by: Event label</li> 
     <li>Pivot by: Default Channel Grouping</li> 
     <li>Filter: <br>Only Show | Event Category (containing) RTP-Segments</li> 
    </ul><p><img width="300" src="assets/image2015-3-23-11-3a32-3a13.png" data-linked-resource-id="7504247" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Name: # of RTP Segmented Users</li> 
     <li>Type: 2.1 Metric</li> 
     <li>Show the following metric:&nbsp;Users<br></li> 
     <li>Filter: <br>Only Show | Event Category (containing) RTP-Segments</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a6.png" data-linked-resource-id="7504249" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Name: Sessions by Industry</li> 
     <li>Type: Pie<br></li> 
     <li>Create a pie chart showing:&nbsp;Sessions</li> 
     <li>Grouped by:&nbsp;RTP-Industry</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a27.png" data-linked-resource-id="7504250" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <th> 
    <ul> 
     <li><strong>Name: Sessions by Industry and Channels</strong></li> 
     <li><strong>Widget type:&nbsp;Bar</strong></li> 
     <li><strong>Create a bar chart showing:&nbsp;Session</strong></li> 
     <li><strong>Grouped by: RTP-Industry</strong></li> 
     <li><strong>Pivot by: Default Channel Grouping</strong><br><img width="300" src="assets/image2015-3-23-11-3a33-3a52.png" data-linked-resource-id="7504252" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></li> 
    </ul></th> 
   <th> 
    <ul> 
     <li><strong>Name: Segmented Sessions by Country</strong></li> 
     <li><strong>Type: Geomap</strong></li> 
     <li><strong>Plot selected metric:&nbsp;Country | Sessions</strong></li> 
     <li><strong>Select a region:&nbsp;The World</strong></li> 
     <li><strong>Filter: Only Show | Event Category (containing) RTP-Segments</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a34-3a18.png" data-linked-resource-id="7504253" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li><strong>Name: Sessions by RTP Category</strong></li> 
     <li><strong>Type: Pie</strong></li> 
     <li><strong>Create a pie chart showing:&nbsp;Sessions</strong></li> 
     <li><strong>Grouped by:&nbsp;RTP-Category</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a35-3a1.png" data-linked-resource-id="7504254" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>Name: Top Target Segments</li> 
     <li>Type: Bar</li> 
     <li>Create a bar chart showing:&nbsp;Users</li> 
     <li>Grouped by:&nbsp;Event Action</li> 
     <li>Filter: Only Show | Event Category (containing) RTP-Segments</li> 
    </ul><p><img width="350" src="assets/add-a-widget.png" data-linked-resource-id="11382874" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li>Name: Sessions by RTP-Groups</li> 
     <li>Type: Bar<br></li> 
     <li>Create a bar chart showing:&nbsp;Sessions</li> 
     <li>Grouped by:&nbsp;RTP-Group</li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a35-3a54.png" data-linked-resource-id="7504256" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>Name: Sessions &amp; Goals by Top Segments</li> 
     <li>Type: Table<br></li> 
     <li>Display the following columns:&nbsp;<br>Event Label | Sessions | Goal Conversion Rate</li> 
     <li>Filter: <br>Only Show | Event Category (containing) RTP-Segments</li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a36-3a15.png" data-linked-resource-id="7504257" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
   <th> </th> 
  </tr> 
 </tbody> 
</table>

## RTP Engagement Dashboard {#rtp-engagement-dashboard}

This dashboard allows users to analyze their RTP campaign performance and recommendation engine engagements. It provides comparison of avg. session duration and pages per session between:

*

    * Unengaged
    * Engaged (impressions and clicks on a personalized campaign)
    * Clicks on the Recommendation Engine and top recommended content

Create a new dashboard called **RTP Engagement Dashboard** and define the following widgets:

![](assets/image2015-3-22-17-3a7-3a19.png)

<table> 
 <thead> 
  <tr> 
   <th> 
    <div> <strong>Column 1 Campaigns Exposure</strong> 
    </div></th> 
   <th> 
    <div> <strong>Column 2 Campaigns Clickthrough</strong> 
    </div></th> 
   <th> 
    <div> <strong>Column 3 Recommendation Engine</strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul> 
     <li>Name: <strong>Total CTA (Engagement)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li>Show the following metric:&nbsp;<strong>Total Events</strong></li> 
     <li>Filters:<br><strong>[only show] Event Category (contains): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matcing): Impression</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a37-3a55.png" data-linked-resource-id="7504259" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul> 
     <li>Name: <strong>Total CTA (Clickthrough)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li>Show the following metric:&nbsp;<strong>Total Events</strong></li> 
     <li>Filters:<br><strong>[only show] Event Category (contains): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): Clicks</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a38-3a12.png" data-linked-resource-id="7504261" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul> 
     <li>Name: <strong>CRE - Total Clicks</strong></li> 
     <li>Type: <strong>2.1 Metric</strong><br></li> 
     <li>Show the following metric:&nbsp;<strong>Pageviews</strong></li> 
     <li>Filter:&nbsp;<strong>[only show] Page (containing): rcmd</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a38-3a30.png" data-linked-resource-id="7504262" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>Avg. Session Duration (Engagement)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li>Show the following metric:&nbsp;<strong>Avg. Session Duration</strong></li> 
     <li>Filters:<br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): impression</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a41-3a21.png" data-linked-resource-id="7504264" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>Avg. Session Duration (Clickthrough)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li>Show the following metric:&nbsp;<strong>Avg. Session Duration</strong></li> 
     <li>Filters:<br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): clicks</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a41-3a37.png" data-linked-resource-id="7504265" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>CRE - Top Recommended Content</strong></li> 
     <li>Type: <strong>Table</strong><br></li> 
     <li>Display the following columns:&nbsp;<br><strong>Page Title | Pageviews</strong><br></li> 
     <li>Filters:<br>Filter:&nbsp;<strong>[only show] Page (containing): rcmd</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a41-3a51.png" data-linked-resource-id="7504266" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Name: <strong>Pages / Session (Engagement)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li>Show the following metric:&nbsp;<strong>Pages / Session</strong></li> 
     <li>Filters:<br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong></li> 
     <li><strong>[only show] Event Action (exactly matching): impression</strong></li> 
     <li><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a10.png" data-linked-resource-id="7504267" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Name: <strong>Pages / Session (Clickthrough)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li>Show the following metric:&nbsp;<strong>Pages / Session</strong></li> 
     <li>Filters:<br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong></li> 
     <li><strong>[only show] Event Action (exactly matching): clicks</strong></li> 
     <li><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a42-3a32.png" data-linked-resource-id="7504268" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Name: <strong>Impressions by CTA</strong></li> 
     <li>Type: <strong>Table</strong></li> 
     <li>Display the following columns:&nbsp;<strong>Event Label | Total Events | Users</strong></li> 
     <li>Filters:<br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): impression</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a48.png" data-linked-resource-id="7504269" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Name: <strong>Clickthrough by CTA</strong></li> 
     <li>Type: <strong>Table</strong></li> 
     <li>Display the following columns:&nbsp;<strong>Event Label | Total Events | Users</strong></li> 
     <li>Filters:<br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): clicks</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a43-3a4.png" data-linked-resource-id="7504270" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> </td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>**Related Articles**
>
>[Integrate RTP with Google Universal Analytics](integrate-rtp-with-google-universal-analytics.md)
>
>[Custom RTP Reports in Google Universal Analytics](custom-rtp-reports-in-google-universal-analytics.md)

