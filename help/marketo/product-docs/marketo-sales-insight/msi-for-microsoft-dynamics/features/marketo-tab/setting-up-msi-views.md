---
description: Setting up MSI Views - Marketo Docs - Product Documentation
title: Setting up MSI Views
exl-id: 8a45c006-73d4-4af8-ad62-b084056d1f7d
---
# Setting up MSI Views {#setting-up-msi-views}

Installing the Sales Insight plugin in Dynamics automatically adds the Best Bets and related dashboards on the Site Map. If for some reason the dashboards are not added, here's how to add them manually.

1. In Dynamics, click the gear icon and select **Advanced Settings** from the drop-down.

1. In the upper-left of the screen, click **Settings**. Under Customization choose **Customizations**.

1. Click **Customize the System**.

1. In the tree on the left, click **Client Extensions** and double-click **Site Map**.

1. Click the right arrow to go to the next page. Under Sales, you should see Marketo. If you don't, make sure you imported the package properly.

   >[!NOTE]
   >
   >Under Marketo you should have: Best Bets, My Email, Web Activity, and Anonymous Web Activity. If any of those dashboards are missing, click the + sign above Sales and add them as a Subarea.

1. Click on a dashboard to select it. In the column on the right, enter the respective information below for each one. You can ignore any categories not listed.

   **Best Bets**</br>
   URL: MainviewBestbets.html</br>
   Icon: /WebResources/mkt_/_MainView/_imgs/icons/bestbets.svg</br>
   ID: marketo_bestbets</br>
   Title: Best Bets

   **My Email**</br>
   URL: mkt_/MainViewMyEmail.html</br>
   Icon: /WebResources/mkt_/_MainView/_imgs/icons/email.svg</br>
   ID: marketo_myemail</br>
   Title: My Email

   **Web Activity**</br>
   URL: mkt_/MainViewWebActivity.html</br>
   Icon: /WebResources/mkt_/_MainView/_imgs/icons/web_activity.svg</br>
   ID: marketo_webactivity</br>
   Title: Web Activity

   **Anonymous Web Activity**</br>
   URL: mkt_/MainViewWebActivity.html</br>
   Icon: /WebResources/mkt_/_MainView/_imgs/icons/anonymous_web_activity.svg</br>
   ID: marketo_anonymous_webactivity</br>
   Title: Anonymous Web Activity

1. Click **Save** when done.
