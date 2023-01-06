---
unique-page-id: 14352477
description: Push to [!DNL Sales Connect] - Marketo Docs - Product Documentation
title: Push to [!DNL Sales Connect]
exl-id: 8fb99d28-d6c6-47c3-b4d2-c416251aff47
---
# Push to [!DNL Sales Connect] {#push-to-sales-connect}

Our [!UICONTROL Push to Tout] button will take a list of your leads/contacts in [!DNL Salesforce] and push them into a group in [!DNL Sales Connect]. You can then quickly send a customizable group email with Tout tracking attached.

## Requirements {#requirements}

* [!DNL Sales Connect Salesforce] package installed by [!DNL Salesforce] Admin

* [!UICONTROL Push to Sales Connect] button installed to list view by [!DNL Salesforce] Admin

* [!DNL Salesforce] Connection made with [!DNL Sales Connect] for user making the Push

## How To {#how-to}

1. Click the **[!UICONTROL Lead/Contact]** tab in [!DNL Salesforce].
1. Toggle to the List View you would like to Push to [!DNL Sales Connect] next to the [!UICONTROL Go] button.
1. Click **[!UICONTROL Go]**.
1. Select all the leads/contacts you want to be pushed to tout.
1. Select **[!UICONTROL Push to MSE]**.
1. A new window will appear verifying the number of leads/contacts you'd like to push over. Select **[!UICONTROL Proceed to Group]**.[!DNLSales Connect] will not push over any contacts marked as [!UICONTROL Email Opt Out] in [!DNL Salesforce] or [!UICONTROL Unsubscribed] in [!DNL Sales Connect].

   >[!NOTE]
   >
   >[!DNL Sales Connect] will add this group titled "SFDC-..." to the Relationships page on the [web application](https://toutapp.com/login).

1. Select **[!UICONTROL Email Entire Group]** to send out this group email.
