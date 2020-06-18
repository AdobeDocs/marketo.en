---
unique-page-id: 14352482
description: How Reply Tracking Works - Marketo Docs - Product Documentation
title: How Reply Tracking Works
---

# How Reply Tracking Works {#how-reply-tracking-works}

How Reply Tracking Works - Marketo Docs - Product Documentation

Reply Tracking is done by looking at a message ID that's in every email you send. Every email contains a unique message ID that allows us to have some of the best reply tracking around.

>[!NOTE]
>
>**Prerequisites**
>
>**Connection with Email Server:** Sales Connect must be connected with your inbox so we know when a new reply has arrived. You'll need to have your Sales Connect account [connected to Gmail](http://docs.marketo.com/x/kYMOAQ). If you're using Outlook, we'll need to integrate with your [exchange server](http://toutapp.com/next#settings/exchange_settings).

If Sales Connect can't track your prospect's reply to your email, it won't be able to stop a campaign based on reply detection or log that reply to Salesforce.  

##### What do we mean any email address can reply? {#howreplytrackingworks-whatdowemeananyemailaddresscanreply}

This means that if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#db91b4b588b5b4ac9b93b4aea8be88afbaa9b0f5b8b4b6) and he responds with [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#6a2005043904051d2a3e020f24030d021e193d0b1e090244090507), we're able to track the reply. Additionally, if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#f9b39697aa97968eb9b1968c8a9caa8d988b92d79a9694) and CC [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#2e4f424f406e4b404d4143004d4143), and Alan writes you back, it will also detect the reply and end the campaign.
