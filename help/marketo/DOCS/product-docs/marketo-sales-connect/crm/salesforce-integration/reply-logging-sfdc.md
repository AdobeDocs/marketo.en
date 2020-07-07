---
unique-page-id: 14352480
description: Reply Logging (SFDC) - Marketo Docs - Product Documentation
title: Reply Logging (SFDC)
---

# Reply Logging (SFDC) {#reply-logging-sfdc}

Reply Logging (SFDC) - Marketo Docs - Product Documentation

Sales Connect arms you with the ability to automatically log your prospects' replies to Salesforce. The structure that allows you to do this is based on our email reply tracking. If we can track a prospect's reply, we can log that reply to Salesforce.

#### Requirements {#requirements}

* Must be logging emails via API logging
* Must be able to [track a reply](http://docs.marketo.com/x/BYPS)
* Must be connected with Salesforce
* Must have Salesforce [API calls](http://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm) available

#### Enable Reply Logging {#enable-reply-logging}

1. To enable reply logging you can head over to your [Salesforce settings](http://docs.marketo.com/pages/assets/external-link.jspa) page. Once API logging is checked off you will see the option to check *Log Replies.  
   *

   >[!NOTE]
   >
   >Reply logging follows the same rules you have in place for logging emails sent. This includes how emails are logged; to Leads and Contacts; when there is a duplicate record; if no matching records are found.

#### Setting Type to Reply in Salesforce {#setting-type-to-reply-in-salesforce}

Getting meaningful data from your Salesforce reports is important. Having the ability to have the Type field populate as 'Reply' allows you to get that data through your reports. Partner up with your `Salesforce admin` to get this setup.&nbsp;

1. Go to **Setup **> **Customize **> **Activities **> **Task Fields**.
1. Click **Type**.
1. Under Task Type Picklist Values, click **New**.
1. Type "Reply" into the empty box. Make sure you capitalize the 'R' and click **Save**.

   >[!NOTE]
   >
   >You will not need to select a Default under the Type picklist. Sales Connect will see that this Activity Type is available in your Salesforce instance and populate the task field on your incoming activities accordingly.

