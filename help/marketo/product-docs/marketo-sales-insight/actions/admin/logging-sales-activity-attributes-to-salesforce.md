---
description: Logging Sales Activity Attributes to Salesforce - Marketo Docs - Product Documentation
title: Logging Sales Activity Attributes to Salesforce
hide: yes
hidefromtoc: yes
exl-id: fdefe53b-eb99-48ce-a04e-3666be33fea4
---
# Logging Sales Activity Attributes to Salesforce {#logging-sales-activity-attributes-to-salesforce}

Salesforce admin can manually add custom activity fields to Salesforce.  

1. In your Salesforce account, click **Setup**.

1. Search for “Activity Custom Fields” in the quick search field and click on it.  

1. Click **New**.

1. Select Data Type corresponding to the field you want to add based on the table below and click **Next**.

1. Enter the Field name and label corresponding to the field you want to add.

Description of each column in the table below:

* **Field Label**: Field name shown in the UI
* **Field Name**: Technical name of the field (make sure the Field Name you enter matches the Field Name in the table below)
* **API Name**: Technical name of the field for API (make sure the API name you enter matches the API name in the table below)
* **Data type**: Type of field
* **Size**: Size of the text field

<table>
 <tr>
  <th>Field Label</th>
  <th>Field Name</th>
  <th>API Name</th>
  <th>Data Type</th>
  <th>Size</th>
 </tr>
 <tr>
  <td>Marketo Sales Call Local Presence ID</td>
  <td>MSE_Call_Local_Presence_ID</td>
  <td>MSE_Call_Local_Presence_ID__c</td>
  <td>Text</td>
  <td>255</td>
 </tr>
 <tr>
  <td>Marketo Sales Call Recording URL</td>
  <td>MSE_Call_Recording</td>
  <td>MSE_Call_Recording__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Campaign</td>
  <td>MSE_Campaign</td>
  <td>MSE_Campaign__c</td>
  <td>Text</td>
  <td>255</td>
 </tr>
 <tr>
  <td>Marketo Sales Campaign Current Step</td>
  <td>MSE_Current_Campaign_Step</td>
  <td>MSE_Current_Campaign_Step__c</td>
  <td>Text</td>
  <td>255</td>
 </tr>
 <tr>
  <td>Marketo Sales Campaign URL</td>
  <td>MSE_Campaign_Details_Link</td>
  <td>MSE_Campaign_Details_Link__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email Attachment Viewed</td>
  <td>MSE_Presentation_Viewed</td>
  <td>MSE_Presentation_Viewed__c</td>
  <td>Checkbox</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email Clicked</td>
  <td>MSE_Clicked</td>
  <td>MSE_Clicked__c</td>
  <td>Checkbox</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email Replied</td>
  <td>MSE_Replied</td>
  <td>MSE_Replied__c</td>
  <td>Checkbox</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email Status</td>
  <td>MSE_Email_Status</td>
  <td>MSE_Email_Status__c</td>
  <td>Text</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email Template</td>
  <td>MSE_Template</td>
  <td>MSE_Template__c</td>
  <td>Text</td>
  <td>255</td>
 </tr>
 <tr>
  <td>Marketo Sales Email Template URL</td>
  <td>MSE_Template_Details</td>
  <td>MSE_Template_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email URL</td>
  <td>MSE_Details</td>
  <td>MSE_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email Viewed</td>
  <td>MSE_Viewed</td>
  <td>MSE_Viewed__c</td>
  <td>Checkbox</td>
  <td></td>
 </tr>
</table>
