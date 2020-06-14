---
unique-page-id: 14352476
description: Activity Type Field on Tasks (SFDC) - Marketo Docs - Product Documentation
title: Activity Type Field on Tasks (SFDC)
---

# Activity Type Field on Tasks (SFDC) {#activity-type-field-on-tasks-sfdc}

Activity Type Field on Tasks (SFDC) - Marketo Docs - Product Documentation

With the help of Sales Connect you can have your emails and calls logged as an activity in Salesforce. A key part to having valuable data in Salesforce is having the Type field populate the correct value.

>[!NOTE]
>
>Logging emails via BCC will not look to the Task Type picklist, and will instead automatically populate the type field as "email" since they are being delivered to Salesforce through your BCC address.

#### Requirements {#activitytypefieldontasks(sfdc)-requirements}

* Connection with Salesforce
* No Default Type value selected on Task Type picklist
* Call, Reply, and Email must all exist under the Task Type picklist (capitalization matters)
* No `Workflows` or `Triggers` taking action on the value of the Type field

#### Setup {#activitytypefieldontasks(sfdc)-setup}

First check that you have the correct picklist values in place. You'll need the help of your Salesforce Admin to make any changes to your picklist.

##### 1. Navigate to [Salesforce.com](http://Salesforce.com) and click on Setup in the top right corner. {#activitytypefieldontasks(sfdc)-navigatetosalesforce.comandclickonsetupinthetoprightcorner.}

##### 2. Click Customize. {#activitytypefieldontasks(sfdc)-clickcustomize.}

##### 3. Click Activities. {#activitytypefieldontasks(sfdc)-clickactivities.}

##### 4. Click Task Fields. {#activitytypefieldontasks(sfdc)-clicktaskfields.}

##### 5. Click Type. {#activitytypefieldontasks(sfdc)-clicktype.}

##### 6. You are now at the Task Type Picklist. Make sure there isn't a 'Default' selected. {#activitytypefieldontasks(sfdc)-youarenowatthetasktypepicklist.makesurethereisn'ta'default'selected.}

##### 7. Make sure there's a Type value listed for Email, Call, and Reply. {#activitytypefieldontasks(sfdc)-makesurethere'satypevaluelistedforemail-call-andreply.}

Now that this is in place, you will begin to see the Type field populate the corresponding value for logged Emails, Calls, and Replies. These values will **not** be populated on Sales Connect reminder tasks.

>[!NOTE]
>
>If you don't see 'Reply' as a value, add it by clicking **New*.*** 'Reply' is not a standard value in Salesforce.

