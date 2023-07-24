---
description: Syncing Call and Call Key Messages - Marketo Docs - Product Documentation
title: Syncing Call and Call Key Messages
exl-id: a8df5b77-e594-4e06-8194-1758a3582cda
feature: Veeva CRM
---
# Syncing Call and Call Key Messages {#syncing-call-and-call-key-messages}

Call and Call Key Message Objects in Veeva CRM are synced by default into Marketo Engage. Marketo syncs data that's up to 6 months old, based on Call Created Date.  

>[!NOTE]
>
>Marketo retains call data up to six months from the date of the Call.  

**What are the triggers/filters related to Call and Call Key Message?**

Triggers:

* Added to Call
* Removed from Call
* Added to Call Key Message
* Removed from Call Key Message
* Updated Call
* Updated Call Key Message

Filters:

* Has Call
* Has Call Key Message

The follow fields on Call and Call Key messages are synced and can be used as constraints and triggers.

<table>
  <colgroup>
    <col>
    <col>
    <col>
    <col>
    <col>
  </colgroup>
  <thead>
    <tr>
      <th>
        Object
      </th>
      <th>
        Field Label
      </th>
      <th>
        Description
      </th>
      <th>
        Field Name
      </th>
      <th>
        Data Type
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Call</td>
      <td>Accountant</td>
      <td>Lookup to the account that the call is associated with.</td>
      <td>Account_vod__c</td>
      <td>Lookup (Account)</td>
    </tr>
    <tr>
      <td>Call</td>
      <td>Call Type</td>
      <td>Type of call which is system maintained based on the type and contents of the call. This field is used for reporting purposes. Valid values are: Detail Only, Detail with Sample, Group Detail, Group Detail with Sample, Sample Only. These values should not be changed, but the translations for these picklists may be changed. Attendees have the same call type as the header call. For a Group call with 3 professionals, all 4 records have the call type of "Group Detail"</td>
      <td>Call_Type_vod__c</td>
      <td>Picklist</td>
    </tr>
    <tr>
     <td>Call</td>
      <td>Contact</td>
      <td>Lookup to the contact (if any) that the call is associated with.</td>
      <td>Contact_vod__c</td>
      <td>Lookup(Contact)</td>
    </tr>
    <tr>
      <td>Call</td>
      <td>Date</td>
      <td>The date of the call when it was first saved or submitted. This field is set via a trigger to the current date if neither the date or datetime field is supplied.</td>
      <td>Call_Date_vod__c</td>
      <td>Date</td>
    </tr>
    <tr>
      <td>Call</td>
      <td>Is Parent Call?</td>
      <td>Formula Field to determine if the Call record is the Parent Call or an Attendee Call record. 1 indicates that the record is the Parent Call. 0 indicates that it is an Attendee Call.</td>
      <td>Is_Parent_Call_vod__c</td>
      <td>Formula (Number)</td>
    </tr>
    <tr>
      <td>Call</td>
      <td>Status</td>
      <td>Status of the call -- Planned, Saved or Submitted. Use the translation workbench to change the display values. The triggers on call look at this field to see whether the call is locked (submitted). This value is set for the user when the Save or Submit button is pressed.</td>
      <td>Status_vod__c</td>
      <td>Picklist</td>
    </tr>
    <tr>
      <td>Call</td>
      <td>Record Type</td>
      <td>&nbsp;</td>
      <td>RecordTypeId</td>
      <td>Record Type</td>
    </tr>
    <tr>
      <td>Call Key Message</td>
      <td>Call</td>
      <td>Lookup to the call. Each key message is associated with a call.</td>
      <td>Call2_vod__c</td>
      <td>Master-Detail(Call)</td>
    </tr>
    <tr>
      <td>Call Key Message</td>
      <td>Category</td>
      <td>Records the message category of the message. Used primarily for reporting.</td>
      <td>Category_vod__c</td>
      <td>Picklist</td>
    </tr>
    <tr>
      <td>Call Key Message</td>
      <td>CLM Presentation Name</td>
      <td>Stamped CLM Presentation name</td>
      <td>Clm_Presentation_Name_vod__c</td>
      <td>Text (80)</td>
    </tr>
    <tr>
      <td>Call Key Message</td>
      <td>Key Message Name</td>
      <td>Stamped Key Message name</td>
      <td>Key_Message_Name_vod__c</td>
      <td>Text (80)</td>
    </tr>
    <tr>
      <td>Call Key Message</td>
      <td>Product Name</td>
      <td>&nbsp;</td>
      <td>Product_Name__c</td>
      <td>Formula (Text)</td>
    </tr>
    <tr>
      <td>Call Key Message</td>
      <td>Reaction</a>
      </td>
      <td>Picklist of reaction to the message. Edit the picklist to change the reaction values.</td>
      <td>Reaction_vod__c</td>
      <td>Picklist</td>
    </tr>
  </tbody>
</table>
