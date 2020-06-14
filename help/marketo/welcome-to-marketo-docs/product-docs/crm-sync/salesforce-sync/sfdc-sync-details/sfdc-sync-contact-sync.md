---
unique-page-id: 2953457
description: SFDC Sync: Contact Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Contact Sync
---

# SFDC Sync: Contact Sync {#sfdc-sync-contact-sync}

SFDC Sync: Contact Sync - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Did you know Marketo syncs your entire database with Salesforce? It syncs, then waits 5 minutes and then syncs again, all day, every day. Here are some details about how Marketo treats Salesforce Contacts specifically.

### What's in this article? {#what-s-in-this-article}

[Sync Direction](#sfdcsync-contactsync-syncdirection)  
[What if changes are made in both systems at the same time?](#sfdcsync-contactsync-whatifchangesaremadeinbothsystemsatthesametime?)  
[Can I convert a person into a contact in Marketo?](#sfdcsync-contactsync-caniconvertapersonintoacontactinmarketo?)  
[Can I manually force a sync of a contact?](#sfdcsync-contactsync-canimanuallyforceasyncofacontact?)  
[Does every single standard field sync to Marketo?](#sfdcsync-contactsync-doeseverysinglestandardfieldsynctomarketo?)  
[Will Marketo respect the Salesforce validation rules?](#sfdcsync-contactsync-willmarketorespectthesalesforcevalidationrules?)

#### Sync Direction {#sfdcsync-contactsync-syncdirection}

The contact sync is bidirectional. If you make changes to a contact in either Salesforce or Marketo, your updates will be reflected in both systems.

#### What if changes are made in both systems at the same time? {#sfdcsync-contactsync-whatifchangesaremadeinbothsystemsatthesametime?}

We are nice and let Salesforce win. It's rare that this sort of collision of data occurs.

#### Can I convert a person into a contact in Marketo? {#sfdcsync-contactsync-caniconvertapersonintoacontactinmarketo?}

Yes, use the ** [Convert Person](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)** flow action.

>[!CAUTION]
>
>Converting a person in Marketo will result in a new account and opportunity in Salesforce. If you do not want duplicate accounts, use Salesforce to convert.

#### Can I manually force a sync of a contact? {#sfdcsync-contactsync-canimanuallyforceasyncofacontact?}

Yes, use the ** [Sync Person to SFDC](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) **flow action and it will sync in real-time.

#### Does every single standard field sync to Marketo? {#sfdcsync-contactsync-doeseverysinglestandardfieldsynctomarketo?}

No, not all the standard fields are useful. All custom fields can be part of the sync.

>[!NOTE]
>
>Marketo will only sync the fields that your Marketo Sync User has access to.

#### Will Marketo respect the Salesforce validation rules? {#sfdcsync-contactsync-willmarketorespectthesalesforcevalidationrules?}

Yes, if there is a conflict it will log the result in the leads Activity Log.
