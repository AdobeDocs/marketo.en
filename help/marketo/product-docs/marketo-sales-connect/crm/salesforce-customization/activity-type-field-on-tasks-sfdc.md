---
unique-page-id: 14352476
description: Activity Type Field on Tasks (SFDC) - Marketo Docs - Product Documentation
title: Activity Type Field on Tasks (SFDC)
exl-id: b291e641-d3af-4667-a01c-cd491cd87add
---
# Activity Type Field on Tasks (SFDC) {#activity-type-field-on-tasks-sfdc}

With the help of [!DNL Sales Connect] you can have your emails and calls logged as an activity in [!DNL Salesforce]. A key part to having valuable data in [!DNL Salesforce] is having the [!UICONTROL Type] field populate the correct value.

>[!NOTE]
>
>Logging emails via BCC will not look to the Task Type picklist, and will instead automatically populate the type field as "email" since they are being delivered to [!DNL Salesforce] through your BCC address.

## Requirements {#requirements}

* Connection with [!DNL Salesforce]
* No Default Type value selected on Task Type picklist
* Call, Reply, and Email must all exist under the Task Type picklist (capitalization matters)
* No Workflows or Triggers taking action on the value of the Type field

## Setup {#setup}

First check that you have the correct picklist values in place. You'll need the help of your [!DNL Salesforce] Admin to make any changes to your picklist.

1. Navigate to [Salesforce.com](https://salesforce.com) and click on Setup in the top right corner.
1. Click **[!UICONTROL Customize]**.
1. Click **[!UICONTROL Activities]**.
1. Click **[!UICONTROL Task Fields]**.
1. Click **[!UICONTROL Type]**.
1. You are now at the Task Type Picklist. Make sure there isn't a 'Default' selected.
1. Make sure there's a [!UICONTROL Type] value listed for [!UICONTROL Email], [!UICONTROL Call], and [!UICONTROL Reply].

Now that this is in place, you will begin to see the [!UICONTROL Type] field populate the corresponding value for logged Emails, Calls, and Replies. These values will **not** be populated on [!DNL Sales Connect] reminder tasks.

>[!NOTE]
>
>If you don't see 'Reply' as a value, add it by clicking **[!UICONTROL New]**. 'Reply' is not a standard value in [!DNL Salesforce].
