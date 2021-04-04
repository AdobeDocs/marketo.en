---
unique-page-id: 4720151
description: Implementing RTP on Marketo Landing Pages - Marketo Docs - Product Documentation
title: Implementing RTP on Marketo Landing Pages
exl-id: fd19c3ad-d3f6-44a3-9f7a-d518e2d3f02a
---
# Implementing RTP on Marketo Landing Pages {#implementing-rtp-on-marketo-landing-pages}

To implement your RTP tag please follow the installation instructions below:

1. Go to the **Design Studio.** Open the item you want to edit. Select **Template Actions**, select **Edit Draft**.

   ![](assets/image2015-4-26-18-3a27-3a4.png)

1. Make your template changes on the **HTML Source** tab.

   ![](assets/image2015-4-26-18-3a28-3a17.png)

1. In your RTP account, go to **Account Settings**.

   a. If you have already received your JavaScript tag from Support - continue to step 5.  

   ![](assets/image2014-11-30-15-3a19-3a21-2.png)

1. Under Domain, locate the relevant domain and click **Generate Tag**.  

   ![](assets/image2015-4-26-18-3a27-3a35.png)

   ![](assets/image2014-11-30-15-3a20-3a17-2.png)

1. Copy the RTP JavaScript tag and paste it to all your landing page templates between the **`<head> </head>`** tags.

1. Click **Save** and **Close** the window.

1. Back in the **Design Studio**, approve the landing page from **Template Actions**, click **Approve**.  

   ![](assets/image2015-4-26-18-3a28-3a30.png)

1. Finally, you’ll need to **re-approve** any landing pages using that template for the template changes to take effect. You can re-approve them all at once from the main Landing Pages section.

   ![](assets/image2015-4-26-18-3a28-3a49.png)

1. Verify that it appears on all pages including landing pages and sub-domains.

   You can do this by right-clicking on you website’s page. Go to **View Page Source.** Search for **RTP** to locate the tag.
