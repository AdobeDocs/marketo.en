---
unique-page-id: 14352405
description: Setting UP SSO Through SAML 2.0 in Sales Connect - Marketo Docs - Product Documentation
title: Setting UP SSO Through SAML 2.0 in Sales Connect
---

# Setting UP SSO Through SAML 2.0 in Sales Connect {#setting-up-sso-through-saml-in-sales-connect}

We support SSO through the SAML 2.0 specification. However, we don't have direct integrations with any provider at this time. We will need to collect some information from your SSO provider in order to get this setup.

>[!NOTE]
>
>This is only applicable to **Marketo Sales Connect** customers. If you don't have Sales Connect but want to learn more, please contact your Customer Success Manager.

## Requirements {#requirements}

* SSO account
* Marketo Sales connect subscription
* Metadata.xml from SSO account (issue URL, the endpoint for validation, and a public key)

## Setup {#setup}

The metadata.xml from your team's SSO instance should contain the issuer URL, the endpoint for validation, and a public key.

We will also need the SSO Location for your company's SSO account to be a unique domain. For example, we require a unique subdomain like `toutapp.pingidentity.com` or similar. Without this type of unique identifier, we will not be able to set up SAML from the dashboard.

One Login and Okta do not always provide unique identifiers when assigning a URL. If you are using Okta or One Login it means we will not be able to set up one login from the dashboard button. We will still be able to set it up from the Single Sign On button on the [web application](http://toutapp.com/login).

Once we have that information, we will work with our engineering team to set this up for your subscription.
