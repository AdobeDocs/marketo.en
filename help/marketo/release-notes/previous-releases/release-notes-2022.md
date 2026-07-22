---
title: "2022"
description: 2022 - Marketo Docs - Product Documentation
feature: Release Information
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
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
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
    internal-label: Smart Lists
  - id: efc9a24a-a6a4-449d-a3e6-44f6c74dfd46
    internal-label: Adobe Identity Management
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: bce87dde-a4ab-44c9-8a18-ad66e4ddb377
    internal-label: Customer experience
  - id: c7d04a2c-412a-4c9d-9d7a-4456eaa5adeb
    internal-label: Governance
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
---
# 2022

## January 2022 {#january}

The following features are included in the January '22 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will start to be released on **January 21, 2022**, with a phased rollout of every feature over the following weeks (unless specified otherwise).

## Next-Generation Experience

* **Updated Screens in the Next-Generation Experience**: We're delivering additional, refreshed screens in the next-generation experience that offer an updated design and usability enhancements accessible via toggle switch:

  * Landing Page Asset Details in [!UICONTROL Design Studio]
  * Landing Page Asset Details in [!UICONTROL Marketing Activities]

## [!DNL Microsoft Dynamics] Integration {#microsoft-dynamics-integration}

* **Syncing of the Multiselect Optionset Field Type Generally Available**: Sync the multiselect optionset field type from [!DNL Microsoft Dynamics] to leverage in Smart Lists and Smart Campaigns for more granular audience targeting. Examples include: topics/products of interest, preferred modes of communication, and more. This new sync is available for [!DNL Microsoft Dynamics] version 9.X (including Dynamics 365 Online).

* **Server to Server Authentication for [!DNL Microsoft Dynamics 365 Online]**: For increased security, we will now support Server to Server (S2S) as an additional mode of authentication for the Marketo Engage sync user on Azure Active Directory for non-interactive access to [!DNL Microsoft Dynamics 365 Online]. This allows you to employ multi-factor authentication, as all authentication and sign-ons will be based on OAuth (only client ID and client secret).

>[!NOTE]
>
>The S2S mode is based on Application User rather than Licensed User, which saves the use of an additional license.

## Administration {#administration}

* **[Form Validation Rules](/help/marketo/product-docs/administration/settings/global-form-validation-rules.md)**: Maintain the health of your database with the ability to block problematic or undesirable email domains from submitting Marketo Engage forms. The Global Form Validation Rule panel allows administrators to define a blocklist or enable a pre-defined list of free consumer domains to block from forms.

* **[Landing Page Header Security](/help/marketo/product-docs/administration/settings/landing-page-headers.md)**: Administrators can manage Strict Transport Security and X-Frame Options headers on their landing page domains to enforce strong security requirements.

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

## AEP Marketo Engage Destination Connector – Create Net-new Leads {#aep-marketo-engage-destination-connector}

Marketo Engage customers that also use the Adobe Experience Platform (AEP) can maximize their database with the ability to push net-new person records into Marketo Engage from AEP via the AEP destination connector. When sending audience segments from AEP to Marketo Engage, people within the segment that don't already exist in your Marketo Engage database [can be automatically added to it](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/push-an-adobe-experience-platform-segment-to-a-marketo-static-list.md).

## [!DNL Sales Insight]

![(star)](assets/yellow-star.png)

**[!DNL Sales Insight] for [!DNL Salesforce] CRM**

* **New Type Column for [!UICONTROL Best Bets]**: Sellers will get quicker insights with a new column labeled "Type" to differentiate between leads and contacts on the [!UICONTROL Best Bets] page.

* **[!DNL Salesforce] Platform API Update**: In response to [!DNL Salesforce] retiring [!DNL Salesforce] Platform API versions 21.0 through 30.0, the [!DNL Sales Insight] package has been updated with the latest APIs.

* **Updated Branding**: All [!DNL Sales Insight] pages are being updated to align with Adobe branding.

**[!DNL Sales Insight] for [!DNL Microsoft Dynamics]**

* **Updated Account Layout**: Sellers can get a collective view of the top activities such as: email activities, web activities, interesting moments, and score changes for all contacts within an account.

## [!DNL Sales Connect]

![(star)](assets/yellow-star.png)

* **Call Outcomes and Reasons**: Understand and track your sales teams' outbound efforts in more detail with new, fully customizable call outcome and call reason options. In addition to these new fields, we are introducing new governance to enforce call reason and outcome selection while sellers are making calls, new governance to enable or disable call reasons and outcomes, and a new Call Reason and Call Outcome [!DNL Salesforce] Activity custom field for logging data to [!DNL Salesforce]. [Click here](https://nation.marketo.com/t5/product-blogs/sales-connect-enhancements-to-call-outcomes-q1-22-release/ba-p/319812) to learn more.

* **[!DNL Salesforce] Activity Detail Customization**: Capture more sales activity and task data in [!DNL Salesforce] by customizing what information is added to the [!DNL Salesforce] task subject field when a sales activity is logged to [!DNL Salesforce] from [!DNL Sales Connect]. [Click here](https://nation.marketo.com/t5/product-blogs/sales-connect-enahncements-to-activity-logging-to-salesforce-q1/ba-p/319819) to learn more.

## Announcements

* **Marketo Sky Deprecation**: In March, Marketo Sky will no longer be available as we focus our resources on delivering the next-generation user experience. In an effort to maintain access to functionality that is exclusive to Marketo Sky today, we are bringing Asset Expiration and Smart Campaign Priority Override into the mainstream experience in March. [Click here](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33) to learn more.

* **Form Endpoints Deprecation**: Unsupported programmatic form POSTs to the leadCapture/save2 endpoint will be rejected by Marketo Engage forms. [Click here](https://nation.marketo.com/t5/product-documents/updated-october-2021-upcoming-changes-to-the-marketo-engage-form/ta-p/306631) to learn more.

* **Login in Invite User Dialog**: In March, the existing, optional feature "Login in Invite User Dialog" will be deprecated. The feature "[!UICONTROL Login in Invite User Dialog]" functionality is overridden by the Universal ID feature, which is required for the upcoming Adobe Identity Management System Integration and was enabled in August 2021 on all subscriptions. As a result of the deprecation, Marketo Engage will enforce only one user to be associated per email address within a subscription.

**Marketo Engage Domains – [!DNL Sales Insight] Configuration**: For Marketo Engage domains which do not have SSL cert provisioned and https://, calls will fail with an SSL handshake error. Therefore, these domains are going to be sunset. As a result, [!DNL Sales Insight] users with an older configuration pointing to any of these domains might run into system callout errors on their Lead, Contact, Account, Opportunity Panels, or Marketo Global page. We recommend you update your [Marketo Engage configuration](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md) in [!DNL Salesforce] if you run into this error. You only need to update Marketo Engage credentials highlighted in the "[!DNL Marketo Sales Insight] Config" section of the document.

**_Product Release Webinar_**

[January 2022 Marketo Engage Release Webinar](https://engage.marketo.com/2022_January_Release_Webinar_DemandPage.html)

## March 2022 {#march}

The following features are included in the March '22 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will start to be released on **March 11, 2022**, with a phased rollout of every feature over the following weeks (unless specified otherwise).

## Cross-Channel Orchestration

* **[!DNL Dynamic Chat]**: Maximize every opportunity on your website by targeting both leads and accounts with proactive, engaging, and 1:1 personalized conversations. [Dynamic Chat](/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md){target="_blank"} allows Marketo Engage users to start leveraging chat as a key part of integrated cross-channel experiences for B2B marketing and sales use cases. Features include: the ability to book meetings directly within the chat, lead routing, starter templates, drag-and-drop conversation creation, and much more. Dynamic Chat is included in all Marketo Engage packages and will be rolled out to all Marketo Engage users this year.

* **Email Bot Activity Filtering Enhancement**: As an enhancement to the previously released [Email Bot Activity Filtering](/help/marketo/product-docs/administration/email-setup/filtering-email-bot-activity.md){target="_blank"} feature, you can now opt-in to logging activities that are identified as bots. You can then filter and trigger actions based on activities that are identified as being performed by bots.

## Next-Generation Experience

* **Updated Screens in the Next-Generation Experience**: We're delivering additional, refreshed screens in the next-generation experience that offer an updated design and usability enhancements accessible via toggle switch:

  * Form List View in [!UICONTROL Design Studio] (including new bulk actions)

* **Import Program Workflow Update**: The import program workflow is being delivered in the next-generation experience with an updated design and usability enhancements. This will be an automatic change without a toggle switch.

* **Admin Control for the Next-generation Experience Toggle Switch**: Manage the rollout of the next-generation experience in a way that works for your users with the ability for admins to select which user types can access the toggle switch.

## Experience Automation

* **Self-Service Flow Steps (Beta)**: Expand connectivity between Marketo Engage and the rest of your stack with the ability to author customized flow steps for use in Smart Campaigns. Both Marketo users and partners can leverage this functionality to allow for the usage of external web services in batch and executable campaigns in contrast to webhooks, which can only be used in trigger campaigns.

* **Asset Expiration**: Maintain control of your time-sensitive assets and campaigns with the ability to schedule their automatic deactivation at a specified date and time in the Classic user experience.

* **Smart Campaign Priority Override**: Ensure that high-priority trigger Smart Campaigns execute as soon as possible with the ability to override the standard campaign priority ranking. Lower-priority trigger Smart Campaigns can also be lowered in priority to free up processing resources for other high-priority tasks.

## API Enhancements

* **Return Disable Open Tracking Status of Emails**: Allows for the reading of open tracking status of emails via API
* **Retrieve Dynamic Content Subject Lines from Email**: Allows marketers to perform analysis of dynamic subject lines in BI tools
* **Program Member Custom Fields CRUD**: Allows marketers to programmatically create program member custom fields
* **Bulk Custom Object Export updatedAt Filter**: Allows marketers to programmatically sync custom objects
* **Expose Head Start Setting for Email Programs**: Allows marketers to configure email programs with head start via API
* **Selective Program Tag Update**: Allows marketers to push selective tag updates without pushing all tags at the same time
* **Bulk Activity Extract actionResult field**: Allows marketers to identify which activities were skipped or failed

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

## [!DNL Bizible] {#bizible}

![(star)](assets/yellow-star.png)

* **BI Templates**: [!DNL Bizible] will now provide downloadable, foundational reporting artifacts and sample reports for Tableau and Power BI to enable rapid development of custom reports tailored for your specific business needs.

## [!DNL Sales Connect]

![(star)](assets/yellow-star.png)

* **Email Connection Throttling (GA)**: Email Connection Throttling allows [!DNL Sales Connect] administrators to configure the send rate of emails when using Gmail or [!DNL Exchange] as your delivery channel, so that the rate at which emails are being handed over to the delivery channel provider do not exceed the enforced limits.

## Announcements

* **Marketo Sky Deprecation**: In March, Marketo Sky will no longer be available as we focus our resources on delivering the next-generation user experience. In an effort to maintain access to functionality that is exclusive to Marketo Sky today, we are bringing Asset Expiration and Smart Campaign Priority Override into the Classic experience. [Click here](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33) to learn more.

**_Product Release Webinar_**

[March and May 2022 Marketo Engage Release Webinar](https://engage.marketo.com/2022_March_May_Release_Webinar_DemandPage.html){target="_blank"}

## May 2022 {#may}

Below you'll find all the features included in the May '22 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will start to be released on **May 6, 2022**, with a phased rollout of remaining features over the subsequent weeks (unless specified otherwise).

## Native CRM Integration {#native-crm-integration}

**[Native Veeva CRM Integration](/help/marketo/product-docs/crm-sync/veeva-crm-sync/understanding-the-veeva-crm-sync.md){target="_blank"} (limited availability)**: Improve engagement with healthcare professionals by syncing activity between Veeva CRM and Marketo Engage via native integration. This integration allows marketers to create more personalized and seamless cross-channel experiences for healthcare professionals. Please contact your Customer Success Manager if you are interested in participating.

## Cross-Channel Orchestration

**Chatbot Events for [!DNL Dynamic Chat]**: Leverage more detailed behavior data for web visitors such as time on page, time on site, and page scroll percentage to define when a chat dialogue should be shown.

**PDF Embed for [!DNL Dynamic Chat]**: Increase engagement and share meaningful content by embedding PDFs into chat dialogues and measure content performance through engagement activity tracking.

**Extended Language Support for [!DNL Dynamic Chat]**: The [!DNL Dynamic Chat] user interface will now also be available in French, German, Japanese, Portuguese, and Spanish. Chat dialogues can also be configured in these languages.

**Exclude URLs for [!DNL Dynamic Chat]**: Control which of your webpages [!DNL Dynamic Chat] appears on with the ability to exclude specific URLs from targeting criteria.

**[Email Bot Activity Filtering Enhancements](/help/marketo/product-docs/administration/email-setup/filtering-email-bot-activity.md){target="_blank"}**: Continue to protect the health of your database with the ability to identify bot behavior based on hidden link User Agents or IPs and proximity patterns, in addition to the existing IAB list match identification. View bot activity stats that allow you to understand the number of bot activities identified for each type.

**[STS Header for Email Tracking Links](/help/marketo/product-docs/administration/settings/email-tracking-link-headers.md){target="_blank"}**: Meet security best practices with the ability to apply Secure Transport Security headers to ensure traffic to tracked links is always secure.

## Next-Generation Experience

**Toggle Switch Defaulted to the Next-Generation Experience**: The toggle switch will be default to the new experience in all screens where it is available, making it easier for users to discover the updated designs and usability enhancements.

**Updated Screen in the Next-Generation Experience**:

We're delivering Email Template Details View within [!UICONTROL Design Studio] in the next-generation experience, offering an updated design and usability enhancements accessible via toggle switch.

## Experience Automation

**Self-Service Flow Steps (continued beta)**: Expand connectivity between Marketo Engage and the rest of your stack with the ability to author customized flow steps for use in Smart Campaigns. Both Marketo Engage users and partners can leverage this functionality to allow for the usage of external web services in trigger, batch, and executable campaigns (in contrast to webhooks which can only be used in trigger campaigns).

## API Enhancements

* **Expanded API Access for CRM-Enabled Subscriptions**: We are expanding API access for subscriptions that have a CRM sync enabled to allow users to retrieve Companies, Opportunities, and Sales Persons from Marketo Engage.
* **Support for "Hidden" Datatypes in Forms**: Provides the ability to manage hidden form fields via API.
* **Support Multiple Comparison Values for isNot Form via Rules**: Manage visibility of form fields based on whether the value of another field is not one of the values in a given list.
* **Allow setting of Display and Submitted Values in Select Lists Separately**: Set the display value and submitted value in a field separately. For example, show the name of a hotel, but submit an Internal ID to the backend.
* **Allow Setting of Disable Open Tracking on Create or Update Email**: Create an email with open tracking disabled.

## Announcements

**Email Verification and Uniqueness**: Beginning in April, rollout of Email Verification will commence. At that point, Marketo Engage user email addresses will require verification and uniqueness (this does not apply to API-only users). Directory service authenticated users will automatically have their emails verified when their subscription is enabled with Email Verification.

Email Verification for subscriptions using the "[!UICONTROL Login in Invite User Dialog]" feature or that have a single email associated with multiple users will coincide with the May release. Subscriptions that have a single email associated with multiple users will be enabled with Email Verification and will require those users to resolve the conflict and use a unique email per user. When the 'Login in Invite User Dialog' feature is enabled, users invited via this feature will need to have a unique email address. For API-only users invited via this feature, the email address does not need to be unique.

**Archive Folder Behavior Change**: With this release, the ability to create new assets in Archive folders will no longer be available from the tree context menus. Menu options for creating new assets will be hidden for all assets. [Learn more here](https://nation.marketo.com/t5/product-discussions/archive-folder-change-in-may-2022-release/m-p/324369#M183235){target="_blank"}.

**_Product Release Webinar_**

[March and May 2022 Marketo Engage Release Webinar](https://engage.marketo.com/2022_March_May_Release_Webinar_DemandPage.html){target="_blank"}

## June 2022 {#june}

Below you'll find all the features included in the June '22 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

The following features will start to be released on **June 24, 2022**, with a phased rollout of remaining features over the subsequent weeks (unless specified otherwise).

## Marketing Data Environment

* **Expose CreatedAt/UpdatedAt fields for Custom Objects**: Gives you the ability to inspect these fields in the Person Detail screen to gain additional insight.

## Cross-Channel Orchestration

* **Improved Stream Designer Usability for [!DNL Dynamic Chat]**: Add cards directly from the Stream Designer canvas without the need to drag and drop. The [!DNL Dynamic Chat] interface has also been improved to offer better visibility of content in individual cards.

* **Advanced Appointment Routing Rules for [!DNL Dynamic Chat]**: [!DNL Dynamic Chat] offers more options for targeted appointment routing. Specify which agent appointments should be routed based on Marketo Engage attributes, ensuring leads are routed to the appropriate agents.

* **Advanced Dialogue Reporting for [!DNL Dynamic Chat]**: View the performance of your [!DNL Dynamic Chat] campaigns in greater detail using all-new data visualizations for engagement and conversion metrics.

* **Unsync Unused Marketo Engage Attributes for [!DNL Dynamic Chat]**:  Unsync Marketo Engage attributes from your [!DNL Dynamic Chat] subscription that go unused, helping you facilitate data cleanliness and allowing for alternative attributes to be synced as needed.

## Next-generation Experience

**New Toggle Switch Views**: The views below are now available in the Next-generation Experience:

* [Email Details View](https://experienceleague.adobe.com/en/docs/marketo/using/home){target="_blank"}
* [Email List View](https://experienceleague.adobe.com/en/docs/marketo/using/home){target="_blank"}

## Experience Automation

* **Global Form Field Validation Rule Exclusions**: Exclude specific forms from Global Form Validation Rules so subscription centers and other business critical workflows can accept all values.

* **Self-service Flow Steps**: Expand connectivity between Marketo Engage and the rest of your stack with the ability to author customized flow steps for use in Smart Campaigns. Both Marketo Engage users and partners can leverage this functionality to allow for the usage of external web services in Trigger, Batch, and Executable Campaigns in contrast to Webhooks, which can only be used in Trigger Campaigns.

* **Munchkin Protocol Agnostic Link Tracking**: Extend support for tracking of `tel` and `mailto` links with Munchkin to track expanded set of web behaviors.

* **Additional HTTP methods for webhooks**: Specify PUT, PATCH, and DELETE as request types to interact with web services.

## [!DNL Sales Insight]

![(star)](assets/yellow-star.png)

* **[!DNL Sales Insight] Permission Set in [!DNL Salesforce]**: Admins can provide [!DNL Sales Insight] access to a limited set of people on a user level rather than profile level through the Marketo App permission set, which is part of the [!DNL Sales Insight] [!DNL Salesforce] package.

* **My Marketo Tile Update - [!DNL Sales Insight] Actions**: Marketo Admins (and users they designate) can now quickly navigate to their [!DNL Sales Insight] Actions instance via a new [!DNL Sales Insight] Actions tile located on the My Marketo page.

## [!DNL Sales Connect]

![(star)](assets/yellow-star.png)

* **[!DNL Salesforce] API Update**: With the [!DNL Salesforce] Summer '22 release, API legacy versions 21 -30 will no longer be supported by [!DNL Salesforce]. With this Marketo Engage release, all [!DNL Sales Connect] requests using legacy API versions have been updated to stay within a supported version. For full details on [!DNL Salesforce] API retirement plans, click [here](https://help.salesforce.com/s/articleView?language=en_US&type=1&id=000354473){target="_blank"}.

## API Enhancements

* **New filtering capabilities for Bulk Program Member Extract API**: Filter by program membership status, updatedAt, cadence, or exhausted content to refine extracted data set.

* **Bulk Program Member Extract API improvement**: Specify up to 10 programs during job creation to improve throughput.

## Announcements

* **Forms Deprecation - Forms 1.0, lead Capture/save endpoint, and no-script versions of forms**: Support for Forms 1.0 assets will be completely removed from Marketo Engage by October, 2022. All existing Forms 1.0 assets will cease to function. Marketo Engage forms will require JavaScript to load on landing pages and websites.

**_Product Release Webinar_**

[June and August 2022 Marketo Engage Release Webinar](https://engage.marketo.com/2022_June_August_Release_Webinar_OnDemandPage.html){target="_blank"}

## August 2022 {#august}

Below you'll find all the features included in the August '22 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

The following features began a phased rollout on **August 26, 2022**.

## Cross-Channel Orchestration

* Enable/Disable All Published Dialogues at Once for [!DNL Dynamic Chat]**: Globally enable/disable all published Dialogues at once from the Configuration page with the press of a button.

* **Custom Avatars for [!DNL Dynamic Chat]**: Upload a custom chatbot avatar so it can be personalized to your brand.

* **Chat Transcripts for [!DNL Dynamic Chat]**: View chat transcripts for every conversation to obtain deeper insight into what each web visitor is interested in.

## Next-generation Experience

* **Adobe Branding**: Updated look and feel for editors and person detail page with new Adobe Experience Cloud branding.

* **Display Folder Hierarchy of Destination Folder in the Move Dialog**: Viewing the folder hierarchy for each folder makes moving assets easier and reduces the likelihood of putting them in the wrong folder.

* **[Updated Screens in the Next-Generation Experience](https://experienceleague.adobe.com/en/docs/marketo/using/home){target="_blank"}**: We're delivering additional, refreshed screens in the next-generation experience that offer an updated design and usability enhancements accessible via toggle switch:

  * Snippet Details
  * "Images and Files" Details

>[!NOTE]
>
>The exception is moving an asset to a folder within a program in Marketing Activities. This move action will not display the folder hierarchy as folders within a program cannot have duplicate names.

## Experience Automation

* **[Self-Service Flow Steps - Program Import Enhancements](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/flow-step-service.md){target="_blank"}**: Improved support for importing programs with custom flow steps where you can now use multiple instances of the same service provider and import programs which have flow steps compatible with those service providers.

* **[!DNL Munchkin] - Expanded Link Tracking**: Extend support for tracking of `tel` and `mailto` links with Munchkin to track an expanded set of web behaviors.

* **Webhook Custom Header Visibility**: Webhook custom headers are now displayed in the [!UICONTROL Admin] > [!UICONTROL Webhooks] tab for better visibility.

* **CAPTCHA**: Evaluate the validity of form submissions [using reCAPTCHA v3](/help/marketo/product-docs/demand-generation/forms/using-captcha/enable-captcha-in-marketo-forms.md){target="_blank"} to score incoming form traffic. Build marketing workflows to automatically exclude, quarantine, or delete suspicious bot traffic.

* **Permission to Approve Form**: New permission to control which designers can approve changes to a form in line with other [!UICONTROL Design Studio] assets. This prevents other designers from pushing changes to forms without someone else with approval permission reviewing it.

* **Always Perform Campaign Replay After Anonymous Merge**: Anonymous lead merge happens before campaign replay so custom field filters behave reliably when anonymous campaign replay is done.

## Marketing Data Environment

* **Fix UI truncation of Custom Object "[!UICONTROL Used By]" fields**: it is now easier to identify custom object fields that are "in use" so you can delete fields from a Custom Object when necessary.

## API Enhancements

* **New Filtering Capabilities for Bulk Program Member Extract API**: Filter by program membership status, updatedAt, cadence, or exhausted content to refine extracted data set.

## [!DNL Sales Insight]

![(star)](assets/yellow-star.png)

* **[[!DNL Sales Insight] Integration with [!DNL Dynamic Chat]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md){target="_blank"}**: View activities from [!DNL Dynamic Chat] in the [!DNL Sales Insight] panel and leverage this new data point in your prospecting effort.

## Announcements

**_Product Release Webinar_**

[June and August 2022 Marketo Engage Release Webinar](https://engage.marketo.com/2022_June_August_Release_Webinar_OnDemandPage.html){target="_blank"}

## October 2022 {#october}

Below you'll find all the features included in the October '22 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **October 14, 2022**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check below each feature for its status.

### Marketing Data Environment

</br>

* **Program Member Custom Field Sync**: Ability to bidirectionally sync extensible fields captured for a program member (e.g., attendee preferences during event registration such as food, sessions, tracks, etc.) with Campaign Member Fields in Salesforce.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-field-sync.md">Program Member Custom Field Sync</a></td>
  </tr>
  </tbody>
</table>

* **Adobe Privacy Service Integration**: Harmonize with Privacy Service to automate compliance with data privacy regulations across Experience Cloud products. Currently, this service is only available to Marketo Engage customers that have onboarded to the Adobe Identity Management System.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md">Adobe Identity Management</a></td>
  </tr>
  </tbody>
</table>

### Next-generation Experience

</br>

* **Updated Screens in the Next-Generation Experience**: We're delivering additional, refreshed screens in the next-generation experience that offer an updated design and usability enhancements accessible via toggle switch:

  * Landing Page Template Details
  * Email Template List

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/home">Toggle Switch</a></td>
  </tr>
  </tbody>
</table>

* **Enhanced Used by tab in Email Template Details**: In the new experience, you will see additional information related to assets using the email template, including Asset Status, Last Modified, and Last Modified By. You can also search, sort, and filter the list of used by assets.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  </tbody>
</table>

* **Report Asset Filter Modals**: New design for report configuration modals displaying a new asset tree in the configuration menu and a filter for Date Created and Modified.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  </tbody>
</table>

### API Enhancements

</br>

* **Bulk Lead Import: Salesperson association**: Parity with Lead REST API to able to associate leads with Salespersons during the bulk lead import process, reducing complexity and the number of API calls required.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td><a href="https://developer.adobe.com/marketo-apis/api/mapi/#tag/Bulk-Import-Leads">Bulk Lead Import</a></td>
  </tr>
  </tbody>
</table>

### Sales Insight

</br>

![(star)](assets/yellow-star.png)

* **Sales Insight Integration with Dynamic Chat**: Insights Dashboard now includes Dynamic Chat activities in the Smart Grid along with a weekly summary and detail cards.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md">Dynamic Chat Integration</a></td>
  </tr>
  </tbody>
</table>

## Agile Release Features

The following features follow an Agile format and are released on various dates before or after the standard release date. Please check below each feature for its status.

* **Auto Arrange Dialogue streams for Dynamic Chat**: Improve your crowded Dialogue canvas by organizing everything on the canvas into a clean and easy to read format with the press of a button through Auto Arrange.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/stream-designer.md#stream-designer-icons">Stream Designer Icons</a></td>
  </tr>
  </tbody>
</table>

* **Meeting Links for Dynamic Chat**: Option to automatically include a Teams or Meet link for Google and Outlook in every calendar invite that's sent to visitors.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/agent-settings.md">Calendar</a></td>
  </tr>
  </tbody>
</table>

* **Support additional data types for Dynamic Chat**: Three new data types (boolean, integer, float) allow you to leverage more existing Marketo Engage fields in Dynamic Chat for things like targeting based on scores or asking visitors yes/no questions.

<table>
  <tr>
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr>
   <td>Released</td>
   <td>n/a</td>
  </tr>
  </tbody>
</table>

## Announcements

* **Forms 1.0**: The deprecation of Forms 1.0 will be completed with the October release. Forms 1.0 assets will no longer be able to submit data to Marketo Engage and will return errors if attempted.

* **No-Script Forms**: Forms will no longer function when Javascript is disabled in the browser. Form submission will require Javascript be enabled.
