---
unique-page-id: 14352482
description: How Reply Tracking Works - Marketo Docs - Product Documentation
title: How Reply Tracking Works
---

# How Reply Tracking Works {#how-reply-tracking-works}

Reply Tracking is done by looking at a message ID that's in every email you send. Every email contains a unique message ID that allows us to have some of the best reply tracking around.

>[!PREREQUISITES]
>
>**Connection with Email Server:** Sales Connect must be connected with your inbox so we know when a new reply has arrived. You'll need to have your Sales Connect account [connected to Gmail](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md). If you're using Outlook, we'll need to integrate with your [exchange server](https://toutapp.com/next#settings/exchange_settings).

If Sales Connect can't track your prospect's reply to your email, it won't be able to stop a campaign based on reply detection or log that reply to Salesforce.  What do we mean any email address can reply?

This means that if you email flynn@flynnsarcade.com and he responds with kevinf@flynnsarcade.com, we're able to track the reply. Additionally, if you email flynn@flynnsarcade.com and CC alan@encom.com, and Alan writes you back, it will also detect the reply and end the campaign.
