---
description: Release Notes - January 2022 - Marketo Docs - Product Documentation
title: Release Notes - January 2022
exl-id: babc4e7f-3f11-4883-80c6-58e69c3e1ab4
TQID: https://experienceleague.adobe.com/sWnFMRl-gpHawYrXU3POsKo2V2OrO9DmiYKvo0oyN3g
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
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
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
subfeature_v2:
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
    internal-label: Smart Lists
  - id: efc9a24a-a6a4-449d-a3e6-44f6c74dfd46
    internal-label: Adobe Identity Management
topic_v2:
  - id: c7d04a2c-412a-4c9d-9d7a-4456eaa5adeb
    internal-label: Governance
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Release Notes: January 2022 {#release-notes-jan-22}

The following features are included in the January '22 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will start to be released on **January 21, 2022**, with a phased rollout of every feature over the following weeks (unless specified otherwise).

## Next-Generation Experience {#modern-ux}

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

## [!DNL Sales Insight] {#sales-insight}

![(star)](assets/yellow-star.png)

**[!DNL Sales Insight] for [!DNL Salesforce] CRM**

* **New Type Column for [!UICONTROL Best Bets]**: Sellers will get quicker insights with a new column labeled “Type” to differentiate between leads and contacts on the [!UICONTROL Best Bets] page.

* **[!DNL Salesforce] Platform API Update**: In response to [!DNL Salesforce] retiring [!DNL Salesforce] Platform API versions 21.0 through 30.0, the [!DNL Sales Insight] package has been updated with the latest APIs.

* **Updated Branding**: All [!DNL Sales Insight] pages are being updated to align with Adobe branding.

**[!DNL Sales Insight] for [!DNL Microsoft Dynamics]**

* **Updated Account Layout**: Sellers can get a collective view of the top activities such as: email activities, web activities, interesting moments, and score changes for all contacts within an account.

## [!DNL Sales Connect] {#sales-connect}

![(star)](assets/yellow-star.png)

* **Call Outcomes and Reasons**: Understand and track your sales teams’ outbound efforts in more detail with new, fully customizable call outcome and call reason options. In addition to these new fields, we are introducing new governance to enforce call reason and outcome selection while sellers are making calls, new governance to enable or disable call reasons and outcomes, and a new Call Reason and Call Outcome [!DNL Salesforce] Activity custom field for logging data to [!DNL Salesforce]. [Click here](https://nation.marketo.com/t5/product-blogs/sales-connect-enhancements-to-call-outcomes-q1-22-release/ba-p/319812) to learn more.

* **[!DNL Salesforce] Activity Detail Customization**: Capture more sales activity and task data in [!DNL Salesforce] by customizing what information is added to the [!DNL Salesforce] task subject field when a sales activity is logged to [!DNL Salesforce] from [!DNL Sales Connect]. [Click here](https://nation.marketo.com/t5/product-blogs/sales-connect-enahncements-to-activity-logging-to-salesforce-q1/ba-p/319819) to learn more.

## Announcements {#announcements}

* **Marketo Sky Deprecation**: In March, Marketo Sky will no longer be available as we focus our resources on delivering the next-generation user experience. In an effort to maintain access to functionality that is exclusive to Marketo Sky today, we are bringing Asset Expiration and Smart Campaign Priority Override into the mainstream experience in March. [Click here](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33) to learn more.

* **Form Endpoints Deprecation**: Unsupported programmatic form POSTs to the leadCapture/save2 endpoint will be rejected by Marketo Engage forms. [Click here](https://nation.marketo.com/t5/product-documents/updated-october-2021-upcoming-changes-to-the-marketo-engage-form/ta-p/306631) to learn more.

* **Login in Invite User Dialog**: In March, the existing, optional feature “Login in Invite User Dialog” will be deprecated. The feature “[!UICONTROL Login in Invite User Dialog]” functionality is overridden by the Universal ID feature, which is required for the upcoming Adobe Identity Management System Integration and was enabled in August 2021 on all subscriptions. As a result of the deprecation, Marketo Engage will enforce only one user to be associated per email address within a subscription.

**Marketo Engage Domains – [!DNL Sales Insight] Configuration**: For Marketo Engage domains which do not have SSL cert provisioned and https://, calls will fail with an SSL handshake error. Therefore, these domains are going to be sunset. As a result, [!DNL Sales Insight] users with an older configuration pointing to any of these domains might run into system callout errors on their Lead, Contact, Account, Opportunity Panels, or Marketo Global page. We recommend you update your [Marketo Engage configuration](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md) in [!DNL Salesforce] if you run into this error. You only need to update Marketo Engage credentials highlighted in the "[!DNL Marketo Sales Insight] Config" section of the document.

**_Product Release Webinar_**

[January 2022 Marketo Engage Release Webinar](https://engage.marketo.com/2022_January_Release_Webinar_DemandPage.html)
