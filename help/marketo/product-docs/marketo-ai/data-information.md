---
description: Review Marketo AI's data scope, governance controls, and PII considerations across key workflows such as lead import, program QA, and data normalization.
title: Marketo AI data information sheet
badge: beta
---
# Marketo AI data information sheet {#data-information}

Marketo AI is a native, agentic feature within Adobe Marketo Engage that enables marketing operations teams to automate select workflows through natural-language interaction, including lead import, program validation, data normalization, program creation, lead investigation, analytics, and product guidance. Marketo AI operates within a user's existing Marketo Engage environment and uses Adobe-managed infrastructure for AI reasoning and orchestration.

**User environment:** Marketo AI operates within an existing Marketo Engage environment and does not introduce a new user-to-user sharing pathway.

**Data scope:** The service processes standard B2B marketing data already present in the user environment, including lead records, program data, and smart campaign activity.

**AI services:** Marketo AI leverages an AI-harness built by Adobe, and uses Azure OpenAI GPT-4.1 and Claude on AWS Bedrock for AI reasoning, with Marketo MCP tools supporting execution of product actions.

**Governance:** AI-generated outputs remain within the user's environment and are subject to existing governance, residency, and retention controls.

**Transparency:** AI-generated outputs are reviewable through conversation and audit history to support user oversight.

## Access controls and rollout

### Import leads

**Function:** Processes user-supplied lead data for mapping, normalization, deduplication, and import into Marketo Engage.

### Program QA

**Function:** Evaluates Marketo programs against organizational rules defined by users in a Skill markdown file, such as naming standards, approval status, email compliance, and flow logic.

### Create program from brief

**Function:** Uses natural-language prompts to generate Marketo program structures, including smart campaigns, flow steps, and content placeholders, directly within the user's environment.

### Callable agents

**Function:** Executes flow action-triggered AI actions within Smart Campaign flow steps for use cases such as validation, normalization, and bot detection.

### Lead investigation

**Function:** Provides conversational analysis of why a person did or did not progress to a milestone by examining flow-step execution and smart-list membership.

### Measurement and analytics

**Function:** Surfaces campaign and program performance analysis, including recommendations and root-cause insights.

### Product knowledge

**Function:** Provides Marketo best-practice and how-to guidance through a shared knowledge layer used across the agent experience.

## Use cases

Besides the ones listed, consider using Marketo AI to diagnose and troubleshoot complex operational issues (CRM sync failures, webhook errors, email delivery root-cause analysis, field mismatches), conduct audits across your account (email deliverability, subscription center compliance, smart campaign reviews, scoring model assessments), and accelerate program creation from briefs and templates (event programs, multi-language email campaigns, webinar setups). Marketo AI is designed to provide AI-assisted lead classification and data enrichment at scale, performance analytics with remediation recommendations, and guided debugging of technical configurations such as Velocity scripts and lifecycle models.

## Availability and rollout status

**Eligibility:** Initial user enablement is limited to eligible Marketo Engage users who have accepted the Adobe Gen AI Rider.

**Provisioning:** Access is managed through existing product enablement controls and feature-flag provisioning within the Marketo Engage experience.

**Rollout model:** Deployment progresses through Alpha and Private Beta before broader Public Beta expansion.

**Geographic scope:** The initial release is intended for global Marketo Engage users, excluding mainland China.

**Industry scope:** The current rollout does not include vertical-specific capabilities for highly regulated industries such as healthcare, financial services, government, or defense.

## Documentation and support

**Documentation:** Experience League documentation is expanding as part of general availability readiness.

**Support model:** The current support approach includes user feedback intake, office hours, and a Marketo AI Experience League community.

**Service monitoring:** Adobe identifies observability, feedback dashboards, and quality evaluation mechanisms as important components of launch maturity and ongoing improvement.

## Out-of-scope data and exclusions

**No new special-category data:** Marketo AI does not introduce new processing for health, financial, precise-location, biometric, or other special-category data.

**No new sharing pathway:** The service does not create a new user-to-user content sharing mechanism.

**User-contained outputs:** AI-generated outputs remain within the user's existing Marketo Engage environment under existing governance controls.

**Current exclusions:** The initial rollout excludes mainland China and does not provide vertical-specific capabilities for highly regulated industries.

## Use of Azure OpenAI and Claude on AWS Bedrock

This section explains how Azure OpenAI supports Marketo AI workflows. Any related diagrams or flow descriptions should be read together with the controls described here, including limitations on data scope, user oversight, and model training.

**Purpose:** Azure OpenAI GPT-4.1 is used for conversational reasoning and orchestration of agent-driven workflows.

**Data scope:** Inputs are limited to standard B2B marketing data already present in the user's Marketo Engage environment and necessary to fulfill the requested workflow.

**AI output:** AI outputs are determined by user prompts and configuration, and Marketo AI features do not make any decisions autonomously without user configuration.

**Training:** Adobe does not use user data to train or fine-tune Azure OpenAI models for this service.

**User oversight:** AI-generated outputs remain reviewable within Marketo Engage through conversation and audit history capabilities.

## Data retention and storage

**User-contained outputs:** AI-generated outputs such as cleaned lead lists, QA reports, generated program structures, and normalized data remain within the user's Marketo Engage environment.

**Governance alignment:** Output data remains subject to the user's existing data governance, residency, and retention controls in Marketo Engage.

**No new cross-user store:** The service does not introduce a separate user-to-user data-sharing pathway.

## Data processing and storage locations

This section summarizes the environments in which Marketo AI operates and where processing occurs. If the document includes regional diagrams or infrastructure visuals, those materials should be understood as high-level representations of service location and processing flow rather than exhaustive network schematics.

**Application environment:** Marketo AI operates within the user's existing Adobe Marketo Engage environment.

**AI processing:** Marketo AI uses Azure OpenAI GPT-4.1 and Claude on AWS Bedrock for conversational reasoning and task orchestration.

**User data location:** User data and AI-generated outputs remain within the user's Marketo Engage environment and are subject to the user's existing residency, governance, and retention controls.

**No separate cross-user store:** The service does not introduce a separate user-to-user data-sharing or storage layer.

## Data scope by workflow type

The data processed by Marketo AI is determined by the user's usage pattern and the specific workflow invoked. Not all workflows require processing lead-level data.

### Workflows that leverage campaign metadata only (no lead information)

* Program creation from brief — generates program structures, smart campaigns, flow steps, and content placeholders from natural-language instructions
* Email cloning and translation — duplicates and translates email HTML content, subject lines, and marketing copy across language variants
* Campaign auditing — reviews smart campaign configurations, trigger/filter definitions, flow logic, and naming conventions
* Program QA validation — evaluates programs against user-defined rules for compliance, approval status, and structural completeness
* Subscription center and program architecture reviews — analyzes campaign logic and program structure
* Product knowledge and best-practice guidance — provides Marketo how-to responses from a shared knowledge layer

### Workflows that leverage lead-level records (standard B2B contact fields)

* Lead investigation and troubleshooting — examines user-supplied individual lead field values, activity history, and lifecycle progression to diagnose why a lead did or did not reach MQL status, or qualify for a marketing campaign
* Lead import and normalization — processes user-supplied lead data including names, email addresses, phone numbers, and company fields for mapping, cleansing, and deduplication
* Lead classification and enrichment — evaluates lead records against user-defined scoring or classification logic (e.g., Valid vs Spam leads for database health, Personas for personalization purposes, Business Leads with corporate email leads vs consumer leads)
* Data quality and deliverability audits — analyzes lead-level engagement data, bounce patterns, and duplicate records to identify database health issues
* Campaign performance analytics — surfaces lead engagement patterns, conversion data, and audience composition to support performance analysis

### Data minimization by design

* In all cases, data sent to the AI model is limited to what is required to fulfill the specific user request within that workflow
* Marketo AI follows the user's existing Marketo Engage permissions — it does not provide access to lead records, fields, or programs beyond what the user has permission to view through the product UI
* Users who wish to limit lead-data processing can restrict access to the tool's investigative workflows through existing Marketo Engage role and permission controls while retaining full access to structural and administrative AI capabilities

### No incremental data exposure

The AI operates as an accelerator on existing user permissions, not an escalation path. A user who cannot view certain lead fields, programs, or partitions in the Marketo Engage UI also cannot surface that data through Marketo AI. The service does not bypass partition rules, field-level permissions, or workspace restrictions.
