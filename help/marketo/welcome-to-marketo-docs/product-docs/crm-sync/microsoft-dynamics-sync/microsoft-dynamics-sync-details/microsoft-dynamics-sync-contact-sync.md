---
unique-page-id: 3571833
description: Microsoft Dynamics Sync: Contact Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync: Contact Sync
---

# Microsoft Dynamics Sync: Contact Sync {#microsoft-dynamics-sync-contact-sync}

Microsoft Dynamics Sync: Contact Sync - Marketo Docs - Product Documentation

Did you know Marketo syncs your entire database with Dynamics? It syncs, then waits 5 minutes and then syncs again, all day, every day. Here are some details about how Marketo treats Dynamics Contacts specifically.

### What's in this article? {#what-s-in-this-article}

[How are details kept in sync between the two systems?](#microsoftdynamicssync-contactsync-howaredetailskeptinsyncbetweenthetwosystems?)  
[What if changes are made to the same field in both systems at the same time? (Data Collision)](#microsoftdynamicssync-contactsync-whatifchangesaremadetothesamefieldinbothsystemsatthesametime?(datacollision))  
[Can I create a contact using Marketo?](#microsoftdynamicssync-contactsync-canicreateacontactusingmarketo?)  
[Can I manually force a sync of a person or a contact?](#microsoftdynamicssync-contactsync-canimanuallyforceasyncofapersonoracontact?)  
[What fields will sync to Marketo?](#microsoftdynamicssync-contactsync-whatfieldswillsynctomarketo?)  
[Will Marketo respect the Dynamics validation rules?](#microsoftdynamicssync-contactsync-willmarketorespectthedynamicsvalidationrules?)

#### How are details kept in sync between the two systems? {#microsoftdynamicssync-contactsync-howaredetailskeptinsyncbetweenthetwosystems?}

The contact sync is bidirectional. If you make changes to a contact in Dynamics or a person in Marketo, your updates will be reflected in both systems.&nbsp;

#### What if changes are made to the same field in both systems at the same time? (Data Collision) {#microsoftdynamicssync-contactsync-whatifchangesaremadetothesamefieldinbothsystemsatthesametime?(datacollision)}

Although this is rare, Marketo will win for people and Dynamics will win for contacts. This is because we consider the marketing department to be authoritative for people, whereas the official system of record for contacts is in the sales (CRM) department.

#### Can I create a contact using Marketo? {#microsoftdynamicssync-contactsync-canicreateacontactusingmarketo?}

Yes. [Here's how](microsoft-dynamics-sync:-lead-sync/create-a-contact-in-microsoft-dynamics.md).&nbsp;

>[!NOTE]
>
>When using the “Sync Person to Microsoft” flow action (in a trigger campaign only), the lead/contact will be created in real-time in Dynamics.

#### Can I manually force a sync of a person or a contact? {#microsoftdynamicssync-contactsync-canimanuallyforceasyncofapersonoracontact?}

`No, the automated background sync is the only way to sync updates between Marketo and Dynamics.` `The [Sync Person to Microsoft](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) will not force a sync of the lead.`

#### What fields will sync to Marketo? {#microsoftdynamicssync-contactsync-whatfieldswillsynctomarketo?}

You can [select fields to sync](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) during setup. But Marketo will only sync the fields that your Dynamics sync user has access to.

#### Will Marketo respect the Dynamics validation rules? {#microsoftdynamicssync-contactsync-willmarketorespectthedynamicsvalidationrules?}

Yes, if there is a conflict it will log the result in the leads Activity Log.
