---
unique-page-id: 2360364
description: Step 2 of 3 -Create a Salesforce User for Marketo (Enterprise/Unlimited) - Marketo Docs - Product Documentation
title: Step 2 of 3 -Create a Salesforce User for Marketo (Enterprise/Unlimited)
exl-id: 871f335c-7b1e-47e1-8320-a18fbf21a970
---
# Step 2 of 3: Create a [!DNL Salesforce] User for Marketo (Enterprise/Unlimited) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>These steps must be completed by a [!DNL Salesforce] administrator

>[!PREREQUISITES]
>
>[Step 1 of 3: Add Marketo Fields to [!DNL Salesforce] (Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)

In this article, you will set up user permissions in [!DNL Salesforce] profile, and create a Marketo-[!DNL Salesforce] integration account.

## Create a Profile {#create-a-profile}

1. Click **[!UICONTROL Setup]**.

   ![](assets/image2015-6-11-16-3a15-3a27.png)

1. Type "profiles" into the Nav search bar and click on the **[!UICONTROL Profiles]** link.

   ![](assets/sfdc-profiles-hands.png)

1. Click on **[!UICONTROL New]**.

   ![](assets/image2014-12-9-9-3a19-3a15.png)

1. Select **[!UICONTROL Standard User]**, name the profile “Marketo-Salesforce Sync” and click **[!UICONTROL Save]**.

   ![](assets/image2014-12-9-9-3a19-3a22.png)

## Set Profile Permissions {#set-profile-permissions}

1. Click **[!UICONTROL Edit]** to set the security permissions.

   ![](assets/image2014-12-9-9-3a19-3a30.png)

1. Under the **[!UICONTROL Administrative Permissions]** section, make sure the following boxes are checked:

    * [!UICONTROL API Enabled]
    * [!UICONTROL Edit HTML Templates]
    * [!UICONTROL Manage Public Documents]
    * [!UICONTROL Manage Public Templates]

   ![](assets/image2014-12-9-9-3a19-3a38.png)

   >[!TIP]
   >
   >Be sure to check the **[!UICONTROL Password Never Expires]** box.

1. Under the [!UICONTROL General User Permissions] section, make sure the following boxes are checked:

    * [!UICONTROL Convert Leads]
    * [!UICONTROL Edit Events]
    * [!UICONTROL Edit Tasks]

   ![](assets/image2014-12-9-9-3a19-3a47.png)

1. Under the [!UICONTROL Standard Object Permissions] section, make sure that [!UICONTROL Read, Create, Edit, and Delete] permissions are checked for:

    * [!UICONTROL Accounts]
    * [!UICONTROL Campaigns]
    * [!UICONTROL Contacts]
    * [!UICONTROL Leads]
    * [!UICONTROL Opportunities]

   >[!NOTE]
   >
   >Grant permissions to the [!UICONTROL Campaigns], if you plan to use Campaign Sync.

   ![](assets/image2014-12-9-9-3a19-3a57.png)

1. When finished, click **[!UICONTROL Save]** at the bottom of the page.

   ![](assets/image2014-12-9-9-3a20-3a5.png)

## Set Field Permissions {#set-field-permissions}

1. Discuss with your marketers to find out what custom fields are necessary to sync.

   >[!NOTE]
   >
   >This step will prevent fields you don't need from showing up in Marketo, which will reduce clutter and speed up sync.

1. In the profile detail page, go to **[!UICONTROL Field-Level Security]** section. Click **[!UICONTROL View]** to edit the accessibility for the objects:

    * [!UICONTROL Lead]
    * [!UICONTROL Contact]
    * [!UICONTROL Account]
    * [!UICONTROL Opportunity]

   >[!TIP]
   >
   >You may configure other objects according to your organization's needs.

   ![](assets/image2014-12-9-9-3a20-3a14.png)

1. For each object, click **[!UICONTROL Edit]**.

   ![](assets/sfdc-sync-field-edit1.png)

1. Locate the unneeded fields, make sure that **[!UICONTROL Read Access]** and **[!UICONTROL Edit Access]** are unchecked. Click **[!UICONTROL Save]** when you’re done.

   >[!NOTE]
   >
   >Only edit the accessibility for the custom fields.

   ![](assets/sfdc-sync-field-edit2.png)

1. After you finish disabling all unneeded fields, you must check **[!UICONTROL Read Access and Edit Access]** for the following object fields. Click **[!UICONTROL Save]** when you’re done.

<table> 
 <tbody> 
  <tr> 
   <th colspan="1" rowspan="1"><p>Object</p></th> 
   <th colspan="1" rowspan="1"><p>Fields</p></th> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Account</p></td> 
   <td colspan="1" rowspan="1"><p>Type field</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Event</p></td> 
   <td colspan="1" rowspan="1"><p>All fields</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Task</p></td> 
   <td colspan="1" rowspan="1"><p>All fields</p></td> 
  </tr> 
 </tbody> 
</table>

   ![](assets/sfdc-check-the-boxes.png)

## Create Marketo-Salesforce Sync Account {#create-marketo-salesforce-sync-account}

>[!TIP]
>
>Create a dedicated [!DNL Salesforce] account (e.g., marketo@yourcompany.com) to distinguish the changes made by Marketo versus other [!DNL Salesforce] users.

1. Type "Manage users" into the Nav search bar, then click on **[!UICONTROL Users]**. Click on **[!UICONTROL New User]**.

   ![](assets/sfdc-new-users.png)

1. Fill out the required fields. Then, select the **[!UICONTROL User License: Salesforce]** and the Profile that you previously created. Click **[!UICONTROL Save]** when you’re done.

   ![](assets/image2014-12-9-9-3a20-3a56.png)

Step 2 of 2 is completed.

>[!NOTE]
>
>[Step 3 of 3: Connect Marketo and [!DNL Salesforce] (Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)
