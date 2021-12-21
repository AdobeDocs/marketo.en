---
description: MSI Actions Admin Guide - Marketo Docs - Product Documentation
title: MSI Actions Admin Guide
hide: yes
hidefromtoc: yes
---
# MSI Actions Admin Guide {#msi-actions-admin-guide}

>[!PREREQUISITES]
>
>* Confirm with your Customer Success Manager that MSI Actions has been enabled for your Marketo Account (If you do not have a CSM, please [contact Support](https://nation.marketo.com/t5/support/ct-p/Support)).
>* Your Marketo/Salesforce sync must be set up.

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
  <td>Marketo Admin or <br/>Salesforce Admin</td>
  <td>Connect Marketo Sales account to Salesforce</td>
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
  <td>Salesforce Admin</td>
  <td>Install/Upgrade MSI Package in Salesforce</td>
 </tr>
 <tr>
  <td>Salesforce Admin</td>
  <td>Configure MSI-Actions in Salesforce</td>
 </tr>
</table>

## Set up Marketo Sales Account {#set-up-marketo-sales-account}

1. In Marketo, click **Admin**.

PICC

1. Click **Sales Insight**, then **Actions Config**. Select from a list of Marketo admins to invite and click **Send Invite**.

PICC

The user will receive an email with steps to get access to the account.

>[!NOTE]
>
>Additional users will not be added through Marketo and will instead be added through the Sales Account User Management page. [Click here](/help/marketo/product-docs/marketo-sales-connect/admin/invite-users.md) to learn more about adding additional users.

## Connect Marketo Sales Account to Salesforce {#connect-marketo-sales-account-to-salesforce}

1. In your Marketo Sales account, click the gear icon and select **Settings**.

PICC

1. Under Admin Settings, click **Salesforce**.

PICC

1. In the Connections & Customizations tab, click **Connect**.

PICC

1. Click **OK**.

PICC

If you’re already logged in to Salesforce, you’ll be connected. If you’re not, you’ll be asked to log in.

## Connect Marketo to Your Sales Apps Account {#connect-marketo-to-your-sales-apps-account}

1. In your Marketo Sales account, click the gear icon and select **Settings**.

PICC

1. Under Admin Settings, click **Marketo**.

PICC

1. Click **connect**. Your account will then be connected.

>[!NOTE]
>
>If it doesn't connect, copy the credentials from Marketo Sales Insight “Actions Config” tab and paste them in the Set Up tab.

## Initiate Data Sync {#initiate-data-sync}

1. In Marketo, click Admin.

PICC

1. Click Sales Insight, then Actions Config.

PICC

1. In the Action Field Sync card, click **Sync**.

PICC

1. You'll see a preview of the fields that will be synced. Click **Start Sync**.

PICC

Person records that exist in Marketo and Salesforce will be synced to your Marketo Sales Apps account.

## Invite Individual Users to MSI Actions {#invite-individual users-to-msi-actions}

1. In your Marketo Sales account, click the gear icon and select **Settings**.

PICC

1. Under Admin Settings, select **User Management**.

PICC

1. Click **Actions** and select **Invite Users**.

PICC

1. Enter the email address(es) and click **Invite**.

>[!NOTE]
>
>By default, all new members will be added to the Everyone team.

You'll receive a confirmation message.

## Invite Users via CSV to MSI Actions {#invite-users-via-csv-to-msi-actions}

1. In your Marketo Sales account, click the gear icon and select **Settings**.

PICC

1. Under Admin Settings, select **User Management**.

PICC

1. Click **Actions** and select **Invite Users via CSV**.

PICC

1. Browse for the CSV on your computer, select it, and click **Next**.

PICC

1. Confirm that the fields are mapped properly and click **Invite**.

PICC

You'll receive a confirmation message once the invites are sent.

>[!NOTE]
>
>Once this is done, you can either upgrade your existing MSI package or install a new one and move on to [configuring MSI Actions in Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/salesforce-configuration/msi-actions-configuration-in-salesforce.md).
