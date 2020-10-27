---
unique-page-id: 2360358
description: Restrict User Login to SSO Only - Marketo Docs - Product Documentation
title: Restrict User Login to SSO Only
---

# Restrict User Login to SSO Only {#restrict-user-login-to-sso-only}

If you're [using SSO](add-single-sign-on-to-a-portal.md) and want to ensure users cannot bypass the SSO security, follow these instructions.

>[!NOTE]
>
>**Admin Permissions Required**

1. Go to Admin and click Login Settings.

![](assets/image2014-9-24-14-3a44-3a40.png)

1. Click Edit Security Settings.

   ![](assets/image2014-9-24-14-3a44-3a53.png)

1. Expand the advanced settings, check Require SSO, and click Save.

![](assets/image2014-9-24-14-3a45-3a6.png)

>[!TIP]
>
>If you select **Require SSO**, you can exclude a [user role](../../../product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) from this restriction by checking the **Bypass Single Sign-On** option while setting up the role. This will allow users to sign in normally. For example, Admin users may still need to log into Marketo through the login screen.

>[!CAUTION]
>
>When new users are invited, they receive invite emails. However, if **Require SSO** is selected, they won't receive these emails, unless they are assigned to a role which is set to **Bypass Single Sign-On**.

That's it! Now all users (except users with permission to bypass single sign-on) will be restricted to using SSO login only. 