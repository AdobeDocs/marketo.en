---
unique-page-id: 14352592
description: How to Insert Dynamic Fields - Marketo Docs - Product Documentation
title: How to Insert Dynamic Fields
---

# How to Insert Dynamic Fields {#how-to-insert-dynamic-fields}

How to Insert Dynamic Fields - Marketo Docs - Product Documentation

We allow you to personalize your email templates with predefined attributes like {{first_name}} or {{company}}. These fields allow you to email multiple contacts and auto-complete these fields without having to type them out separately for each contact.

### What's in this article? {#what-s-in-this-article}

[Insert a Dynamic Field into a Template](#howtoinsertdynamicfields-insertadynamicfieldintoatemplate)  
[Insert Dynamic Fields in a Subject Line](#howtoinsertdynamicfields-insertdynamicfieldsinasubjectline)

>[!TIP]
>
>The "first_name" and "company" field are the `only fields that will look to both Sales Connect and Salesforce.` That means if a contact does not exist in the [web application](http://toutapp.com/login), we look in Salesforce to see if we can find a contact/lead record with a matching email address. We then use information from that record to populate the field.

#### Insert a Dynamic Field into a Template {#howtoinsertdynamicfields-insertadynamicfieldintoatemplate}

##### 1. In Templates & Campaigns, find the template you want to edit and click Edit Template. {#howtoinsertdynamicfields-intemplates&campaigns-findthetemplateyouwanttoeditandclickedittemplate.}

##### 2. Click Tout Dynamic Fields. {#howtoinsertdynamicfields-clicktoutdynamicfields.}

>[!NOTE]
>
>When emailing contacts who exist in Sales Connect, you can use the basic dynamic fields. These will pull directly from the contact.

If you're emailing contacts who exist in Salesforce, you can take advantage of the Salesforce dynamic fields. These all begin with "sfdc". As long as you have a connection to Salesforce, these fields will call directly to the lead/contact in Salesforce to populate information in the template. 

#### Insert Dynamic Fields in a Subject Line {#howtoinsertdynamicfields-insertdynamicfieldsinasubjectline}

Simply manually copy and paste them into the subject field of an email, taking care to ensure you have the proper formatting.
