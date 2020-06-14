---
unique-page-id: 18874696
description: Recommended Salesforce Permissions for Bizible Connected User - Bizible - Product Documentation
title: Recommended Salesforce Permissions for Bizible Connected User
---

# Recommended Salesforce Permissions for Bizible Connected User {#recommended-salesforce-permissions-for-bizible-connected-user}

Recommended Salesforce Permissions for Bizible Connected User - Bizible - Product Documentation

Bizible sends and receives data through a connected Salesforce user within the Bizible app.  
  
In order to push touchpoint data to your Salesforce instance, the connected user must have access to Bizible custom objects (i.e. Bizible Touchpoint and Bizible Attribution Touchpoint) as well as standard Salesforce objects such as Leads and Contacts (see [Bizible in Salesforce](http://docs.marketo.com/x/MAEgAQ)).  
  
Salesforce Administrator user licenses can serve as the connected user as they often have the necessary data privileges by default. However, your team may prefer to use an integrations user or a dedicated Salesforce user license to track the impact of Bizible on your instance.  
  
We recommend the following permissions to ensure that Bizible data is accurately flowing:

* Bizible Administrator Permission Set For Dedicated User

The managed permission set gives an SFDC admin the ability to create, read, write, delete records from Bizible objects.

* View and Edit Converted Leads Permission Set

This allows Bizible to decorate leads after they have been converted to contacts.&nbsp; If this permission set is not enabled there can be significant data tracking gaps. You can find more information in [Salesforce Trailblazer community](http://help.salesforce.com/articleView?id=leads_view_edit_converted.htm&type=5).

* Salesforce Marketing User Checkbox

The Marketing User checkbox allows the user to create campaigns and use the Campaign Import Wizards. If this option isn’t selected, the user can only view campaigns and advanced campaign setup, edit the Campaign History for a single lead or contact, and run campaign reports. Bizible needs to ability to read and write to the campaign object.  
  
**Additional Troubleshooting** 
  
If Bizible is still experiencing issues reading or writing data it may be helpful to investigate the following:

* Access to Salesforce Queues

If the dedicated user does not have access to leads in queues then it is unable to modify the leads with Bizible data. You can accomplish this by having a role in the hierarchy that allows access to queues or individually granting users access.

* Field Level Security and Accessibility

Field level security and field accessibility are related but have some key differences. Field Level Security defines field visibility for a given profile while Field Accessibility determines whether a field is editable based on the field level security and page layout configuration. Using the Bizible package’s permission sets you will receive the necessary field object security settings. In some cases, in order to have the correct field accessibility, the connected user will need to have the Bizible fields on the page layouts. Bizible fields on the layout allow for the Bizible data to map into Salesforce. This will depend on your particular Salesforce environment.  
  
Every organization’s Salesforce has individual needs but we provide you with our requirements to balance Bizible’s access needs with your security protocols. Don’t hesitate to reach out to [ `[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#7c0f090c0c130e083c1e1506151e1019521f1311) with your questions or concerns.

