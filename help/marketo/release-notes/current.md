---
description: "Current Release Notes - Marketo Docs - Product Documentation"
title: Current Release Notes
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
---
# Release Notes: October 2025 {#release-notes-oct-25}

Below you'll find all the features included in the October '25 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **October 31, 2025**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Email Designer - Template Importer (Beta)</strong>: Import email templates from the classic email editor to create  templates compatible with the New Email Designer in the Design Studio.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Conditional Content</strong>: Parity feature for the new Email Designer, allowing you to achieve email personalization beyond tokens.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - A/B Testing</strong>: Parity feature for the new Email Designer, allowing you to perform A/B tests to see which types of content receive the best response.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Brand Themes</strong>: You can now define brand themes within Marketo Engage. Styling configurations can be reused and applied across email templates and other email assets for brand consistency.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
 <tr>
   <td><strong>Email Designer - Image to HTML Converter</strong>: Upload a compliant PNG/JPEG image file of an email and it will automatically be converted into HTML for use in the new Email Designer.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Clone Email Action</strong>: You can now clone an email into another program folder in Marketing Activities and quickly reuse existing emails.</td>
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Salesforce CRM Integration Upgrade**: A new version of the native CRM integration will be deployed to active sandboxes that have the native connector enabled over the course of seven days, beginning November 13, 2025. Get full details in [this Nation post](https://nation.marketo.com/t5/product-blogs/salesforce-crm-integration-upgrade/ba-p/358702){target="_blank"}

* **REST API Double Slash Deprecation**: On September 16, 2025, Adobe transitioned to a more modern hosting infrastructure for REST API URLs that leverages newer technology, adding security and scalability. If your subscription has been using APIs with a double forward slash (//) in the URL, please read [this Nation post](https://nation.marketo.com/t5/product-blogs/rest-api-double-slash-deprecation/ba-p/358616){target="_blank"} for next steps.

* **Switching Back to Velocity Scripting in the new Email Designer**: Adobe Marketo Engage released a feature called _Conditional Content_ for the new Email Designer this past June. The feature was powered by Handlebar scripting instead of Velocity scripting, in an effort to provide a little more flexibility in your dynamic content. But when we discovered it was causing some tokens to be resolved incorrectly, we decided to temporarily disable it. [Learn More](https://nation.marketo.com/t5/product-blogs/update-on-email-scripting-in-the-new-email-designer/ba-p/358179){target="_blank"}

* **Marketo Engage Identity End of Life**: In August 2025, Adobe began phasing out support for Marketo Engage Identity (logging in via `login.marketo.com`). To prevent interrupted access to Marketo Engage, you must transition to [Adobe Identity](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"} no later than September 30, 2025.

  * _IP Restrictions Deprecation_: Support for [Restricting Marketo Logins Based on IP](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"} ended on July 30, 2025. The feature will remain operational until the transition to Adobe Identity is complete. A new location-based access control feature for Adobe Identity in the Adobe Admin Console is coming soon.

  * _Single Sign-On (SSO) Deprecation_: Support for [Marketo Identity SSO](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"} ended on July 30, 2025. The feature will remain operational until the transition to Adobe Identity is complete. Single Sign-On for Adobe Identity in the Adobe Admin Console must be configured separately. For setup steps, see [Set up identity and Single Sign-On](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

* **Deprecation of _Forward to a Friend_ Feature**: On September 29, 2025, the _Forward to a Friend_ feature in Marketo Engage 2.0 emails (the legacy email editor) was completely deprecated for all subscriptions. This affected the 'Forward to a Friend' token and 'Forward to a Friend' links in emails that have already been or were scheduled to be sent using the token. [Learn more](https://nation.marketo.com/t5/product-blogs/deprecation-of-forward-to-a-friend/ba-p/358045#M2889){target="_blank"}

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after January 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on January 31, 2026. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.
