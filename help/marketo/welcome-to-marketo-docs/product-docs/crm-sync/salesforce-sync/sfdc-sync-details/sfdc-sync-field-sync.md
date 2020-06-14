---
unique-page-id: 2953461
description: SFDC Sync: Field Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Field Sync
---

# SFDC Sync: Field Sync {#sfdc-sync-field-sync}

SFDC Sync: Field Sync - Marketo Docs - Product Documentation

Marketo syncs field information from Salesforce. Here are the details.

### What's in this article? {#what-s-in-this-article}

[Which fields are synced?](#sfdcsync-fieldsync-whichfieldsaresynced?)  
[How do you determine if a record in Marketo is a lead or a contact in Salesforce?](#sfdcsync-fieldsync-howdoyoudetermineifarecordinmarketoisaleadoracontactinsalesforce?)  
[How do you determine if a lead or contact is deleted in SFDC?](#sfdcsync-fieldsync-howdoyoudetermineifaleadorcontactisdeletedinsfdc?)  
[How do I make sure a new field I add in SFDC also gets added to Marketo?](#sfdcsync-fieldsync-howdoimakesureanewfieldiaddinsfdcalsogetsaddedtomarketo?)  
[What if I change a field label in SFDC?](#sfdcsync-fieldsync-whatifichangeafieldlabelinsfdc?)  
[What if I change a field type in SFDC?](#sfdcsync-fieldsync-whatifichangeafieldtypeinsfdc?)  
[What if I change an API name in SFDC?](#sfdcsync-fieldsync-whatifichangeanapinameinsfdc?)  
[What happens if I add a new picklist value in SFDC?](#sfdcsync-fieldsync-whathappensifiaddanewpicklistvalueinsfdc?)  
[What about Custom SFDC Lookup Fields?](#sfdcsync-fieldsync-whataboutcustomsfdclookupfields?)  
[What about SFDC Formula Fields?](#sfdcsync-fieldsync-whataboutsfdcformulafields?)  
[What happens when I delete a field from Salesforce that was previously syncing with Marketo?](#sfdcsync-fieldsync-whathappenswhenideleteafieldfromsalesforcethatwaspreviouslysyncingwithmarketo?)

#### Which fields are synced? {#sfdcsync-fieldsync-whichfieldsaresynced?}

We sync most standard fields in SFDC and any custom field that the sync user has permission to see.&nbsp;

#### How do you determine if a record in Marketo is a lead or a contact in Salesforce? {#sfdcsync-fieldsync-howdoyoudetermineifarecordinmarketoisaleadoracontactinsalesforce?}

We have a field in Marketo called SFDC Type. It has three possible values: lead, contact, or it's empty. If it's empty, it means that this Marketo lead does not exist in SFDC.&nbsp;

#### How do you determine if a lead or contact is deleted in SFDC? {#sfdcsync-fieldsync-howdoyoudetermineifaleadorcontactisdeletedinsfdc?}

We have a field in Marketo called&nbsp;SFDC isDeleted. If the value is true, then the lead was deleted in SFDC.&nbsp;

#### How do I make sure a new field I add in SFDC also gets added to Marketo? {#sfdcsync-fieldsync-howdoimakesureanewfieldiaddinsfdcalsogetsaddedtomarketo?}

>[!TIP]
>
>If you want a field in both systems, create it in SFDC first and it will automatically sync down to Marketo.

If you add a new field in SFDC and the sync user has permission to see it, it will automatically get added to Marketo.&nbsp;  

#### What if I change a field label in SFDC? {#sfdcsync-fieldsync-whatifichangeafieldlabelinsfdc?}

Changing the field label in SFDC does not affect the field label in Marketo.&nbsp;

#### What if I change a field type in SFDC? {#sfdcsync-fieldsync-whatifichangeafieldtypeinsfdc?}

When you change a field type, Marketo deletes the data in the fields if they don't match (but first displays a warning). To preserve the data, be sure to export it and re-import it after you change the field type.

#### What if I change an API name in SFDC? {#sfdcsync-fieldsync-whatifichangeanapinameinsfdc?}

If you change the API name of a field in SFDC&nbsp;a new field is created in Marketo.

#### What happens if I add a new picklist value in SFDC? {#sfdcsync-fieldsync-whathappensifiaddanewpicklistvalueinsfdc?}

If a new picklist value is added in SFDC to a field, Marketo will send you a notification.&nbsp;

#### What about Custom SFDC Lookup Fields? {#sfdcsync-fieldsync-whataboutcustomsfdclookupfields?}

Lookup fields in SFDC sync the ID but not the referenced name.&nbsp;

#### What about SFDC Formula Fields? {#sfdcsync-fieldsync-whataboutsfdcformulafields?}

Formula fields are synced, however, updates to the references in the formula are not synced until there is an update to a [System Mod Stamp](https://help.salesforce.com/apex/HTViewSolution?id=000193203&language=en_US).&nbsp;

#### What happens when I delete a field from Salesforce that was previously syncing with Marketo? {#sfdcsync-fieldsync-whathappenswhenideleteafieldfromsalesforcethatwaspreviouslysyncingwithmarketo?}

If you delete a field in SFDC it doesn’t automatically delete the field in Marketo, it just stops syncing.
