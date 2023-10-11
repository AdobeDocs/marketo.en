---
description: Dynamic Chat FAQ - Marketo Docs - Product Documentation
title: Dynamic Chat FAQ
feature: Dynamic Chat
exl-id: 7b31afc3-77f4-46fb-9f0e-8cb9d60f3ffb
---
# Dynamic Chat FAQ {#dynamic-chat-faq}

See below for answers to some frequently asked questions about Dynamic Chat.

**Can I install Dynamic Chat anywhere on my company website or does it only work on Marketo landing pages?**

The Dynamic Chat JavaScript snippet can be installed on any website as well as Marketo landing pages.

**How long is data stored for reporting?**

90 days. For a full list of limits/parameters, please visit the Marketo Engage [Product Description page](https://helpx.adobe.com/legal/product-descriptions/adobe-marketo-engage---product-description.html){target="_blank"}.

**Does Dynamic Chat support any languages besides English?**

Yes. Dynamic Chat supports the following languages: French, German, Japanese, Spanish, Italian, Brazilian Portuguese, Korean, Simplified Chinese, and Traditional Chinese. Learn more in [Changing the Language](#changing-the-language).

**Do you support AI/NLP functionality?**

We do not support AI/NLP functionality.

**How can I target anonymous people?**

In your dialogue, you would need to use the _Person Email is Empty_ attribute.

**What qualifies as an engaged conversation?**

An engaged conversation occurs as soon as a visitor responds to the bot in a Dialogue or Conversational Flow. If the visitor opens the chatbot but does not respond to the bot (e.g., select a response or submit information), it does not count as an engagement.

**What happens if I hit my monthly engaged conversation limit?**

When you reach your monthly engaged conversation limit, all published Dialogues and Conversational Flows will stop triggering until you increase your limit or your limit resets at the beginning of the next month.

**How will I know when I am nearing my engaged conversation limit?**

When you've reached 90% of your engaged conversation limit, Dynamic Chat admins will receive an email notification and all users will see a banner notification in Dynamic Chat.

**If a visitor engages with a Dialogue and then subsequently connects with a live agent, does that count as one engagement or two?**

For customers on the Select package, this will count as two separate engagements&mdash;one for the Dialogue engagement and one for the live chat engagement. For customers on the Prime package, live chat engagements are not counted separately, so this would only count as one engagement.

**How often does the engaged conversation limit get reset?**

The engaged conversation limit is reset on the first of each calendar month.

**Why doesn't the chatbot come back after I've finished a conversation?**

Dialogues are designed to be shown to a visitor only once. So as soon as a visitor reaches the end of any given branch in a Dialogue, that Dialogue is considered complete and will never be shown to that visitor again.

**When I click the Dynamic Chat tile in My Marketo and log in to Adobe Experience Cloud, why do I get the following message? "_It seems that your Adobe ID is not linked with your Adobe Experience Cloud solution accounts_."**

This most likely indicates that you haven't been added as a Dynamic Chat user in the Adobe Admin Console. Please contact either a system administrator for your Adobe org or a product administrator for Dynamic Chat to request access to Dynamic Chat.

**How do I access the transcript for an engaged conversation?** 

Dynamic Chat transcripts can be accessed for any known lead that has engaged with a Dynamic Chat Dialogue via the "Engaged with Dialogue" activity in Marketo Engage.

**Once a visitor engages in a Dialogue, can they restart the conversation or go back to a previous question?**

There is currently no systematic way to restart a conversation or go back to a previous point, but this is on the Dynamic Chat roadmap.

**Does Dynamic Chat integrate with Salesforce?** 

Dynamic Chat integrates with Salesforce via the Marketo Engage Salesforce integration.

**My calendar is connected in Dynamic Chat and I'm included in the routing rules, so why am I not getting any meetings?**

This most likely indicates that your calendar connection needs to be re-authenticated. This most often occurs when you change your password for your calendar provider and Dynamic Chat loses connection. You can simply go to the Agent Settings page in Dynamic Chat and click "Reauthenticate calendar."

**What is the difference between a Dialogue and a Conversational Flow?**

A Dialogue is a conversation that is automatically displayed to web visitors who meet a defined set of targeting criteria. A Conversational Flow is only displayed to visitors who perform a specific action on the web, such as pressing a button.

**Can I use Dynamic Chat without Marketo Engage?**

No. While Dynamic Chat is a separate application from Marketo Engage, the two are inextricably linked.
