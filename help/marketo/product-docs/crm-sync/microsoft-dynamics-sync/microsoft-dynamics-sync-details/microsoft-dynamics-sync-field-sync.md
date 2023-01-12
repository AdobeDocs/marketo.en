---
unique-page-id: 3571838
description: Microsoft Dynamics Sync -Field Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync -Field Sync
exl-id: 78eef0eb-4086-45c5-bce3-a3399016f228
---
# [!DNL Microsoft Dynamics] Sync: Field Sync {#microsoft-dynamics-sync-field-sync}

Marketo to [!DNL Dynamics] sync is super powerful. Here are the details.

## How are field details kept in sync between the two systems? {#how-are-field-details-kept-in-sync-between-the-two-systems}

The sync is bidirectional for lead and contact entities. If you make changes to a lead or contact in [!DNL Dynamics] or a person in Marketo, your updates will be reflected in both systems.

For account, user, opportunity, team, and custom entities, the sync is one-way: [!DNL Dynamics] to Marketo. If you make changes to these entities in [!DNL Dynamics], your updates will be reflected in Marketo.

## What if changes are made to the same field in both systems at the same time? (Data Collision) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Although this is rare, Marketo will win for people (leads) and [!DNL Dynamics] will win for contacts. This is because we consider the marketing department to be authoritative for people, whereas the official system of record for contacts is in the sales (CRM) department. For one-way sync entities, [!DNL Dynamics] will always win.

## Can I create a field in [!DNL Dynamics] using Marketo? {#can-i-create-a-field-in-dynamics-using-marketo}

No, this is not currently supported.

## I created a field in [!DNL Dynamics]. Can I sync it to Marketo? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

Yes, you can [sync the field](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) as long as your sync user has access to it in [!DNL Dynamics].

## What fields will sync to Marketo? {#what-fields-will-sync-to-marketo}

You can [select fields to sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) during setup.

## What if I need to add a custom field after Marketo and [!DNL Dynamics] are synced? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

You can add fields at any time and expect the data to be refreshed from [!DNL Dynamics] to Marketo. See [Use Quick Sync with [!DNL Microsoft Dynamics] for a New Custom Field](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md) for details.

## What if I want to delete a field in [!DNL Dynamics] after the field has been added to sync? {#what-if-i-want-to-delete-a-field-in-dynamics-after-the-field-has-been-added-to-sync}

Marketo stores a reference to the fields to sync. If you delete a field in [!DNL Dynamics], we recommended doing so with the [sync disabled](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Then refresh the schema in Marketo by editing and saving the [Select Fields to Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md).
