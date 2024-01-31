---
description: Use a Conversational Flow Landing Page - Marketo Docs - Product Documentation
title: Use a Conversational Flow Landing Page
hide: yes
hidefromtoc: yes
feature: Dynamic Chat
---
# Use a Conversational Flow Landing Page{#use-a-conversational-flow-landing-page}

Embedding a Dynamic Chat Conversational Flow directly into a Marketo Engage Landing Page allows visitors to schedule a meeting through Dynamic Chat without having to fill out a form or interact with a chatbot.

>[!PREREQUISITES]
>
>Create a simple [Conversational Flow](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-conversational-flow.md) that only contains a **Meeting booking** card.

## Guided Landing Pages {#guided-landing-pages}

Embed the following code in your Guided Landing Page template: `<div class="mktoConversation" id="exampleConversation" mktoName= "Example Conversation"></div>`.

Open your Guided Landing Page template in the editor and select the Conversational Flow placeholder.

Click the Conversational Flow drop-down and select the CF you created in Step 1.

Always keep Delivery Type as **In-line**. Click **Insert**.

The Conversational Flow you just entered will appear as an Element on the right.

SCREENSHOT

>[!NOTE]
>
>At this time, the Conversational Flow will not appear in the main preview window. 

## Free-form Landing Pages {#free-form-landing-pages}

Text


NOTES FROM STEVE MEETING

guided lp, new div id for template, choose conv flow

freeform lp, bring over icon - caveat: add note--when you put cf on the editor, it doesn't show you a preview (no placeholder either) - "you won't see a preview" - on the sidebar they will see that the cf is on the page - guided lp lists it as an element - use "at this time" when explaining - feature goes live maybe week of 22nd

