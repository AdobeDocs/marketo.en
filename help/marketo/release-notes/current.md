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
# Release Notes: July 2026 #1 of 2 {#release-notes-july-26-one}

Below you'll find all the features included in the first July '26 release. Check your Adobe Marketo Engage edition for feature availability.

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
   <td><strong>Marketo AI skill - Product knowledge</strong>: Product knowledge gives you on-demand access to Marketo expertise without leaving the platform. Ask a question in plain language and Marketo AI draws on official Adobe documentation to answer it.
</td>
   <td>Open beta</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-ai/skills/product-knowledge" target="_blank">Marketo AI overview</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Marketo AI skill - Investigate leads</strong>: Find out why a specific person/lead did not reach a milestone (like MQL, program qualification, or a campaign) and get a plain-language explanation of what happened.
</td>
   <td>Open beta</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-ai/skills/investigate-leads" target="_blank">Marketo AI overview</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - AI Assistant Contextual Menu</strong>: The AI Assistant features of the Email Designer can now be accessed from the contextual menu (the black bar). For example, when you select text content, the AI Assistant icon appears on the contextual menu, allowing you to perform quick actions from there.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after July 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **REST API Merge Leads limit**: Beginning July 31, 2026, calls that include more than 25 IDs in the leadIds parameter of a Merge Leads API call will result in a 1080 error code, and the call will be skipped. Jobs requiring the merger of more than 25 records into one should be split into multiple jobs to ensure the success of those calls.

* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on July 31, 2026. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.

* **Static List Size Limits for Get Lead Activities and Get Lead Changes**: Beginning September 30, 2026, calls to the Get Lead Activities and Get Lead Changes endpoints that include the `listId` parameter will return a 1003 error code if the target static list contains 10,000 or more leads. Consult the [Migration Guide](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"} for more information.
