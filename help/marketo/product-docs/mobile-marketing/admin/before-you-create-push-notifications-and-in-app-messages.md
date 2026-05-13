---
unique-page-id: 11376159
description: Understand what to set up before creating push and in-app messages. Get Admin and developer steps, SDK, and custom event guidance.
title: Before You Create Push Notifications and In-App Messages
exl-id: c7e24338-387b-4c6f-bb29-7f7e6a1a7de5
feature: Mobile Marketing
TQID: https://experienceleague.adobe.com/YNAyIX3spLETvHChasi9xpP9K96ksYdkr-MSdGp2qog
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
topic_v2:
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
---
# Before You Create Push Notifications and In-App Messages {#before-you-create-push-notifications-and-in-app-messages}

Creating push notifications and in-app messages is not difficult, but you need to have everything ready before you can start. The Marketo Admin and mobile app developer should follow the steps below to prepare the necessary integrations.

1. First, the Marketo Admin [adds a mobile app](/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md).

1. The Marketo Admin then [sends a code snippet to the developer](/help/marketo/product-docs/mobile-marketing/admin/send-sdk-code-to-a-developer.md).

1. The developer downloads the SDK, and includes snippet and other methods, for [Android](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) or [iOS](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-ios).

1. By default, in-app messages are triggered when your app opens. If you want to trigger messages for other events, such as when a particular page is viewed or a specific button is pushed, the developer needs to add custom events to the code (see [Custom Events for In-App Messages](#CustomEvents) below).

1. The developer [generates the Server API key and project number for Android](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) or [the certification and password for iOS](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#install-marketo-sdk-on-ios) and sends it to the Marketo Admin.

1. The Marketo Admin configures push notification access [with the Server API key (Android)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-android-push-access.md) or [with the certificate (iOS)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-ios-push-access.md).

>[!TIP]
>
>it is easy for a Marketo Admin to check to see if your push configuration is verified. Just go [here](/help/marketo/product-docs/mobile-marketing/admin/verify-push-configuration.md).

## Custom Events for In-App Messages {#custom-events-for-in-app-messages}

For in-app messaging, the display trigger is set to **[!UICONTROL App Open]** by default. If you want to use any custom events to trigger the display of in-app messages (for example, **Clicks Add to Cart**, **Views Settings Page**), create a list of desired events and give it to your mobile apps developer. The developer will then add the custom events into the code. After they are approved, they appear as display triggers when setting up your audience. **Caution**: The custom event coding approval process may take some time to complete.

After you've got all of your preparation done for in-app messages and push notifications, it is time to get started!

>[!MORELIKETHIS]
>
>* [Create an In-App Message](/help/marketo/product-docs/mobile-marketing/in-app-messages/creating-in-app-messages/create-an-in-app-message.md)
>
>* [Create a Push Notification](/help/marketo/product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)
