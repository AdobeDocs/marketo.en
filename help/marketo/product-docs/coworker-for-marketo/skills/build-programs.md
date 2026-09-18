---
description: Use Coworker for Marketo Engage to build a Marketo program by adapting an existing template. Get Smart Campaigns, scheduling, and asset placeholders ready to review and refine.
title: Build programs
---
# Build programs {#build-programs}

Describe a marketing campaign in plain language and Coworker for Marketo Engage adapts an existing program template to match your needs, automatically updating email content and creating additional assets by duplicating your template structure.

Your organization's [Organizational Rules](/help/marketo/product-docs/coworker-for-marketo/organizational-rules.md){target="_blank"} guide how Coworker for Marketo Engage structures and validates the program during creation. These rules ensure the new program aligns with your naming conventions, required tokens, folder structure, and compliance standards.

>[!PREREQUISITES]
>
>* To use this feature you must first agree to the [Core Gen-AI terms and the supplemental terms](https://www.adobe.com/legal/terms/enterprise-licensing/genai-ww.html){target="_blank"}. Contact the Adobe Account Team (your account manager) for details.
>
>* You must have permission to create programs in your Marketo account and have at least one existing Marketo program to use as a template. The template program should contain at least one email and one Smart Campaign.

## How to use {#how-to-use}

1. In your My Marketo, click the **Coworker for Marketo Engage** tile.

1. Select a template program. Choose an existing program that matches your campaign type (e.g., Email, Webinar, Nurture).

1. In the prompt window, type a description of the campaign you want to create. Be as specific or as general as you want (you can always refine).

1. Coworker for Marketo Engage confirms its interpretation of your brief and lists what it plans to create. Review this before it builds.

1. Confirm, and Coworker for Marketo Engage creates the program in your environment.

1. Open the newly created program in Marketo and review the structure.

1. Replace placeholder email assets with your actual content.

1. Verify Smart Campaign filters and flow steps match your intended audience and logic.

1. After you complete all manual refinements (configure Smart Campaign logic, finalize filters, customize email content), run [Validate programs](/help/marketo/product-docs/coworker-for-marketo/skills/validate-programs.md) to ensure your changes comply with your Organizational Rules before activating.

## Use cases {#use-cases}

**Webinar registration program**: A campaign manager types, "Create a webinar registration program for our August product demo. Send an invitation email, a reminder the day before, and a follow-up with the recording link afterward." Coworker for Marketo Engage creates a program with three Smart Campaigns (invitation, reminder, follow-up), placeholder emails for each, and scheduling based on the event date.

**Lead scoring trigger campaign**: A marketing ops specialist types, "Build a program that triggers when a lead reaches a score of 50 and sends them to an MQL Smart List." Coworker for Marketo Engage creates the program with a trigger campaign listening for the score change and a flow step that adds the lead to the MQL list.

**Re-engagement nurture**: A demand gen manager asks for a 3-email re-engagement series targeting leads who haven't engaged in 90 days. Coworker for Marketo Engage creates the batch campaign with the inactivity filter, three email send steps with appropriate wait steps between them, and a flow step to update lead status if someone re-engages.

**Event follow-up program**: After a trade show, a manager asks Coworker for Marketo Engage to create a post-event follow-up program that sends a thank-you email to attendees and a missed-you email to registrants who didn't show. Coworker for Marketo Engage creates two Smart Campaigns, one for each segment, with the correct filters and email placeholders.

>[!NOTE]
>
>In each example above, Coworker clones an existing program template (a simple email or event program with basic structure) and creates the additional emails and campaigns by duplicating the template assets and updating their content. The Smart Campaign flow steps and filters are adapted where possible, but may require manual refinement to match the specific campaign logic.

## Things to note {#things-to-note}

* Have a clear idea of what the campaign should do, who the audience is, what action triggers it (or whether it's a batch send), and what the goal is.
* Template selection is required. Choose a template with at least one email and one Smart Campaign. The tool cannot work with empty templates.
* Email content is auto-generated, but Smart Campaign filters and flow steps remain manual. You must configure the logic after creation to match your campaign's intended behavior.
* Extra assets are created by duplication. If your brief calls for 4 emails but your template has 1, the tool creates 3 duplicates. Review them all for consistency; they inherit the template's design and structure.
* Coworker for Marketo Engage cannot access your existing audience lists automatically. You must manually configure Smart List filters to target your actual segments after the program is created.
* Complex multi-step programs with advanced branching logic may need manual refinement after creation.
* If your Marketo environment uses naming conventions or folder structures, specify them in your brief so the program is created in the right place.
