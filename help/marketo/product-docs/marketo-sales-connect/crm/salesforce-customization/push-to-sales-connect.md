---
unique-page-id: 14352477
description: Learn how to use the Push to Sales Connect button in Salesforce. Add leads or contacts from Salesforce to Sales Connect with one click.
title: Push to [!DNL Sales Connect]
exl-id: 8fb99d28-d6c6-47c3-b4d2-c416251aff47
feature: Marketo Sales Connect
TQID: https://experienceleague.adobe.com/piy3bPtiO48FQhWEmpu5qo4denlJ8v1ZU-VXBlWh0Mg
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
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
1. A new window will appear verifying the number of leads/contacts you'd like to push over. Select **[!UICONTROL Proceed to Group]**.[!DNL Sales Connect] will not push over any contacts marked as [!UICONTROL Email Opt Out] in [!DNL Salesforce] or [!UICONTROL Unsubscribed] in [!DNL Sales Connect].

   >[!NOTE]
   >
   >[!DNL Sales Connect] will add this group titled "SFDC-..." to the Relationships page on the [web application](https://toutapp.com/login).

1. Select **[!UICONTROL Email Entire Group]** to send out this group email.
