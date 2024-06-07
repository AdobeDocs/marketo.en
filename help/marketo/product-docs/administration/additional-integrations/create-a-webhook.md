---
unique-page-id: 2360360
description: Create a [!DNL Webhook] - Marketo Docs - Product Documentation
title: Create a [!DNL Webhook]
exl-id: 3e753d2d-6f33-4987-884e-8e13167cf3df
feature: Administration, Webhooks
---
# Create a [!DNL Webhook] {#create-a-webhook}

Use [!DNL Webhooks] to take advantage of third-party web services to send text messages, expand person data, and more.

>[!AVAILABILITY]
>
>Not all Marketo Engage users have purchased this functionality. Contact the Adobe Account Team (your Account Manager) for details.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/create-a-webhook-1.png)

1. Click **[!UICONTROL Webhooks]**.

   ![](assets/create-a-webhook-2.png)

1. Click **[!UICONTROL New Webhook]**.

   ![](assets/create-a-webhook-3.png)

1. Name and configure your [!DNL Webhook].

   ![](assets/create-a-webhook-4.png)

   >[!NOTE]
   >
   >This often includes entering your third-party service credentials as a URL parameter, or in the POST template.

   * **[!UICONTROL URL]**: Enter the URL you use in your request to the web service. To insert a token, such as the person's email address (**`{{lead.Email Address}}`**), in your request, click **[!UICONTROL Insert Token]**.

   * **[!UICONTROL Template]**: If you wish to transmit information in the body of the request, enter via the payload template. Templates permitted for the following request types: POST, DELETE, PATCH, or PUT. You may use data formats such as JSON or XML. To insert a token in your template, click **[!UICONTROL Insert Token]**.

   * **[!UICONTROL Request Token Encoding]**: If the token values include special characters (such as an ampersand, '&'), indicate the format of your request (**JSON** or **Form/Url**).

   * **[!UICONTROL Response type]**: Select the format of the response you receive from the service (**JSON** or **XML**).

   * **[!UICONTROL Request Type]**: Select the HTTP method to use (DELETE, GET, PATCH, POST, PUT).

1. Click **[!UICONTROL Create]**.

   ![](assets/create-a-webhook-5.png)

>[!NOTE]
>
>Learn more in the [[!DNL Webhooks]](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/webhooks/webhooks){target="_blank"} deep dive.
