---
unique-page-id: 2360350
description: Create a Custom Service for Use with ReST API - Marketo Docs - Product Documentation
title: Create a Custom Service for Use with ReST API
---

# Create a Custom Service for Use with ReST API {#create-a-custom-service-for-use-with-rest-api}

Create a Custom Service for Use with ReST API - Marketo Docs - Product Documentation

If you want to integrate with Marketo via the ReST API, you'll want to create a custom service. Here's how.

>[!NOTE]
>
>**Prerequisites**
>
>* [Create an API Only User Role](../../../product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [Create an API Only User](../../../product-docs/administration/users-and-roles/create-an-api-only-user.md)
>

>[!NOTE]
>
>**Admin Permissions Required**

### What's in this article? {#whats-in-this-article}

[Create Custom Service](#create-custom-service)  
[Credentials for API Access](#credentials-for-api-access)

>[!NOTE]
>
>**Deep Dive**
>
>Check out our developers documentation for details on the [ReST API](http://developers.marketo.com/documentation/rest/). We also have the [SOAP API](http://developers.marketo.com/documentation/soap/) if that's what you need.

>[!NOTE]
>
>You can't create a custom service if you have the Spark level of Marketo.

#### Create Custom Service {#create-custom-service}

1. Go to **Admin** and click **LaunchPoint**.

   ![](assets/image2014-9-19-10-3a38-3a15.png)

1. Under **New**, click **New Service**.

   ![](assets/image2014-9-19-10-3a38-3a22.png)

1. Enter a **Display Name** for the service. Select the **API Only User** [previously created](../../../product-docs/administration/users-and-roles/create-an-api-only-user.md).

   >[!NOTE]
   >
   >**Reminder**
   >
   >Notice that we already have native integration for popular webinar services.

   ![](assets/image2014-9-19-10-3a38-3a32.png)

1. Click **Create**.

   ![](assets/image2014-9-19-10-3a39-3a28.png)

   Oh yeah! The service is now created, let's go ahead and get all the credentials to provide for access.

#### Credentials for API Access {#credentials-for-api-access}

1. Go to **Admin** and click **LaunchPoint**.

   ![](assets/image2014-9-19-10-3a42-3a11.png)

1. Click **View Details** for the custom LaunchPoint service created above.

   ![](assets/image2014-9-19-10-3a42-3a16.png)

1. Click **Get Token**.

   ![](assets/image2014-9-19-10-3a42-3a24.png)

1. Provide the** Client Id**, **Client Secret**, **Authorized User**, and **Token** to the person in charge of establishing the connection.

   ![](assets/image2014-9-19-10-3a42-3a38.png)

>[!CAUTION]
>
>Don't share this information; it's the backdoor to your data. Keep it safe!

