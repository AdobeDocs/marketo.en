---
unique-page-id: 7513865
description: Install and Configure Marketo Sales Insight in Microsoft Dynamics 2015 - Marketo Docs - Product Documentation
title: Install and Configure Marketo Sales Insight in Microsoft Dynamics 2015
---

# Install and Configure Marketo Sales Insight in Microsoft Dynamics 2015 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is a fantastic tool for giving your sales team a "window" into the wealth of data the Marketing team has. Here is how to install and configure it in Microsoft Dynamics 201

>[!PREREQUISITES]
>
>Complete your [Marketo-Microsoft integration](http://docs.marketo.com/x/ZwBd).
>
>[Download the correct solution](http://docs.marketo.com/x/LoJo) for your version of Microsoft Dynamics CRM.

## Import Solution {#import-solution}

OK, now it's time to import the Marketo Sales Insight solution into Microsoft Dynamics. Here's how:

1. Under Microsoft Dynamics CRM click **Settings**.

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. Under SETTINGS, click **Customizations**.

   ![](assets/image2015-4-29-14-3a22-3a1.png)

1. Click **Solutions**.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >**Reminder**
   >
   >
   >You should already have installed and configured the Marketo solution before moving forward.

1. Click **Import**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. In the new window, click **Browse**.

   ![](assets/image2014-12-12-9-3a5-3a36.png)

1. Find and select the solution you downloaded above.

   ![](assets/image2014-12-12-9-3a5-3a45.png)

1. Click **Next**.

   ![](assets/image2014-12-12-9-3a5-3a55.png)

1. The solution will upload. You can view the package contents if you like. Click **Next**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. Make sure to leave the box checked and click **Import**.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. Feel free to download the log file, then click **Close**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. Awesome! You should see the solution now. If it's not there, refresh your screen.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

## Connect Marketo and Sales Insight {#connect-marketo-and-sales-insight}

Let's tie your Marketo instance to Sales Insight in Dynamics. Here's how:

>[!NOTE]
>
>Admin rights required.

1. Log into Marketo and go to the **Admin **section.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Under the Sales Insight section, click **Edit API Configuration**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Copy the **Marketo Host**, **API URL**, and **API User Id** for use in a later step. Enter an API Secret Key of your choice and click **Save**.

   >[!CAUTION]
   >
   >Don't use an ampersand (&) in your API Secret Key.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >The following fields must be synced with Marketo for *both Lead and Contact* for Sales Insight to work:
   >
   >    
   >    
   >    * Priority 
   >    * Urgency
   >    * Relative Score
   >    
   >    
   >If any of these fields are missing, you will see an error message in Marketo with the name of the missing fields. To fix this, perform [this procedure](../../../../product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Back in Microsoft Dynamics, go to **Settings**.

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. Under **Settings**, click **Marketo API Config**.

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. Click **New**.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. Enter the information that you took from Marketo earlier and click **Save**.

   ![](assets/image2014-12-12-9-3a8-3a17.png)

## Set User Access {#set-user-access}

Finally, you have to give specific users access to use Marketo Sales Insight.

1. Go to **Settings**.

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. Go to **Security**.

   ![](assets/image2015-4-29-14-3a56-3a33.png)

1. Click **Users**.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. Select the users you want to give access to Sales Insight to and click **Manage Roles**.

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. Select the Marketo Sales Insight role and click **OK**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   And you should be all done! Finally, to test, log into Dynamics as a user who has access to Marketo Sales Insight and look at a lead or contact.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

You have now unlocked the power of Marketo Sales Insight for your sales team.

>[!MORELIKETHIS]
>
>[Setting up Stars and Flames for Lead/Contact Records](http://docs.marketo.com/x/BICMAg)

