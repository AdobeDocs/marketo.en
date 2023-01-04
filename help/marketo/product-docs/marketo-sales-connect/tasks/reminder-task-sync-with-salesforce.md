---
description: Reminder Task Sync with Salesforce - Marketo Docs - Product Documentation
title: Reminder Task Sync with Salesforce
exl-id: 4de933db-4626-4845-be70-8ad55d03a18e
---
# Reminder Task Sync with [!DNL Salesforce] {#reminder-task-sync-with-salesforce}

>[!NOTE]
>
>To learn how to enable Task Sync check out [Sync [!DNL Sales Connect] Tasks/Reminders to [!DNL Salesforce] Tasks](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md#sync-sales-connect-tasks-reminders-to-salesforce-tasks).  

Once task sync settings are enabled users will see their reminder tasks bidirectionally synced with [!DNL Salesforce]. This means users can manage tasks from either [!DNL Salesforce] or [!DNL Sales Connect] and feel confident that systems will stay aligned.  

## Reminder Task Field Sync {#reminder-task-field-sync}

![](assets/reminder-task-sync-with-salesforce-1.png)

Below is a list of the reminder task fields in [!DNL Sales Connect] and their corresponding [!DNL Salesforce] fields that are supported via the bidirectional task sync.

<table>
 <tr>
  <th>[!DNL Sales Connect] Task Field</th>
  <th>[!DNL Salesforce] Task Field</th>
  <th>[!DNL Salesforce] Task</th>
 </tr>
 <tr>
  <td>[!UICONTROL Task Name]</td>
  <td>[!UICONTROL Subject Field]</td>
  <td>A short summary field meant to show the title of the task.</td>
 </tr>
 <tr>
  <td>[!UICONTROL Status]</td>
  <td>[!UICONTROL Task Status]</td>
  <td><p>Shows the status of the task. [!DNL Sales Connect] tasks have two statuses that map to two of the values in the [!DNL Salesforce] task status picklist.</p>
  <p>Open in [!DNL Sales Connect] = Not Started in [!DNL Salesforce].</p>
  <p>Complete in [!DNL Sales Connect] = Completed in [!DNL Salesforce].</p>
  <p>The other status values in [!DNL Salesforce] will not sync to [!DNL Sales Connect].</p></td>
 </tr>
 <tr>
  <td>[!UICONTROL Priority]</td>
  <td>[!UICONTROL Priority]</td>
  <td><p>[!DNL Sales Connect] priority can be either Normal or High which maps to the Normal and High priority values in [!DNL Salesforce].</p>
  <p>The low priority value in [!DNL Salesforce] will not sync to [!DNL Sales Connect].</p></td>
 </tr>
 <tr>
  <td>[!UICONTROL Due Date]</td>
  <td>[!UICONTROL Due Date]</td>
  <td>The date the task is due.</td>
 </tr>
 <tr>
  <td>[!UICONTROL Details]</td>
  <td>[!UICONTROL Comments]</td>
  <td>Shows more detailed information around what was meant to be completed with the reminder task.</td>
 </tr>
</table>

## Syncing [!DNL Sales Connect] Tasks with [!DNL Salesforce] for the First Time {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

When you first turn on the sync between [!DNL Sales Connect] and [!DNL Salesforce] tasks, we import your [!DNL Salesforce] tasks. We will **not** push over any current tasks you have in [!DNL Sales Connect] to [!DNL Salesforce]. To reduce clutter and duplicates, the only tasks that get synced from [!DNL Sales Connect] into [!DNL Salesforce] are tasks created *after* you sync [!DNL Sales Connect] with SFDC.

Here's what happens when you sync [!DNL Sales Connect] and SFDC tasks:

* As soon as you click save on tasks syncing, they begin to sync over. This will take some time initially.

* Any reminders that have been updated or created in the last 24 hours will be pulled in from SFDC to [!DNL Sales Connect]. The sync is based on due date and all of those tasks will get synced over on the back-end, but in Command Center, you will only see tasks due today and tomorrow.

* If sync has been turned on previously and you delete any tasks in SFDC, anything that's been deleted in the last 15 days will be deleted from Command Center.

* We'll constantly sync tasks between [!DNL Sales Connect] and SFDC as long as the sync is enabled.

After the initial sync, any tasks you create, edit, complete, or delete in [!DNL Sales Connect] will sync over to your tasks list in [!DNL Salesforce]. And anything created, edited, completed, or deleted in [!DNL Salesforce] will update your tasks list in [!DNL Sales Connect].

To turn on this sync, just check the sync box in your [Settings page](https://toutapp.com/login) in the web application.

>[!NOTE]
>
>The subject field of a task can be updated in [!DNL Sales Connect] and that update will be synced in the [!DNL Salesforce] subject field for the corresponding synced task, if you are using the `{{activity_subject}}` dynamic field in your [Activity Detail Customization](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md) settings. Conversely, any updates made to the subject field in [!DNL Salesforce] will _not_ sync over to the [!DNL Sales Connect] reminder task subject field.
