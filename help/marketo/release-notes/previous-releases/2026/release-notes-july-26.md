---
description: Release Notes - July 2026 - Marketo Docs - Product Documentation
title: Release Notes - July 2026
feature: Release Information
---
# Release Notes: July 2026 {#release-notes-july-26}

Below you'll find all the features included in the July '26 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **July 10, 2026**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Marketo AI Skill - Product knowledge</strong>: Product knowledge gives you on-demand access to Marketo expertise without leaving the platform. Ask a question in plain language and Marketo AI draws on official Adobe documentation to provide an answer.
</td>
   <td>Open beta</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-ai/skills/product-knowledge" target="_blank">Product knowledge</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Marketo AI Skill - Investigate leads</strong>: Find out why a specific person/lead did not reach a milestone (like MQL, program qualification, or a campaign) and get a plain-language explanation of what happened.
</td>
   <td>Open beta</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-ai/skills/investigate-leads" target="_blank">Investigate leads</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Generate Content Contextual Menu</strong>: The "Generate content" features of the Email Designer can now be accessed from the contextual menu (the black bar). For example, when you select text content, the Generate content icon appears on the contextual menu, allowing you to perform quick actions from there.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after August 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.
* **REST API Merge Leads limit**: Beginning July 31, 2026, calls that include more than 25 IDs in the leadIds parameter of a Merge Leads API call will result in a 1080 error code, and the call will be skipped. Jobs requiring the merger of more than 25 records into one should be split into multiple jobs to ensure the success of those calls.
* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on July 31, 2026. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.
* **Static List Size Limits for Get Lead Activities and Get Lead Changes**: Beginning September 30, 2026, calls to the Get Lead Activities and Get Lead Changes endpoints that include the `listId` parameter will return a 1003 error code if the target static list contains 10,000 or more leads. Consult the [Migration Guide](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"} for more information.
