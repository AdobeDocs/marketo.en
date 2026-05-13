---
unique-page-id: 2360358
description: Require SSO for all users so they cannot bypass SSO security via Admin Login Settings (does not apply to Adobe IMS).
title: Restrict User Login to SSO Only
exl-id: 74915871-dcf5-478d-a5ae-b20c3d2de553
feature: Administration
TQID: https://experienceleague.adobe.com/2YaweRRhrf8po6RR3V64kCan8qQhDNKDrhr7TfnNNJs
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
topic_v2:
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Restrict User Login to SSO Only {#restrict-user-login-to-sso-only}

If you are [using SSO](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) and want to ensure users cannot bypass the SSO security, follow these instructions.

>[!IMPORTANT]
>
>This article does not apply to [Adobe IMS-enabled](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md) Marketo subscriptions.

>[!NOTE]
>
>**Admin Permissions Required**

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/restrict-user-login-to-sso-only-1.png)

1. Click **[!UICONTROL Login Settings]**.

   ![](assets/restrict-user-login-to-sso-only-2.png)

1. Click **[!UICONTROL Edit Security Settings]**.

   ![](assets/restrict-user-login-to-sso-only-3.png)

1. Expand the **[!UICONTROL Advanced]** settings, check **[!UICONTROL Require SSO]**, and click **[!UICONTROL Save]**.

![](assets/restrict-user-login-to-sso-only-4.png)

>[!NOTE]
>
>Best practice is for the user(s) to be invited and accept the invite. _After_ the invite is accepted, Admins should then set them to "[!UICONTROL Require SSO]."

>[!TIP]
>
>If you select **[!UICONTROL Require SSO]**, you can exclude a [user role](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) from this restriction by checking the **[!UICONTROL Bypass Single Sign-On]** option while setting up the role. This allows users to sign in normally. For example, Admin users may still need to log into Marketo through the login screen. If both SSO and Universal ID are enabled, you must have the "Bypass Single Signed On" permission set to toggle between subscriptions.

>[!CAUTION]
>
>When new users are invited, they receive invite emails. However, if **[!UICONTROL Require SSO]** is selected, they do not receive these emails, unless they are assigned to a role which is set to **[!UICONTROL Bypass Single Sign-On]**.

Now all users (except users with permission to bypass single sign-on) are restricted to using SSO login only.

>[!MORELIKETHIS]
>
>* [Add Single Sign-On to a Portal](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [Inviting Marketo Users to Two Instances with Universal ID](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)
