---
unique-page-id: 4719316
description: Using Person Accounts - Marketo Docs - Product Documentation
title: Using Person Accounts
---

# Using Person Accounts {#using-person-accounts}

Person accounts can be set up in Salesforce to fit the need of your organization. Here's how Marketo treats person accounts.

>[!NOTE]
>
>The default Salesforce accounts are business accounts. Your Salesforce Admin needs to set up person accounts separately.

## What is a person account? {#what-is-a-person-account}

A person account is very similar to the account object in Salesforce. However, a person account has access to both account fields and contact fields.

## What happens when a person account is synced to Marketo? {#what-happens-when-a-person-account-is-synced-to-marketo}

A person account is synced to Marketo as a company and as a person.

>[!NOTE]
>
>The custom fields for a person account are copied to both company and person in Marketo.

## How do I differentiate business accounts and person accounts? {#how-do-i-differentiate-business-accounts-and-person-accounts}

Use the **Is Person Account** filter in your smart list to separate person accounts from standard business accounts.

## Where is my person accounts information displayed in Marketo Sales Insight? {#where-is-my-person-accounts-information-displayed-in-marketo-sales-insight}

Activities related to person accounts are displayed in the **Account** panel.

>[!NOTE]
>
>Marketo Sales Insight's **Add to Marketo Campaign **and **Send Email **options are not currently available for person accounts.

## How do I associate opportunities to a person account? {#how-do-i-associate-opportunities-to-a-person-account}

Marketo depends on the opportunity contact role to determine which person to associate the opportunity to. You need to add the opportunity contact role for each person account to connect the opportunity to the appropriate person in Marketo. We recommend that you set up a workflow to add the opportunity contact role automatically.

## Which email field should I use for person accounts? {#which-email-field-should-i-use-for-person-accounts}

There are two email fields for a person account. Use the **Email Address** field in your forms (not the **Person Email Address**) to ensure Marketo's de-duplication and other email processing work properly.
