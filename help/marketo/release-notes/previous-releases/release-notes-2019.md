---
title: 2019
description: 2019 - Marketo Docs - Product Documentation
feature: Release Information
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
    internal-label: Implementation
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: a1d50dda-6d94-4e16-8c30-5eb7181c4650
    internal-label: Segmentation
  - id: d5c7388a-594e-4d15-9b39-98d6ce479e8b
    internal-label: Microsoft Dynamics
  - id: de9e3aa9-f002-4fe1-897b-09ee3c55114b
    internal-label: Sales Connect
  - id: df8eb12b-4f82-491f-acbb-d74012ca5654
    internal-label: Snippets
  - id: ffdd6159-0e10-4a57-8021-94e93bab8183
    internal-label: Event programs
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
    internal-label: Metadata
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
  - id: bbbea26f-9621-49eb-9ab8-e06fb3bbce8c
    internal-label: Artificial intelligence
  - id: bce87dde-a4ab-44c9-8a18-ad66e4ddb377
    internal-label: Customer experience
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
---
# 2019

## Winter 2019 {#winter}

The following features are included in the Winter '19 release. Check your Marketo edition for feature availability.

Please click the title links to view detailed articles for each feature, if available.

>[!NOTE]
>
>[!DNL Facebook] now requires a Business Manager account in order to leverage your Custom Audience integration. Your [!DNL Facebook] LaunchPoint service *must* be associated with a Business Manager account or **your integration will no longer work after January 14, 2019**. To set up a Business Manager account, please refer to [[!DNL Facebook] Help](https://www.facebook.com/business/help/1710077379203657).

>[!NOTE]
>
>Microsoft is pushing all online customers to upgrade to the latest version of [!DNL Microsoft Dynamics]. If you are integrating your Marketo instance with [!DNL Dynamics Online], you will need to [upgrade to the latest version of the Marketo Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md) before **January 31, 2019** to ensure that your integration will continue working.

>[!NOTE]
>
>Marketo is upgrading the OAuth version for GoToWebinar from 1.0 to 2.0. Support for OAuth 1.0 will be deprecated in January 2019. If you are a GoToWebinar customer, you will need to re-authenticate your logins through LaunchPoint (in the Admin area) by **January 31, 2019** to ensure that your integration will continue working. For more details, please refer to our [Community page](https://nation.marketo.com/docs/DOC-6739-gotowebinar-authentication-change-take-action-before-1312019).

## Core Platform Enhancements

**[Email CC for Marketo Emails](/help/marketo/product-docs/email-marketing/general/email-cc.md)**

Include up to five CC addresses per recipient on emails sent through Marketo.

**API**

* **Multi-Branding Domain Support for Asset API:** Approving and cloning assets produce the same results within the API and UI.
* **Email CC Support for Asset API**: Users cloning, approving, and processing emails via the API will maintain parity with the UI settings.

**[[!DNL Munchkin] v155 (Beta)](https://developers.marketo.com/javascript-api/lead-tracking/configuration/)**

* **API-Only Mode**: Users can now determine when and how to track members of their database by allowing single-page web apps to explicitly call when they want to record a webpage visit instead of relying on Marketo's automatic tracking.
* **Opt-Out Management**: Easily manage opt-outs by matching the opt-out cookie domain with the [!DNL Munchkin] tracking cookie domain.
* **Domain-Level Decider Parameter**: Two-letter domains (i.e. " [website.io](https://website.io)") will automatically track in Marketo without additional setup requirements.

## Marketo Sales Engage

* **[!DNL Salesforce] Custom Profile**: Sales Engage now supports unlimited custom profiles.

* **[!DNL Salesforce] Customization**: By removing non-critical custom activity fields, users can set up Sales Engage in the CRM platform more efficiently.
* **Email Service**: Enjoy better deliverability plus improved Reply Tracking, Scheduled Email functionality, and bulk email functionality by connecting to [!DNL Microsoft Outlook] (either through Office365 or On-Prem through the Email Connection tab).
* **New Admin Settings**: Two admin pages have been added to optimize your Sales Engage instance

  * *Team Management* supports a seamless account set-up process by allowing admins to edit subscriptions and teams.
  * *Salesforce Admin Settings* helps teams set up their SFDC sync faster and easier than ever before.

* **OWA Plugin for [!DNL Windows]**: With one single add-in, all [!DNL Windows Office365] clients will be supported in Sales Engage, providing the ability to use Live Feed in Outlook. The new plugin will be available in the Microsoft Store.
* **Activities Pusher**: Sync Sales Engage to the core Marketo platform to leverage real-time marketing insights.

## [!DNL Marketo Sky]

>[!NOTE]
>
>[!DNL Marketo Sky] releases occur on a more frequent cadence. The following features and enhancements are expected to release during late Q4/early Q1. For more details and updates, check our [Sky documentation](https://help.marketo.com/).

* **Optional Default Experience**: Marketo users may set [!DNL Marketo Sky] as their default experience if they have been provided access by an Admin.

* **Reimagined My Marketo**: Customize your experience by adding widgets that provide critical information, notifications, and links to your most frequently visited areas.

* **Design Studio List Views & Detail Pages**: Enjoy an increased level of organization and accuracy with filterable and searchable list views of emails, landing pages, and forms. Asset Detail Pages provide key information around each asset, including which programs the asset is used by, the number of snippets being used, and more.

* **Global Search**: Marketo now offers a faster and more robust global search function across the platform. Search queries now run across all accessible workspaces and can search assets (both active and archived), labels, campaigns, and programs. Search results are provided via an overlay and each result includes its file location trail to specify where the asset lives.

* **Improved User Interface**: New icons, modals, and buttons, along with a new color palette to reflect our brand refresh and make [!DNL Marketo Sky] even more stunning and functional.

* **Email Program Usability Enhancements**: We continue to move towards parity in Email Program functionality between our classic Marketo Lead Management platform and the new [!DNL Marketo Sky] experience.
* **Event-With-Webinar Programs**: Event-With-Webinar programs are now available in [!DNL Marketo Sky] (note: only GoToWebinar will be supported in this release, with further integrations established over time).

## Account-Based Marketing

**[ABM Persona-Based Segmentation & Filtering](/help/marketo/product-docs/target-account-management/using-personas.md)**

Personalize your ABM campaigns for specific personas within named accounts. The ABM Persona feature creates a default job title based on lead segmentation and allows configuration of additional persona segmentations.

## Analytics {#analytics}

**[!DNL Bizible]**

* **Custom Calculated Fields**: Use any [!DNL Bizible] attribute to build custom fields that can be used for dashboard reporting and segmentation.

* **SOC II Type II Certification**: New security and privacy certification builds on Type I accreditation from earlier this year.

## [!DNL Web Personalization] {#web-personalization}

**[Add Subdomains in Account Settings](/help/marketo/product-docs/web-personalization/getting-started/workspaces-in-web-personalization.md)**

To manage domains and subdomains more efficiently, users can now add subdomains to their RTP account settings.

## Marketo Mobile Engagement (MME) {#marketo-mobile-engagement-mme}

**Updated MME Software Development Kit (SDK) for Android**

We've updated our SDK for Android to a more modern, stable and scalable framework that contains more flexibility and new engineering features. Android app developers can now directly use Google's [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) (FCM) with this new SDK.

* [Developer instructions](https://developers.marketo.com/mobile/installation/#android_adding_fcm_to_your_application)
* [Developer FAQ](https://developers.marketo.com/mobile/installation/#android_fcm_faq)

>[!NOTE]
>
>App developers **must** update to the new version before March 31, 2019. If you do not update your SDK by March 31, 2019, any new user who downloads your app after this date will not be able to receive push notifications until you update to the latest version of the SDK. The SDK update will not require your current existing mobile app users to re-download a new version of your app.

## Additional Updates {#additional-updates}

**Extensible Webinar Platform**

In addition to our product release, our partner team is working on a new framework that allows webinar providers to build and maintain their own integrations with Marketo, providing more flexibility in updating and enhancing their solutions while enabling marketers to get the most out of their chosen integrations.

We plan to roll out our new platform with providers on a case-by-case basis. For more information, see our [program details](https://www.marketo.com/why-marketo/partners/technology/) or reach out to your Marketo contact.

## Spring 2019 {#spring}

The following features are included in the Spring '19 release. Check your Marketo edition for feature availability.

Please click the title links to view detailed articles for each feature, if available.

***Quarterly Releases_**

The following features were released on March 15, 2019.

## Core Platform Enhancements

* **Waitlisted:** New program/event status for waitlisting a member when you want to [put them on hold](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md) until a vacancy opens. This applies to channels associated with Event programs in Marketo Classic, and both Event and Event with Webinar programs in [!DNL Marketo Sky]. By default, Waitlisted has the same step value as Registered.
* **[Custom Communication Limit](/help/marketo/product-docs/administration/email-setup/enable-communication-limits.md)**: Admins can now set custom daily or weekly communication limits.
* **[Smart Campaign Asset APIs](https://developers.marketo.com/rest-api/assets/smart-campaigns/)**: Enrich your analytics outside of Marketo with smart campaign record retrieval by updated date and ID.
* **HTTPS Tracking Links for Email:** For customers that have purchased "Secure Domains for Tracking Links," branded tracking links can now be displayed within your emails as HTTPS.
* **Email Deliverability Powerpack Updates**: Ability to flag and comment on specific test results, share results with stakeholders through a URL, and track changes to see the evolution of an email as stakeholders edit content.

Account-Based Marketing

**[AccountAI](/help/marketo/product-docs/target-account-management/account-profiling/account-profiling-ranking-and-tuning.md)** Now generally available. AccountAI uses artificial intelligence to reveal the accounts you should target for your ABM strategy.

<br>&nbsp;

**_Non-Quarterly Releases_**

The following features are expected to release throughout the first calendar quarter and into the beginning of the second quarter of 2019.

## [!DNL Marketo Sky]

* **Full Email Program Functionality**: Send emails, create A/B tests, and track results in a user-friendly experience.
* **Smart Campaign Functionality**: Enjoy enhanced stability in a new user interface as smart campaign functionality continues rolling out in Sky.
* **Manage Design Studio Assets**: Added ability to manage Templates, Images, Forms, Snippets, Files, Emails, and Landing Pages in bulk from Design Studio list views.
* **Deliver in Recipient Time Zone Dashboard**: Understand customer behavior with reporting for emails sent using the Deliver in Recipient Time Zone feature in Sky.

## Marketo Sales Engage

* **Enhanced Auditing**: New visibility into all people, emails, and [content](/help/marketo/product-docs/marketo-sales-connect/templates/view-template-list-as-another-user.md) in an instance with added ability to [end existing campaigns](/help/marketo/product-docs/marketo-sales-connect/campaigns/view-campaigns-list-as-another-user.md)created by other users.
* **[Unsubscribe Management](/help/marketo/product-docs/marketo-sales-connect/email/unsubscribes/marketo-unsubscribe-check.md)**: Maximize deliverability and compliance with the ability to [block email domains](/help/marketo/product-docs/marketo-sales-connect/admin/blocked-domains.md) from being contacted. Marketo will also cross-reference the lead database for unsubscribes before sending an email.

## [!DNL Bizible] by Marketo

* **[!DNL Bizible] Discover Feature Enhancements**: New dashboard segmentation capabilities enable marketers to better understand performance.
* **Multi-Currency Support**: Switch between your corporate currency and any local currency with [!DNL Bizible]'s new automatic currency conversion functionality built on CRM currency tables.
* **CRM Campaign Costs**:  Measure the spend and ROI of offline marketing activities with the ability to automatically pull cost data from the CRM campaign object.

## June 2019 {#june}

The following features are included in the June '19 release. Check your Marketo edition for feature availability.

**_Quarterly Releases_**

The following features were released on June 14, 2019.

## Marketo Core Services {#marketo-core-services}

* **Bulk Extract File Checksum**: Verify that a complete file was retrieved by comparing your file hash to the checksum string of your completed extract jobs.
* **Automated Migration from Email 1.0 to Email 2.0**: Email 2.0 is fully compatible with Email 1.0 emails and templates. Enjoy new capabilities, such as the ability to group content elements (images, text, etc.) into modules, define variables like String, Color, Image, etc. within templates, and leverage fully responsive starter templates. Also includes a visual Email Template Picker.

>[!CAUTION]
>
>As of June 18, 2019, Email 1.0 is no longer available. You can learn more about Email 2.0 and the deprecation of Email 1.0 [here](https://nation.marketo.com/docs/DOC-7038).

## Account-Based Marketing

* **[!DNL LinkedIn] Account Matching (BETA)** : A new ABM capability is now available in beta, offering you the ability to send lists of known and whitespace accounts directly from Marketo into LinkedIn. This functionality is automatically included for all Marketo ABM customers.

<br>&nbsp;

**_Releasing Throughout the Quarter_**

The following features are expected to release throughout the second calendar quarter and into the beginning of the third quarter of 2019.

## [!DNL Marketo Sky]

* **Event Caps** and **Event Goals** are generally available in [!DNL Marketo Sky] under the Premium Events add-on.

  * Event Caps: Optimize the customer experience for your events and webinars with registration caps, page redirects, and waitlisting functionality.
  * Event Goals: Set event registration and attendance goals and track progress in real time.

* **Full Navigation Links**: We've enabled navigation to all permissioned applications, such as Hootsuite, Calendar, and more.
* **Email, Landing Page, Snippet, Form, Image, and File List Views**: View, search, and take mass actions on any of your assets in Design Studio.
* **Image, File, and Snippet Details Page**: Get quick details about your assets with metadata like _created at/by_ and actions like _delete_ and _approve_.
* **Community Blog Posts Widget**: Access recent posts from the Community within My Marketo.
* **Expiring Soon Widget**: Add the "Expiring Soon" widget to your My Marketo dashboard to see which campaigns and landing pages are set to expire next.
* **More Smart List Cards**: Segment and target appropriately with additional smart list cards, including "Create Task" flow step, CRM smart list rules, and more.
* **Email Champion/Challenger Details Page**: See data like winning criteria, created at, etc. from your email champion/challenger tests.

## Marketo [!DNL Sales Connect] {#marketo-sales-connect}

* **Bulk Actions in [!DNL Salesforce] Customization**: Maximize productivity by sending emails and adding contacts to campaigns in bulk with [!DNL Salesforce] Customization.
* **Settings - [!DNL Salesforce] Page for Admin and Non-Admin**: Manage your [!DNL Sales Connect] instance with a clear view of the [!DNL Salesforce] instance connected to [!DNL Sales Connect] as well as My Email to [!DNL Salesforce] updates. Enhanced sync settings for Admins, Non-Admins, and Team Wide Sync are releasing in the coming months.
* **Settings - Integration Page**: A one-stop shop for all of your integrations, so you can get the most out of our open ecosystem.
* **Settings - Profile Page**: View and update your account details, change your password, and check the status of your instance's implementation on this new profile page.

* **System Email Templates**: Updated design, responsiveness, and internationalization capabilities.

## [!DNL Bizible] by Marketo

* **Multi-Currency Support for [!DNL Dynamics]**: [!DNL Bizible] now adapts to [!DNL Microsoft Dynamics] currency tables, so you can easily switch between corporate and local currencies. (Note: Support for SFDC was released in Q1 2019.)
* **Drift Integration**: Understand how Drift conversations impact your customer's journey. [!DNL Bizible] will also pull email addresses from conversations to either create a new lead or connect the touchpoint to an existing lead.
* **Localization**: [!DNL Bizible] is now available in all Marketo-supported languages (English, Japanese, German, Spanish, French, and Portuguese).

_**Product Release Webinar**_ Watch the recording of our June '19 Release Innovations webinar [here](https://engage.marketo.com/Marketo-June-Product-Release-2019-On-Demand.html).

## August 2019 {#august}

The following features are included in the August '19 release. Check your Marketo edition for feature availability.

**_Quarterly Releases_**

The following features were released on August 16, 2019.

## Core Marketo Engage {#core-marketo-engage}

* **Extensible Webinar Framework**: Save time with Marketo's new out-of-the-box webinar framework (introduced in the Winter '19 release notes) that seamlessly passes data from webinar providers into Marketo and vice versa. Cvent and Zoom are now available in this new framework.
* **Smart Campaign API Update**: Manage smart campaign lifecycle capabilities as we round out the CRUD (create, read, update, delete) interface.
* **Update Email Headers API Change**: The Update Email Header API no longer requires an email to have an attached template to update header fields, such as subject line.

**Account-Based Marketing** ![(star)](assets/yellow-star.png)

* **[!DNL LinkedIn] Account Matching**, previously in beta, is now generally available.
* **AccountAI** is being officially rebranded as **Account Profiling**.

<br>&nbsp;

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the third calendar quarter and into the beginning of Q4 2019.

**[!DNL Marketo Sales Connect]** ![(star)](assets/yellow-star.png)

* **People Page Layout Enhancement:** Manage your people and groups through list imports and bulk actions in the new people page layout.

>[!AVAILABILITY]
>
>Features denoted by a star ( ![(star)](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo representative to learn more.

>[!NOTE]
>
>**TLS 1.0 & 1.1 Deprecation**: To align with Adobe's world-class standard for security, we will be deprecating support for Transport Layer Security (TLS) 1.0 and 1.1 starting December 13, 2019. Systems integrating with Marketo that are not compliant with 1.2 protocol could potentially lose access to Marketo Engage services.
>
>**To maintain your Marketo Engage access, please ensure that all client systems are TLS 1.2 compliant before December 13, 2019**. More detailed information can be found [here](https://nation.marketo.com/docs/DOC-7059-tls-10-11-deprecation-faq).

**_Product Release Webinar_** [Join us](https://engage.marketo.com/August_19_Release_Webinar.html) on August 28 at 1:00PM PT / 4:00PM ET for a live webinar hosted by our product team and learn more about the features included in this release.

