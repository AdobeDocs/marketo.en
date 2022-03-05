---
description: How Do I Prevent Self Views - Marketo Docs - Product Documentation
title: How Do I Prevent Self Views
hide: yes
hidefromtoc: yes
exl-id: 52de102f-6c6c-4663-9725-aae2f620d5bb
---
# How Do I Prevent Self Views? {#how-do-i-prevent-self-views}

Getting false positives on your view tracking can lead to reporting inconsistencies. This often occurs when users of Marketo Sales accidentally invoke the tracking pixel from their email client (we call this a self-view). Below are a few tips on significantly reducing and even eliminating self-views.

## Web (Outlook Web App and Gmail) {#web-outlook-web-app-and-gmail}

Marketo Sales will store a cookie in your browser to prevent views from being tracked when opening your emails from Outlook Web App and Gmail. If you are still receiving self-views, we recommend doing the following:

* Ensure that you have cookies enabled on your computer.

* If you're using a new computer or mobile device, make sure you've logged in to the web application. This will allow us to recognize your computer/device going forward.

## Desktop (Windows) {#desktop-windows}

Views are tracked by downloading a small invisible image pixel in your email client. You can significantly lower the amount of self-views in Outlook by disabling images to be automatically downloaded. Below are the steps how.

1. In Outlook, click **File** in the menu bar.

   ![](assets/how-do-i-prevent-self-views-1.png)

1. Click **Options**.

   ![](assets/how-do-i-prevent-self-views-2.png)

1. In the Outlook Options dialog box, click **Trust Center**.

   ![](assets/how-do-i-prevent-self-views-3.png)

1. Under Microsoft Outlook Trust Center, click **Trust Center Settings**.

   ![](assets/how-do-i-prevent-self-views-4.png)

1. Click Automatic Download in the menu on the left, and select the **Don't download pictures automatically in HTML email or RSS items** check box.

   ![](assets/how-do-i-prevent-self-views-5.png)

1. Click **OK** in the Trust Center dialog box.

   ![](assets/how-do-i-prevent-self-views-6.png)

1. Click **OK** in the Outlook Options dialog box.

   ![](assets/how-do-i-prevent-self-views-7.png)

## Desktop (Mac) {#desktop-mac}

Views are tracked by downloading a small invisible image pixel in your email client. You can significantly lower the amount of self-views in Outlook by disabling images to be automatically downloaded. Below are the steps how.

1. In Outlook, click **Outlook** in the menu bar and select **Preferences**.

   ![](assets/how-do-i-prevent-self-views-8.png)

1. Under Email, choose **Reading**.

   ![](assets/how-do-i-prevent-self-views-9.png)

1. Under Security, click the **Never** radio button.

   ![](assets/how-do-i-prevent-self-views-10.png)
