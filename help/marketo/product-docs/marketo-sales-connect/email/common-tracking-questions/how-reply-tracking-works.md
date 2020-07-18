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

##### What do we mean any email address can reply? {#what-do-we-mean-any-email-address-can-reply}

This means that if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#581237360b36372f1810372d2b3d0b2c392a33763b3735) and he responds with [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#682207063b06071f283c000d26010f001c1b3f091c0b00460b0705), we're able to track the reply. Additionally, if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#f7bd9899a4999880b7bf98828492a48396859cd994989a) and CC [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#5e3f323f301e3b303d3133703d3133), and Alan writes you back, it will also detect the reply and end the campaign.
