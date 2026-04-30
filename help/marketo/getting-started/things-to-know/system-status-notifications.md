---
description: Subscribe to System Status Notifications - Marketo Engage Docs - Product Documentation
title: Subscribe to System Status Notifications
feature: Getting Started
exl-id: f4404a26-3b86-4dc7-8ecb-52a24fdb09b4
---
# Subscribe to system status notifications {#subscribe-to-system-status-notifications}

Learn how to subscribe to different status notifications to stay up to date on current issues.

>[!PREREQUISITES]
>
>Before you can create a subscription, you must first identify what data center and pod/server your subscription is located in.

## Identify your data center {#identify}

1. In the **Admin** section of Marketo Engage, click **My Account**.

   ![](assets/subscribe-to-system-status-notifications-1.png)

1. Scroll down to _Support Information_.  

   ![](assets/subscribe-to-system-status-notifications-2.png)

In the _Data center_ field, the letters are the data center and the numbers are the pod. In the example above, the user is in our Ashburn data center on pod 49. 

In step 7 of [the section below](#create-a-subscription), the user would select the regional location **Marketo Ashburn** and pod **ab49**.

**Data center abbreviations**

* ab: Ashburn
* sj: San Jose
* sn: Sydney
* lon: London
* nld: Amsterdam

>[!TIP]
>
>This method can also be used to identify what Real Time Personalization (RTP) pod/server your subscription is in.

## Create a subscription {#create-a-subscription}

After [identifying your data center and pod/server](#identify), follow the steps below to create a subscription.

1. On [status.adobe.com](https://status.adobe.com), click **Manage Subscriptions**.

   ![](assets/subscribe-to-system-status-notifications-3.png)

1. Sign in (if you are not already) using your Adobe credentials, or click **Create an account** if you don't have one.

   ![](assets/subscribe-to-system-status-notifications-4.png)
 
1. Stay in the _Product descriptions_ tab and click **Create subscriptions**.

   ![](assets/subscribe-to-system-status-notifications-5.png)

1. Click the ![plus sign icon](assets/icon-plus-sign.png) icon next to _Experience Cloud_ to expand the menu. Do the same for _Adobe Marketo Engage_.

   ![](assets/subscribe-to-system-status-notifications-6.png){width="800"}

1. Select the product offerings/services you want to receive notifications about and click **Continue**.

   >[!TIP]
   >
   >Check _Adobe Marketo Engage_ to select all.

   ![](assets/subscribe-to-system-status-notifications-7.png){width="800"}

1. Select the desired event types.

   ![](assets/subscribe-to-system-status-notifications-8.png)

   <table style="width:500px;">
   <tr>
   <td style="width:35%;"><b>Major Service Issue</b></td>
   <td>Service unavailability or severe performance degradation for multiple users on production systems.</td>
   </tr>
   <tr>
   <td style="width:35%;"><b>Minor Service Issue</b></td>
   <td>Partial service unavailability or moderate performance degradation for multiple users on production systems.</td>
   </tr>
   <tr>
   <td style="width:35%;"><b>Service Maintenance</b></td>
   <td>Scheduled windows to perform product maintenance that may impact product availability or performance.</td>
   </tr>
   <tr>
   <td style="width:35%;"><b>Announcements</b></td>
   <td>Global, product family, or product-related messages that have a wide impact.</td>
   </tr>
   </table>

1. Select the regional location and environment. Click **Continue**.

   ![](assets/subscribe-to-system-status-notifications-9.png){width="900"}

   >[!NOTE]
   >
   >If you missed where to find this, see [Identify your data center](#identify).

1. Choose your subscription preference, **Email** or **Slack**, and click **Continue**.

   ![](assets/subscribe-to-system-status-notifications-10.png)

1. Review your selections and click **Confirm preferences**.

   ![](assets/subscribe-to-system-status-notifications-11.png)
