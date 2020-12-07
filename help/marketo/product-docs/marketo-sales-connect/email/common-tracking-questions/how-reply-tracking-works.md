---
unique-page-id: 14352482
description: How Reply Tracking Works - Marketo Docs - Product Documentation
title: How Reply Tracking Works
---

# How Reply Tracking Works {#how-reply-tracking-works}

Reply Tracking is done by looking at a message ID that's in every email you send. Every email contains a unique message ID that allows us to have some of the best reply tracking around.

>[!NOTE]
>
>**Prerequisites**
>
>**Connection with Email Server:** Sales Connect must be connected with your inbox so we know when a new reply has arrived. You'll need to have your Sales Connect account [connected to Gmail](http://docs.marketo.com/x/kYMOAQ). If you're using Outlook, we'll need to integrate with your [exchange server](http://toutapp.com/next#settings/exchange_settings).

If Sales Connect can't track your prospect's reply to your email, it won't be able to stop a campaign based on reply detection or log that reply to Salesforce.  What do we mean any email address can reply?

This means that if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#783217162b16170f3830170d0b1d2b0c190a13561b1715) and he responds with [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#c08aafae93aeafb78094a8a58ea9a7a8b4b397a1b4a3a8eea3afad), we're able to track the reply. Additionally, if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#450f2a2b162b2a32050d2a303620163124372e6b262a28) and CC [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#3e5f525f507e5b505d5153105d5153), and Alan writes you back, it will also detect the reply and end the campaign.
