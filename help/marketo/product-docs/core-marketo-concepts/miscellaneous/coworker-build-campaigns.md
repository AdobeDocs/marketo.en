---
description: A step-by-step guide to building an email campaign in CX Enterprise Coworker, from writing prompts to reviewing and exporting your campaign.
title: Build and generate email campaigns
---
# Build and generate email campaigns {#build-and-generate-email-campaigns}

Learn how to build and review complete email campaigns in minutes.

## Before you start

Make sure you have:

* An active CX Enterprise Coworker account ([sign up here](https://coworker-essentials.experience.adobe.com/) if you have not already).

* Your brand set up under **Your stuff** > **Brands**.

* (Optional but recommended) An HTML email template uploaded under **Your stuff** > **Email templates**.

* An audience CSV ready to upload.

* A clear idea of your campaign goal (for example, "win back lapsed customers," "invite trial users to a webinar.").

>[!TIP]
>
>If you are new to writing prompts for marketing campaigns, take two minutes to skim _Prompting CX Enterprise Coworker: best practices_ before you start.

## Step 1: Start a new chat

From the home page, you have three ways to begin:

* Type a prompt in the central prompt bar.
* Pick a ready-made campaign template from the templates section below the prompt bar.
* Use a "help me prompt" option from the dropdown in the prompt bar to have CX Enterprise Coworker guide you through writing your prompt.

[SCREENSHOT: Home page with prompt bar, template row, and "help me prompt" option highlighted]

[FOR KEITH: Brief description of each option and when to use which. Recommend templates for first-timers, free-form prompts for marketers who know what they want, and "help me prompt" for anyone in between.]

## Step 2: Write your prompt

A strong CX Enterprise Coworker prompt includes:

* The campaign goal (what you are trying to achieve).
* The audience (who it is for, or where the audience data is coming from).
* The format and structure (number of emails, cadence, tone).
* Brand or context cues (references to your brand, product, or campaign).

Example:

```
"Create a win-back email series for customers who bought last year but haven't returned. Use the CSV I uploaded. Include 2–3 emails that feel seasonal and remind them to shop again."
```

[FOR KEITH: Can add 2–3 more prompt examples spanning B2B and B2C to give variety. Pull from the Use cases from our collection doc for consistency.]

[SCREENSHOT: Prompt bar with example prompt typed in]

## Step 3: Upload your audience

[FOR KEITH: Walkthrough of CSV upload. Cover: - Where the upload button is in the UI. - Required columns and format expectations. - Personalization fields CX Enterprise Coworker can use (first name, last order date, product category, etc.). - Link to sample CSV. - What happens if data is messy or fields are missing.]

[SCREENSHOT: CSV upload flow]

>[!TIP]
>
>Exclude any contacts you do not want to email (unsubscribed users, internal addresses, test accounts) before uploading. While we will progressively enable the functionality to 'exclude' specific users or 'add attributes' during the course of the trial, it is not immediately available from the launch date.

## Step 4: Add a brief and reference materials

[FOR KEITH: Explain how to attach a brief, brand reference docs, or other context. Cover: - Supported file types. - How CX Enterprise Coworker uses this information (extracted into the prompt context, applied to content generation, etc.). - File size limits, if any

Here's a deep-dive of my session at summit where I go over this: https://business.adobe.com/summit/2026/sessions/3-2-1-launch-project-halo-revealed-s232.html   
Limitations – I can connect you with the engg – Neha Pullabhotla, who will be able to help us on specifics here. ]

[SCREENSHOT: Brief / reference attachment UI]

## Step 5: Generate the campaign

Click **Generate campaign**. CX Enterprise Coworker will:

* Generate a structured campaign plan.
* Ask for your target audience, which will also be used for content personalization.
* Draft personalized email content for each step.
* Dynamically build the journey along the way.
* Assemble it all on a single campaign board.

[FOR KEITH: Description of what the campaign board looks like and what's on it. Cover the plan view, the journey view, and the content view. Note how long generation can typically take – which depends on the # of touch points in their journey. Call out that when they open an editor for the workflow or for the email, they're conversation will show them this so they're in context of the specific component, how the email editor is a point & click email editor with the limitation that it is not intended to be a full-fledged designer, users can edit images in Adobe Express or even connect to Google Drive or AEM Assets using Adobe Express, All their image assets are stored in Express, they re-generate images within our email editor with Firefly in-line, or replace them with a local image from their computer. They can switch out the HTML template & regenerate the content, and finally send themselves s 'Test email' to validate what their end customer will receive]

[SCREENSHOT: Generated campaign board with plan, journey, and content visible]

## Step 6: Review and refine

The conversational interface makes refinement straightforward. To make changes, talk to CX Enterprise Coworker:

* "Make the subject line in email 2 more urgent."
* "Shorten the body copy across all emails."
* "Swap the audience to customers from the West region only."
* "Add a fourth email with a stronger CTA."
* "Change the wait from 3 days to 5 days."

[FOR KEITH: Cover how to make changes both via chat and via direct editing. Explain how artifacts update in place. Mention no ability to add more nodes to the workflow via the editor exists, nor does versioning currently exist. For best results, we also encourage them to request any changes for their overall workflow at the very beginning when their plan is created]

[SCREENSHOT: Conversational refinement in action — show a before-and-after of an email after a chat request]

## Step 7: Send a proof email

Before launching, send the campaign to yourself or a member of your team to review in a real inbox.

[FOR KEITH: Steps for sending a proof. Cover: - Where the proof button is. - Who can receive proofs (currently only the signed in user - Whether all emails in the journey are sent, or just one at a time (currently just 1 at a time, unless the user says 'proof this series' in the chat. - What to check for in the proof (rendering, links, personalization tokens, unsubscribe footer).]

[SCREENSHOT: Send proof flow]

## Step 8: Launch or export

When you are satisfied with the campaign, you have a few options:

>[!NOTE]
>Launch is not currently available at release but will be enabled within two weeks of the initial release, pending legal clearance.

* Launch the campaign.
* Export individual emails as HTML.
* Export the full campaign as a Word document or PDF for team review.

[FOR KEITH: Details on each option, and any pre-launch checks CX Enterprise Coworker runs (compliance, broken links, missing personalization fields, etc.).]

[SCREENSHOT: Launch / export options]

## Common questions

[FOR KEITH: 4–6 FAQs based on early user feedback. Suggested starters – to discuss with our Eng team:
* "Why does the first response take so long?  
* "What if CX Enterprise Coworker's output isn't quite right?"  
* "Can I edit emails directly, or only via chat?"  
* "How do I save a campaign without launching it?"  
* "What if my audience CSV has errors?"  
* "Can I duplicate or remix a campaign?"  
* "How do I share a draft campaign with a teammate for review?"]
