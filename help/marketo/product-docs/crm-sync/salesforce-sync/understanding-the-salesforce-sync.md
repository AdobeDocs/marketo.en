---
unique-page-id: 4719283
description: Understanding the Salesforce Sync - Marketo Docs - Product Documentation
title: Understanding the Salesforce Sync
exl-id: 658c81ff-5fb3-4ad8-8759-da55bbf4e263
---
# Understanding the [!DNL Salesforce] Sync {#understanding-the-salesforce-sync}

Marketo and [!DNL Salesforce] go together like peas and carrots. We keep your sales and marketing data in sync.

## How Sync Works {#how-sync-works}

Marketo syncs with [!DNL Salesforce] all day, every day. Each sync takes some time and then pauses for 5 minutes, then starts again.

>[!NOTE]
>
>The very first sync in your subscription may take hours or even days because Marketo is copying the entire database from [!DNL Salesforce]. After that, each sync typically takes seconds or minutes and only syncs data that has changed.

![](assets/sync-illustration.png)

The sync between [!DNL Salesforce] and Marketo is bidirectional only for leads, contacts, and [!DNL Salesforce] campaigns. In these cases, whenever you make changes in either [!DNL Salesforce] or Marketo, your updates will be reflected in both systems. All other syncs are from [!DNL Salesforce] to Marketo only. Click the links below for details on each one.

## What is Synced between Marketo and [!DNL Salesforce]? {#what-is-synced-between-marketo-and-salesforce}

* [Leads](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-sync.md)
* [Contacts](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md)
* [Accounts](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md)
* [Users](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md)
* [Opportunities](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-opportunity-sync.md)
* [[!DNL Salesforce] campaigns](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md)
* [Custom objects](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.md)
* [Activity](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-activity-sync.md)

>[!NOTE]
>
>The [credentials you enter in Marketo for [!DNL Salesforce]](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) are used to sync data over. Only data those credentials have access to will be included.

Marketo's sync with [!DNL Salesforce] is the most powerful of its kind in the world. It feels like magic; a change is made and the other system is soon up-to-date.
