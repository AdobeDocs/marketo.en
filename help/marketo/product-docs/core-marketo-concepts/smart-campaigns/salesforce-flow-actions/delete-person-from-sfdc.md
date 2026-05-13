---
unique-page-id: 1147031
description: Learn how to delete a person from Salesforce with a flow step. Remove the lead or contact from SFDC when they enter the flow.
title: Delete Person from SFDC
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
feature: Smart Campaigns, Salesforce Integration
TQID: https://experienceleague.adobe.com/f-Zvc4glfCtAagE314vrZjiWIcD3vaGIKmKGeZO18v0
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
---
# Delete Person from SFDC {#delete-person-from-sfdc}

If you need to remove a specific set of leads from Salesforce but leave them as people in Marketo Engage, you can use the Delete Person from SFDC flow action.

>[!NOTE]
>
>Only available when integrated with [!DNL Salesforce].

1. In the Database, click the person you want to remove from Salesforce. Then click **[!UICONTROL Person Actions]** and select **[!DNL Salesforce]**.

   ![](assets/delete-person-from-sfdc-1.png)

1. Select **[!UICONTROL Delete Person from SFDC]**.

   ![](assets/delete-person-from-sfdc-2.png)

1. Be sure the **[!UICONTROL Delete in Marketo]** setting is **[!UICONTROL false]**, then click **[!UICONTROL Run Now]**.

   ![](assets/delete-person-from-sfdc-3.png)

   After the flow step runs, your person will no longer be a lead in [!DNL Salesforce] but will remain in Marketo.

   >[!CAUTION]
   >
   >If you set **[!UICONTROL Delete in Marketo]** to **[!UICONTROL true]** and delete the people from Marketo and the leads from Salesforce, they are gone forever. This can't be undone.
