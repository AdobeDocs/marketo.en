---
description: Setting up OAuth 2.0 - Marketo Docs - Product Documentation
title: Setting up OAuth 2.0
---

# Setting up OAuth 2.0 {#setting-up-oauth-2-0}

Salesforce uses the OAuth protocol to allow users of applications to securely access (authenticate the application using OAuth 2.0) data via REST API calls without having to reveal login credentials. Below are the steps to be performed to securely connect and sync Marketo with Salesforce.

## Set Up Connected App {#set-up-connected-app}

1. In Salesforce, under Setup, within the Platform Tools, navigate to Apps, App Manager, and click **New Connected App**.

   ![](assets/setting-up-oauth-2-1.png)

1. Fill in the details and click **Save**.

   ![](assets/setting-up-oauth-2-2.png)

1. Click the **Enable OAuth Settings** checkbox. For Callback URL, enter `https://app.marketo.com/salesforce/getSfdcOAuthTokensRedirect`. Select all the available OAuth Scopes and click **Add**.

   ![](assets/setting-up-oauth-2-3.png)

1. Click **Save**.

   ![](assets/setting-up-oauth-2-4.png)

1. Click **Continue**.

   ![](assets/setting-up-oauth-2-5.png)

1. Copy the Consumer Key and Consumer Secret.

   ![](assets/setting-up-oauth-2-6.png)

>[!NOTE]
>
>Save the Consumer Key and Consumer Secret info for later use in Marketo.

## Set Up Marketo {#set-up-marketo}

>[!PREREQUISITES]
>
>* API access must be enabled for the Salesforce Sync User (if you're a Salesforce Professional Edition user, that access is not available by default–please contact your Salesforce Account Executive).
>* Marketo Sync user has to be created in Salesforce.
>* For existing customers, Feature to “Enable OAuth for SFDC sync” is enabled on the customer’s subscription.
>* Pop-up blockers are disabled.
>* Connected App is created and we have the Consumer Key and Consumer Secret are available for use.

1. In the Marketo Admin section, click **CRM**, then **Sync with Salesforce**.

   ![](assets/setting-up-oauth-2-7.png)

1. Add the Consumer Key and Consumer Secret info you previously recorded and click and **Save**.

   ![](assets/setting-up-oauth-2-8.png)

1. On the Marketo Salesforce sync page, click the **Login with Salesforce** button.

   ![](assets/setting-up-oauth-2-9.png)

1. A pop-up with the salesforce login page will show up. Key in your “Marketo Sync User” credentials and log in.

   ![](assets/setting-up-oauth-2-10.png)

1. Enter the verification code you received via email (sent by Salesforce) and click **Verify**.

   ![](assets/setting-up-oauth-2-11.png)

1. Upon successful verification, the access page will show up requesting access. Click **Allow**.

   ![](assets/setting-up-oauth-2-12.png)

1. In a few minutes, a pop-up will appear in Marketo. Click **Confirm Credentials**.

   ![](assets/setting-up-oauth-2-13.png)

1. Upon completion of Field Syncing, click **Start Salesforce Sync**.

   ![](assets/setting-up-oauth-2-14.png)

1. Click **Start Sync**.

   ![](assets/setting-up-oauth-2-15.png)

Your Sync between Marketo and Salesforce is now in progress.

   ![](assets/setting-up-oauth-2-16.png)
