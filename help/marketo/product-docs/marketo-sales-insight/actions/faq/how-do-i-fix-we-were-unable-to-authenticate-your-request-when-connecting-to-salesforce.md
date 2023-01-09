---
description: How Do I Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce - Marketo Docs - Product Documentation
title: How Do I Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce
exl-id: ef876f0f-bd76-4ba5-bf48-885ee048ceae
---
# How Do I Fix "We Were Unable to Authenticate Your Request" When Connecting to [!DNL Salesforce] {#how-do-i-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

If you receive the error message "We were unable to authenticate your request" when trying to connect [!DNL Sales Insight Actions] to [!DNL Salesforce], there might be a restriction on your access to [!DNL Salesforce]'s API. Check with your [!DNL Salesforce] Admin to make sure the following things are in place.

## Enable API in User Permissions {#enable-api-in-user-permissions}

1. Have a [!DNL Salesforce] Admin log into SFDC.
1. Select **[!UICONTROL Setup]**.
1. Select **[!UICONTROL Manage Users]**.
1. Select **[!UICONTROL Profiles]**.
1. Find the Profile that the ToutApp users are under and click **[!UICONTROL Edit]**.
1. Scroll down to **[!UICONTROL Administrative Permissions]** and make sure **[!UICONTROL API Enabled]** is checked.

## Check if [!DNL Salesforce] is Blocking [!DNL Sales Insight Actions] from Connecting {#check-if-salesforce-is-blocking-sales-insight-actions-from-connecting}

1. Have a [!DNL Salesforce] Admin log in to SFDC.
1. Select **[!UICONTROL Setup]**.
1. Select **[!UICONTROL Manage Apps]**.
1. Select **[!UICONTROL Connected Apps OAuth Usage]**.
1. Make sure that [!DNL Sales Insight Actions] shows "Block" next to it. If you see "[!UICONTROL Unblock]", click the button to unblock [!DNL Sales Insight Actions]' access to [!DNL Salesforce].
