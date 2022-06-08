---
unique-page-id: 2953455
description: SFDC Sync - Lead Sync - Marketo Docs - Product Documentation
title: SFDC Sync - Lead Sync
exl-id: cf38e091-7344-4b95-b9e1-77eda751c4a9
---
# SFDC Sync: Lead Sync {#sfdc-sync-lead-sync}

Did you know Marketo syncs from your Salesforce database? It syncs, waits 5 minutes, then syncs again. All day, every day. Here are some details about how Marketo treats Salesforce leads specifically.

## Sync Direction {#sync-direction}

The lead (person) and contact sync is bidirectional. If you make changes to a record in either Salesforce or Marketo, your updates will be reflected in both systems.

## What if changes are made in both systems at the same time? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

Marketo wins. It's rare that this sort of collision of data occurs.

## Can I create a lead in Salesforce using Marketo? {#can-i-create-a-lead-in-salesforce-using-marketo}

Yes, use the [Sync Person to SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) flow action. This will create a lead in Salesforce if the lead doesn't exist.

## Can I manually force a sync of a person in Marketo to a lead in Salesforce? {#can-i-manually-force-a-sync-of-a-person-in-marketo-to-a-lead-in-salesforce}

Yes, use the [Sync Person to SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) flow action and it will sync in real-time.

## Does every single standard field sync to Marketo? {#does-every-single-standard-field-sync-to-marketo}

No, not all the standard fields are useful. All custom fields can be part of the sync.

>[!NOTE]
>
>Marketo will only sync the fields that your Salesforce sync user has access to.

## Will Marketo respect the Salesforce validation rules? {#will-marketo-respect-the-salesforce-validation-rules}

Yes. The sync will fail if the data format is wrong or missing required field information. Marketo will log the result in the leads Activity Log if this happens.
