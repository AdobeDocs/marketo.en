---
description: The Investigate lead agent answers the questions marketers ask most often. It's faster and more reliable than manually digging through activity logs, smart campaign history, and scoring records.
title: Investigate leads
badge: Beta
hide: true
hidefromtoc: yes
---
# Investigate leads {#investigate-leads}

Find out why a specific person/lead didn't reach a milestone (like MQL, program qualification, or a campaign) and get a plain-language explanation of what happened.

>[!PREREQUISITES]
>
>* To use this feature you must first agree to the [Core Gen-AI terms and the supplemental terms](https://www.adobe.com/legal/terms/enterprise-licensing/genai-ww.html){target="_blank"}. Contact the Adobe Account Team (your account manager) for details.
>
>* You must have view access to the person/lead record and the program or milestone you're investigating.

>[!AVAILABILITY]
>
>This feature is currently in closed beta. Please do not disseminate this documentation.

## How to use {#how-to-use}

1. In your My Marketo, click the **Build with AI** tile.

1. In the prompt window, describe what you're investigating. Include the lead (by email or name) and what you expected to happen.

   >[!NOTE]
   >
   >Examples include: "Why didn't `john.smith@example.com` reach MQL last month?" or "Why wasn't Sato Hanako added to the Q3 webinar program?"

1. Marketo AI pulls up the lead's record and relevant history.

1. Review the explanation. Marketo AI tells you the specific reason the milestone wasn't reached and, where possible, what would need to change for the lead to qualify.

1. Take action based on the finding: correct a data issue, adjust a filter, update the lead's score, or accept that the outcome was correct.

## Use cases {#use-cases}

**MQL threshold not reached**: A demand gen manager notices a lead that sales flagged as interested, but who never hit MQL. They ask: "Why didn't `david.chen@techcorp.com` reach MQL?" Marketo AI finds that the lead's behavioral score is 42 (8 points below the MQL threshold of 50) and lists the scoring activities that contributed. They can see exactly which behaviors would push the lead over the threshold.

**Campaign skip due to suppression**: A campaign manager asks why a specific contact didn't receive an invitation email that went to the rest of the list. Marketo AI finds that the contact is on the marketing suspended list, which automatically excludes them from all campaign sends. The manager reaches out to them directly to investigate why they were suppressed.

**Program qualification failure**: A marketing ops specialist is troubleshooting why a lead who attended a webinar wasn't added to the post-event follow-up program. Marketo AI traces the issue: the lead registered but was marked as "No Show" in the event program, and the follow-up campaign filter requires "Attended" status. The status was set incorrectly in the integration.

## Things to note {#things-to-note}

* Lead Investigation explains what happened based on Marketo's recorded activity and configuration. It cannot explain decisions made outside Marketo (for example, why a lead was manually removed by a colleague).
* If a lead's activity history is very long, Marketo AI focuses on the most recent and most relevant events related to your question.
* Lead Investigation is read-only. It tells you what happened, but does not make changes to the lead record or program membership.
* For issues that turn out to be data quality problems (missing field values, incorrect lead source), the fix must be made manually in the lead record.
* If the investigation reveals a smart campaign logic issue affecting many leads, use Program QA to review the full program configuration.
