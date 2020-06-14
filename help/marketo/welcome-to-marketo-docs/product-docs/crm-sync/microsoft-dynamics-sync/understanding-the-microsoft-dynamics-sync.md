---
unique-page-id: 10098625
description: Understanding the Microsoft Dynamics Sync - Marketo Docs - Product Documentation
title: Understanding the Microsoft Dynamics Sync
---

# Understanding the Microsoft Dynamics Sync {#understanding-the-microsoft-dynamics-sync}

Understanding the Microsoft Dynamics Sync - Marketo Docs - Product Documentation

Marketo and Microsoft Dynamics go together. We keep your sales and marketing data in sync.

>[!NOTE]
>
>Marketo only supports SSL certs that are compatible with Java 7 at this time.

#### How Sync Works {#understandingthemicrosoftdynamicssync-howsyncworks}

Marketo continuously syncs data with Microsoft Dynamics all day, every day. It's done using background sync, in batches, not in real time.

>[!NOTE]
>
>The very first sync in your subscription takes minutes to hours, depending on the size of your database. Marketo copies the entire database from Dynamics. After that, each sync typically takes seconds or minutes and only syncs data that has changed.

The sync between Marketo and Dynamics is bidirectional for leads and contacts. If you make changes in either Marketo or Dynamics, your updates will be reflected in both systems. All other fields, such as accounts and opportunities, are synced one way only, from Dynamics to Marketo. 

#### What is Synced between Marketo and Microsoft Dynamics? {#understandingthemicrosoftdynamicssync-whatissyncedbetweenmarketoandmicrosoftdynamics?}

* [Leads](microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [Contacts](microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [Accounts](microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [Users](microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* Teams (groups of SystemUsers)
* [Opportunities](microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [Custom entities](microsoft-dynamics-sync-details/microsoft-dynamics-sync-custom-entity-sync.md)

>[!NOTE]
>
>The [credentials you enter in Marketo for Dynamics](sync-setup/microsoft-dynamics-365/step-2-of-3-set-up-marketo-sync-user-in-dynamics.md) are used to sync data over.

There are many nuances and features about Dynamics sync. Check out the details in the [Microsoft Dynamics Sync Details section](microsoft-dynamics-sync-details.md).

>[!CAUTION]
>
>We do not currently support sandbox refresh for Marketo Dynamics Sync. If you need to refresh your Dynamics CRM sandbox, a new Marketo sandbox will be required. Please contact your Customer Success Manager for additional details.

>[!NOTE]
>
>**Related Articles**
>
>* [Sync Setup](sync-setup.md)
>
>* [Microsoft Dynamics Sync Details](microsoft-dynamics-sync-details.md)
>

