---
description: Add Sales Insight Access to Profiles - Marketo Docs - Product Documentation
title: Add Sales Insight Access to Profiles
exl-id: 269f9093-f530-4e3b-aac7-e317976cf0f0
---
# Add [!DNL Sales Insight] Access to Profiles {#add-sales-insight-access-to-profiles}

Here's how to create a profile with access to [!DNL Sales Insight] while removing access for your other profiles. This is for users who have already installed the [[!DNL Sales Insight] AppExchange package](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}.

>[!IMPORTANT]
>
>If you’ve previously given [!DNL Sales Insight] access to all profiles, you must [remove profile level access](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md){target="_blank"} to use this permission set.

## Create a New Profile for [!DNL Sales Insight] {#create-a-new-profile-for-sales-insight}

If you have a dedicated profile for your [!DNL Sales Insight] users, you can skip this step.

1. In [!DNL Salesforce], go to the Setup page.

1. Search for profiles in Quick Find and select the **[!UICONTROL Profile]** option.

1. Click the **[!UICONTROL New Profile]** button at the top of the page.

1. Pick a profile to clone and give it a name (ex: Sales Insight User).

1. Click **[!UICONTROL Save]** when done.

## Add [!DNL Sales Insight] Permissions {#add-sales-insight-permissions}

1. Go back to your Profiles list.

1. Click the **[!UICONTROL Edit]** link for the new profile you just created (or any other existing profile you’d like to give [!DNL Sales Insight] Access to).

1. On the edit page, you'll need to change a few settings.

   **For profiles that are allowed access [!DNL Sales Insight]**:

   * In Tab Settings, change the Marketo tabs to Default On
   * In Custom Object Permissions, check Read, Create, Edit, and Delete on [!DNL Marketo Sales Insight] Config (if the user should have access to the config settings - typically used for Admins)

   **For profiles that are not allowed access to [!DNL Sales Insight]**:

   * In Tab Settings, change the Marketo tabs to Tab Hidden
   * In Custom Object Permissions, uncheck Read, Create, Edit, and Delete on [!DNL Marketo Sales Insight] Config

1. Click **[!UICONTROL Save]** when done.

## Create Layout for [!DNL Sales Insight] {#create-layout-for-sales-insight}

1. Go to the Setup page, then click **[!UICONTROL App Setup]** > **[!UICONTROL Customize]** > **[!UICONTROL Leads]** > **[!UICONTROL Page Layouts]**. Then click the **[!UICONTROL New]** button.

1. Clone your layout of choice and give the layout an appropriate name (ex: Sales Insight Layout).  

1. Click **[!UICONTROL Save]** when done.

1. Repeat these steps for your [!UICONTROL Contacts], [!UICONTROL Opportunities], and [!UICONTROL Accounts]' page layouts.

## Assign Profile to Layout {#assign-profile-to-layout}

1. Go back to the Page Layouts section and click the **[!UICONTROL Page Layout Assignment]** button.

1. Select **[!UICONTROL Edit Assignment]**.

1. Select your [!DNL Sales Insight] profile from the list, then select your [!DNL Sales insight] layout from the “[!UICONTROL Select Page Layout]” drop-down.

1. Click **[!UICONTROL Save]** when done.

1. Repeat these steps for your [!UICONTROL Contacts], [!UICONTROL Opportunities], and [!UICONTROL Accounts]' page layouts.

## Other Changes {#other-changes}

Here are some other places where [!DNL Sales Insight] items could appear. You'll have to remove them outright since you can't use Profiles to limit their access:

* Remove [!DNL Sales Insight] buttons from Search Layouts for [!UICONTROL Contacts], [!UICONTROL Leads], and [!UICONTROL Accounts]
* Remove [!DNL Sales Insight] columns from Contact and Lead lists
