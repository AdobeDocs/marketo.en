---
unique-page-id: 14352405
description: Understand how to set up SSO through SAML 2.0 in Sales Connect. Get requirements and setup steps for your SSO provider and unique domain.
title: Setting UP SSO Through SAML 2.0 in [!DNL Sales Connect]
exl-id: aab80626-d6d1-4194-9733-09c90c0b49a6
feature: Marketo Sales Connect
TQID: https://experienceleague.adobe.com/FLGacQUvOJFtKJ5O1PzWRmpk3Zm1KH1D-W3ATHSVRSA
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
    internal-label: Metadata
---
# Setting UP SSO Through SAML 2.0 in [!DNL Sales Connect] {#setting-up-sso-through-saml-in-sales-connect}

We support SSO through the SAML 2.0 specification. However, we don't have direct integrations with any provider at this time. We will need to collect some information from your SSO provider in order to get this setup.

>[!NOTE]
>
>This is only applicable to **Marketo Sales Connect** users. If you don't have Sales Connect but want to learn more, please contact the Adobe Account Team (your Account Manager).

## Requirements {#requirements}

* SSO account
* Marketo Sales Connect subscription
* Metadata.xml from SSO account (issue URL, the endpoint for validation, and a public key)

## Setup {#setup}

The metadata.xml from your team's SSO instance should contain the issuer URL, the endpoint for validation, and a public key.

We will also need the SSO Location for your company's SSO account to be a unique domain. For example, we require a unique subdomain like `toutapp.pingidentity.com` or similar. Without this type of unique identifier, we will not be able to set up SAML from the dashboard.

One Login and Okta do not always provide unique identifiers when assigning a URL. If you are using Okta or One Login it means we will not be able to set up one login from the dashboard button. We will still be able to set it up from the Single Sign On button on the [web application](https://toutapp.com/login).

Once we have that information, we will work with our engineering team to set this up for your subscription.
