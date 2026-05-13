---
description: How to customize email tracking link headers in Admin under Email, including Strict-Transport-Security for HTTPS, with IT review guidance.
title: Email Tracking Link Headers
exl-id: 2db1f1b3-3afe-4710-a8b1-b06fbf09ec8c
feature: Administration
TQID: https://experienceleague.adobe.com/myoUsAnpIvAZVY-ar4iQl9xDHr886vAH-l0YXtM1mfg
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
topic_v2:
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Email Tracking Link Headers {#email-tracking-link-headers}

Follow the steps below to customize your email tracking link headers.

1. In Marketo, click **[!UICONTROL Admin]**.

   ![](assets/email-tracking-link-headers-1.png)

1. Click **[!UICONTROL Email]**.

   ![](assets/email-tracking-link-headers-2.png)

1. Scroll down to Custom Header Options. Choose your desired settings and click **[!UICONTROL Save Changes]**.

   ![](assets/email-tracking-link-headers-3.png)

<table>
 <tr>
  <td><strong>Strict-Transport-Security</strong></td>
  <td>Use this to guarantee tracking links will always be served over HTTPS (should only be set for subscriptions with tracking links secured by SSL)</td>
 </tr>
</table>

>[!CAUTION]
>
>It is important to review these settings with your IT team to determine what your organization's policy should be set to. Incorrect settings can prevent some visitors from accessing your Email links.
