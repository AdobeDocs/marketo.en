---
unique-page-id: 7504218
description: Custom RTP Reports in Google Universal Analytics - Marketo Docs - Product Documentation
title: Custom RTP Reports in Google Universal Analytics
---

# Custom RTP Reports in Google Universal Analytics {#custom-rtp-reports-in-google-universal-analytics}

Custom RTP Reports in Google Universal Analytics - Marketo Docs - Product Documentation

### What's in this article? {#whats-in-this-article}

[Setting up a Custom Report](#setting-up-a-custom-report)  
[RTP B2B Report](#rtp-b-b-report)  
[RTP Engagement Report](#rtp-engagement-report)

>[!NOTE]
>
>**Prerequisites**
>
>[Integrate RTP with Google Universal Analytics](integrate-rtp-with-google-universal-analytics.md)

This post explains how to setup RTP custom reports for Google Universal Analytics (GUA).  The data sent from RTP to GUA can be set up as two separate custom reports called:

* RTP B2B
* RTP Engagement

#### Setting up a Custom Report {#setting-up-a-custom-report}

1. Log in to Google Analytics.
1. Click on **Customization **in the top menu.
1. Click **+New Custom Report.**

** ![](assets/image2015-3-22-16-3a10-3a48.png)

**

#### RTP B2B Report {#rtp-b-b-report}

1. Name the report **RTP B2B Report**.
1. Name the 1st tab **Industry **

    1. (Note: you will **Duplicate this tab** and create additional similar ones - step 5)

1. Select the** Explorer** report type.  
   ** ![](assets/image2015-3-22-16-3a15-3a25.png)

   **

1. In the **Metric Groups** section, select the metrics that are relevant for your business.

    1. We recommend the following:  
       ** ![](assets/image2015-3-22-16-3a16-3a40.png)    
    
       **

1. Duplicate this tab 4 times and name them:

    1. **Industry**
    1. **Group**
    1. **Category**
    1. **ABM**
    1. **Organizations**

   ![](assets/image2015-3-22-16-3a17-3a41.png)

1. In the&nbsp;**Dimension Drill downs** section set the relevant dimensions for each tab as below.

   |  
   Tab Name  | 
   Dimension Drill downs  |
   |---|---|
   | Industry | ![](assets/1.png)

   |
   | Group | ![](assets/2.png)

   |
   | Category | ![](assets/3.png)

   |
   | ABM | ![](assets/5.png)

   |
   | Organizations | ![](assets/5.png)

   |

1. Do not set any filters and set this report to be available for **All Web Site Data **(or change if relevant to specific Analytics account).
1. Click **Save**.  
   ![](assets/image2015-3-22-16-3a21-3a23.png)

#### RTP Engagement Report {#rtp-engagement-report}

1. Name the report **RTP Engagement Report.**
1. Set the 1st tab name to **All Engagement**

    1. (Note: you will Duplicate this tab and create additional similar ones - step 5)

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

   ** ![](assets/image2015-3-22-16-3a26-3a21.png)\**

1. In the **Dimension Drill downs** section set the relevant dimensions for each tab as below:

   |  
   Tab Name  | 
   Dimension Drill downs  |
   |---|---|
   | All Engagement | ![](assets/a.png)

   |
   | Engagement by ABM | ![](assets/4.png)

   |
   | Engagement by Category | ![](assets/a.png)

   |
   | Engagement by Group | ![](assets/c.png)

   |
   | Engagement by Industry | ![](assets/b.png)

   |

1. Set the following filters:
1. 

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

1. Set this report to be available for **All Web Site Data **(or change if necessary)

   ![](assets/image2015-3-22-16-3a29-3a5.png)

1. Click **Save**.

![](assets/image2015-3-22-16-3a30-3a0.png)

>[!NOTE]
>
>**Related Articles**
>
>[Integrate RTP with Google Universal Analytics](integrate-rtp-with-google-universal-analytics.md)
>
>[Custom RTP Dashboards in Google Universal Analytics](custom-rtp-dashboards-in-google-universal-analytics.md)

