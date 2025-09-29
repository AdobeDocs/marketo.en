---
description: "[!DNL Sales Insight] for Non-Native MS [!DNL Dynamics] Integrations - Marketo Docs - Product Documentation"
title: "[!DNL Sales Insight] for Non-Native MS [!DNL Dynamics] Integrations"
exl-id: 07613ff8-b197-4a3d-88e9-720b68a6b8da
feature: Marketo Sales Insights
---
# [!DNL Sales Insight] for Non-Native MS [!DNL Dynamics] Integrations {#sales-insight-for-non-native-ms-dynamics-integrations}

If your Adobe Marketo Engage account is connected to MS [!DNL Dynamics] through a customized or non-native integration, use this article to configure [!DNL Sales Insight].

>[!PREREQUISITES]
>
>* The "MSI Non-Native" feature enabled for your Marketo instance before you start setting up MSI. If it isn't and you already purchased the feature, please contact [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}. If you have not yet purchased this feature, contact the Adobe Account Team (your Account Manager).
>* Download [MSI Package for Custom Sync](https://mktg-cdn.marketo.com/community/MarketoSalesInsight_NonNative.zip){target="_blank"}.
>* An MS Dynamics subscription with MSI Setup (we only support [Dynamics Online](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online.md){target="_blank"} at this time).
>* Marketo REST API [successfully set up](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}. The exposed CRUD APIs will be the basis of performing the non-native sync.
>* Read [this blog post](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/){target="_blank"} in order to get an understanding of the object and relationships.

## Successful non-native sync for MSI requires the following {#successful-non-native-sync-for-msi-requires-the-following}

1. Sync the MS [!DNL Dynamics] Sales User to Marketo.

   The MS [!DNL Dynamics] Sales User is an external user that owns the Leads/Contacts in MS [!DNL Dynamics]. A Marketo Sales Person needs to be upserted for the MS [!DNL Dynamics] Sales User. The externalSalesPersonId field is mandated for the upsert of the Sales Person.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Sales Person Field</strong></td>
        <td><strong>MS <span class="dnl">Dynamics</span> User Field</strong></td>
      <td><strong>Description</strong></td>
     </tr>
     <tr>
      <td>externalSalesPersonId</td>
        <td>MS <span class="dnl">Dynamics</span> User case-insensitive globally unique identifier</td>
      <td><p>Identifies the Marketo Sales Person record to an external MS <span class="dnl">Dynamics</span> User object.</p><p>It's mandated that the Sales Person be synced first before syncing the other objects so that the proper relationships will be created.</p></td>
     </tr>
    </tbody>
   </table>

   * [API documentation for Sales Person](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/sales-persons){target="_blank"}
   * [API documentation for syncing the Sales Person](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST){target="_blank"}

1. Sync the MS [!DNL Dynamics] Accounts to Marketo.

   A Marketo Company will need to be upserted for the MS [!DNL Dynamics] Account. The _externalCompanyId_ and _externalSalesPersonId_ fields are mandated for the upsert of the Company.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Company Field</strong></td>
        <td><strong>MS <span class="dnl">Dynamics</span> Account Field</strong></td>
      <td><strong>Description</strong></td>
     </tr>
     <tr>
      <td>externalCompanyId</td>
        <td>MS <span class="dnl">Dynamics</span> Account case-insensitive globally unique identifier</td>
        <td>Identifies a Marketo Company record to an external MS <span class="dnl">Dynamics</span> Account object.</td>
     </tr>
     <tr>
      <td>externalSalesPersonId</td>
        <td>MS <span class="dnl">Dynamics</span> Sales User case-insensitive globally unique identifier</td>
        <td>Identifies a Marketo Company record to an external MS <span class="dnl">Dynamics</span> Sales User object who is the Account owner.<br><br>Also used within Marketo to associate the Company to the Sales Person who owns the Company record. It is mandated to have the Sales Person synced first before setting this field.</td>
     </tr>
    </tbody>
   </table>

   * API documentation for Companies: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/companies](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/companies){target="_blank"}
   * API documentation for syncing Companies: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST){target="_blank"}

1. Sync the MS [!DNL Dynamics] Leads/Contacts to Marketo.

   You will need to upsert a Marketo Lead for the MS [!DNL Dynamics] Lead/Contact. The _externalPersonId_, _externalSalesPersonId_, and _externalCompanyId_ fields are mandated for the upsert of the Lead.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Lead Field</strong></td>
        <td><strong>MS <span class="dnl">Dynamics</span> Lead/Contact Field</strong></td>
      <td><strong>Description</strong></td>
     </tr>
     <tr>
      <td>externalPersonId</td>
        <td>MS <span class="dnl">Dynamics</span> Lead/Contact case-insensitive globally unique identifier</td>
        <td>Identifies the Marketo Lead record to an external MS <span class="dnl">Dynamics</span> Lead/Contact object.<br><br>This is a new field that is introduced for MSI Non-Native.</td>
     </tr>
     <tr>
      <td>externalSalesPersonId</td>
        <td>MS <span class="dnl">Dynamics</span> Sales User case-insensitive globally unique identifier</td>
        <td>Identifies the external MS <span class="dnl">Dynamics</span> Sales User object who owns this Lead/Contact.<br><br>Also relates the Lead with the Sales Person in Marketo. It is mandated to have the Sales Person correctly synced first.</td>
     </tr>
     <tr>
      <td>externalCompanyId</td>
        <td>MS <span class="dnl">Dynamics</span> Account case-insensitive globally unique identifier</td>
        <td>Identifies the external MS <span class="dnl">Dynamics</span> Account object that the Lead/Contact belongs to.<br><br>Also relates the lead record to a Company in Marketo. It is mandated that the MS <span class="dnl">Dynamics</span> Account be correctly synced first.</td>
     </tr>
    </tbody>
   </table>

   * API documentation for Leads: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/lead-database](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/lead-database){target="_blank"}
   * API documentation for syncing Leads: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST){target="_blank"}

1. Sync MS [!DNL Dynamics] Opportunities to Marketo.

   You will need to upsert a Marketo Opportunity for the MS [!DNL Dynamics] Opportunity. The _externalOpportunityId_, _externalCompanyId_, and _externalSalesPersonId_ fields are mandated for the upsert of the Opportunity.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Opportunity Object Field</strong></td>
        <td><strong>MS <span class="dnl">Dynamics</span> Opportunity Object Field</strong></td>
      <td><strong>Description</strong></td>
     </tr>
     <tr>
      <td>externalOpportunityId</td>
        <td>MS <span class="dnl">Dynamics</span> Lead/Contact case-insensitive globally unique identifier</td>
      <td>Identifies the Marketo Opportunity record to an external MS <span class="dnl">Dynamics</span> Opportunity object.</td>
     </tr>
     <tr>
      <td>externalCompanyId</td>
        <td>MS <span class="dnl">Dynamics</span> Account case-insensitive globally unique identifier</td>
        <td>Identifies the external MS <span class="dnl">Dynamics</span> Account object which this Opportunity belongs to. <br><br>It is mandated that the MS <span class="dnl">Dynamics</span> Account be correctly synced first.</td>
     </tr>
     <tr>
      <td>externalSalesPersonId</td>
        <td>MS <span class="dnl">Dynamics</span> Sales User case-insensitive globally unique identifier</td>
        <td>Identifies the external MS <span class="dnl">Dynamics</span> Sales User object who owns this Opportunity. </td>
     </tr>
    </tbody>
   </table>

   * API documentation for Opportunity: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * API documentation for syncing Opportunities: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Sync MS [!DNL Dynamics] Contact Roles to Marketo.

   MS [!DNL Dynamics] Contact Roles for a MS [!DNL Dynamics] Opportunity can be then synced via the Marketo Opportunity Role. The Opportunity Role record mandates the _externalOpportunityId_, _role_, and _leadId_ fields.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Opportunity Role Field</strong></td>
        <td><strong>MS <span class="dnl">Dynamics</span> Contact Role Field</strong></td>
      <td><strong>Description</strong></td>
     </tr>
     <tr>
      <td>externalOpportunityId</td>
        <td>MS <span class="dnl">Dynamics</span> Opportunity case-insensitive globally unique identifier</td>
      <td>Identifies the Marketo Opportunity Role to an external MS <span class="dnl">Dynamics</span> Opportunity object.<br><br>It is mandated that the MS <span class="dnl">Dynamics</span> Opportunity be correctly synced first.</td>
     </tr>
     <tr>
      <td>leadId</td>
      <td>N/A, this would be a Marketo Lead ID</td>
        <td>This would be the Marketo Lead ID of the synced MS <span class="dnl">Dynamics</span> Contact.<br><br>Once the contact is synced in Marketo, you can use the MS <span class="dnl">Dynamics</span> Contact case-insensitive globally unique identifier as the externalPersonId and query for the Marketo Lead using the Marketo REST API.</td>
     </tr>
     <tr>
      <td>role</td>
        <td>The Role field for the MS <span class="dnl">Dynamics</span> Contact</td>
      <td>Describes the role of the contact for this opportunity.</td>
     </tr>
    </tbody>
   </table>

   * API documentation for Opportunity: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * API documentation for syncing Opportunities: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Sync Last Interesting Moment/MSI Scoring fields to MS [!DNL Dynamics].

   Once your MS [!DNL Dynamics] objects are correctly synced to Marketo, you can then take advantage of the MSI features. The MSI Last Interesting Moment/Scoring fields will be exposed in the REST API for Leads. These fields are calculated by MSI and are read-only.

   The Last Interesting Moment/Scoring fields of a Marketo Lead will need to be regularly synced to MS [!DNL Dynamics] by using the REST API Lead endpoint. Query this endpoint for a Marketo Lead using the _externalPersonId_ as the filterType and passing in the MS [!DNL Dynamics] Lead GUID as the filterValue.

   | GET /rest/v1/leads.json?filterType=externalPersonId&filterValues=MS DynamicsLeadId1,MS DynamicsLeadId2  |
   |---|

   You can then use the values of these fields to sync to your MS [!DNL Dynamics] Lead/Contact object.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Lead Field</strong></td>
        <td><strong>MS <span class="dnl">Dynamics</span> Lead/Contact Field</strong></td>
      <td><strong>Description</strong></td>
     </tr>
     <tr>
      <td>msiLastInterestingMomentType</td>
      <td>Label: Last Interesting Moment Type<br>Name: Last_Interesting_Moment_Type__c</td>
      <td>Type of the last interesting moment for the Lead</td>
     </tr>
     <tr>
      <td>msiLastInterestingMomentDate</td>
      <td><p>Label: Last Interesting Moment Date</p><p>Name: Last_Interesting_Moment_Date__c</p></td>
      <td>Date of the last interesting moment for the Lead</td>
     </tr>
     <tr>
      <td>msiLastInterestingMomentDesc</td>
      <td><p>Label: Last Interesting Moment Description</p><p>Name: Last_Interesting_Moment_Desc__c</p></td>
      <td>Description of the last interesting moment for the Lead</td>
     </tr>
     <tr>
      <td>msiLastInterestingMomentSource</td>
      <td><p>Label: Last Interesting Moment Source</p><p>Name: Last_Interesting_Moment_Source__c</p></td>
      <td>Source of the last interesting moment for the Lead</td>
     </tr>
     <tr>
      <td>priority</td>
      <td><p>Label: Engagement</p><p>Name: Priority__c</p></td>
      <td>Priority of the Lead</td>
     </tr>
     <tr>
      <td>relativeUrgency</td>
      <td><p>Label: Relative Urgency Value</p><p>Name: Urgency_Value__c</p></td>
      <td>Relative Urgency of the Lead</td>
     </tr>
     <tr>
      <td>relativeScoring</td>
      <td><p>Label: Relative Scoring Value</p><p>Name: Relative_Score_Value__c</p></td>
      <td>Relative Scoring of the Lead</td>
     </tr>
    </tbody>
   </table>

   * Documentation for the Lead REST API: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET){target="_blank"}.

   >[!NOTE]
   >
   >For Lead/Contacts and Accounts object types: if you are syncing to your own custom fields for these mandatory fields, we support this customization while operating Marketo Sales Insights. Please reach out to [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} for help with this customization.

   Proper use of the external fields is key to a successful non-native sync. If you fail to see data in some of the views, it is likely that a certain field was not correctly synced. For example, if a lead's activities and interesting moments don't show up when looking in the MSI widget under their Account, it is likely that either the lead's company or the Account was not correctly synced. Performing a GET request for this lead while specifying the external fields will help you verify whether the lead was correctly synced. Moreover, the email for the external sales person in Marketo must match the email for that user in MS Dynamics. Data may not show in the Marketo tab in MS Dynamics if the emails do not match.
