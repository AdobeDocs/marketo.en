---
description: Notification details for Marketo Engage users who received the Unable to Establish a Websocket Connection notification
title: Notification - Websocket Connection
hide: true
exl-id: 00c754f8-3850-4209-803d-5cdb108dc6dc
TQID: https://experienceleague.adobe.com/NpcRnxQPi03CF8z77Urrfs2P2phkuRbh2pd5J1UquFk
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
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
