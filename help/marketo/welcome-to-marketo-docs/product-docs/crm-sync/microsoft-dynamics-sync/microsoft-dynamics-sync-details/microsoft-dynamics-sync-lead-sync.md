---
unique-page-id: 3571848
description: Microsoft Dynamics Sync: Lead Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync: Lead Sync
---

# Microsoft Dynamics Sync: Lead Sync {#microsoft-dynamics-sync-lead-sync}

Microsoft Dynamics Sync: Lead Sync - Marketo Docs - Product Documentation

Marketo to Dynamics sync is super powerful. Here are all the details:

### What's in this article? {#what-s-in-this-article}

[How are details kept in sync between the two systems?](#microsoftdynamicssync-leadsync-howaredetailskeptinsyncbetweenthetwosystems?)  
[What if changes are made to the same field in both systems at the same time? (Data Collision)](#microsoftdynamicssync-leadsync-whatifchangesaremadetothesamefieldinbothsystemsatthesametime?(datacollision))  
[Can I create a lead in Dynamics using Marketo?](#microsoftdynamicssync-leadsync-canicreatealeadindynamicsusingmarketo?)  
[Can I manually force a sync of a person from Marketo to a lead in Dynamics?](#microsoftdynamicssync-leadsync-canimanuallyforceasyncofapersonfrommarketotoaleadindynamics?)  
[What fields will sync to Marketo?](#microsoftdynamicssync-leadsync-whatfieldswillsynctomarketo?)  
[Will Marketo respect the Dynamics validation rules?](#microsoftdynamicssync-leadsync-willmarketorespectthedynamicsvalidationrules?)

#### How are details kept in sync between the two systems? {#microsoftdynamicssync-leadsync-howaredetailskeptinsyncbetweenthetwosystems?}

The sync is bidirectional. If you make changes to either a lead in Dynamics or a person in Marketo, your updates will be reflected in both systems.

#### What if changes are made to the same field in both systems at the same time? (Data Collision) {#microsoftdynamicssync-leadsync-whatifchangesaremadetothesamefieldinbothsystemsatthesametime?(datacollision)}

Although this is rare, Marketo will win for people (leads) and Dynamics will win for contacts. This is because we consider the marketing department to be authoritative for people, whereas the official system of record for contacts is in the sales (CRM) department.

#### Can I create a lead in Dynamics using Marketo? {#microsoftdynamicssync-leadsync-canicreatealeadindynamicsusingmarketo?}

Yes, use the [Sync Person to Microsoft](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) flow action. This will create a lead in Dynamics if the lead doesn't exist. If the lead does exist, the flow step will not perform any action.

>[!NOTE]
>
>When using the “Sync Person to Microsoft” flow action (in a trigger campaign only), the lead/contact will be created in real-time in Dynamics.

#### Can I manually force a sync of a person from Marketo to a lead in Dynamics? {#microsoftdynamicssync-leadsync-canimanuallyforceasyncofapersonfrommarketotoaleadindynamics?}

No, the automated background sync is the only way to sync updates between Marketo and Dynamics. The [Sync Person to Microsoft](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) flow action will not force a sync of the lead.

#### What fields will sync to Marketo? {#microsoftdynamicssync-leadsync-whatfieldswillsynctomarketo?}

`You can` [select fields to sync](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) `during setup.`

#### Will Marketo respect the Dynamics validation rules? {#microsoftdynamicssync-leadsync-willmarketorespectthedynamicsvalidationrules?}

Yes. The sync will fail if the data format is wrong or missing required field information. Marketo will log the result in the person's Activity Log if this happens.

