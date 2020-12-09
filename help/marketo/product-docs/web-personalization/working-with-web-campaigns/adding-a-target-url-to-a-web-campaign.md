---
unique-page-id: 6094879
description: Adding a Target URL to a Web Campaign - Marketo Docs - Product Documentation
title: Adding a Target URL to a Web Campaign
---

# Adding a Target URL to a Web Campaign {#adding-a-target-url-to-a-web-campaign}

A Target URL is located under the Set Campaign page and defines the specific URL or URLs that a web campaign will appear on.

## Adding a Target URL for Dialog or Widget Web Campaigns {#adding-a-target-url-for-dialog-or-widget-web-campaigns}

1. Go to **Web Campaigns**.

   ![](assets/web-campaigns-hand-5.jpg)

1. Select **Create New Web Campaign**.

   ![](assets/create-new-web-campaign-hand.jpg)

1. Add a **Campaign Name**. Select a **Target Segment**. Add **Target URL**.

   ![](assets/set-web-campaign-hands.jpg)

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1">Name</th> 
   <th colspan="1" rowspan="1">Description</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1"><strong>Any Page</strong></td> 
   <td colspan="1" rowspan="1"><p>Allow campaign to appear on any pages.</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong>Include URL parameter when matching</strong></p></td> 
   <td colspan="1" rowspan="1">Add URL parameter to match and show campaign on URLs including this parameter. Eg. campaign=cpc</td> 
  </tr> 
 </tbody> 
</table>

## Adding Multiple URLs to Target URL {#adding-multiple-urls-to-target-url}

Clicking on the plus icon (![--](assets/image2015-2-18-8-3a40-3a59.png)) will open the Multiple Value Entry dialog to add multiple URLs. Add one URL per line.

![](assets/image2015-2-23-18-3a15-3a57.png)

>[!NOTE]
>
>
>* Dialog and Widget web campaigns can use Any Page and Wildcard (&#42;) options.
>* In advanced use cases, In Zone web campaigns can use Wildcards at end of URL path. Example: [www.marketo.com/software/personalization/*](http://www.marketo.com/software/personalization/*)
>* URL is case sensitive

## Adding a Target URL for In Zone Web Campaigns {#adding-a-target-url-for-in-zone-web-campaigns}

1. Go to **Web** **Campaigns**.

   ![](assets/web-campaigns-hand-5.jpg)

1. Select **Create New Web Campaign**.

   ![](assets/create-new-web-campaign-hand.jpg)

1. Add a** Campaign Name**. Select a **Target Segment**. Add **Target URL**.

   >[!NOTE]
   >
   >Target URL with In Zones must define a specific URL or URLs. In advanced use cases, In Zone web campaigns can use Wildcards at end of URL path. Example: [www.marketo.com/software/personalization/*](http://www.marketo.com/software/personalization/*) 

   ![](assets/set-web-campaign-multiple-hands.jpg)

>[!MORELIKETHIS]
>
>* [Create a New Dialog Web Campaign](create-a-new-dialog-web-campaign.md)
>* [Create a New In Zone Web Campaign](create-a-new-in-zone-web-campaign.md)
>* [Create a New Widget Web Campaign](create-a-new-widget-web-campaign.md)
