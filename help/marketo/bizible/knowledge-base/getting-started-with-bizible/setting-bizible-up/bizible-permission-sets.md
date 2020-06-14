---
unique-page-id: 18874789
description: Bizible Permission Sets - Bizible - Product Documentation
title: Bizible Permission Sets
---

# Bizible Permission Sets {#bizible-permission-sets}

Bizible Permission Sets - Bizible - Product Documentation

Learn how to access and assign Bizible Permission Sets in Salesforce.

### What's in this article? {#what-s-in-this-article}

[Bizible Permission Sets](#biziblepermissionsets-biziblepermissionsets)  
[Bizible Permission Sets Explained](#biziblepermissionsets-biziblepermissionsetsexplained)

#### Bizible Permission Sets {#biziblepermissionsets-biziblepermissionsets}

Three permission sets are included with the Bizible Salesforce package. These permission sets provide access to Bizible for Admins, Marketers and Standard Users.

To access and assign Permission Sets in Salesforce:

##### 1. Click Setup. {#biziblepermissionsets-clicksetup.}

##### 2. In the left margin, Click Users, then Permission Sets. {#biziblepermissionsets-intheleftmargin-clickusers-thenpermissionsets.}

##### 3. Select the Bizible Permission Set you'd like to assign. {#biziblepermissionsets-selectthebiziblepermissionsetyou'dliketoassign.}

##### 4. Click Manage Assignments, then Add Assignments. {#biziblepermissionsets-clickmanageassignments-thenaddassignments.}

##### 5. Select the users for the permission set and click Assign. {#biziblepermissionsets-selecttheusersforthepermissionsetandclickassign.}

![](assets/1-9.png)

#### Bizible Permission Sets Explained {#biziblepermissionsets-biziblepermissionsetsexplained}

<table class="confluenceTable"> 
 <tbody> 
  <tr> 
   <td><span class="wysiwyg-font-size-large"><strong>Bizible Administrator</strong></span></td> 
   <td><span class="wysiwyg-font-size-large">Gives an SFDC admin the ability to create, read, write, delete records from Bizible objects. The license under which Bizible pushes data to SFDC should have this permission set enabled. Additionally, it's recommended this license has the ability to edit converted Leads in the scenarios where the Lead is converted prior to Bizible applying data to the record. This will ensure accuracy in reporting between Salesforce and Bizible.<a href="http://releasenotes.docs.salesforce.com/en-us/spring17/release-notes/rn_sales_leads_view_converted.htm" class="external-link" rel="nofollow">Read more here</a>.</span></td> 
  </tr> 
  <tr> 
   <td><span class="wysiwyg-font-size-large"><strong>Bizible Marketing User</strong></span></td> 
   <td><span class="wysiwyg-font-size-large">Gives a marketing user the ability to read and write records from Bizible objects. All members of the marketing team should have the Bizible Marketing User permission set enabled. <br></span></td> 
  </tr> 
  <tr> 
   <td><span class="wysiwyg-font-size-large"><strong>Bizible Standard User</strong></span></td> 
   <td><span class="wysiwyg-font-size-large">Gives a user the ability to read records from Bizible objects.</span></td> 
  </tr> 
 </tbody> 
</table>

`  
`

Inbound sales development teams and account executives may benefit from Bizible’s data. If these roles would like to use Bizible data in reporting, enable the Bizible Standard User permission set.

>[!NOTE]
>
>In addition, the user we are connected through needs to have the "Marketing User" Salesforce Profile enabled at a user level in order for us to access the Campaign object. To check for this, click into**Setup** >**Manage Users**>**Profiles** >**Marketing User** > **Assigned Users**.

