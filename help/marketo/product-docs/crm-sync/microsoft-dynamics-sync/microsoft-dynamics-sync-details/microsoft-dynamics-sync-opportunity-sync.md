---
unique-page-id: 3571844
description: Microsoft Dynamics Sync -Opportunity Sync - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync -Opportunity Sync
exl-id: dcb72f28-c980-4183-8473-a1e5ad0c8d3c
feature: Microsoft Dynamics
---
# Microsoft Dynamics Sync: Opportunity Sync {#microsoft-dynamics-sync-opportunity-sync}

Marketo Engage to Dynamics sync is super powerful. Here are all the details for opportunity sync.

## How are opportunity details kept in sync between the two systems? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

The opportunity sync is one way - Dynamics to Marketo. If you make changes to an opportunity in Dynamics, your update will be reflected in Marketo.

## Can I create an opportunity in Dynamics using Marketo? {#can-i-create-an-opportunity-in-dynamics-using-marketo}

No, you must create the opportunity in Dynamics and it will automatically sync to Marketo.

## What fields will sync to Marketo? {#what-fields-will-sync-to-marketo}

You can [select fields to sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} during setup.

## How is an Account/Contact associated with an Opportunity? {#how-is-an-account-contact-associated-with-an-opportunity}

The Contact/Account can be associated to Opportunity in two ways:

* While creating an opportunity, the Contact (lookup field on the form to contact) and/or Account (lookup field on the form to account) can be set. In either case, these values are stored in the Potential Customer (customerid) field in Dynamics. This field does not show up on the opportunity form, but can be added from settings. This field can contain only 1 value, either contact or account. Marketo does the following:

  * If the contact value is set and account is left empty, Marketo creates an `opportunitycontactrole` and sets the account on the opportunity to the contact's account. If the contact doesn't have an account, this field is left empty.
  * If the account value is set and contact is left empty, Marketo will only set the account on the opportunity to this account.
  * If both values are set, Dynamics picks account as the value for customerid, so the behavior would be the same as above.
 

* Through Stakeholders: Dynamics uses connections to connect opportunity to contact through stakeholders from the opportunity create page. For this, we will create an `opportunitycontactrole` record for every new stakeholder.
