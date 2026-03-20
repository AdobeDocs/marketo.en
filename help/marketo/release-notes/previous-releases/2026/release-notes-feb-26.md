---
description: Release Notes - February 2026 - Marketo Docs - Product Documentation
title: Release Notes - February 2026
feature: Release Information
exl-id: 679d2fca-99ba-4321-ad0d-a297b7f193fc
---
# Release Notes: February 2026 {#release-notes-feb-26}

Below you'll find all the features included in the February '26 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **February 20, 2026**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Email Designer - Folder Actions</strong>: Parity with the old email editor.
   <ul>
   <li>Share and archive folder actions for Email Designer assets.</li>
   <li>Share folders across workspaces, right-click on a folder to create a new asset, move assets via drag-and-drop.</li>
   </ul>
   </td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - API</strong>: You can now use API calls for the Email Designer.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Brand Quality Checker</strong>: Assess general content quality to identify potential issues with readability, content cohesiveness, and effectiveness, independent of your brand guidelines.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - AI Assistant Image Generation</strong>: Now, in addition to Firefly, you can use Nano Banana models to generate images with the AI Assistant for email content.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **SEO Feature Deprecation**: On Tuesday, March 31, 2026, Marketo Engage will deprecate the Search Engine Optimization feature (SEO). If you don't actively use SEO, you don't have to do anything. If you have used SEO recently, you have the option of exporting your data. [Learn more](https://experienceleaguecommunities.adobe.com/adobe-marketo-engage-27/seo-feature-deprecation-248617){target="_blank"}.

* **REST API Merge Leads limit**: Beginning March 31, 2026, calls that include more than 25 IDs in the leadIds parameter of a Merge Leads API call will result in a 1080 error code, and the call will be skipped. Jobs requiring the merger of more than 25 records into one should be split into multiple jobs to ensure the success of those calls.

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after July 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on July 31, 2026. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.
