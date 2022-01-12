---
description: Configure Salesforce Activity Detail Customization - Marketo Docs - Product Documentation
title: Configure Salesforce Activity Detail Customization
hide: yes
hidefromtoc: yes
exl-id: 4b20ca29-18d6-4026-9bf9-77656ad1442d
---
# Configure Salesforce Activity Detail Customization {#configure-salesforce-activity-detail-customization}

>[!PREREQUISITES]
>
>* Salesforce and Marketo Sales Connect [must be connected](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/connect-your-sales-connect-account-to-salesforce.md)
>* Logging email activity via API [must be enabled](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md)

Activity Detail Customization allows admins to configure the information that will log to the Salesforce Task - Subject Field, when a Sales Connect activity/reminder task is synced to Salesforce.

![](assets/configure-salesforce-activity-detail-customization-1.png)

![](assets/configure-salesforce-activity-detail-customization-2.png)

<table>
 <tr>
  <td><strong>1</td>
  <td>InMail Reminder Task</td>
 </tr>
 <tr>
  <td><strong>2</td>
  <td>Email Activity</td>
 </tr>
 <tr>
  <td><strong>3</td>
  <td>Call Activity</td>
 </tr>
</table>

The feature can be used to unlock the following benefits:

* By customizing what information is visible on the subject field, activity details are easily scannable for sales in Salesforce.
* Admins can tag the subject field with a unique identifier such as “Mkto_sales” so activities from Sales Connect can be easily identified and differentiated from other email activities, call activities, and tasks.
* Reduce the need for custom activity fields. Salesforce enforces limits on the number of custom activity fields, which can restrict what data is available to be used in reports. By using activity dynamic fields to add key data to the subject line you can reduce the number of custom activity fields you need created in your Salesforce instance.  
* The subject field of activities and tasks will follow a consistent pattern defined by the Sales Connect Admin.  

## Activity Dynamic Fields Supported {#activity-dynamic-fields-supported}

Activity Dynamic Fields reference information about your sales activities to populate data. Today, they can be used with Salesforce Activity Detail Customization.

>[!NOTE]
>
>If there's no value to populate the dynamic field for a specific activity/task, it will not populate any data for that dynamic field when the Salesforce Task – Subject Field is updated.  

<table>
 <tr>
  <th>Field</th>
  <th>Description</th>
 </tr>
 <tr>
  <td>{{activity_type}}</td>
  <td>Will populate the task type as Email, Call, InMail, or Custom.</td>
 </tr>
 <tr>
  <td>{{activity_subject}}</td>
  <td><p>Will populate the subject of the task.</p>
      <p>In the case of an email it will populate the subject line of the email.</p>
      <p>In the case of call, inMail, or custom, it will populate a value if there was a reminder task created with a value in the task name/subject field.</p></td>
 </tr>
 <tr>
  <td>{{sales_campaign_name}}</td>
  <td>If the activity was initiated from a sales campaign, it will populate the name of the sales campaign.</td>
 </tr>
 <tr>
  <td>{{sales_campaign_day}}</td>
  <td>If the activity was initiated from a sales campaign, it will populate the sales campaign day number this activity occurred on.</td>
 </tr>
 <tr>
  <td>{{sales_campaign_step}}</td>
  <td>If the activity was initiated from a sales campaign, it will populate the step number within the sales campaign day this activity occurred on.</td>
 </tr>
 <tr>
  <td>{{call_outcome}}</td>
  <td>If the activity is a call and a call outcome is selected, this will populate the call outcome value.</td>
 </tr>
 <tr>
  <td>{{call_reason}}</td>
  <td>If the activity is a call and a call reason is selected, this will populate the call reason value.</td>
 </tr>
</table>

## Configuring Salesforce Activity Detail Customization {#configuring-salesforce-activity-detail-customization}

>[!NOTE]
>
>**Admin permissions required.**

When configuring your activity details, consider what data would be most relevant to sales when reviewing task history in Salesforce.

1. Click the gear icon and select **Settings**.

PICC

1. Click **Salesforce**.

PICC

1. Click **Sync Settings**.

PICC

1. In the Activity Details Customization editor add any free text you want, this will remain unchanged for the subject field of all tasks synced to Salesforce.

1. Add any dynamic fields you would like to add by clicking the dynamic field button and selecting the dynamic fields you want to use from the list.  

1. Click **Save**.

>[!NOTE]
>
>Salesforce enforces a 255 character limit. If your activity detail exceeds that, it will be truncated to ensure the information can be stored on the Salesforce subject field.  

>[!MORELIKETHIS]
>
>* [Sync Settings](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md)
>* [Reminder Task Sync with Salesforce](/help/marketo/product-docs/marketo-sales-connect/tasks/reminder-task-sync-with-salesforce.md)
>* [Sales Connect Customization for CRM](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/sales-connect-customizations-for-crm.md)
