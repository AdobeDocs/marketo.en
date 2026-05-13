---
description: Learn about field prompts in email templates. Add placeholders that prompt the sender to fill in custom content when sending.
title: Field Prompts
exl-id: c138b627-f853-4d35-b022-cc517d6b86d4
TQID: https://experienceleague.adobe.com/ahVbX8SGxaVUjSPsU-1uVc36ecIW60lwYXxDZSxC0kU
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Field Prompts {#field-prompts}

Field prompts allow you to add a string of text to emails that need to be removed or replaced before the email can be sent. This is a great way to remind users to add additional personalization.

To add a field prompt, type out the desired text. Preface it with an exclamation mark and surround it with curly brackets (see below).

**Examples:**

`{{! Introduce yourself}}`

`{{! Insert name of Account Executive}}`

`{{! Add sentence that references their industry and role}}`

<p>Users will need to replace this text with their own personalization before the email can be sent.

   ![](assets/field-prompts-1.png)

>[!NOTE]
>
>When using prompts with Sales Campaigns, it is best to use them with manual email steps. These steps will assign a user a reminder task to send the email, giving them an opportunity to replace the prompts with custom text. Automatic email steps in Sales Campaigns will attempt to automatically send, without allowing the user to replace the prompts. Prompts that are not replaced will cause the emails to fail to send.
