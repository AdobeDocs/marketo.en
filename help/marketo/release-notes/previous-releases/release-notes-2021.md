---
title: 2021
description: 2021 - Marketo Docs - Product Documentation
feature: Release Information
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
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
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
    internal-label: Smart Lists
  - id: d5c7388a-594e-4d15-9b39-98d6ce479e8b
    internal-label: Microsoft Dynamics
  - id: ea4e3ff5-e7b9-4b4c-a5a0-dc27cc3f4275
    internal-label: Custom objects
  - id: efc9a24a-a6a4-449d-a3e6-44f6c74dfd46
    internal-label: Adobe Identity Management
  - id: fc9b09fe-b844-4544-887b-e420c3b82065
    internal-label: Webhooks
  - id: fd4ca7b1-bd80-47f4-ad1a-846912e45cc5
    internal-label: Target Account Management
  - id: ffdd6159-0e10-4a57-8021-94e93bab8183
    internal-label: Event programs
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
    internal-label: Metadata
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: beb7a3c1-66ab-4786-b879-7621375b3c40
    internal-label: Email marketing
  - id: cc72dcf1-72e1-48cc-b434-e7c27d62d67c
    internal-label: Accessibility
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: ebde5b41-29c9-4f5e-9ef6-1197e85409e3
    internal-label: Data management
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
---
# 2021

## January 2021 {#january}

The following features are included in the Jan '21 release. Check your Marketo edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![(star)](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will be released on **January 15, 2021**.

## Next-Generation User Experience {#next-generation-user-experience}

* Support for Workspaces: The Marketo Engage next-generation user experience brings together the look and feel of Adobe Experience Cloud with productivity innovations to help marketing practitioners work faster and smarter. In the latest release, we're adding full support for workspaces and partitions, including the ability to share folders across workspaces. The right-hand canvas will offer a toggle switch to allow you to seamlessly transition between old and new experiences per feature without losing context. [Learn more](https://nation.marketo.com/t5/The-modern-ux/modern-ux-FAQ/ba-p/307124) from the next-generation experience FAQ on Marketing Nation.

## Multi-Channel Personalization {#multi-channel-personalization}

* **[Adobe Experience Cloud Audience Sync Phase 3](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**: The existing Adobe Experience Cloud (AEC) Audience Sync capability now supports continuous, bi-directional B2B audience sync from Marketo Engage to other AEC applications, including Adobe Experience Platform (AEP) offerings like Real-time Customer Data Platform and Adobe Experience Platform Activation.  As leads are added and removed to your audience segments, Marketo Engage will automatically sync the updated audience across your connected AEC apps. Use it to take advantage of Adobe's multi-channel orchestration, re-targeting, audience suppression, personalization and reporting use cases across your AEC tech stack.
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
* **Metadata Export**: Enhanced to support opportunity object attributes, named accounts, program member's standard and custom fields.

## Administration {#administration}

* **Updated My Account Page**: Review essential subscription information on the My Account page. Users with any level of access can view the subscription name, data center identifier, and [!DNL Munchkin] ID.

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

## [!DNL Sales Insight] {#sales-insight}

![(star)](assets/yellow-star.png)

* **[Enhanced Test Email Workflows ([!DNL Salesforce] CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/actions-in-the-msi-panel/send-marketo-email/send-a-test-email.md)**: Increase your sales team's efficiency with enhanced [!DNL Sales Insight] test email workflows. Sellers can send test email to chosen email addresses before sending bulk emails to up to 200 recipients.
* **[Insights into Email Status ([!DNL Salesforce] CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/email-tab.md)**: Users see a warning message when they are trying to send an email to an invalid email ID or an unsubscribed email address prior to sending an email.  Emails delivery statuses can be reviewed in the email tab of [!DNL Sales Insight].
* **Send Bulk Emails from [Account](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#account-layout) and [Opportunity](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#opportunity-layout) Panels ([!DNL Salesforce] CRM)**: Improve the efficiency of seller's workflow and engage with an entire account or opportunity contact list by using new bulk action features. Send emails or add contacts to Marketo Engage campaigns by using the new drop-down option in the account or opportunity tabs instead of working with individual contacts. Add account contacts to a watchlist to be notified when leads become hot.
* **[[!DNL Sales Insight] for Non-Native [!DNL Salesforce] CRM Integrations](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)**: GA subscriptions with custom Salesforce CRM integrations can install the [!DNL Sales Insight] package and help sales teams prioritize and interact with the most promising leads and opportunities.
* **[Best Bets Enhancements](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/marketo-tab/best-bets.md)**: Quickly contact hot leads from the Best Bets tab by emailing or adding them to a Marketo Engage Campaign. View a lead in Marketo Engage or add it to your watchlist. Bulk actions and sorting options on the [!UICONTROL Best Bets] tab save time and improve the sales team's efficiency.

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
* In 2021, Marketo Engage will be making changes to the URL structure for landing pages, forms, and images and files assets. For existing Marketo Engage subscriptions, we will begin the gradual rollout on April 1, 2021. More details on the rollout timeline will be released in March 2021. For details on how each affected asset type will change, refer to [our post in Marketing Nation](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-Design-Studio-URLs/ta-p/306632).

**_Product Release Webinar_**

Want to learn more about these features and enhancements? Be sure to [register now](https://engage.marketo.com/January_21_Release_Webinar_Registration.html) to join us on January 21 at 1:00 PM PT / 4:00 PM ET for a live webinar with our product team to take a deeper dive into these innovations.

## May 2021 {#may}

The following features are included in the May '21 release. Check your Marketo edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will be released on **May 7, 2021**.

## Account-Based Experiences {#Account-based-eaperiences}

* **Account Smart Lists (general availability)** ![](assets/yellow-star.png): Dynamically identify and qualify accounts with desired account and person attributes to target in cross-channel marketing campaigns and send timely alerts to Sales to close deals faster. This new capability allows for robust automation of account-based marketing strategies. Account Smart Lists are available for customers with Target Account Management that are on the next-generation user experience.

## Next-Generation User Experience {#next-generation-user-experience}

With global search preview, marketers can quickly see where a shared asset exists in their instance. Browser tabs display the location to improve navigation in [!UICONTROL Marketing Activities] or [!UICONTROL Design Studio]. Additional tree and global search filters help refine your search criteria. Drag-and-drop functionality within the tree has been reinstated, allowing you to move folders and assets quickly and efficiently within the main app areas. Newly updated icons (that meet Adobe's accessibility standards) and status badges allow marketers to distinguish between folders and assets quickly and easily in the tree and identify the status of programs and assets.

## Experience Automation {#experience-automation}

* **Execute Campaign Flow Steps**: Streamline campaign creation workflows and improve campaign performance with a new flow step for Smart Campaigns. Create and save centralized, template campaigns for repetitive tasks in your workspace, such as country code normalization, to be called and run from any Smart Campaign via the new "Execute Campaign" flow step. Linked campaigns will run in the designated order and ensure task completion before advancing to the next flow step. Quickly edit the flow in just one centralized campaign to update every Smart Campaign that's using it to streamline data management, lead scoring and routing workflows.

## Cross-Channel Orchestration {#cross-channel-orchestration}

* **Sensitive Data Fields in Forms**: Protect customer's personally identifiable information (PII) from showing in Adobe Marketo Engage forms by defining data fields as sensitive and restricting form prefill for those fields. Whenever a visitor views a form on the landing page, the fields defined as sensitive will not show any prefilled data.

* **Block Spam Form Submissions**: Protect your Adobe Marketo Engage database from junk data that can cause invalid alerts to sales, trigger campaign backlogs, and create unwanted activities. The new validation mechanism rejects invalid form submissions and stops bot attacks. Your data is cleaner, and your marketing campaigns run as intended, minimizing the risk of sending unqualified leads to sales.

* **Email Program Approval Warning**: Prevent sending erroneous emails when the new edits were made to a previously approved program.  The warning acts as a guardrail when a marketer applies changes to an email that is already approved, but then forgets to approve the latest changes, and sends the email out to a large audience with no content, bad content, or old content.

* **Filter-out Email Bots Activity**: Prevent unintended sales alerts and inaccurate email reporting through the new email bot activity filtering capability. Identify and filter out opens and clicks that can be associated with email bots inspecting links leading to false triggers and sales alerts, or incorrect reporting.

## API Enhancements {#api-enhancements}

Several critical updates to Bulk and Lead APIs, including the ability to export custom object data in bulk, associate company with lead in bulk, ability to filter bulk activity extract based on a primary attribute, and the ability to create and update program membership.

* **Nest Event Programs**: In Adobe Marketo Engage you can create, clone, or move event programs under other program types. This functionality is now permitted in assets API.

* **Enhanced Delete Program API**: Allows integrated applications to delete programs containing additional types of assets, without requiring users to do so manually from Adobe Marketo Engage.

* **Program Membership**: Marketers can query all program member records for a select program given different criteria, such as program member status. Share this information with an external application, business intelligence tool, or Adobe Experience Cloud to and improve segmentation and create more targeted engagement.

* **Bulk Custom Object Extract**: Bulk data export complements the import capabilities that data analysts are already enjoying in Adobe Marketo Engage. Now they can extract data stored in the 1st level Adobe Marketo Engage Custom Objects in bulk, load this data into another application, data warehouse, or BI (Business Intelligence) tool to gain better insights into the data in the Adobe Marketo Engage instance.  Custom object bulk data movement is bi-directional and can be scheduled at a convenient time.

* **Custom Fields Metadata API**: Save time by automating the creation of custom fields while setting up your Adobe Marketo Engage integrations with a 3rd party application. This automation especially benefits customers with multiple Adobe Marketo Engage instances who are now able to streamline custom fields creation that used to require manual work in each instance. Streamline custom fields creation and save time on this resource consuming activity.

* **Bulk Activity Extract API**: Gain control over the amount and type of data when performing bulk extractions. Filter out unnecessary data points and control the number of API calls necessary to extract activity data in bulk.  For example, select open emails, visit a webpage, or change in lead score and leave behind other changes in value you don't want to analyze. Streamline the process to decrease the number of API calls and data cleanup.

* **Lead API**: Identify leads in Adobe Marketo Engage that have Adobe ECID (Experience Cloud ID) associated with them.  Adobe Marketo Engage customers can create a list of leads from a select campaign and use the ECIDs (Experience Cloud ID) to create reporting in Adobe Analytics for that specific list. Integration between Adobe Marketo Engage and Adobe Experience Cloud opens up unlimited opportunities for segmentation, targeting and reporting.

* **Bulk Lead Import API**: Control bulk lead import and resources it takes. This enhancement creates association between lead and company during bulk lead import process. Increase efficiency and of working with data and decrease usage if API calls.

* **Web API based Integration for the [!DNL Microsoft Dynamics Online] Customers**: [!DNL MS Dynamics] Web API was introduced with version 8.0 REST protocol and implements OData (Open Data Protocol) v4. OData is an OASIS (Organization for the Advancement of Structured Information Standards) standard for building and consuming RESTful services over rich data. Adobe Marketo Engage customers that require integration with [!DNL Microsoft Dynamics] using this method are currently being migrated to Web API-based connection from SOAP (Simple Object Access Protocol).

## Marketing Data Environment {#marketing-data-environment}

* **XLSX Export**: We upgraded export capabilities throughout the product to support XLSX in place of XLS. This means that anywhere in the product where XLS export is currently supported, this option will be replaced with an option to export to XLSX instead. This change will affect the file names for all Excel exports of reports and other data from Adobe Marketo Engage.

* **Search by Lead ID**: Quickly access lead record searching by Adobe Marketo Engage lead ID within the lead database or static list. In the Quick Find window simply type `[id]` with the corresponding number, then the lead information will be displayed. Users can quickly review lead, company, or opportunity details.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Integration with [!DNL LinkedIn] Lead Gen Forms (Beta)**: Gain deep visibility into your [!DNL LinkedIn] channel spend and ROI with Bizible premium attribution solution. Through the latest integration with [!DNL LinkedIn]'s Lead Gen Forms, Bizible gains insight into forms that have been submitted within the [!DNL LinkedIn] platform. These form fills are matched against leads from your CRM (Customer Relationship Management) or Adobe Marketo Engage instance so that they're eligible for attribution and can be tracked against your other marketing engagements.

## Announcements {#announcements}

* **Marketo Product Docs Switching Platforms**: We're excited to announce that the Marketo Product Docs has joined the Adobe Experience League as of Friday, May 7. You'll still be able to use the URL: docs.marketo.com, and if you have any existing articles bookmarked, you'll be redirected. All product docs are available on the new platform, with enhancements planned for later this year.

* **Streamlined User Administration and Single Sign-on Powered by Adobe Identity System**: Beginning July 2021, the new Adobe Marketo Engage customers will be onboarded using Adobe user credentials. Migration of current customers to the integrated identity system will not occur until mid-2022 and no customer action is required until further notice. Single sign-on enables IT/Security admins to manage multiple Adobe Marketo Engage product instances along with other Experience Cloud solutions as well as configure SSO (Shared Services Organization) through a common console. Admins can conveniently manage user groups and user entitlements through a common Admin Console.

**_Product Release Webinar_**

[May 2021 Marketo Engage Release Webinar](https://engage.marketo.com/May_21_Release_webinar_RegistrationPage.html)

## August 2021 {#august}

The following features are included in the August '21 release. Check your Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![](assets/yellow-star.png)) are paid add-ons. Please contact your Adobe Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will be released on **August 20, 2021**.

## Experience Automation {#experience-automation}

* **Marketo Engage User Authentication via Adobe Identity**: Soon, new Marketo Engage users with Enterprise packages will be onboarded using Adobe ID user credentials. Migration of current users to the integrated identity system will not occur until mid-2022 and no action is required until further notice. Adobe identity user authentication allows IT/Security admins to manage multiple Marketo Engage product instances along with other Experience Cloud solutions, as well as configuring SSO through a common console. Admins can conveniently manage user groups and user entitlements in one place.

* **Executable Campaign Nesting**: Executable campaigns may now also call other executable campaigns allowing you to nest them up to three levels deep. This enables further consolidation of common operational flows and improves Smart Campaign management.

* **Single Flow Action in Person Detail Page** (Available by September 9): Execute flow actions like sending email, change person owner, or any other smart campaign action on individual people from the person detail page using the flow action menu without switching to the database grid view.

* **[Custom Activities Export](/help/marketo/product-docs/administration/marketo-custom-activities/custom-activity-metadata-export.md)**: Metadata export now supports all objects and respective metadata which can be used to share, analyze and design your subscription data model.

## API Enhancements {#api-enhancements}

* **Submit Form API**: When an email address is duplicated in two or more Lead records, we update "last updated" record instead of skipping altogether. Provides parity with Forms 2.0 API.

* **Email API**: Retrieve champion or challenger email assets. Retrieve email assets using date range filter.

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

## [!DNL Sales Insight] {#sales-insight}

![(star)](assets/yellow-star.png)

* **Enhanced visibility into Lead, Contact, Account & Opportunity Activities for Salesforce CRM Users**: Engagement with prospects during long sales cycles is more informed due to an increased number of engagement records in [!DNL Sales Insight]. Interesting moments, web activity, email, and score tabs show up to 400 activities across Lead, Contact, Account, and Opportunity objects.

## [!DNL Sales Connect] {#sales-connect}

![(star)](assets/yellow-star.png)

* **Email Connection Throttling (Beta)**: Improve email deliverability and scale personalized sales communication with the email connection throttling for Sales Connect. This new technology automatically manages email send timing to create seamless experiences for [!DNL Exchange] and Gmail users. Decrease or eliminate the usage of third-party bulk email send applications and send all your emails from [!DNL Sales Connect] with confidence.

>[!NOTE]
>
>Email throttling is available in Beta now. [Learn more](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

* **Enhanced Sales Activity Insights**: Capture and activate personalized engagement based on your sales team's prior activities. New attributes such as Sales Call Recording Link, Sales Campaign Name, and Sales Email Subject can be used in Marketo Engage smart lists.  These activities can be exported and reported through the Marketo Engage REST API or Bulk Export and are available on filters and triggers as additional constraints for smart lists.

## [!DNL Bizible] {#bizible}

![](assets/yellow-star.png)

* **[!DNL Bizible] [!DNL LinkedIn] Lead Gen Forms Integration**: Marketers can now perform revenue attribution on conversions that occur when [!DNL LinkedIn] captures form fills through their Lead Gen Forms ad units. These insights can then be used to optimize form performance and paid media investments. [!DNL LinkedIn] Lead Gen Forms are one of [!DNL LinkedIn]'s fastest-growing paid media offerings and this new capability is included with our existing [!DNL LinkedIn] Ads integration with [!DNL Bizible].

* **Improved Velocity Dashboard**: We have added a new velocity metric and dashboard filter for deeper insights. This dashboard is used by marketers to understand stage-by-stage lead and opportunity velocity and the efficiency of different forms of marketing and sales engagement.

* **New Cohort Waterfall Journey Dashboard**: This will enable marketers to view the progression of a selected cohort through a classic "demand waterfall" set of stages, providing a quick understanding of conversion rates and implied stage conversion causality on a stage-by-stage basis.

## [!DNL Bizible] Integration with Adobe Experience Cloud {#bizible-integration-with-adobe-experience-cloud}

This section includes new features for Bizible users that have completed their Adobe Identity Management System (IMS) migration. If you have been migrated, you'll see your new Adobe ID in [!DNL Bizible] Settings under the Adobe ID tab. All accounts should be migrated by the end of 2021.

* **[!DNL Bizible] Integration with Adobe Privacy Service** (available September 2021): [!DNL Bizible]'s integration with the Adobe Privacy Service centralizes compliance with critical data privacy regulations (such as GDPR) across Adobe Experience Cloud applications. You can now take advantage of this service and manage all privacy requests centrally so that change requests coming into [!DNL Bizible] and other Adobe products are reflected across applications.

* **[!DNL Bizible] on Adobe Unified Shell**: [!DNL Bizible]'s adoption of Adobe Unified Shell gives users new capabilities that will appear in the [!DNL Bizible] application header bar and include better access to support resources and application switching. Adobe Unified Shell helps create a consistent experience between [!DNL Bizible] and other Adobe Experience Cloud applications.

* **[!DNL Bizible] Domain Ownership and Self-Management**: [!DNL Bizible] users can leverage Adobe Admin Console to manage the domains they want [!DNL Bizible] to track. This brings self-service to a previously manual process and provides a consistent experience in how domain ownership and tracking are managed across Adobe Experience Cloud applications.

## Announcements {#announcements}

* **Update to Subscription Universal ID Settings**: To support the upcoming Marketo Engage and Adobe Identity integration for existing users, all Marketo Engage subscriptions will be unified in the enablement of Universal ID support.

**_Product Release Webinar_**

[August 2021 Marketo Engage Release Webinar](https://engage.marketo.com/August21_Release_Webinar.html)

## October 2021 {#october}

The following features are included in the October '21 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will start to be released on **October 22, 2021**, with a phased rollout of every feature over the following week (unless specified otherwise).

## AI-Driven Innovation {#ai-driven-innovation}

* **Predictive Audiences Enhancements**: You now have more visibility into top behaviors that are influencing AI predictions for the AI-powered predictive models used in event and email programs. You can review the campaign member behaviors that result in higher event registrations and attendance, as well as what leads to unsubscribes. AI-powered lookalike models can now be used in all program types in Marketo Engage.

## Next-generation Experience {#next-gen-experience}

* **Choose Your Own Experience**: Easily switch to your preferred experience with the new toggle while working on Marketo Engage form details or landing page list view without losing context, asset changes, or preferences. Additionally, the new landing page list view enhances your experience with new filters and the ability to perform mass actions.

* **Search Efficiently**: Accessibility improvements to global search include updated keyboard navigation and label descriptions, a new scroll feature for results, and more visible applied filters.

* **Monitor Tasks**: Monitor the status of tasks running in the background of the new experience via the new task notification tray in the global navigation bar. The tray captures notifications for tasks initiated from the new experience view of form details and landing page list, including changing status on landing pages and general mass actions using the new experience.

## Experience Automation {#experience-automation}

* **Submit Form API Program Member Custom Field Support**: The Submit Form API endpoint has been upgraded to support Program Member Custom Fields, allowing custom form integrations to collect program-specific data.

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

* **Native Adobe Experience Platform Connector for Sharing Audiences to Marketo Engage**: Enable multi-channel campaign orchestration in Marketo Engage for audience segments created in Adobe Experience Platform via a native destination connector. The connector uses email addresses or ECID to match Adobe Experience Platform profiles to Marketo Engage person records resulting in segment sharing between applications. Marketo Engage static lists are automatically populated which enables marketers to reach target audiences with highly personalized messaging or initiate workflows. Activate people audiences leveraging their account and opportunity context, and a more complete real-time unified profile in Experience Platform.

* **Adobe Experience Platform Marketo Data Source Connector**: Users of both Adobe Experience Platform and Marketo Engage will be able to utilize the Marketo Source Connector in bringing data from Marketo to AEP. You'll be able to stream data (and its changes) from Marketo within AEP to keep data consistent between the two products. The Marketo Connector can be seen via the Sources catalog, listed under "Adobe Applications."

## [!DNL Sales Insight] {#sales-insight}

![(star)](assets/yellow-star.png)

**[!DNL Sales Insight] for [!DNL Microsoft Dynamics 365] Sales**

* **[!UICONTROL Best Bets] Enhancements**: The [!UICONTROL Best Bets] tab in [!DNL Sales Insight] provides sales with a real-time view of the hottest contacts and leads prioritized by quality and urgency. We added the ability for sales reps to take actions, such as: review a person's score, send an email, or add prospects to designated Marketo Engage campaigns directly from the [!DNL Best Bets] page, increasing efficiency and speeding up response time.

* **New Email, Web Activity, Anonymous Web Activity Dashboards**: We added the new sales dashboards to inform sellers about their leads and contacts' most recent email and web activities. With new filtering capability, the dashboards now provide insight into email opens, clicks, and web page visits for the complete list of accounts or a specific account. Marketo Engage tracks all web activity and provides sales with critical information, turning anonymous traffic into leads. Sellers are enabled to personalize engagement and convert leads to sales faster because they're better informed about lead behaviors and are acting based on the relevance of all the touchpoints.

**[!DNL Sales Insight] for [!DNL Salesforce]**

* **Account and Opportunity-level [!UICONTROL Best Bets]**: [!DNL Sales Insight] now offers the ability for sales reps to review Best Bets for all contacts on the account or opportunity they own, even when the contact is assigned to a different team member. This gives account and opportunity owners complete visibility into the activities of relevant contacts and helps them act based on a more holistic view of the account or opportunity.

## [!DNL Sales Connect] {#sales-connect}

![(star)](assets/yellow-star.png)

* **Enhanced Sales Activity Insights**: A new email reply tracking activity, Sales Email Replied, tracks recipients' interactions with an email which is automatically synchronized with Marketo Engage. Additionally, the Source attribute has been updated from "Tout" to "Sales App." This activity can be exported and reported through the Marketo Engage REST API or Bulk Export and is available on filters and triggers as additional constraints for smart lists, expanding personalization options in Smart Campaigns.

* **Streamlined User Experience**: This update introduces new fonts, colors, buttons, and modals for [!DNL Sales Connect] that are based on the Adobe Spectrum design system. With these updates, we are delivering a more efficient experience, where sellers can focus on what's needed, when it is needed.

## [!DNL Bizible] {#bizible}

![](assets/yellow-star.png)

* **[!DNL Bizible] Integration with Adobe Privacy Service (GA)**: [!DNL Bizible] integration with the Adobe Privacy Service centralizes compliance with critical data privacy regulations, such as GDPR (General Data Privacy Regulation) or CCPA (California Consumer Privacy Act) across Adobe Experience Cloud applications. You can now take advantage of this service and manage all privacy requests centrally through Adobe's Privacy Service so that change requests coming into [!DNL Bizible], and other Adobe products, are reflected across applications.

## Announcements {#announcements}

* **Associate Lead Deprecation/Munchkin Beta 161 Update**: On September 7th, 2021, version 161 of Munchkin began rolling out to 10% of subscriptions with Munchkin Beta enabled, followed by 50% on September 16th, and 100% on September 30th. This change affects Marketo Engage landing pages and the version of the file munchkin-beta.js served to external landing pages which are loaded from subscriptions that the recent version has been rolled out to. This version fully deprecates the [!DNL Munchkin] Associate Lead method, which is a feature that allows the submission of a person's data to a Marketo Engage subscription and associated web browsing history with a known person record. Associate Lead is being removed in favor of more modern and secure alternatives, like the Forms JS API, the Form Submit API, and the Associate Lead REST API. [Learn more about this deprecation here](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/).

* **[!DNL Sales Connect] Update**: A recent UI change in [!DNL Sales Connect] has caused some modals in [!DNL Salesforce] to get cut off. To fix this, please perform a [package update](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/sales-connect-customizations-for-crm.md).

**_Product Release Webinar_**

[October 2021 Marketo Engage Release Webinar](https://engage.marketo.com/October_Release_Webinar_On-Demand.html)

