---
unique-page-id: 2360358
description: Restrict User Login to SSO Only - Marketo Docs - Product Documentation
title: Restrict User Login to SSO Only
exl-id: 74915871-dcf5-478d-a5ae-b20c3d2de553
---
# Restrict User Login to SSO Only {#restrict-user-login-to-sso-only}

If you're [using SSO](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) and want to ensure users cannot bypass the SSO security, follow these instructions.

>[!IMPORTANT]
>
>This article does not apply to [Adobe IMS-enabled](/help/marketo/product-docs/administration/marketo-with-adobe-identity/overview.md) Marketo subscriptions.

>[!NOTE]
>
>**Admin Permissions Required**

1. Go to **Admin** and click **Login Settings**.

   ![](assets/image2014-9-24-14-3a44-3a40.png)

1. Click **Edit Security Settings**.

   ![](assets/image2014-9-24-14-3a44-3a53.png)

1. Expand the Advanced settings, check **Require SSO**, and click **Save**.

![](assets/image2014-9-24-14-3a45-3a6.png)

>[!NOTE]
>
>Best practice is for the user(s) to be invited and accept the invite. _After_ the invite is accepted, Admins should then set them to "Require SSO."

>[!TIP]
>
>If you select **Require SSO**, you can exclude a [user role](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) from this restriction by checking the **Bypass Single Sign-On** option while setting up the role. This will allow users to sign in normally. For example, Admin users may still need to log into Marketo through the login screen.

>[!CAUTION]
>
>When new users are invited, they receive invite emails. However, if **Require SSO** is selected, they won't receive these emails, unless they are assigned to a role which is set to **Bypass Single Sign-On**.

That's it! Now all users (except users with permission to bypass single sign-on) will be restricted to using SSO login only.

>[!MORELIKETHIS]
>
>* [Add Single Sign-On to a Portal](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [Using a Universal ID for Subscription Login](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [Inviting Marketo Users to Two Instances with Universal ID](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)
