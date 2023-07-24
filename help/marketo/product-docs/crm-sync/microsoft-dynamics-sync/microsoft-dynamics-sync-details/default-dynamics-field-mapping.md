---
description: Default Dynamics Field Mapping - Marketo Docs - Product Documentation
title: Default Dynamics Field Mapping
exl-id: 5f39bd0c-202e-4aa1-a0ac-49ac2554aa1e
feature: Microsoft Dynamics
---
# Default Dynamics Field Mapping {#default-dynamics-field-mapping}

When you initially sync your Marketo account with Microsoft, Marketo automatically makes these associations between your built-in Dynamics and Marketo fields.  Marketo will also sync your custom fields on your Leads, Accounts, Opportunities, and Contacts.

## Lead Fields {#lead-fields}

<table>
  <colgroup>
    <col>
    <col>
    <col>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo Field</th>
      <th>MS Dynamics Field</th>
      <th>MS Dynamics API Name</th>
    </tr>
    <tr>
      <td>Microsoft Created Date</td>
      <td>Created On</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>Salutation</td>
      <td>Salutation</td>
      <td>salutation</td>
    </tr>
    <tr>
      <td>First</td>
      <td>First Name</td>
      <td>firstname</td>
    </tr>
    <tr>
      <td>Middle</td>
      <td>Middle Name</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>Last</td>
      <td>Last Name</td>
      <td>lastname</td>
    </tr>
    <tr>
      <td>Email</td>
      <td>Email</td>
      <td>emailaddress1</td>
    </tr>
    <tr>
      <td>Job Title</td>
      <td>Job title</td>
      <td>jobtitle</td>
    </tr>
    <tr>
      <td>Phone</td>
      <td>Business Phone</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>Mobile</td>
      <td>Mobile Phone</td>
      <td>mobilephone</td>
    </tr>
    <tr>
      <td>Fax</td>
      <td>Fax</td>
      <td>fax</td>
    </tr>
    <tr>
      <td>Address</td>
      <td>Street 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>City</td>
      <td>City</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>State</td>
      <td>State/Province</td>
      <td>address1_stateorprovince</td>
    </tr>
    <tr>
      <td>Country</td>
      <td>Country/Region</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>Postal Code</td>
      <td>Zip/Postal Code</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>Person Source</td>
      <td>Lead Source</td>
      <td>leadsourcecode</td>
    </tr>
    <tr>
      <td>Person Status</td>
      <td>Status</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>Status Reason</td>
      <td>Status Reason</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>Person Notes</td>
      <td>Description</td>
      <td>description</td>
    </tr>
    <tr>
      <td>Do Not Call</td>
      <td>Do Not Allow Phone Calls</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>Unsubscribed</td>
      <td>Do not bulk email</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>Person Rating</td>
      <td>Rating</td>
      <td>leadqualitycode</td>
    </tr>
    <tr>
      <td>Microsoft Address 2</td>
      <td>Street 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft Address 3</td>
      <td>Street 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Microsoft Do Not Email</td>
      <td>Do Not Allow Emails</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>Microsoft Do Not Fax</td>
      <td>Do Not Allow Faxes</td>
      <td>donotfax</td>
    </tr>
    <tr>
      <td>Microsoft Do Not Send Marketing Material</td>
      <td>Marketing Material</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>Microsoft Home Phone</td>
      <td>Home Phone</td>
      <td>telephone2</td>
    </tr>
    <tr>
      <td>Microsoft Preferred Method Of Contact</td>
      <td>Preferred Method of Contact</td>
      <td>preferredcontactmethodcode</td>
    </tr>
    <tr>
      <td>Microsoft Topic</td>
      <td>Topic</td>
      <td>subject</td>
    </tr>
    <tr>
      <td>Last interesting moment date</td>
      <td>Last interesting moment date</td>
      <td>mkt_lastinterestingmomentdate</td>
    </tr>
    <tr>
      <td>Last Interesting moment desc</td>
      <td>Last Interesting moment desc</td>
      <td>mkt_lastinterestingmomentdesc</td>
    </tr>
    <tr>
      <td>Last Interesting moment source</td>
      <td>Last Interesting moment source</td>
      <td>mkt_leadinterestingmomentsource</td>
    </tr>
    <tr>
      <td>Last interesting moment type</td>
      <td>Last interesting moment type</td>
      <td>mkt_lastinterestingmomenttype</td>
    </tr>
    <tr>
      <td>Company</td>
      <td>Company Name</td>
      <td>companyname</td>
    </tr>
    <tr>
      <td>Relative Score</td>
      <td>Relative Score</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>Priority</td>
      <td>Priority</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>Relative Urgency</td>
      <td>urgency</td>
      <td>mkt_urgency</td>
    </tr>
    <tr>
      <td>Subject</td>
      <td>Topic</td>
      <td>subject</td>
    </tr>
    <tr>
      <td>Annual Revenue</td>
      <td>Annual Revenue</td>
      <td>revenue</td>
    </tr>
  </tbody>
</table>

The Lead fields below are synced for internal use.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics Field</th>
      <th>MS Dynamics API Name</th>
    </tr>
    <tr>
      <td>Owner </td>
      <td>ownerid</td>
    </tr>
    <tr>
      <td>created On</td>
      <td>createdon</td>
    </tr>
  </tbody>
</table>

## Contact Fields {#contact-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo Field</th>
      <th>MS Dynamics Field</th>
      <th>MS Dynamics API Name</th>
    </tr>
    <tr>
      <td>Microsoft Created Date</td>
      <td>Created On</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>Salutation</td>
      <td>Salutation</td>
      <td>salutation</td>
    </tr>
    <tr>
      <td>First</td>
      <td>First Name</td>
      <td>firstname</td>
    </tr>
    <tr>
      <td>Middle</td>
      <td>Middle Name</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>Last</td>
      <td>Last Name</td>
      <td>lastname</td>
    </tr>
    <tr>
      <td>Email</td>
      <td>Email</td>
      <td>emailaddress1</td>
    </tr>
    <tr>
      <td>Job Title</td>
      <td>Job Title</td>
      <td>jobtitle</td>
    </tr>
    <tr>
      <td>Phone</td>
      <td>Business Phone</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>Mobile</td>
      <td>Mobile Phone</td>
      <td>mobilephone</td>
    </tr>
    <tr>
      <td>Address</td>
      <td>Address 1: Street 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>City</td>
      <td>Address 1: City</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>State</td>
      <td>Address 1: State/Province</td>
      <td>address1_stateorprovince</td>
    </tr>
    <tr>
      <td>Country</td>
      <td>Address 1: Country/Region</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>Postal Code</td>
      <td>Address 1: Zip/Postal Code</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>Person Status</td>
      <td>Status</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>Status Reason</td>
      <td>Status Reason</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>Do Not Call</td>
      <td>Do Not Allow Phone Calls</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>Unsubscribed</td>
      <td>Do not bulk email</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>Microsoft Address 2</td>
      <td>Address 1: Street 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft Address 3</td>
      <td>Address 1: Street 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Microsoft Do Not Email</td>
      <td>Do Not Allow Emails</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>Microsoft Home Phone</td>
      <td>Home Phone</td>
      <td>telephone2</td>
    </tr>
    <tr>
      <td>Microsoft Preferred Method Of Contact</td>
      <td>Preferred Method Of Contact</td>
      <td>preferredcontactmethodcode</td>
    </tr>
    <tr>
      <td>Last interesting moment date</td>
      <td>Last interesting moment date</td>
      <td>mkt_lastinterestingmomentdate</td>
    </tr>
    <tr>
      <td>Last interesting moment type</td>
      <td>Last interesting moment type</td>
      <td>mkt_lastinterestingmomenttype</td>
    </tr>
    <tr>
      <td>Last Interesting moment source</td>
      <td>Last Interesting moment source</td>
      <td>mkt_leadinterestingmomentsource</td>
    </tr>
    <tr>
      <td>Last Interesting moment desc</td>
      <td>Last Interesting moment desc</td>
      <td>mkt_lastinterestingmomentdesc</td>
    </tr>
    <tr>
      <td>Microsoft Do Not Send Marketing Material</td>
      <td>Marketing Material</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>Microsoft Do Not Fax</td>
      <td>Microsoft Do Not Fax</td>
      <td>donotfax</td>
    </tr>
    <tr>
      <td>Priority</td>
      <td>Priority</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>Relative Urgency</td>
      <td>urgency</td>
      <td>mkt_urgency</td>
    </tr>
    <tr>
      <td>Relative Score</td>
      <td>Relative Score</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>Person Notes</td>
      <td>Description</td>
      <td>description </td>
    </tr>
    <tr>
      <td>Person Score</td>
      <td>Lead Score</td>
      <td>mkt_leadscore</td>
    </tr>
    <tr>
      <td>Person Notes</td>
      <td>Description</td>
      <td>description </td>
    </tr>
  </tbody>
</table>

The Contact fields below are synced for internal use.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics Field</th>
      <th>MS Dynamics API Name</th>
    </tr>
    <tr>
      <td>Owner </td>
      <td>ownerid</td>
    </tr>
    <tr>
      <td>created On</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>parentcustomerid</td>
      <td>Company Name</td>
    </tr>
  </tbody>
</table>

## Account Fields {#account-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo Field</th>
      <th>MS Dynamics Field</th>
      <th>MS Dynamics API Name</th>
    </tr>
    <tr>
      <td>Account (a)</td>
      <td>Account</td>
      <td>accountid</td>
    </tr>
    <tr>
      <td>Billing Address</td>
      <td>Address 1: Street 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>Billing City</td>
      <td>Address 1: City</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>Billing Country</td>
      <td>Address 1: Country/Region</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>Billing Postal Code</td>
      <td>Address 1: Zip/Postal Code</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>Microsoft Billing Address 2</td>
      <td>Address 1: Street 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft Billing Address 3</td>
      <td>Address 1: Street 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Main Phone</td>
      <td>Main Phone</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>Business Type</td>
      <td>Business Type</td>
      <td>businesstypecode</td>
    </tr>
    <tr>
      <td>Microsoft Account Number</td>
      <td>Account Number</td>
      <td>accountnumber</td>
    </tr>
    <tr>
      <td>Microsoft Company Status</td>
      <td>Status</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>Annual Revenue</td>
      <td>Annual Revenue</td>
      <td>revenue</td>
    </tr>
    <tr>
      <td>Company Notes</td>
      <td>Description</td>
      <td>description</td>
    </tr>
    <tr>
      <td>Industry</td>
      <td>Industry</td>
      <td>industrycode</td>
    </tr>
    <tr>
      <td>SIC Code</td>
      <td>SIC Code</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>Website</td>
      <td>Website</td>
      <td>website</td>
    </tr>
    <tr>
      <td>Num Employees</td>
      <td>Number of Employees</td>
      <td>numberofemployees</td>
    </tr>
    <tr>
      <td>SIC Code</td>
      <td>SIC Code</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>Company</td>
      <td>name</td>
      <td>Account Name</td>
    </tr>
    <tr>
      <td>Num Employees</td>
      <td>Number of Employees</td>
      <td>numberofemployees</td>
    </tr>
  </tbody>
</table>

The Account fields below are synced for internal use.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics Field</th>
      <th>MS Dynamics API Name</th>
    </tr>
    <tr>
      <td>Owner </td>
      <td>ownerid</td>
    </tr>
    <tr>
      <td>created On</td>
      <td>createdon</td>
    </tr>
  </tbody>
</table>

## Opportunity Fields {#opportunity-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo Field</th>
      <th>MS Dynamics Field</th>
      <th>MS Dynamics API Name</th>
    </tr>
    <tr>
      <td>Close Probability</td>
      <td>Probabliity</td>
      <td>closeprobability</td>
    </tr>
    <tr>
      <td>Stage</td>
      <td>status</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>Actual Close Date</td>
      <td>Actual Close Date</td>
      <td>actualclosedate</td>
    </tr>
    <tr>
      <td>Name</td>
      <td>Topic</td>
      <td>name</td>
    </tr>
    <tr>
      <td>Estimated Value</td>
      <td>Est. Revenue</td>
      <td>estimatedValue</td>
    </tr>
    <tr>
      <td>Description</td>
      <td>Description</td>
      <td>description</td>
    </tr>
  </tbody>
</table>

The Account fields below are synced for internal use.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics Field</th>
      <th>MS Dynamics API Name</th>
    </tr>
    <tr>
      <td>Owner </td>
      <td>ownerid</td>
    </tr>
    <tr>
      <td>Opportunity</td>
      <td>opportunityId</td>
    </tr>
    <tr>
      <td>Potential Customer</td>
      <td>customerId</td>
    </tr>
  </tbody>
</table>

## Microsoft-Related System Fields in Marketo (Read-only) {#microsoft-related-system-fields}

The fields below are created in Marketo but cannot be adjusted by users.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo Field</th>
      <th>Description</th>
    </tr>
    <tr>
      <td>Microsoft Type</td>
      <td>Lead or Contact. If empty, the lead exists only as a person in Marketo</td>
    </tr>
    <tr>
      <td>Microsoft Created Date</td>
      <td>Date created in MS Dynamics (can be different from Created in Marketo)</td>
    </tr>
    <tr>
      <td>Microsoft is Deleted</td>
      <td>Person used to be in Microsoft but was deleted and now lives only in Marketo</td>
    </tr>
  </tbody>
</table>
