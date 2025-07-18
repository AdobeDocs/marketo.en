---
description: Stream Designer - Marketo Docs - Product Documentation
title: Stream Designer
feature: Dynamic Chat
exl-id: 310b1dff-dd93-48a6-85c2-64c58494ce48
---
# Stream Designer {#stream-designer}

There are _many_ stream combinations possible. This article contains an example where the marketer asks the site visitor if they have any product questions. If yes, the visitor can schedule an appointment. If no, the visitor is given the option to join a mailing list for future correspondence. They're also offered a free PDF. The ultimate goal is either scheduling an appointment or collecting the visitor's email.

>[!PREREQUISITES]
>
>Before you can use the Document card, you must first [set it up](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-pdf-embed-api.md){target="_blank"} in your Adobe account.

## Stream Designer Cards {#stream-designer-cards}

The Stream Designer contains multiple cards you can add to shape the chat conversation.

<table>
 <tr>
  <td style="width:25%"><strong>Message</strong></td>
  <td style="width:75%">Use when you want to make a statement with no response necessary (ex: "Hi! All items are 25% off today with code SAVE25").
</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Question</strong></td>
  <td>Use when you want to ask a multiple choice question, of which you supply the available responses (ex: What type of vehicle are you interested in? Responses = SUV, Compact, Truck, etc.).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Document</strong></td>
  <td>Allows you to embed PDF documents in Dialogues and track document engagement activity of visitors (how many pages were viewed, if the document was downloaded, and/or any search terms that were used).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Information capture</strong></td>
  <td>Use when you want to collect information (e.g., name, email address, job title, etc.). After you choose which field to attribute their response to, you can choose from letting the visitor type in their response, or select options from a picklist that you determine (tip: the latter can help with database cleanliness). You can also choose to overwrite whatever data you currently have listed for them with their response, or, skip the question entirely if you already have a value for them.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Meeting booking</strong></td>
  <td>Provides the visitor with a calendar of available dates to schedule a meeting. Choose the calendar availability via round robin, a specific agent, or using custom rules. Click <b>Add Attribute</b> if you want to capture the agent's name or email address and assign it to the chat visitor's person record for future querying (tip: create a <a href="/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md" target="_blank">custom field</a> to map the agent's info to as to not overwrite a standard Marketo Engage field).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Goal</strong></td>
  <td>This is the only card the visitors won't see. It's for you to determine at which point a goal is achieved within the specific chat (ex: if collecting the visitor's email is your goal, place the Goal card immediately after Info Capture in the stream).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Action&#42;</strong></td>
  <td>Similar to hidden fields in a form, with the action card you can populate any lead or company attribute (that has a <a href="/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md#string">string data type</a>) with implicit values that you'd like to capture against a lead record. You can add the action card at any point in the conversation and update respective attributes with a value or native tokens that automatically populate the respective value.
  <p><i>&#42; This card requires Dynamic Chat Prime. Please contact the Adobe Account Team (your Account Manager) for details.</i></td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Live chat</strong></td>
  <td>Use the live chat card when you want visitors to chat with a live agent.
  <li>The live chat card must be the last card in the branch.</li>
  <li>Visitors will be routed to an agent as soon as they reach this card in the stream, so it's recommended to precede this card with a question card asking visitors if they'd like to chat with a live agent.</li></td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Generated responses&#42;</strong></td>
  <td>Create a message for the visitor for when they reach a certain point in the conversation. Set a number of questions they can ask in one go to achieve your desired key performance indicator.
  <p><i>&#42; This card requires Dynamic Chat Prime. Please contact the Adobe Account Team (your Account Manager) for details.</i></td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Conditional branching</strong></td>
  <td>Create branches in your Dialogue flows based on different conditions. Present different content to different people in the same Dialogue based off of lead and company attributes in Marketo Engage.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>Conversational Flow</strong></td>
  <td>Streamline multiple steps in a flow within your Dialogues by using the Conversational Flow card.</td>
 </tr>
</table>

## Stream Designer Icons {#stream-designer-icons}

In the upper-right of the Stream Designer, you'll see a handful of icons. Here's what they do.

<table>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-1.png"></td>
  <td>Zooms in, creating larger cards</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-2.png"></td>
  <td>Zooms out, creating smaller cards</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-3.png"></td>
  <td>Opens a window for you to test your chat (press the same button to close)</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-4.png"></td>
  <td>Allows you to search card types or content within your stream</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-5.png"></td>
  <td>Arranges all of the cards in your stream</td>
 </tr>
</table>

## Create a Stream {#create-a-stream}

You can create streams for Dialogues or [Conversational Forms](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-overview.md){target="_blank"}. In this example, we'll create one for a Dialogue.

1. After you've [created your Dialogue](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}, click the **[!UICONTROL Stream Designer]** tab.

   ![](assets/stream-designer-6.png)

1. Drag and drop the _[!UICONTROL Question]_ card.

   ![](assets/stream-designer-7.png)

1. Under [!UICONTROL Chatbot Response], word your question how you'd like.

   ![](assets/stream-designer-8.png)

   >[!TIP]
   >
   >You can customize the experience for chat visitors!
   >
   >* Click the "insert HTML" icon `</>` to insert your own HTML for the desired look and feel of the conversation.
   >
   >* Use tokens for known chat visitors to personalize their experience (ex: Hello `{{lead.leadFirstName:""}}`). Click the curly bracket icon `{}` and make your selection. Add a default value between the quotes if you want anonymous visitors to see something generic (ex: Hello `{{lead.leadFirstName:"there"}}`).

   >[!NOTE]
   >
   >Poke is set to on by default, which displays the opening question next to the chat icon without the visitor having to click on it to see it. Poke is only available on the first card in the conversation.

1. Enter your User Responses and click **[!UICONTROL Save]**.

   ![](assets/stream-designer-9.png)

   >[!NOTE]
   >
   >**[!UICONTROL Edit Stored Values]** is an optional step for those who'd like to store a different value in the database than what's being displayed to visitors in the chatbot for mapped attributes in the Question card (ex: visitor sees "Search Engine Optimization," you store that value as "SEO.").

1. For "Yes" we want to book a meeting, so below that option, drag over the _Meeting booking_ card.

   ![](assets/stream-designer-10.png)

1. Choose your routing option and click **[!UICONTROL Save]**.

   ![](assets/stream-designer-11.png)

1. Since that's a goal, drag the _[!UICONTROL Goal]_ card below the Meeting booking.

   ![](assets/stream-designer-12.png)

1. Name your goal (or choose an existing one) and click **[!UICONTROL Save]**. Assigning a conversation score is optional.

   ![](assets/stream-designer-13.png)

1. For "No" we want to see if they'll join the mailing list, so below that option drag over another [!UICONTROL Question] card.

   ![](assets/stream-designer-14.png)

1. Enter your response, and add response choices for the visitor. Click **[!UICONTROL Save]** when done.

   ![](assets/stream-designer-15.png)

   >[!NOTE]
   >
   >You can add more responses by clicking **[!UICONTROL Add Response]**.

1. Below the "Yes" response, drag over the _Info Capture_ card so you can collect the visitor's email.

   ![](assets/stream-designer-16.png)

1. Click the drop-down and select **[!UICONTROL Email Address]**.

   ![](assets/stream-designer-17.png)

1. Enter a chatbot message and placeholder. If there's already a value for this attribute in your database, choose whether you want to skip, or have this data overwrite it. Click **[!UICONTROL Save]** when done.

   ![](assets/stream-designer-18.png)

1. Since collecting their email is a goal, drag the _[!UICONTROL Goal]_ card below Info Capture.

   ![](assets/stream-designer-19.png)

1. Name your goal (or choose an existing one) and click **[!UICONTROL Save]**.

   ![](assets/stream-designer-20.png)

1. Remember to add a response if they say "No." One option is to drag a Message card below and say "thanks anyway." But in this example, we'll provide them with a free PDF document instead.

   ![](assets/stream-designer-21.png)

1. In this example we'll create a new document. Give it a name, enter the URL to the PDF you already have hosted, and click **[!UICONTROL Save]**.

   ![](assets/stream-designer-22.png)

1. When you're ready to activate your Dialogue, click **[!UICONTROL Publish]**.

   ![](assets/stream-designer-23.png)

>[!NOTE]
>
>Before clicking [!UICONTROL Publish], remember to make sure you've [entered your target URL(s)](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/audience-criteria.md#target){target="_blank"}.

>[!MORELIKETHIS]
>
>* [Create a Dialogue](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}
>* [Audience Criteria](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/audience-criteria.md){target="_blank"}
>* [Adobe PDF Embed API](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-pdf-embed-api.md){target="_blank"}
