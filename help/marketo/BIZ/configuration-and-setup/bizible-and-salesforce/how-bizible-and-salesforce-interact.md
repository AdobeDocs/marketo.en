---
unique-page-id: 18874672
description: How Bizible and Salesforce Interact - Bizible - Product Documentation
title: How Bizible and Salesforce Interact
---

# How Bizible and Salesforce Interact {#how-bizible-and-salesforce-interact}

How Bizible and Salesforce Interact - Bizible - Product Documentation

Let's take a high-level look at the relationship between Bizible and Salesforce.

### What's in this article? {#whats-in-this-article}

[Salesforce and Bizible](#salesforce-and-bizible)  
[Salesforce Standard Objects and Access](#salesforce-standard-objects-and-access)  
[Bizible Custom Objects in Salesforce](#bizible-custom-objects-in-salesforce)  
[Bizible Attribution Touchpoint](#bizible-attribution-touchpoint)

#### Salesforce and Bizible&nbsp; {#salesforce-and-bizible}

Once the Bizible account is created and Salesforce is connected, Bizible will begin pushing marketing data&nbsp;into the CRM instance as long as the Bizible managed package is installed. If it's not, Bizible will not write any data, but it will read information from your SFDC instance.

![](assets/1-3.png)

#### Salesforce Standard Objects and Access {#salesforce-standard-objects-and-access}

This lists the Salesforce Standard Objects that Bizible interacts with, as well as the custom fields that we add to these objects once the connection is established and the Bizible package is installed. Out of the box, Bizible will NOT write into any standard Salesforce Object fields.

##### Lead {#lead}

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>Id</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>Email</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>Status</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CreatedDate</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LastModifiedDate</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ConvertedDate</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ConvertedContactId</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ConvertedOpportunityId</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IsConverted</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IsDeleted</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>Website</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>Company</p></td> 
   <td colspan="1"><p>Standard</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"> </td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Account__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Campaign_Name_FT__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Campaign_Name_LC__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Landing_Page_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Landing_Page_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Marketing_Channel_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Marketing_Channel_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Date_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Date_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Source_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Source_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x&nbsp;</p></td> 
  </tr> 
 </tbody> 
</table>

##### Contact {#contact}

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>Account</p></td> 
   <td><p>Standard</p></td> 
   <td><span>x</span></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>Id</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Email</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Created Date</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsDeleted</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>LastModifiedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Ad_Campaign_Name_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Ad_Campaign_Name_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Landing_Page_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Landing_Page_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Marketing_Channel_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Marketing_Channel_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Date_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Date_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Source_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Source_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x&nbsp;</p></td> 
  </tr> 
 </tbody> 
</table>

##### Case {#case}

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>Id</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>CreatedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>LastModifiedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>SuppliedEmail</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsDeleted</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Ad_Campaign_Name_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Ad_Campaign_Name_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Landing_Page_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Landing_Page_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Marketing_Channel_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Marketing_Channel_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Date_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Date_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Source_FT__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Source_LC__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x&nbsp;</p></td> 
  </tr> 
 </tbody> 
</table>

##### Account {#account}

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>Id</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Website</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>LastModifiedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsDeleted</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Engagement_Score__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x&nbsp;</p></td> 
  </tr> 
 </tbody> 
</table>

##### Opportunity {#opportunity}

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>Account</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>Id</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>CreatedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>LastModifiedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsWon</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsClosed</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsDeleted</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>CloseDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>StageName</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Amount</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Bizible_Opportunity_Amount__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x&nbsp;</p></td> 
  </tr> 
 </tbody> 
</table>

##### Campaign {#campaign}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>Id</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Email</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Status</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>CreatedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>LastModifiedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>ConvertedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>ConvertedContactId</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>ConvertedOpportunityId</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsConverted</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsDeleted</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Website</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Company</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>Type</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

##### Campaign Member {#campaign-member}

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>Id</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>CreatedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>LastModifiedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsDeleted</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>FirstRespondedDate</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>HasResponded</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>ContactId</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>LeadId</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>IsConverted</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>CampaignId</p></td> 
   <td><p>Standard</p></td> 
   <td><p>x</p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Bizible_Touchpoint_Date__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Status_Date__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Status_Contact__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Status_Leade__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Status_Opportunity__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x&nbsp;</p></td> 
  </tr> 
 </tbody> 
</table>

#### Bizible Custom Objects in Salesforce&nbsp; {#bizible-custom-objects-in-salesforce}

Apart from creating custom fields on SFDC's Standard Objects, once the Bizible package is installed,&nbsp;it will create a couple of Custom Objects. Below is a list of these Custom Objects along with a table denoting the fields that Bizible will&nbsp;write to.

##### Bizible Touchpoint {#bizible-touchpoint}

The Bizible Touchpoint is a Bizible Custom Object to encapsulate the marketing interactions for Contacts, Leads, and Cases. 

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>bizible2__Bizible_Person__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__SF_Campaign__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__UniqueId__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Marketing_Channel__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Marketing_Channel_Path__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Touchpoint_Type__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Content__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Group_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Group_Name__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Campaign_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Campaign_Name__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Placement_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Placement_Name__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Site_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Site_Name__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Form_URL__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Form_URL_Raw__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Platform__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Browser__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Geo_City__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Geo_Country__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Geo_Region__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Keyword_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Keyword_MatchType__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Touchpoint_Position__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Keyword_Text__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Landing_Page__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Landing_Page_Raw__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Medium__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Referrer_Page__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Referrer_Page_Raw__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Search_Phrase__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Date__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Source__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Segment__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Count_First_Touch__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Count_Lead_Creation_Touch__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Count_U_Shaped__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Ad_Destination_URL__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Case__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Contact__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
 </tbody> 
</table>

##### Bizible Person {#bizible-person}

The Bizible Person is a Bizible Custom Object that is related to both the Lead, Contact, and Case Objects.

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>bizible2__UniqueId__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Lead__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Case__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Contact__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x&nbsp;</p></td> 
  </tr> 
 </tbody> 
</table>

#### Bizible Attribution Touchpoint {#bizible-attribution-touchpoint}

The Bizible Attribution Touchpoint is a Bizible Custom Object to encapsulate marketing's influence on Opportunities.&nbsp;

##### Bizible Attribution Touchpoint {#bizible-attribution-touchpoint-1}

<table> 
 <tbody> 
  <tr> 
   <th><p>Fields</p></th> 
   <th><p>Standard/Custom</p></th> 
   <th><p>Read</p></th> 
   <th><p>Write</p></th> 
  </tr> 
  <tr> 
   <td><p>bizible2__Account__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__SF_Campaign__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Contact__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Opportunity__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__UniqueId__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Marketing_Channel__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Marketing_Channel_Path__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Touchpoint_Type__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Content__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Group_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Group_Name__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Campaign_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Campaign_Name__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Placement_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Placement_Name__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Site_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Site_Name__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Form_URL__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Form_URL_Raw__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Platform__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Browser__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Geo_City__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Geo_Country__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Geo_Region__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Keyword_Id__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Keyword_MatchType__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Touchpoint_Position__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Keyword_Text__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Landing_Page__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Landing_Page_Raw__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Medium__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Referrer_Page__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Referrer_Page_Raw__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Search_Phrase__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Date__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Touchpoint_Source__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Segment__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Attribution_First_Touch__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Attribution_Lead_Conversion_Touch__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Attribution_U_Shaped__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Attribution_W_Shaped__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Attribution_Custom_Model__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Attribution_Custom_Model_2__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Count_First_Touch__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Count_Lead_Creation_Touch__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Count_U_Shaped__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td><p>bizible2__Count_W_Shaped__c</p></td> 
   <td><p>Custom</p></td> 
   <td><p>x</p></td> 
   <td><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Count_Custom_Model__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Count_Custom_Model_2__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Ad_Destination_URL__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Revenue_First_Touch__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Revenue_Lead_Creation_Touch__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Revenue_U_Shaped__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Revenue_W_Shaped__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Revenue_Custom_Model__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>bizible2__Revenue_Custom_Model_2__c</p></td> 
   <td colspan="1"><p>Custom</p></td> 
   <td colspan="1"><p>x</p></td> 
   <td colspan="1"><p>x</p></td> 
  </tr> 
 </tbody> 
</table>

**`  
`**

