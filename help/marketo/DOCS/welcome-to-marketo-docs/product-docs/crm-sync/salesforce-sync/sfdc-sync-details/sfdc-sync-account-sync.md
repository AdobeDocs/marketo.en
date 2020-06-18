---
unique-page-id: 2953459
description: SFDC Sync: Account Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Account Sync
---

# SFDC Sync: Account Sync {#sfdc-sync-account-sync}

SFDC Sync: Account Sync - Marketo Docs - Product Documentation

Marketo also syncs your account information with Salesforce. Here's a few specific things you should know!

### What's in this article? {#what-s-in-this-article}

[Which way does the information sync?](#sfdcsync-accountsync-whichwaydoestheinformationsync)  
[How do the updates work?](#sfdcsync-accountsync-howdotheupdateswork)  
[Can a contact belong to multiple accounts?](#sfdcsync-accountsync-canacontactbelongtomultipleaccounts)  
[Can I create Accounts from Marketo?](#sfdcsync-accountsync-canicreateaccountsfrommarketo)  
[Does a change in an Account Field in Salesforce result in a Change Data Value Activity Log for each contact?](#sfdcsync-accountsync-doesachangeinanaccountfieldinsalesforceresultinachangedatavalueactivitylogforeachcontact)

#### Which way does the information sync? {#sfdcsync-accountsync-whichwaydoestheinformationsync}

Only one way: from&nbsp;SFDC&nbsp;to Marketo.

#### How do the updates work? {#sfdcsync-accountsync-howdotheupdateswork}

If you update an Account field for a contact in Marketo, it changes the values of all those contacts belonging to that account in Marketo. It does not sync to SFDC. However, the next time that account is updated in SFDC, the changes will override all account information in Marketo.&nbsp;

#### Can a contact belong to multiple accounts?&nbsp; {#sfdcsync-accountsync-canacontactbelongtomultipleaccounts}

No. An Account can have many contacts, a contact can have only one account.

#### Can I create Accounts from Marketo? {#sfdcsync-accountsync-canicreateaccountsfrommarketo}

Mostly, no. However, if you use the&nbsp; [Convert Person](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)&nbsp;flow step on a person, it will create a new Contact, a new Account, and a new Opportunity.&nbsp;

>[!CAUTION]
>
>This flow step has a very limited use case. If you aren't sure, you probably shouldn't use it.

#### Does a change in an Account Field in Salesforce result in a Change Data Value Activity Log for each contact?&nbsp; {#sfdcsync-accountsync-doesachangeinanaccountfieldinsalesforceresultinachangedatavalueactivitylogforeachcontact}

Mostly, yes. However, if an account has more than 5,000 contacts and a field on that account changes in SFDC, we sync down the change but do not log the activity for the 5,000+ contacts.
