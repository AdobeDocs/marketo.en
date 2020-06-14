---
unique-page-id: 3571737
description: Install and Configure Marketo Sales Insight in Microsoft Dynamics 2013 - Marketo Docs - Product Documentation
title: Install and Configure Marketo Sales Insight in Microsoft Dynamics 2013
---

# Install and Configure Marketo Sales Insight in Microsoft Dynamics 2013 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Install and Configure Marketo Sales Insight in Microsoft Dynamics 2013 - Marketo Docs - Product Documentation

Marketo Sales Insight is a fantastic tool for giving your sales team a "window" into the wealth of data the marketing team has. Here's how to install and configure it.

>[!NOTE]
>
>**Prerequisites**
>
>Complete your [Marketo-Microsoft integration](http://docs.marketo.com/x/EIA2).
>
>[Download the correct solution](http://docs.marketo.com/x/LoJo) for your version of Microsoft Dynamics CRM.

### What's in this article? {#what-s-in-this-article}

[Import Solution](#installandconfiguremarketosalesinsightinmicrosoftdynamics2013-importsolution)  
[Connect Marketo and Sales Insight](#installandconfiguremarketosalesinsightinmicrosoftdynamics2013-connectmarketoandsalesinsight)  
[Set User Access](#installandconfiguremarketosalesinsightinmicrosoftdynamics2013-setuseraccess)

#### Import Solution {#installandconfiguremarketosalesinsightinmicrosoftdynamics2013-importsolution}

OK, now it's time to import the Marketo Sales Insight solution into Microsoft Dynamics.

1. Under **Microsoft Dynamics CRM** click **Settings**.

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. Under **Settings**, click **Customizations**.

   ![](assets/image2014-12-12-9-3a5-3a6.png)

1. Click **Solutions**.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >**Reminder**
   >
   >
   >You should already have installed and configured Marketo before moving forward

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

1. Feel free to download the log file. Click **Close**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. Awesome! You should see the solution now. If it's not there, refresh your screen.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

#### Connect Marketo and Sales Insight {#installandconfiguremarketosalesinsightinmicrosoftdynamics2013-connectmarketoandsalesinsight}

Let's tie your Marketo instance to Sales Insight in Dynamics.

>[!NOTE]
>
>Admin rights required.

1. Log in to Marketo and go to the **Admin** section.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Under the **Sales Insight** section click **Edit API Configuration**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Copy the **Marketo Host**, **API URL**, and **API User Id** for use in a later step. Enter an **API Secret Key** of your choice and click **SAVE**.

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
   >If any of these fields are missing, you will see an error message in Marketo with the name of the missing fields. To fix this, perform [this procedure](../../../../../welcome-to-marketo-docs/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Back in Microsoft Dynamics, go to **Settings**.

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. Under **Settings**, click **Marketo API Config**.

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. Click **New**.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. Enter the information that you took from Marketo earlier and click **Save**.

   ![](assets/image2014-12-12-9-3a8-3a17.png)

#### Set User Access {#installandconfiguremarketosalesinsightinmicrosoftdynamics2013-setuseraccess}

Finally, you can give specific users access to Marketo Sales Insight.

1. Go to **Settings**.

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. Click **Users**.

   ![](assets/image2014-12-12-9-3a8-3a42.png)

1. Select the user(s) you want to give access to Sales Insight to and click **Manage Roles**.

   ![](assets/image2014-12-12-9-3a9-3a13.png)

1. Select the **Marketo Sales Insight** role and click **OK**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   And you should be all done! Finally, to test, log in to Dynamics as a user who has access to Marketo Sales Insight and look at a lead or contact.

   ![](assets/image2014-12-12-9-3a9-3a31.png)

You have now unlocked the power of Marketo Sales Insight for your sales team.

>[!NOTE]
>
>**Related Articles**
>
>[Setting up Stars and Flames for Lead/Contact Records](http://docs.marketo.com/x/BICMAg)

