---
unique-page-id: 1147031
description: Delete Person from SFDC - Marketo Docs - Product Documentation
title: Delete Person from SFDC
---

# Delete Person from SFDC {#delete-person-from-sfdc}

Delete Person from SFDC - Marketo Docs - Product Documentation

If you need to remove a specific set of leads from Salesforce but leave them as people in Marketo, you can use the Delete Person from SFDC flow action.

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

>[!NOTE]
>
>Only available when integrated with Salesforce.

1. In the Database, click the person you want to remove from Salesforce. Then click **Person Actions** and select **Salesforce**.

   ![](assets/person-actions-salesforce.png)

1. Select **Delete Person from SFDC**.

   ![](assets/delete-person-from-sfdc.png)

1. Be sure the **Delete in Marketo** setting is **false**, then click **Run Now**.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   After the flow step runs, your person will no longer be a lead in Salesforce but will remain in Marketo.

   >[!CAUTION]
   >
   >If you set **Delete in Marketo** to **true** and delete the people from Marketo and the leads from Salesforce, they are gone forever. This can't be undone.

