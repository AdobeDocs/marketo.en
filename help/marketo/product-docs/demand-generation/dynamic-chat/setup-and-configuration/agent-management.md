---
description: Agent Management - Marketo Docs - Product Documentation
title: Agent Management
feature: Dynamic Chat
exl-id: 151d8cf2-a5b7-43c4-8418-cc22252108b2
---
# Agent Management {#agent-management}

In Agent Management, view a list of agents in your Dynamic Chat instance, manage teams, and set your fallback rules.

   ![](assets/agent-management-1.png)

## Agents {#agents}

This tab lists all of the agents in your Dynamic Chat instance, and includes such information as their name, email address, live chat status, and more.

   ![](assets/agent-management-2.png){width="800" zoomable="yes"}

   >[!NOTE]
   >
   >Don't see an agent you _just_ added? It could take up to two hours for them to appear here after adding them in the Adobe Admin console.

## Teams {#teams}

Admins can create teams of agents to facilitate ease of routing to specific groups of sales agents.

>[!AVAILABILITY]
>
>Access to Teams requires a Dynamic Chat Prime subscription. Please contact the Adobe Account Team (your Account Manager) for details.

   ![](assets/agent-management-3.png)

### Create a Team {#create-a-team}

1. Click **+ Create Team**.

   ![](assets/agent-management-4.png)

1. Give your team a name.

   ![](assets/agent-management-5.png)

1. Click the **Add Agents** drop-down and select the desired agents.

   ![](assets/agent-management-6.png)

1. Click **Create**.

   ![](assets/agent-management-7.png)

## Fallback Rules {#fallback-rules}

### Meeting Fallback {#meeting-fallback}

Select a standard (system) message or write a custom one for visitors to see when meeting booking is unavailable.

   ![](assets/agent-management-8.png)

### Live Chat Fallback {#live-chat-fallback}

Select a standard (system) message or write a custom one for visitors to see when Live Chat is unavailable.

   ![](assets/agent-management-9.png)

>[!NOTE]
>
>* Selecting the _Include Meeting Booking Option_ checkbox will give the chat visitor the option to book a meeting when no agents are available to live chat.
>
>* **For any custom rules/Teams as a Live Chat card**: While checking for agents, if they are not available or could not connect, it will fall back to Round Robin to try for "Available Agents" (all who are available at that time regardless of which routing logic/rule was placed in the stream).

>[!TIP]
>
>When creating a custom message, you can style the font, use links, even insert emojis! `:)`
