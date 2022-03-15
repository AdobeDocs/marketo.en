---
description: How Do I Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce - Marketo Docs - Product Documentation
title: How Do I Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce
hide: yes
hidefromtoc: yes
exl-id: ef876f0f-bd76-4ba5-bf48-885ee048ceae
---
# How Do I Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce {#how-do-i-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

If you receive the error message "We were unable to authenticate your request" when trying to connect Sales Insight Actions to Salesforce, there might be a restriction on your access to Salesforce's API. Check with your Salesforce Admin to make sure the following things are in place.

## Enable API in User Permissions {#enable-api-in-user-permissions}

1. Have a Salesforce Admin log into SFDC.
1. Select **Setup**.
1. Select **Manage Users**.
1. Select **Profiles**.
1. Find the Profile that the ToutApp users are under and click **Edit**.
1. Scroll down to **Administrative Permissions** and make sure **API Enabled** is checked.

## Check if Salesforce is Blocking Sales Insight Actions from Connecting {#check-if-salesforce-is-blocking-sales-insight-actions-from-connecting}

1. Have a Salesforce Admin log in to SFDC.
1. Select **Setup**.
1. Select **Manage Apps**.
1. Select **Connected Apps OAuth Usage**.
1. Make sure that Sales Insight Actions shows "Block" next to it. If you see "Unblock", click the button to unblock Sales Insight Actions' access to Salesforce.
