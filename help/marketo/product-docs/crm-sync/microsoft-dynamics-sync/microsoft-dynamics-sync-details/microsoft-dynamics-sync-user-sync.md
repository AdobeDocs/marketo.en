---
unique-page-id: 3571840
description: Learn about how user data syncs from Microsoft Dynamics to Marketo. Understand which owner fields sync and how to use them in Smart Lists and flow actions.
title: Microsoft [!DNL Dynamics] Sync -User Sync
exl-id: d642d4d2-2beb-42c6-a6b2-3da5df1cd9c8
feature: Microsoft Dynamics
TQID: https://experienceleague.adobe.com/8H1bMdkhxcvyTuYtHHk00GUy4uycuQ1unsGbZ19AjCM
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
---
# Microsoft [!DNL Dynamics] Sync: User Sync {#microsoft-dynamics-sync-user-sync}

Marketo syncs your entire database with [!DNL Dynamics]. It syncs, then waits 5 minutes and then syncs again, all day, every day. Here are some details about how Marketo treats [!DNL Dynamics] Accounts specifically.

You will need a dedicated Microsoft [!DNL Dynamics] CRM user for the purpose of the integration. We call this user the Sync User.

## How are user details kept in sync between the two systems? {#how-are-user-details-kept-in-sync-between-the-two-systems}

The user sync is one way - [!DNL Dynamics] to Marketo. If you make changes to a user in [!DNL Dynamics] the changes will be reflected in Marketo.

## Can I create an user using Marketo? {#can-i-create-an-user-using-marketo}

No. Marketo cannot create users in [!DNL Dynamics].

## Which fields will sync to Marketo? {#which-fields-will-sync-to-marketo}

You can [select fields to sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) during setup. But Marketo will only sync the fields that your [!DNL Dynamics] sync user has access to.
