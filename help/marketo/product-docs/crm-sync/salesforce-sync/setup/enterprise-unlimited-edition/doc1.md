---
description: Step 1 of 3 - Add Marketo Fields to Salesforce (Enterprise/Unlimited) - Marketo Docs - Product Documentation
title: Step 1 of 3 - Add Marketo Fields to Salesforce (Enterprise/Unlimited)
hide: yes
hidefromtoc: yes
feature: Salesforce Integration
---
# Step 1 of 3: Add Marketo Fields to Salesforce (Enterprise/Unlimited) {#step-of-add-marketo-fields-to-salesforce-enterprise-unlimited}

>[!PREREQUISITES]
>
>You must have access to Salesforce APIs to sync between Marketo Engage and Salesforce.

Marketo uses a set of fields to capture certain kinds of marketing related information. If you would like this data in Salesforce, please follow the instructions below.

1. Create three custom fields in Salesforce on the lead and contact objects: Score, Acquisition Program, and Acquisition Date.
1. Map these custom fields between leads and contacts so that on conversion in Salesforce, the values carry over.
1. You can create other additional fields, if necessary (see the table below).

All of these custom fields are optional and are not required to sync Marketo and Salesforce. As a best practice, we recommend that you do create fields for Score, Acquisition Program, and Acquisition Date.

## Add Marketo Fields to Salesforce {#add-marketo-fields-to-salesforce}

Add three custom fields on the lead and contact objects in Salesforce listed above. If you want to add more, see the table of available fields at the end of this section.

Perform the following steps for each of the three custom fields to add them. Start with Score.

1. Log in to Salesforce and click Setup.

   SCREENSHOT

1. In the Quick Find, search for the word "Object"

   SCREENSHOT

1. Click on Object Managers and search for "Leads"

   SCREENSHOT

1. Click on Lead under LABEL, and then click Fields and Relationships on the left.

   SCREENSHOT

1. Click on the button named New in the page "Fields & Relationships"

   SCREENSHOT

1. Choose the appropriate field type (for Score - number; Acquisition Program - text; Acquisition Date - Date/Time).

   SCREENSHOT

1. Click Next.

   SCREENSHOT

1. Enter the Field Label, Length, and Field Name for the field, as shown in the table below.

   TABLE

   >[!NOTE]
   >
   >Salesforce appends __c to Field Names when it uses them to create API Names.

   SCREENSHOT

   >[!NOTE]
   >
   >Text and number fields require a length, but Date/Time fields don't. A description is optional.

1. Click Next.

   SCREENSHOT

1. Specify the access settings and click Next:

   Set all roles to Visible and Read-Only

   Clear the Read-Only checkbox for the profile of your sync user:

   If you have a user with the profile of a System Administrator as the sync user, clear the Read-Only checkbox for the System Administrator profile (as shown below)
   If you created a custom profile for the sync user, clear the Read-Only checkbox for that custom profile

   SCREENSHOT

1. Choose the page layouts that should display the field.

   SCREENSHOT

1. Click Save & New to go back and create each of the other two custom fields. Click Save with you're done with all three.

   SCREENSHOT

* In the Object Manager, search "Contacts". Click Fields & Relationships.
* Perform steps 5 through 12 for the Score, Acquisition Date, and Acquisition Program fields on the contact object, just as you did for the lead object.
* Optionally, use the above procedure for any additional custom fields from this table.

   TABLE

   >[!NOTE]
   >
   >Values in the fields automatically assigned by Marketo will not immediately be available in Salesforce when the new field has been created. Marketo will sync the data to Salesforce upon the next update to the record on either system (i.e., an update to any of the fields in sync between Marketo and Salesforce).

## Map Custom Fields for Conversions {#map-custom-fields-for-conversions}

A custom field on the lead object in Salesforce should be mapped to a contact field on the contact object so that data is carried over when a conversion occurs.

1. In the top right corner, click Setup.

   SCREENSHOT

1. In the Quick Find, search for the word "Object"

   SCREENSHOT

1. Go to the Lead Custom Fields & Relationships section and click Map Lead Fields

   SCREENSHOT

1. Click the drop-down next to the field you want to map, under the corresponding tab- account, contact or opportunity .

   SCREENSHOT

1. Select the corresponding contact custom field.

   SCREENSHOT

1. Repeat the above steps for any other fields you've created.

1. Click Save when done.
