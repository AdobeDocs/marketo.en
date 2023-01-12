---
unique-page-id: 3571833
description: Microsoft Dynamics Sync -Contact Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync -Contact Sync
exl-id: d4583ea0-2b52-415e-b28c-a8eafebeff64
---
# [!DNL Microsoft Dynamics] Sync: Contact Sync {#microsoft-dynamics-sync-contact-sync}

Did you know Marketo syncs your entire database with [!DNL Dynamics]? It syncs, then waits 5 minutes and then syncs again, all day, every day. Here are some details about how Marketo treats [!DNl Dynamics] Contacts specifically.

## How are details kept in sync between the two systems? {#how-are-details-kept-in-sync-between-the-two-systems}

The contact sync is bidirectional. If you make changes to a contact in [!DNL Dynamics] or a person in Marketo, your updates will be reflected in both systems.

## What if changes are made to the same field in both systems at the same time? (Data Collision) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Although this is rare, Marketo will win for people and [!DNL Dynamics] will win for contacts. This is because we consider the marketing department to be authoritative for people, whereas the official system of record for contacts is in the sales (CRM) department.

## Can I create a contact using Marketo? {#can-i-create-a-contact-using-marketo}

Yes. [Here's how](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md).

>[!NOTE]
>
>When using the “Sync Person to Microsoft” flow action (in a trigger campaign only), the lead/contact will be created in real-time in [!DNL Dynamics].

## Can I manually force a sync of a person or a contact? {#can-i-manually-force-a-sync-of-a-person-or-a-contact}

No, the automated background sync is the only way to sync updates between Marketo and [!DNL Dynamics]. The [Sync Person to Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) will not force a sync of the lead.

## What fields will sync to Marketo? {#what-fields-will-sync-to-marketo}

You can [select fields to sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) during setup. But Marketo will only sync the fields that your [!DNL Dynamics] sync user has access to.

## Will Marketo respect the [!DNL Dynamics] validation rules? {#will-marketo-respect-the-dynamics-validation-rules}

Yes, if there is a conflict it will log the result in the leads Activity Log.
