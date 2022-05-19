---
description: Dynamic Chat Overview - Marketo Docs - Product Documentation
title: Dynamic Chat Overview
exl-id: 73ab651e-bb11-459d-aa6a-39d9e208d512
---
# Dynamic Chat Overview {#dynamic-chat-overview}

Dynamic Chat allows you to leverage an easy-to-use interface to target both people and accounts visiting your website. Collect relevant content such as name, contact information, and free text. Site visitors can also book meetings with your Sales Team. Dynamic Chat activity and engagement data can be used to add members to Marketo programs and trigger cross-channel activities.

   >[!NOTE]
   >
   >Dynamic Chat is in the process of being rolled out gradually and is currently in limited availability. This page will be updated with general availability (GA) details as they become available.

   >[!TIP]
   >
   >Visit [this page](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dynamic-chat-overview.html) to view tutorial videos of Dynamic Chat.

## Integrations {#integrations}

A key component of Dynamic Chat is its ability to natively interface with your Marketo subscription. In order to leverage the full capability of this integration, you’ll first need to initiate the data sync. Depending on the size of your Marketo database, it may take up to 24 hours for data for the initial, [one-time sync](/help/marketo/product-docs/demand-generation/dynamic-chat/connect-dynamic-chat-to-marketo.md) to complete.

The following is synced:

* Person field data
* Company field data
* Activity data

## Dialogues {#dialogues}

Dialogues represent a single chat engagement. Think of it as a container with all the stuff you need to have an engaging chat dialogue to your website visitors. In each Dialogue, you can specify which page(s) you’d like the Dialogue to appear on, to whom you'd like it to be shown to, and the content and flow of the Dialogue itself. Additionally, you can find metrics to see how well your Dialogue is performing. [Learn more about Dialogues](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/dialogue-overview.md){target="_blank"}.

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

**Can I install Dynamic Chat anywhere on my company website or does it only work on Marketo landing pages?**

The Dynamic Chat JavaScript snippet can be installed on any website as well as Marketo landing pages.

**How long is data stored for reporting?**

90 days (see the full list of limits [below](#limits-in-dynamic-chat)).

**Does Dynamic Chat allow for live chat?**

No, it only utilizes pre-determined responses.

**How can I target anonymous people?**

In your dialogue, you would need to use the _Person Email is Empty_ attribute.

**Do you support AI/NLP functionality?**

We do not support AI/NLP functionality.

**Does Dynamic Chat offer any languages besides English?**

Not at this time.

## Limits in Dynamic Chat {#limits-in-dynamic-chat}

<table>
  <th>Parameter</th>
  <th>Description</th>
  <th>Limit</th>
 <tr>
  <td>Total Dialogues</td>
  <td>Total number of Dialogues (published and draft)</td>
  <td>500</td>
 </tr>
 <tr>
  <td>Published Dialogues</td>
  <td>Number of published Dialogues saved</td>
  <td>100</td>
 </tr>
 <tr>
  <td>Target URLs per Dialogue</td>
  <td>Number of Target URLs that can be added to a single Dialogue</td>
  <td>20</td>
 </tr>
 <tr>
  <td>Attributes per Dialogue</td>
  <td>Number of attributes that can be added to audience criteria for a single Dialogue</td>
  <td>100</td>
 </tr>
 <tr>
  <td>Groups</td>
  <td>Number of groups that can be added to a single Dialogue</td>
  <td>10</td>
 </tr>
 <tr>
  <td>Attributes per Group</td>
  <td>Number of attributes that can be added to a group</td>
  <td>10</td>
 </tr>
 <tr>
  <td>Cards</td>
  <td>Number of cards that can be added to the canvas per Dialogue</td>
  <td>500</td>
 </tr>
 <tr>
  <td>Anonymous Lead Data Retention Period</td>
  <td>Duration for how long information of an anonymous lead without any engagement will be retained</td>
  <td>90 days</td>
 </tr>
 <tr>
  <td>Goal Activity Retention Period</td>
  <td>Amount of time goal activity data is retained</td>
  <td>24 months</td>
 </tr>
 <tr>
  <td>Document Activity Retention Period</td>
  <td>Amount of time document activity data is retained</td>
  <td>24 months</td>
 </tr>
 <tr>
  <td>Interacted w/ Dialogue Activity Retention Period</td>
  <td>Amount of time interacted with Dialogue activity data is retained</td>
  <td>90 days</td>
 </tr>
 <tr>
  <td>Meeting Booking Activity Retention Period</td>
  <td>Amount of time meeting booking activity will be stored in Dynamic Chat</td>
  <td>24 months</td>
 </tr>
</table>
