---
description: "Current Release Notes - Marketo Docs - Product Documentation"
title: Current Release Notes
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
---
# Release Notes: March 2026 {#release-notes-mar-26}

Below you'll find all the features included in the March '26 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **March 27, 2026**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Email Designer - Manage Brands (beta)</strong>: Generate email content based on your organization/brand's specific copywriting guidelines.</td>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/brands/manage-brands.md" target="_blank">Create and manage brands</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Quick Actions</strong>: <i>Parity with the old email editor</i>. Quick actions are now available for all Email Designer assets (emails, email templates, fragments). Supported quick actions include: Duplicate, Delete, Move, Create/Edit Draft.
   </td>
   <td>Released</i></td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
   <tr>
   <td><strong>Email Designer - Outlook Rendering Fix</strong>: This update fixes rendering issues, especially in MS Outlook. Advanced HTML Mode allows you to make minor HTML/CSS edits or add script tags to your email template.
   </td>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/advanced-html-mode.md" target="_blank">Edit email templates with the advanced HTML editor</a></td>
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
   <td><strong>Picklist Management</strong>: You can now specify the values that can be used in fields in Marketo Engage.
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
   <td><strong>Push Notifications</strong>: Redirect URLs configured in Push notification messages now support Marketo Engage tokens (applicable to <i>Launch App URLs</i> only).
   </td>
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
