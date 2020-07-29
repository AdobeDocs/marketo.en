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

If Sales Connect can't track your prospect's reply to your email, it won't be able to stop a campaign based on reply detection or log that reply to Salesforce.  

##### What do we mean any email address can reply? {#what-do-we-mean-any-email-address-can-reply}

This means that if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#014b6e6f526f6e7641496e747264527560736a2f626e6c) and he responds with [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#9ed4f1f0cdf0f1e9decaf6fbd0f7f9f6eaedc9ffeafdf6b0fdf1f3), we're able to track the reply. Additionally, if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#541e3b3a073a3b23141c3b212731072035263f7a373b39) and CC [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#c7a6aba6a987a2a9a4a8aae9a4a8aa), and Alan writes you back, it will also detect the reply and end the campaign.
