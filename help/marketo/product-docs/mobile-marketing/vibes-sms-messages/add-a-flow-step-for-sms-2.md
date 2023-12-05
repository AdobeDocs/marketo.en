---
description: Add a Flow Step for SMS - Marketo Docs - Product Documentation
title: Add a Flow Step for SMS
hide: yes
hidefromtoc: yes
feature: Mobile Marketing
---
# Add a Flow Step for SMS {#add-a-flow-step-for-sms}

Marketo Engage has three flow steps you can use in your SMS Smart Campaigns:

* **Send SMS Message** - This flow action sends messages to people from the Marketo Smart List that are subscribed to a user opted-in Vibes subscription list. It does not initiate the subscription process.
* **Subscribe to Vibes List** - This flow action initiates the SMS subscription process via a user-selected Vibes Acquisition Campaign. Vibes then sends a confirmation message; the recipient must reply "Y" to it to confirm opt-in within 24 hours. Once the user has opted in, they will become a member of your associated Vibes subscription list. 
* **Unsubscribe from Vibes List** - This flow action unsubscribes each person from a user opted-in Vibes subscription list. When a user texts "stop" to your code, their person record is updated to reflect they're no longer a member of the Vibes Subscription list.

>[!NOTE]
>
>When sending SMS messages:
>
>* Marketo de-dupes by phone number. So, if multiple people have the same phone number, only one person will receive the message if they're a member of only one Vibes Subscription list. De-duping is done at the Vibes Subscription list level, not the Marketo program level.
>* Marketo will not send to people who are blocklisted or Marketing Suspended.

For general information on setting up flow steps, see [Add a Flow Step to a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md).

Here are the basics for using SMS.

1. In My Marketo, click **Marketing Activities**.

   ![](assets/add-a-flow-step-for-sms-1.png)

1. Find and select the Smart Campaign you want to add the SMS flow to.

   SCREENSHOT

1. In the Smart List tab, choose the desired trigger(s) (e.g., "Filled out Form").

   SCREENSHOT

1. In the **Flow** tab, drag over the flow step (e.g., **Send SMS Message**). Select the SMS Message and the Vibes list from the drop-downs.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >The Vibes List selector acts as a further filter to the audience already identified in the smart list to target only those leads who belong to that Vibes list.
   >
   >The **Subscribe to Vibes List** and **Unsubscribe from Vibes List** flows have different requirements. For **Subscribe**, you must select the Vibes list and the Vibes acquisition campaign. For **Unsubscribe**, only the Vibes list is required.
