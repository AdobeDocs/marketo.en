---
unique-page-id: 14352477
description: Push to Sales Connect - Marketo Docs - Product Documentation
title: Push to Sales Connect
exl-id: 8fb99d28-d6c6-47c3-b4d2-c416251aff47
---
# Push to Sales Connect {#push-to-sales-connect}

Our Push to Tout button will take a list of your leads/contacts in Salesforce and push them into a group in Sales Connect. You can then quickly send a customizable group email with Tout tracking attached.

## Requirements {#requirements}

* Sales Connect Salesforce package installed by Salesforce Admin

* Push to Sales Connect button installed to list view by Salesforce Admin

* Salesforce Connection made with Sales Connect for user making the Push

## How To {#how-to}

1. Click the **Lead/Contact** tab in Salesforce.
1. Toggle to the List View you would like to Push to Sales Connect next to the Go button.
1. Click **Go**.
1. Select all the leads/contacts you want to be pushed to tout.
1. Select **Push to MSE**.
1. A new window will appear verifying the number of leads/contacts you'd like to push over. Select **Proceed to Group**. Sales Connect will not push over any contacts marked as Email Opt Out in Salesforce or Unsubscribed in Sales Connect.

   >[!NOTE]
   >
   >Sales Connect will add this group titled "SFDC-..." to the Relationships page on the [web application](https://toutapp.com/login).

1. Select **Email Entire Group** to send out this group email.
