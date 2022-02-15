---
description: Overview - Marketo Docs - Product Documentation
title: Overview
hide: yes
hidefromtoc: yes
exl-id: 18ddeebc-bc89-411c-9d2c-23df6841cb3a
---
# Overview {#overview}

If you have a new account with Adobe Marketo Engage (new account, not just a new instance for an existing account)
as of Feb 15, 2022, it may come integrated with the Adobe Identity Management System, depending on the product package purchased. To find out if you have it, please contact your Marketo Admin or your account's Customer Success Manager.

Existing Marketo subscriptions will be migrated to the Adobe Identity Management System beginning later this year.

>[!NOTE]
>
>Marketo Support will not be able to provide any updates regarding Adobe IMS migration. Your Customer Success Manager will reach out with the estimated timeline in the coming months.

## Profile Levels

Adobe Marketo Engage subscriptions onboarded to the Adobe Identity Management System supports various profiles. The following are the types of user profiles relevant in this integration.

<table>
 <tr>
  <td><strong>Adobe Admin Console System Admin</strong></td>
  <td>Responsible for setting up identity concepts for the Adobe org and the Marketo Engage product in the Adobe Admin Console. Granted role at Adobe organization setup.</td>
 </tr>
 <tr>
  <td><strong>Adobe Admin Console Product Admin</strong></td>
  <td>Responsible for entitling users for the Marketo Engage product in the Adobe Admin Console. Granted role in Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage Product Admin</strong></td>
  <td>A person who has been given access to Marketo Engage with Administrative privileges. Granted role in Marketo Engage, not Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage User</strong></td>
  <td>A person who has been given access to Marketo Engage. No Administrative privileges.</td>
 </tr>
</table>

## FAQ

**What is Adobe Identity?**

Adobe Identity Management System consists of three components.

* Adobe Identity Service: Handles authentication and validation of the end-user, including federation and runtime Single-Sign-On (SSO).

* Adobe Admin Console: The Admin Console provides a central location for managing Adobe entitlements across your entire organization. It handles user management, cloud service, desktop license entitlement, federation configuration, and provides data loss prevention security features.

* Adobe User Management API (UMAPI): Allows organizations to manage enterprise users and entitlements in the Adobe Admin Console at the API level.

**When will existing Marketo Engage subscriptions be integrated with IMS?**

Existing Marketo subscriptions will be migrated to the Adobe Identity Management System later this year. Marketo Support will not be able to provide any updates regarding Adobe IMS migration. Your Customer Success Manager will reach out with the estimated timeline in the coming months.

**What's the difference between an Adobe Product Admin and a Marketo Engage Admin?**

* Adobe Product Admin is a new role in the Marketo platform.
* Adobe Product Admin role is granted to users added as a Product Admin in Adobe Admin Console
* Adobe Product Admin is a read-only role and can't be edited or deleted from Marketo Engage.  
* Adobe Product Admin has the same rights and privileges as a standard Marketo Admin.
* Marketo Engage Admin’s role is still an Admin and is granted to a user in Marketo Engage.

**Is there any change in User Management API client support?**

Yes. Those who've been onboarded to Adobe IMS cannot utilize all the existing Marketo User Management APIs. For user invite, update, and deletion actions, the Adobe [IMS APIs](https://www.adobe.io/apis/experienceplatform/umapi-new.html) should be used. For role management, the Marketo User Management APIs still apply. Beyond this there are no other changes to Marketo REST API client support.

**Who do we contact for support if we are integrated with IMS?**

You would follow the standard procedure for contacting [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support).

**Are Marketo user roles (within workspaces) managed in Adobe Admin Console?**

No. User Role management (within workspaces) is completed in Marketo Engage.

**I'm a Marketo Admin in an IMS integrated subscription and don't have access to the Admin Console. How do I gain access?**

Any Adobe System or Product Admin that has access to your organization's Admin Console can give you access. If you're not sure who in your organization has admin privileges in the console, contact [Adobe Customer Care](https://helpx.adobe.com/contact.html).

**How would an Admin add users to Marketo Sales Connect?**

While there will be a product card in Admin Console for Sales Connect, Admin Console should not be used to add/manage users. The following link will allow Admins to manage users via Marketo Sales Connect: [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management).

**Where can I learn more about the Adobe Admin Console?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/enterprise/admin-guide.html).

**Do I still go to the Admin section in Marketo to make user account changes for my account?**

No, you would need to navigate to [account.adobe.com](https://account.adobe.com).

**How does this work with Marketo's Universal ID?**

Those onboarded to Adobe identity can access all IMS-enabled subscriptions seamlessly via the subscription switcher in the product.

**Does this work with SSO?**

Yes. Marketo integration with Adobe IMS supports Universal ID users and SSO. SSO is now driven by Adobe IMS and is set up at the organization level in the Adobe Admin Console. [Learn more here](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

**How does device authorization work?**

Adobe IMS does not currently support anything like Marketo’s device authorization feature.

**Is it still possible to use the "Login in Invite User Dialog" feature, to make a user's login unique from their email?**

No. The User Invite workflow is no longer active when a subscription is IMS-enabled, so the feature is no longer valid. Adobe identity requires a user’s identity to be driven by their email.

**For Adobe IMS, do we have the option to use Adobe ID, Enterprise ID, or Federated ID?**

Yes, you determine the type of identity to have your organization support. More info can be found here: [Identity Overview](https://helpx.adobe.com/enterprise/using/identity.html) and here: [Set up Identity](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

>[!MORELIKETHIS]
>
>* [Admin Setup](/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md)
>* [Add or Remove a Product Admin](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-product-admin.md)
>* [Add or Remove a User](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md)
