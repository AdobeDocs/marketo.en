---
unique-page-id: 14352541
description: Syncing Sales Connect Tasks with Salesforce for the First Time - Marketo Docs - Product Documentation
title: Syncing Sales Connect Tasks with Salesforce for the First Time
---

# Syncing Sales Connect Tasks with Salesforce for the First Time {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

Syncing Sales Connect Tasks with Salesforce for the First Time - Marketo Docs - Product Documentation

When you first turn on the sync between Sales Connect and Salesforce tasks, we import your Salesforce tasks. We will **not** push over any current tasks you have in Sales Connect to Salesforce. To reduce clutter and duplicates, the only tasks that get synced from Sales Connect into Salesforce are tasks created *after* you sync Sales Connect with SFDC.

Here's what happens when you sync Sales Connect and SFDC tasks:

- As soon as you click save on tasks syncing, they begin to sync over. This will take some time initially.

- Any reminders that have been updated or created in the `last 24 hours` will be pulled in from SFDC to Sales Connect. The sync is based on `due date` and all of those tasks will get synced over on the back-end, but in Command Center, you will only see tasks due today and tomorrow.

-&nbsp;If sync has been turned on previously and you delete any tasks in SFDC, anything that's been deleted in the last 15 days will be deleted from Command Center.

- We'll constantly sync tasks between Sales Connect and SFDC as long as the sync is enabled.

After the initial sync, any tasks you create, edit, complete, or delete in Sales Connect will sync over to your tasks list in Salesforce. And anything created, edited, completed, or deleted in Salesforce will update your tasks list in Sales Connect.

To turn on this sync, just check the sync box in your [Settings page](http://toutapp.com/next#settings/crm/salesforce/configure) in the web application.

