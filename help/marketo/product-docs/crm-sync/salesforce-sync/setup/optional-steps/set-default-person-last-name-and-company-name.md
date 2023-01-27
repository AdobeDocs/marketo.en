---
unique-page-id: 4719291
description: Set Default Person Last Name and Company Name - Marketo Docs - Product Documentation
title: Set Default Person Last Name and Company Name
exl-id: 0216fb41-adf0-4ccf-be22-c064e90be65a
---
# Set Default Person Last Name and Company Name {#set-default-person-last-name-and-company-name}

[!DNL Salesforce] requires (minimum) last name and company name for its Leads and Contacts. Incomplete records will not sync to [!DNL Salesforce]. If you wish to sync partial records, you must set default values for Marketo to use with [!DNL Salesforce].

1. Go to **[!UICONTROL Admin]** and click **[!UICONTROL Salesforce]**.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. Click **[!UICONTROL Edit Sync Options]**.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. Enter a **[!UICONTROL Default person last name]** and a **[!UICONTROL Default person company]** then click **[!UICONTROL Save]**.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo only assigns a default value when the record is initially synced to [!DNLSalesforce], and only if either of the required fields are empty.

And that's that! Every time a person is missing a last name and/or company name, Marketo will add the default value as it syncs the record over.
