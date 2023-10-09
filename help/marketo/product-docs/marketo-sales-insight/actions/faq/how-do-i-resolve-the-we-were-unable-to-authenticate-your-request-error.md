---
description: How Do I Resolve the We Were Unable to Authenticate Your Request Error? - Marketo Docs - Product Documentation
title: How Do I Resolve the We Were Unable to Authenticate Your Request Error?
hide: yes
hidefromtoc: yes
feature: Sales Insight Actions
---
# How Do I Resolve the "We Were Unable to Authenticate Your Request" Error? {#how-do-i-resolve-the-we-were-unable-to-authenticate-your-request-error}

If you're trying to connect your Marketo Sales instance to Salesforce and you're seeing the "We are unable to authenticate your request" error, it's likely related to how your Salesforce instance is configured.

There are two types of errors that could be producing this failed authentication page.

* Login error restricted Domain
* Oauth App Blocked

You can identify which type you're getting by checking the URL.

PICC

PICC

## Resolve Login Error Restricted Domain {#resolve-login-error-restricted-domain}

This error typically indicates you have a custom domain that we're not able to route to. To resolve this error, try signing in to the Salesforce instance you want to connect to first. Then, go through the steps to connect to Salesforce.

If the instance you're trying to connect to is a Salesforce Sandbox domain and you're getting an error, you'll need to go through additional steps to update your instance to be Salesforce Sandbox compatible. [Learn more](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/set-up-a-sales-insight-actions-sandbox.md){target="_blank"}. 

## Resolve Oauth App Blocked {#resolve-oauth-app-blocked}

This error is typically caused by Salesforce blocking your instance from connecting. A Salesforce admin can resolve this in the Connected Apps Oauth usage section of their account settings.

1. Log in to your Salesforce account. 

1. Navigate to **Setup**. 

1. Search for "Connected Apps Oauth Usage" in the quick find box. 

1. Find the connected app called ToutApp and click **Unblock**.
