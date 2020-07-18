---
unique-page-id: 11370952
description: Release Notes: Spring '16 - Marketo Docs - Product Documentation
title: Release Notes: Spring '16
---

# Release Notes: Spring '16 {#release-notes-spring}

Release Notes: Spring '16 - Marketo Docs - Product Documentation

The following features are included in the Spring '16 release. Please click the title links to view detailed articles for each feature.

### What's in this article? {#whats-in-this-article}

[Email Insights](#email-insights)  
[Email Template Picker](#email-template-picker)  
[Email Editing---Re-imagined](#email-editing-re-imagined)  
[Mobile In-App Messages](#mobile-in-app-messages)  
[No Draft Snippets](#no-draft-snippets)  
[Custom Activities](#custom-activities)  
[Landing Page, Landing Page Template, and Form APIs](#landing-page-landing-page-template-and-form-apis)  
[IP Allowlisting for API Access](#ip-allowlisting-for-api-access)  
[New High-Speed Microsoft Dynamics Sync Connector](#new-high-speed-microsoft-dynamics-sync-connector)  
[Friendly Instance Name](#friendly-instance-name)  
[Limited Time Access for Subscriptions](#limited-time-access-for-subscriptions)  
[Custom Objects Grid](#custom-objects-grid)

#### [Email Insights](../../product-docs/reporting/email-insights.md) {#email-insights}

Email Insights is a brand new historical aggregate data email analytics experience —&nbsp;redesigned&nbsp;end-to-end&nbsp;for lightning fast performance as part of Project Orion. It features a completely new user interface design optimized to fit the needs and workflow of Email Marketers.&nbsp;

>[!NOTE]
>
>We are launching Email Insights to customers in batches, beginning June 3rd. Our goal is to complete this over the next several months. We’ll notify you by email when you’re enabled.

![](assets/two.png)

#### [Email Template Picker](../../product-docs/email-marketing/general/email-editor-2.0/email-template-picker-overview.md) {#email-template-picker}

Create beautiful emails using our new Starter Templates! Also, quickly locate your templates from their live thumbnails.

>[!NOTE]
>
>Email Editor 2.0 (with the Template Picker) will gradually be rolled out beginning June 3rd. We will complete the rollout by June 30th. Unlike Email Insights, you will not be notified when you have access. To see if you do, please follow the steps in [this article](https://docs.marketo.com/pages/viewpage.action?pageId=11373011).

![](assets/5-29-home-starter-templates.png)  

#### [Email Editing---Re-imagined](http://docs.marketo.com/display/docs/assets/email-editor-v2.0-overview) {#email-editing-re-imagined}

That’s right, a brand new email editor! Use lightweight drag-and-drop functionality to add and re-order content. New elements, including images, videos, variables, and modules, are sure to enhance your editing experience. Also check out the updated code editor, previewer, and preheader support.

![](assets/17a-29-modules-next.png)

#### [Mobile In-App Messages](../../product-docs/mobile-marketing/in-app-messages/understanding-in-app-messages.md) {#mobile-in-app-messages}

Create stunning in-app messages for your app right within Marketo. Define exactly who should see it and when with the in-app message program. Easily monitor its performance with the program dashboard.

![](assets/pasted-image-at-2016-05-24-09-45-am.png)

#### [No Draft Snippets](../../product-docs/administration/users-and-roles/managing-user-roles-and-permissions/enable-no-draft-for-snippets.md) {#no-draft-snippets}

Gone are the days where you have to re-approve everything each time a snippet is updated! With No-Draft, all emails and landing pages using a snippet will get the snippet updates and maintain their prior statuses. Each time you approve a snippet, you’ll have a choice to run No-Draft and update everything, or create drafts. It’s up to you! No-Draft will be available to all customers and controlled by a new permission in Admin.

![](assets/image2016-5-16-15-3a41-3a17.png)

#### [Custom Activities](../../product-docs/administration/marketo-custom-activities.md) {#custom-activities}

Marketo admins can now define and manage their custom activity types via the Marketo Custom Activity Definition modeler. Similar to (and in conjunction with) the Marketo Custom Object Modeler, admins can now extend the data model to suit their exact business needs. Details on how to use this functionality is available on the [Marketo documentation site](https://docs.marketo.com/display/public/DOCS/Marketo+Custom+Activities).

#### [Landing Page, Landing Page Template, and Form APIs](http://developers.marketo.com/blog/spring-2016-updates/) {#landing-page-landing-page-template-and-form-apis}

The Marketo REST APIs now support control over Marketo landing pages, landing page templates, and forms. Users can now create, update content, approve, and delete these assets directly via the Marketo REST API.

#### [IP Allowlisting for API Access](../../product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.md) {#ip-allowlisting-for-api-access}

Similar to the IP allowlisting feature for Marketo user logins, Marketo admins can now set up a allowlist of IP addresses that can access the Marketo SOAP and REST APIs, thereby blocking access from non-authorized IP addresses. This provides an added layer of security to your Marketo instance, and ensures that API access can only occur from within your organization’s network. Details on how to set this up are available on the [Marketo documentation site](https://docs.marketo.com/display/public/DOCS/Create+a+Whitelist+for+IP-Based+API+Access).

#### [New High-Speed Microsoft Dynamics Sync Connector](../../product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/sync-status.md) {#new-high-speed-microsoft-dynamics-sync-connector}

Built atop Orion architecture, the new, high-speed dynamics connector provides speeds up to 20 times faster for initial sync and up to 5 times faster for incremental sync. All new customers will onboard to this connector on the release date, and we will gradually roll it out to existing customers over the summer release time frame.

**Refresh data for new fields: **Now you can enable new sync fields at any point in time and all data values for that field will be refreshed from Dynamics CRM into Marketo. No more worries about having to select all fields during initial setup. If you disable an existing sync field and re-enable it later, all data values for that field will be refreshed from Dynamics CRM into Marketo.

**Sync Lead as Contact**: The Sync Lead to Microsoft flow action has a new option to sync as a lead or a contact.

![](assets/image2016-5-19-8-3a59-3a9.png)

**Sync Errors Admin Tab**: &nbsp;Browse,&nbsp;search, or export leads (and other objects) that failed to synchronize with details such as operation, direction, error code and error message.

![](assets/sync-errors.png)

**Microsoft Dynamics 2016**: Connector is fully certified for Dynamics 2016 Online and On-premise versions.

**Plug-In Updates are now documented: **See the [plug-in updates docs article](../../product-docs/crm-sync/microsoft-dynamics-sync/marketo-plugin-releases-for-microsoft-dynamics.md).

#### [Friendly Instance Name](../../product-docs/administration/settings/edit-subscription-settings.md) {#friendly-instance-name}

Today, it’s hard to differentiate between Marketo instances, for example, sandbox and production instances. This feature lets you know which instances you're currently working on.

![](assets/image2016-5-16-15-3a57-3a14.png)

#### [Limited Time Access for Subscriptions](../../product-docs/administration/users-and-roles/managing-marketo-users.md) {#limited-time-access-for-subscriptions}

Today, users are invited to Marketo subscription for an indefinite period of time. This feature enables admins to invite users to subscriptions for a limited period of time, for example, 2 weeks or 1 month.

![](assets/image2016-5-16-15-3a59-3a52.png)

#### [Custom Objects Grid](../../product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) {#custom-objects-grid}

Now, you can view the number of records and fields for all published custom objects.

![](assets/custom-objects-grid.png)

