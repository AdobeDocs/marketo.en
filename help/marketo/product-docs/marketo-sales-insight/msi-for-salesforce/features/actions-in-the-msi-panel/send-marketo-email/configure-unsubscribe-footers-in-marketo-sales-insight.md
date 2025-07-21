---
unique-page-id: 2953373
description: Configure Unsubscribe Footers in Marketo Sales Insight - Marketo Docs - Product Documentation
title: Configure Unsubscribe Footers in Marketo Sales Insight
exl-id: 16c1fcba-6826-400c-ab7c-371d8653d4ad
feature: Marketo Sales Insights
---
# Configure Unsubscribe Footers in [!DNL Marketo Sales Insight] {#configure-unsubscribe-footers-in-marketo-sales-insight}

Sales emails automatically put the unsubscribe footer at the bottom. However, you can adjust the settings to meet your needs.

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>**Definition**
>
>**Sales emails** are those sent from [!DNL Sales Insight] (it does not include those sent from the Marketo Outlook Plugin).

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/one-1.png)

1. Click **[!UICONTROL Sales Insight]**, then **[!UICONTROL Edit Settings]**.

   ![](assets/two-1.png)

   There are several options. First let's take a look at the types of emails you can change the settings for.

   ![](assets/three-1.png)

    * **[!UICONTROL No Template]** - Manually composed by sales user.
    * **[!UICONTROL Standard Email]** - Emails based on a template.
    * **[!UICONTROL Operational Email]** - Emails that ignore Unsubscribed, Marketing Suspended, and Communication Limits (they send no matter what).

   You have the option to set different behavior for each type.

   >[!CAUTION]
   >
   >**[!UICONTROL Respect Unsubscribe Settings]**: unsubscribed leads will NOT receive the email even if the published email is "operational"
   >
   >**[!UICONTROL Ignore Unsubscribe Settings]**: unsubscribed leads WILL receive the email

1. Make the changes you want, then click **[!UICONTROL Save]**.

   >[!TIP]
   >
   >The last two choices allow you to dynamically include/exclude the unsubscribe footer depending on number of recipients (Greater than 1 or Greater than 5).

   ![](assets/four-1.png)

Whew! A little complicated, but pretty flexible, right?
