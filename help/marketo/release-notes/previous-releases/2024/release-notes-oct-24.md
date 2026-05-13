---
description: Release Notes - October 2024 - Marketo Docs - Product Documentation
title: Release Notes - October 2024
feature: Release Information
exl-id: 2e28ae7f-51de-4510-b3e8-79a989f0daf5
TQID: https://experienceleague.adobe.com/3Qk4bF8OVxVoJYZbtedik6vRsAebYvj-ZMOfxXuzDMk
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
subfeature_v2:
  - id: c942e9f6-ed06-481a-abdd-1195363d1452
    internal-label: Dynamic Chat
  - id: efc9a24a-a6a4-449d-a3e6-44f6c74dfd46
    internal-label: Adobe Identity Management
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
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
   <td><strong>Tokenization for Interactive Webinars</strong>: you are now able to use tokens to promote Interactive Webinars in emails and Landing Pages without having to manually add the webinar details.</td>
   <td>Released</td>
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
   <td>Released</td>
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
   <td>Released</td>
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
   <td>Released</td>
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
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-backlog-metrics.md" target="_blank">Salesforce Sync Backlog Metrics</a></td>
  </tr>
 </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Bulk Extract API Update**: We fixed an issue in the Bulk Extract API involving the columnHeaderNames option, which lets you specify custom column header names in the exported file. Previously, column header names containing non-ASCII characters could become corrupted.

* **Rest API access_token Parameter Deprecation**: The 'access_token' query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after March 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication#using-an-access-token).

* **QR Code Deprecation**: On October 4, 2024, the QR code feature used in push notifications and in-app messaging assets will be deprecated. This includes using QR codes for a new test device, as well as creating new assets with QR codes. Deprecating features with lower usage allows us to reallocate their resources to the overall maintenance of Marketo Engage.

* **Munchkin Changes**

  * **New Version**: On September 17, 2024, [Munchkin](/help/marketo/product-docs/administration/setup-administration/munchkin.md){target="_blank"} v.164 will begin rolling out to Marketo Engage instances that have the "Munchkin Beta" setting enabled in **Admin** > **Treasure Chest**. It is scheduled to begin rollout to all other instances on October 29. This version updates Munchkin cookie creation. There are no changes in functionality.

  * **Characters from URL Removed**: 'Visits Web Page' and 'Clicks Link' activities created by Munchkin JS will now remove non-URL encoded control characters from all URL fields. This change is designed to prevent errors related to propagation of those types of characters into systems that don't support them, and don't have a valid use within Marketo Engage.
