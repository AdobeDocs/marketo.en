---
description: Overview - Marketo Docs - Product Documentation
title: Overview
hide: yes
hidefromtoc: yes
---
# Overview {#overview}

If your Adobe Marketo Engage subscription was provisioned on or after 10/4/21, it will come integrated with the Adobe Identity Management System. AIMS allows users to sign in to Marketo Engage and other Experience Cloud applications using a common Adobe Identity.

## Profile Levels

There are three profile levels.

<table>
 <tr>
  <td><strong>System Admin</strong></td>
  <td>Responsible for setting up identity concepts for the Adobe org and the Marketo Engage product in the Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Product Admin</strong></td>
  <td>Responsible for entitling users for the Marketo Engage product in the Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>User</strong></td>
  <td>A person who has been given access to Marketo Engage. No Administrative privileges.</td>
 </tr>
</table>

## FAQ

**What is Adobe Identity?**

Adobe Identity Management System consists of three components.

* Adobe Identity Service: Handles authentication and validation of the end-user, including federation and runtime Single-Sign-On (SSO).

* Adobe Admin Console: The Admin Console provides a central location for managing Adobe entitlements across your entire organization. It handles user management, cloud service, desktop license entitlement, federation configuration, and provides data loss prevention security features.

* Adobe User Management API (UMAPI): Allows organizations to manage enterprise users and entitlements in the Adobe Admin Console at the API level.

**What's the difference between an Adobe Product Admin and a Marketo Engage Admin?**

* Adobe Product Admin is a new role in the Marketo platform.  
* It is a read-only role and can't be edited or deleted from Marketo.  
* It has the same rights and privileges as standard Marketo Admin.

**Is there any change in API client support?**

Yes. Those who've been onboarded to Adobe IMS cannot utilize the existing Marketo User Management APIs. They would use the [IMS APIs](https://www.adobe.io/apis/experienceplatform/umapi-new.html).

**Who do we contact for support?**

You would follow the standard procedure for contacting [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support).

**Are Marketo user roles (within workspaces) managed in Adobe Admin Console?**

No. User Role management (within workspaces) is completed in Marketo.

**I'm a Marketo Admin and don't have access to the Admin Console. How do I gain access?**

Any system or product administrator that has access to your organization's Admin Console can give you access. If you're not sure who in your organization has admin privileges in the console, contact [Adobe Customer Care](https://helpx.adobe.com/contact.html).

**How would an Admin add users to Marketo Sales Connect?**

While there will be a product card in AC for Sales Connect, AC should not be used to add/manage users. The following link will allow Admins to manage users via Marketo Sales Connect: [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management).

**Where can I learn more about the Adobe Admin Console?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/enterprise/admin-guide.html).

**Do I still go to the Admin section in Marketo to make account changes?**

No, you would need to navigate to [account.adobe.com](https://account.adobe.com).

**How does this work with Marketo's Universal ID?**

Those onboarded to Adobe identity can access all IMS-enabled subscriptions seamlessly via the subscription switcher in the product.

**Does this work with SSO?**

Yes. Marketo integration with Adobe IMS supports Universal ID users and SSO. SSO is now driven by Adobe IMS and is set up at the organization level in the Adobe Admin Console. [Learn more here](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

**How does device authorization work?**

Adobe IMS does not currently support anything like Marketo’s device authorization feature.

**Is it still possible to use the "Login in Invite User Dialog" feature, to make the login unique from our email?**

No. The User Invite workflow is no longer active when a subscription is IMS-enabled, so the feature is no longer valid. Adobe identity requires a user’s identity to be driven by their email.

**For Adobe IMS, do we have the option to use Adobe ID, Enterprise ID, or Federated ID?**

Yes, you determine the type of identity to have your organization support. More info [here](https://helpx.adobe.com/enterprise/using/identity.html) and [here](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

>[!MORELIKETHIS]
>
>* [Admin Setup](/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md)
>* [Add or Remove a Product Admin](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-product-admin.md)
>* [Add or Remove a User](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md)