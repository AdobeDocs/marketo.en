---
description: Current Release Notes - Marketo Docs - Product Documentation
title: Current Release Notes
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
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
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Autocomplete Removal</strong>: The Autocomplete option in the token personalization editor was pointing to erroneous objects and has been removed. There are no plans to reimplement it at this time.</td>
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Email Preview Optimization</strong>: Some users were experiencing slower load times when trying to preview their email in the email/email template/fragment details page. This experience has been optimized for up to 60% faster load times.</td>
   <td><i>Coming Soon</i></td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Template Fixes</strong>: Some out-of-the-box templates were having rendering issues (e.g., not rendering correctly on certain browsers/dark mode, images misaligned, CTA buttons misplaced, and a few more). These are all fixed with this release.</td>
   <td><i>Coming Soon</i></td>
   <td>n/a</td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Content Locking Fix</strong>: Previously, if an email template was created with content locking and the template was used to create an email, content locking would persist even when the email was reset or "change design" was selected. This issue is fixed with this release.</td>
   <td><i>Coming Soon</i></td>
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

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after October 31, 2025. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on October 31, 2025. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.
