---
description: Current Release Notes - Marketo Docs - Product Documentation
title: Current Release Notes
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
---
# Release Notes: April 2024 {#release-notes-apr-24}

Below you'll find all the features included in the April '24 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **April 26, 2024**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Feature</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documention</th>
  </tr>
   <tr> 
   <td><strong>Templates for Interactive Webinars</strong>: Save time by creating custom templates for room layouts branded with specifications that fit your organization.</td> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
   <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
   </tr>
     <tr> 
   <td><strong>Interactive Webinars Enhancements</strong>: You can now provide hosts and presenters with the ability to add a webinar title, rename a room, and manually sync engagement data after the event delivery.</td> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
    <tr> 
   <td><strong>Audit Trail Enhancements</strong>: 
   New types of actions can now be captured in Audit Trail for changes made in Field Management, changes made to Users and Roles, and the count of people exported from lists and Smart Lists.</td> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
    <tr> 
   <td><strong>New Users & Roles Permissions</strong>: New permissions are available, providing users with more granular access to Marketo Engage. Control parts of Admin not previously gated such as New Experience and Predictive Audiences, split permissions to grant access to Asset Audit Trail and Admin Audit Trail separately, and utilize new create and move permissions for assets and folders to prevent read-only users from making changes.</td> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## Announcements {#announcements}

* **Activities API Update**: On April 26, we're adding several new attributes to web-based and email-based activities that are returned when you retrieve activities using the [Marketo REST API](https://developers.marketo.com/rest-api/lead-database/activities/){target="_blank"}. The activities listed below will now include Browser, Platform, Device, and User Agent attributes. Call the [Get Activity Types](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Activities/getAllActivityTypesUsingGET){target="_blank"} endpoint to review attribute details for each activity.

**Web-based Activities**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:30%">Activity</th> 
   <th style="width:70%">Newly Added Attributes</th>
   </tr>
  <tr> 
   <td>Visit Webpage</td> 
   <td>Browser, Platform, Device</td>
  </tr>
   <tr> 
   <td>Fill Out Form</td> 
   <td>Browser, Platform, Device</td>
  </tr>
  <tr> 
   <td>Click Link</td> 
   <td>Browser, Platform, Device</td>
  </tr>
 </tbody> 
</table>

**Email-based Activities**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:30%">Activity</th> 
   <th style="width:70%">Newly Added Attributes</th>
  </tr>
   <tr> 
   <td>Send Email</td> 
   <td>Browser, Platform, Device, User Agent</td>
  </tr>
   </tr>
  <tr> 
   <td>Email Delivered</td> 
   <td>Browser, Platform, Device, User Agent</td>
  </tr>
   <tr> 
   <td>Email Bounced</td> 
   <td>Browser, Platform, Device, User Agent</td>
  </tr>
  <tr> 
   <td>Unsubscribe Email</td> 
   <td>Browser, Platform, Device</td>
  </tr>
  <tr> 
   <td>Open Email</td> 
   <td>Browser</td>
  </tr>
   <tr> 
   <td>Click Email</td> 
   <td>Browser</td>
  </tr>
  <tr> 
   <td>Email Bounced Soft</td> 
   <td>Browser, Platform, Device, User Agent</td>
  </tr>
 </tbody> 
</table>
