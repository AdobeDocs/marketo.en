---
unique-page-id: 7504238
description: Custom RTP Dashboards in Google Universal Analytics - Marketo Docs - Product Documentation
title: Custom RTP Dashboards in Google Universal Analytics
exl-id: 712c71b6-74eb-4743-9ca8-50c912278e62
---
# Custom RTP Dashboards in Google Universal Analytics {#custom-rtp-dashboards-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[Integrate RTP with Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

This post explains how to setup RTP dashboards in Google Universal Analytics (GUA). The data sent from RTP to GUA can be set up as two separate custom dashboards called:

* RTP B2B
* RTP Engagement

## Setting up a Custom Dashboard {#setting-up-a-custom-dashboard}

1. Log in to Google Analytics. Click on **[!UICONTROL Reporting]** in the top menu. Click **[!UICONTROL Dashboards]** and **[!UICONTROL New Dashboard]**.

   ![](assets/image2015-3-22-16-3a41-3a29.png)

1. Select **Blank Canvas**, add a **Dashboard Name** and click **[!UICONTROL Create Dashboard]**.

1. Click **[!UICONTROL Add Widget]** to create a new widget.

   ![](assets/image2015-3-22-16-3a46-3a48.png)

## RTP B2B Dashboard {#rtp-b-b-dashboard}

This dashboard allows users to analyze their website performance from a B2B perspective.

It provides information like visit source and onsite behavior by industry, revenue, size, Account-Based lists, and target segments.

The dashboard consists of 3 columns

* Traffic source
* Segmentation
* Firmographic drill down

1. Create a new dashboard called **RTP B2B Dashboard** and define the following widgets:

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
     <li>Widget type: <span class="uicontrol">Bar</span><br></li> 
     <li><span class="uicontrol">Create a bar chart showing</span>: <span class="uicontrol">Session</span></li> 
     <li><span class="uicontrol">Grouped by</span>: <span class="uicontrol">Event label</span></li> 
     <li><span class="uicontrol">Pivot by</span>: <span class="uicontrol">Default Channel Grouping</span></li> 
     <li>Filter: <br><span class="uicontrol">Only Show</span> | <span class="uicontrol">Event Category</span> (<span class="uicontrol">containing</span>) RTP-Segments</li> 
    </ul><p><img width="300" src="assets/image2015-3-23-11-3a32-3a13.png" data-linked-resource-id="7504247" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Name: # of RTP Segmented Users</li> 
     <li>Type: <span class="uicontrol">2.1 Metric</span></li> 
     <li><span class="uicontrol">Show the following metric</span>: <span class="uicontrol">Users</span><br></li> 
     <li>Filter: <br><span class="uicontrol">Only Show</span> | <span class="uicontrol">Event Category</span> (containing) RTP-Segments</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a6.png" data-linked-resource-id="7504249" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Name: Sessions by Industry</li> 
     <li>Type: <span class="uicontrol">Pie</span><br></li> 
     <li><span class="uicontrol">Create a pie chart showing</span>: <span class="uicontrol">Sessions</span></li> 
     <li><span class="uicontrol">Grouped by</span> : <span class="uicontrol">RTP-Industry</span></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a27.png" data-linked-resource-id="7504250" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <th> 
    <ul> 
     <li><strong>Name: Sessions by Industry and Channels</strong></li> 
     <li><strong>Widget type: <span class="uicontrol">Bar</span></strong></li> 
     <li><strong><span class="uicontrol">Create a bar chart showing</span>: <span class="uicontrol">Session</span></strong></li> 
     <li><strong><span class="uicontrol">Grouped by</span>: <span class="uicontrol">RTP-Industry</span></strong></li> 
     <li><strong><span class="uicontrol">Pivot by</span>: <span class="uicontrol">Default Channel Grouping</span></strong><br><img width="300" src="assets/image2015-3-23-11-3a33-3a52.png" data-linked-resource-id="7504252" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></li> 
    </ul></th> 
   <th> 
    <ul> 
     <li><strong>Name: Segmented Sessions by Country</strong></li> 
     <li><strong>Type: <span class="uicontrol">Geomap</span></strong></li> 
     <li><strong><span class="uicontrol">Plot selected metric</span>: <span class="uicontrol">Country</span> | <span class="uicontrol">Sessions</span></strong></li> 
     <li><strong><span class="uicontrol">Select a region</span>: <span class="uicontrol">The World</span></strong></li> 
     <li><strong>Filter: <span class="uicontrol">Only Show</span> | <span class="uicontrol">Event Category</span> (containing) RTP-Segments</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a34-3a18.png" data-linked-resource-id="7504253" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li><strong>Name: Sessions by RTP Category</strong></li> 
     <li><strong>Type: <span class="uicontrol">Pie</span></strong></li> 
     <li><strong><span class="uicontrol">Create a pie chart showing</span>: <span class="uicontrol">Sessions</span></strong></li> 
     <li><strong><span class="uicontrol">Grouped by</span>: <span class="uicontrol">RTP-Category</span></strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a35-3a1.png" data-linked-resource-id="7504254" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>Name: Top Target Segments</li> 
     <li>Type: <span class="uicontrol">Bar</span></li> 
     <li><span class="uicontrol">Create a bar chart showing</span>: <span class="uicontrol">Users</span></li> 
     <li><span class="uicontrol">Grouped by</span>: <span class="uicontrol">Event Action</span></li> 
     <li>Filter: <span class="uicontrol">Only Show</span> | <span class="uicontrol">Event Category</span> (containing) RTP-Segments</li> 
    </ul><p><img width="350" src="assets/add-a-widget.png" data-linked-resource-id="11382874" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li>Name: Sessions by RTP-Groups</li> 
     <li>Type: <span class="uicontrol">Bar</span><br></li> 
     <li><span class="uicontrol">Create a bar chart showing</span>: <span class="uicontrol">Sessions</span></li> 
     <li><span class="uicontrol">Grouped by</span>: <span class="uicontrol">RTP-Group</span></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a35-3a54.png" data-linked-resource-id="7504256" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>Name: Sessions &amp; Goals by Top Segments</li> 
     <li>Type: <span class="uicontrol">Table</span><br></li> 
     <li><span class="uicontrol">Display the following columns</span>: <br><span class="uicontrol">Event Label</span> | <span class="uicontrol">Sessions</span> | <span class="uicontrol">Goal Conversion Rate</span></li> 
     <li>Filter: <br><span class="uicontrol">Only Show</span> | <span class="uicontrol">Event Category</span> (containing) RTP-Segments</li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a36-3a15.png" data-linked-resource-id="7504257" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
   <th> </th> 
  </tr> 
 </tbody> 
</table>

## RTP Engagement Dashboard {#rtp-engagement-dashboard}

This dashboard allows users to analyze their RTP campaign performance and recommendation engine engagements. It provides comparison of avg. session duration and pages per session between:

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
     <li>Type: <strong><span class="uicontrol">2.1 Metric</span> </strong></li> 
     <li><span class="uicontrol">Show the following metric</span>: <strong><span class="uicontrol">Total Events</span></strong></li> 
     <li>Filters:<br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Category</span> (contains): RTP-Campaigns</strong><br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Action</span> (<span class="uicontrol">exactly matcing</span>): Impression</strong><strong>[<span class="uicontrol">don't show</span>] <span class="uicontrol">Event Label</span> (<span class="uicontrol">containing</span>): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a37-3a55.png" data-linked-resource-id="7504259" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul> 
     <li>Name: <strong>Total CTA (Clickthrough)</strong></li> 
     <li>Type: <strong><span class="uicontrol">2.1 Metric</span> </strong></li> 
     <li><span class="uicontrol">Show the following metric</span>: <strong><span class="uicontrol">Total Events</span></strong></li> 
     <li>Filters:<br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Category</span> (contains): RTP-Campaigns</strong><br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Action</span> (exactly matching): Clicks</strong><strong>[<span class="uicontrol">don't show</span>] <span class="uicontrol">Event Label</span> (containing): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a38-3a12.png" data-linked-resource-id="7504261" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul> 
     <li>Name: <strong>CRE - Total Clicks</strong></li> 
     <li>Type: <strong><span class="uicontrol">2.1 Metric</span></strong><br></li> 
     <li><span class="uicontrol">Show the following metric</span>: <strong><span class="uicontrol">Pageviews</span></strong></li> 
     <li>Filter: <strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Page</span> (<span class="uicontrol">containing</span>): rcmd</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a38-3a30.png" data-linked-resource-id="7504262" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>Avg. Session Duration (Engagement)</strong></li> 
     <li>Type: <strong><span class="uicontrol">2.1 Metric</span> </strong></li> 
     <li><span class="uicontrol">Show the following metric</span>: <strong><span class="uicontrol">Avg. Session Duration</span></strong></li> 
     <li>Filters:<br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Category</span> (exactly matching): RTP-Campaigns</strong><br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Action</span> (exactly matching): impression</strong><strong>[<span class="uicontrol">don't show</span>] <span class="uicontrol">Event Label</span> (<span class="uicontrol">containing</span>): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a41-3a21.png" data-linked-resource-id="7504264" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>Avg. Session Duration (Clickthrough)</strong></li> 
     <li>Type: <strong><span class="uicontrol">2.1 Metric</span> </strong></li> 
     <li><span class="uicontrol">Show the following metric</span>: <strong><span class="uicontrol">Avg. Session Duration</span></strong></li> 
     <li>Filters:<br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Category</span> (<span class="uicontrol">exactly matching</span>): RTP-Campaigns</strong><br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Action</span> (<span class="uicontrol">exactly matching</span>): clicks</strong><strong>[<span class="uicontrol">don't show</span>] <span class="uicontrol">Event Label</span> (<span class="uicontrol">containing</span>): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a41-3a37.png" data-linked-resource-id="7504265" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>CRE - Top Recommended Content</strong></li> 
     <li>Type: <strong><span class="uicontrol">Table</span></strong><br></li> 
     <li><span class="uicontrol">Display the following columns</span>: <br><strong><span class="uicontrol">Page Title</span> | <span class="uicontrol">Pageviews</span></strong><br></li> 
     <li>Filters:<br>Filter: <strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Page</span> (<span class="uicontrol">containing</span>): rcmd</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a41-3a51.png" data-linked-resource-id="7504266" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Name: <strong>Pages / Session (Engagement)</strong></li> 
     <li>Type: <strong><span class="uicontrol">2.1 Metric</span> </strong></li> 
     <li><span class="uicontrol">Show the following metric</span>: <strong><span class="uicontrol">Pages / Session</span></strong></li> 
     <li>Filters:<br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Category</span> (<span class="uicontrol">exactly matching</span>): RTP-Campaigns</strong></li> 
     <li><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Action</span> (<span class="uicontrol">exactly matching</span>): impression</strong></li> 
     <li><strong>[<span class="uicontrol">don't show</span>] <span class="uicontrol">Event Label</span> (<span class="uicontrol">containing</span>): #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a10.png" data-linked-resource-id="7504267" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Name: <strong>Pages / Session (Clickthrough)</strong></li> 
     <li>Type: <strong><span class="uicontrol">2.1 Metric</span> </strong></li> 
     <li><span class="uicontrol">Show the following metric</span>: <strong><span class="uicontrol">Pages / Session</span></strong></li> 
     <li>Filters:<br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Category</span> (<span class="uicontrol">exactly matching</span>): RTP-Campaigns</strong></li> 
     <li><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Action</span> (<span class="uicontrol">exactly matching</span>): clicks</strong></li> 
     <li><strong>[<span class="uicontrol">don't show</span>] <span class="uicontrol">Event Label</span> (<span class="uicontrol">containing</span>): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a42-3a32.png" data-linked-resource-id="7504268" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Name: <strong>Impressions by CTA</strong></li> 
     <li>Type: <strong><span class="uicontrol">Table</span></strong></li> 
     <li><span class="uicontrol">Display the following columns</span>: <strong><span class="uicontrol">Event Label</span> | <span class="uicontrol">Total Events</span> | <span class="uicontrol">Users</span></strong></li> 
     <li>Filters:<br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Category</span> (<span class="uicontrol">exactly matching</span>): RTP-Campaigns</strong><br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Action</span> (<span class="uicontrol">exactly matching</span>): impression</strong><strong>[<span class="uicontrol">don't show</span>] <span class="uicontrol">Event Label</span> (<span class="uicontrol">containing</span>): #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a48.png" data-linked-resource-id="7504269" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>Name: <strong>Clickthrough by CTA</strong></li> 
     <li>Type: <strong><span class="uicontrol">Table</span></strong></li> 
     <li><span class="uicontrol">Display the following columns</span>: <strong><span class="uicontrol">Event Label</span> | <span class="uicontrol">Total Events</span> | <span class="uicontrol">Users</span></strong></li> 
     <li>Filters:<br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Category</span> (<span class="uicontrol">exactly matching</span>): RTP-Campaigns</strong><br><strong>[<span class="uicontrol">only show</span>] <span class="uicontrol">Event Action</span> (<span class="uicontrol">exactly matching</span>): clicks</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a43-3a4.png" data-linked-resource-id="7504270" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[Integrate RTP with Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-reports-in-google-universal-analytics.md)
>
>[Custom RTP Reports in Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-reports-in-google-universal-analytics.md)
