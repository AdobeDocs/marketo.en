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

This means that if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#cb81a4a598a5a4bc8b83a4beb8ae98bfaab9a0e5a8a4a6) and he responds with [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#ade7c2c3fec3c2daedf9c5c8e3c4cac5d9defaccd9cec583cec2c0), we're able to track the reply. Additionally, if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#7a3015142914150d3a32150f091f290e1b081154191517) and CC [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#b1d0ddd0dff1d4dfd2dedc9fd2dedc), and Alan writes you back, it will also detect the reply and end the campaign.
