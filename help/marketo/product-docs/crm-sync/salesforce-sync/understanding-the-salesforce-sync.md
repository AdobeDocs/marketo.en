---
unique-page-id: 4719283
description: Understanding the Salesforce Sync - Marketo Docs - Product Documentation
title: Understanding the Salesforce Sync
exl-id: 658c81ff-5fb3-4ad8-8759-da55bbf4e263
feature: Salesforce Integration
---
# Understanding the Salesforce Sync {#understanding-the-salesforce-sync}

Marketo Engage and Salesforce go together like peas and carrots. We keep your sales and marketing data in sync.

## How Sync Works {#how-sync-works}

Marketo syncs with Salesforce all day, every day. Each sync takes some time and then pauses for 5 minutes, then starts again.

>[!NOTE]
>
>The very first sync in your subscription may take hours or even days because Marketo is copying the entire database from Salesforce. After that, each sync typically takes seconds or minutes and only syncs data that has changed.

![](assets/sync-illustration.png)

The sync between Salesforce and Marketo is bidirectional only for leads, contacts, and Salesforce campaigns. In these cases, whenever you make changes in either Salesforce or Marketo, your updates will be reflected in both systems. All other syncs are from Salesforce to Marketo only. Click the links below for details on each one.

## What is Synced between Marketo and Salesforce? {#what-is-synced-between-marketo-and-salesforce}

* [Leads](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-sync.md){target="_blank"}
* [Contacts](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md){target="_blank"}
* [Accounts](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md){target="_blank"}
* [Users](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md){target="_blank"}
* [Opportunities](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-opportunity-sync.md){target="_blank"}
* [Salesforce campaigns](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md){target="_blank"}
* [Custom objects](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.md){target="_blank"}
* [Activity](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-activity-sync.md){target="_blank"}

>[!NOTE]
>
>The [credentials you enter in Marketo for Salesforce](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} are used to sync data over. Only data those credentials have access to will be included.

Marketo's sync with Salesforce is the most powerful of its kind in the world. It feels like magic; a change is made and the other system is soon up-to-date.
