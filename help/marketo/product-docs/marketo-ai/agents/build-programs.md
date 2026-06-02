---
description: Use Marketo AI to build a Marketo program from a plain-language brief. Get smart campaigns, scheduling, and asset placeholders ready to review and refine.
title: Build programs
badge: Beta
hide: true
---
# Build programs {#build-programs}

Describe a marketing campaign in plain language and Marketo AI builds the program structure, complete with asset placeholders and scheduling.

>[!PREREQUISITES]
>
>* To use this feature you must first agree to the [Core Gen-AI terms and the supplemental terms](https://www.adobe.com/legal/terms/enterprise-licensing/genai-ww.html){target="_blank"}. Contact the Adobe Account Team (your account manager) for details.
>
>* You must have permission to create programs in your Marketo account.

>[!AVAILABILITY]
>
>This feature is currently in closed beta. Please do not disseminate this documentation.

## How to use {#how-to-use}

1. In your My Marketo, click the **Build with AI** tile.

1. In the prompt window, type a description of the campaign you want to create. Be as specific or as general as you want (you can always refine).

1. Marketo AI confirms its interpretation of your brief and lists what it plans to create. Review this before it builds.

1. Confirm, and Marketo AI creates the program in your environment.

1. Open the newly created program in Marketo and review the structure.

1. Replace placeholder email assets with your actual content.

1. Verify smart campaign filters and flow steps match your intended audience and logic.

1. Run the [Validate programs](/help/marketo/product-docs/marketo-ai/agents/validate-programs.md) agent before activating.

## Use cases {#use-cases}

**Webinar registration program**: A campaign manager types, "Create a webinar registration program for our August product demo. Send an invitation email, a reminder the day before, and a follow-up with the recording link afterward." Marketo AI creates a program with three smart campaigns (invitation, reminder, follow-up), placeholder emails for each, and scheduling based on the event date.

**Lead scoring trigger campaign**: A marketing ops specialist types, "Build a program that triggers when a lead reaches a score of 50 and sends them to an MQL smart list." Marketo AI creates the program with a trigger campaign listening for the score change and a flow step that adds the lead to the MQL list.

**Re-engagement nurture**: A demand gen manager asks for a 3-email re-engagement series targeting leads who haven't engaged in 90 days. Marketo AI creates the batch campaign with the inactivity filter, three email send steps with appropriate wait steps between them, and a flow step to update lead status if someone re-engages.

**Event follow-up program**: After a trade show, a manager asks Marketo AI to create a post-event follow-up program that sends a thank-you email to attendees and a missed-you email to registrants who didn't show. Marketo AI creates two smart campaigns, one for each segment, with the correct filters and email placeholders.

## Things to note {#things-to-note}

* Have a clear idea of what the campaign should do; who the audience is, what action triggers it (or whether it's a batch send), and what the goal is.
* No templates or forms are required upfront. Marketo AI creates the structure and you can connect assets afterward (you are still responsible for writing email copy and setting up any landing pages).
* Marketo AI cannot access your existing audience lists automatically. You must connect smart list filters to your actual segments after the program is created.
* Complex multi-step programs with advanced branching logic may need manual refinement after creation.
* If your Marketo environment uses naming conventions or folder structures, specify them in your brief so the program is created in the right place.
