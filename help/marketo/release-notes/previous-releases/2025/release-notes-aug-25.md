---
description: Release Notes - August 2025 - Marketo Docs - Product Documentation
title: Release Notes - August 2025
feature: Release Information
exl-id: f4f71a77-d0c0-41c3-9362-afbfb467cc7a
TQID: https://experienceleague.adobe.com/Tt3KgAUlQd8oBN2KV-dFUQdEPmlZ-3tOzQ8T-EaCTfI
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: c942e9f6-ed06-481a-abdd-1195363d1452
    internal-label: Dynamic Chat
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: cdd65e7e-8839-44a2-bc21-0e03623b5dd1
    internal-label: Optimization
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Release Notes: August 2025 {#release-notes-aug-25}

Below you'll find all the features included in the August '25 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **August 22, 2025**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Email Designer - Reporting</strong>: Email Performance and Email Link Performance reports now show data from emails created using the new Email Designer.</td>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Autocomplete Removal</strong>: The Autocomplete option in the token personalization editor was pointing to erroneous objects and has been removed. There are no plans to reimplement it at this time.</td>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Email Preview Optimization</strong>: Some users were experiencing slower load times when trying to preview their email in the email/email template/fragment details page. This experience has been optimized for up to 60% faster load times.</td>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Template Fixes</strong>: Some out-of-the-box templates were having rendering issues (e.g., not rendering correctly on certain browsers/dark mode, images misaligned, CTA buttons misplaced, and a few more). These are all fixed with this release.</td>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Content Locking Fix</strong>: Previously, if an email template was created with content locking and the template was used to create an email, content locking would persist even when the email was reset or "change design" was selected. This issue is fixed with this release.</td>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Marketo Engage Identity End of Life**: In August 2025, Adobe began phasing out support for Marketo Engage Identity (logging in via `login.marketo.com`). To prevent interrupted access to Marketo Engage, you must transition to [Adobe Identity](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"} no later than September 30, 2025.

  * _IP Restrictions Deprecation_: Support for [Restricting Marketo Logins Based on IP](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"} ended on July 30, 2025. The feature will remain operational until the transition to Adobe Identity is complete. A new location-based access control feature for Adobe Identity in the Adobe Admin Console is coming soon.

  * _Single Sign-On (SSO) Deprecation_: Support for [Marketo Identity SSO](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"} ended on July 30, 2025. The feature will remain operational until the transition to Adobe Identity is complete. Single Sign-On for Adobe Identity in the Adobe Admin Console must be configured separately. For setup steps, see [Set up identity and Single Sign-On](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

* **Deprecation of _Forward to a Friend_ Feature**: On September 29, 2025, the _Forward to a Friend_ feature in Marketo Engage 2.0 emails (the legacy email editor) will be completely deprecated for all subscriptions. This affects the 'Forward to a Friend' token and 'Forward to a Friend' links in emails that have already been or will be sent using the token. [Learn more](https://nation.marketo.com/t5/product-blogs/deprecation-of-forward-to-a-friend/ba-p/358045#M2889){target="_blank"}

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after March 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on March 31, 2026. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.
