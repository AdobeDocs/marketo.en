---
unique-page-id: 4719302
description: Enable Non-English Custom Object Sync - Marketo Docs - Product Documentation
title: Enable Non-English Custom Object Sync
exl-id: 5d1c5b52-5323-4f68-847b-7d24e6acd6c4
feature: Salesforce Integration
---
# Enable Non-English Custom Object Sync {#enable-non-english-custom-object-sync}

If your Marketo sync user is set to a language other than English you may run into an error when trying to enable a custom object sync.

## The Error {#the-error}

![](assets/image2014-12-10-13-3a17-3a51.png)

## Getting Around It {#getting-around-it}

1. Log in to [!DNL Salesforce] using the marketo sync user.

   ![](assets/image2014-12-10-13-3a18-3a1.png)

1. Under the user name, go to **[!UICONTROL Setup]**.

   ![](assets/image2014-12-10-13-3a18-3a11.png)

1. Under **[!UICONTROL Personal Information]**, click **[!UICONTROL My Personal Information]**.

   ![](assets/image2014-12-10-13-3a18-3a22.png)

1. Click **[!UICONTROL Edit]**.

   ![](assets/image2014-12-10-13-3a18-3a32.png)

1. Change the **[!UICONTROL Language]** to **[!UICONTROL English]**.

   ![](assets/image2014-12-10-13-3a18-3a45.png)

1. Click **[!UICONTROL Save]**.

   ![](assets/image2014-12-10-13-3a18-3a55.png)

1. Back in Marketo, under **[!UICONTROL Admin]** > **[!UICONTROL Salesforce]** > **[!UICONTROL Objects]**, click **[!UICONTROL Refresh Schema]**.

   ![](assets/image2014-12-10-13-3a19-3a6.png)

1. This will pull the objects list in English. Now select the object of your choice and click **[!UICONTROL Enable Sync]**.

   ![](assets/image2014-12-10-13-3a19-3a16.png)

1. Notice your custom object is now enabled and syncing.

   ![](assets/image2014-12-10-13-3a19-3a26.png)

1. Now go back to Salesforce and use the above steps to change the sync user back to your preferred language.

>[!NOTE]
>
>Don't forget to Refresh Schema one last time to pull the objects back in your language.
