---
description: Release Notes - Jan 2021 - Marketo Docs - Product Documentation
title: Release Notes - Jan 2021
exl-id: 24a5f955-ef4b-4adf-9478-2653db6f9d79
---
# Release Notes: Jan 2021 {#release-notes-jan-21}

The following features are included in the Jan '21 release. Check your Marketo edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![(star)](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will be released on **January 15, 2021**.

## Next-Generation User Experience {#next-generation-user-experience}

* Support for Workspaces: The Marketo Engage next-generation user experience brings together the look and feel of Adobe Experience Cloud with productivity innovations to help marketing practitioners work faster and smarter. In the latest release, we're adding full support for workspaces and partitions, including the ability to share folders across workspaces. The right-hand canvas will offer a toggle switch to allow you to seamlessly transition between old and new experiences per feature without losing context. [Learn more](https://nation.marketo.com/t5/The-modern-ux/modern-ux-FAQ/ba-p/307124) from the next-generation experience FAQ on Marketing Nation.

## Multi-Channel Personalization {#multi-channel-personalization}

* **[Adobe Experience Cloud Audience Sync Phase 3](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**: The existing Adobe Experience Cloud (AEC) Audience Sync capability now supports continuous, bi-directional B2B audience sync from Marketo Engage to other AEC applications, including Adobe Experience Platform (AEP) offerings like Real-time Customer Data Platform and Adobe Experience Platform Activation.  As leads are added and removed to your audience segments, Marketo Engage will automatically sync the updated audience across your connected AEC apps. Use it to take advantage of Adobe’s multi-channel orchestration, re-targeting, audience suppression, personalization and reporting use cases across your AEC tech stack.
* **[Continuous Audience Sync to Google, [!DNL Facebook], and [!DNL LinkedIn]](/help/marketo/product-docs/demand-generation/ad-network-integrations/send-a-list-to-an-ad-network.md)**: Continuously automated sync with an ad network can be enabled on a static list, updating the ad network as list membership changes without requiring user intervention.
* **[Tokens for Program Member Custom Fields](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/program-member-custom-field-tokens.md)**: We've extended program member custom field features to support the token framework. Marketers can insert program member custom fields tokens into emails, landing pages, SMS messages, push notifications, and webhooks. Use new tokens in campaign flow actions to change data values, create a task, or an interesting moment.

## Landing Pages and Forms {#landing-pages-and-forms}

* **Form API**: Pull in lead information or trigger nurture campaigns while pulling data from non-Marketo forms. Non-Marketo forms can integrate with Marketo Engage through REST API. The new API provides the ability to mimic Marketo Engage form submission with all associated functionalities.
* **Landing Pages API**: Streamline editing and translation workflows in integrated applications with the new Landing Page Preview API. Third-party vendors can now render fully personalized previews of landing pages without logging into Marketo Engage.  The Landing Page Preview API enables end-to-end editing and localization workflows in third-party integrated applications.

## Email Marketing {#email-marketing}

* **[Custom Objects Retrieval Limits Increased](/help/marketo/product-docs/administration/email-setup/change-custom-object-retrieval-limits-in-velocity-scripting.md)**: Developers of Email Velocity Scripting can quickly increase the number of custom objects to 100 through self-serve override. Marketers can increase the effectiveness of Smart Campaigns by accessing a larger number of first- and second-level custom objects.

## [!DNL Salesforce] CRM Integration {#salesforce-crm-integration}

* [[!DNL Salesforce] CRM Authentication](/help/marketo/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.md): OAuth 2.0 protocol is available for syncing operations between Marketo Engage and [!DNL Salesforce] CRM. For new subscribers, this option is enabled by default. Current subscribers can request this feature by contacting Marketo Support.
* [[!DNL Salesforce] CRM Syncing Dashboard](/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-errors.md): Admins can quickly review [!DNL Salesforce] CRM syncing status from the dashboard. Syncing performance report timespan has been increased from 2 hours to 5 days.
* **Metadata Export**: Enhanced to support opportunity object attributes, named accounts, program member’s standard and custom fields.

## Administration {#administration}

* **Updated My Account Page**: Review essential subscription information on the My Account page. Users with any level of access can view the subscription name, data center identifier, and [!DNL Munchkin] ID.

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

## [!DNL Sales Insight] {#sales-insight}

![(star)](assets/yellow-star.png)

* **[Enhanced Test Email Workflows ([!DNL Salesforce] CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/actions-in-the-msi-panel/send-marketo-email/send-a-test-email.md)**: Increase your sales team’s efficiency with enhanced [!DNL Sales Insight] test email workflows. Sellers can send test email to chosen email addresses before sending bulk emails to up to 200 recipients.
* **[Insights into Email Status ([!DNL Salesforce] CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/email-tab.md)**: Users see a warning message when they are trying to send an email to an invalid email ID or an unsubscribed email address prior to sending an email.  Emails delivery statuses can be reviewed in the email tab of [!DNL Sales Insight].
* **Send Bulk Emails from [Account](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#account-layout) and [Opportunity](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#opportunity-layout) Panels ([!DNL Salesforce] CRM)**: Improve the efficiency of seller's workflow and engage with an entire account or opportunity contact list by using new bulk action features. Send emails or add contacts to Marketo Engage campaigns by using the new drop-down option in the account or opportunity tabs instead of working with individual contacts. Add account contacts to a watchlist to be notified when leads become hot.
* **[[!DNL Sales Insight] for Non-Native [!DNL Salesforce] CRM Integrations](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)**: GA subscriptions with custom Salesforce CRM integrations can install the [!DNL Sales Insight] package and help sales teams prioritize and interact with the most promising leads and opportunities.
* **[Best Bets Enhancements](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/marketo-tab/best-bets.md)**: Quickly contact hot leads from the Best Bets tab by emailing or adding them to a Marketo Engage Campaign. View a lead in Marketo Engage or add it to your watchlist. Bulk actions and sorting options on the [!UICONTROL Best Bets] tab save time and improve the sales team’s efficiency.

## [!DNL Sales Connect] {#sales-connect}

![(star)](assets/yellow-star.png)

* **Email Connection Throttling (BETA)**: Improve your email deliverability and scale your 1:1 sales communication with Email Connection Throttling for [!DNL Sales Connect]. Our new throttling technology automatically manages email send timing to create seamless experiences for [!DNL Exchange] and Gmail users. Decrease or eliminate the usage of third-party bulk email send applications.
* **Email Connection Bounce Tracking**: Gain insight into lead quality and email template performance with the new email bounce report. [!DNL Exchange] and Gmail users may choose to receive bounce notifications that will roll up to the Live Feed, Email Folders, Template Analytics, and Campaign Analytics.
* **Profile Page Configuration**: Manage user preferences with ease in the new profile page. Change password, edit geolocation and language settings, and review integrations statuses in one place.
* **Templates Management**: Organize sales email templates into categories with a new drag-and-drop feature to ensure quick access to relevant templates and reduce search time.
* **[!DNL Sales Connect] User Experience Updates**: Customize [!DNL Sales Connect] grid layout by resizing and re-ordering columns. Your viewing preferences are automatically saved.

**_Announcements & Deprecations_**

* All users must upgrade to the latest version of Sales Insight **before January 15th, 2021**. If you have not completed the upgrade, you will be prompted to do so upon logging into the application. Follow the instructions [in this guide](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md). The updated version includes a patch for an identified security vulnerability. The patch was originally released on April 6, 2016. Note: **Versions 1.4363 or above** do not need to perform an upgrade.
* Deprecation of Form 1.0 service will go into effect in **May 2021** release. Forms 1.0 service will be fully deprecated, resulting in loss of functionality of any remaining Forms 1.0 assets still in use. Also, form submissions made through unsupported methods, such as programmatic form POSTs to the leadCapture/save and leadCapture/save2 endpoints, will be rejected. For more information and remediation, refer to [our post in Marketing Nation](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-the-Marketo-Engage-Form-Platform/ta-p/306631).
* In 2021, Marketo Engage will be making changes to the URL structure for landing pages, forms, and images and files assets. For existing Marketo Engage subscriptions, we will begin the gradual rollout on April 1, 2021. More details on the rollout timeline will be released in March 2021. For details on how each affected asset type will change, refer to [our post in Marketing Nation](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-Design-Studio-URLs/ta-p/306632).

**_Product Release Webinar_**

Want to learn more about these features and enhancements? Be sure to [register now](https://engage.marketo.com/January_21_Release_Webinar_Registration.html) to join us on January 21 at 1:00 PM PT / 4:00 PM ET for a live webinar with our product team to take a deeper dive into these innovations.
