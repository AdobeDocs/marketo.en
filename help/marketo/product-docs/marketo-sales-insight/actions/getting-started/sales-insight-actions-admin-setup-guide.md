---
description: Sales Insight Actions Admin Setup Guide - Marketo Docs - Product Documentation
title: Sales Insight Actions Admin Setup Guide
exl-id: 339d518d-445b-4634-ab81-92c9d5541927
---
# Sales Insight Actions Admin Setup Guide {#sales-insight-actions-admin-setup-guide}

>[!PREREQUISITES]
>
>* Confirm with your Customer Success Manager that MSI Actions has been enabled for your Marketo Account (if you do not have a CSM, contact [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}).
>* Your Marketo/[!DNL Salesforce] sync must be set up.

<table>
 <tr>
  <th>Persona</th>
  <th>Step</th>
 </tr>
 <tr>
  <td>Marketo Admin</td>
  <td>Set up Marketo Sales account</td>
 </tr>
 <tr>
  <td>Marketo Admin or <br/>[!DNL Salesforce] Admin</td>
  <td>Connect Marketo Sales account to [!DNL Salesforce]</td>
 </tr>
 <tr>
  <td>Marketo Admin</td>
  <td>Connect Marketo Sales account to Marketo</td>
 </tr>
 <tr>
  <td>Marketo Admin</td>
  <td>Initiate Data Sync from Marketo to Marketo Sales Account</td>
 </tr>
 <tr>
  <td>Marketo Admin</td>
  <td>Invite users to MSI-Actions</td>
 </tr>
 <tr>
  <td>[!DNL Salesforce] Admin</td>
  <td>Install/Upgrade MSI Package in [!DNL Salesforce]</td>
 </tr>
 <tr>
  <td>[!DNL Salesforce] Admin</td>
  <td>Configure MSI-Actions in [!DNL Salesforce]</td>
 </tr>
</table>

## Set up Marketo Sales Account {#set-up-marketo-sales-account}

1. In Marketo, click **[!UICONTROL Admin]**.

   ![](assets/msi-actions-admin-guide-1.png)

1. Click **[!UICONTROL Sales Insight]**, then **[!UICONTROL Actions Config]**. Select from a list of Marketo admins to invite and click **[!UICONTROL Send Invite]**.

   ![](assets/msi-actions-admin-guide-2.png)

The user will receive an email with steps to get access to the account.

>[!NOTE]
>
>Additional users will not be added through Marketo and will instead be added through the Sales Account User Management page. [Click here](/help/marketo/product-docs/marketo-sales-connect/admin/invite-users.md){target="_blank"} to learn more about adding additional users.

## Connect Marketo Sales Account to [!DNL Salesforce] {#connect-marketo-sales-account-to-salesforce}

1. In your Marketo Sales account, click the gear icon and select **[!UICONTROL Settings]**.

   ![](assets/msi-actions-admin-guide-3.png)

1. Under [!UICONTROL Admin Settings], click **[!UICONTROL Salesforce]**.

   ![](assets/msi-actions-admin-guide-4.png)

1. In the [!UICONTROL Connections & Customizations] tab, click **[!UICONTROL Connect]**.

   ![](assets/msi-actions-admin-guide-5.png)

1. Click **[!UICONTROL OK]**.

   ![](assets/msi-actions-admin-guide-6.png)

If you’re already logged in to [!DNL Salesforce], you’ll be connected. If you’re not, you’ll be asked to log in.

## Connect Marketo to Your Sales Apps Account {#connect-marketo-to-your-sales-apps-account}

1. In your Marketo Sales account, click the gear icon and select **[!UICONTROL Settings]**.

   ![](assets/msi-actions-admin-guide-7.png)

1. Under [!UICONTROL Admin Settings], click **Marketo**.

   ![](assets/msi-actions-admin-guide-8.png)

1. Click **[!UICONTROL connect]**. Your account will then be connected.

   ![](assets/msi-actions-admin-guide-9.png)

>[!NOTE]
>
>If it doesn't connect, copy the credentials from Marketo Sales Insight “[!UICONTROL Actions Config]” tab and paste them in the [!UICONTROL Set Up] tab.

## Initiate Data Sync {#initiate-data-sync}

The data unification field sync for Sales Insight Actions enables the system to pull person information from your Marketo Engage database into your Sales Insight Actions database, keeping your people data up-to-date and ensuring activities are logged to the right records across Marketo and [!DNL Salesforce].

>[!CAUTION]
>
>Once you initiate data sync, you should **not** remove the original user on your Sales Insight Actions instance. This is the user that the first invite was sent to.

1. In Marketo, click **[!UICONTROL Admin]**.

   ![](assets/msi-actions-admin-guide-10.png)

1. Click **[!UICONTROL Sales Insight]**.

   ![](assets/msi-actions-admin-guide-11.png)

1. Click the **[!UICONTROL Actions Config]** tab. In the Action Field Sync card, click **[!UICONTROL Sync]**.

   ![](assets/msi-actions-admin-guide-12.png)

1. You'll see a preview of the fields that will be synced. Click **[!UICONTROL Start Sync]**.

   ![](assets/msi-actions-admin-guide-13.png)

Person records that exist in Marketo and [!DNL Salesforce] will be synced to your Marketo Sales Apps account.

   >[!NOTE]
   >
   >To learn more about how people and activity data syncs between Sales Insight Actions, Marketo, and [!DNL Salesforce], [click here](/help/marketo/product-docs/marketo-sales-insight/actions/admin/actions-data-sync-faq.md){target="_blank"}.

## Invite Individual Users to MSI Actions {#invite-individual-users-to-msi-actions}

1. In your Marketo Sales account, click the gear icon and select **[!UICONTROL Settings]**.

   ![](assets/msi-actions-admin-guide-14.png)

1. Under [!UICONTROL Admin Settings], select **[!UICONTROL User Management]**.

   ![](assets/msi-actions-admin-guide-15.png)

1. Click **[!UICONTROL Actions]** and select **[!UICONTROL Invite Users]**.

   ![](assets/msi-actions-admin-guide-16.png)

1. Enter the email address(es) and click **[!UICONTROL Invite]**.

   ![](assets/msi-actions-admin-guide-17.png)

>[!NOTE]
>
>By default, all new members will be added to the Everyone team.

You'll receive a confirmation message.

## Invite Users via CSV to MSI Actions {#invite-users-via-csv-to-msi-actions}

1. In your Marketo Sales account, click the gear icon and select **[!UICONTROL Settings]**.

   ![](assets/msi-actions-admin-guide-18.png)

1. Under [!UICONTROL Admin Settings], select **[!UICONTROL User Management]**.

   ![](assets/msi-actions-admin-guide-19.png)

1. Click **[!UICONTROL Actions]** and select **[!UICONTROL Invite Users via CSV]**.

   ![](assets/msi-actions-admin-guide-20.png)

1. Browse for the CSV on your computer, select it, and click **[!UICONTROL Next]**.

   ![](assets/msi-actions-admin-guide-21.png)

1. Confirm that the fields are mapped properly and click **[!UICONTROL Invite]**.

   ![](assets/msi-actions-admin-guide-22.png)

You'll receive a confirmation message once the invites are sent.

>[!NOTE]
>
>Once this is done, you can either upgrade your existing MSI package or install a new one and move on to [configuring MSI Actions in [!DNL Salesforce]](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-configuration/sales-insight-actions-configuration-in-salesforce.md){target="_blank"}.
