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
# Release Notes: September 2026 {#release-notes-sep-26}

Below you'll find all the features included in the September '26 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **September 25, 2026**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Marketo Engage New UI</strong>: The Marketo Engage interface has a refreshed look, including updated menus, icons, and layout for a cleaner, more modern experience. This is a visual update only; no existing functionality or workflows are affected. <i>The ability to select the Classic UI will be available through the January 2027 release</i>.
</td>
   <td>General Availability by the end of September</td>
   <td><i>n/a</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Select Partition on Import</strong>: You can now select from the local workspace's list of Partitions when importing person records in environments that have Workspaces and Partitions enabled.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Instant Alert on CRM Sync</strong>: Users subscribed to CRM notifications will receive an immediate notification when the enabled status of their native CRM sync changes, giving admins greater visibility of their CRM sync status.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
   <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Self-Service Flow Steps - Increased Callback Timeout</strong>: The callback timeout period for Self-Service Flow Steps is being increased from one hour to four hours. No action is required on your end.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Tables</strong>: You can now drag and drop the content type "table" into your email, with the ability to set the number of columns and rows.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **API Name Restrictions for Custom Activity Attributes**: API Names for Custom Activity Attributes created via the API or UI may now only contain alphanumeric characters and underscores, and must begin with an alphanumeric character.

* **Static List Size Limits for Get Lead Activities and Get Lead Changes**: Beginning September 30, 2026, calls to the Get Lead Activities or Get Lead Changes endpoints which include the `listId` parameter will fail with a 1003 Error Code (indicating that the target static list has too many records) if the target lists contain 10,000 or more leads. Consult the [Migration Guide](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"} for additional information.

* **REST API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls has been deprecated as of August 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **REST API Campaign Run ID**: Under certain circumstances, the Campaign Run ID value of an activity was sometimes returned with incorrect formatting, between two pairs of quotation marks (for example, `"campaignRunId": ""102938""`).<br/>As of the August release, this value will always be returned with the correct numerical format (`"campaignRunId": 102938`).

* **Deprecation of Grab Images from Web**: To conform to modern security and privacy best practices, the [Grab Images from Web](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/images-and-files/grab-the-images-from-a-web-page){target="_blank"} feature will be deprecated as of the October release.
