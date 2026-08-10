---
description: Current Release Notes - Marketo Docs - Product Documentation
title: Current Release Notes
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
TQID: https://experienceleague.adobe.com/QJFy7PeGXlvS3jcJGcZJROlc8c1UvphO-TOOwPUQeX8
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: c942e9f6-ed06-481a-abdd-1195363d1452
    internal-label: Dynamic Chat
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Release Notes: August 2026 {#release-notes-aug-26}

Below you'll find all the features included in the August '26 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **August 14, 2026**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Marketo Engage New UI</strong>: The Marketo Engage interface has a refreshed look, including updated menus, icons, and layout for a cleaner, more modern experience. This is a visual update only, no existing functionality or workflows are affected.
</td>
   <td>Phased rollout throughout the month of August</td>
   <td><i>n/a</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Script Builder</strong>: Script Builder is an AI-powered assistant that helps you create personalization scripts faster.
</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Disable Campaigns on Archive</strong>: Archiving a folder now disables and deschedules all campaigns in that folder tree, preventing unexpected execution of archived Smart Campaigns.
</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after August 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **REST API Campaign Run ID**: Under certain circumstances, the Campaign Run ID value of an activity was sometimes returned with incorrect formatting, between two pairs of quotation marks (for example, `"campaignRunId": ""102938""`).<br/>Beginning with the August release, this value will always be returned with the correct numerical format (`"campaignRunId": 102938`)

* **Static List Size Limits for Get Lead Activities and Get Lead Changes**: Beginning September 30, 2026, calls to the Get Lead Activities or Get Lead Changes endpoints which include the `listId` parameter will fail if the target lists contain 10,000 or more leads with a 1003 Error Code indicating that the target static list has too many records.

Consult the [Migration Guide](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"} for additional information.

* **REST API Merge Leads limit**: As of July 31, 2026, calls that include more than 25 IDs in the leadIds parameter of a Merge Leads API call result in a 1080 error code, and the call is skipped. Jobs requiring the merger of more than 25 records into one should be split into multiple jobs to ensure the success of those calls.
