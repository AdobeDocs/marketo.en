---
description: Sales Activity Glossary - Marketo Docs - Product Documentation
title: Sales Activity Glossary
hide: yes
hidefromtoc: yes
---
# Sales Activity Glossary {#sales-activity-glossary}

In Sales Connect, when a seller: adds a lead to a sales cadence, sends them an email, or makes a call an activity, it will be logged under the Marketo activity history. Additionally, when the lead engages with emails, opens, clicks, and replies also get logged.

The activities below will be logged to Marketo from Sales Connect.

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
  <th rowspan="3">Send Sales Email</th>
  <td>Sent By</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>Template ID</td>
 </tr>
 <tr>
  <th rowspan="3">Open Sales Email</th>
  <td>Sent By</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>Template ID</td>
 </tr>
 <tr>
  <th rowspan="4">Clicked Sales Email</th>
  <td>Link</td>
 </tr>
 <tr>
  <td>Sent By</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>Template ID</td>
 </tr>
 <tr>
  <th rowspan="2">Received Sales Email</th>
  <td>Received By</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <th rowspan="4">Sales Email Bounced</th>
  <td>Details</td>
 </tr>
 <tr>
  <td>Template ID</td>
 </tr>
 <tr>
  <td>Email</td>
 </tr>
 <tr>
  <td>Sent By</td>
 </tr>
 <tr>
  <th rowspan="7">Received Sales Call</th>
  <td>Sales Call Made By</td>
 </tr>
 <tr>
  <td>Sales Call Status</td>
 </tr>
 <tr>
  <td>Sales Call Subject</td>
 </tr>
 <tr>
  <td>Sales Campaign Name</td>
 </tr>
 <tr>
  <td>Sales Campaign URL</td>
 </tr>
 <tr>
  <td>Sales Phone Number Called</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <th rowspan="6">Add to Sales Campaign</th>
  <td>Sales Campaign Name</td>
 </tr>
 <tr>
  <td>Sales Call Status</td>
 </tr>
 <tr>
  <td>Sales Campaign URL</td>
 </tr>
 <tr>
  <td>Sent By</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>Sales Campaign ID</td>
 </tr>
 <tr>
  <th rowspan="6">Remove from Sales Campaign</th>
  <td>Sales Campaign Name</td>
 </tr>
 <tr>
  <td>Sales Call Status</td>
 </tr>
 <tr>
  <td>Sales Campaign URL</td>
 </tr>
 <tr>
  <td>Sent By</td>
 </tr>
 <tr>
  <td>Source</td>
 </tr>
 <tr>
  <td>Sales Campaign ID</td>
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
   <td><strong>Sent By</strong></td>
   <td>Email address of the person who sent the email.</td> 
  </tr> 
  <tr> 
   <td><strong>Source</strong></td> 
   <td>Source of the activity. Will be set as "Tout" for Sales Connect activities.</td> 
  </tr> 
  <tr> 
   <td><strong>Template ID</strong></td> 
   <td>When the source is Tout, the Template ID will be the Marketo Sales Connect Template ID. Use this to target a specific template instead of subject line, which could exist in multiple templates.
</td> 
  </tr> 
  <tr> 
   <td><strong>Received By</strong></td> 
   <td>Email address of the person who sent the email.</td> 
  </tr> 
  <tr> 
   <td><strong>Details</strong></td> 
   <td>Bounce error message detail.</td> 
  </tr> 
  <tr> 
   <td><strong>Email</strong></td> 
   <td>Email address that bounced.</td> 
  </tr> 
 </tbody> 
</table>