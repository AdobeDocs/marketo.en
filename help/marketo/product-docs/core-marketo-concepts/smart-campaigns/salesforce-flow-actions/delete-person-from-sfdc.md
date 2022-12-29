---
unique-page-id: 1147031
description: Delete Person from SFDC - Marketo Docs - Product Documentation
title: Delete Person from SFDC
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
---
# Delete Person from SFDC {#delete-person-from-sfdc}

If you need to remove a specific set of leads from [!DNL Salesforce] but leave them as people in Marketo, you can use the Delete Person from SFDC flow action.

>[!NOTE]
>
>Only available when integrated with [!DNL Salesforce].

1. In the Database, click the person you want to remove from [!DNL Salesforce]. Then click **[!UICONTROL Person Actions]** and select **[!UICONTROL Salesforce]**.

   ![](assets/person-actions-salesforce.png)

1. Select **[!UICONTROL Delete Person from SFDC]**.

   ![](assets/delete-person-from-sfdc.png)

1. Be sure the **[!UICONTROL Delete in Marketo]** setting is **[!UICONTROL false]**, then click **[!UICONTROL Run Now]**.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   After the flow step runs, your person will no longer be a lead in [!DNL Salesforce] but will remain in Marketo.

   >[!CAUTION]
   >
   >If you set **[!UICONTROL Delete in Marketo]** to **[!UICONTROL true]** and delete the people from Marketo and the leads from [!DNL Salesforce], they are gone forever. This can't be undone.
