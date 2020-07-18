---
unique-page-id: 7515133
description: SFDC Sync: Merging a Lead/Contact/Person - Marketo Docs - Product Documentation
title: SFDC Sync: Merging a Lead/Contact/Person
---

# SFDC Sync: Merging a Lead/Contact/Person {#sfdc-sync-merging-a-lead-contact-person}

SFDC Sync: Merging a Lead/Contact/Person - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Sometimes it's best to just list the rules. Here we go:

* When you merge two leads in **Salesforce**, the normal sync tells Marketo and the leads are merged automatically as people in Marketo.
* Merging two people in **Marketo** actually invokes the same process as merging them as leads in Salesforce. It still works automatically.
* Merging a **lead (person) into a contact** works the same way. You end up with a single contact on both sides.
* When merging, the default score is summed.

>[!NOTE]
>
>**Example**
>
>Merging 3 leads (people) with scores of 10 each, will yield a result of 1 lead (person) with a score of 30.

* Conflicting field values are taken from the "winning record." (Record = the resulting lead or contact)
* If the "losing record" (the one that is disappearing) had a value and the winning record has none, we will keep the losing record. In other words, "Some value is better than no value."
* All activity log items are merged.

>[!NOTE]
>
>**Deep Dive**
>
>Deep dive for more information about [merging people in Marketo](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md).

