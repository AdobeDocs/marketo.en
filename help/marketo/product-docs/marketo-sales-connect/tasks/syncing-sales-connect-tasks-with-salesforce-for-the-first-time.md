---
unique-page-id: 14352541
description: Syncing Sales Connect Tasks with Salesforce for the First Time - Marketo Docs - Product Documentation
title: Syncing Sales Connect Tasks with Salesforce for the First Time
exl-id: 42ac6b4f-76ac-40d7-9e10-7e0d3886a638
feature: Marketo Sales Connect
---
# Syncing [!DNL Sales Connect] Tasks with [!DNL Salesforce] for the First Time {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

When you first turn on the sync between [!DNL Sales Connect] and [!DNL Salesforce] tasks, we import your [!DNL Salesforce] tasks. We will **not** push over any current tasks you have in [!DNL Sales Connect] to [!DNL Salesforce]. To reduce clutter and duplicates, the only tasks that get synced from [!DNL Sales Connect] into [!DNL Salesforce] are tasks created *after* you sync [!DNL Sales Connect] with SFDC.

Here's what happens when you sync [!DNL Sales Connect] and SFDC tasks:

- As soon as you click save on tasks syncing, they begin to sync over. This will take some time initially.

- Any reminders that have been updated or created in the last 24 hours will be pulled in from SFDC to [!DNL Sales Connect]. The sync is based on due date and all of those tasks will get synced over on the back-end, but in Command Center, you will only see tasks due today and tomorrow.

- If sync has been turned on previously and you delete any tasks in SFDC, anything that's been deleted in the last 15 days will be deleted from Command Center.

- We'll constantly sync tasks between [!DNL Sales Connect] and SFDC as long as the sync is enabled.

After the initial sync, any tasks you create, edit, complete, or delete in [!DNL Sales Connect] will sync over to your tasks list in [!DNL Salesforce]. And anything created, edited, completed, or deleted in [!DNL Salesforce] will update your tasks list in [!DNL Sales Connect].

To turn on this sync, just check the sync box in your [Settings page](https://toutapp.com/login) in the web application.
