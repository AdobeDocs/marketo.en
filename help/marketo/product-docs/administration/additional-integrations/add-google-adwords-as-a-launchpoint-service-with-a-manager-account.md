---
unique-page-id: 7504893
description: "Add [!DNL Google AdWords] as a [!DNL Launchpoint] Service with a Manager Account - Marketo Docs - Product Documentation"
title: "Add [!DNL Google AdWords] as a [!DNL Launchpoint] Service with a Manager Account"
exl-id: aac106f4-6615-49d5-a561-0dd965c7b0ff
feature: "Administration, Integrations"
---
# Add [!DNL Google AdWords] as a [!DNL Launchpoint] Service with a Manager Account {#add-google-adwords-as-a-launchpoint-service-with-a-manager-account}

Link your [!DNL Google AdWords] account to Marketo to automatically upload offline conversion data from Marketo to [!DNL Google AdWords]. Then, from the [!DNL AdWords] UI, you will be able to easily see which clicks resulted in qualified leads, opportunities and new customers (or whatever revenue stages you want to track) after you  [add custom columns](https://support.google.com/adwords/answer/3073556){target="_blank"} in [!DNL AdWords]. This information does not appear in the Marketo UI.

If you have multiple [!DNL Google Adwords] accounts, you can use a [[!DNL Google AdWords Manager Account]](https://www.google.com/adwords/manager-accounts/){target="_blank"} (formerly known as [!DNL My Client Center]) to integrate them with Marketo.

Learn more about [Google's offline conversion import feature](https://support.google.com/adwords/answer/2998031?hl=en){target="_blank"}.

>[!AVAILABILITY]
>
>Not all customers have purchased this feature. Please contact the Adobe Account Team (your Account Manager) for details.

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>You can also integrate a [stand-alone [!DNL Google AdWords] account as a [!DNL Launchpoint] service](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service.md){target="_blank"}.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-1.png)

1. Select **[!UICONTROL LaunchPoint]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-2.png)

1. Click the **[!UICONTROL New]** drop-down and select **[!UICONTROL New Service]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-3.png)

1. Enter a **[!UICONTROL Display Name]** and select **[!UICONTROL Google AdWords]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-4.png)

1. Select **[!UICONTROL Authorize Marketo]**.

   >[!NOTE]
   >
   >Make sure to log out of your personal [!DNL Gmail] account and enable pop-ups.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-5.png)

1. Select your account associated with **[!DNL Google AdWords]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-6.png)

1. Click **[!UICONTROL Accept]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-7.png)

1. Status will display as **[!UICONTROL Success]**. Select **[!UICONTROL Next]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-8.png)

1. Upload your offline conversions from Marketo to [!DNL Google AdWords] **[!UICONTROL Weekly]** or **[!UICONTROL Daily]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-9.png)

1. Attribute conversion to the **[!UICONTROL First Click]** or **[!UICONTROL Last Click]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-10.png)

   | Type |Definition |
   |---|---|
   | [!UICONTROL First Click] |Offline conversions will be attributed to the first [!DNL AdWords] ad that a person clicked in the past 90 days |
   | [!UICONTROL Last Click] |Offline conversions will be attributed to the last [!DNL AdWords] ad that a person clicked |

   >[!NOTE]
   >
   >[Auto-tagging](https://support.google.com/adwords/answer/1752125?hl=en){target="_blank"} must be selected for this feature to work. It must be activated inside [!DNL AdWords].

1. Click **[!UICONTROL Next]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-11.png)

1. Deselect accounts you do not want to update. Click **[!UICONTROL Create]**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-12.png)

   Now see the Related Article below for how to map [!DNL AdWords] offline conversions in your revenue model.

   >[!MORELIKETHIS]
   >
   >[Set [!DNL Google AdWords] Conversions in the Revenue Model with a Manager Account](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account.md){target="_blank"}
