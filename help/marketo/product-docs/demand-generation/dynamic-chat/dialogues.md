---
description: Dialogues - Marketo Docs - Product Documentation
title: Dialogues
hide: yes
hidefromtoc: yes
---
# Dialogues {#dialogues}

Dialogues are the individual chat conversations you'll set up. Learn how to customize them visually, determine what pages they appear on, and decide what is said as well as who sees it.

## Create a New Dialogue {#create-a-new-dialogue}

1. Click **Dialogues**.

PICC

1. Click the **Create New** button.

PICC

1. Enter a name (description is optional), set the priority level, and click **Save**.

PICC

>[!NOTE]
>
>Priority level determines where the dialogue shows on your list (ex: priority = 1 means it will be at the very top).

## Audience Criteria {#audience-criteria}

Similar to Marketo Smart Lists, Audience Criteria attributes allow you to define your target audience. You can target known or unknown leads using inferred, lead, or company attributes (or a combination thereof).

There are _many_ attribute combinations to choose from. In this example we're targeting all known leads in California who work at a company with more than 50 employees.

1. Grab the Lead State attribute and drag it to the right.

PICC

1. _Is_ is set by default. In the Select Values field, type in CA (you can also click the drop-down and select from the list).

PICC

1. Grab the Company Size attribute and drag it to the right.

PICC

1. Click the operator drop-down and select Greater Than.

PICC

1. Type 50 and click elsewhere on the screen to save.

PICC

HOW TO CAPTURE ANON LEADS

NOTE - maybe mentioned how inferred works/show anon use case, lead email is empty

## Add Groups {#add-groups}

You have the option of grouping attributes as well, in case you want to have all of certain attributes along with "any" of another.

FINISH THIS

## Target {#target}

This is where you enter the specific URL(s) that you want a specific Dialogue to be shown on.

Acceptable formats:

* `http://website.com`
* `https://*.website.com`
* `http://website.com/folder/*`
* `https://*.website.com/folder/*`

>[!NOTE]
>
>Using an asterisk acts as a catch-all wilcard. So `https://*.website.com` would put the dialogue on every page of the site, including subdomains (ex: `support.website.com`). And `https://website.com/folder/*` would put the dialogue on every HTML page in the subsequent folder (ex: in this case let's say the folder is "sports," so: website.com/sports/baseball.html, website.com/sports/football.html, etc.).

## Stream Designer {#stream-designer}

The stream designer contains different cards you can add to shape the chat conversation.

<table>
 <tr>
  <td><strong>Message</strong></td>
  <td>Use when you want to make a statement with no response necessary (ex: "Hi! All items are 25% off today with code SAVE25").
</td>
 </tr>
 <tr>
  <td><strong>Question</strong></td>
  <td>Use when you want to ask a multiple choice question, of which you supply the available responses (ex: What type of vehicle are you interested in? Responses = SUV, Compact, Truck, etc.).</td>
 </tr>
 <tr>
  <td><strong>Information Capture</strong></td>
  <td>Use when you want to collect information. The  three fields to choose from are Email Address, Phone Number, and Text (which allows the visitor to write their own message).</td>
 </tr>
 <tr>
  <td><strong>Appointment Scheduler</strong></td>
  <td>Provides the visitor with a calendar of available dates to schedule a follow-up. Calendar availability reflects [the next agent in line](/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md#routing).</td>
 </tr>
 <tr>
  <td><strong>Goal</strong></td>
  <td>This is the only card the visitors won't see. It's for you to determine at which point a goal is achieved within the specific chat (ex: if collecting the visitor's email is your goal, place the Goal card after Info Capture in the Stream).</td>
 </tr>
</table>

POSSIBLE OWN SECTION

SHOW EXAMPLE(S) BELOW

## Reports {#reports}

Text
