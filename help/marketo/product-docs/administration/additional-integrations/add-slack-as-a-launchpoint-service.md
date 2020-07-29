---
unique-page-id: 12983619
description: Add Slack as a LaunchPoint Service - Marketo Docs - Product Documentation
title: Add Slack as a LaunchPoint Service
---

# Add Slack as a LaunchPoint Service {#add-slack-as-a-launchpoint-service}

There are two notification types included in the Slack integration:

* **System notifications**: Get Slack notifications regarding important events in your Marketo instance, like alerts about current campaign statuses and any issues that require immediate attention (CRM errors and API limits).
* **Interesting moments**: When a Marketo Insight has been triggered by a known individual from a sales account, lead owners can be notified via Slack. Notifications include lead information as well as details about the sales account.

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>**Prerequisites**
>
>If you don't have Slack System Notifications already enabled, please [contact Support](http://docs.marketo.com/cdn-cgi/l/email-protection#ed9e989d9d829f99ad808c9f86889982c38e8280).

1. Go to **LaunchPoint**, then under **New** click **New Service**.

   ![](assets/image2017-11-27-14-3a13-3a18.png)

1. Enter a display name for your Slack integration. In the **Service** drop-down, select **Slack**. Click **Create**.

   ![](assets/image2017-11-27-15-3a54-3a11.png)

1. Click **Authorize**. This opens Slack in a new tab, where you will complete the authorization and grant Marketo permission to pull information from Slack.

   ![](assets/image2017-11-27-14-3a16-3a6.png)

1. In the new Slack tab, enter your workspace's URL and click **Continue**.

   ![](assets/image2017-11-27-15-3a1-3a29.png)

1. Enter your Slack credentials and click **Sign in**.

   ![](assets/image2017-11-27-15-3a1-3a3.png)

1. In the **Post to** drop-down, select the channel where you want notifications from Marketo to be posted. Review the requested permissions, then click **Authorize**.

   ![](assets/image2018-1-9-13-3a21-3a50.png)

1. You should see the confirmation screen below. The tab closes automatically.

   ![](assets/image2017-11-27-15-3a51-3a57.png)

1. Refresh the Marketo tab and confirm that Slack is now listed as an active service in LaunchPoint.

   ![](assets/image2017-11-27-15-3a55-3a37.png)

   Notifications will now begin posting to the channel you selected in step 6. They'll look something like this:

   ![](assets/samplenotification.png)

