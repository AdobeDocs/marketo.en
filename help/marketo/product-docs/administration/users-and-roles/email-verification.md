---
description: Email Verification - Marketo Docs - Product Documentation
title: Email Verification
exl-id: 976e46a7-8c85-45ed-86c1-0c5cdb2d5c3e
---
# Email Verification {#email-verification}

Adobe Marketo Engage subscriptions require all non-API only users, including Marketo Engage Administrators, to verify their email address. Single Sign-on (SSO) users who are not assigned an Admin role, or who are assigned a role with the 'Bypass SSO' permission, will automatically have their email verified when their subscription is enabled with the Email Verification feature.

## User Invite {#user-invite}

When an Admin invites a user, that user is automatically verified once they click the invite link. SSO users, not assigned the Admin role, are automatically verified.

## Changing an Email Address {#changing-an-email-address}

When a user's email address is changed, it becomes unverified. An email will be sent to them allowing them to re-verify. Users can manually resend that email by clicking **Resend Verification**.

   ![](assets/email-verification-1.png)

   ![](assets/email-verification-2.png)

## Users and Roles {#users-and-roles}

In **Admin** > **Users & Roles**, the Email Status column shows the verification status of every user.

   ![](assets/email-verification-3.png)

## Multiple User Login IDs {#multiple-user-login-ids}

Only one user account can be associated with a single email address. If there are multiple user accounts associated with a single email address, Marketo Engage will require the conflict to be resolved and display all user logins associated with the email address, as well as three resolution options:<p>
`1` Use the current email for the current User Login ID<p>
`2` Use a new email for the current User Login ID<p>
`3` Delay the decision until next login

   ![](assets/email-verification-4.png)

## Verification Email {#verification-email}

Invited users will receive the following email:

   ![](assets/email-verification-5.png)

>[!NOTE]
>
>To resend a verification email to an unverified user, simply select their record and click the **Verify Email** button.
