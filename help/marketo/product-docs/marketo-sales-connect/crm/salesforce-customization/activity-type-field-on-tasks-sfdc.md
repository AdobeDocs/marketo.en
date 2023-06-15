---
unique-page-id: 14352476
description: Activity Type Field on Tasks (SFDC) - Marketo Docs - Product Documentation
title: Activity Type Field on Tasks (SFDC)
exl-id: b291e641-d3af-4667-a01c-cd491cd87add
---
# Activity Type Field on Tasks (SFDC) {#activity-type-field-on-tasks-sfdc}

With the help of Sales Connect you can have your emails and calls logged as an activity in Salesforce. A key part to having valuable data in Salesforce is having the Type field populate the correct value.

>[!NOTE]
>
>Logging emails via BCC will not look to the Task Type picklist, and will instead automatically populate the type field as "email" since they are being delivered to Salesforce through your BCC address.

## Requirements {#requirements}

* Connection with Salesforce
* No Default Type value selected on Task Type picklist
* Call, Reply, and Email must all exist under the Task Type picklist (capitalization matters)
* No Workflows or Triggers taking action on the value of the Type field

## Setup {#setup}

First check that you have the correct picklist values in place. You'll need the help of your Salesforce Admin to make any changes to your picklist.

1. Navigate to [Salesforce.com](https://salesforce.com) and click on Setup in the top right corner.
1. Click Customize.
1. Click Activities.
1. Click Task Fields.
1. Click Type.
1. You are now at the Task Type Picklist. Make sure there isn't a 'Default' selected.
1. Make sure there's a Type value listed for Email, Call, and Reply.

Now that this is in place, you will begin to see the Type field populate the corresponding value for logged Emails, Calls, and Replies. These values will _not_ be populated on Sales Connect reminder tasks.

>[!NOTE]
>
>If you don't see 'Reply' as a value, add it by clicking **New**. 'Reply' is not a standard value in Salesforce.
