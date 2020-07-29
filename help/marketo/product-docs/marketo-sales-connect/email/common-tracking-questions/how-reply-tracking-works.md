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

This means that if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#d49ebbba87babba3949cbba1a7b187a0b5a6bffab7bbb9) and he responds with [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#88c2e7e6dbe6e7ffc8dce0edc6e1efe0fcfbdfe9fcebe0a6ebe7e5), we're able to track the reply. Additionally, if you email [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#96dcf9f8c5f8f9e1d6def9e3e5f3c5e2f7e4fdb8f5f9fb) and CC [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#e889848986a88d868b8785c68b8785), and Alan writes you back, it will also detect the reply and end the campaign.
