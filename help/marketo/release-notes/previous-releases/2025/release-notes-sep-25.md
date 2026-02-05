---
description: Release Notes - September 2025 - Marketo Docs - Product Documentation
title: Release Notes - September 2025
feature: Release Information
exl-id: fd40d9df-67ba-4fc4-891f-81aebfd07b0a
---
# Release Notes: September 2025 {#release-notes-sep-25}

Below you'll find all the features included in the September '25 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **September 19, 2025**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>On-Demand Webinar Activity Retention</strong>: Interactive Webinars users now have On-demand Webinar Dashboard data available for more than 30 days (previously it was only up to 30 days from the day of the webinar).</td>
   <td>Released</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/event-workflows#manual-sync">Manual sync</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - AI Assistant Permissions</strong>: Marketo Admins can provide specific users with access to GenAI features.</td>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/ai-assistant.md#set-up-permissions">Set up permissions</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Dark Mode</strong>: You can now utilize Dark Mode, which allows supporting email clients and apps to display emails with darker backgrounds and lighter colors for text, buttons, and other UI elements.</td>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/dark-mode.md">Dark mode</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Content Collaboration Workflow</strong>: You can now comment on and collaborate with fellow Marketo users within an email asset. Tag team members (Marketo users who have the appropriate asset permissions) and they will receive an email or pulse notification.</td>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/email-collaboration.md">Email collaboration</a></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <td><strong>Email Designer - Redirect Fixes</strong>: Some users were experiencing redirect issues with URLs for emails created using the new Designer (e.g., directly pasting the URLs or bookmarking email assets did not always work). This issue has been resolved. Additionally, links to email assets from <b>Email Templates</b> > <b>Details</b> > <b>Used By</b> will redirect to the corresponding email asset.</td>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **REST API Double Slash Deprecation**: On September 16, 2025, Adobe transitioned to a more modern hosting infrastructure for REST API URLs that leverages newer technology, adding security and scalability. If your subscription has been using APIs with a double forward slash (//) in the URL, please read [this Nation post](https://nation.marketo.com/t5/product-blogs/rest-api-double-slash-deprecation/ba-p/358616){target="_blank"} for next steps.

* **Switching Back to Velocity Scripting in the new Email Designer**: Adobe Marketo Engage released a feature called _Conditional Content_ for the new Email Designer this past June. The feature was powered by Handlebar scripting instead of Velocity scripting, in an effort to provide a little more flexibility in your dynamic content. But when we discovered it was causing some tokens to be resolved incorrectly, we decided to temporarily disable it. [Learn More](https://nation.marketo.com/t5/product-blogs/update-on-email-scripting-in-the-new-email-designer/ba-p/358179){target="_blank"}

* **Marketo Engage Identity End of Life**: In August 2025, Adobe began phasing out support for Marketo Engage Identity (logging in via `login.marketo.com`). To prevent interrupted access to Marketo Engage, you must transition to [Adobe Identity](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"} no later than September 30, 2025.

  * _IP Restrictions Deprecation_: Support for [Restricting Marketo Logins Based on IP](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"} ended on July 30, 2025. The feature will remain operational until the transition to Adobe Identity is complete. A new location-based access control feature for Adobe Identity in the Adobe Admin Console is coming soon.

  * _Single Sign-On (SSO) Deprecation_: Support for [Marketo Identity SSO](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"} ended on July 30, 2025. The feature will remain operational until the transition to Adobe Identity is complete. Single Sign-On for Adobe Identity in the Adobe Admin Console must be configured separately. For setup steps, see [Set up identity and Single Sign-On](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

* **Deprecation of _Forward to a Friend_ Feature**: On September 29, 2025, the _Forward to a Friend_ feature in Marketo Engage 2.0 emails (the legacy email editor) will be completely deprecated for all subscriptions. This affects the 'Forward to a Friend' token and 'Forward to a Friend' links in emails that have already been or will be sent using the token. [Learn more](https://nation.marketo.com/t5/product-blogs/deprecation-of-forward-to-a-friend/ba-p/358045#M2889){target="_blank"}

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after March 31, 2026. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on March 31, 2026. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.
