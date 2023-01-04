---
description: Sales Activity Glossary - Marketo Docs - Product Documentation
title: Sales Activity Glossary
exl-id: c7805642-07b6-4697-9efe-5c673ae9ca53
---
# Sales Activity Glossary {#sales-activity-glossary}

In Sales Connect, when a seller: adds a lead to a sales cadence, sends them an email, or makes a call an activity, it will be logged under the Marketo activity history. Additionally, when the lead engages with emails, opens, clicks, and replies also get logged.

The activities below will be logged to Marketo from [!DNL Sales Connect].

>[!NOTE]
>
>These activities and attributes are available to be consumed from our REST and Bulk API.

## Activities {#activities}

<table>
 <tr>
  <th>Sales Activity</th>
  <th>Attribute</th>
 </tr>
 <tr>
  <th rowspan="9">Send Sales Email</th>
  <td>[!UICONTROL Sent By]</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>[!UICONTROL Template ID]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Template] URL</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign] URL</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Template] Name</td>
 </tr>
 <tr>
  <td>[!UICONTROL Email Subject]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign Name]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Person ID]</td>
 </tr>
 <tr>
  <th rowspan="9"> Open Sales Email</th>
  <td>[!UICONTROL Sent By]</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>[!UICONTROL Template ID]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Template URL]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign URL]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Template Name]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Email Subject]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign Name]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Person ID]</td>
 </tr>
 <tr>
  <th rowspan="10">Clicked Sales Email</th>
  <td>[!UICONTROL Link]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sent By]</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>[!UICONTROL Template ID]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Template URL]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign URL]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Template Name]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Email Subject]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign Name]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Person ID]</td>
 </tr>
<tr>
  <th rowspan="3">Replied to Sales Email</th>
  <td>[!UICONTROL Received By]</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Person ID]</td>
 </tr>
 <tr>
  <th rowspan="11">Received Sales Call</th>
  <td>[!UICONTROL Sales Call Made By]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Call Status]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Call Subject]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign Name]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign URL]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Phone Number Called]</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Call Duration]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Call Recording URL]</td>
 </tr>
  <tr>
  <td>[!UICONTROL Sales Call Answered By]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Person ID]</td>
 </tr>
 <tr>
  <th rowspan="6">Add to Sales Campaign</th>
  <td>[!UICONTROL Sales Campaign Name]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Call Status]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign URL]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sent By]</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign ID]</td>
 </tr>
 <tr>
  <th rowspan="6">Remove from Sales Campaign</th>
  <td>[!UICONTROL Sales Campaign Name]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Call Status]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign URL]</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sent By]</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>[!UICONTROL Sales Campaign ID]</td>
 </tr>
</table>

## Descriptions {#descriptions}

<table> 
 <tr>
  <th>Attribute</th>
  <th>Description</th>
 </tr>
 <tbody> 
 <tr> 
   <td><strong>[!UICONTROL Details]</strong></td> 
   <td>Bounce error message detail.</td> 
  </tr> 
  <tr> 
   <td><strong>[!UICONTROL Email]</strong></td> 
   <td>Email address that bounced.</td> 
  </tr> 
  <tr> 
   <td><strong>[!UICONTROL Link]</strong></td> 
   <td>URL that was clicked.</td> 
  </tr> 
  <tr> 
   <td><strong>[!UICONTROL Marketo Sales Person ID]</strong></td> 
   <td>Unique ID for person record in [!DNL Sales Connect].</td> 
  </tr> 
  <tr> 
   <td><strong>[!UICONTROL Received By]</strong></td> 
   <td>Email address of the person who sent the email.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Call Answered By]</strong></td> 
   <td>Name of person who answered the call.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Call Duration]</strong></td> 
   <td>Length of call in seconds.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Call Made By]</strong></td> 
   <td>Email address of sales person who made the call.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Call Recording URL]</strong></td> 
   <td>URL of call recording.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Call Status]</strong></td> 
   <td>Will save the final call status of the call which includes: completed, no answer, cancelled, failed.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Call Subject]</strong></td> 
   <td>Call outcome that's selected by a sales user in the dialer.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Campaign ID]</strong></td> 
   <td>Unique ID for Sales Campaign asset in [!DNL Sales Connect].</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Campaign Name]</strong></td> 
   <td>Name of Sales Campaign.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Campaign URL]</strong></td> 
   <td>[!DNL Sales Connect] URL for Sales Campaign.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Email Subject]</strong></td> 
   <td>Subject line of email followed by a unique ID (ex: My Subject Line (MSC-12345678)</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Phone Number Called]</strong></td> 
   <td>Phone number called by Sales.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Template Name]</strong></td> 
   <td>Name of email template in [!DNL Sales Connect].</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sales Template URL]</strong></td> 
   <td>[!DNL Sales Connect] URL for email template.</td> 
  </tr>
  <tr> 
   <td><strong>[!UICONTROL Sent By]</strong></td>
   <td>Email address of the person who sent the email.</td> 
  </tr> 
  <tr> 
   <td><strong>[!UICONTROL Source]</strong></td> 
   <td>Source of the activity. Will be set as "Tout" for [!DNL Sales Connect] activities prior to the Oct '21 Release. Will be "Sales App" for [!DNL Sales Connect] activities after the Oct '21 Release.</td>
  </tr> 
  <tr> 
   <td><strong>[!UICONTROL Template ID]</strong></td> 
   <td>When the source is Tout, the Template ID will be the [!DNL Marketo Sales Connect] Template ID. Use this to target a specific template instead of subject line, which could exist in multiple templates.
</td> 
  </tr> 
 </tbody> 
</table>
