---
description: Why Aren't My Sales Activities and Activity Fields Syncing to Salesforce? - Marketo Docs - Product Documentation
title: Why Aren't My Sales Activities and Activity Fields Syncing to Salesforce?
exl-id: 0836876d-1b89-4464-a841-81320a6e45fd
---
# Why Aren't My Sales Activities and Activity Fields Syncing to Salesforce? {#why-arent-my-sales-activities-and-activity-fields-syncing-to-salesforce}

**I'm not seeing email or call activities synced to Salesforce.**

* Make sure you're connected to Salesforce. Each user will need to have a connection to log their email and calls to Salesforce. 
* Make sure you have configured [Salesforce Sync Settings](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md){target="_blank"}.
* Emails will do a record lookup based on Salesforce ID as the primary lookup and email address as the secondary. You can confirm that a person record has a Salesforce ID and email address linked to them in the [Actions web app](https://toutapp.com/next#command_center){target="_blank"}.
* Calls will do a record lookup based on Salesforce ID only. If no Salesforce ID exists on the person record in Actions, the call will not log. You can confirm that a person record has a Salesforce ID linked to them in the [Actions web app](https://toutapp.com/next#command_center){target="_blank"}.

**I'm not seeing activity fields in Salesforce update.**

If you're not seeing email [activity attribute fields](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"} update in Salesforce, it might be due to restrictions on your team's Field Accessibility. Salesforce Field Level security gives Salesforce Admins the ability to put restrictions around what information is viewable and editable by users. If Actions users do not have access to view and edit these fields, the Actions activity sync will fail to update these fields.

* Work with your Salesforce Admin to ensure these security settings are not interfering with [Actions Salesforce Activity fields](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"}.
* If you're a Salesforce Admin, you can see your Field Accessibility under the Security Controls tab. The main objects that Actions will interact with are: Leads, Contacts, Accounts, Opportunities, and Task/Activities.

>[!NOTE]
>
>Fields associated with the Lead, Contact, Account, and Opportunity objects will be installed with the Sales Insight Salesforce package. Fields associated with the [Task/Activity record type will need to be created](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"} by a Salesforce Admin.
