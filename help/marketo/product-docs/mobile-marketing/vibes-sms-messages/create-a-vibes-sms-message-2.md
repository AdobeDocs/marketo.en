---
description: Create a Vibes SMS Message - Marketo Docs - Product Documentation
title: Create a Vibes SMS Message
hide: yes
hidefromtoc: yes
feature: Mobile Marketing
---
# Create a Vibes SMS Message {#create-a-vibes-sms-message}

Here's how to create a Vibes SMS message.

>[!AVAILABILITY]
>
>This feature is available as an add-on for your Adobe Marketo Engage Account. In order for it to be provisioned properly, it must be purchased through Adobe. Please contact the Adobe Account Team (your Account Manager) for details.

1. Go to **Marketing Activities**.

   ![](assets/mobile-right-click-hand.jpg)

1. Right-click on a program and select **New Local Asset**.

   ![](assets/mobile-right-click-hand.jpg)

1. Click **New Local Asset**.

   ![](assets/new-local-asset-hand.jpg)

   >[!TIP]
   >
   >Alternatively, you can click the **New** drop-down.

1. Click **SMS Message**.

   ![](assets/new-local-asset-selection-hand.jpg)

1. Enter a name and an optional description for the new SMS message and click **Create**.

   ![](assets/new-sms-message-offer-ends-soon-hands.jpg)

1. Click **Edit Draft**.

   ![](assets/edit-draft-hand.jpg)

1. In the message editor, click inside the blue bubble and begin entering text.

   ![](assets/message-text-pencil.jpg)

   >[!NOTE]
   >
   >The character limit for an SMS message is 160 characters using the standard ASCII character set. If you exceed 160 characters, your message will be split based on total character count.

1. Click **Token** in the Insert menu to add a token to your message.

   ![](assets/add-token-real-hand.jpg)

   >[!NOTE]
   >
   >Adding a token may cause the message to exceed the character limit. The message then will split, resulting in additional messages.

   >[!IMPORTANT]
   >
   >SMS Compliance: All outbound SMS messages must include the Brand Name or Program description. HELP and STOP instructions should be provided at least once per month per subscriber for recurring message programs.

   ?????? Using the Marketo URL shortener will result in X characters being used in your message ??????

1. Click **Link** in the Insert menu to add a link to your message.

   ![](assets/full-message-link-hand.jpg)

1. Select a link type. Marketo Landing Page is the default. If you go with that, you need to select the landing page from the drop-down and click **Insert**.

   ![](assets/insert-link-real-hands.jpg)

   >[!NOTE]
   >
   >* The two tracking links are selected by default.
   >* Using the Marketo URL shortener will result in X characters being used in your message.??????????????????

1. If you want to use an external URL instead, click the **External URL** button and enter the URL in the URL field. Click **Insert**.

   ![](assets/insert-link-url-hands.jpg)

   >[!CAUTION]
   >
   >It is recommended to _not_ use URL shorteners (e.g., Bitly), as the carriers may flag your message as spam. 

1. The link displays in the message.

   ![](assets/link-added.jpg)

   >[!NOTE]
   >
   >Marketo displays a link preview of the branded tracking domain. If you clear the mkt_tok link checkbox, the link is changed. Clear the Track Link checkbox too and the URL will be shortened to its basic length (for example, www.mygooglepage.com).

   ![](assets/image2016-7-27-16-3a20-3a16.png)

   >[!NOTE]
   >
   >Character count reflects only the characters contained in the lowest message.

If you insert more than the US limit, the editor breaks your message into sections. There is an absolute total limit of 900 characters. After reaching that limit, the message will be automatically truncated when it's sent to its audience.

US LIMIT????????
