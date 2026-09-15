---
description: Description goes here.
title: Organizational rules
---
# Organizational rules {#organizational-rules}

Organizational Rules define your marketing operations standards and governance requirements in a single document that guides Coworker across program creation, campaign planning, and validation workflows.

## What are Organizational Rules? {#what-are-organizational-rules}

Organizational Rules are a markdown-based configuration document that capture your organization's campaign standards:

* Naming conventions for programs, emails, and smart campaigns
* Required assets and structure (folders, tokens, reports)
* Compliance requirements (unsubscribe links, UTM parameters, exclusion filters)
* Best practices (email design, smart list configuration)

Every Marketo instance includes default Organizational Rules. You can customize them to reflect your organization's specific governance needs.

## Where Organizational Rules are used {#where-organizational-rules-are-used}

Organizational Rules guide Coworker across three skills:

| Skill | How rules are applied |
| --- | --- |
| Build Programs | Rules guide the creation of program structure, naming, and initial setup. Coworker flags any compliance issues in your brief before creating the program. |
| Plan Campaigns | Rules inform how Coworker structures smart campaigns, filters, and flow steps based on your standards. |
| Validate Programs | Rules define what Coworker checks when validating programs before activation. |

## How to access and customize Organizational Rules {#how-to-access-and-customize-organizational-rules}

1. In your My Marketo, click the **Coworker for Marketo Engage** tile.
1. Click the gear icon.
1. Select the **Organizational Rules** tab.
1. Review the default rules (these come pre-populated with marketing operations best practices).
1. Edit the rules to match your organization's:

   * Naming conventions (programs, emails, campaigns)
   * Required folder structure
   * Required tokens and fields
   * Compliance and exclusion standards

1. Update the version number when you make changes.
1. Save your changes. All Coworker skills will use your customized rules immediately.

## Organizational Rules structure {#organizational-rules-structure}

Organizational Rules are formatted in markdown with YAML frontmatter:

```markdown
---
name: Your Organization Name — Marketo Campaign Governance
version: 1.0
enabled: true
customized: true
---

# Naming Conventions

## Programs
- Pattern: {{REGION}}_FY{{YEAR}}_{{QUARTER}}_{{TYPE}}_{{DATE}}_{{NAME}}
- Example: AMER_FY25_Q2_WBR_250315_Product_Launch_Webinar
- Region codes: AMER, EMEA, APAC, GLOBAL

## Emails
- Pattern: {{PROGRAM_NAME}}_{{SEQUENCE}}_{{PURPOSE}}
- Example: Product_Launch_01_Invitation

# Program Structure

## Required Local Folders
- 01 Emails
- 02 Smart Campaigns
- 03 Reports

## Required Tokens
- {{my.eventDate}}
- {{my.replyToEmail}}

# Email Compliance

## ⚠️ REQUIRED Elements
- Unsubscribe link in footer
- Company name and physical address
- All external links include UTM parameters

## Recommended Elements
- Alt text on all images
- Mobile-responsive design (600px max-width)
```

## Best practices for Organizational Rules {#best-practices-for-organizational-rules}

* **Start with defaults**: Review the default rules before customizing. They reflect industry best practices for marketing operations.
* **Keep rules focused**: Only include requirements that matter to your organization. Unnecessary rules create noise and reduce compliance scores unnecessarily.
* **Use both automated and manual checks**:

  * Automated checks — naming conventions, required folders, token usage (Coworker can verify these)
  * Manual checks — email visual design, brand compliance, campaign logic (Coworker will flag these as manual review steps)

* **Balance strictness with flexibility**: Rules that are too strict may slow program creation. Rules that are too loose won't catch important compliance issues.
* **Version your rules**: Update the version number when you make significant changes so your team knows governance standards have been updated.
* **Communicate changes**: When you update Organizational Rules, let your marketing ops team know what changed and why.

## What Coworker can and cannot validate {#what-coworker-can-and-cannot-validate}

Coworker CAN validate (automated checks):

* Naming conventions match your patterns
* Required folder structure exists
* Required tokens are in place
* Email has unsubscribe link and required footer elements
* External links include UTM parameters
* Smart campaign names follow conventions

Coworker CANNOT validate (manual review required):

* Smart list filter logic (API limitation — you must configure filters manually)
* Smart campaign flow step logic (API limitation — you must configure flows manually)
* Email visual rendering and responsiveness (requires visual inspection)
* Brand compliance and messaging tone (requires human judgment)
* Dynamic content segmentation rules (API limitation)

When Coworker encounters something it cannot validate, it flags it as a manual review step in the workflow.

## Compliance scoring {#compliance-scoring}

When you use Validate Programs, Coworker calculates a compliance score based on:

* **Passed checks** — Coworker verified compliance and found no issues
* **Failed checks** — Coworker found violations of your Organizational Rules
* **Manual review steps** — Items that require human verification (these do NOT count against your score)

A program can have 100% compliance and still require manual review steps — they are excluded from the score calculation.

## Examples of Organizational Rules customization {#examples-of-organizational-rules-customization}

**Example 1: Strict naming convention**

```markdown
## Programs
Pattern: {{COUNTRY}}-{{BUSINESS_UNIT}}-{{CAMPAIGN_TYPE}}-FY{{YEAR}}-{{QUARTER}}-{{DATE}}
```

Use this if your organization requires strict governance across regions and business units.

**Example 2: Flexible naming with required prefix**

```markdown
## Programs
Pattern: {{PREFIX}}_* (where PREFIX = EMEA, AMER, APAC, GLOBAL)
Example: AMER_Q2_Product_Launch_Webinar_2025
```

Use this if you want consistency on region codes but flexibility on the rest.

**Example 3: Minimal rules (focus on compliance)**

```markdown
# Email Compliance — REQUIRED

- Unsubscribe link present
- CAN-SPAM physical address in footer
- Reply-to email configured
```

Use this if your organization prioritizes compliance over naming/structure consistency.

## Troubleshooting {#troubleshooting}

**Q: I updated Organizational Rules but Coworker is still using the old rules.**

A: Changes take effect immediately for new programs and validations. If you're working on an existing program, refresh your browser or start a new Coworker workflow to see the updated rules.

**Q: Can I revert to default rules?**

A: Yes. Go to **Settings** > **Organizational Rules** and click **Reset to Default**. Your custom rules will be replaced with the default rules.

**Q: My compliance score is low even though the program looks good.**

A: Check which checks are failing. Review your Organizational Rules to see if they're too strict for your current workflows, or if you need to adjust the program to meet your standards.
