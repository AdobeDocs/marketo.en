---
unique-page-id: 4720218
description: Implementing RTP using Adobe Tag Manager - Marketo Docs - Product Documentation
title: Implementing RTP using Adobe Tag Manager
---

# Implementing RTP using Adobe Tag Manager {#implementing-rtp-using-adobe-tag-manager}

Implementing RTP using Adobe Tag Manager - Marketo Docs - Product Documentation

To implement your RTP tag please follow the installation instructions below:

1. Login to your RTP account**.**
1. Go to** Account Settings.**

    1. If you have already received your JavaScript tag from Support - continue to step 4.  
       ![](assets/image2014-11-30-15-3a19-3a21-4.png)

1. Under Domain, locate the relevant domain and click&nbsp;**Generate Tag**.  
   ** ![](assets/image2014-11-30-15-3a20-3a17-4.png)

   **

1. Login to your Dynamic Tag Manager account ([https://dtm.adobe.com/sign_in](https://dtm.adobe.com/sign_in)).
1. Go to&nbsp;**Dashboard. **Click on** **the relevant web property.  
   ![](assets/image2014-12-3-17-3a58-3a17.png)  

1. Go to&nbsp;**Rules,&nbsp;**click **Create New Rule.**

1. Fill out the following

    1. Name: **Marketo RTP**
    1. Conditions (collapse) : Trigger rule at &nbsp;-&nbsp;**Top of Page**
    1. Javascript (collapse): click **Add New Script**

   ![](assets/image2014-12-3-17-3a59-3a40.png)

1. Call the new tag: **Marketo RTP Tag**&nbsp;
1. Remove the following code from the RTP tag

    1. <script type='text/javascript'>
    1. </script>

1. Paste the RTP JavaScript tag.

   ![](assets/image2014-12-3-18-3a3-3a45.png)

   >[!CAUTION]
   >
   >Make sure you remove all tags and leave only the script itself (no <script type='text/javascript'> , </script> )

1. Click **Save Code** in the script editor and **Save Rule **in the rule editor.

1. In the Rules panel, locate the Marketo RTP page load rule and within the **Actions **dropdown select&nbsp;**Activate Rules**.  
   ![](assets/image2014-12-3-18-3a4-3a14.png)

1. &nbsp;**Verify**&nbsp;that it appears on all pages including landing pages and sub-domains.

    1. You can do it by right-clicking on your website’s pages. Go to **Inspect Element**, click on **Network,&nbsp;**Search: **RTP**.

