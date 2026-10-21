---
description: Release Notes - September 2026 - Marketo Docs - Product Documentation
title: Release Notes - September 2026
feature: Release Information
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
subfeature_v2:
  - id: af97ce94-35fa-4fa9-b85a-46b752ac4028
    internal-label: Release information
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
   <td>General Availability by mid-October</td>
   <td><i>n/a</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Select Partition on Import</strong>: You can now select from the local workspace's list of Partitions when importing person records in environments that have Workspaces and Partitions enabled.</td>
   <td>Released</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/quick-wins/import-a-list-of-people#step-import-your-spreadsheet-into-marketo:~:text=If%20you%20have%20Person%20Partitions%20set%20up" target="_blank">List import</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Self-Service Flow Steps - Increased Callback Timeout</strong>: The callback timeout period for Self-Service Flow Steps is being increased from one hour to four hours. No action is required on your end.</td>
   <td>Released</td>
   <td>n/a</td>
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

* **Deprecation of Grab Images from Web**: To conform to modern security and privacy best practices, the [Grab Images from Web](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/images-and-files/grab-the-images-from-a-web-page){target="_blank"} feature will be deprecated as of the November release.
