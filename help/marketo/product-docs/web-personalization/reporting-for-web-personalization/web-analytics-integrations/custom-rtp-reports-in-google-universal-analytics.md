---
unique-page-id: 7504218
description: Custom RTP Reports in Google Universal Analytics - Marketo Docs - Product Documentation
title: Custom RTP Reports in Google Universal Analytics
---

# Custom RTP Reports in Google Universal Analytics {#custom-rtp-reports-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[Integrate RTP with Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

This article explains how to setup RTP custom reports for Google Universal Analytics (GUA).  The data sent from RTP to GUA can be set up as two separate custom reports called:

* RTP B2B
* RTP Engagement

## Setting up a Custom Report {#setting-up-a-custom-report}

1. Log in to Google Analytics.

1. Click on **Customization** in the top menu.

1. Click **+New Custom Report**.

![](assets/image2015-3-22-16-3a10-3a48.png)

## RTP B2B Report {#rtp-b-b-report}

1. Name the report **RTP B2B Report**.

1. Name the 1st tab **Industry**.

>[!NOTE]
>
>You will **Duplicate this tab** and create additional similar ones - step 5)

1. Select the **Explorer** report type.

   ![](assets/image2015-3-22-16-3a15-3a25.png)

1. In the **Metric Groups** section, select the metrics that are relevant for your business.

    a. We recommend the following:

   ![](assets/image2015-3-22-16-3a16-3a40.png)

1. Duplicate this tab 4 times and name them:

    1. **Industry**
    1. **Group**
    1. **Category**
    1. **ABM**
    1. **Organizations**

   ![](assets/image2015-3-22-16-3a17-3a41.png)

1. In the **Dimension Drill downs** section set the relevant dimensions for each tab as below.

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Tab Name 
    </div></th> 
   <th> 
    <div>
      Dimension Drill downs
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>Industry</td> 
   <td><img src="assets/1.png" data-linked-resource-id="7514675" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Group</td> 
   <td><img src="assets/2.png" data-linked-resource-id="7514674" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Category</td> 
   <td><img src="assets/3.png" data-linked-resource-id="7514673" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>ABM</td> 
   <td><img src="assets/5.png" data-linked-resource-id="7514677" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Organizations</td> 
   <td><img src="assets/5.png" data-linked-resource-id="7514677" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
 </tbody> 
</table>

1. Do not set any filters and set this report to be available for **All Web Site Data** (or change if relevant to specific Analytics account).

1. Click **Save**.

   ![](assets/image2015-3-22-16-3a21-3a23.png)

## RTP Engagement Report {#rtp-engagement-report}

1. Name the report **RTP Engagement Report**.

1. Set the 1st tab name to **All Engagement**.

>[!NOTE]
>
>You will Duplicate this tab and create additional similar ones - step 5)

1. Select the **Explorer** report type.

   ![](assets/image2015-3-22-16-3a23-3a36.png)

1. In the Metric Groups section, select the metrics that are relevant for your business. Here is a recommendation:

   ![](assets/image2015-3-22-16-3a24-3a57.png)

1. Duplicate this tab 4 times and name them:

    1. **All Engagement**
    1. **Engagement by Industry**
    1. **Engagement by Group**
    1. **Engagement by Category**
    1. **Engagement by ABM**

   ![](assets/image2015-3-22-16-3a26-3a21.png)

1. In the **Dimension Drill downs** section set the relevant dimensions for each tab as below:

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Tab Name 
    </div></th> 
   <th> 
    <div>
      Dimension Drill downs 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>All Engagement</td> 
   <td><img src="assets/a.png" data-linked-resource-id="7514683" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Engagement by ABM</td> 
   <td><img width="277" src="assets/4.png" data-linked-resource-id="7514678" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Engagement by Category</td> 
   <td><img src="assets/a.png" data-linked-resource-id="7514683" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Engagement by Group</td> 
   <td><img src="assets/c.png" data-linked-resource-id="7514681" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
  <tr> 
   <td>Engagement by Industry</td> 
   <td><img src="assets/b.png" data-linked-resource-id="7514682" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td> 
  </tr> 
 </tbody> 
</table>

1. Set the following filters:

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      Inc/Exc 
    </div></th> 
   <th> 
    <div>
      Field 
    </div></th> 
   <th> 
    <div>
      Match type 
    </div></th> 
   <th> 
    <div>
      Values 
    </div></th> 
   <th colspan="1"> 
    <div>
      Comments 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td><p>Include</p></td> 
   <td><p>Event Category</p></td> 
   <td>Regex</td> 
   <td>RTP-Campaigns|RTP-Recommendations|RTP-Segments</td> 
   <td colspan="1">Will filter all other custom events that are not related to RTP</td> 
  </tr> 
  <tr> 
   <td>Exclude</td> 
   <td>Event Label</td> 
   <td>Regex</td> 
   <td>#</td> 
   <td colspan="1">Allows you to filter from your reports campaign using # in the campaign name</td> 
  </tr> 
 </tbody> 
</table>

1. Set this report to be available for **All Web Site Data** (or change if necessary).

   ![](assets/image2015-3-22-16-3a29-3a5.png)

1. Click **Save**.

![](assets/image2015-3-22-16-3a30-3a0.png)

>[!MORELIKETHIS]
>
>[Integrate RTP with Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)
>
>[Custom RTP Dashboards in Google Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-dashboards-in-google-universal-analytics.md)
