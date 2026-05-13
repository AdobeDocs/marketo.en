---
description: Learn about Marketo Unsubscribe Check so sellers cannot email people who unsubscribed in Marketo.
title: Marketo Unsubscribe Check
exl-id: 3c242d04-cf6c-466b-9bcd-e77c6d97d308
feature: Sales Insight Actions
TQID: https://experienceleague.adobe.com/RaIYKEVyjdeUlOa4paltYIS8NPZHi1XWTmO4IeLBy-o
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
---
# [!UICONTROL Marketo Unsubscribe Check] {#marketo-unsubscribe-check}

The [!UICONTROL Marketo Unsubscribe Check] uses your team's connection to Marketo to prevent emails from going to people who are unsubscribed in Marketo's Lead Management system. When a sales user sends an email with [!DNL Marketo Sales], an API call will be made to Marketo to check if the email ID is unsubscribed. If it is, we will block the email from being sent.

>[!NOTE]
>
>**Admin Permissions Required**

## Turning it On {#turning-it-on}

1. Click the gear icon and select **[!UICONTROL Settings]**.

   ![](assets/marketo-unsubscribe-check-1.png)

1. Under [!UICONTROL Admin Settings], click **[!UICONTROL Unsubscribes]**.

   ![](assets/marketo-unsubscribe-check-2.png)

1. Click the **[!UICONTROL Integrations]** tab. In the [!UICONTROL Marketo Unsubscribe Check] section, click the slider to activate the check.

   ![](assets/marketo-unsubscribe-check-3.png)

## Things to Know {#things-to-know}

The Marketo Unsubscribe check...

* Does not count against your API limits
* Requires a Marketo connection be established
* Is a global setting
* Blocks emails sent from the web application, email clients, and [!DNL Salesforce]
