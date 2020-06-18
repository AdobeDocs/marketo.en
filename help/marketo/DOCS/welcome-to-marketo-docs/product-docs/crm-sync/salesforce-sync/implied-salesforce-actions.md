---
unique-page-id: 4719304
description: Implied Salesforce Actions - Marketo Docs - Product Documentation
title: Implied Salesforce Actions
---

# Implied Salesforce Actions {#implied-salesforce-actions}

Implied Salesforce Actions - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

When a Salesforce-specific flow step runs, sometimes extra steps are performed automatically. Here are the rules, so you know:&nbsp;

##### These rules will apply&nbsp;*when the person is not currently in [Salesforce.com](http://Salesforce.com)*&nbsp;as a contact or lead. {#impliedsalesforceactions-theseruleswillapplywhenthepersonisnotcurrentlyinsalesforce-comasacontactorlead}

<table> 
 <thead> 
  <tr> 
   <th>Marketo Flow step</th> 
   <th>Automatic Action</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>Add to SFDC Campaign</td> 
   <td>Sync Person to SFDC</td> 
  </tr> 
  <tr> 
   <td>Change Status in SFDC Campaign</td> 
   <td>Sync Person to SFDC<br>Add to SFDC Campaign</td> 
  </tr> 
  <tr> 
   <td>Change Owner</td> 
   <td><p>Sync Person to SFDC</p></td> 
  </tr> 
  <tr> 
   <td>Convert Person</td> 
   <td><p>Sync Person to SFDC</p></td> 
  </tr> 
  <tr> 
   <td>Create Task</td> 
   <td>Sync Person to SFDC</td> 
  </tr> 
 </tbody> 
</table>

You can filter out SFDC records in a Smart List using the&nbsp;**SFDC Type**&nbsp;Filter with the operator set to "is not empty". &nbsp;All SFDC records have a value in this field.

Remember, these automatic actions only happen if the lead is not currently in [Salesforce.com](http://Salesforce.com)

The Salesforce sync is cool, right?
