---
description: Add Sales Insight Access to Profiles - Marketo Docs - Product Documentation
title: Add Sales Insight Access to Profiles
exl-id: 269f9093-f530-4e3b-aac7-e317976cf0f0
---
# Add Sales Insight Access to Profiles {#add-sales-insight-access-to-profiles}

Here's how to create a profile with access to Sales Insight while removing access for your other profiles. This is for users who have already installed the [Sales Insight AppExchange package](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}.

>[!IMPORTANT]
>
>If you’ve previously given Sales Insight access to all profiles, you must [remove profile level access](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md){target="_blank"} to use this permission set.

## Create a New Profile for Sales Insight {#create-a-new-profile-for-sales-insight}

If you have a dedicated profile for your Sales Insight users, you can skip this step.

1. In Salesforce, go to the Setup page.

1. Search for profiles in Quick Find and select the **Profile** option.

1. Click the **New Profile** button at the top of the page.

1. Pick a profile to clone and give it a name (ex: Sales Insight User).

1. Click **Save** when done.

## Add Sales Insight Permissions {#add-sales-insight-permissions}

1. Go back to your Profiles list.

1. Click the **Edit** link for the new profile you just created (or any other existing profile you’d like to give Sales Insight Access to).

1. On the edit page, you'll need to change a few settings.

   **For profiles that are allowed access Sales Insight**:

   * In Tab Settings, change the Marketo tabs to Default On
   * In Custom Object Permissions, check Read, Create, Edit, and Delete on Marketo Sales Insight Config (if the user should have access to the config settings - typically used for Admins)

   **For profiles that are not allowed access to Sales Insight**:

   * In Tab Settings, change the Marketo tabs to Tab Hidden
   * In Custom Object Permissions, uncheck Read, Create, Edit, and Delete on Marketo Sales Insight Config

1. Click **Save** when done.

## Create Layout for Sales Insight {#create-layout-for-sales-insight}

1. Go to the Setup page, then click **App Setup** > **Customize** > **Leads** > **Page Layouts**. Then click the **New** button.

1. Clone your layout of choice and give the layout an appropriate name (ex: Sales Insight Layout).  

1. Click **Save** when done.

1. Repeat these steps for your Contacts, Opportunities, and Accounts' page layouts.

## Assign Profile to Layout {#assign-profile-to-layout}

1. Go back to the Page Layouts section and click the **Page Layout Assignment** button.

1. Select **Edit Assignment**.

1. Select your Sales Insight profile from the list, then select your Sales insight layout from the “Select Page Layout” drop-down.

1. Click **Save** when done.

1. Repeat these steps for your Contacts, Opportunities, and Accounts' page layouts.

## Other Changes {#other-changes}

Here are some other places where Sales Insight items could appear. You'll have to remove them outright since you can't use Profiles to limit their access:

* Remove Sales Insight buttons from Search Layouts for Contacts, Leads, and Accounts
* Remove Sales Insight columns from Contact and Lead lists
