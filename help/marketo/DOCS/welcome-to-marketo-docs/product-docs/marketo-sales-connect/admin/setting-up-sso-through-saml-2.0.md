---
unique-page-id: 14352405
description: Setting UP SSO Through SAML 2.0 - Marketo Docs - Product Documentation
title: Setting UP SSO Through SAML 2.0
---

# Setting UP SSO Through SAML 2.0 {#setting-up-sso-through-saml}

Setting UP SSO Through SAML 2.0 - Marketo Docs - Product Documentation

We support SSO through the SAML 2.0 specification. However, we don't have direct integrations with any provider at this time. We will need to collect some information from your SSO provider in order to get this setup.

**Requirements**

* SSO account
* Metadata.xml from SSO account (issue URL, the endpoint for validation, and a public key)&nbsp;

**Setup**

The metadata.xml&nbsp;from your team's SSO instance should contain the&nbsp;issuer URL, the endpoint for validation, and a public key.

We will also need the SSO Location for your company's SSO account to be a unique domain. For example, we `require a unique subdomain` like ‘toutapp.pingidentity.com' or similar. Without this type of unique identifier, we will not be able to set up SAML from the dashboard.

One Login and Okta do not always provide unique&nbsp;identifiers when assigning a URL. If you are using Okta or One Login it means we will not be able to set up one login from the dashboard button. We will still be able to set it up from the Single Sign On button on the [web application](http://toutapp.com/login).

Once we have that information, we will work with our engineering team to set this up for your subscription.&nbsp;
