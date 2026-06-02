---
description: Have a conversation with Marketo AI about your Marketo Engage performance data. Ask questions in plain language and get answers grounded in your Marketo environment.
title: Surface insights
badge: Beta
hide: true
---
# Surface insights {#surface-insights}

Surface insights lets you have a conversation about your Marketo performance data. Ask questions in plain language and get answers grounded in your Marketo environment.

>[!PREREQUISITES]
>
>* To use this feature you must first agree to the [Core Gen-AI terms and the supplemental terms](https://www.adobe.com/legal/terms/enterprise-licensing/genai-ww.html){target="_blank"}. Contact the Adobe Account Team (your account manager) for details.
>
>* You must have access to the programs and reports you are inquiring about.

>[!AVAILABILITY]
>
>This feature is currently in closed beta. Please do not disseminate this documentation.

## How to use {#how-to-use}

1. In your My Marketo, click the **Build with AI** tile.

1. In the prompt window, ask a performance question. Be specific about the timeframe or program if you have one in mind.

1. Review the summary Marketo AI returns. It will include key metrics like open rates, click rates, conversion rates, and lead counts depending on what you asked.

1. Ask follow-up questions to explore specific areas (for example, "Which email in that program had the highest click rate?" or "How does that compare to last quarter?").

## Use cases {#use-cases}

**Quarterly program review**: A demand gen manager is preparing for a campaign review meeting. They ask: "How did my Q2 nurture programs perform overall?" Marketo AI returns open rates, click-to-open rates, unsubscribe rates, and the number of people/leads that progressed to MQL across all Q2 nurture programs, with a note on which programs outperformed the group average.

**Comparing two campaigns**: A campaign manager ran two versions of a webinar invitation series with different subject lines. They ask: "How did the April webinar program compare to the March one in terms of registration rate?" Marketo AI returns the registration numbers for each and highlights the difference, so they can see which approach worked better.

**Finding top-performing content**: A marketing ops specialist wants to know which email assets drove the most engagement last month. They ask: "Which emails had the highest click rates in May?" Marketo AI returns a ranked list of email assets with click rates, so they can identify what resonated and inform future content decisions.

## Things to note {#things-to-note}

* Surface insights are based on the data available in your Marketo instance. If a program isn't tracked or a metric isn't captured, Marketo AI won't be able to report on it.
* Very large date ranges or broad questions may return high-level summaries rather than granular detail. For example, "How did all my programs perform over the last two years?"
* Marketo AI can surface data but cannot make changes to your programs or reports based on what it finds.
* For detailed custom reporting with specific filters and breakdowns, the Marketo built-in reporting tools or a BI integration may be more appropriate.
* Attribution across multi-touch campaigns requires proper program setup. Marketo AI reports on what's tracked, not infer attribution that wasn't configured.
