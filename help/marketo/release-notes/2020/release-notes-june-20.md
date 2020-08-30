---
unique-page-id: 37357276
description: Release Notes: June '20 - Marketo Docs - Product Documentation
title: Release Notes: June '20
---

# Release Notes: June '20 {#release-notes-june}

The following features are included in the June '20 release. Check your Marketo edition for feature availability.

>[!NOTE]
>
>**Availability**
>
>Features denoted by a star ( ![(star)](assets/star-yellow.svg)) may be paid add-ons. Please contact your Marketo Engage representative to learn more.

***Quarterly Releases*** The following features will be released on **June 5, 2020**.

## Core Marketo Engage {#core-marketo-engage}

* ** [Predictive Audiences](https://help.marketo.com/hc/en-us/articles/360045746253) ![(star)](assets/star-yellow.svg)

  **: New Smart List and Smart Campaign filters powered by Adobe Sensei allow you to create AI-powered audience segments for email, event, and webinar marketing programs. Use AI to help you segment audiences based on lead likelihood to register for an event, attend an event, or unsubscribe. Build lookalike audiences based on past programs to efficiently replicate previous success. Achieve conversion goals with predictive goal-tracking and get recommendations for how to refine your audience segments for event programs.
* **Batch Email Boost ![(star)](assets/star-yellow.svg): ** Enhancement to our email marketing capability that allows you to send up to 3 million batch emails per hour. We have re-architected our batch campaign and email report processing to enhance performance of email programs and batch email campaigns. This results in shorter lead time to send, as well as improved completion time. Set up your email sends as you normally would, there is no added complexity. This enhancement is available as a product add-on which also includes a Delivery Services Launch Pack, Email Delivery Tools, and multiple Dedicated IP addresses.
* ** [Audience Integration with Adobe Experience Cloud (AEC)](https://docs.marketo.com/x/ogI6Ag): **New Adobe Experience Cloud (AEC) integration that allows you to sync static lists of known leads from Marketo Engage with multiple AEC applications to enhance existing programs, unlock new use cases, and orchestrate multi-channel campaigns. This integration includes Adobe Analytics, Adobe Target, Adobe Experience Manager, Adobe Audience Manager and Adobe Advertising Cloud.
* ** [Program Member Custom Fields](https://docs.marketo.com/x/MQA6Ag)**: Capture and utilize custom fields about a program member. Use these new fields in your Marketo Engage forms, view them in a program’s member list, leverage them in Smart List filters and triggers, and include them in a new Smart Campaign Flow Action for enhanced automation and more granular personalization. These can also be imported and exported via the UI and APIs. Enhancement to our custom data objects and fields capability.
* **Describe Program Member**: Retrieve Program Member metadata, giving you the ability to import and export Program Member Custom Field data using REST API. Enhancement to our API*. *

* ** [Create Task in Microsoft Dynamics](https://docs.marketo.com/x/jQM6Ag)**: Create tasks for Sales inside Microsoft Dynamics using a new Flow Action based on customer behavior captured in Marketo Engage. Enhancement to our native Microsoft Dynamics CRM integration*. *

* **Get Form Used By List Asset API Endpoint**: Retrieve a list of assets that depend on a form. Enhancement to our API*.* 

* **Set Email Preheader via API**: Enable the automatic translation and localization of email preheader fields. Enhancement to our API*.*

* **Image and Files Caching**: We are enhancing the Marketo Engage server stability by serving Image and File assets from a 60-second cache.

**Account-Based Marketing ![(star)](assets/star-yellow.svg)

**

* **New Account Discovery Generally Available**

    * New Account Discovery is an enhancement to our Account Profiling capability that enables you to discover net-new target accounts for your ABM strategy based on your AI-powered ideal customer profile model. View, select, and import recommended new accounts, along with their AI-based fit and intent data indicators.

---

**

***Releasing Throughout the Quarter***

The following features are on a non-quarterly cycle and will be released throughout the coming months.
**Bizible  ![(star)](assets/star-yellow.svg)

**

* **Marketo Engage Programs Integration**: Pull program data directly from Marketo Engage to create touchpoints along the attribution journey in Bizible to appropriately credit email and engagement programs. Enhancement to our Marketo Engage integration.
* **Marketo Engage Activities Integration`<sup>BETA</sup>`**: Bring Marketo Engage activity data directly into Bizible to create touchpoints across the customer journey and all attribution models. Examples include lead score changes, interesting moments, email click, or any custom activities. Enhancement to our Marketo Engage integration.
* **Bizible B2B Customer Attributes Integration`<sup>BETA</sup>`**: This is an Adobe Experience Cloud integration with Adobe Analytics that allows you to bring select Bizible data directly into Adobe Analytics for more in-depth analysis. Examples include account-based site traffic and content analysis by company name, account attributes, CRM opportunities, and high-value individuals as defined by Bizible attributed revenue and funnel stage.
* **Bizible Discover Filters and Enhancements:** Analyze your data with channel, subchannel, campaign, and segment filters across dashboards. Strengthen data visibility with more drill-down attributes. This is an enhancement to our Discover Boards.
* **Activities Sync for Microsoft Dynamics**: Attribute sales interactions by bringing in Microsoft Dynamics CRM activities to the touchpoint journey and track events such as calls, appointments, or tasks associated with your leads or contacts. Enhancement to our Microsoft Dynamics CRM integration.

**Sales Insight ![(star)](assets/star-yellow.svg)

**

* ** [Insights Dashboard for Salesforce CRM](https://docs.marketo.com/x/EoGMAg)**: We're reimagining our Sales Insight capability with new visibility into upcoming marketing events and campaigns to give sellers the ability to make recommendations more relevant to customers and prospects based on their needs and interests. Sellers can also view both Contact and Account Activity within the timeline and easily access additional activity details. Find more details on how to upgrade your package [here](https://docs.marketo.com/x/F4GMAg).

---

## Announcements {#announcements}

* **ITP 2.1+ RTP Update**: Due to changes to the cookie policy for Safari, RTP cookies' ability to track users across sessions on the same domain will be limited by ITP to either 1 or 7 days based on the browser and browser version used by the visitor. To account for this, we are implementing a new web service to allow RTP cookies to be set with a Set-Cookie header via HTTP response. More information can be found [here](https://nation.marketo.com/t5/Knowledgebase/Browser-Cookie-Updates-How-Marketo-RTP-Is-Affected/ta-p/299603).

* **Batch Campaign Infrastructure Changes**: We are upgrading our batch campaign services throughout the remainder of this year. This will be a seamless update that will not affect any batch campaigns that are in progress and will not result in a change of behavior. No action is required. Find more details in this [Nation post](https://nation.marketo.com/t5/Product-Documents/Batch-Campaign-Processing-Infrastructure-Update/ta-p/301374).

## Deprecations {#deprecations}

* ** [Munchkin Associate Lead](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/):** Beginning with the version 159 release of Munchkin JS, a deprecation warning will be logged in the browser console when the Associate Lead method is invoked, indicating that the feature will be removed in a future release.  The full deprecation schedule will be announced at a later date.

***Product Release Webinar*** [Watch the recording](https://engage.marketo.com/June-Release-2020-On-Demand.html) of our June '20 Product Release Innovations webinar.
