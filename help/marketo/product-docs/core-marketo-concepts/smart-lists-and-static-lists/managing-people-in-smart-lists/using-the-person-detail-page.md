---
unique-page-id: 2953415
description: Using the Person Detail Page - Marketo Docs - Product Documentation
title: Using the Person Detail Page
exl-id: 8476ed02-6d94-4aa5-91f6-55c81a87f745
---
# Using the Person Detail Page {#using-the-person-detail-page}

The person detail page contains all the information Marketo knows about a person. You can edit data directly from this page.

## Getting to Person Detail Page {#getting-to-person-detail-page}

There are lots of ways to open specific people. Some examples are:

* From the **Database**, you can search in the Quick Find
* Any smart **list** or list
* **[!UICONTROL Members]** tab of a program
* **View Campaign Members** in a Smart Campaign
* Some **reports**
<br>&nbsp;

1. Either double-click on any person or single-click the ID on the left.

   ![](assets/one-1.png)

1. This will open the person detail screen.

   ![](assets/two-5.png)

## Page Organization - Salesforce {#page-organization-salesforce}

Person information is categorized into the following tabs:

| Tab |Description |
|---|---|
| Info |Contact information and custom fields about a person. |
| Company Info |Person's company information and address. |
| Opportunity Info |Opportunity information synced from Salesforce. |
| SFDC Lead Field |Built-in Salesforce fields. |
| SFDC Custom Field |Custom Salesforce fields. |
| Activity Log |All activities related to the person. |

## Page Organization - Microsoft Dynamics {#page-organization-microsoft-dynamics}

| Tab |Description |
|---|---|
| Info |Contact information and custom fields about a person. |
| Company Info |Person's company information and address. |
| Opportunity Info |Opportunity information synced from Microsoft. |
| Microsoft Custom Fields |Custom Microsoft fields. |
| Microsoft Lead Field |Built-in Microsoft fields. |
| Activity Log |All activities related to the person. |

>[!NOTE]
>
>You can also see Opportunity info [inserted via API](https://developers.marketo.com/rest-api/lead-database/opportunities/) for instances that are not synced with a CRM.

## Editing a Field {#editing-a-field}

Many fields are editable. To update a person's information, type in a new value and click outside the field to save.

![](assets/image2015-2-27-11-3a14-3a2.png)

## Marketo Default Fields Prior to CRM Sync {#marketo-default-fields-prior-to-crm-sync}

|   |  |  |  |  |
|---|---|---|---|---|
| Address |Annual Revenue |Anonymous IP |Billing Address |Billing City |
| Billing Country |Billing Postal Code |Billing State |City |Company Name |
| Country |Created At |Date of Birth |Department |Do Not Call |
| Do Not Call Cause |Do Not Call Reason |Email Address |Email Invalid |Email Invalid Cause |
| External Company Id |External Sales Person Id |Fax Number |First Name |Full Name |
| Industry |Inferred City |Inferred Company |Inferred Country |Inferred Metropolitan Area |
| Inferred Phone Area Code |Inferred Postal Code |Inferred State Region |Is Anonymous |Is Customer |
| Is Partner |Job Title |Last Name |Rating |Score |
| Person Source |Status |Main Phone |Marketo Social [!DNL Facebook] Display Name |Marketo Social [!DNL Facebook] Id |
| Marketo Social [!DNL Facebook] Photo URL |Marketo Social [!DNL Facebook] Profile URL |Marketo Social [!DNL Facebook] Reach |Marketo Social [!DNL Facebook] Referred Enrollments |Marketo Social [!DNL Facebook] Referred Visits |
| Marketo Social Gender |Marketo Social Last Referred Enrollment |Marketo Social Last Referred Visit |Marketo Social [!DNL LinkedIn] Display Name |Marketo Social [!DNL LinkedIn] Id |
| Marketo Social [!DNL LinkedIn] Photo URL |Marketo Social [!DNL LinkedIn] Profile URL |Marketo Social [!DNL LinkedIn] Reach |Marketo Social [!DNL LinkedIn] Referred Enrollments |Marketo Social [!DNL LinkedIn] Referred Visits |
| Marketo Social Syndication ID |Marketo Social Total Referred Enrollments |Marketo Social Total Referred Visits |Marketo Social [!DNL Twitter] Display Name |Marketo Social [!DNL Twitter] Id |
| Marketo Social [!DNL Twitter] Photo URL |Marketo Social [!DNL Twitter] Profile URL |Marketo Social [!DNL Twitter] Reach |Marketo Social [!DNL Twitter] Referred Enrollments |Marketo Social [!DNL Twitter] Referred Visits |
| Middle Name |Mobile Phone Number |Num Employees |Phone Number |Postal Code |
| Priority |Relative Score |Role |Salutation |SIC Code |
| Site |State |Unsubscribed |Unsubscribed Reason |Updated At |
| Urgency |Website |  |  |  |

>[!NOTE]
>
>Some fields are _not_ editable:
>
>* Activity Log
>* Company Information
>* Opportunities for SFDC Contacts
>* Certain Marketo-specific fields, such as Created Date and Original Source Type.
>
>Learn more about [System Managed Fields](/help/marketo/product-docs/administration/field-management/understanding-system-managed-fields.md).

>[!MORELIKETHIS]
>
>[Creating a Custom Tab for the Person Detail Page](/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md)
