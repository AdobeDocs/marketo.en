---
unique-page-id: 2360350
description: Create a Custom Service for Use with ReST API - Marketo Docs - Product Documentation
title: Create a Custom Service for Use with ReST API
exl-id: d94f723b-2e98-4350-a9e5-bd57aff2303b
---
# Create a Custom Service for Use with ReST API {#create-a-custom-service-for-use-with-rest-api}

If you want to integrate with Marketo via the ReST API, you'll want to create a custom service. Here's how.

>[!PREREQUISITES]
>
>* [Create an API Only User Role](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [Create an API Only User](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md)
>

>[!NOTE]
>
>**Admin Permissions Required**

>[!TIP]
>
>Check out our developers documentation for details on the [ReST API](https://developers.marketo.com/documentation/rest/). We also have the [SOAP API](https://developers.marketo.com/documentation/soap/) if that's what you need.

## Create Custom Service {#create-custom-service}

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/create-a-custom-service-for-use-with-rest-api-1.png)

1. Click **[!UICONTROL LaunchPoint]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-2.png)

1. Select **[!UICONTROL New]** and then **[!UICONTROL New Service]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-3.png)

1. Enter a **[!UICONTROL Display Name]** for the service. Select the **[!UICONTROL API Only User]** [previously created](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md).

   ![](assets/create-a-custom-service-for-use-with-rest-api-4.png)

   >[!NOTE]
   >
   >Notice that we already have native integration for popular webinar services.

1. Click **[!UICONTROL Create]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-5.png)

   Oh yeah! The service is now created, let's go ahead and get all the credentials to provide for access.

## Credentials for API Access {#credentials-for-api-access}

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/create-a-custom-service-for-use-with-rest-api-6.png)

1. Click **[!UICONTROL LaunchPoint]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-7.png)

1. Click **[!UICONTROL View Details]** for the custom [!UICONTROL LaunchPoint] service created above.

   ![](assets/create-a-custom-service-for-use-with-rest-api-8.png)

1. Click **[!UICONTROL Get Token]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-9.png)

1. Provide the **[!UICONTROL Client Id]**, **[!UICONTROL Client Secret]**, **[!UICONTROL Authorized User]**, and **[!UICONTROL Token]** to the person in charge of establishing the connection.

   ![](assets/create-a-custom-service-for-use-with-rest-api-10.png)

>[!CAUTION]
>
>Don't share this information; it's the backdoor to your data. Keep it safe!
