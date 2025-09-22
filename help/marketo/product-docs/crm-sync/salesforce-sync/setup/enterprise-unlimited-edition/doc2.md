---
description: "Step 2 of 3 - Create a Salesforce User for Marketo (Enterprise/Unlimited) - Marketo Docs - Product Documentation"
title: Step 2 of 3 - Create a Salesforce User for Marketo (Enterprise/Unlimited)
hide: yes
hidefromtoc: yes
feature: Salesforce Integration
---
# Step 2 of 3: Create a Salesforce User for Marketo (Enterprise/Unlimited) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>These steps must be completed by a Salesforce administrator

>[!PREREQUISITES]
>
>[Step 1 of 3: Add Marketo Fields to Salesforce (Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md){target="_blank"}

In this article, you will set up user permissions in Salesforce profile, and create a Marketo-Salesforce integration account.

## Create a Profile {#create-a-profile}

1. Click **[!UICONTROL Setup]**.

   SCREENSHOT

1. Type "profiles" into the Nav search bar and click on the Profiles link.

   SCREENSHOT

1. Click on New Profile.

   SCREENSHOT

1. Select Standard User, name the profile "Marketo-Salesforce Sync" and click Save.

   SCREENSHOT

## Set Profile Permissions {#set-profile-permissions}

1. Click Edit to set the security permissions.

   SCREENSHOT

1. Under the Administrative Permissions section, make sure the following boxes are checked:

   * API Enabled
   * Edit HTML Templates
   * Manage Public Documents
   * Manage Public Templates

   >[!TIP]
   >
   >Be sure to check the Password Never Expires box.

1. Under the General User Permissions section, make sure the following boxes are checked:

   * Convert Leads
   * Edit Events
   * Edit Tasks

1. Under the Standard Object Permissions section, make sure that Read, Create, Edit, and Delete permissions are checked for:

   * Accounts
   * Campaigns
   * Contacts
   * Leads
   * Opportunities

   >[!NOTE]
   >
   >Grant permissions to the Campaigns, if you plan to use Campaign Sync.

   SCREENSHOT

1. When finished, click Save at the bottom of the page.

   SCREENSHOT

## Set Field Permissions {#set-field-permissions}

1. Discuss with your marketers to find out what custom fields are necessary to sync.

   >[!NOTE]
   >
   >This step will prevent fields you don't need from showing up in Marketo, which will reduce clutter and speed up sync.

1. In the profile detail page, go to Field-Level Security section. Click View to edit the accessibility for the objects:

   * Lead
   * Contact
   * Account
   * Opportunity

   >[!TIP]
   >
   >You may configure other objects according to your organization's needs.

1. For each object, click Edit.

   SCREENSHOT

1. Locate the unneeded fields, make sure that Read Access and Edit Access are unchecked. Click Save when done.

   >[!NOTE]
   >
   >Only edit the accessibility for the custom fields.

   SCREENSHOT

1. After you finish disabling all unneeded fields, you must check Read Access and Edit Access for the following object fields. Click Save when done.

   TABLE

   SCREENSHOT

## Create Marketo-Salesforce Sync Account {#create-marketo-salesforce-sync-account}

   >[!TIP]
   >
   >Create a dedicated Salesforce account (e.g., `marketo@yourcompany.com`) to distinguish the changes made by Marketo versus other Salesforce users.

1. Type "Manage users" into the Nav search bar, then click on Users. Click New User.

   SCREENSHOT

   SCREENSHOT

1. Fill out the required fields. Then, select the User License: Salesforce and the Profile that you previously created. Click Save when you're done.

   SCREENSHOT

Step 2 of 3 is completed.
