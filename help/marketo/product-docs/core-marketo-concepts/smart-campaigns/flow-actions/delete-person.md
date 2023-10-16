---
unique-page-id: 1147082
description: Delete Person - Marketo Docs - Product Documentation
title: Delete Person
exl-id: 40039444-9b2a-4b80-93bc-7da3d6e9475c
feature: Smart Campaigns
---
# Delete Person {#delete-person}

Erroneous people sometimes get into your database. The Delete Person flow step can get rid of them.

## Overview {#overview}

Use the flow step in a Smart Campaign.

![](assets/one-4.png)

>[!CAUTION]
>
>When you delete a person, all of their historical RCE data will be deleted as well. It cannot be undone.

## Usage {#usage}

When you drag in the flow step it will automatically be set to delete from your CRM as well.

![](assets/two-4.png)

You can delete from Marketo Engage and not from your CRM, like so:

![](assets/three-3.png)

>[!NOTE]
>
>Removing the person from your CRM _only works with [!DNL Salesforce]_. If you delete a person from Marketo and choose to keep them in [!DNL Salesforce], they will be recreated in Marketo if their [!DNL Salesforce] record ever gets updated.
