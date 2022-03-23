---
description: Stream Designer - Marketo Docs - Product Documentation
title: Stream Designer
exl-id: aa44c7a5-f81b-4029-a1a4-5439bea83847
---
# Stream Designer {#stream-designer}

There are _many_ stream combinations you can create. This article contains an example where the marketer asks the site visitor if they have any product questions. If yes, the visitor can schedule an appointment. If no, the visitor is given the option to join a mailing list for future correspondence. The goal is either scheduling an appointment or collecting the visitor's email.

## Stream Designer Cards {#stream-designer-cards}

The stream designer contains multiple cards you can add to shape the chat conversation.

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
  <td>Provides the visitor with a calendar of available dates to schedule a follow-up. Calendar availability reflects <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md#routing">the next agent in line</a>.</td>
 </tr>
 <tr>
  <td><strong>Goal</strong></td>
  <td>This is the only card the visitors won't see. It's for you to determine at which point a goal is achieved within the specific chat (ex: if collecting the visitor's email is your goal, place the Goal card immediately after Info Capture in the stream).</td>
 </tr>
</table>

## Create a Stream {#create-a-stream}

1. After you've [created your dialogue](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target="_blank"}, click the **Stream Designer** tab.

   ![](assets/create-a-stream-1.png)

1. Drag and drop the Question card.

   ![](assets/create-a-stream-2.png)

1. Under Chatbot Response, word your question how you'd like.

   ![](assets/create-a-stream-3.png)

   >[!NOTE]
   >
   >Poke is set to on by default, which displays the opening question next to the chat icon without the visitor having to click on it to see it.

1. Enter your User Responses and click **Save**.

   ![](assets/create-a-stream-4.png)

1. For "Yes" we want to schedule an appointment, so below that option drag over the Appointment Scheduler card.

   ![](assets/create-a-stream-5.png)

1. In the column on the right, click **Save**.

   ![](assets/create-a-stream-6.png)

1. Since that's a goal, drag the Goal card below the Appointment Scheduler.

   ![](assets/create-a-stream-7.png)

1. Name your goal (or choose an existing one) and click **Save**.

   ![](assets/create-a-stream-8.png)

1. For "No" we want to see if they'll join the mailing list, so below that option drag over another Question card.

   ![](assets/create-a-stream-9.png)

1. Enter your response, and add response choices for the visitor. Click **Save** when done.

   ![](assets/create-a-stream-10.png)

   >[!NOTE]
   >
   >You can add more responses by clicking **Add Response**.

1. Below the "Yes" response, drag over the Info Capture card so you can collect the visitor's email.

   ![](assets/create-a-stream-11.png)

1. Click the **Type** drop-down and select **Email**.

   ![](assets/create-a-stream-12.png)

1. Enter a chatbot message and placeholder. Make sure the attribute is mapped to the appropriate field in Marketo and click **Save**.

   ![](assets/create-a-stream-13.png)

   <table>
    <tr>
     <td><strong>Type</strong></td>
     <td>The type of info you want to capture: Phone, Text, Email.</td>
    </tr>
    <tr>
     <td><strong>Chatbot Message</strong></td>
     <td>The message the visitor sees prompting them to provide the info.</td>
    </tr>
    <tr>
     <td><strong>Placeholder</strong></td>
     <td>Sample text helping the visitor see what to enter.</td>
    </tr>
    <tr>
     <td><strong>Map Response to Attribute</strong></td>
     <td>Allows you to sync the vistor's response to the corresponding field in their Person record in your Marketo subscription.</td>
    </tr>
   </table>

1. Since collecting their email is a goal, drag the Goal card below Info Capture.

   ![](assets/create-a-stream-14.png)

1. Name your goal (or choose an existing one) and click **Save**.

   ![](assets/create-a-stream-15.png)

1. Remember to add a response if they say "No." Drag a Message card below that option.

   ![](assets/create-a-stream-16.png)

1. Enter your message and click **Save**.

   ![](assets/create-a-stream-17.png)

1. Select the **Preview** toggle to preview your Dialogue.

   ![](assets/create-a-stream-18.png)

1. When you're ready to activate your Dialogue, click **Publish**.

   ![](assets/create-a-stream-19.png)

>[!NOTE]
>
>Before clicking Publish, remember to make sure you've [entered your target URL(s)](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/audience-criteria.md#target){target="_blank"}.

>[!MORELIKETHIS]
>
>* [Create a Dialogue](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target="_blank"}
>* [Audience Criteria](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/audience-criteria.md){target="_blank"}
>* [Reports](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/reports.md){target="_blank"}
