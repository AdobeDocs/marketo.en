---
unique-page-id: 4719304
description: Implied Salesforce Actions - Marketo Docs - Product Documentation
title: Implied Salesforce Actions
---

# Implied Salesforce Actions {#implied-salesforce-actions}

When a Salesforce-specific flow step runs, sometimes extra steps are performed automatically. Here are the rules, so you know:

These rules will apply _when the person is not currently in [Salesforce.com](http://Salesforce.com)_ as a contact or lead.

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

You can filter out SFDC records in a Smart List using the **SFDC Type** Filter with the operator set to "is not empty". All SFDC records have a value in this field.

Remember, these automatic actions only happen if the lead is not currently in [Salesforce.com](https://salesforce.com)
