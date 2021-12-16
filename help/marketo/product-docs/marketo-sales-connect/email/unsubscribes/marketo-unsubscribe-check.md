---
unique-page-id: 18317340
description: Marketo Unsubscribe Check - Marketo Docs - Product Documentation
title: Marketo Unsubscribe Check
exl-id: b8bd5b38-a4f5-4ac7-a5ce-a155fce57998
---
# Marketo Unsubscribe Check {#marketo-unsubscribe-check}

The Marketo Unsubscribe Check uses your team's connection to Marketo to prevent emails from going to people who are unsubscribed in Marketo's Lead Management system. When a sales user sends an email with Sales Connect, an API call will be made to Marketo to check if the email ID is unsubscribed. If it is, we will block the email from being sent.

>[!NOTE]
>
>**Admin Permissions Required**

## Turning it On {#turning-it-on}

1. In the web application, click the gear icon and select **Settings**.

   ![](assets/one-2.png)

1. Under Admin Settings, click **Unsubscribes**.

   ![](assets/two-3.png)

1. Click **Integrations**.

   ![](assets/three-3.png)

1. In the Marketo Unsubscribe Check section, click the slider to activate the check.

   ![](assets/four-2.png)

## Things to Know {#things-to-know}

The Marketo Unsubscribe check...

* Does not count against your API limits
* Requires a Marketo connection be established
* Is a global setting
* Blocks emails sent from the web application, email clients, and Salesforce
* Will log a failed email or prevent a user from sending when they try to send for all workflows (email plugin send, individual send, sales campaign send, multiple select and send) except for [group emails](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md), in which we will prevent the emails from sending silently
