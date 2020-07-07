---
unique-page-id: 2953461
description: SFDC Sync: Field Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Field Sync
---

# SFDC Sync: Field Sync {#sfdc-sync-field-sync}

SFDC Sync: Field Sync - Marketo Docs - Product Documentation

Marketo syncs field information from Salesforce. Here are the details.

### What's in this article? {#whats-in-this-article}

[Which fields are synced?](#which-fields-are-synced)  
[How do you determine if a record in Marketo is a lead or a contact in Salesforce?](#how-do-you-determine-if-a-record-in-marketo-is-a-lead-or-a-contact-in-salesforce)  
[How do you determine if a lead or contact is deleted in SFDC?](#how-do-you-determine-if-a-lead-or-contact-is-deleted-in-sfdc)  
[How do I make sure a new field I add in SFDC also gets added to Marketo?](#how-do-i-make-sure-a-new-field-i-add-in-sfdc-also-gets-added-to-marketo)  
[What if I change a field label in SFDC?](#what-if-i-change-a-field-label-in-sfdc)  
[What if I change a field type in SFDC?](#what-if-i-change-a-field-type-in-sfdc)  
[What if I change an API name in SFDC?](#what-if-i-change-an-api-name-in-sfdc)  
[What happens if I add a new picklist value in SFDC?](#what-happens-if-i-add-a-new-picklist-value-in-sfdc)  
[What about Custom SFDC Lookup Fields?](#what-about-custom-sfdc-lookup-fields)  
[What about SFDC Formula Fields?](#what-about-sfdc-formula-fields)  
[What happens when I delete a field from Salesforce that was previously syncing with Marketo?](#what-happens-when-i-delete-a-field-from-salesforce-that-was-previously-syncing-with-marketo)

#### Which fields are synced? {#which-fields-are-synced}

We sync most standard fields in SFDC and any custom field that the sync user has permission to see.

#### How do you determine if a record in Marketo is a lead or a contact in Salesforce? {#how-do-you-determine-if-a-record-in-marketo-is-a-lead-or-a-contact-in-salesforce}

We have a field in Marketo called SFDC Type. It has three possible values: lead, contact, or it's empty. If it's empty, it means that this Marketo lead does not exist in SFDC.

#### How do you determine if a lead or contact is deleted in SFDC? {#how-do-you-determine-if-a-lead-or-contact-is-deleted-in-sfdc}

We have a field in Marketo called SFDC isDeleted. If the value is true, then the lead was deleted in SFDC.

#### How do I make sure a new field I add in SFDC also gets added to Marketo? {#how-do-i-make-sure-a-new-field-i-add-in-sfdc-also-gets-added-to-marketo}

>[!TIP]
>
>If you want a field in both systems, create it in SFDC first and it will automatically sync down to Marketo.

If you add a new field in SFDC and the sync user has permission to see it, it will automatically get added to Marketo.  

#### What if I change a field label in SFDC? {#what-if-i-change-a-field-label-in-sfdc}

Changing the field label in SFDC does not affect the field label in Marketo.

#### What if I change a field type in SFDC? {#what-if-i-change-a-field-type-in-sfdc}

When you change a field type, Marketo deletes the data in the fields if they don't match (but first displays a warning). To preserve the data, be sure to export it and re-import it after you change the field type.

#### What if I change an API name in SFDC? {#what-if-i-change-an-api-name-in-sfdc}

If you change the API name of a field in SFDC a new field is created in Marketo.

#### What happens if I add a new picklist value in SFDC? {#what-happens-if-i-add-a-new-picklist-value-in-sfdc}

If a new picklist value is added in SFDC to a field, Marketo will send you a notification.

#### What about Custom SFDC Lookup Fields? {#what-about-custom-sfdc-lookup-fields}

Lookup fields in SFDC sync the ID but not the referenced name.

#### What about SFDC Formula Fields? {#what-about-sfdc-formula-fields}

Formula fields are synced, however, updates to the references in the formula are not synced until there is an update to a [System Mod Stamp](https://help.salesforce.com/apex/HTViewSolution?id=000193203&language=en_US).

#### What happens when I delete a field from Salesforce that was previously syncing with Marketo? {#what-happens-when-i-delete-a-field-from-salesforce-that-was-previously-syncing-with-marketo}

If you delete a field in SFDC it doesn’t automatically delete the field in Marketo, it just stops syncing.
