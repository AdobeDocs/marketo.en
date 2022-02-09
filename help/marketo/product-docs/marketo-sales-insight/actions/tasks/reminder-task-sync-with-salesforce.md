---
description: Reminder Task Sync with Salesforce - Marketo Docs - Product Documentation
title: Reminder Task Sync with Salesforce
hide: yes
hidefromtoc: yes
---
# Reminder Task Sync with Salesforce {#reminder-task-sync-with-salesforce}

>[!NOTE]
>
>To learn how to enable Task Sync check out [Sync Sales Insight Actions Tasks/Reminders to Salesforce Tasks](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/salesforce-sync-settings.md#sync-sales-insight-actions-tasks-reminders-to-salesforce-tasks).

Once task sync settings are enabled users will see their reminder tasks bidirectionally synced with Salesforce. This means users can manage tasks from either Salesforce or Sales Insight Actions and feel confident that systems will stay aligned.  

## Reminder Task Field Sync {#reminder-task-field-sync}

![](assets/reminder-task-sync-with-salesforce-1.png)

Below is a list of the reminder task fields in Sales Insight Actions and their corresponding Salesforce fields that are supported via the bidirectional task sync.

<table>
 <tr>
  <th>Sales Insight Actions Task Field</th>
  <th>Salesforce Task Field</th>
  <th>Salesforce Task</th>
 </tr>
 <tr>
  <td>Task Name</td>
  <td>Subject Field</td>
  <td>A short summary field meant to show the title of the task.</td>
 </tr>
 <tr>
  <td>Status</td>
  <td>Task Status</td>
  <td><p>Shows the status of the task. Sales Insight Actions tasks have two statuses that map to two of the values in the Salesforce task status picklist.</p>
  <p>Open in Sales Insight Actions = Not Started in Salesforce.</p>
  <p>Complete in Sales Insight Actions = Completed in Salesforce.</p>
  <p>The other status values in Salesforce will not sync to Sales Insight Actions.</p></td>
 </tr>
 <tr>
  <td>Priority</td>
  <td>Priority</td>
  <td><p>Sales Insight Actions priority can be either Normal or High which maps to the Normal and High priority values in Salesforce.</p>
  <p>The low priority value in Salesforce will not sync to Sales Insight Actions.</p></td>
 </tr>
 <tr>
  <td>Due Date</td>
  <td>Due Date</td>
  <td>The date the task is due.</td>
 </tr>
 <tr>
  <td>Details</td>
  <td>Comments</td>
  <td>Shows more detailed information around what was meant to be completed with the reminder task.</td>
 </tr>
</table>

## Syncing Sales Insight Actions Tasks with Salesforce for the First Time {#syncing-sales-insight-actions-tasks-with-salesforce-for-the-first-time}

When you first turn on the sync between Sales Insight Actions and Salesforce tasks, we import your Salesforce tasks. We will **not** push over any current tasks you have in Sales Insight Actions to Salesforce. To reduce clutter and duplicates, the only tasks that get synced from Sales Insight Actions into Salesforce are tasks created *after* you sync Sales Insight Actions with SFDC.

Here's what happens when you sync Sales Insight Actions and SFDC tasks:

* As soon as you click save on tasks syncing, they begin to sync over. This will take some time initially.

* Any reminders that have been updated or created in the last 24 hours will be pulled in from SFDC to Sales Insight Actions. The sync is based on due date and all of those tasks will get synced over on the back-end, but in Command Center, you will only see tasks due today and tomorrow.

* If sync has been turned on previously and you delete any tasks in SFDC, anything that's been deleted in the last 15 days will be deleted from Command Center.

* We'll constantly sync tasks between Sales Insight Actions and SFDC as long as the sync is enabled.

After the initial sync, any tasks you create, edit, complete, or delete in Sales Insight Actions will sync over to your tasks list in Salesforce. And anything created, edited, completed, or deleted in Salesforce will update your tasks list in Sales Insight Actions.

To turn on this sync, just check the sync box in your [Settings page](https://toutapp.com/login) in the web application.

>[!NOTE]
>
>The subject field of a task can be updated in Sales Insight Actions and that update will be synced in the Salesforce subject field for the corresponding synced task, if you are using the `{{activity_subject}}` dynamic field in your [Activity Detail Customization](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md) settings. Conversely, any updates made to the subject field in Salesforce will _not_ sync over to the Sales Insight Actions reminder task subject field.
