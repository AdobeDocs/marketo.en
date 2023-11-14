---
description: Adobe Identity Management FAQ - Marketo Docs - Product Documentation
title: Adobe Identity Management FAQ
feature: Marketo with Adobe Identity
exl-id: 2401def7-1696-4d77-a8a3-96c490517121
---
# Adobe Identity Management FAQ {#adobe-identity-management-faq}

**What is Adobe Identity?**

Adobe Identity Management System consists of three components.

* [!DNL Adobe Identity Service]: Handles authentication and validation of the end-user, including federation and runtime Single-Sign-On (SSO).

* Adobe Admin Console: The Admin Console provides a central location for managing Adobe entitlements across your entire organization. It handles user management, cloud service, desktop license entitlement, federation configuration, and provides data loss prevention security features.

* Adobe User Management API (UMAPI): Allows organizations to manage enterprise users and entitlements in the Adobe Admin Console at the API level.

**When will existing Marketo Engage subscriptions be integrated with IMS?**

Existing Marketo subscriptions will be migrated to the Adobe Identity Management System later this year. Marketo Support will not be able to provide any updates regarding Adobe IMS migration. The Adobe Account Team will reach out with the estimated timeline in the coming months.

**What's the difference between an Adobe Product Admin and a Marketo Engage Admin?**

* Adobe Product Admin is a new role in the Marketo platform.
* Adobe Product Admin role is granted to users added as a Product Admin in Adobe Admin Console
* Adobe Product Admin is a read-only role and can't be edited or deleted from Marketo Engage.  
* Adobe Product Admin has the same rights and privileges as a standard Marketo Admin.
* Marketo Engage Admin's role is still an Admin and is granted to a user in Marketo Engage.

**Is there any change in User Management API client support?**

Yes. Those who've been onboarded to Adobe IMS cannot utilize all the existing Marketo User Management APIs. For user invite, update, and deletion actions, the Adobe [IMS APIs](https://www.adobe.io/apis/experienceplatform/umapi-new.html){target="_blank"} should be used. For role management, the Marketo User Management APIs still apply. Beyond this there are no other changes to Marketo REST API client support.

**Who do we contact for support if we are integrated with IMS?**

You would follow the standard procedure for contacting [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

**If I use an Adobe Identity to access other Adobe applications, can I use that to access Marketo?**

Even if you have other Adobe products, you cannot access Marketo with Adobe Identity until the subscription is migrated to IMS.

**Are Marketo user roles (within workspaces) managed in Adobe Admin Console?**

No. User Role management (within workspaces) is completed in Marketo Engage.

**I'm a Marketo Admin in an IMS integrated subscription and don't have access to the Admin Console. How do I gain access?**

Any Adobe System or Product Admin that has access to your organization's Admin Console can give you access. If you're not sure who in your organization has admin privileges in the console, contact [Adobe Customer Care](https://helpx.adobe.com/contact.html){target="_blank"}.

**How would an Admin add users to Marketo [!DNL Sales Connect]?**

While there will be a product card in Admin Console for [!DNL Sales Connect], Admin Console should not be used to add/manage users. The following link will allow Admins to manage users via Marketo [!DNL Sales Connect]: [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management){target="_blank"}.

**Where can I learn more about the Adobe Admin Console?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/enterprise/admin-guide.html){target="_blank"}.

**Do I still go to the Admin section in Marketo to make user account changes for my account?**

No, you would need to navigate to [account.adobe.com](https://account.adobe.com){target="_blank"}.

**How does this work with Marketo's Universal ID?**

Those onboarded to Adobe identity can access all IMS-enabled subscriptions seamlessly via the subscription switcher in the product.

**Does this work with SSO?**

Yes. Marketo integration with Adobe IMS supports Universal ID users and SSO. SSO is now driven by Adobe IMS and is set up at the organization level in the Adobe Admin Console. [Learn more here](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

**How does device authorization work?**

Adobe IMS does not currently support anything like Marketo's device authorization feature.

**Is it still possible to use the "Login in Invite User Dialog" feature, to make a user's login unique from their email?**

No. The User Invite workflow is no longer active when a subscription is IMS-enabled, so the feature is no longer valid. Adobe identity requires a user's identity to be driven by their email.

**For Adobe IMS, do we have the option to use Adobe ID, Enterprise ID, or Federated ID?**

Yes, you determine the type of identity to have your organization support. More info can be found here: [Identity Overview](https://helpx.adobe.com/enterprise/using/identity.html) and here: [Set up Identity](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

**Which product cards are supported in the Adobe Admin Console?**

The supported product cards are: Marketo Engage, Marketo Measure, Marketo Dynamic Chat, Marketo Sales Connect, and Marketo Sales Insight Actions.

**What if my user login doesn't match my email when I get migrated to an Adobe Identity?**

Current Marketo users with logins different from their email address will no longer log in with that credential once migrated to an Adobe Identity. Adobe Identities always authenticate with a user's email address. 
 
**What happens after the Adobe Identity migration if my subscription uses IP restriction settings?**

When subscriptions are onboarded to Adobe Identity, IP restriction settings do not get migrated to the Adobe Admin Console. Marketo's IP restriction settings include allowing only access from specific IP addresses, and blocking specific IP addresses from access. At this time, Adobe Identity Management System does not support IP restriction features.  

Coming in 2024, Adobe Identity Management System will release a feature to support allowing only specific IP addresses, supporting a transition for Marketo users currently utilizing this feature. Those who currently use this feature will not undergo user migration until the feature is released. Once the feature is delivered, users will be notified of their migration being scheduled. More information about the feature will be provided when available. 

Users who currently use the IP restriction, blocking specific addresses from access, will no longer be able to use this feature after being migrated to Adobe Identity, as it is not supported by Adobe Identity Management System. 

**What happens after Adobe Identity migration if I have users with a role that has the option to 'Bypass Single Sign On'?**

When subscriptions are onboarded to Adobe Identity, Single Sign On (SSO) is set up at the Adobe Organization level for all users. When SSO is set up, it will be enforced for all Marketo users/all Marketo instances in that Adobe Org. Previously, Marketo supported allowing a user role to be set up to have the option to 'Bypass Single Sign On.' This is not supported by Adobe Identity Management System. 

**I have more than one subscription, but not all have Single Sign On enabled. What happens after Adobe Identity migration?**

When subscriptions are onboarded to Adobe Identity, Single Sign On (SSO) is set up at the Adobe Organization level. This means SSO applies to all product instances in the Adobe Org. When SSO is set up, it will apply to all Marketo instances in that Adobe Org. Previously, Marketo supported this setting at an instance level. That is not supported by Adobe Identity Management System.
