---
unique-page-id: 2953457
description: SFDC Sync: Contact Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Contact Sync
---

# SFDC Sync: Contact Sync {#sfdc-sync-contact-sync}

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Did you know Marketo syncs your entire database with Salesforce? It syncs, then waits 5 minutes and then syncs again, all day, every day. Here are some details about how Marketo treats Salesforce Contacts specifically.

### What's in this article? {#whats-in-this-article}

[Sync Direction](#sync-direction)  
[What if changes are made in both systems at the same time?](#what-if-changes-are-made-in-both-systems-at-the-same-time)  
[Can I convert a person into a contact in Marketo?](#can-i-convert-a-person-into-a-contact-in-marketo)  
[Can I manually force a sync of a contact?](#can-i-manually-force-a-sync-of-a-contact)  
[Does every single standard field sync to Marketo?](#does-every-single-standard-field-sync-to-marketo)  
[Will Marketo respect the Salesforce validation rules?](#will-marketo-respect-the-salesforce-validation-rules)

#### Sync Direction {#sync-direction}

The contact sync is bidirectional. If you make changes to a contact in either Salesforce or Marketo, your updates will be reflected in both systems.

#### What if changes are made in both systems at the same time? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

We are nice and let Salesforce win. It's rare that this sort of collision of data occurs.

#### Can I convert a person into a contact in Marketo? {#can-i-convert-a-person-into-a-contact-in-marketo}

Yes, use the ** [Convert Person](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)** flow action.

>[!CAUTION]
>
>Converting a person in Marketo will result in a new account and opportunity in Salesforce. If you do not want duplicate accounts, use Salesforce to convert.

#### Can I manually force a sync of a contact? {#can-i-manually-force-a-sync-of-a-contact}

Yes, use the ** [Sync Person to SFDC](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) **flow action and it will sync in real-time.

#### Does every single standard field sync to Marketo? {#does-every-single-standard-field-sync-to-marketo}

No, not all the standard fields are useful. All custom fields can be part of the sync.

>[!NOTE]
>
>Marketo will only sync the fields that your Marketo Sync User has access to.

#### Will Marketo respect the Salesforce validation rules? {#will-marketo-respect-the-salesforce-validation-rules}

Yes, if there is a conflict it will log the result in the leads Activity Log.
