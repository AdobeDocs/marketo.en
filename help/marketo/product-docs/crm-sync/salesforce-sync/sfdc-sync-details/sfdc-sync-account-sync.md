---
unique-page-id: 2953459
description: SFDC Sync: Account Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Account Sync
---

# SFDC Sync: Account Sync {#sfdc-sync-account-sync}

Marketo also syncs your account information with Salesforce. Here's a few specific things you should know!

## Which way does the information sync? {#which-way-does-the-information-sync}

Only one way: from SFDC to Marketo.

## How do the updates work? {#how-do-the-updates-work}

If you update an Account field for a contact in Marketo, it changes the values of all those contacts belonging to that account in Marketo. It does not sync to SFDC. However, the next time that account is updated in SFDC, the changes will override all account information in Marketo.

## Can a contact belong to multiple accounts?  {#can-a-contact-belong-to-multiple-accounts}

No. An Account can have many contacts, a contact can have only one account.

## Can I create Accounts from Marketo? {#can-i-create-accounts-from-marketo}

Mostly, no. However, if you use the [Convert Person](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) flow step on a person, it will create a new Contact, a new Account, and a new Opportunity.

>[!CAUTION]
>
>This flow step has a very limited use case. If you aren't sure, you probably shouldn't use it.

## Does a change in an Account Field in Salesforce result in a Change Data Value Activity Log for each contact?  {#does-a-change-in-an-account-field-in-salesforce-result-in-a-change-data-value-activity-log-for-each-contact}

Mostly, yes. However, if an account has more than 5,000 contacts and a field on that account changes in SFDC, we sync down the change but do not log the activity for the 5,000+ contacts.
