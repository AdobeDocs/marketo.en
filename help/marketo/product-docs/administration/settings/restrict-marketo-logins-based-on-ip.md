---
unique-page-id: 2360297
description: "Restrict Marketo Logins Based on IP - Marketo Docs - Product Documentation"
title: Restrict Marketo Logins Based on IP
exl-id: 5d9d0b88-b4bc-4e1b-b70c-2c2e7b4269f5
feature: Administration
---
# Restrict Marketo Logins Based on IP {#restrict-marketo-logins-based-on-ip}

You can restrict or enable users from accessing Marketo based on their IP addresses. Here's how.

>[!NOTE]
>
>**Admin Permissions Required**

>[!IMPORTANT]
>
>Adobe Admin Console (AAC) supports [IP-based access control](https://helpx.adobe.com/enterprise/using/ip-based-access.html){target="_blank"}. To ensure a smooth transition, existing Marketo Engage IP restrictions will be active including Adobe ID users through Q1 2027 in subscriptions where this feature is enabled.
>
>* You can configure AAC IP-based access anytime.
>* Both AAC and Marketo Engage restrictions can run simultaneously. Use the same IP allow list for compatibility.
>
>After Q1 2027, Marketo Engage IP restrictions will be retired. IP-based access will be managed exclusively through AAC and must be configured to enforce login restrictions. A final transition date will be announced later.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/restrict-marketo-logins-based-on-ip-1.png)

1. Click **[!UICONTROL Login Settings]**.

   ![](assets/restrict-marketo-logins-based-on-ip-2.png)

1. Click **[!UICONTROL Edit IP Restrictions]**.

   ![](assets/restrict-marketo-logins-based-on-ip-3.png)

1. Choose whether you want to **Allow** or **Block** specific addresses, enter the address(es), then click **[!UICONTROL Save]**.

   >[!NOTE]
   >
   >**Definition**
   >
   >* **[!UICONTROL Allowed IP addresses]**: Adding allowed IP addresses is inclusionary. It will include all of the IP addresses specified and exclude everything else.
   >* **[!UICONTROL Block IP addresses]**: Prevents specific IPs from accessing Marketo.
   >* **[!UICONTROL Disable IP Restrictions]**: Checking this will stop any/all restriction rules from working. Use this for testing purposes.

   >[!NOTE]
   >
   >You can add multiple restrictions, but they can only be ALL allowed or ALL blocked. You cannot mix and match allowed and blocked.

   ![](assets/restrict-marketo-logins-based-on-ip-4.png)
