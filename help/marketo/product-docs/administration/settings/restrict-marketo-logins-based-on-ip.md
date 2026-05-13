---
unique-page-id: 2360297
description: Learn how to allow or block Marketo logins by IP address.
title: Restrict Marketo Logins Based on IP
exl-id: 5d9d0b88-b4bc-4e1b-b70c-2c2e7b4269f5
feature: Administration
TQID: https://experienceleague.adobe.com/05hhFeXOdOg2zw9ioSV3kVI9DbDscpjx-s9SKYVDzv0
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Restrict Marketo Logins Based on IP {#restrict-marketo-logins-based-on-ip}

You can restrict or enable users from accessing Marketo based on their IP addresses. Follow the steps below.

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

1. Choose whether you want to **Allow** or **Block** specific addresses, enter one or more addresses, then click **[!UICONTROL Save]**.

   >[!NOTE]
   >
   >**Definition**
   >
   >* **[!UICONTROL Allowed IP addresses]**: Adding allowed IP addresses is inclusionary. It will include all of the IP addresses specified and exclude everything else.
   >* **[!UICONTROL Block IP addresses]**: Prevents specific IPs from accessing Marketo.
   >* **[!UICONTROL Disable IP Restrictions]**: Checking this will stop any/all restriction rules from working. Use this for testing purposes.

   >[!NOTE]
   >
   >You can add multiple restrictions, but they can only be ALL allowed or ALL blocked. You cannot combine allowed and blocked addresses.

   ![](assets/restrict-marketo-logins-based-on-ip-4.png)
