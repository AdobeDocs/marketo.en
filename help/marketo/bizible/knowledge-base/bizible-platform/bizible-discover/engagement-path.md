---
unique-page-id: 35586105
description: Engagement Path - Bizible - Product Documentation
title: Engagement Path
---

# Engagement Path {#engagement-path}

Engagement Path - Bizible - Product Documentation

Engagement Path allows you to see a complete view of lead, contact, account, and opportunity engagements from first touch all the way to close.

![](assets/one-2.png)

#### Tile Description {#engagementpath-tiledescription}

**Event Type:** The type of touchpoint (Session, CRM Campaign, CRM Event, CRM Task, Impression)

**Bizible Touchpoint Position:** Touchpoint Position of the lead/contact

**Bizible Attribution Touchpoint Position:** Bizible Attribution Touchpoint Position of the Opportunity

**Touchpoint Date:** For online sources: date & time the engagement occurred. For offline events: date & time set in the Salesforce Campaign. For activities touchpoint: touchpoint date field being referenced in the activities configuration

**Email:** The email associated to the engagement

**Marketing Touch Type:** Type of engagement(Web Visit, Web Form, Web Chat, CRM, Activity Types)

**Channel:** Marketing channel which drove the engagement

**Medium:** Medium of engagement

* If the engagement comes from an API connected platform (Adwords/BingAds) medium will be CPC
* If the engagement’s landing page contains utm_medium, we will parse
* If the engagement comes from CRM campaign, the medium comes from the ‘Type’ field from the CRM campaign

**Web Source:** This column will display the source of the engagement

* If the engagement comes from an API connected platform, web source will display the name of the ad platform
* If the touchpoint came from organic search, this field will display the name of the search engine
* If not #1 or #2, and the utm_source value is present in the landing page URL for the touchpoint, that value will be displayed here
* If not #1 or #2 and there is no utm_source value present, the root domain of the referring URL will be displayed here.
* If none of the above, this will display Web Direct or Web

**First Interaction with the Person:** This column will display Yes or No if that touchpoint was the individuals first interaction

**Attributed Revenue:** This column will display the revenue attributed to that touchpoint based on the selected attribution model selected

#### Filter Description {#engagementpath-filterdescription}

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Filter Name</th> 
   <th>Description</th> 
  </tr> 
  <tr> 
   <td><p>Account Name/ID</p></td> 
   <td><p>Allows for multiple values by adding filters through the plus sign "+" on the right. Multiple filter values will have "either or" relationship, meaning tile will show results for both filter values. If any of the filter values are not valid, the dashboard will not produce results for the invalid value, but will still filter to the valid filter values. Not case sensitive.</p></td> 
  </tr> 
  <tr> 
   <td><p>Opportunity Name/ID</p></td> 
   <td><p>Allows for multiple values by adding filters through the plus sign "+" on the right. Multiple filter values will have "either or" relationship, meaning tile will show results for both filter values. If any of the filter values are not valid, the dashboard will not produce results for the invalid value, but will still filter to the valid filter values. Not case sensitive.</p></td> 
  </tr> 
  <tr> 
   <td><p>Lead ID/Email</p></td> 
   <td><p>Allows for multiple values by adding filters through the plus sign "+" on the right. Multiple filter values will have "either or" relationship, meaning tile will show results for both filter values. If any of the filter values are not valid, the dashboard will not produce results for the invalid value, but will still filter to the valid filter values. Not case sensitive.</p></td> 
  </tr> 
  <tr> 
   <td><p>Contact ID/Email</p></td> 
   <td><p>Allows for multiple values by adding filters through the plus sign "+" on the right. Multiple filter values will have "either or" relationship, meaning tile will show results for both filter values. If any of the filter values are not valid, the dashboard will not produce results for the invalid value, but will still filter to the valid filter values. Not case sensitive.</p><p>Account Name/ID, Lead ID/Email, Contact ID/Email filter are "either or" relationship, meaning if both lead filter and contact filter has value, it will show all records for either of the IDs.</p></td> 
  </tr> 
  <tr> 
   <td><p>Attribution Model</p></td> 
   <td><p>Specify which model the attributed revenue should be calculated against. Allowed values: "Full Path Attribution", "First Touch Attribution", "Custom Model Attribution", "Lead Creation Attribution", "U Shaped Attribution", "W Shaped Attribution".</p></td> 
  </tr> 
  <tr> 
   <td><p>Event Type</p></td> 
   <td><p>Filter journey by type of event the user touchpoint is based on. Allows for multiple values by adding filters through the plus sign "+" on the right. Allowed values: "Session", "CRM Campaign", "CRM Event", "CRM Task", "Impression".</p></td> 
  </tr> 
  <tr> 
   <td><p>Lead Stages</p></td> 
   <td><p>Filter journey by lead stage the user touchpoint is based on. Allows for multiple values by adding filters through the plus sign "+" on the right. Filter default to "is equal to" will show suggestions to choose from, but recommend using "contains" as filter criteria for multiple filters on stages.</p></td> 
  </tr> 
  <tr> 
   <td><p>Opportunity Stages</p></td> 
   <td><p>Filter journey by opportunity stage the user touchpoint is based on. Allows for multiple values by adding filters through the plus sign "+" on the right. Filter default to "is equal to" will show suggestions to choose from, but recommend using "contains" as filter criteria for multiple filters on stages.</p></td> 
  </tr> 
  <tr> 
   <td><p>Touchpoint Date</p></td> 
   <td><p>Filter journey by touchpoint date/time.</p></td> 
  </tr> 
  <tr> 
   <td><p>User Touchpoint Email</p></td> 
   <td><p>Filter journey by email on user touchpoint. This allows for filtering emails that are not associated with a lead/contact/account.</p></td> 
  </tr> 
  <tr> 
   <td><p>Marketing Touch Type</p></td> 
   <td><p>Filter journey by marketing touch type.</p></td> 
  </tr> 
  <tr> 
   <td><p>Channel</p></td> 
   <td><p>Filter journey by channel.</p></td> 
  </tr> 
  <tr> 
   <td><p>Medium</p></td> 
   <td><p>Filter journey by medium.</p></td> 
  </tr> 
  <tr> 
   <td><p>Web Source</p></td> 
   <td><p>Filter journey by web source.</p></td> 
  </tr> 
  <tr> 
   <td><p>First Interaction with the Person</p></td> 
   <td><p>Filter journey by "Is First Touch" column on user touchpoints table.</p></td> 
  </tr> 
  <tr> 
   <td><p>Attributed Revenue</p></td> 
   <td><p>Filter journey by attributed revenue value.</p></td> 
  </tr> 
 </tbody> 
</table>

