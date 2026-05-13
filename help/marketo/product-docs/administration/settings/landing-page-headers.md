---
description: How to customize HTTP headers for landing page domains, including Strict-Transport-Security and X-Frame-Options.
title: Landing Page Headers
exl-id: 58eaa0cd-2a2b-4abe-9180-f60a2a1dcc87
feature: Administration, Landing Pages
TQID: https://experienceleague.adobe.com/ecRuR4V-YCsesHZpm9UrP1rPlOjBCediq-9DtXZRfBo
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
# Landing Page Headers {#landing-page-headers}

Follow the steps below to customize some of the HTTP headers on your Landing Page domains.

1. In Marketo, click **[!UICONTROL Admin]**.

   ![](assets/landing-page-headers-1.png)

1. Click **[!UICONTROL Landing Pages]**.

   ![](assets/landing-page-headers-2.png)

1. Click **[!UICONTROL Edit]** next to Landing Page HTTP Headers.

   ![](assets/landing-page-headers-3.png)

1. Choose your desired settings and click **[!UICONTROL Save]** when done.

   ![](assets/landing-page-headers-4.png)

<table>
 <tr>
  <td><strong>[!UICONTROL Strict-Transport-Security]</strong></td>
  <td>Use this to guarantee connections to Landing Pages will always be served over HTTPS (should only be set for subscriptions with Landing Pages secured by SSL)</td>
 </tr>
 <tr>
  <td><strong>[!UICONTROL X-Frame-Options]</strong></td>
  <td>Allows you to define whether or not Marketo Engage hosted assets can be embedded in external web pages</td>
 </tr>
</table>

>[!CAUTION]
>
>It is important to review these settings with your IT team to determine what your organization's policy should be set to. Incorrect settings can prevent some visitors from accessing your Landing Pages.
