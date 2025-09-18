---
description: Release Notes - May 2025 - Marketo Docs - Product Documentation
title: Release Notes - May 2025
feature: Release Information
exl-id: 99cd1d54-0a80-40fa-9d0c-1cb437be90f0
---
# Release Notes: May 2025 {#release-notes-may-25}

Below you'll find all the features included in the May '25 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **May 23, 2025**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Role-based Access Control for Email Designer Assets</strong>: A new enhancement to the role-based access control (RBAC) system provides more granular permissions and improved user management for assets powered by the new Email Designer.</td>
   <td>Shipped</td>
   <td><a href="https://nation.marketo.com/t5/latest-product-innovations/product-updates-granular-permissions-to-new-email-designer/ba-p/357057">Granular permissions to New Email Designer (blog post)</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Cloning Emails Created in the Email Designer</strong>: You now have the ability to clone an existing email created using the new Email Designer.</td>
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Trigger Tokens for Any Attribute</strong>: Expanded list of trigger tokens to support using data from any activity attribute in Smart Campaign fields.</td>
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
 </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Facebook Offline Conversion Integration Update**: On May 29, 2025, the [Facebook Offline Conversion](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions){target="_blank"} integration for Marketo Engage will be migrated to the new Meta [Conversions API](https://developers.facebook.com/docs/marketing-api/conversions-api){target="_blank"}, due to Meta's deprecation of the [Offline Conversions API](https://developers.facebook.com/docs/marketing-api/offline-conversions/){target="_blank"} in line with Graph API versioning. For more information, please view Meta's guide to [sending offline events via Conversions API](https://developers.facebook.com/docs/marketing-api/conversions-api/offline-events/){target="_blank"} (CAPI for Offline).

* **New Analytics Feature - Public Beta**: [Advanced BI Analytics](/help/marketo/product-docs/reporting/advanced-bi-analytics/overview.md){target="_blank"} (formerly known as Revenue Explorer and Advanced Report Builder) began rolling out to all current Revenue Cycle Explorer users in mid-April. This new tool offers a flexible reporting and visualization interface on Marketo Engage data, providing granular details about progression, performance, and more. It features richer interactivity and visualization, faster performance, and a more seamless and intuitive user experience.

To access this feature, you must have purchased the Advanced BI Analytics add-on. Please contact the Adobe Account Team (your Account Manager) for details.

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after January 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on January 31, 2026. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.
