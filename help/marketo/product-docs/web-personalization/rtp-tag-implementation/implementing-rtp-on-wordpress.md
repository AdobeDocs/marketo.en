---
unique-page-id: 4720149
description: Implementing RTP on Wordpress - Marketo Docs - Product Documentation
title: Implementing RTP on Wordpress
exl-id: f010942b-02bb-447b-a272-c4237782b2d7
feature: Web Personalization
---
# Implementing RTP on Wordpress {#implementing-rtp-on-wordpress}

To implement your RTP tag please follow the installation instructions below:

1. Open up the **header.php** file of your **WordPress theme**.

   You can either use an FTP client to access your server or edit your theme files directly from the WordPress dashboard. Your file editor is located under the **Appearance** tab in the sidebar menu.

   ![](assets/image2014-11-30-15-3a35-3a30.png)

1. In the list of template files to the right of the text editor, find **header.php** and open it.

1. Go to **Account Settings**.

   a. If you have already received your JavaScript tag from Support - continue to step 5.  

   ![](assets/image2014-11-30-15-3a19-3a21-1.png)

1. Under Domain, locate the relevant domain and click **Generate Tag**.

   ![](assets/image2014-11-30-15-3a20-3a17-1.png)

1. Copy the RTP JavaScript tag and paste it to your website templates.

   a. Make sure it’s the first script at the header of the page - between the **`<head> </head>`** tags.

   ![](assets/image2014-11-30-15-3a36-3a31.png)

1. Click on **Update File** for the header.php file.

1. Verify that it appears on all pages including landing pages and sub-domains.

   a. You can do this by right-clicking on you website’s page. Go to **View Page Source.** Search for **RTP** to locate the tag.
