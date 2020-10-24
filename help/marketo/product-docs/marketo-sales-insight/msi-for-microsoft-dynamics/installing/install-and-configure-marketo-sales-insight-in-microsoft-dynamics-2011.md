---
unique-page-id: 3571735
description: Install and Configure Marketo Sales Insight in Microsoft Dynamics 2011 - Marketo Docs - Product Documentation
title: Install and Configure Marketo Sales Insight in Microsoft Dynamics 2011
---

# Install and Configure Marketo Sales Insight in Microsoft Dynamics 2011 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is a fantastic tool for your sales team. Here is the step-by-step instruction of how to install and configure it in Microsoft Dynamics 2011 On-Premises.

>[!NOTE]
>
>**Prerequisites**
>
>Complete your [Marketo-Microsoft integration](http://docs.marketo.com/x/DoA2).
>
>[Download the correct solution](http://docs.marketo.com/x/LoJo) for your version of Microsoft Dynamics CRM.

## Import Solution {#import-solution}

1. Sign in to Microsoft Dynamics CRM. Click **Settings** in the bottom left menu.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Select **Solutions** in the tree.

   ![](assets/image2015-5-4-10-3a41-3a56.png)

1. Click **Import** ( ![](assets/image2015-5-4-10-3a45-3a44.png)).

   ![](assets/image2015-5-4-10-3a42-3a38.png)

   >[!NOTE]
   >
   >**Reminder**
   >
   >
   >You should already have [installed and configured](install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2011.md) the Marketo solution before moving forward.

1. Click **Browse**. Select the Marketo Sales Insight solution you [downloaded](download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md). Click **Next**.

   ![](assets/image2015-5-4-10-3a55-3a15.png)

1. Verify the details of the solution, and click **Next**.

   ![](assets/image2015-5-4-10-3a57-3a31.png)

1. Make sure the SDK message option is checked. Click **Next**.

   ![](assets/image2015-5-4-11-3a43-3a37.png)

1. Now wait for the import to finish.

   ![](assets/image2015-5-4-11-3a0-3a58.png)

1. Click **Close**.

   ![](assets/crmhand.png)

1. Marketo Sales Insight will now show up in the solution list. Yay!

   ![](assets/image2015-5-4-11-3a2-3a37.png)

1. Select Marketo Sales Insight and click on **Publish All Customizations** ( ![](assets/image2015-5-4-11-3a7-3a8.png)).

   ![](assets/image2015-5-4-11-3a8-3a27.png)

## Connect Marketo and Sales Insight  {#connect-marketo-and-sales-insight}

>[!NOTE]
>
>**Admin Permissions Required**

1. Log in to Marketo and click **Admin**.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Under the **Sales Insight **section click **Edit API Configuration**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Copy the **Marketo Host**, **API URL**, and **API User Id** for use in a later step. Enter an **API Secret Key** of your choice and click **SAVE**.

   >[!CAUTION]
   >
   >Don't use an ampersand (&) in your API Secret Key.

   ![](assets/image2015-5-4-11-3a16-3a3.png)

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

1. Go back to Dynamics, select **Settings**.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Select **Marketo API Config** in the tree.

   ![](assets/image2015-5-4-11-3a22-3a41.png)

1. Click **Default Configuration**.

   ![](assets/image2015-5-4-11-3a26-3a10.png)

1. Enter the information you took from Marketo earlier.

   ![](assets/image2015-5-4-11-3a27-3a16.png)

1. Click **Save.**

   ** ![](assets/image2015-5-4-11-3a28-3a13.png)

   **

## Set User Access {#set-user-access}

Set up user roles to give specific users access to Sales Insight.

1. Select **Settings**.

   ![](assets/image2015-5-4-11-3a30-3a54.png)

1. Select **Administration** in the tree.

   ![](assets/image2015-5-4-11-3a31-3a39.png)

1. Click **Users**.

   ![](assets/image2015-5-4-11-3a32-3a25.png)

1. Select the user(s) you want to grant access to and click **Manage Roles**.

   ![](assets/image2015-5-4-11-3a35-3a8.png)

1. Select the **Marketo Sales Insight** role and click **OK**.

   ![](assets/image2015-5-4-11-3a36-3a59.png)

   And that's it! All the users have access will now be able to see the sales insight section in the lead/contact detail view.

   ![](assets/image2015-5-4-11-3a39-3a23.png)

   Congrats. You have now unleashed the power of Marketo Sales Insight.

>[!NOTE]
>
>**Related Articles**
>
>[Setting up Stars and Flames for Lead/Contact Records](http://docs.marketo.com/x/BICMAg)

