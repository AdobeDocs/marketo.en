---
unique-page-id: 3571848
description: Microsoft Dynamics Sync: Lead Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync: Lead Sync
---

# Microsoft Dynamics Sync: Lead Sync {#microsoft-dynamics-sync-lead-sync}

Marketo to Dynamics sync is super powerful. Here are all the details:

### What's in this article? {#whats-in-this-article}

[How are details kept in sync between the two systems?](#how-are-details-kept-in-sync-between-the-two-systems)  
[What if changes are made to the same field in both systems at the same time? (Data Collision)](#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision)  
[Can I create a lead in Dynamics using Marketo?](#can-i-create-a-lead-in-dynamics-using-marketo)  
[Can I manually force a sync of a person from Marketo to a lead in Dynamics?](#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics)  
[What fields will sync to Marketo?](#what-fields-will-sync-to-marketo)  
[Will Marketo respect the Dynamics validation rules?](#will-marketo-respect-the-dynamics-validation-rules)

#### How are details kept in sync between the two systems? {#how-are-details-kept-in-sync-between-the-two-systems}

The sync is bidirectional. If you make changes to either a lead in Dynamics or a person in Marketo, your updates will be reflected in both systems.

#### What if changes are made to the same field in both systems at the same time? (Data Collision) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Although this is rare, Marketo will win for people (leads) and Dynamics will win for contacts. This is because we consider the marketing department to be authoritative for people, whereas the official system of record for contacts is in the sales (CRM) department.

#### Can I create a lead in Dynamics using Marketo? {#can-i-create-a-lead-in-dynamics-using-marketo}

Yes, use the [Sync Person to Microsoft](../../../../product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) flow action. This will create a lead in Dynamics if the lead doesn't exist. If the lead does exist, the flow step will not perform any action.

>[!NOTE]
>
>When using the “Sync Person to Microsoft” flow action (in a trigger campaign only), the lead/contact will be created in real-time in Dynamics.

#### Can I manually force a sync of a person from Marketo to a lead in Dynamics? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

No, the automated background sync is the only way to sync updates between Marketo and Dynamics. The [Sync Person to Microsoft](../../../../product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md)&nbsp;flow action will not force a sync of the lead.

#### What fields will sync to Marketo? {#what-fields-will-sync-to-marketo}

You can&nbsp; [select fields to sync](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync)&nbsp;during setup.&nbsp;

#### Will Marketo respect the Dynamics validation rules? {#will-marketo-respect-the-dynamics-validation-rules}

Yes. The sync will fail if the data format is wrong or missing required field information. Marketo will log the result in the person's Activity Log if this happens.

