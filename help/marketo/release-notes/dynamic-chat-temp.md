---
description: Dynamic Chat Release Notes - Marketo Docs - Product Documentation
title: Dynamic Chat Release Notes
feature: Release Information, Dynamic Chat
hide: yes
hidefromtoc: yes
exl-id: 0a7e5cc9-f2a6-4721-bbdc-661249a2e2b6
---
# Dynamic Chat Release Notes {#dynamic-chat-release}

Adobe Dynamic Chat releases operate on a continuous delivery model which allows for a more scalable approach to feature deployment. Sometimes there are multiple releases in a month, so please check back regularly for the most up-to-date information.

The standard Release Notes page for Marketo Engage [can be found here](/help/marketo/release-notes/current.md){target="_blank"}.

## June 2025 Release {#june-2025-release}

### Routing Logic Revamp {#routing-logic-revamp}

We've revamped the live chat routing logic in Dynamic Chat to ensure more intelligent and predictable engagement behavior across all routing types (Account, Custom, Team, and Round Robin). The new logic simplifies routing flows and improves fallback handling when agents are unavailable.

#### Key Improvements in Routing Behavior

* **Up to two engagement attempts per session**

  * The system will try to connect with up to two agents (at most), but strictly within the primary routing rule.

  * If an agent is available but doesn't respond (e.g., declines or misses the chat), the system will attempt to connect to a different agent from the same pool.

  * Fallback logic (like Round Robin) is only activated if no eligible agents are found during the initial resolution, not to retry after a failed engagement.

* **Routing Rule-Specific Behavior**

_**Account Routing**_

If a visitor's email domain maps to a known account, the mapped agent is always prioritized.

If the agent is available, the chat is routed to them directly.

If the agent is unavailable, the system:

  * Does not attempt another agent, even if Round Robin is enabled as fallback.

  * Instead, it:

    * Shows the mapped agent's meeting calendar (if enabled),
    -or-
    * Falls back to a default message (worst case).

The card-level routing rule (e.g. Team, Custom) is only considered if Account Routing is not eligible (no matching domain or agent).

_**Custom/Team Routing**_

These rules may return multiple eligible agents.

If the first available agent doesn't engage, the system will try one more agent from the same list.

Round Robin fallback is not triggered just because one agent doesn't respond.

If neither agent engages:

  * The system shows the first tried agent's calendar (if enabled),
  -or-
  * Displays the default fallback message.

_**Round Robin Routing**_

When used as a primary routing rule, the system:

  * Attempts to engage the first available agent from the round robin pool.

  * If the first agent doesn't respond, it retries with the next best eligible agent.

If Round Robin is used as a fallback, it activates only if no agents are resolved from the primary rule.

_**Visitor Experience Flow**_

The system checks if Account Routing is applicable.

  * If yes and agent is available, it connects immediately.

  * If the agent is not eligible or unavailable, it proceeds to card-level routing rule.

Card-level routing rule (Custom, Team, Round Robin) is evaluated.

  * Eligible agents are checked for availability (permissions, status).

  * System engages one agent, and if needed, tries a second agent from same rule.

  * If no engagement succeeds, fallback logic is applied:

    * Calendar fallback (if enabled),
    -or-
    * Default message.

Round Robin fallback is only considered when no eligible agents are found from the primary routing rule, not when individual agents fail to respond.

##### Use Cases {#use-cases}

_**Account Routing**_

<table><thead>
  <tr>
    <th>Type</th>
    <th>Example</th>
    <th>Outcome</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideal</td>
    <td>Visitor's domain maps to an account; mapped agent has live chat enabled and is available</td>
    <td>Chat connects directly to the mapped agent</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>Mapped agent is unavailable, Round Robin fallback is enabled</td>
    <td>System selects one available agent via Round Robin and engages them </td>
  </tr>
  <tr>
    <td>No Fallback Agent</td>
    <td>Mapped agent is unavailable, no Round Robin fallback; meeting booking is enabled</td>
    <td>System shows mapped agent's calendar or displays a default fallback message</td>
  </tr>
</tbody></table>

_**Custom Routing**_

<table><thead>
  <tr>
    <th>Type</th>
    <th>Example</th>
    <th>Outcome</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideal</td>
    <td>Custom logic resolves a list of agents; first agent is available and accepts chat.</td>
    <td>Chat connects to the first agent.</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>Custom rule resolves no agents, Round Robin fallback is enabled.</td>
    <td>System selects one available agent via Round Robin and engages them.</td>
  </tr>
  <tr>
    <td>No Fallback Agent</td>
    <td>Two agents resolved; neither accepts chat, fallback set to meeting calendar.</td>
    <td>First tried agent's calendar is shown or default fallback message is displayed.</td>
  </tr>
</tbody></table>

_**Team Routing**_

<table><thead>
  <tr>
    <th>Type</th>
    <th>Example</th>
    <th>Outcome</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideal</td>
    <td>Team includes agents with live chat; first available agent accepts the chat.</td>
    <td>Chat connects to that agent.</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>No team agent is available, and Round Robin fallback is enabled.</td>
    <td>System selects and connects with one agent from Round Robin pool.</td>
  </tr>
  <tr>
    <td>No Fallback Agent</td>
    <td>Two agents available, but neither engages; calendar fallback enabled.</td>
    <td>First tried agent's calendar is shown or fallback message is triggered.</td>
  </tr>
</tbody></table>

_**Round Robin Routing**_

<table><thead>
  <tr>
    <th>Type</th>
    <th>Example</th>
    <th>Outcome</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideal</td>
    <td>Round Robin pool has multiple agents; second agent accepts chat after first doesn't.</td>
    <td>Chat connects to second agent.</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>No agents available in Round Robin pool; meeting calendar is enabled.</td>
    <td>Calendar is shown for first agent in the list (if configured), or fallback message shown.</td>
  </tr>
  <tr>
    <td>No Fallback Agent</td>
    <td>No available agents; fallback is disabled.</td>
    <td>Static fallback message is shown to the visitor.</td>
  </tr>
</tbody></table>

### Pulse Notification {#pulse-notification}

Whenever a visitor requests to connect with an agent, we provide in-app, browser notification to the agent. But sometimes, agents miss these chats.

With this release, the live agent can get an email, Slack, in-app, and browser notification when a new visitor is interested in chatting.

1. On your Adobe Experience Cloud homepage, click the Account icon and select **Preferences**.

   ![](assets/dynamic-chat-june-2025-release-1.png)

1. Scroll down to _Notifications_ and make your desired Dynamic Chat selections.

   ![](assets/dynamic-chat-june-2025-release-2.png)

>[!NOTE]
>
>Content for a Pulse notification can be the same as what we use for in-app, browser notifications.
