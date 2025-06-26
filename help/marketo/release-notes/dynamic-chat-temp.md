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

## June 2025 Release {#june-25-release}

### Routing Logic Revamp {#routing-logic-revamp}

We've revamped the live chat routing logic in Dynamic Chat to ensure more intelligent and predictable engagement behavior across all routing types (Account, Custom, Team, and Round Robin). The new logic simplifies routing flows and improves fallback handling when agents are unavailable. 
 
#### Key Improvements in Routing Behavior 

* **Up to two engagement attempts per session**

  * The system will try to connect with at most two agents, but strictly within the primary routing rule. 

  * If an agent is available but doesn't respond (e.g., declines or misses), the system will attempt a second agent from the same pool. 

  * Fallback logic (like Round Robin) is only activated if no eligible agents are found during the initial resolution — not to retry after a failed engagement. 

* **Routing Rule-Specific Behavior**

_**Account Routing**_

If a visitor's email domain maps to a known Account, the mapped agent is always prioritized. 

If the agent is available, the chat is routed to them directly. 

If the agent is unavailable, the system: 

Does not attempt another agent, even if Round Robin is enabled as fallback. 

Instead, it: 

Shows the mapped agent's meeting calendar (if enabled), or 

Falls back to a default message (worst case). 

The card-level routing rule (e.g. Team, Custom) is only considered if Account Routing is not eligible (no matching domain or agent). 

_**Custom/Team Routing**_

These rules may return multiple eligible agents. 

If the first available agent doesn't engage, the system will try one more agent from the same list. 

Round Robin fallback is not triggered just because one agent didn't respond. 

If neither agent engages: 

The system shows the first tried agent's calendar (if enabled), or 

Displays the default fallback message. 

_**Round Robin Routing**_

When used as a primary routing rule, the system: 

Attempts to engage the first available agent from the round robin pool. 

If the first doesn't respond, it retries with the next best eligible agent. 

If Round Robin is used as fallback, it activates only if no agents are resolved from the primary rule. 

**Visitor Experience Flow**

System checks if Account Routing is applicable. 

If yes and agent is available → connects immediately. 

If not eligible or agent unavailable → proceeds to card-level routing rule. 

Card-level routing rule (Custom, Team, Round Robin) is evaluated. 

Eligible agents are checked for availability (permissions, status). 

System engages one agent, and if needed, tries a second agent from same rule. 

If no engagement succeeds → fallback logic is applied: 

Calendar fallback (if enabled), or 

Default message. 

Round Robin fallback is only considered when no eligible agents are found from the primary routing rule — not when individual agents fail to respond.

**Use Cases**

Account Routing

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

Custom Routing

<table><thead>
  <tr>
    <th>Type</th>
    <th>Example</th>
    <th>Outcome</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideal</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>No Fallback Agent</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
</tbody></table>

Team Routing

<table><thead>
  <tr>
    <th>Type</th>
    <th>Example</th>
    <th>Outcome</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideal</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>No Fallback Agent</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
</tbody></table>

Round Robin Routing

<table><thead>
  <tr>
    <th>Type</th>
    <th>Example</th>
    <th>Outcome</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideal</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>No Fallback Agent</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
</tbody></table>

### Pulse Notification {#pulse-notification}

Whenever a visitor requests to connect with an agent, today we provide in-app, browser notification to the agent, but agents are often missing these chats. 

* Now live agent will get email, Slack, Inapp, browser notification when a new visitor is interested in chatting 

* Content for Pulse notification can be the same as what we use today for in-app, browser notification 

Behavior should be same as current for agent to accept when multiple agents accepts.
