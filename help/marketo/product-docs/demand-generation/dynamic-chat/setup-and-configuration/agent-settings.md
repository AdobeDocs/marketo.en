---
description: Agent Settings - Marketo Docs - Product Documentation
title: Agent Settings
feature: Dynamic Chat
exl-id: a782ef9b-6a89-448a-8bd9-f127ceea3bf5
---
# Agent Settings {#agent-settings}

Configure your calendar and set meeting/live chat availability.

>[!PREREQUISITES]
>
>Make sure your agents have been granted the appropriate [permissions](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions.md){target="_blank"}.

   ![](assets/agent-settings-1.png)

## Connect Calendar {#connect-calendar}

In the Calendar configuration tab, connect your Outlook or Gmail calendar for use in appointment scheduling in the chatbot.

   ![](assets/agent-settings-2.png)

Once a user's calendar is connected to Dynamic Chat, they'll be added to the queue and their calendar will be available for website visitors to schedule appointments on.

>[!NOTE]
>
>You can connect one calendar per user. If you want to receive meetings on multiple calendars, you must add multiple users and have them each connect their calendars.

Users can also customize the body of the invite that's sent to the visitor when they schedule an appointment on the user's calendar. They can also select the checkbox at the bottom to include a Google Meet or Microsoft Teams link (depending on which calendar was connected).

   ![](assets/agent-settings-3.png)

>[!TIP]
>
>Use the token icon (curly brackets) to personalize your meeting booking confirmation emails using person or company attributes.

### Permissions {#permissions}

Configuring with Outlook grants the following permissions to Dynamic Chat:

* Full access to your calendars
* Sign you in and read your profile
* Maintain access to data you've given it access to
* Read your mailbox settings

Configuring with Google grants the following permissions to Dynamic Chat:

* Create, change, or delete calendars
* Update individual calendar events
* Change your settings, including who can see your events
* Change who the calendar is shared with
* Access to your name, email address, language preference, and profile picture

## Meeting Booking Availability {#meeting-booking-availability}

Set your time zone and time/day of week availabilty to receive meeting bookings.

   ![](assets/agent-settings-4.png)

<table> 
 <tbody> 
  <tr> 
   <td><b>Meeting duration</b></td>
   <td>Determines the length of time visitors will see in your available meeting slots.</td>
  </tr> 
  <tr> 
   <td><b>Buffer time between meetings</b></td>
   <td>Amount of time you set as a buffer for after the meeting. If you set it for 30 minutes, no one will be able to book a meeting with you until 30 minutes after the scheduled end of a meeting on your calendar.</td>
  </tr>
 </tbody> 
</table>

>[!TIP]
>
>You can select multiple blocks of time on the same day (e.g., Friday from 8a-12p _and_ 1p-5p) by clicking the **+** sign on the right.

## Live Chat Availability {#live-chat-availability}

Set your time zone and time/day of week availabilty to receive live chats.

   ![](assets/agent-settings-5.png)

If you're logged in to the app, you'll receive an in-app notification of an incoming chat. If you're not logged in, you'll receive a browser notification (if you've [set that up](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md#live-chat-notifications){target="_blank"}).

>[!IMPORTANT]
>
>* The [availability toggle](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md#availability-toggle){target="_blank"} in the Agent Inbox **will override** what is entered in the _Live chat availability_ tab. So if the agent is scheduled as available from 1p-5p but needs to take a quick break at 3p, they don't need to alter their agent settings. Availability toggle status will remain until it's manually changeed, until the next block of time in the agent's availability is reached, or until midnight of the agent's specified time zone (see the next bullet for more info).
>
>* When the agent uses the availability toggle to change their status to "available," their status automatically resets (switches to not available) at midnight of the time zone specified in their availabilty schedule. If no time zone is specified, it defaults to UTC (Coordinated Universal Time).

>[!TIP]
>
>You can select multiple blocks of time on the same day (e.g., Friday from 8a-12p _and_ 1p-5p) by clicking the **+** sign on the right.

## Agent Profile Photo

While an agent has the ability to upload their own profile photo, that action is not performed in Dynamic Chat. They would need to navigate to `account.adobe.com/profile`. Learn more here: [Update your account profile](https://helpx.adobe.com/manage-account/using/edit-adobe-account-personal-profile.html).

>[!NOTE]
>
>The profile image shown in `experience.adobe.com` is **not** supported.
