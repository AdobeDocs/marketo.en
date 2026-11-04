---
description: Use CX Enterprise Coworker for Marketo Engage to turn a campaign brief into a structured program plan covering audience logic, emails, tokens, and QA checks.
title: Plan campaigns
---
# Plan campaigns {#plan-campaigns}

Turn a campaign brief into a structured implementation plan for Marketo Engage. The Plan campaigns skill outlines program structure, audience logic, emails, Smart Campaigns, tokens, reporting, and pre-activation checks. The output is a downloadable report that appears in the workspace panel.

>[!NOTE]
>
>This skill generates implementation plans for Marketo Engage programs (structured documents that tell a human or automation system exactly how to build a campaign). It does not create anything in Marketo Engage. There is a separate skill for [building programs](/help/marketo/product-docs/coworker-for-marketo/skills/build-programs.md).

## Prerequisites {#prerequisites}

- For a program plan, provide a campaign brief with the information available, such as campaign goals, target audience, messaging, timeline, and success metrics.
- To improve an existing brief or plan, provide the document and describe the changes you want.
- To get started without a brief, request a sample brief or ask for a plan based on a common campaign scenario.

## How to use {#how-to-use}

1. In your My Marketo, click the **[!UICONTROL CX Enterprise Coworker for Marketo Engage]** tile.

1. Select the **[!UICONTROL Plan campaigns]** skill and click **[!UICONTROL Use this skill]**.

1. Choose what you want to do:
   - Plan a program from a campaign brief.
   - Generate a sample campaign brief.
   - Polish an existing brief.
   - Revise an existing setup plan.

1. Provide the brief or document. Include any specific changes, campaign requirements, or organizational conventions.

1. Review the generated report in the workspace panel. Open it to review the details or download the report.

1. Review and approve the setup plan before building the program in Marketo Engage.

## Skill options {#skill-options}

### Plan a program {#plan-a-program}

A program plan translates campaign requirements into instructions for building the program. Depending on the brief, it can include:

- **Program overview:** Campaign name, objectives, target audience, and timeline.
- **Folder structure:** Recommended local folders for emails, Smart Campaigns, and reports.
- **Smart Lists:** Segmentation logic, filter definitions, and required exclusions.
- **Email configuration:** Subject lines, preheader text, content structure, sender details, and compliance elements.
- **Smart Campaigns:** Campaign names, trigger or batch designation, flow steps, and schedule recommendations.
- **Tokens and fields:** My Tokens, required and custom tokens, and any needed custom fields with their types and values.
- **Journey flow:** Campaign sequence, wait steps, and decision logic.
- **Reporting and QA:** Success metrics, recommended reports, and pre-activation validation checks.

### Create a sample brief {#create-a-sample-brief}

Request a sample brief when you want an example to adapt. You can specify a topic or campaign type, such as a product launch or webinar. If you ask for a plan without providing a brief, the skill can use a sample scenario, such as a product-launch webinar, as the basis for the plan.

### Polish a brief or revise a plan {#polish-a-brief-or-revise-a-plan}

The skill identifies the document type from its contents, rather than relying only on the wording of your request.

A **campaign brief** typically describes goals, audience, messaging strategy, timeline, and success metrics. A **setup plan** typically contains implementation details such as Smart List configurations, Smart Campaign flow steps, token definitions, email specifications, and technical requirements.

Provide the document and your requested changes. For example, if you ask to polish a plan but provide a campaign brief, the skill treats the document as a brief. If you provide a setup plan and ask to revise a brief, it treats the document as a plan.

## Organizational rules integration {#organizational-rules-integration}

Setup documents should incorporate your organization's rules from the system context.

### Naming Conventions {#naming-conventions}

- Programs: `{{REGION}}_FY{{YEAR}}_{{QUARTER}}_{{TYPE}}_{{DATE}}_{{NAME}}`
- Emails: `{{PROGRAM_NAME}}_{{SEQUENCE}}_{{PURPOSE}}`
- Smart Campaigns: `{{NUMBER}}_{{TRIGGER_OR_BATCH}}_{{ACTION}}`

### Required Elements {#required-elements}

- Three local folders (01 Emails, 02 Smart Campaigns, 03 Reports)
- Four required tokens (eventDate, eventTime, replyToEmail, senderName)
- Exclusion filters (Unsubscribed, Email Invalid, Marketing Suspended, Blocklisted)
- Email compliance (unsubscribe link, physical address)

### Pre-Activation QA {#pre-activation-qa}

- Name pattern validation
- Folder structure confirmation
- Exclusion filter verification
- Compliance element checks

## Use cases {#use-cases}

**Plan a webinar program:** Provide the webinar objective, audience, event timeline, and messaging needs. The setup plan can outline the program structure, email specifications, campaign sequence, tokens, and QA checks.

**Generate a sample brief:** Request an example brief for a campaign type, then adapt it with your campaign details before asking for a program plan.

**Update an existing setup plan:** Provide the plan and specify the changes, such as updating the timeline, adding a campaign step, or revising the audience logic.

## Next steps {#next-steps}

After a planning operation completes, appropriate follow-up prompts may include:

- "Revise this setup plan"
- "Get a sample campaign brief"
- "Create this program in Marketo" (to build a program, you must use the [build programs](/help/marketo/product-docs/coworker-for-marketo/skills/build-programs.md) skill).
