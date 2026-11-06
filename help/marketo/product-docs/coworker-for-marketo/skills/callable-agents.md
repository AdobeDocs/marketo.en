---
description: Use callable agents in CX Enterprise Coworker for Marketo Engage to run AI steps in Smart Campaigns that clean, classify, enrich, or screen lead data.
title: Callable agents
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
---
# Callable agents {#callable-agents}

Callable agents let you use an AI agent as a step in a Marketo Engage Smart Campaign. Build an agent in CX Enterprise Coworker for Marketo Engage, choose the lead fields it reads and updates, and publish it for use in campaigns. Agents can help clean up data, classify leads, enrich missing information, or screen form submissions.

>[!PREREQUISITES]
>
>You must have the **Access admin** permission in Marketo Engage.

## Before you begin {#before-you-begin}

- Decide which lead fields the agent needs to read and which fields it should update. Every input and output must map to a Marketo Engage lead field.
- Confirm that output fields are updatable. Read-only fields and program member fields are not supported.

## How to use {#how-to-use}

1. In your My Marketo, click the **[!UICONTROL CX Enterprise Coworker for Marketo Engage]** tile.

1. Select **[!UICONTROL Callable agents]** in the left navigation. The list shows each agent's name, creation date, creator, and status. Search by name or sort by name or creation date.

1. Select **[!UICONTROL Create callable agent]**. Choose a template, or leave the template picker empty to start from scratch.

1. Enter an **[!UICONTROL Agent name]** and write **[!UICONTROL Agent instructions]** describing how to process each lead.

1. Under **[!UICONTROL Lead fields to send]**, add the lead fields the agent needs as inputs. Under **[!UICONTROL Lead fields to update]**, add each value the agent should return and map it to an updatable lead field.

1. Select **[!UICONTROL Save]** to save a draft, or **[!UICONTROL Save and publish]** to make the agent available in Marketo Engage.

1. Open a Smart Campaign and select the **[!UICONTROL Flow]** tab. In the Marketing section of the flow-step list, find **Call agent: _[Agent name]_** and drag it into the flow.

1. Test the campaign with a small set of leads. Review the activity log and confirm that output fields update as expected before activating the campaign for all leads.

## Things to note {#things-to-note}

- A callable agent processes each lead independently. Marketo Engage sends the mapped lead values to the agent, writes the returned values to the mapped lead fields, and continues to the next campaign step.
- You create and manage callable agents in CX Enterprise Coworker for Marketo Engage. No external connection is required.
- Published agents are not editable. To change an agent that is already published, you must create a new agent and update the relevant Smart Campaigns.

## Create an agent {#create-an-agent}

### Create an agent from scratch {#create-an-agent-from-scratch}

Leave the template picker empty. The form starts with one empty input field and one empty output field. Enter the name and instructions, then configure the input and output fields to match your business rule.

### Start from a template {#start-from-a-template}

Choose a template to prefill the instructions, input fields, and output fields. The agent is saved as your own copy, which you can edit or delete. If you delete an agent created from a template, the template becomes available in the picker again.

| Template | Purpose | Inputs | Outputs |
| --- | --- | --- | --- |
| Company Name Normalizer | Cleans company names by removing legal suffixes, correcting common typos, and applying standard brand capitalization. | Company | Normalized company (text); confidence (number) |
| Phone E.164 Formatter | Formats phone numbers to the international E.164 standard. | Phone | Normalized phone (text); confidence (number) |
| Job Title Standardizer | Standardizes job titles and derives seniority. | Title | Normalized title (text); seniority (C-Level, VP, Director, Manager, Individual, or Unknown); confidence |
| Bot and Spam Detector | Flags bot or spam form submissions. | Email, First name, Last name, Company, Phone | Is bot (true/false); confidence; reason; flags (comma-separated) |
| Disposable Email Detector | Identifies temporary or disposable email addresses. | Email | Is bot (true/false); confidence; reason; email type (disposable, personal, or business) |
| Lead Classifier | Segments leads by company size, industry, persona, and intent. | Company, Title, Email, Employees, Revenue | Segment (Enterprise, Mid-Market, SMB, Startup, or Unknown); industry; persona; intent level (High, Medium, or Low); confidence |
| Lead Enrichment | Infers missing lead details from available information. | Email, Title, Company | Inferred company, department, seniority, is decision maker (true/false), is B2B (true/false), confidence |
| Company Research | Generates sales intelligence from company information. | Company, Website, Description | See the template for the full list |

### Write effective instructions {#write-effective-instructions}

- Put general rules and examples in the agent instructions. Use field instructions to specify expectations for an individual output.
- Be specific. For example, "Remove legal suffixes such as Inc, LLC, and Corp" is clearer than "clean up company names."
- Include examples of inputs and expected outputs, especially for edge cases.
- State what the agent should return when it cannot decide, such as "If you are unsure, return the original value."
- Add a confidence output so campaign logic can route low-confidence results for review.
- Keep prompts concise. Shorter prompts run faster and cost less.

## Save, publish, and manage agents {#save-publish-and-manage-agents}

### Save as a draft or publish {#save-as-a-draft-or-publish}

Select **[!UICONTROL Save]** to save the agent as a draft. Drafts can be edited but are not available as Smart Campaign flow steps. Select **[!UICONTROL Save and publish]** when the agent is ready. Marketo Engage makes the agent available as a flow step and returns you to the agent list with a publication confirmation. Select **[!UICONTROL Cancel]** to leave without saving.

| Status | Meaning | Available action |
| --- | --- | --- |
| Draft | The agent is saved but is not available in Marketo Engage. | Edit it, then select **[!UICONTROL Save and publish]** when it is ready. |
| Published | The agent is available in Smart Campaigns. Published agents are frozen. | Use the published agent, or create a new agent to make changes. |
| Publication failed | Marketo Engage rejected the agent, for example, because an output field name is reserved. But the agent is still saved as a draft. | Edit the agent, correct the field named in the message, and publish again. |

### Edit, check usage, or delete {#edit-check-usage-or-delete}

- Select **[!UICONTROL Edit]** on a draft to change it. **[!UICONTROL Save]** keeps you on the page and shows an "Agent saved" confirmation. You can also select **[!UICONTROL Save and publish]**, **[!UICONTROL Cancel]**, or **[!UICONTROL Delete]**.
- Published agents are frozen because Smart Campaigns may depend on them. Create a new agent to make changes.
- Check **[!UICONTROL Used by]** to see which Smart Campaigns reference an agent before you delete an agent or change its campaign setup.
- You cannot delete an agent while a Smart Campaign still uses it. Remove the agent's flow step from each listed campaign, then delete the agent.

## Organizational rules integration {#organizational-rules-integration}

### Naming conventions {#naming-conventions}

- **Agent name:** 1-100 characters and unique within the subscription. The name is also used in the Smart Campaign flow step. Choose a recognizable name, such as `Company Name Normalizer`.
- **Output field name:** Use letters, digits, and underscores. The name must start with a letter or underscore, be unique, and be no more than 64 characters.
- **Reserved names:** Some output names are reserved for system use. If a name is rejected, choose another name, such as `qualificationReason` instead of `reason`.

### Required elements and supported fields {#required-elements-and-supported-fields}

- Map every input field to a Marketo Engage lead field before saving.
- Configure at least one output field. Map each output to an updatable lead field; read-only fields are not available in the field picker.
- Program member fields are not supported. The field picker shows lead fields only.
- Supported output types are **Text**, **Number**, and **True/False**.
- To return a list, use a comma-separated text value and describe the expected format in the field instructions.
- Each successful run returns exactly the configured output fields.

### Limits {#limits}

| Setting | Limit |
| --- | --- |
| Agent name | 1-100 characters; unique within the subscription |
| Agent instructions | 1-4,000 characters |
| Input fields | Up to 20; each must map to a lead field |
| Output fields | 1-20; each must map to an updatable lead field |
| Output field name | Up to 64 characters; letters, digits, and underscores; starts with a letter or underscore; unique |
| Output field instructions | Up to 512 characters |
| Leads per request | Up to 1,000 leads from Marketo Engage, processed in parallel |

## Content screening and data handling {#content-screening-and-data-handling}

When you create an agent or edit its instructions, Marketo Engage screens the agent instructions and output field instructions for policy violations, prompt injection, and data-exfiltration attempts. Examples include requests to reveal credentials or override agent behavior. If content is flagged, saving is blocked and a message may appear, such as "Prompt contains restricted content" or "Prompt failed content moderation." Revise the text and save again.

- **Access:** Managing agents requires the **Access admin** permission. Agents and call history are isolated by subscription.
- **Lead data protection:** Lead data is passed separately from agent instructions, with safeguards that treat lead values as data rather than commands.
- **Content policy:** If a lead's data violates the AI provider's content policy, that lead receives an error activity instead of a result.
- **Retention:** Request and response payloads, including lead field values sent to the agent, are kept in call history for 30 days to support troubleshooting, then deleted automatically.

## How callable agents run in a campaign {#how-callable-agents-run-in-a-campaign}

1. When the campaign runs, Marketo Engage sends the mapped lead field values for each qualifying lead to the agent.
1. The agent processes each lead independently and returns the configured output fields.
1. Marketo Engage writes the results to the mapped lead fields. Changed fields also appear as standard data value change activities.
1. The campaign moves to the next step.

Processing is asynchronous. The flow step waits for a result up to the flow-step wait window in Marketo Engage. If one lead fails (for example, because of a timeout), that lead receives an error activity and other leads continue. Each result appears in the lead's activity log for the callable agent.

Use output fields in campaign logic. For example, branch on **Is bot** to route spam submissions differently, or branch on **confidence** to send low-confidence results to a review step.

## Pre-activation QA {#pre-activation-qa}

Before activating a campaign for all leads:

- Run the campaign with a small test set of leads.
- Review each lead's activity log and confirm that output fields updated correctly.
- Test edge cases, including missing values and unusual inputs.
- Confirm that campaign branches handle values such as low confidence or a bot/spam classification as intended.

## Use cases {#use-cases}

- **Data cleanup:** Standardize company names, format phone numbers to E.164, and normalize job titles when leads are created or imported.
- **Bot and spam screening:** Check submissions for gibberish names, suspicious emails, and repeated-digit phone numbers; branch the campaign based on the result.
- **Disposable email detection:** Identify temporary email addresses and route them differently from business addresses.
- **Lead classification:** Segment leads by company size, industry, persona, and intent to support routing or scoring.
- **Lead enrichment:** Infer missing details such as department, seniority, or whether a lead is a decision maker.
- **Custom rules:** Build a yes/no check or categorization that can be described as a lead-processing rule, such as flagging leads from a region or industry.

## Troubleshooting {#troubleshooting}

| Issue | Resolution |
| --- | --- |
| **Agents** does not appear in navigation. | Ask your Marketo Engage administrator to grant the **Access admin** permission. |
| Saving is blocked with a content message. | Revise the agent instructions or field instructions to remove the flagged content, then save again. |
| The agent status is **Publication failed**. | Edit the agent, correct the field named in the message, and select **Save and publish**. |
| You cannot edit a published agent. | Published agents are frozen. Create a new agent to make changes. |
| You cannot delete an agent. | Remove its flow step from each Smart Campaign listed as using the agent, then delete it. |
| A field name is reported as reserved. | Choose a different output field name, such as `qualificationReason`, and save again. |
| Some leads receive an error activity. | Check the lead's activity log. Individual failures, including timeouts or content policy violations, do not affect other leads. |
| Results are unexpected. | Make the instructions more specific, add examples, refine field instructions, and test again with a small set of leads. |

## Next steps {#next-steps}

- Review the agent's **Used by** list and confirm which Smart Campaigns will use it.
- Test the flow step with a small group of leads and validate activity logs and output fields.
- Use the output fields to add campaign branches for classifications or low-confidence results.
- Remove the agent flow step from all campaigns before deleting the agent.
