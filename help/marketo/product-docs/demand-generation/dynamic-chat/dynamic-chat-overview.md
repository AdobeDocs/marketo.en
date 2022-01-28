---
description: Dynamic Chat Overview - Marketo Docs - Product Documentation
title: Dynamic Chat Overview
hide: yes
hidefromtoc: yes
exl-id: 73ab651e-bb11-459d-aa6a-39d9e208d512
---
# Dynamic Chat Overview {#dynamic-chat-overview}

Dynamic Chat allows you to leverage an easy-to-use interface to target both people and accounts visiting your website. Collect relevant content such as name, contact information, and free text. Site visitors can also book meetings with your Sales Team. Dynamic Chat activity and engagement data can be used to add members to Marketo programs and trigger cross-channel activities.

   >[!NOTE]
   >
   >Dynamic Chat is in the process of being rolled out gradually and is currently in limited availability. This page will be updated with general availability (GA) details as they become available.

   >[!TIP]
   >
   >Visit [this page](https://dcweb.z20.web.core.windows.net/) to view tutorial videos as well as a recorded demo of Dynamic Chat.

## Integrations {#integrations}

A key component of Dynamic Chat is its ability to natively interface with your Marketo subscription. In order to leverage the full capability of this integration, you’ll first need to initiate the data sync. Depending on the size of your Marketo database, it may take up to 24 hours for data for the initial, [one-time sync](/help/marketo/product-docs/demand-generation/dynamic-chat/connect-dynamic-chat-to-marketo.md) to complete.

The following is synced:

* Person field data
* Company field data
* Activity data

## Dialogues {#dialogues}

Dialogues represent a single chat engagement. Think of it as a container with all the stuff you need to have an engaging chat dialogue to your website visitors. In each Dialogue, you can specify which page(s) you’d like the Dialogue to appear on, to whom you'd like it to be shown to, and the content and flow of the Dialogue itself. Additionally, you can find metrics to see how well your Dialogue is performing. [Learn more about Dialogues](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues.md).

## Configuration {#configuration}

In the Configuration tab, customize the look and feel of your various Dialogues. Change font, colors, response time, and more! [Learn more about Configuration](/help/marketo/product-docs/demand-generation/dynamic-chat/configuration.md).

## Calendar {#calendar}

In the Calendar tab, connect your (Outlook or Gmail) calendar for use in appointment scheduling in the chatbot. Once a user’s calendar is connected to Dynamic Chat, that user will be added to the queue and their calendar will be available for website visitors to schedule appointments on.

You can also customize the body of the invite that's sent to the visitor when they schedule an appointment on the user’s calendar.

## Meetings {#meetings}

This is where you'll see all of the appointments that have been scheduled by website visitors through your various Dialogues. Here you’ll find the email address of the person that booked the appointment, which agent they booked the appointment with, when the appointment is scheduled to occur, and whether the meeting has happened or not.

## Routing {#routing}

This is where you can see a list of all the agents that have connected their calendars as well as what order they'll be presented to website visitors. Meetings go round robin style, so if you have five agents and agent three took the last meeting, agent four will get the next one, followed by agent five, then back to agent one.

## FAQ {#faq}

**Does Dynamic Chat allow for live chat?**

No, it only utilizes pre-determined responses.

**How can I target anonymous people?**

In your dialogue, you would need to use the _Person Email is Empty_ attribute.

**Do you support AI/NLP functionality?**

We do not support AI/NLP functionality.

**How long is data stored for reporting?**

90 days.

**Does Dynamic Chat offer any languages besides English?**

Not at this time.
