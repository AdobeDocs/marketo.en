---
unique-page-id: 14746177
description: Resubscribing an Unsubscribe - Marketo Docs - Product Documentation
title: Resubscribing an Unsubscribe
exl-id: 1c451ff7-c56f-477e-b287-898c359aedcf
---
# Resubscribing an [!UICONTROL Unsubscribe] {#resubscribing-an-unsubscribe}

Sometimes people want to opt back into receiving emails. Here's how to make unsubscribes mailable again.

>[!NOTE]
>
>**Admin Permissions Required**

>[!CAUTION]
>
>Before resubscribing someone, you should be able to demonstrate that the authorization to resubscribe them is documented and in compliance with all applicable laws.

>[!NOTE]
>
>If you have unsubscribe sync turned on you must remove the unsubscribe from ToutApp and uncheck the opt out in [!DNL Salesforce] for the person record to not sync again.

1. Go to the [web application](https://toutapp.com/login) and click **[!UICONTROL People]**.

1. Select the person to open the person details view.

   ![](assets/two.png)

1. Click the three dots in the person details view and select **[!UICONTROL Remove Unsubscribe]**.

   ![](assets/three.png)

1. Select the reason why the person is being opted back in to receive emails, then click **[!UICONTROL Remove Unsubscribe]**.

   ![](assets/four.png)

>[!NOTE]
>
>If you have the unsubscribe sync turned on, you must uncheck the opt out box on the record in Salesforce as well or the nightly sync will re-unsubscribe the person in [!DNL Sales Connect], as it will detect the person is opted out in [!DNL Salesforce]. If either of the records are opt out/unsubscribed, the sync will mark the linked record as such.
