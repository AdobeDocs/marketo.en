---
description: Release Notes - July 2026 - Marketo Docs - Product Documentation
title: Release Notes - July 2026
feature: Release Information
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
   <td><strong>Marketo Engage New UI</strong>: The Marketo Engage interface has a refreshed look, including updated menus, icons, and layout for a cleaner, more modern experience. This is a visual update only; no existing functionality or workflows are affected.
</td>
   <td>Phased rollout throughout August and September</td>
   <td><i>n/a</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Marketo Engage MCP Server</strong>: The Marketo Engage MCP server acts as a bridge between your AI assistant and Marketo Engage. It exposes more than 100 operations across forms, programs, smart campaigns, people/leads, emails, snippets, lists, and folders.</td>
   <td>Now Generally Available</td>
   <td><a href="https://experienceleague.adobe.com/docs/marketo-developer/marketo/mcp-server.html" target="_blank">Marketo MCP Server</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Disable Campaigns on Archive</strong>: Archiving a folder now disables and deschedules all campaigns in that folder tree, preventing unexpected execution of archived Smart Campaigns.
</td>
   <td>Released</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-folders#disable-campaigns-archive" target="_blank">Disable Campaigns on Archive</a></td>
  </tr>
    <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Generate Content Contextual Menu</strong>: The "Generate content" features of the Email Designer can now be accessed from the contextual menu (the black bar). For example, when you select text content, the Generate content icon appears on the contextual menu, allowing you to perform quick actions.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Marketo AI is now Coworker for Marketo Engage**: Coworker for Marketo Engage provides agent skills designed to automate time-consuming marketing functions. New name, same features, available to all users. [Learn more](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/coworker-for-marketo/overview){target="_blank"}

* **REST API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after August 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **REST API Campaign Run ID**: Under certain circumstances, the Campaign Run ID value of an activity was sometimes returned with incorrect formatting, between two pairs of quotation marks (for example, `"campaignRunId": ""102938""`).<br/>Beginning with the August release, this value will always be returned with the correct numerical format (`"campaignRunId": 102938`)

* **Static List Size Limits for Get Lead Activities and Get Lead Changes**: Beginning September 30, 2026, calls to the Get Lead Activities or Get Lead Changes endpoints which include the `listId` parameter will fail with a 1003 Error Code (indicating that the target static list has too many records) if the target lists contain 10,000 or more leads. Consult the [Migration Guide](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"} for additional information.

* **REST API Merge Leads limit**: As of July 31, 2026, calls that include more than 25 IDs in the leadIds parameter of a Merge Leads API call result in a 1080 error code, and the call is skipped. Jobs requiring the merger of more than 25 records into one should be split into multiple jobs to ensure the success of those calls.
