---
description: Sales Insight for Non-Native MS Dynamics Integrations - Marketo Docs - Product Documentation
title: Sales Insight for Non-Native MS Dynamics Integrations
exl-id: 07613ff8-b197-4a3d-88e9-720b68a6b8da
---
# Sales Insight for Non-Native MS Dynamics Integrations {#sales-insight-for-non-native-ms-dynamics-integrations}

If your Adobe Marketo Engage account is connected to MS Dynamics through a customized or non-native integration, use this article to configure Sales Insight.

>[!PREREQUISITES]
>
>* The “MSI Non-Native” feature enabled for your Marketo instance before you start setting up MSI (if it isn’t and you already purchased the feature, please contact [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} - if you have not yet purchased this feature, contact your Customer Success Manager).
>* An MS Dynamics subscription with MSI Setup ([On-prem](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-365.md){target="_blank"}, [Dynamics Online](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online.md){target="_blank"}).
>* Marketo REST API [successfully set up](https://developers.marketo.com/rest-api/){target="_blank"}. The exposed CRUD APIs will be the basis of performing the non-native sync.
>* Read [this blog post](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/){target="_blank"} in order to get an understanding of the object and relationships.

## Successful non-native sync for MSI requires the following {#successful-non-native-sync-for-msi-requires-the-following}

1. Sync the MS Dynamics Sales User to Marketo.

   The MS Dynamics Sales User is an external user that owns the Leads/Contacts in MS Dynamics. A Marketo Sales Person needs to be upserted for the MS Dynamics Sales User. The externalSalesPersonId field is mandated for the upsert of the Sales Person.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Sales Person Field</strong></td> 
      <td><strong>MS Dynamics User Field</strong></td> 
      <td><strong>Description</strong></td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics User case-insensitive globally unique identifier</td> 
      <td><p>Identifies the Marketo Sales Person record to an external MS Dynamics User object.</p><p>It's mandated that the Sales Person be synced first before syncing the other objects so that the proper relationships will be created.</p></td> 
     </tr> 
    </tbody> 
   </table>

   * API documentation for Sales Person: [https://developers.marketo.com/rest-api/lead-database/sales-persons/](https://developers.marketo.com/rest-api/lead-database/sales-persons/){target="_blank"}
   * API documentation for syncing the Sales Person: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsUsingPOST){target="_blank"}

1. Sync the MS Dynamics Accounts to Marketo.

   A Marketo Company will need to be upserted for the MS Dynamics Account. The _externalCompanyId_ and _externalSalesPersonId_ fields are mandated for the upsert of the Company.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Company Field</strong></td> 
      <td><strong>MS Dynamics Account Field</strong></td> 
      <td><strong>Description</strong></td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics Account case-insensitive globally unique identifier</td> 
      <td>Identifies a Marketo Company record to an external MS Dynamics Account object.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales User case-insensitive globally unique identifier</td> 
      <td>Identifies a Marketo Company record to an external MS Dynamics Sales User object who is the Account owner.<br><br>Also used within Marketo to associate the Company to the Sales Person who owns the Company record. It is mandated to have the Sales Person synced first before setting this field.</td> 
     </tr> 
    </tbody> 
   </table>

   * API documentation for Companies: [https://developers.marketo.com/rest-api/lead-database/companies/](https://developers.marketo.com/rest-api/lead-database/companies/){target="_blank"}  
   * API documentation for syncing Companies: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST){target="_blank"}

1. Sync the MS Dynamics Leads/Contacts to Marketo.

   You will need to upsert a Marketo Lead for the MS Dynamics Lead/Contact. The _externalPersonId_, _externalSalesPersonId_, and _externalCompanyId_ fields are mandated for the upsert of the Lead.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Lead Field</strong></td> 
      <td><strong>MS Dynamics Lead/Contact Field</strong></td> 
      <td><strong>Description</strong></td> 
     </tr> 
     <tr> 
      <td>externalPersonId</td> 
      <td>MS Dynamics Lead/Contact case-insensitive globally unique identifier</td> 
      <td>Identifies the Marketo Lead record to an external MS Dynamics Lead/Contact object.<br><br>This is a new field that is introduced for MSI Non-Native.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales User case-insensitive globally unique identifier</td> 
      <td>Identifies the external MS Dynamics Sales User object who owns this Lead/Contact.<br><br>Also relates the Lead with the Sales Person in Marketo. It is mandated to have the Sales Person correctly synced first.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics Account case-insensitive globally unique identifier</td> 
      <td>Identifies the external MS Dynamics Account object that the Lead/Contact belongs to.<br><br>Also relates the lead record to a Company in Marketo. It is mandated that the MS Dynamics Account be correctly synced first.</td> 
     </tr> 
    </tbody> 
   </table>

   * API documentation for Leads: [https://developers.marketo.com/rest-api/lead-database/leads/](https://developers.marketo.com/rest-api/lead-database/leads/){target="_blank"}
   * API documentation for syncing Leads: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST){target="_blank"}

1. Sync MS Dynamics Opportunities to Marketo.

   You will need to upsert a Marketo Opportunity for the MS Dynamics Opportunity. The _externalOpportunityId_, _externalCompanyId_, and _externalSalesPersonId_ fields are mandated for the upsert of the Opportunity.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Opportunity Object Field</strong></td> 
      <td><strong>MS Dynamics Opportunity Object Field</strong></td> 
      <td><strong>Description</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>MS Dynamics Lead/Contact case-insensitive globally unique identifier</td> 
      <td>Identifies the Marketo Opportunity record to an external MS Dynamics Opportunity object.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics Account case-insensitive globally unique identifier</td> 
      <td>Identifies the external MS Dynamics Account object which this Opportunity belongs to. <br><br>It is mandated that the MS Dynamics Account be correctly synced first.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales User case-insensitive globally unique identifier</td> 
      <td>Identifies the external MS Dynamics Sales User object who owns this Opportunity. </td> 
     </tr> 
    </tbody> 
   </table>

   * API documentation for Opportunity: [https://developers.marketo.com/rest-api/lead-database/opportunities/](https://developers.marketo.com/rest-api/lead-database/opportunities/){target="_blank"}  
   * API documentation for syncing Opportunities: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST){target="_blank"}

1. Sync MS Dynamics Contact Roles to Marketo.

   MS Dynamics Contact Roles for a MS Dynamics Opportunity can be then synced via the Marketo Opportunity Role. The Opportunity Role record mandates the _externalOpportunityId_, _role_, and _leadId_ fields.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Opportunity Role Field</strong></td> 
      <td><strong>MS Dynamics Contact Role Field</strong></td> 
      <td><strong>Description</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>MS Dynamics Opportunity case-insensitive globally unique identifier</td> 
      <td>Identifies the Marketo Opportunity Role to an external MS Dynamics Opportunity object.<br><br>It is mandated that the MS Dynamics Opportunity be correctly synced first.</td> 
     </tr> 
     <tr> 
      <td>leadId</td> 
      <td>N/A, this would be a Marketo Lead ID</td> 
      <td>This would be the Marketo Lead ID of the synced MS Dynamics Contact.<br><br>Once the contact is synced in Marketo, you can use the MS Dynamics Contact case-insensitive globally unique identifier as the externalPersonId and query for the Marketo Lead using the Marketo REST API.</td> 
     </tr> 
     <tr> 
      <td>role</td> 
      <td>The Role field for the MS Dynamics Contact</td> 
      <td>Describes the role of the contact for this opportunity.</td> 
     </tr> 
    </tbody> 
   </table>

   * API documentation for Opportunity: [https://developers.marketo.com/rest-api/lead-database/opportunities/](https://developers.marketo.com/rest-api/lead-database/opportunities/){target="_blank"}
   * API documentation for syncing Opportunities: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST){target="_blank"}

1. Sync Last Interesting Moment/MSI Scoring fields to MS Dynamics.

   Once your MS Dynamics objects are correctly synced to Marketo, you can then take advantage of the MSI features. The MSI Last Interesting Moment/Scoring fields will be exposed in the REST API for Leads. These fields are calculated by MSI and are read-only.  
  
   The Last Interesting Moment/Scoring fields of a Marketo Lead will need to be regularly synced to MS Dynamics by using the REST API Lead endpoint. Query this endpoint for a Marketo Lead using the _externalPersonId_ as the filterType and passing in the MS Dynamics Lead GUID as the filterValue.

   | GET /rest/v1/leads.json?filterType=externalPersonId&filterValues=MS DynamicsLeadId1,MS DynamicsLeadId2  |
   |---|

   You can then use the values of these fields to sync to your MS Dynamics Lead/Contact object.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Lead Field</strong></td> 
      <td><strong>MS Dynamics Lead/Contact Field</strong></td> 
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

   * Documentation for the Lead REST API: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET){target="_blank"}.

   Proper use of the external fields is key to a successful non-native sync. If you fail to see data in some of the views, it is likely that a certain field was not correctly synced. For example, if a lead’s activities and interesting moments don’t show up when looking in the MSI widget under their Account, it is likely that either the lead’s company or the Account was not correctly synced. Performing a GET request for this lead while specifying the external fields will help you verify whether the lead was correctly synced. Moreover, the email for the external sales person in Marketo must match the email for that user in MS Dynamics. Data may not show in the Marketo tab in MS Dynamics if the emails do not match.
