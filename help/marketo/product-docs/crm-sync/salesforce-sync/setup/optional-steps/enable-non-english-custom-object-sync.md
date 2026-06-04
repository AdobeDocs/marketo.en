---
unique-page-id: 4719302
description: Learn how to enable custom object sync when the Marketo sync user uses a non-English language. Set the sync user language to English in Salesforce and refresh schema.
title: Enable Non-English Custom Object Sync
exl-id: 5d1c5b52-5323-4f68-847b-7d24e6acd6c4
feature: Salesforce Integration
TQID: https://experienceleague.adobe.com/kPzDEdjDnDAvuJmCtPj0I2Lfl63Lset00t-LwB8DDhI
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
---
# Enable Non-English Custom Object Sync {#enable-non-english-custom-object-sync}

If your Marketo sync user is set to a language other than English you may run into an error when trying to enable a custom object sync.

![](assets/image2014-12-10-13-3a17-3a51.png)

## How to fix {#how-to-fix}

1. Log in to [!DNL Salesforce] using the marketo sync user.

   ![](assets/image2014-12-10-13-3a18-3a1.png)

1. Click the user name drop-down and select **[!UICONTROL Setup]**.

   ![](assets/image2014-12-10-13-3a18-3a11.png)

1. Under **[!UICONTROL Personal Information]**, click **[!UICONTROL My Personal Information]**.

   ![](assets/image2014-12-10-13-3a18-3a22.png)

1. Click **[!UICONTROL Edit]**.

   ![](assets/image2014-12-10-13-3a18-3a32.png)

1. Change the **[!UICONTROL Language]** to **[!UICONTROL English]**.

   ![](assets/image2014-12-10-13-3a18-3a45.png)

1. Click **[!UICONTROL Save]**.

   ![](assets/image2014-12-10-13-3a18-3a55.png)

1. In your [Adobe Account Profile](https://account.adobe.com/profile){target="_blank"}, scroll down to **[!UICONTROL Preferred languages]** and make sure your first language is set to English.

   ![](assets/enable-non-english-custom-object-sync-step-6.5.png)

1. In Marketo Engage, navigate to **[!UICONTROL Admin]** > **[!UICONTROL Salesforce]** > **[!UICONTROL Objects]**. Click **[!UICONTROL Refresh Schema]**.

   ![](assets/image2014-12-10-13-3a19-3a6.png)

1. This pulls the objects list in English. Select the object of your choice and click **[!UICONTROL Enable Sync]**.

   ![](assets/image2014-12-10-13-3a19-3a16.png)

1. Your custom object is now enabled and syncing.

   ![](assets/image2014-12-10-13-3a19-3a26.png)

1. Go back to [!DNL Salesforce] and use the above steps to change the sync user back to your preferred language.

>[!NOTE]
>
>Refresh the schema one last time to pull the objects back in your language.
