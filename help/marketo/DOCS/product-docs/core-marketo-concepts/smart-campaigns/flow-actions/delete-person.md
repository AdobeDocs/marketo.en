---
unique-page-id: 1147082
description: Delete Person - Marketo Docs - Product Documentation
title: Delete Person
---

# Delete Person {#delete-person}

Delete Person - Marketo Docs - Product Documentation

Erroneous people sometimes get in your database. The Delete Person flow step can get rid of them.

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

#### Overview {#overview}

Use the flow step in a smart campaign.

![](assets/one-4.png)

>[!CAUTION]
>
>When you delete a person, all of their historical RCE data will be deleted as well. It cannot be undone.

#### Usage {#usage}

When you drag in the flow step it will automatically be set to delete from your CRM as well.

![](assets/two-4.png)

You can delete from Marketo and not from your CRM, like so:

![](assets/three-3.png)

>[!NOTE]
>
>Removing the person from your CRM **only works with Salesforce**. If you delete a person from Marketo and choose to keep them in Salesforce, they will be recreated in Marketo if their Salesforce record ever gets updated.

