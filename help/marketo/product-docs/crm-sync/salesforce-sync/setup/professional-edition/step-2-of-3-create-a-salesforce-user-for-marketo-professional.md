---
unique-page-id: 3571797
description: Step 2 of 3 -Create a Salesforce User for Marketo (Professional) - Marketo Docs - Product Documentation
title: Step 2 of 3 -Create a Salesforce User for Marketo (Professional)
exl-id: 7eb4bf89-b6e4-45e0-adee-e2976cb01dd3
feature: Salesforce Integration
---
# Step 2 of 3: Create a Salesforce User for Marketo (Professional) {#step-of-create-a-salesforce-user-for-marketo-professional}

>[!NOTE]
>
>These steps must be completed by a Salesforce administrator.

>[!PREREQUISITES]
>
>[Step 1 of 3: Add Marketo Fields to Salesforce (Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-1-of-3-add-marketo-fields-to-salesforce-professional.md){target="_blank"}

In this article, you will customize field permissions with a Salesforce Page Layout and create a Marketo-Salesforce sync user.

## Set Page Layouts {#set-page-layouts}

Salesforce Professional sets field level accessibility with Page Layouts, as opposed to Salesforce Enterprise/Unlimited's Profiles. Following these steps will allow the Marketo sync user to update the custom fields.

1. Type "[!UICONTROL page layouts]" in the Nav search bar without pressing **[!UICONTROL Enter]**, and click **[!UICONTROL Page Layout]** under **[!UICONTROL Leads]**.

   ![](assets/image2016-2-26-12-3a58-3a32.png)

1. Click **[!UICONTROL Edit]** next to Lead Layout.

   ![](assets/image2016-2-26-13-3a2-3a46.png)

1. Click and drag a new **[!UICONTROL Section]** into the page layout.

   ![](assets/image2014-12-9-12-3a56-3a40.png)

1. Enter "Marketo" for **[!UICONTROL Section Name]** and click **[!UICONTROL OK]**.

   ![](assets/image2014-12-9-12-3a56-3a52.png)

1. Click and drag the field **[!UICONTROL Acquisition Date]** into the **Marketo** section.

   ![](assets/image2014-12-9-12-3a57-3a0.png)

1. Repeat the above step for the following fields:

    * Acquisition Program
    * Acquisition Program Id
    * Email Opt Out
    * Inferred City
    * Inferred Company
    * Inferred Country
    * Inferred Metropolitan Area
    * Inferred Phone Area Code
    * Inferred Postal Code
    * Inferred State Region
    * Lead Score
    * Original Referrer
    * Original Search Engine
    * Original Search Phrase
    * Original Source Info
    * Original Source Type

   >[!NOTE]
   >
   >These fields need to be on the page layout so that Marketo can read/write to them.

   >[!TIP]
   >
   >Create two columns for the fields by dragging down to the right side of the page. You can move fields from one side to the other to balance the column lengths.

1. Click **[!UICONTROL Save]** when finished adding fields.

   ![](assets/image2014-12-9-12-3a57-3a10.png)

1. Repeat all of the above steps for the Salesforce **[!UICONTROL Contact Page Layout]**.

   ![](assets/image2016-2-26-13-3a10-3a1.png)

1. Remember to click **[!UICONTROL Save]** when you are done with the **[!UICONTROL Contact Page Layout]**.

   ![](assets/image2014-12-9-12-3a57-3a30.png)

   >[!NOTE]
   >
   >Make sure that the **[!UICONTROL All-Day Event]** field has been added to the **[!UICONTROL Event Page Layout]**.

## Create Sync User {#create-sync-user}

Marketo requires credentials to access Salesforce. This is best done with a dedicated user created with the steps below.

>[!NOTE]
>
>If your organization has no additional Salesforce licenses, you can use an existing Marketing user with the System Administrator profile.

1. Enter "users" in the Nav search bar, and click **[!UICONTROL Users]** under **[!UICONTROL Manage Users]**.

   ![](assets/image2014-12-9-12-3a57-3a42.png)

1. Click **[!UICONTROL New User]**.

   ![](assets/image2014-12-9-12-3a58-3a1.png)

1. Fill in the required fields, select the **[!UICONTROL User License: Salesforce]**, set the **[!UICONTROL Profile: System Administrator]**, check **[!UICONTROL Marketing User]** and click **[!UICONTROL Save]**.

   ![](assets/image2014-12-9-12-3a58-3a11.png)

   >[!TIP]
   >
   >Make sure the email address you enter is valid. You will need to log in as the sync user to reset the password.

Excellent! Now you have an account that Marketo can use to connect to Salesforce. Let's do it.

>[!MORELIKETHIS]
>
>[Step 3 of 3: Connect Marketo and Salesforce (Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-3-of-3-connect-marketo-and-salesforce-professional.md){target="_blank"}
