---
unique-page-id: 4720917
description: Personalized Remarketing in Facebook - Marketo Docs - Product Documentation
title: Personalized Remarketing in Facebook
---

# Personalized Remarketing in Facebook {#personalized-remarketing-in-facebook}

Personalized Remarketing in Facebook - Marketo Docs - Product Documentation

### What's in this article? {#whats-in-this-article}

[Creating an Audience in Facebook](#creating-an-audience-in-facebook)  
[RTP Data Points in Facebook](#rtp-data-points-in-facebook)  
[Target your Audience with an Ad](#target-your-audience-with-an-ad)  
Personalized Remarketing lets you re-engage with your users using RTP Data and the power of Facebook Remarketing.

>[!NOTE]
>
>**Prerequisites**
>
>* Complete the [Retargeting with Web Personalization Data](retargeting-with-web-personalization-data.md) setup
>* Review the [](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) [Facebook documentation on Custom Audiences](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel)and Remarketing
>

#### Creating an Audience in Facebook {#creating-an-audience-in-facebook}

1. In Facebook, go to your [Audience tab](https://www.facebook.com/ads/audience_manager) in Ads Manager.
1. Click **Tools** and select **Audiences**.

   ![](assets/one-1.png)

1. Click **Create a Custom Audience**.

   ![](assets/two-1.png)

1. Select **Website Traffic**.

   ![](assets/image2015-1-19-16-3a32-3a2.png)

1. In the Website traffic list, select** Custom Combination**.

   ![](assets/image2015-1-19-16-3a33-3a21.png)

1. In the Include list, select **Event**.

   ![](assets/image2015-1-19-16-3a34-3a9.png)

1. In the Event list, select **RTP Remarketing **and select a parameter.

   ![](assets/image2015-1-19-16-3a52-3a29.png)

1. For this example, select Industry to contain **Education**. Enter **Education**, and edit **In the Last** to be 180 days. Enter Audience Name: **Education Industry**. Click **Create Audience**.

   ![](assets/image2015-1-19-16-3a56-3a15.png)

1. You have now created a new custom audience using RTP data in Facebook.

   ![](assets/image2015-1-19-16-3a59-3a2.png)

#### RTP Data Points in Facebook {#rtp-data-points-in-facebook}

<table> 
 <tbody> 
  <tr> 
   <th>Event Name</th> 
   <th> </th> 
  </tr> 
  <tr> 
   <td>RTP Remarketing</td> 
   <td> 
    <div> 
     <table> 
      <tbody> 
       <tr> 
        <th>Parameter</th> 
        <th>Value</th> 
       </tr> 
       <tr> 
        <td>ABM List</td> 
        <td>(Name of Account-Based List)</td> 
       </tr> 
       <tr> 
        <td colspan="1">Category</td> 
        <td colspan="1"><p>Fortune 500</p><p>Fortune 1000</p><p>Global 2000</p></td> 
       </tr> 
       <tr> 
        <td colspan="1">Group</td> 
        <td colspan="1"><p>Enterprise</p><p>SMB</p></td> 
       </tr> 
       <tr> 
        <td>Industry</td> 
        <td><p>Defense</p><p>Education</p><p>Financial Services</p><p>Government</p><p>Healthcare, Pharma, Biotech</p><p>Software and Internet</p><p>etc... (as per RTP Industry options)</p></td> 
       </tr> 
       <tr> 
        <td colspan="1">Segmented Audience</td> 
        <td colspan="1">(Name of Segmented Audience created in RTP)</td> 
       </tr> 
      </tbody> 
     </table> 
    </div></td> 
  </tr> 
 </tbody> 
</table>

#### Target your Audience with an Ad {#target-your-audience-with-an-ad}

For additional details, see [Facebook's documentation](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#target-your-audience).

1. Go to Ads Manager, Click **Create Ad**.

   ![](assets/image2015-1-19-17-3a10-3a19.png)

1. Select **Send people to your website** as the objective of your campaign.

   ![](assets/image2015-1-19-17-3a11-3a20.png)

1. Enter your website URL.

   ![](assets/image2015-1-19-17-3a12-3a39.png)

1. Create your ad set. Select a custom audience from the list of Audiences you created, for example, Education Industry.

   ![](assets/image2015-1-19-17-3a18-3a13.png)

1. Select all other ad set options, set your budget and define your ad creatives.

   ![](assets/image2015-1-19-17-3a19-3a25.png)

1. You are now all set up with a personalized remarketing campaign in Facebook.

>[!NOTE]
>
>**Related Articles**
>
>* [Retargeting with Web Personalization Data](retargeting-with-web-personalization-data.md)
>* [Personalized Remarketing in Google](personalized-remarketing-in-google.md)
>

