---
unique-page-id: 3571836
description: Microsoft Dynamics Sync -Account Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync -Account Sync
exl-id: 86249d33-60dd-47e1-a7c8-3996c9444084
---
# Microsoft Dynamics Sync: Account Sync {#microsoft-dynamics-sync-account-sync}

Did you know Marketo syncs your entire database with Dynamics? It syncs, then waits 5 minutes and then syncs again, all day, every day. Here are some details about how Marketo treats Dynamics Accounts specifically.

## Which way does the information sync? {#which-way-does-the-information-sync}

Only one way: from Dynamics to Marketo.

## How do the updates work? {#how-do-the-updates-work}

If you update an Account field for a contact in Marketo, it changes the values of all those contacts belonging to that account in Marketo. It does not sync to Dynamics. However, the next time that account is updated in Dynamics, the changes will override all account information in Marketo.

## Can I create an account using Marketo? {#can-i-create-an-account-using-marketo}

No. Marketo cannot create accounts in Dynamics.

## Which fields will sync to Marketo? {#which-fields-will-sync-to-marketo}

You can [select fields to sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync) during setup. But Marketo will only sync the fields that your Dynamics sync user has access to.

## Does a Change in an Account Field in Dynamics results in a Change Data Value Activity Log for Each Contact?  {#does-a-change-in-an-account-field-in-dynamics-results-in-a-change-data-value-activity-log-for-each-contact}

Mostly, yes. However, if an account has more than 5,000 contacts and a field on that account changes in Dynamics, we sync down the change but do not log the activity for the 5,000+ contacts.
