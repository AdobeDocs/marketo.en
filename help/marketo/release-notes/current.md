---
description: Current Release Notes - Marketo Docs - Product Documentation
title: Current Release Notes
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
---
# Release Notes: August 2021 {#release-notes-aug-21}

The following features are included in the August '21 release. Check your Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![](assets/yellow-star.png)) are paid add-ons. Please contact your Adobe Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will be released on **August 20, 2021**.

## Experience Automation {#experience-automation}

* **Marketo Engage User Authentication via Adobe Identity**: Beginning September 2021, new Marketo Engage users with Enterprise packages will be onboarded using Adobe ID user credentials. Migration of current users to the integrated identity system will not occur until mid-2022 and no action is required until further notice. Adobe identity user authentication allows IT/Security admins to manage multiple Marketo Engage product instances along with other Experience Cloud solutions, as well as configuring SSO through a common console. Admins can conveniently manage user groups and user entitlements in one place.

* **Executable Campaign Nesting**: Executable campaigns may now also call other executable campaigns allowing you to nest them up to three levels deep. This enables further consolidation of common operational flows and improves Smart Campaign management.

* **Single Flow Action in Person Detail Page** (Available by September 9): Execute flow actions like sending email, change person owner, or any other smart campaign action on individual people from the person detail page using the flow action menu without switching to the database grid view.

* **[Custom Activities Export](/help/marketo/product-docs/administration/marketo-custom-activities/custom-activity-metadata-export.md)**: Metadata export now supports all objects and respective metadata which can be used to share, analyze and design your subscription data model.

## API Enhancements {#api-enhancements}

* **Submit Form API**: When an email address is duplicated in two or more Lead records, we update “last updated” record instead of skipping altogether. Provides parity with Forms 2.0 API.

* **Email API**: Retrieve champion or challenger email assets. Retrieve email assets using date range filter.

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

## Sales Insight {#sales-insight}

![(star)](assets/yellow-star.png)

* **Enhanced visibility into Lead, Contact, Account & Opportunity Activities for Salesforce CRM Users**: Engagement with prospects during long sales cycles is more informed due to an increased number of engagement records in Sales Insight. Interesting moments, web activity, email, and score tabs show up to 400 activities across Lead, Contact, Account, and Opportunity objects.  

## Sales Connect {#sales-connect}

![(star)](assets/yellow-star.png)

* **Email Connection Throttling (Beta)**: Improve email deliverability and scale personalized sales communication with the email connection throttling for Sales Connect. This new technology automatically manages email send timing to create seamless experiences for Exchange and Gmail users. Decrease or eliminate the usage of third-party bulk email send applications and send all your emails from Sales Connect with confidence.

>[!NOTE]
>
>Email throttling is available in Beta now. [Learn more](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

* **Enhanced Sales Activity Insights**: Capture and activate personalized engagement based on your sales team’s prior activities. New attributes such as Sales Call Recording Link, Sales Campaign Name, and Sales Email Subject can be used in Marketo Engage smart lists.  These activities can be exported and reported through the Marketo Engage REST API or Bulk Export and are available on filters and triggers as additional constraints for smart lists.  

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Bizible LinkedIn Lead Gen Forms Integration**: Marketers can now perform revenue attribution on conversions that occur when LinkedIn captures form fills through their Lead Gen Forms ad units. These insights can then be used to optimize form performance and paid media investments. LinkedIn Lead Gen Forms are one of LinkedIn’s fastest-growing paid media offerings and this new capability is included with our existing LinkedIn Ads integration with Bizible.  
  
* **Improved Velocity Dashboard**: We have added a new velocity metric and dashboard filter for deeper insights. This dashboard is used by marketers to understand stage-by-stage lead and opportunity velocity and the efficiency of different forms of marketing and sales engagement.

* **New Cohort Waterfall Journey Dashboard**: This will enable marketers to view the progression of a selected cohort through a classic “demand waterfall” set of stages, providing a quick understanding of conversion rates and implied stage conversion causality on a stage-by-stage basis.

## Bizible Integration with Adobe Experience Cloud {#bizible-integration-with-adobe-experience-cloud}

This section includes new features for Bizible users that have completed their Adobe Identity Management System (IMS) migration. If you have been migrated, you’ll see your new Adobe ID in Bizible Settings under the Adobe ID tab. All accounts should be migrated by the end of 2021.

* **Bizible Integration with Adobe Privacy Service** (available September 2021): Bizible’s integration with the Adobe Privacy Service centralizes compliance with critical data privacy regulations (such as GDPR) across Adobe Experience Cloud applications. You can now take advantage of this service and manage all privacy requests centrally so that change requests coming into Bizible and other Adobe products are reflected across applications.

* **Bizible on Adobe Unified Shell**: Bizible’s adoption of Adobe Unified Shell gives users new capabilities that will appear in the Bizible application header bar and include better access to support resources and application switching. Adobe Unified Shell helps create a consistent experience between Bizible and other Adobe Experience Cloud applications.

* **Bizible Domain Ownership and Self-Management**: Bizible users can leverage Adobe Admin Console to manage the domains they want Bizible to track. This brings self-service to a previously manual process and provides a consistent experience in how domain ownership and tracking are managed across Adobe Experience Cloud applications.

## Announcements {#announcements}

* **Update to Subscription Universal ID Settings**: To support the upcoming Marketo Engage and Adobe Identity integration for existing users, all Marketo Engage subscriptions will be unified in the enablement of Universal ID support.
