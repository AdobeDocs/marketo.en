---
description: Notification - Websocket Connection - Marketo Docs - Product Documentation
title: Notification - Websocket Connection
hide: yes
hidefromtoc: yes
exl-id: 00c754f8-3850-4209-803d-5cdb108dc6dc
---
# Notification: Websocket Connection {#notification-websocket-connection}

This document is for Marketo Engage users who received the following notification in their Marketo instance: `"We were unable to establish a websocket connection to <some-server.adobe.net>. We are ending support of the servers you are currently connected to. Please work with your IT Team to allowlist required Marketo Engage and Adobe domains and ports to prevent access disruptions."`

If you or your organization use restrictive firewall or proxy server settings, you or your network administrator may need to allowlist certain domains and IP address ranges to ensure Adobe Marketo Engage works as expected.

Marketo Support is not set up to assist with implementing the protocols below. If you need assistance, please share this document with your IT team. If they restrict web access using an allowlist, ask them to add the following domains (including the asterisk) to allow all Marketo resources and websockets:

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`
* `*.experience.adobe.com`
* `*.adobe.net`
