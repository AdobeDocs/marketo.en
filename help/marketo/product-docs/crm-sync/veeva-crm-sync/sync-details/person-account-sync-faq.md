---
description: Person Account Sync FAQ - Marketo Docs - Product Documentation
title: Person Account Sync FAQ
exl-id: b77bb44f-94d0-40b2-9955-9636421ac468
feature: Veeva CRM
---
# Person Account Sync FAQ {#person-account-sync-faq}

Marketo Engage syncs your entire database with Veeva for the Person Account type of records. After the sync it waits 5 minutes, then syncs again, all day, every day.

Person accounts can be set up in Veeva to fit the needs of your organization.

>[!NOTE]
>
>We only sync "Professional" tier accounts as Person Accounts.

**What is a person account?**

A person account is very similar to the account object in Veeva CRM. However, a person account has access to both account fields and contact fields.

**What happens when a person account is synced to Marketo?**

A person account is synced to Marketo as a company and as a person.

>[!NOTE]
>
>The custom fields for a person account are copied to both company and person in Marketo.

**How do I differentiate business accounts and person accounts?**

Use the "Is Person" Account filter in your Smart List to separate person accounts from standard business accounts.

**Which email field should I use for person accounts?**

There are two email fields for a person account. Use the Email Address field in your forms (not the Person Email Address) to ensure Marketo’s de-duplication and other email processing work properly.

## Sync Direction {#sync-direction}

The sync of contact related fields of the Person Account is bidirectional. If you make changes to a contact in either Veeva CRM or Marketo, your updates will be reflected in both systems. The fields on the account only sync in one direction, from Veeva CRM to Marketo.

**What if changes are made in both systems to Contact fields on the Person Account at the same time?**

We'd be nice and let Veeva CRM win. It’s rare that this sort of collision of data occurs, however.

**Are Lead or Contact type of records synced with Veeva CRM?**

Veeva CRM only really deals with Person Account objects and also has Business Accounts. The traditional CRM types of Lead, Contacts, and Opportunities are not really in use in traditional Veeva CRM systems. These may be created in Veeva CRM, but they are not officially supported using this connector.  

**Can I convert a person into a contact in Marketo?**

No, since Lead and Contact are not supported types for the sync with Veeva CRM. As a result, conversion is not supported.

**Can I manually force a sync of a contact?**

No, since Contact is not an independent type of record, syncing a person to Veeva is not supported.

**Does every single standard field sync to Marketo?**

No, not all standard fields are useful. All custom fields can be part of the sync.

>[!NOTE]
>
>Marketo will only sync the fields that your Marketo Sync User has access to.

**Will Marketo respect the Veeva validation rules?**

Yes, if there is a conflict, we will log the result in the lead's Activity Log.

>[!MORELIKETHIS]
>
>* [Default Veeva Field Mapping](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/default-veeva-field-mapping.md){target="_blank"}
>* [Syncing Call and Call Key Messages](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
