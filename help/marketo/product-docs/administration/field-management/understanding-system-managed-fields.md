---
unique-page-id: 5472615
description: Understanding System Managed Fields - Marketo Docs - Product Documentation
title: Understanding System Managed Fields
exl-id: 4a58d41f-c2f5-4bcc-93ef-10a31e5475fd
feature: Field Management
---
# Understanding System Managed Fields {#understanding-system-managed-fields}

You might have noticed that the [person detail page](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) has a series of non-editable fields created by Marketo. This data comes from various sources, and there are countless values that could display.

## Field Types {#field-types}

| **Field Name** |**Definition** |
|---|---|
| Original Source Type |The location a person or website visitor was first discovered (Example: List Import, Web Page Visit) |
| Original Source Info |Specifics about that location (Example: Name of the list, URL of the web page) |
| Original Search Engine |If applicable, the search engine that referred the person to the original entry source |
| Original Search Phrase |If applicable, the search term used that referred the person to the original entry source |
| Original Referrer |URL that hosted the original entry source |
| Registration Source Type |The location an activity first became a person (Example: List Import, Web Page Visit) |
| Registration Source Info |Specifics about that location (Example: Name of the list, URL of the web page) |
| Anonymous IP |Indicates the IP address of a person |
| Inferred Company |Marketo's best guess (based on IP) of the person's company |
| Inferred City |Marketo's best guess (based on IP) of the person's city |
| Inferred State Region |Marketo's best guess (based on IP) of the person's state or region |
| Inferred Postal Code |Marketo's best guess (based on IP) of the person's postal code |
| Inferred Country |Marketo's best guess (based on IP) of the person's country |
| Inferred Metropolitan Area |Marketo's best guess (based on IP) of the person's metropolitan area |
| Inferred Phone Area Code |Marketo's best guess (based on IP) of the person's area code |

## Possible Values for Original and Registration Source Type {#possible-values-for-original-and-registration-source-type}

Below are some possible values and what they mean. 

| **Original Source Type** |**Definition** |
|---|---|
| Salesforce.com |Person was discovered from a Salesforce sync |
| Web Page Visits |Person was discovered from a web page |
| Web Form Fillout |Person was discovered after filling out a form |
| List Import |Person was discovered from a list import |
| New Person |Person was manually entered into the database |
| Web Link Click |Person was discovered after clicking on a link |
| Sales Email |Person was sent an email via Sales Insight Email Add-In |
| Person |Person was synced over from Salesforce as a person |
| Contact |Person was synced over from Salesforce as a contact |
| Munchkin API |Person was discovered by Marketo's Munchkin API |
| Social App |Person was discovered by a social widget |
| Web Service API |Person was discovered by a web service API |
| Event Partner |Person was discovered through a synced webinar service |
| Associate Lead |Person that was merged via Associate Lead API call |

| **Registration Source Type** |**Definition** |
|---|---|
| List Import |Became a person through a list import |
| Salesforce.com |Became a person through a Salesforce sync |
| Web Form Fillout |Became a person after filling out a form |
| Sales Email |Person was sent an email via Sales Insight Email Add-In |
| Web Service API |Person was created via SOAP/REST API |
| New Person |Person was manually entered into the database |
| Munchkin API |Became a person through Marketo's Munchkin API |
| Social App |Became a person through a social widget |
| Event Partner |Became a person through a linked webinar service |
