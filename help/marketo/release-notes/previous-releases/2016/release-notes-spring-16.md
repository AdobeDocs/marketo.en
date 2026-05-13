---
unique-page-id: 11370952
description: Release Notes -Spring '16 - Marketo Docs - Product Documentation
title: Release Notes -Spring '16
exl-id: 0ca26acf-2ac2-418e-bc4e-9820f483fa71
feature: Release Information
TQID: https://experienceleague.adobe.com/TIzpFh7-yNA686kqS2u3A-scPk-ew7XqX-wx4IqnSKI
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: d5c7388a-594e-4d15-9b39-98d6ce479e8b
    internal-label: Microsoft Dynamics
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Release Notes: Spring '16 {#release-notes-spring}

The following features are included in the Spring '16 release. Please click the title links to view detailed articles for each feature.

## [Email Insights](/help/marketo/product-docs/reporting/email-insights/email-insights-overview.md) {#email-insights}

Email Insights is a brand new historical aggregate data email analytics experience - redesigned end-to-end for lightning fast performance. It features a completely new user interface design optimized to fit the needs and workflow of Email Marketers.

>[!NOTE]
>
>We are launching Email Insights to customers in batches, beginning June 3rd. Our goal is to complete this over the next several months. We'll notify you by email when you are enabled.

![](assets/two.png)

## [Email Template Picker](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-picker-overview.md) {#email-template-picker}

Create beautiful emails using our new Starter Templates! Also, quickly locate your templates from their live thumbnails.

>[!NOTE]
>
>Email Editor 2.0 (with the Template Picker) will gradually be rolled out beginning June 3rd. We will complete the rollout by June 30th. Unlike Email Insights, you will not be notified when you have access. To see if you do, please follow the steps in [this article](/help/marketo/product-docs/email-marketing/general/email-editor-2/transitioning-to-email-editor-2-0.md).

![](assets/5-29-home-starter-templates.png)

## [Email Editing---Re-imagined](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md) {#email-editing-re-imagined}

That's right, a brand new email editor! Use lightweight drag-and-drop functionality to add and re-order content. New elements, including images, videos, variables, and modules, are sure to enhance your editing experience. Also check out the updated code editor, previewer, and preheader support.

![](assets/17a-29-modules-next.png)

## [Mobile In-App Messages](/help/marketo/product-docs/mobile-marketing/in-app-messages/understanding-in-app-messages.md) {#mobile-in-app-messages}

Create stunning in-app messages for your app right within Marketo. Define exactly who should see it and when with the in-app message program. Easily monitor its performance with the program dashboard.

![](assets/pasted-image-at-2016-05-24-09-45-am.png)

## [No Draft Snippets](/help/marketo/product-docs/administration/users-and-roles/enable-no-draft-for-snippets.md) {#no-draft-snippets}

Gone are the days where you have to re-approve everything each time a snippet is updated! With No-Draft, all emails and landing pages using a snippet will get the snippet updates and maintain their prior statuses. Each time you approve a snippet, you'll have a choice to run No-Draft and update everything, or create drafts. It is up to you! No-Draft will be available to all customers and controlled by a new permission in Admin.

![](assets/image2016-5-16-15-3a41-3a17.png)

## [Landing Page, Landing Page Template, and Form APIs](https://developers.marketo.com/blog/spring-2016-updates/) {#landing-page-landing-page-template-and-form-apis}

The Marketo REST APIs now support control over Marketo landing pages, landing page templates, and forms. Users can now create, update content, approve, and delete these assets directly via the Marketo REST API.

## [IP Allowlisting for API Access](/help/marketo/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.md) {#ip-allowlisting-for-api-access}

Similar to the IP allowlisting feature for Marketo user logins, Marketo admins can now set up a allowlist of IP addresses that can access the Marketo SOAP and REST APIs, thereby blocking access from non-authorized IP addresses. This provides an added layer of security to your Marketo instance, and ensures that API access can only occur from within your organization's network. Details on how to set this up are available on the [Marketo documentation site](/help/marketo/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.md).

## [New High-Speed Microsoft Dynamics Sync Connector](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/sync-status.md) {#new-high-speed-microsoft-dynamics-sync-connector}

The new, high-speed Dynamics connector provides speeds up to 20 times faster for initial sync and up to 5 times faster for incremental sync. All new customers will onboard to this connector on the release date, and we will gradually roll it out to existing customers over the summer release time frame.

**Refresh data for new fields**: Now you can enable new sync fields at any point in time and all data values for that field will be refreshed from [!DNL Dynamics] CRM into Marketo. No more worries about having to select all fields during initial setup. If you disable an existing sync field and re-enable it later, all data values for that field will be refreshed from [!DNL Dynamics] CRM into Marketo.

**Sync Lead as Contact**: The [!UICONTROL Sync Lead to Microsoft] flow action has a new option to sync as a lead or a contact.

![](assets/image2016-5-19-8-3a59-3a9.png)

**Sync Errors Admin Tab**:  Browse, search, or export leads (and other objects) that failed to synchronize with details such as operation, direction, error code and error message.

![](assets/sync-errors.png)

**[!DNL Microsoft Dynamics] 2016**: Connector is fully certified for [!DNL Dynamics] 2016 [!DNL Online] and [!DNL On-premise] versions.

**Plug-In Updates are now documented:** See the [plug-in updates docs article](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/marketo-plugin-releases-for-microsoft-dynamics.md).

## [Friendly Instance Name](/help/marketo/product-docs/administration/settings/edit-subscription-settings.md) {#friendly-instance-name}

Today, it is hard to differentiate between Marketo instances, for example, sandbox and production instances. This feature lets you know which instances you are currently working on.

![](assets/image2016-5-16-15-3a57-3a14.png)

## Limited Time Access for Subscriptions {#limited-time-access-for-subscriptions}

Today, users are invited to Marketo subscription for an indefinite period of time. This feature enables admins to invite users to subscriptions for a limited period of time, for example, 2 weeks or 1 month.

![](assets/image2016-5-16-15-3a59-3a52.png)

## [Custom Objects Grid](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) {#custom-objects-grid}

Now, you can view the number of records and fields for all published custom objects.

![](assets/custom-objects-grid.png)

## Custom Activities {#custom-activities}

Marketo admins can now define and manage their custom activity types via the Marketo Custom Activity Definition modeler. Similar to (and in conjunction with) the Marketo Custom Object Modeler, admins can now extend the data model to suit their exact business needs. Details on how to use this functionality is available on the [Marketo documentation site](/help/marketo/product-docs/administration/marketo-custom-activities/understanding-custom-activities.md).
