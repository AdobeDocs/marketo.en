---
description: Auto-Append Unsubscribe Message Setting - Marketo Docs - Product Documentation
title: Auto-Append Unsubscribe Message Setting
hide: yes
hidefromtoc: yes
feature: Marketo Sales Connect
exl-id: 8aa75123-f6b5-4dfe-8fa7-f764620c04e8
---
# Auto-Append Unsubscribe Message Setting {#auto-append-unsubscribe-message-setting}

Ensure every email sent includes an unsubscribe message so recipients have an easy option to opt out of communication. When append unsubscribe message is enabled, all communication your team sends from Marketo Sales will include an unsubscribe message, including emails sent from the web application, Salesforce, the Gmail plugin, and the Outlook plugin.
 
## Things to Note {#things-to-note}

* For emails sent from the plugins, the unsubscribe will only be appended when a template is used.

* If you use the `{{team_unsubscribe}}` dynamic field in an email template and the unsubscribe message append setting is enabled, the team unsubscribe dynamic field will populate your unsubscribe message _instead of_ appending your unsubscribe message.

## Enable/Disable Unsubscribe Append {#enable-disable-unsubscribe-append}

1. Click the gear icon and select **Settings**.

   ![](assets/auto-append-unsubscribe-message-setting-1.png)

1. Under Admin Settings, Click **Unsubscribes**.

   ![](assets/auto-append-unsubscribe-message-setting-2.png)

1. In the Messaging tab, under Append Unsubscribe Message, move the slider to the desired state.

   ![](assets/auto-append-unsubscribe-message-setting-3.png)

>[!TIP]
>
>If you disable the append unsubscribe message setting, we recommend adding an unsubscribe footer to your templates to ensure your communication has an opt-out option. You can do this by adding your own custom message to each template, or by using the `{{team_unsubscribe}}` [dynamic field](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/dynamic-fields-glossary.md){target="_blank"}.
