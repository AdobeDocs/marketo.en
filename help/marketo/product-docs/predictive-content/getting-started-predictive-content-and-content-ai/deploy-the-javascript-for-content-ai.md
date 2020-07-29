---
unique-page-id: 11385053
description: Deploy the JavaScript for Content-AI - Marketo Docs - Product Documentation
title: Deploy the JavaScript for Content-AI
---

# Deploy the JavaScript for Content-AI {#deploy-the-javascript-for-content-ai}

>[!NOTE]
>
>Depending on the purchase date, your Marketo subscription may include either Marketo Predictive Content or Content`<sup>AI</sup>`. For those using Predictive Content, Marketo is enabling Content`<sup>AI</sup>` Analytics features until April 30, 2018. To keep these features beyond that date, please contact your Marketo Customer Success Manager to upgrade to Marketo Content`<sup>AI</sup>`.

To use Predictive Content, you need to generate and set up your the RTP (Web Personalization) `tag.`  

#### Generate Tag {#generate-tag}

1. Login to your Predictive Content account. Go to **Account Settings**.

   ![](assets/settings-dropdown-account-hands.png)

1. In **Domain Configuration**, locate the relevant domain and click **Generate Tag.**

   ![](assets/generate-tag.png)

1. Copy and paste the Web Personalization tag into the HTML of your website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Copy the Web Personalization JavaScript tag and paste it as the first script in the header of your pages, between the <head> </head> tags. See more detailed [implementation instructions here](http://docs.marketo.com/display/docs/rtp+tag+implementation) [.](http://pages2.marketo.com/rtp-implementation.html)

1. Verify the tag appears on all pages, including landing pages and sub-domains. Check this by right-clicking on your  `website’s`&nbsp;page. Go to **View Page Source** in a web browser. Search: ‘RTP’.
1. Confirm that the Tag toggle set to **ON**.

