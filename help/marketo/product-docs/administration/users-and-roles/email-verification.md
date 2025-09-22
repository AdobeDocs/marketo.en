---
description: "Email Verification - Marketo Docs - Product Documentation"
title: Email Verification
exl-id: 976e46a7-8c85-45ed-86c1-0c5cdb2d5c3e
feature: Users and Roles
---
# Email Verification {#email-verification}

Adobe Marketo Engage subscriptions require all non-API only users, including Marketo Engage Administrators, to verify their email address.

## Why This Feature Was Introduced {#why-this-feature-was-introduced}

Marketo Engage is continuing the rollout of Email Verification in preparation for migrating customers to the Adobe Business Platform, including user migration to Adobe IDs. This feature enhances the security of existing Marketo Engage user accounts. To ensure a Marketo Engage user is associated with the proper Adobe ID, existing Marketo Engage users must verify their email address. A Marketo Engage user must have a verified email address to be migrated to an Adobe ID. If a Marketo Engage user does not verify their email address, they cannot be migrated to an Adobe ID and will lose access to a Marketo subscription after the user migration for the subscription is complete.

## User Invite {#user-invite}

When an Admin invites a user, that user is automatically verified once they click the invite link.

>[!IMPORTANT]
>
>The exception to the above is, _in an SSO-only subscription_, Admins will receive a new user invitation, but non-Admin users will not. Users who are not Admins must still go through the email verification process to ensure migration of their records. Users can send themselves the email verification link by clicking their "My Profile" icon and navigating to **My Account** > **Account Settings** > **Resend Verification**.

   ![](assets/email-verification-1.png)

## Verification Email {#verification-email}

Users will receive the email below when email verification is activated for a subscription, or if it's triggered by an Admin/user.

An active user session is required for Email Verification success. The user must first sign in to their Marketo subscription using their Identity Provider (IdP) url. Once a session is established, they would _then_ click the **Verify email address** link in the email.

   ![](assets/email-verification-2.png)

>[!TIP]
>
>To resend a verification email to an unverified user, simply select their record and click the **[!UICONTROL Verify Email]** button.

## Changing an Email Address {#changing-an-email-address}

When a user's email address is changed, it becomes unverified. An email will be sent to them allowing them to re-verify. Users can manually resend that email by clicking **[!UICONTROL Resend Verification]**.

   ![](assets/email-verification-3.png)

   ![](assets/email-verification-4.png)

## Users and Roles {#users-and-roles}

In **[!UICONTROL Admin]** > **[!UICONTROL Users & Roles]**, the Email Status column shows the verification status of every user.

   ![](assets/email-verification-5.png)

## Multiple User Login IDs {#multiple-user-login-ids}

Only one user account can be associated with a single email address. If there are multiple user accounts associated with a single email address, Marketo Engage will require the conflict to be resolved and display all user logins associated with the email address, as well as three resolution options:

* Use the current email for the current User Login ID
* Use a new email for the current User Login ID
* Delay the decision until next login

   ![](assets/email-verification-6.png)

>[!NOTE]
>
>While a user account has to be associated with a single address, a user account can be used across many subscriptions via Universal ID.
