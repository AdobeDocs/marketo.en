---
description: Clone program duplicates an existing Marketo program into a new folder with a new name, preserving its structure while letting you customize the new campaign.
title: Clone program
badge: Beta
hide: true
---
# Clone program {#clone-program}

The Clone program agent copies a working program, including its smart campaigns, flow steps, email assets, and configuration, into a new location in your Marketo environment.

>[!PREREQUISITES]
>
>* To use this feature you must first agree to the [Core Gen-AI terms and the supplemental terms](https://www.adobe.com/legal/terms/enterprise-licensing/genai-ww.html){target="_blank"}. Contact the Adobe Account Team (your account manager) for details.
>
>* You must have permission to create programs in the destination folder.
>
>* The source program you want to clone must already exist in your Marketo environment.

>[!AVAILABILITY]
>
>This feature is currently in closed beta. Please do not disseminate this documentation.

## How to use {#how-to-use}

1. In your My Marketo, click the **Build with AI** tile.

1. In the prompt window, type your instructions. For example, "Clone my Q2 Webinar program into the Q3 Campaigns folder and call it Q3 Product Demo Webinar."

1. Marketo AI confirms the source program, destination folder, and new name. Review and confirm.

1. The clone is created. Marketo AI confirms when it is done and tells you where to find it.

1. Open the new program in Marketo and update what is different: email content, dates, audience filters, tokens, etc.

1. Run the [Program QA](/help/marketo/product-docs/marketo-ai/agents/program-qa.md) agent before activating.

## Use cases {#use-cases}

**Quarterly campaign reuse**: A campaign manager runs the same webinar series each quarter. They ask Marketo AI to clone last quarter's webinar program into the new quarter's folder with an updated name. They then update the email copy, webinar date tokens, and registration link, saving hours of setup time.

**Creating a template from a proven program**: A marketing ops specialist clones a high-performing product launch program into a "Templates" folder to serve as the starting point for future launches. The clone is left deactivated and used as a reference copy.

**A/B testing a new approach**: A campaign manager wants to test a different email cadence without changing a running program. They clone the active program, modify the wait steps in the clone, and activate both, running them against different audience segments to compare results.

## Things to note {#things-to-note}

* Cloned programs are created in a deactivated state. Nothing goes live until you activate the smart campaigns.
* Email assets in the clone are copies, not shared with the original. Changes to the clone's emails won't affect the source program.
* Tokens used in the source program are copied into the clone. However, they must still be updated with new values (dates, URLs, event names).
* Smart campaign filters in the clone reference the same lists and fields as the original. Review and update audience targeting before activating.
* Local assets referencing other programs or shared lists are copied into the clone. Those references should be reviewed before activating.
