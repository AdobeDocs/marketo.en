---
unique-page-id: 3571838
description: Microsoft Dynamics Sync: Field Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync: Field Sync
---

# Microsoft Dynamics Sync: Field Sync {#microsoft-dynamics-sync-field-sync}

Microsoft Dynamics Sync: Field Sync - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Marketo to Dynamics sync is super powerful. Here are the details.

### What's in this article? {#what-s-in-this-article}

[How are field details kept in sync between the two systems?](#microsoftdynamicssync-fieldsync-howarefielddetailskeptinsyncbetweenthetwosystems?)  
[What if changes are made to the same field in both systems at the same time? (Data Collision)](#microsoftdynamicssync-fieldsync-whatifchangesaremadetothesamefieldinbothsystemsatthesametime?(datacollision))  
[Can I create a field in Dynamics using Marketo?](#microsoftdynamicssync-fieldsync-canicreateafieldindynamicsusingmarketo?)  
[I created a field in Dynamics. Can I sync it to Marketo?](#microsoftdynamicssync-fieldsync-icreatedafieldindynamics.canisyncittomarketo?)  
[What if I need to add a custom field after Marketo and Dynamics are synced?](#microsoftdynamicssync-fieldsync-whatifineedtoaddacustomfieldaftermarketoanddynamicsaresynced?)

#### How are field details kept in sync between the two systems? {#microsoftdynamicssync-fieldsync-howarefielddetailskeptinsyncbetweenthetwosystems?}

The sync is bidirectional for lead and contact entities. If you make changes to a lead or contact in Dynamics or a person in Marketo, your updates will be reflected in both systems.

For account, user, opportunity, team, and custom entities, the sync is one-way: Dynamics to Marketo. If you make changes to these entities in Dynamics, &nbsp;your updates will be reflected in Marketo.

#### What if changes are made to the same field in both systems at the same time? (Data Collision) {#microsoftdynamicssync-fieldsync-whatifchangesaremadetothesamefieldinbothsystemsatthesametime?(datacollision)}

Although this is rare, Marketo will win for people (leads) and Dynamics will win for contacts. This is because we consider the marketing department to be authoritative for people, whereas the official system of record for contacts is in the sales (CRM) department. For one-way sync entities, Dynamics will always win.

#### Can I create a field in Dynamics using Marketo? {#microsoftdynamicssync-fieldsync-canicreateafieldindynamicsusingmarketo?}

No, this is not currently supported.&nbsp;

#### I created a field in Dynamics. Can I sync it to Marketo? {#microsoftdynamicssync-fieldsync-icreatedafieldindynamics.canisyncittomarketo?}

Yes, you can [sync the field](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) as long as your sync user has access to it in Dynamics.

What fields will sync to Marketo?

You can&nbsp; [select fields to sync](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync)&nbsp;during setup.&nbsp;

#### What if I need to add a custom field after Marketo and Dynamics are synced? {#microsoftdynamicssync-fieldsync-whatifineedtoaddacustomfieldaftermarketoanddynamicsaresynced?}

You can add fields at any time and expect the data to be refreshed from Dynamics to Marketo. See&nbsp; [Use Quick Sync with Microsoft Dynamics for a New Custom Field](microsoft-dynamics-sync:-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md) for details.

>[!NOTE]
>
>**Related Articles**
>
>* [Use Quick Sync with Microsoft Dynamics for a New Custom Field](microsoft-dynamics-sync:-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md)
>

&nbsp; 