---
description: Learn how to configure Dynamic Chat security with blocked or allowed domains. Restrict which email domains agents see and which sites can use your chat script.
title: Security Settings
feature: Dynamic Chat
exl-id: 68a53986-6f42-4aa2-86f6-0b2097f94963
TQID: https://experienceleague.adobe.com/7ans6J5WCXbTalK7ubMCrWBLWaJm3prPCoxsrCWEKtg
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
topic_v2:
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
---
# Security Settings {#security-settings}

In Security settings, you have the ability to add domains to a blocked or allowed list.

   ![](assets/security-settings-1.png)

>[!IMPORTANT]
>
>Block and Allow Email Domain filtering applies only when a visitor enters their email address directly within Dynamic Chat, either in the chatbot or in a conversational flow. It does not apply to email addresses that Dynamic Chat receives from integrated products, such as Marketo Engage. For more information see the table below.

| Scenario | Does filtering apply? |
|---|---|
| Visitor types their email directly into the Dynamic Chat chatbot | Yes |
| Visitor types their email directly into a Dynamic Chat conversational flow | Yes |
| Email is pre-populated from a Marketo form submission (conversational flow appears after form fill) | No |
| Email is passed to Dynamic Chat from any other integrated system | No |

## Blocked Email Domains {#blocked-email-domains}

If there are any visitors with email domains you don't want your agents to interact with (e.g., a competitor), add their email domain to the blocklist.

1. Select the **Enable Validation** slider to activate your blocklist. Enter up to 50 domains and click **Save**.

   ![](assets/security-settings-2.png)

## Allowed Domains {#allowed-domains}

Adding allowed domains ensures that third parties can't scrape the javascript from your site and add it to their own.

1. Select the **Enable Validation** slider to activate your allowlist. Enter the allowed domains and click **Save**.

   ![](assets/security-settings-3.png)
