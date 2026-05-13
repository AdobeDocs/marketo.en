---
unique-page-id: 1147019
description: Learn how to convert a person in a flow step. Mark anonymous visitors as known when they convert.
title: Convert Person
exl-id: b0ff0b63-a6a3-48c5-92ef-7ece5c182d28
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/XI6TVsdMugb-Fim88OIONkLjDxXSvSqRVV4gMHtu7wU
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
---
# Convert Person {#convert-person}

Use this flow step to convert a person to a contact in [!DNL Salesforce]. You can decide who to assign the contact to, to send a notification to the owner, and to set a converted status.

>[!NOTE]
>
>This is only available when integrated with [!DNL Salesforce].

![](assets/convert-person-1.png)

1. Select who you want to assign the resulting contact, account, and opportunity to.

   ![](assets/convert-person-2.png)

   >[!CAUTION]
   >
   >Converting a person in Marketo will result in a new account and opportunity in [!DNL Salesforce]. If you don't want duplicate accounts, use [!DNL Salesforce] to convert.

1. Choose if you want a **[!UICONTROL notification]** sent to the owner or not.

   ![](assets/convert-person-3.png)

1. Select the **[!UICONTROL converted status]**.

   ![](assets/convert-person-4.png)
