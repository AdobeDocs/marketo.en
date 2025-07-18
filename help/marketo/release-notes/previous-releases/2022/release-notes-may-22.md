---
description: Release Notes - May 2022 - Marketo Docs - Product Documentation
title: Release Notes - May 2022
exl-id: f591ab95-5ad8-45fa-8c4e-8e42b5d1359a
---
# Release Notes: May 2022 {#release-notes-may-22}

Below you'll find all the features included in the May '22 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will start to be released on **May 6, 2022**, with a phased rollout of remaining features over the subsequent weeks (unless specified otherwise).

## Native CRM Integration {#native-crm-integration}

**[Native Veeva CRM Integration](/help/marketo/product-docs/crm-sync/veeva-crm-sync/understanding-the-veeva-crm-sync.md){target="_blank"} (limited availability)**: Improve engagement with healthcare professionals by syncing activity between Veeva CRM and Marketo Engage via native integration. This integration allows marketers to create more personalized and seamless cross-channel experiences for healthcare professionals. Please contact your Customer Success Manager if you're interested in participating.

## Cross-Channel Orchestration {#cross-channel-orchestration}

**Chatbot Events for [!DNL Dynamic Chat]**: Leverage more detailed behavior data for web visitors such as time on page, time on site, and page scroll percentage to define when a chat dialogue should be shown.  

**PDF Embed for [!DNL Dynamic Chat]**: Increase engagement and share meaningful content by embedding PDFs into chat dialogues and measure content performance through engagement activity tracking.

**Extended Language Support for [!DNL Dynamic Chat]**: The [!DNL Dynamic Chat] user interface will now also be available in French, German, Japanese, Portuguese, and Spanish. Chat dialogues can also be configured in these languages.  

**Exclude URLs for [!DNL Dynamic Chat]**: Control which of your webpages [!DNL Dynamic Chat] appears on with the ability to exclude specific URLs from targeting criteria.

**[Email Bot Activity Filtering Enhancements](/help/marketo/product-docs/administration/email-setup/filtering-email-bot-activity.md){target="_blank"}**: Continue to protect the health of your database with the ability to identify bot behavior based on hidden link User Agents or IPs and proximity patterns, in addition to the existing IAB list match identification. View bot activity stats that allow you to understand the number of bot activities identified for each type.

**[STS Header for Email Tracking Links](/help/marketo/product-docs/administration/settings/email-tracking-link-headers.md){target="_blank"}**: Meet security best practices with the ability to apply Secure Transport Security headers to ensure traffic to tracked links is always secure.

## Next-Generation Experience {#modern-ux}

**Toggle Switch Defaulted to the Next-Generation Experience**: The toggle switch will be default to the new experience in all screens where it's available, making it easier for users to discover the updated designs and usability enhancements.

**Updated Screen in the Next-Generation Experience**:

We’re delivering Email Template Details View within [!UICONTROL Design Studio] in the next-generation experience, offering an updated design and usability enhancements accessible via toggle switch.

## Experience Automation {#experience-automation}

**Self-Service Flow Steps (continued beta)**: Expand connectivity between Marketo Engage and the rest of your stack with the ability to author customized flow steps for use in Smart Campaigns. Both Marketo Engage users and partners can leverage this functionality to allow for the usage of external web services in trigger, batch, and executable campaigns (in contrast to webhooks which can only be used in trigger campaigns).

## API Enhancements {#api-enhancements}

* **Expanded API Access for CRM-Enabled Subscriptions**: We are expanding API access for subscriptions that have a CRM sync enabled to allow users to retrieve Companies, Opportunities, and Sales Persons from Marketo Engage.
* **Support for “Hidden” Datatypes in Forms**: Provides the ability to manage hidden form fields via API.
* **Support Multiple Comparison Values for isNot Form via Rules**: Manage visibility of form fields based on whether the value of another field is not one of the values in a given list.
* **Allow setting of Display and Submitted Values in Select Lists Separately**: Set the display value and submitted value in a field separately. For example, show the name of a hotel, but submit an Internal ID to the backend.
* **Allow Setting of Disable Open Tracking on Create or Update Email**: Create an email with open tracking disabled.  

## Announcements {#announcements}

**Email Verification and Uniqueness**: Beginning in April, rollout of Email Verification will commence. At that point, Marketo Engage user email addresses will require verification and uniqueness (this does not apply to API-only users). Directory service authenticated users will automatically have their emails verified when their subscription is enabled with Email Verification.

Email Verification for subscriptions using the “[!UICONTROL Login in Invite User Dialog]” feature or that have a single email associated with multiple users will coincide with the May release. Subscriptions that have a single email associated with multiple users will be enabled with Email Verification and will require those users to resolve the conflict and use a unique email per user. When the ‘Login in Invite User Dialog’ feature is enabled, users invited via this feature will need to have a unique email address. For API-only users invited via this feature, the email address does not need to be unique.

**Archive Folder Behavior Change**: With this release, the ability to create new assets in Archive folders will no longer be available from the tree context menus. Menu options for creating new assets will be hidden for all assets. [Learn more here](https://nation.marketo.com/t5/product-discussions/archive-folder-change-in-may-2022-release/m-p/324369#M183235){target="_blank"}.

**_Product Release Webinar_**

[March and May 2022 Marketo Engage Release Webinar](https://engage.marketo.com/2022_March_May_Release_Webinar_DemandPage.html){target="_blank"}
