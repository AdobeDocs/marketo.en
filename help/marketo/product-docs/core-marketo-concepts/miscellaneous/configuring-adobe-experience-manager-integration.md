---
unique-page-id: 30081815
description: Learn how to configure Adobe Experience Manager integration with Marketo. Set up AEM so you can access and import assets into Design Studio.
title: Configuring Adobe Experience Manager Integration
hide: true
exl-id: 06b2c214-1afb-443f-ae01-0c00fed77dce
feature: Integrations
TQID: https://experienceleague.adobe.com/nJBydVi8mRwVf1vAIFuI1S3nEuX0FGiztp8fhRHq6RM
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
    internal-label: Implementation
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
---
# Configuring Adobe Experience Manager Integration {#configuring-adobe-experience-manager-integration}

Configure Adobe Experience Manager (AEM) so you can access, select, and import AEM assets into the Marketo Engage Design Studio.

>[!NOTE]
>
>**Admin Permissions Required**

>[!IMPORTANT]
>
>* This integration only works with on-premise implementations of AEM and is not supported for AEM Cloud Service implementations.
>
>* Currently, this feature is only fully supported in Firefox. It is not supported in Safari, and it might not work in the latest version of Chrome, depending on your SameSite cookie settings.

1. Navigate to the Adobe Experience Manager (the URL is specific to your company).

   ![](assets/one.png)

1. You can sign in with Adobe or sign in locally. This example uses local sign-in.

   ![](assets/two.png)

1. In **[!UICONTROL Tools]**, click **[!UICONTROL Operations]** and select **[!UICONTROL Web Console]**.

   ![](assets/2a.png)

1. In your browser, search (ctrl+f on Windows, cmd+f on Mac) for "[!UICONTROL Adobe Granite Cross-Origin Resource Sharing Policy]."

   ![](assets/three.png)

1. Click the **+** sign on the right.

   ![](assets/four.png)

1. In the **[!UICONTROL Allowed Origins (Regexp)]** text box, type in `https://.*\.marketo\.com` and click **[!UICONTROL Save]**.

   ![](assets/five-psd.png)

1. In the header at the top of the page, click **[!UICONTROL Web Console]** and select **[!UICONTROL System Information]**.

   ![](assets/six.png)

1. Under Server Information, click the **[!UICONTROL Restart]** button.

   ![](assets/seven.png)

1. Click **[!UICONTROL OK]** to confirm.

   ![](assets/eight.png)

1. In Marketo Engage, click **[!UICONTROL Admin]**.

   ![](assets/nine.png)

1. Under Integration, select **[!UICONTROL Adobe Experience Manager]**.

   ![](assets/ten.png)

1. Click **[!UICONTROL Edit]**.

   ![](assets/eleven.png)

1. Enter your AEM URL and click **[!UICONTROL OK]**.

   ![](assets/twelve.png)
