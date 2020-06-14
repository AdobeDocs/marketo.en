---
unique-page-id: 11385053
description: Deploy the JavaScript for Content-AI - Marketo Docs - Product Documentation
title: Deploy the JavaScript for Content-AI
---

# Deploy the JavaScript for Content-AI {#deploy-the-javascript-for-content-ai}

Deploy the JavaScript for Content-AI - Marketo Docs - Product Documentation

>[!NOTE]
>
>Depending on the purchase date, your Marketo subscription may include either Marketo Predictive Content or Content`<sup>AI</sup>`. For those using Predictive Content, Marketo is enabling Content`<sup>AI</sup>` Analytics features until April 30, 2018. To keep these features beyond that date, please contact your Marketo Customer Success Manager to upgrade to Marketo Content`<sup>AI</sup>`.

To use Predictive Content, you need to generate and set up your the RTP (Web Personalization) `tag.`  

#### Generate Tag {#deploythejavascriptforcontent-ai-generatetag}

1. Login to your Predictive Content account. Go to **Account Settings**.

   ![](assets/settings-dropdown-account-hands.png)

1. `In **Domain Configuration**,` `locate the relevant domain and click`**`Generate Tag.`**

   ![](assets/generate-tag.png)

1. Copy and paste the Web Personalization tag into the HTML of your website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Copy the Web Personalization JavaScript tag and paste it as the first script in the header of your pages, between the <head> </head> tags. See more detailed [implementation instructions here](../../../../welcome-to-marketo-docs/product-docs/web-personalization/getting-started-(rtp)/rtp-tag-implementation.md) [.](http://pages2.marketo.com/rtp-implementation.html)

   ##### Verify the tag appears on all pages, including landing pages and sub-domains. Check this by right-clicking on your website’s page. Go to View Page Source in a web browser. Search: ‘RTP’. {#deploythejavascriptforcontent-ai-verifythetagappearsonallpages-includinglandingpagesandsub-domains.checkthisbyright-clickingonyourwebsite’spage.gotoviewpagesourceinawebbrowser.search-‘rtp’.}

   ##### Confirm that the Tag toggle set to ON. {#deploythejavascriptforcontent-ai-confirmthatthetagtogglesettoon.}

