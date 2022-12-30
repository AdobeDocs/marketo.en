---
description: "Default [!DNL Veeva] Field Mapping - Marketo Docs - Product Documentation"
title: "Default [!DNL Veeva] Field Mapping"
exl-id: 3bf36d50-daea-431f-9537-b3007ad75945
---
# Default [!DNL Veeva] Field Mapping {#default-veeva-field-mapping}

When you initially sync your Marketo Engage account with [!DNL Veeva], Marketo automatically makes these associations between your built-in [!DNL Veeva] and Marketo fields. Marketo will also sync your custom fields on your Accounts and Contacts.

## Contact Fields {#contact-fields}

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>SFDC field</th>
      <th>Marketo field</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Birthdate</td>
      <td>Date of Birth</td>
    </tr>
    <tr>
      <td>Created Date</td>
      <td>SFDC Created Date</td>
    </tr>
    <tr>
      <td>Contact Description</td>
      <td>Person Notes</td>
    </tr>
    <tr>
      <td>Email</td>
      <td>Email Address</td>
    </tr>
    <tr>
      <td>Business Fax</td>
      <td>Fax Number</td>
    </tr>
    <tr>
      <td>First Name</td>
      <td>First Name</td>
    </tr>
    <tr>
      <td>Email Opt Out</td>
      <td>Unsubscribed</td>
    </tr>
    <tr>
      <td>Deleted</td>
      <td>SFDC Is Deleted</td>
    </tr>
    <tr>
      <td>Last Name</td>
      <td>Last Name</td>
    </tr>
    <tr>
      <td>Lead Source</td>
      <td>Source</td>
    </tr>
    <tr>
      <td>Lead Score</td>
      <td>Score</td>
    </tr>
    <tr>
      <td>MailingCity</td>
      <td>City</td>
    </tr>
    <tr>
      <td>MailingCountry</td>
      <td>Country</td>
    </tr>
    <tr>
      <td>MailingPostalCode</td>
      <td>Postal Code</td>
    </tr>
    <tr>
      <td>MailingState</td>
      <td>State</td>
    </tr>
    <tr>
      <td>MailingStreet</td>
      <td>Address</td>
    </tr>
    <tr>
      <td>Mobile Phone</td>
      <td>Mobile Phone Number</td>
    </tr>
    <tr>
      <td>Business Phone</td>
      <td>Phone Number</td>
    </tr>
    <tr>
      <td>Salutation</td>
      <td>Salutation</td>
    </tr>
    <tr>
      <td>Title</td>
      <td>Job Title</td>
    </tr>
  </tbody>
</table>

## Account Fields {#account-fields}

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>SFDC field</th>
      <th>Marketo field</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Annual Revenue</td>
      <td>Annual Revenue</td>
    </tr>
    <tr>
      <td>Billing City</td>
      <td>Billing City</td>
    </tr>
    <tr>
      <td>Billing Country</td>
      <td>Billing Country</td>
    </tr>
    <tr>
      <td>Billing Zip/Postal Code</td>
      <td>Billing Postal Code</td>
    </tr>
    <tr>
      <td>Billing State/Province</td>
      <td>Billing State</td>
    </tr>
    <tr>
      <td>Billing Street</td>
      <td>Billing Address</td>
    </tr>
    <tr>
      <td>Account Description</td>
      <td>Company Notes</td>
    </tr>
    <tr>
      <td>Industry</td>
      <td>Industry</td>
    </tr>
    <tr>
      <td>Deleted</td>
      <td>SFDC Is Deleted</td>
    </tr>
    <tr>
      <td>Account Name</td>
      <td>Company Name</td>
    </tr>
    <tr>
      <td>Employees</td>
      <td>Num Employees</td>
    </tr>
    <tr>
      <td>Account Phone</td>
      <td>Main Phone</td>
    </tr>
    <tr>
      <td>SIC Code</td>
      <td>SIC Code</td>
    </tr>
    <tr>
      <td>Account Site</td>
      <td>Site</td>
    </tr>
    <tr>
      <td>Account Type</td>
      <td>SFDC Type</td>
    </tr>
    <tr>
      <td>Website</td>
      <td>Website</td>
    </tr>
  </tbody>
</table>

## [!DNL Veeva]-Related System Fields in Marketo (Read-only) {#veeva-related-system-fields-in-marketo}

These fields are created in Marketo but can’t be adjusted by customers.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>Field</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>[!DNL Veeva] Id</td>
      <td>The 18-character [!DNL Salesforce] Id</td>
    </tr>
    <tr>
      <td>[!DNL Veeva] Type</td>
      <td>Contact. If empty, the lead exists only as a person in Marketo</td>
    </tr>
    <tr>
      <td>[!DNL Veeva] Created Date</td>
      <td>Date created in SFDC (can be different from Created in Marketo)</td>
    </tr>
    <tr>
      <td>[!DNL Veeva] is Deleted</td>
      <td>Person used to be in SFDC but was deleted and now lives only in Marketo</td>
    </tr>
  </tbody>
</table>
