---
unique-page-id: 2360350
description: Create a custom LaunchPoint service linked to an API-only user for ReST API integration.
title: Create a Custom Service for Use with ReST API
exl-id: d94f723b-2e98-4350-a9e5-bd57aff2303b
feature: Administration
TQID: https://experienceleague.adobe.com/7RYZTS-1WiaU0A8ThqHvk01S7GLIIP65xyKI3SIuPyo
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Create a Custom Service for Use with ReST API {#create-a-custom-service-for-use-with-rest-api}

If you want to integrate with Marketo via the ReST API, create a custom service.

>[!PREREQUISITES]
>
>* [Create an API Only User Role](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [Create an API Only User](/help/marketo/product-docs/administration/users-and-roles/create-api-only-user.md)
>

>[!NOTE]
>
>**Admin Permissions Required**

>[!TIP]
>
>See the Developers documentation for details on the [REST API](https://developer.adobe.com/marketo-apis/).

## Create Custom Service {#create-custom-service}

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/create-a-custom-service-for-use-with-rest-api-1.png)

1. Click **[!UICONTROL LaunchPoint]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-2.png)

1. Select **[!UICONTROL New]** and then **[!UICONTROL New Service]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-3.png)

1. Enter a **[!UICONTROL Display Name]** for the service. Select the **[!UICONTROL API Only User]** [previously created](/help/marketo/product-docs/administration/users-and-roles/create-api-only-user.md).

   ![](assets/create-a-custom-service-for-use-with-rest-api-4.png)

1. Click **[!UICONTROL Create]**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-5.png)

   The service is now created. Retrieve the credentials to provide for access.

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
>Do not share this information, as it provides access to your data.
