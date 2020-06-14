---
unique-page-id: 2953455
description: SFDC Sync: Lead Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Lead Sync
---

# SFDC Sync: Lead Sync {#sfdc-sync-lead-sync}

SFDC Sync: Lead Sync - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Did you know Marketo syncs from your Salesforce database? It syncs, waits 5 minutes, then syncs again. All day, every day. Here are some details about how Marketo treats Salesforce leads specifically.

### What's in this article? {#what-s-in-this-article}

[Sync Direction](#sfdcsync-leadsync-syncdirection)  
[What if changes are made in both systems at the same time?](#sfdcsync-leadsync-whatifchangesaremadeinbothsystemsatthesametime?)  
[Can I create a lead in Salesforce using Marketo?](#sfdcsync-leadsync-canicreatealeadinsalesforceusingmarketo?)  
[Can I manually force a sync of a person in Marketo to a lead in Salesforce?](#sfdcsync-leadsync-canimanuallyforceasyncofapersoninmarketotoaleadinsalesforce?)  
[Does every single standard field sync to Marketo?](#sfdcsync-leadsync-doeseverysinglestandardfieldsynctomarketo?)  
[Will Marketo respect the Salesforce validation rules?](#sfdcsync-leadsync-willmarketorespectthesalesforcevalidationrules?)

#### Sync Direction {#sfdcsync-leadsync-syncdirection}

The lead (person) and contact sync is bidirectional. If you make changes to a record in either Salesforce or Marketo, your updates will be reflected in both systems.&nbsp;

#### What if changes are made in both systems at the same time? {#sfdcsync-leadsync-whatifchangesaremadeinbothsystemsatthesametime?}

Marketo wins. It's rare that this sort of collision of data occurs.

#### Can I create a lead in Salesforce using Marketo? {#sfdcsync-leadsync-canicreatealeadinsalesforceusingmarketo?}

Yes, use the&nbsp; [Sync Person to SFDC](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)&nbsp;flow action. This will create a lead in Salesforce if the lead doesn't exist.&nbsp;

#### Can I manually force a sync of a person in Marketo to a lead in Salesforce? {#sfdcsync-leadsync-canimanuallyforceasyncofapersoninmarketotoaleadinsalesforce?}

Yes, use the&nbsp; [Sync Person to SFDC](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)&nbsp;flow action and it will sync in real-time.&nbsp;

#### Does every single standard field sync to Marketo? {#sfdcsync-leadsync-doeseverysinglestandardfieldsynctomarketo?}

No, not all the standard fields are useful. All custom fields can be part of the sync.&nbsp;

>[!NOTE]
>
>Marketo will only sync the fields that your Salesforce sync user has access to.

#### Will Marketo respect the Salesforce validation rules? {#sfdcsync-leadsync-willmarketorespectthesalesforcevalidationrules?}

Yes. The sync will fail if the data format is wrong or missing required field information. Marketo will log the result in the leads Activity Log if this happens.
