---
unique-page-id: 4720218
description: Implementing RTP using Adobe Tag Manager - Marketo Docs - Product Documentation
title: Implementing RTP using Adobe Tag Manager
exl-id: 5a938d02-6b09-45d5-94b0-dbb50b5d62b6
feature: Web Personalization
---
# Implementing RTP using Adobe Tag Manager {#implementing-rtp-using-adobe-tag-manager}

To implement your RTP tag please follow the installation instructions below:

1. Log in to your RTP account.

1. Go to **Account Settings**.

   a. If you have already received your JavaScript tag from Support - continue to step 4.

   ![](assets/image2014-11-30-15-3a19-3a21-4.png)

1. Under Domain, locate the relevant domain and click **Generate Tag**.  

   ![](assets/image2014-11-30-15-3a20-3a17-4.png)

1. Login to your Dynamic Tag Manager account ([https://dtm.adobe.com/sign_in](https://dtm.adobe.com/sign_in)).

1. Go to **Dashboard.** Click on the relevant web property.

   ![](assets/image2014-12-3-17-3a58-3a17.png)

1. Go to **Rules**, click **Create New Rule**.

1. Fill out the following

    1. Name: **Marketo RTP**
    1. Conditions (collapse) : Trigger rule at  - **Top of Page**
    1. Javascript (collapse): click **Add New Script**

   ![](assets/image2014-12-3-17-3a59-3a40.png)

1. Call the new tag: **Marketo RTP Tag**

1. Remove the following code from the RTP tag

   * `<script type='text/javascript'>`
   * `</script>`

1. Paste the RTP JavaScript tag.

   ![](assets/image2014-12-3-18-3a3-3a45.png)

   >[!CAUTION]
   >
   >Make sure you remove all tags and leave only the script itself (no `<script type='text/javascript'>` , `</script>` )

1. Click **Save Code** in the script editor and **Save Rule** in the rule editor.

1. In the Rules panel, locate the Marketo RTP page load rule and within the **Actions** dropdown select **Activate Rules**.

   ![](assets/image2014-12-3-18-3a4-3a14.png)

1. **Verify** that it appears on all pages including landing pages and sub-domains.

    You can do it by right-clicking on your website’s pages. Go to **Inspect Element**, click on **Network**, Search: **RTP**.
