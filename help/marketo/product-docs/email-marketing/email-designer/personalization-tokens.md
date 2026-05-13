---
solution: Marketo Engage
product: marketo
title: Personalization Tokens
description: Learn how to use personalization tokens in the Email Designer. Add dynamic recipient data to your email content.
level: Beginner, Intermediate
feature: Email Designer
exl-id: 4828e1a5-822f-48a9-bbb8-b1ffe8421e4f
hide: true
TQID: https://experienceleague.adobe.com/2F6SP0sUvcScw0Y86X10nRTfL2b45krGTLeSi-td7Uc
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Personalization Tokens {#personalization-tokens}

The email designer has a different format than the classic email editor when it comes to email personalization tokens. The change was implemented to improve compatibility with Handlebar scripting and streamline your email creation process.

>[!AVAILABILITY]
>
>Beginning May 23, 2025, this feature will be provisioned to Marketo Engage users in batches, with one region updated per week. During the rollout, any emails created using the new email designer will automatically migrate existing tokens to the new format. With this update, all tokens will be available in English only.

## Primary Use Case {#primary-use-case}

This enhancement primarily benefits those transitioning from [Velocity scripting](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/email-scripting){target="_blank"} to Handlebar scripting. The new email designer only supports the new token format. The updated format eliminates spaces and introduces a revised default text structure, ensuring a smoother and more efficient scripting experience.

## Token Experience {#token-experience}

A look at the token experience, both old and new.

### Old Format {#old-format}

In the classic email editor, you could add tokens with spaces, such as `lead.Anonymous IP`, or `member.registration code`. The format for default text was: `{{lead.City:default=fallback}}`

   ![](assets/personalization-tokens-1.png){width="800" zoomable="yes"}

### New Format {#new-format}

In the email designer, you must use [camel case](https://developer.mozilla.org/en-US/docs/Glossary/Camel_case) or underscores for tokens (e.g., `lead.anonymousIP` or `member.registration_code`). The format for default text also changes to `{%=lead.city ?: "fallback" %}`.

   ![](assets/personalization-tokens-2.png){width="800" zoomable="yes"}

## Things to Note {#things-to-note}

* The personalization editor also features the following functions for ease of authoring:

  * Undo/redo
  * Find/Find & replace

* **All** tokens previously supported in Marketo Engage are supported in the new personalization editor.
