---
unique-page-id: 17727823
description: Release Notes -Winter '19 - Marketo Docs - Product Documentation
title: Release Notes -Winter '19
exl-id: 0cb3b3a1-472e-41d4-84f4-47f06e65017c
---
# Release Notes: Winter '19 {#release-notes-winter}

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

## Core Platform Enhancements {#core-platform-enhancements}

**[Email CC for Marketo Emails](/help/marketo/product-docs/email-marketing/general/email-cc.md)**

Include up to five CC addresses per recipient on emails sent through Marketo.

**API**

* **Multi-Branding Domain Support for Asset API:** Approving and cloning assets produce the same results within the API and UI.
* **Email CC Support for Asset API**: Users cloning, approving, and processing emails via the API will maintain parity with the UI settings.

**[[!DNL Munchkin] v155 (Beta)](https://developers.marketo.com/javascript-api/lead-tracking/configuration/)**

* **API-Only Mode**: Users can now determine when and how to track members of their database by allowing single-page web apps to explicitly call when they want to record a webpage visit instead of relying on Marketo's automatic tracking.
* **Opt-Out Management**: Easily manage opt-outs by matching the opt-out cookie domain with the [!DNL Munchkin] tracking cookie domain.
* **Domain-Level Decider Parameter**: Two-letter domains (i.e. " [website.io](https://website.io)") will automatically track in Marketo without additional setup requirements.

## Marketo Sales Engage {#marketo-sales-engage}

* **[!DNL Salesforce] Custom Profile**: Sales Engage now supports unlimited custom profiles.

* **[!DNL Salesforce] Customization**: By removing non-critical custom activity fields, users can set up Sales Engage in the CRM platform more efficiently.
* **Email Service**: Enjoy better deliverability plus improved Reply Tracking, Scheduled Email functionality, and bulk email functionality by connecting to [!DNL Microsoft Outlook] (either through Office365 or On-Prem through the Email Connection tab).
* **New Admin Settings**: Two admin pages have been added to optimize your Sales Engage instance

   * _Team Management_ supports a seamless account set-up process by allowing admins to edit subscriptions and teams.
   * _Salesforce Admin Settings_ helps teams set up their SFDC sync faster and easier than ever before.

* **OWA Plugin for [!DNL Windows]**: With one single add-in, all [!DNL Windows Office365] clients will be supported in Sales Engage, providing the ability to use Live Feed in Outlook. The new plugin will be available in the Microsoft Store.
* **Activities Pusher**: Sync Sales Engage to the core Marketo platform to leverage real-time marketing insights.

## [!DNL Marketo Sky] {#marketo-sky}

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

## Account-Based Marketing {#account-based-marketing}

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

We’ve updated our SDK for Android to a more modern, stable and scalable framework that contains more flexibility and new engineering features. Android app developers can now directly use Google’s [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) (FCM) with this new SDK.

* [Developer instructions](https://developers.marketo.com/mobile/installation/#android_adding_fcm_to_your_application)
* [Developer FAQ](https://developers.marketo.com/mobile/installation/#android_fcm_faq)

>[!NOTE]
>
>App developers **must** update to the new version before March 31, 2019. If you do not update your SDK by March 31, 2019, any new user who downloads your app after this date will not be able to receive push notifications until you update to the latest version of the SDK. The SDK update will not require your current existing mobile app users to re-download a new version of your app.

## Additional Updates {#additional-updates}

**Extensible Webinar Platform**

In addition to our product release, our partner team is working on a new framework that allows webinar providers to build and maintain their own integrations with Marketo, providing more flexibility in updating and enhancing their solutions while enabling marketers to get the most out of their chosen integrations.

We plan to roll out our new platform with providers on a case-by-case basis. For more information, see our [program details](https://www.marketo.com/why-marketo/partners/technology/) or reach out to your Marketo contact.
