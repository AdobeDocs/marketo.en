---
unique-page-id: 11376159
description: Before You Create Push Notifications and In-App Messages - Marketo Docs - Product Documentation
title: Before You Create Push Notifications and In-App Messages
exl-id: c7e24338-387b-4c6f-bb29-7f7e6a1a7de5
feature: Mobile Marketing
---
# Before You Create Push Notifications and In-App Messages {#before-you-create-push-notifications-and-in-app-messages}

Creating push notifications and in-app messages isn't difficult, but you need to have everything ready before you can start. The Marketo Admin and mobile app developer should follow the steps below to prepare the necessary integrations.

1. First, the Marketo Admin [adds a mobile app](/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md).

1. The Marketo Admin then [sends a code snippet to the developer](/help/marketo/product-docs/mobile-marketing/admin/send-sdk-code-to-a-developer.md).

1. The developer downloads the SDK, and includes snippet and other methods, for [Android](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) or [iOS](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-ios).

1. By default, in-app messages are triggered when your app opens. If you want to trigger messages for other events, such as when a particular page is viewed or a specific button is pushed, the developer needs to add custom events to the code (see [Custom Events for In-App Messages](#CustomEvents) below).

1. The developer [generates the Server API key and project number for Android](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) or [the certification and password for iOS](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/installation#install-marketo-sdk-on-ios) and sends it to the Marketo Admin.

1. The Marketo Admin configures push notification access [with the Server API key (Android)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-android-push-access.md) or [with the certificate (iOS)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-ios-push-access.md).

>[!TIP]
>
>It's easy for a Marketo Admin to check to see if your push configuration is verified. Just go [here](/help/marketo/product-docs/mobile-marketing/admin/verify-push-configuration.md).

## Custom Events for In-App Messages {#custom-events-for-in-app-messages}

For in-app messaging, the display trigger is set to **App Open** by default. If you want to use any custom events to trigger the display of in-app messages (for example, **Clicks Add to Cart**, **Views Settings Page**), create a list of desired events and give it to your mobile apps developer. The developer will then add the custom events into the code. After they are approved, they appear as display triggers when setting up your audience. **Caution**: The custom event coding approval process may take some time to complete.

After you've got all of your preparation done for in-app messages and push notifications, it's time to get started!

>[!MORELIKETHIS]
>
>* [Create an In-App Message](/help/marketo/product-docs/mobile-marketing/in-app-messages/creating-in-app-messages/create-an-in-app-message.md)
>
>* [Create a Push Notification](/help/marketo/product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)
