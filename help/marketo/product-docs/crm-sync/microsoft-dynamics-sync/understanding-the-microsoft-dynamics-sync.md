---
unique-page-id: 10098625
description: Understanding the Microsoft Dynamics Sync - Marketo Docs - Product Documentation
title: Understanding the Microsoft Dynamics Sync
exl-id: bc87f744-7f1c-421b-8507-1a6e23d27fa2
feature: Microsoft Dynamics
---
# Understanding the Microsoft Dynamics Sync {#understanding-the-microsoft-dynamics-sync}

Marketo Engage and Microsoft Dynamics go together. We keep your sales and marketing data in sync.

>[!NOTE]
>
>Marketo only supports SSL certs that are compatible with Java 7 at this time.

>[!CAUTION]
>
>We do not currently support sandbox refresh for Marketo Dynamics Sync. If you need to refresh your Dynamics CRM sandbox, a new Marketo sandbox will be required. Please contact the Adobe Account Team (your Account Manager) for additional details.

## How Sync Works {#how-sync-works}

Marketo continuously syncs data with Microsoft Dynamics all day, every day. It's done using background sync, in batches, not in real time.

>[!NOTE]
>
>The very first sync in your subscription takes minutes to hours, depending on the size of your database. Marketo copies the entire database from Dynamics. After that, each sync typically takes seconds or minutes and only syncs data that has changed.

The sync between Marketo and Dynamics is bidirectional for leads and contacts. If you make changes in either Marketo or Dynamics, your updates will be reflected in both systems. All other fields, such as accounts and opportunities, are synced one way only, from Dynamics to Marketo.

## What is Synced between Marketo and Microsoft Dynamics? {#what-is-synced-between-marketo-and-microsoft-dynamics}

* [Leads](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [Contacts](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [Accounts](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [Users](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* Teams (groups of SystemUsers)
* [Opportunities](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [Custom entities](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/enable-sync-for-a-custom-entity.md)

The [credentials you enter in Marketo for Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md) are used to sync data over.

>[!NOTE]
>
>Instance copy is not supported if the source instance is integrated with Microsoft Dynamics.
