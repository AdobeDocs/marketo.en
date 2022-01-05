---
unique-page-id: 3571840
description: Microsoft Dynamics Sync -User Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync -User Sync
exl-id: d642d4d2-2beb-42c6-a6b2-3da5df1cd9c8
---
# Microsoft Dynamics Sync: User Sync {#microsoft-dynamics-sync-user-sync}

Did you know Marketo syncs your entire database with Dynamics? It syncs, then waits 5 minutes and then syncs again, all day, every day. Here are some details about how Marketo treats Dynamics Accounts specifically.

You will need a dedicated Microsoft Dynamics CRM user for the purpose of the integration. We call this user the Sync User.

## How are user details kept in sync between the two systems? {#how-are-user-details-kept-in-sync-between-the-two-systems}

The user sync is one way - Dynamics to Marketo. If you make changes to a user in Dynamics the changes will be reflected in Marketo.

## Can I create an user using Marketo? {#can-i-create-an-user-using-marketo}

No. Marketo cannot create users in Dynamics.

## Which fields will sync to Marketo? {#which-fields-will-sync-to-marketo}

You can [select fields to sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-4-of-4-connect.md#select-fields-to-sync) during setup. But Marketo will only sync the fields that your Dynamics sync user has access to.
