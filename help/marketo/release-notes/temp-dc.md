---
description: Dynamic Chat Release Notes - Marketo Docs - Product Documentation
title: Dynamic Chat Release Notes
feature: Release Information, Dynamic Chat
hide: yes
hidefromtoc: yes
exl-id: 12130dee-2dbf-4e71-b542-30d4732b1067
---
# TEMP Dynamic Chat Release Notes {#dynamic-chat-release}

## September/October 2024 Release {#august-release}

### Enhanced live chat analytics {#enhanced-live-chat-analytics}

Several enhancements have been made to the Analytics Dashboard, including: 

* Total Requested Live Chat Count: number of visitors requested for a "chat with agent" 

* Total Connected Live Chat: number of visitors connected vs. total requested for a "chat with agent" 

* Total Missed Live Chat Requests: number of visitors unattended vs. total requested for a "chat with agent" 

* Average Chat Length in Minutes: analyze "average chat length" between visitors and your agents 

* Average Agent Response Time in Seconds: analyze "average time taken" by agents to respond their live chat Q&A 

* Daily Dashboard: live chat requests connected successfully, live chat requests missed, sort and filter recent live chat activities

SCREENSHOT

### Conversation scoring {#conversation-scoring}

Quantify your leads based on the quality of their chat interaction and use that metric as a Trigger/Filter in Marketo Engage Smart Campaigns. Use the new attribute _conversation score_ on the following activities: 

* Engaged with a dialogue  
* Engaged with a conversation flow 
* Engaged with an agent

**Things to note:**

* The score value will be from 0, 1, 2, 3 (default value is null)

* Once the conversation is completed or dropped, in the activity save the scoring value and post that it cannot be edited????? (what does this sentence mean)

* Setting a score:

  * In the agent inbox - during a live chat, the agent is able to update or set a score for the conversation, which is stored in the conversation activity 

  * In the stream designer - in the goal card, the user is able to update or set a score for the conversation  

SCREENSHOT

SCREENSHOT

SCREENSHOT

### New lead creation logic {#new-lead-creation-logic}
 
If a lead fills out a form with the email `abc@test.com` and is cookied as xyz, then later fills out the same form with the email `def@test.com`, a new lead gets created, but cookie xyz becomes associated with new the lead and removed from lead `abc@test.com`. 

From then on, `abc@test.com` will be a lead with no cookie. ANONYMOUS LEAD??  

So, when a visitor with cookie abc lands on a page and provides an email ID as `abc@p.com`: 

TABLE

### Optimized conversation flow load time {#optimized-conversation-flow-load-time}
 
To improve the user experience, a shimmer loader is now displayed instead of a blank space while the conversation flow loads. CONVERSATION OR CONVERSATIONAL???

**Before**

GIF

**After**

GIF

### Option to inherit font {#option-to-inherit-font}
 
You can now enable the chatbot to directly inherit the font from the web page where it's being hosted rather than managing the brand font in Dynamic Chat. When you enable this option, the chatbot will take the font that is defined on `<body>` tag of the page.

SCREENSHOT

### Demandbase integration with Dynamic Chat {#demandbase-integration-with-dynamic-chat}
 
Demandbase users are able to bring their own license of Demandbase and activate the integration. Use Demandbase person attributes for dialogue targeting, conditional branding, and custom routing.

Resolution of these attribute values against a lead would be done in realtime and are stored in the respective lead profile.
