---
description: Understanding the Veeva CRM Sync - Marketo Docs - Product Documentation
title: Understanding the Veeva CRM Sync
hide: yes
hidefromtoc: yes
---
# Understanding the Veeva CRM Sync {#understanding-the-veeva-crm-sync}

In a few easy steps, it's easy to run a sync between Adobe Marketo Engage and the Veeva CRM.

## How the Sync Works {#how-the-sync-works}

Marketo Engage syncs with Veeva CRM all day, every day. Each sync takes some time, pauses for 5 minutes, then starts again.

>[!NOTE]
>
>The very first sync could take hours or even days because Marketo Engage is copying the entire database from Veeva. After that, each sync typically takes minutes (sometimes seconds) and only syncs data that has changed.

   ![](assets/understanding-the-veeva-sync-1.png)

The sync between Veeva and Marketo Engage is bidirectional only for Contact fields on the Person account object. In these cases, whenever you make changes in either Veeva or Marketo Engage, your updates will be reflected in both systems. All other syncs are from Veeva to Marketo Engage only. Click the links below for details on each one.

## What is Synced between Marketo Engage and Veeva {#what-is-synced-between-marketo-engage-and-veeva}

* Person Accounts
* Users
* Call and Call Key Objects
* Custom Objects

## Things to Know {#things-to-know}

* The credentials you enter in Marketo Engage for Veeva are used to sync data over. Only data those credentials have access to will be included.

* Veeva CRM is based on force.com and the rich experience Marketo Engage has with the platform is inherited into this sync.

* The Veeva CRM shows: Lead, Contact, Accounts (Business Accounts, Opportunity, Campaign, and Activity. However, they are not supported in the sync with Marketo Engage.
