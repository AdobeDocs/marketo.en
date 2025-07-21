---
description: Callback Functions - Marketo Docs - Product Documentation
title: Callback Functions
feature: Dynamic Chat
exl-id: 5ae7f6cb-5c57-4257-8a1a-992c9602cfaa
---
# Callback Functions {#callback-functions}

You can use Dynamic Chat widget callback functions to send conversation events to any third-party platforms.

## Getting Started {#getting-started}

This event indicates the Dynamic Chat widget is ready for use and is fired when all scripts related to Dynamic Chat are loaded in the webpage.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    // code here will execute when chatbot scripts are loaded in a webpage 
}); 
```

## Conversation Events {#conversation-events}

These events are related to a conversation that is targeted on a specific page for a specific visitor.

### Conversation Triggered

A conversation (e.g., a Dialogue) that is targeted for a website visitor is resolved and the chatbot is shown to them. 

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_TRIGGERED, (event) => { 
 // code here will execute when the chatbot is loaded for a visitor 
    }); 
});  
```

### Conversation Engaged {#conversation-engaged}

Visitor engaged (e.g., provided their first response) with the chatbot.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_ENGAGED, (event) => { 
 // code here will execute when a visitor engages with the chatbot 
     }); 
}); 
```

### Conversation Completed {#conversation-completed}

The visitor has reached the end of the conversation.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_COMPLETED, (event) => { 
 // code here will execute when a conversation is completed 
     }); 
}); 
```

### Conversation Closed

The visitor has closed the conversation before reaching the end.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_CLOSED, (event) => { 
 // code here will execute when a conversation is closed 
    }); 
}); 
```

The `event` parameter is an object with metadata related to the conversation. You can access this metadata by accessing `event.data`.

Here are some key metadata values you can access: 

<table>
<thead>
  <tr>
    <th style="width:75%">Metadata</th>
    <th style="width:25%">Attributes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Conversation name</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>Conversation ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>Conversation Type (dialogue/conversation flow)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>UI Type (popup/chatbot/inline)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>Session ID</td>
    <td>payload.sid</td>
  </tr>
</tbody>
</table>

## Visitor Input Events

These events are triggered when a visitor engaging in a conversation provides their contact information (e.g., phone number or email address). Below are the events that fall under this category.

### Phone Number {#phone-number} 

This event is triggered when a visitor provides their phone number during the conversation.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_INPUT_PHONE, (event) => { 
 // code here will execute when a visitor provides their phone number 
    }); 
});  
```

### Email ID {#email-id}

This event is triggered when a visitor provides their email address during the conversation.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_INPUT_EMAIL, (event) => { 
 // code here will execute when a visitor provides their email address 
    }); 
}); 
```

The `event` parameter is an object with metadata related to the conversation. You can access this metadata by accessing `event.data`.

Here are some key metadata values you can access:

<table>
<thead>
  <tr>
    <th style="width:75%">Metadata</th>
    <th style="width:25%">Attributes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Conversation name</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>Conversation ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>Conversation Type (dialogue/conversation flow)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>UI Type (popup/chatbot/inline)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>Session ID</td>
    <td>payload.sid</td>
  </tr>
</tbody>
</table>

## Meeting Booking Events {#meeting-booking-events}

These events are triggered when a visitor books a meeting with your business representative.

Below are the events that fall under this category.

### Meeting Booked {#meeting-booked}

This event is triggered when a visitor books a meeting on an agent's calendar.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_MEETING_BOOKED, (event) => { 
 // code here will execute when a meeting is booked 
    }); 
}); 
```

The `event` parameter is an object with metadata related to the conversation. You can access this metadata by accessing `event.data`.

Here are some key metadata values you can access:

<table>
<thead>
  <tr>
    <th style="width:75%">Metadata</th>
    <th style="width:25%">Attributes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Conversation name</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>Conversation ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>Conversation Type (dialogue/conversation flow)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>UI Type (popup/chatbot/inline)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>Session ID</td>
    <td>payload.sid</td>
  </tr>
  <tr>
    <td>Agent Name</td>
    <td>payload.agentName</td>
  </tr>
  <tr>
    <td>Agent ID</td>
    <td>payload.agentID</td>
  </tr>
  <tr>
    <td>Meeting Information</td>
    <td>payload.meetingInfo</td>
  </tr>
</tbody>
</table>

## Live Chat Events {#live-chat-events}

These events are triggered when a visitor connects with a live agent during their engagement with the chatbot.

Below are the events that fall under this category.

### Live Chat Requested {#live-chat-requested} 

This event is triggered when a visitor selects the option to chat with a live agent and an available agent is being resolved.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_REQUESTED, (event) => { 
 // code here will execute when a visitor requests a live chat 
    }); 
}); 
```

### Live Chat Initiated {#live-chat-initiated}

This event is triggered when a visitor selects the option to chat with a live agent and an agent accepts the chat.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_INITIATED, (event) => { 
 // code here will execute after a live agent accepts the chat 
    }); 
}); 
```

### Live Chat Ended {#live-chat-ended}

This event is triggered when a conversation between a visitor and the live agent ends.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_ENDED, (event) => { 
 // code here will execute when a live chat is ended 
    }); 
}); 
```

### Live Chat Timeout {#live-chat-timeout}

This event is triggered when a live chat conversation times out because the visitor stops responding, or they dropped. 

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_REQUEST_TIMEOUT, (event) => { 
 // code here will execute when a visitor abandons a live chat 
    }); 
}); 
```

The `event` parameter is an object with metadata related to the conversation. You can access this metadata by accessing `event.data`.

Here are some key metadata values you can access: 

<table>
<thead>
  <tr>
    <th style="width:75%">Metadata</th>
    <th style="width:25%">Attributes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Conversation name</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>Conversation ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>Conversation Type (dialogue/conversation flow)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>UI Type (popup/chatbot/inline)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>Session ID</td>
    <td>payload.sid</td>
  </tr>
  <tr>
    <td>Agent Name</td>
    <td>payload.agentName</td>
  </tr>
  <tr>
    <td>Agent ID</td>
    <td>payload.agentID</td>
  </tr>
</tbody>
</table>

If you wanted to send any of these events to an analytics platform like Adobe Analytics or Google Analytics, you would need to add their respective tracking call inside these Dynamic Chat events. It would look something like the example below.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    const {addListener, Enum} = window.AdobeDX; 
    addListener(Enum.Events.CONVERSATION_TRIGGERED, (event) => { 
 // Enter Adobe Analytics or Google Analytics function here 
    ga('send', 'event', { 
      eventCategory: Dynamic Chat Conversations', 
      eventAction: 'Conversation Triggered', 
      eventLabel: event.data.payload.id, 
    }); 
    }); 
}); 
```
