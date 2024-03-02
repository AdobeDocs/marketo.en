---
description: Understanding Marketo Subscription and User Migration to the Adobe Admin Console - Marketo Docs - Product Documentation
title: Understanding Marketo Subscription and User Migration to the Adobe Admin Console
exl-id: 91e7b56b-2563-4986-a55c-f9760ea88b05
feature: Marketo with Adobe Identity
---
# Understanding Marketo Subscription and User Migration to the Adobe Admin Console {#understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console}

Adobe is enhancing how you manage your Adobe Marketo Engage subscriptions and users, bringing increased productivity to you and your organization. As part of this change, Adobe is migrating your Marketo Engage subscriptions and users to the Adobe Admin Console. This is a necessary migration and will not affect any marketing workflow, content, integrations, or assets.

Learn how you can use the Adobe Admin Console to manage your Adobe entitlements across your entire organization with the [Enterprise and Teams Admin Guide](https://helpx.adobe.com/enterprise/admin-guide.html){target="_blank"}. 

## What is Changing? {#what-is-changing}

As part of the migration, your subscription and user management will move from within the Marketo application to the Adobe Admin Console.

* **System Admins will manage subscriptions on Adobe Admin Console**. See all your Adobe products in one console.  

* **Product Admins will manage users and their access on Adobe Admin Console**. Add and remove users for all your Adobe subscriptions.

* **Users will sign in with Adobe Identity**. Adobe will migrate existing users to the Adobe Admin Console. Users will sign in to their Marketo subscriptions using their new Adobe Identity - either an Adobe ID or Adobe Federated ID (SSO).

* **There is no change to how you manage all other functionality** within the Marketo Engage application itself, including management of features, user roles, workspaces, functionality, and behavior.

## Migration Journey Timeline {#migration-journey-timeline}

Adobe will migrate your Marketo Engage subscription(s) to the Adobe Admin Console first, then migrate all existing users with verified email addresses. If you're a System Admin or Marketo Product Admin, you'll receive emails guiding you through the migration journey. Here's a timeline of what you can expect:

### Subscription Migration Complete {#subscription-migration-complete}

System Admins will receive an email when subscription migration to Adobe Admin Console is complete.

System Admins may need to complete some required steps before user migration starts to minimize impact to Marketo users:

* If your Marketo users currently log in with SSO, you'll be required to set up SSO on the Adobe Admin Console so your users can continue logging in with SSO. If your Marketo users do not currently utilize SSO, but you would like to set it up on Adobe Admin Console, you can do so at this point in the migration journey.

* If you already manage other Adobe products in your Adobe Admin Console, Adobe may seek your consent to automatically migrate users to your existing console. Click the "Get Started" button in the email to navigate to the consent page.

There is no change to user management at this time. Although Marketo products appear in the Admin Console, Marketo Admins will continue to manage users in the Marketo Admin area, and users will continue to log in with their Marketo Identity until their user migration is complete. During this time, Marketo products cannot be administered in Admin Console until user migration begins. This includes the Dynamic Chat instance associated with the subscription. 

>[!NOTE]
>
>If you do not currently use SSO but are thinking about implementing it, we suggest to do so before user migration occurs. If you want to implement Single Sign On and your subscription has been onboarded to Adobe Identity without SSO implemented in the Adobe Org, please submit a ticket to [Marketo Support](https://nation.marketo.com/){target="_blank"} and specify the topic as "Marketo on Admin Console, implementing SSO."

### Schedule User Migration {#schedule-user-migration}

After your System Admin completes the prerequisites outlined in the previous section, Adobe will automatically schedule your user migration 30 days ahead and communicate with Marketo Product Admins to manage the user migration.

Marketo Product Admins will:

* Receive an email with their scheduled User Migration Start Date 30 days ahead.

* Gain access to the Marketo Migration Console, located within the Marketo Admin area, where they have the option to change a subscription's migration date.

>[!NOTE]
>
>Due to the complexity of the migration, date changes are restricted to no more than 30 days beyond the scheduled date. Send an email to `marketocares@marketo.com` if you require a later date.

* See a banner in My Marketo displaying a countdown to the User Migration Start Date.

* Receive a reminder email the day before the User Migration Start Date.

### Prepare Users for Migration Day {#prepare-users-for-migration-day}

As a Marketo Product Admin, you're encouraged to ensure all users are prepared for migration day.

* Check [email verification](/help/marketo/product-docs/administration/users-and-roles/email-verification.md){target="_blank"} status for all users in the Marketo Admin area. Encourage users who have not verified their email address to do so, and help users resolve any challenges in completing the verification process.

* Prepare all users for the upcoming migration to Adobe Identity.

>[!NOTE]
>
>As users migrate, they will receive an email from Adobe notifying them of the change to the way they log in to Marketo. Users will be invited to accept an invitation to sign in using Adobe Identity for the first time, either by signing in with an existing Adobe ID or by setting up a new one using the same email address.

>[!IMPORTANT]
>
>If a Marketo Engage user does not verify their email address, they won't be migrated to an Adobe ID and will lose access to the Marketo subscription after the migration for the subscription is complete. To regain access, a Marketo product admin would need to add them as a new user.

### What to Expect on Migration Day {#what-to-expect-on-migration-day}

All Marketo subscriptions with a U.S. timezone will be migrated starting at midnight, Pacific Standard Time, of the migration start date. User migration for all other subscriptions will begin at midnight of the subscription's specified timezone.

**Adobe will automatically migrate Marketo Admins first**. When Marketo Admins are migrated to Adobe Identity, they will be assigned the Adobe Product Admin role within the Marketo application along with any other roles they previously had.

**If your Marketo subscription has less than 75 users and does not have SSO in Marketo and/or your Adobe Org**, Adobe will automatically migrate the rest of your users. This workflow aims to deliver the highest level of automation to minimize overhead for Adobe Marketo users. No action on your part is required to execute the migration.

**If your Marketo subscription has over 75 users or has SSO in Marketo and/or your Adobe Org**, Marketo Product Admins will gain access to the Self-Service User Migration area of the Marketo Migration Console, located in the Marketo Admin Area. For those who need greater control during the user migration process, Marketo Product Admins will be able to begin selecting users to migrate in batches or all at one time. Once users are selected, Admins have the option to "Migrate Now" or "Schedule Migration" for a later date, giving Admins ultimate flexibility and control over which users are migrated when.

>[!NOTE]
>
>There will be no loss of access to the product during user migration. If a user is logged in during the time their user is being migrated, the user will be logged out and be prompted to log back in within minutes using Adobe Identity after the migration is complete.

As users are migrated, they will receive an email from Adobe notifying them of the change to the way they sign in to Marketo. Users will be invited to accept an invitation to sign in using Adobe Identity for the first time, either by signing in with an existing Adobe ID or by setting up a new Adobe ID using the same email address. 

More information can be found in [Migrating to Adobe Identity](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}, [User Sign-in with Adobe](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"}, and [Adobe Identity Management FAQ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}.

## User Migration Complete {#user-migration-complete}

Adobe will notify all System Admins and Product Admins via email once all Admins and users are migrated. At this time, all Marketo users for that subscription will sign in to Marketo using Adobe Identity, and Product Admins will manage users only on Adobe Admin Console.

## Get Support {#get-support}

For additional support regarding your subscription or user migration, email `marketocares@marketo.com`.

>[!MORELIKETHIS]
>
>* [Migrating to Adobe Identity](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}
>* [User Sign-in with Adobe](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"} 
>* [Adobe Identity Management FAQ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}
