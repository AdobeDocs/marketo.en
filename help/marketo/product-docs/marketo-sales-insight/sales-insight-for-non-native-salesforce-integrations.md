---
unique-page-id: 45417125
description: Sales Insight for Non-Native Salesforce Integrations - Marketo Docs - Product Documentation
title: Sales Insight for Non-Native Salesforce Integrations
---

# Sales Insight for Non-Native Salesforce Integrations {#sales-insight-for-non-native-salesforce-integrations}

If your Marketo account is connected to Salesforce through a customized or non-native integration, use this document to configure Sales Insight.

>[!PREREQUISITES]
>
>* Reach out to your Customer Success Manager to enable the “MSI Non-Native” feature for your Marketo instance.
>* A Salesforce account with MSI Package set-up.
>* Marketo REST API [successfully set up](https://developers.marketo.com/rest-api/). The exposed CRUD APIs will be the basis of performing the non-native sync.
>* Read [this blog post](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/) in order to get an understanding of the object and relationships.
>* Set up Salesforce objects to display the 18 character case-insensitive globally unique identifier rather than the 15 character case-sensitive globally unique identifier.

>[!NOTE]
>
>The REST API Configuration in the Marketo MSI Admin Panel cannot be used for the Non-Native sync.

## Successful non-native sync for MSI requires the following {#successful-non-native-sync-for-msi-requires-the-following}

1. Sync the Salesforce Sales User to Marketo.

   The Salesforce Sales User is an external user that owns the Leads/Contacts in Salesforce. A Marketo Sales Person needs to be upserted for the Salesforce Sales User. The *externalSalesPersonId* field is mandated for the upsert of the Sales Person.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Sales Person Field</strong></td> 
   <td><strong>Salesforce Sales User Field</strong></td> 
   <td><strong>Description</strong></td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce Sales User case-insensitive globally unique identifier</td> 
   <td><p>Identifies the Marketo Sales Person record to an external Salesforce Sales User object.</p><p>It's mandated that the Sales Person be synced first before syncing the other objects so that the proper relationships will be created.</p></td> 
  </tr> 
 </tbody> 
</table>

   API documentation for Sales Person: [https://developers.marketo.com/rest-api/lead-database/sales-persons/](https://developers.marketo.com/rest-api/lead-database/sales-persons/)  
   API documentation for syncing the Sales Person: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsUsingPOST)

1. Sync the Salesforce Accounts to Marketo.

   A Marketo Company will need to be upserted for the Salesforce Account. The _externalCompanyId_ and _externalSalesPersonId_ fields are mandated for the upsert of the Company.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Company Field</strong></td> 
   <td><strong>Salesforce Account Field</strong></td> 
   <td><strong>Description</strong></td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce Account case-insensitive globally unique identifier</td> 
   <td>Identifies a Marketo Company record to an external Salesforce Account object.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce Sales User case-insensitive globally unique identifier</td> 
   <td>Identifies a Marketo Company record to an external Salesforce Sales User object who is the Account owner.<br><br>Also used within Marketo to associate the Company to the Sales Person who owns the Company record. It is mandated to have the Sales Person synced first before setting this field.</td> 
  </tr> 
 </tbody> 
</table>

   API documentation for Companies: [https://developers.marketo.com/rest-api/lead-database/companies/](https://developers.marketo.com/rest-api/lead-database/companies/)  
   `API documentation for syncing Companies:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST)`

1. Sync the Salesforce Leads/Contacts to Marketo.

   You will need to upsert a Marketo Lead for the Salesforce Lead/Contact. The _externalPersonId_, _externalSalesPersonId_, and _externalCompanyId_ fields are mandated for the upsert of the Lead.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Lead Field</strong></td> 
   <td><strong>Salesforce Lead/Contact Field</strong></td> 
   <td><strong>Description</strong></td> 
  </tr> 
  <tr> 
   <td>externalPersonId</td> 
   <td>Salesforce Lead/Contact case-insensitive globally unique identifier</td> 
   <td>Identifies the Marketo Lead record to an external Salesforce Lead/Contact object.<br><br>This is a new field that is introduced for MSI Non-Native.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce Sales User case-insensitive globally unique identifier</td> 
   <td>Identifies the external Salesforce Sales User object who owns this Lead/Contact.<br><br>Also relates the Lead with the Sales Person in Marketo. It is mandated to have the Sales Person correctly synced first.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce Account case-insensitive globally unique identifier</td> 
   <td>Identifies the external Salesforce Account object that the Lead/Contact belongs to.<br><br>Also relates the lead record to a Company in Marketo. It is mandated that the Salesforce Account be correctly synced first.</td> 
  </tr> 
 </tbody> 
</table>

   API documentation for Leads: [`https://developers.marketo.com/rest-api/lead-database/leads/`](https://developers.marketo.com/rest-api/lead-database/leads/)  
   API documentation for syncing Leads:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST)

1. Sync Salesforce Opportunities to Marketo.

   You will need to upsert a Marketo Opportunity for the Salesforce Opportunity. The _externalOpportunityId_, _externalCompanyId_, and _externalSalesPersonId_ fields are mandated for the upsert of the Opportunity.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Opportunity Object Field</strong></td> 
   <td><strong>Salesforce Opportunity Object Field</strong></td> 
   <td><strong>Description</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Salesforce Lead/Contact case-insensitive globally unique identifier</td> 
   <td>Identifies the Marketo Opportunity record to an external Salesforce Opportunity object.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce Account case-insensitive globally unique identifier</td> 
   <td>Identifies the external Salesforce Account object which this Opportunity belongs to. <br><br>It is mandated that the Salesforce Account be correctly synced first.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce Sales User case-insensitive globally unique identifier</td> 
   <td>Identifies the external Salesforce Sales User object who owns this Opportunity. </td> 
  </tr> 
 </tbody> 
</table>

   API documentation for Opportunity: [`https://developers.marketo.com/rest-api/lead-database/opportunities/`](https://developers.marketo.com/rest-api/lead-database/opportunities/)  
   `API documentation for syncing Opportunities:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST)`

1. Sync Salesforce Contact Roles to Marketo.

   Salesforce Contact Roles for a Salesforce Opportunity can be then synced via the Marketo Opportunity Role. The Opportunity Role record mandates the _externalOpportunityId_, _role_, and _leadId_ fields.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Opportunity Role Field</strong></td> 
   <td><strong>Salesforce Contact Role Field</strong></td> 
   <td><strong>Description</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Salesforce Opportunity case-insensitive globally unique identifier</td> 
   <td>Identifies the Marketo Opportunity Role to an external Salesforce Opportunity object.<br><br>It is mandated that the Salesforce Opportunity be correctly synced first.</td> 
  </tr> 
  <tr> 
   <td>leadId</td> 
   <td>N/A, this would be a Marketo Lead ID</td> 
   <td>This would be the Marketo Lead ID of the synced Salesforce Contact.<br><br>Once the contact is synced in Marketo, you can use the Salesforce Contact case-insensitive globally unique identifier as the externalPersonId and query for the Marketo Lead using the Marketo REST API.</td> 
  </tr> 
  <tr> 
   <td>role</td> 
   <td>The Role field for the Salesforce Contact</td> 
   <td>Describes the role of the contact for this opportunity.</td> 
  </tr> 
 </tbody> 
</table>

   API documentation for Opportunity: [`https://developers.marketo.com/rest-api/lead-database/opportunities/`](https://developers.marketo.com/rest-api/lead-database/opportunities/)  
   `API documentation for syncing Opportunities:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST)`

1. Sync Last Interesting Moment/MSI Scoring fields to SFDC.

   Once your Salesforce objects are correctly synced to Marketo, you can then take advantage of the MSI features. The MSI Last Interesting Moment/Scoring fields will be exposed in the REST API for Leads. These fields are calculated by MSI and are read-only.  
  
   The Last Interesting Moment/Scoring fields of a Marketo Lead will need to be regularly synced to Salesforce by using the REST API Lead endpoint. Query this endpoint for a Marketo Lead using the _externalPersonId_ as the filterType and passing in the Salesforce Lead GUID as the filterValue.

   | GET /rest/v1/leads.json?filterType=externalPersonId&filterValues=salesforceLeadId1,salesforceLeadId2  |
   |---|

   You can then use the values of these fields to sync to your Salesforce Lead/Contact object.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Lead Field</strong></td> 
   <td><strong>Salesforce Lead/Contact Field</strong></td> 
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

   Documentation for the Lead REST API: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET).

   Proper use of the external fields is key to a successful non-native sync. If you fail to see data in some of the views, it is likely that a certain field was not correctly synced. For example, if a lead’s activities and interesting moments don’t show up when looking in the MSI widget under their Account, it is likely that either the lead’s company or the Account was not correctly synced. Performing a GET request for this lead while specifying the external fields will help you verify whether the lead was correctly synced. Moreover, the email for the external sales person in Marketo must match the email for that user in Salesforce. Data may not show in the Marketo tab in Salesforce if the emails do not match.
