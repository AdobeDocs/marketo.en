---
unique-page-id: 1147082
description: Learn how to delete a person from the database with a flow step. Remove people who meet criteria from Marketo.
title: Delete Person
exl-id: 40039444-9b2a-4b80-93bc-7da3d6e9475c
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/89EPt9SVBCuluSojdqLE4BawaPGGbzHLSmYHV9w6Uko
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
---
# Delete Person {#delete-person}

Erroneous people sometimes get into your database. The Delete Person flow step can get rid of them.

![](assets/delete-person-1.png)

>[!CAUTION]
>
>When you delete a person, all of their historical RCE data will be deleted as well. It cannot be undone.

1. When you drag in the flow step, it will automatically be set to delete from your CRM as well.

   ![](assets/delete-person-2.png)

1. You can delete from Marketo Engage and not from your CRM, like so:

   ![](assets/delete-person-3.png)

>[!NOTE]
>
>Removing the person from your CRM _only works with [!DNL Salesforce]_. If you delete a person from Marketo and choose to keep them in [!DNL Salesforce], they will be recreated in Marketo if their [!DNL Salesforce] record ever gets updated.
