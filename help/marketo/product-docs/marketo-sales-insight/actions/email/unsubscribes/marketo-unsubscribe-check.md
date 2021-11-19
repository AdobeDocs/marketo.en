---
description: Marketo Unsubscribe Check - Marketo Docs - Product Documentation
title: Marketo Unsubscribe Check
hide: yes
hidefromtoc: yes
---
# Marketo Unsubscribe Check {#marketo-unsubscribe-check}

The Marketo Unsubscribe Check uses your team's connection to Marketo to prevent emails from going to people who are unsubscribed in Marketo's Lead Management system. When a sales user sends an email with Marketo Sales, an API call will be made to Marketo to check if the email ID is unsubscribed. If it is, we will block the email from being sent.

>[!NOTE]
>
>**Admin Permissions Required**

## Turning it On {#turning-it-on}

1. Click the gear icon and select **Settings**.

   ![](assets/marketo-unsubscribe-check-1.png)

1. Under Admin Settings, click **Unsubscribes**.

   ![](assets/marketo-unsubscribe-check-2.png)

1. Click the **Integrations** tab. In the Marketo Unsubscribe Check section, click the slider to activate the check.

   ![](assets/marketo-unsubscribe-check-3.png)

## Things to Know {#things-to-know}

The Marketo Unsubscribe check...

* Does not count against your API limits
* Requires a Marketo connection be established
* Is a global setting
* Blocks emails sent from the web application, email clients, and Salesforce
