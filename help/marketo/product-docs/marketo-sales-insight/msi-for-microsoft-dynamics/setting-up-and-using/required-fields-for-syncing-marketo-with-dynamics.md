---
unique-page-id: 11375827
description: Required Fields for Syncing Marketo with Dynamics - Marketo Docs - Product Documentation
title: Required Fields for Syncing Marketo with Dynamics
---

# Required Fields for Syncing Marketo with Dynamics {#required-fields-for-syncing-marketo-with-dynamics}

These fields *must* be synced with Marketo for both Lead and for Contact for Sales Insight to work:

* Priority 
* Urgency 
* Relative Score

If any of these fields are missing, you will see an error message in Marketo with the name of the missing fields. To fix this, check in your instance to be sure the fields are synced for both **Lead** and **Contact**. If not, add them.

Here's how to verify and add sync fields.

##### 1. Go to Admin and click Microsoft Dynamics. {#go-to-admin-and-click-microsoft-dynamics}

![](assets/image2015-10-9-9-3a50-3a9.png)

##### 2. Click Edit on Field Sync Details. {#click-edit-on-field-sync-details}

![](assets/image2015-10-9-9-3a52-3a23.png)

##### 3. Under Lead, check the Priority checkbox. {#under-lead-check-the-priority-checkbox}

![](assets/image2016-6-8-13-3a33-3a50.png)

##### 4. Now, scroll down and check the Urgency checkbox... {#now-scroll-down-and-check-the-urgency-checkbox}

![](assets/image2016-6-8-13-3a35-3a22.png)

##### 5. ...and the Relative Score checkbox. {#and-the-relative-score-checkbox}

![](assets/image2016-6-8-13-3a36-3a1.png)

##### 6. Next, check the checkboxes for Priority, Urgency, and Relative Score for Contact. {#next-check-the-checkboxes-for-priority-urgency-and-relative-score-for-contact}

![](assets/image2016-6-8-13-3a36-3a36.png)

##### 7. Click Save. {#click-save}

![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>Be sure to wait at least 10 minutes for a sync to run before verifying that you've fixed the issue.

>[!NOTE]
>
>**Related Articles**
>
>[Setting up Stars and Flames for Lead/Contact Records](http://docs.marketo.com/x/BICMAg)

