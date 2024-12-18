---
description: Release Notes - October 2024 - Marketo Docs - Product Documentation
title: Release Notes - October 2024
feature: Release Information
---
# Release Notes: October 2024 {#release-notes-oct-24}

Below you'll find all the features included in the October '24 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **October 4, 2024**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Feature</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documention</th>
  </tr>
    <tr> 
   <td><strong>Tokenization for Interactive Webinars</strong>: You're now able to use tokens to promote Interactive Webinars in emails and Landing Pages without having to manually add the webinar details.</td> 
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/promoting-an-interactive-webinar.md#interactive-webinars-tokens" target="_blank">Promoting an Interactive Webinar</a></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  </tr>
   <tr> 
   <td><strong>Smart List "Set to Affect" Count</strong>: See how many people will be affected when editing the qualification rules of a Smart Campaign.</td> 
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  </tr>
   <tr> 
   <td><strong>My Account button in navigation rail</strong>: For those who have migrated to Adobe Identity Management System, a new "My Account" button in the left navigation rail allows configuring your time zone and accessing subscription details.</td> 
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
   <tr> 
   <td><strong>Email Performance Report Enhancements</strong>: Multiple improvements have been made to email reporting metrics and activity tracking, offering additional insights and improving accuracy.
   <ul>
   <li>Filter deleted and merged people from email performance metrics</li>
   <li>Emails now classified as <i>aborted</i> after waiting three days for response activity</li>
   <li>Email opens count as unique open separately for each Smart Campaign</li>
   </td> 
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md" target="_blank">Email Performance Report</a></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
   <tr> 
   <td><strong>Salesforce Sync Backlog Metrics</strong>: Monitor sync throughput and backlog trends in order to plan and schedule CRM updates for an optimum sync experience.
   </td> 
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-backlog-metrics.md" target="_blank">Salesforce Sync Backlog Metrics</a></td>
  </tr>
 </tbody> 
</table>
<br/> 

## Announcements {#announcements}

* **Bulk Extract API Update**: We fixed an issue in the Bulk Extract API involving the columnHeaderNames option, which lets you specify custom column header names in the exported file. Previously, column header names containing non-ASCII characters could become corrupted.

* **Rest API access_token Parameter Deprecation**: The 'access_token' query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after June 30, 2025. All new and existing integrations should authenticate REST API calls using the 'Authorization' header [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication#using-an-access-token).


* **QR Code Deprecation**: On October 4, 2024, the QR code feature used in push notifications and in-app messaging assets will be deprecated. This includes using QR codes for a new test device, as well as creating new assets with QR codes. Deprecating features with lower usage allows us to reallocate their resources to the overall maintenance of Marketo Engage.

* **Munchkin Changes**

  * **New Version**: On September 17, 2024, [Munchkin](/help/marketo/product-docs/administration/setup-administration/munchkin.md){target="_blank"} v.164 will begin rolling out to Marketo Engage instances that have the "Munchkin Beta" setting enabled in **Admin** > **Treasure Chest**. It's scheduled to begin rollout to all other instances on October 29. This version updates Munchkin cookie creation. There are no changes in functionality.

  * **Characters from URL Removed**: 'Visits Web Page' and 'Clicks Link' activities created by Munchkin JS will now remove non-URL encoded control characters from all URL fields. This change is designed to prevent errors related to propagation of those types of characters into systems that don't support them, and don't have a valid use within Marketo Engage.
