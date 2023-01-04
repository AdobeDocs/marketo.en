---
unique-page-id: 14352592
description: How to Insert Dynamic Fields - Marketo Docs - Product Documentation
title: How to Insert Dynamic Fields
exl-id: e4989350-872d-47a1-84b0-210e631ae23a
---
# How to Insert Dynamic Fields {#how-to-insert-dynamic-fields}

We allow you to personalize your email templates with predefined attributes like `{{first_name}}` or `{{company}}`. These fields allow you to email multiple contacts and auto-complete these fields without having to type them out separately for each contact.

>[!TIP]
>
>The "first_name" and "company" field are the only fields that will look to both [!DNL Sales Connect] and [!DNL Salesforce]. That means if a contact does not exist in the [web application](https://toutapp.com/login), we look in [!DNL Salesforce] to see if we can find a contact/lead record with a matching email address. We then use information from that record to populate the field.

## Insert a Dynamic Field into a Template {#insert-a-dynamic-field-into-a-template}

1. In **[!UICONTROL Templates & Campaigns]**, find the template you want to edit and click **[!UICONTROL Edit Template]**.

1. Click **[!UICONTROL Tout Dynamic Fields]**.

   >[!NOTE]
   >
   >When emailing contacts who exist in [!DNL Sales Connect], you can use the basic dynamic fields. These will pull directly from the contact.

If you're emailing contacts who exist in [!DNL Salesforce], you can take advantage of the [!DNL Salesforce] dynamic fields. These all begin with "sfdc". As long as you have a connection to [!DNL Salesforce], these fields will call directly to the lead/contact in [!DNL Salesforce] to populate information in the template.

## Insert Dynamic Fields in a Subject Line {#insert-dynamic-fields-in-a-subject-line}

Simply manually copy and paste them into the subject field of an email, taking care to ensure you have the proper formatting.
