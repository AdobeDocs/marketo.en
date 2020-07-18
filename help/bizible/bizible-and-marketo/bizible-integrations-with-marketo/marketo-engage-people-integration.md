---
unique-page-id: 37356395
description: Marketo Engage People Integration - Bizible - Product Documentation
title: Marketo Engage People Integration
---

# Marketo Engage People Integration {#marketo-engage-people-integration}

Marketo Engage People Integration - Bizible - Product Documentation

The Marketo people integration allows Bizible to start downloading people from Marketo and begin to tie their tracked sessions to the individual and map touchpoints to their engagements. Historically, Bizible was only able to map touchpoints to a person from the CRM, so this helps marketers measure their marketing efforts sooner rather than waiting for a stage or trigger to sync it to the CRM.

### What's in this article? {#whats-in-this-article}

[Requirements](#requirements)  
[How It Works](#how-it-works)  
[Bizible Discover](#bizible-discover)  
[Field Mappings](#field-mappings)  
[FAQ](#faq)

#### Requirements {#requirements}

* Production Marketo instance
* Production Salesforce or Microsoft Dynamics instance
* Any paid Bizible subscription
* SOLR enabled (Please reach out to the Bizible Support Team to have this enabled)

#### How It Works {#how-it-works}

As a current customer, Bizible is already downloading people from your CRM. The standard process is that Bizible downloads the people and maps the email address to a web session that we’ve tracked via Bizible.js.

With the introduction of downloading Marketo people, Bizible is now able to map web sessions to a larger pool of individuals, those that have not been synced with the CRM. We commonly see this due to internal processes that wait until people reach a certain status before they are pushed to the CRM.

When Bizible successfully maps the Marketo person to a web session, our processing will generate any relevant touchpoints for it, which are ultimately reportable in Bizible Discover. If that Marketo person gets pushed to the CRM, Bizible will handle the duplicate scenario and we will recreate the touchpoint for the CRM person, and mark the initial set as “duplicate.”

In order for us to detect these duplicates, make sure your Marketo-Salesforce or Marketo-Dynamics sync is populating the Lead and Contact Ids on the Marketo Person. If the Id is syncing properly, you should be able to see the CRM Id on the Person record, like this:

![](assets/5a.png)

![](assets/5b.png)

Customers have the option of reporting the full set of Marketo people and CRM people inside of Bizible Discover. If you’re interested in reporting on CRM people only, we recommend creating a Segment to filter them.

#### Bizible Discover {#bizible-discover}

When reporting on leads (people) in Bizible Discover, you'll see the total of your Marketo and CRM leads. In order to report on only Marketo people or only CRM leads, you'll want to create a Segment Category for your source, then create Segment rules for Marketo and CRM using the "Source System" field to define the rule. Once your segments are created, you'll see the Source category available to filter across your Bizible Discover dashboards.

![](assets/bizible-discover-1.png)

![](assets/bizible-discover-2.png)

#### Field Mappings {#field-mappings}

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><p><strong>biz_leads</strong></p></th> 
   <th><p><strong>Marketo</strong></p></th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>id</p></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>updatedAt<strong>*</strong></p></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE</p></td> 
   <td><p>createdAt</p></td> 
  </tr> 
  <tr> 
   <td><p>EMAIL</p></td> 
   <td><p>email</p></td> 
  </tr> 
  <tr> 
   <td><p>WEB_SITE</p></td> 
   <td><p>website</p></td> 
  </tr> 
  <tr> 
   <td><p>COMPANY</p></td> 
   <td><p>company</p></td> 
  </tr> 
  <tr> 
   <td><p>IS_CONVERTED</p></td> 
   <td><p>n/a</p></td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNT_ID</p></td> 
   <td><p>Account Id (L2A)</p></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_STAGE</p></td> 
   <td><p>Status</p></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>true/false</p></td> 
  </tr> 
 </tbody> 
</table>

**&#42;**There is a known behavioral issue where fields from the Marketo Company entity do not impact the Person’s updatedAt value, so if relevant fields such as Website or Company are updated, Bizible will not know that those values are modified because the updatedAt date/time value is not updated. This impacts the ABM feature, where we wouldn’t have fresh data to resolve the Account for the lead. There is no workaround at the moment, but there are plans to address this in the future.

#### FAQ {#faq}

##### Why do my lead counts differ between my CRM and Bizible Discover? {#why-do-my-lead-counts-differ-between-my-crm-and-bizible-discover}

Because this integration allows us to create touchpoints for leads that we’ve imported directly from Marketo, there may be leads that didn’t get synced to the CRM so therefore the count within Discover could be higher than the CRM since touchpoints are only pushed for the CRM Leads.

##### How does this replace my data? {#how-does-this-replace-my-data}

This integration actually merges the data sets within your current Bizible instance so nothing is getting replaced. What we would expect from your current CRM Leads is that when we download the 2 years worth of Marketo Leads, we would simply update that Lead record to show that there was also a match to a Marketo Lead. That all happens in the backend and the touchpoints are expected to remain the same. We would also expect that we'd see more touchpoints because of the eligible Marketo Leads. If we're able to find web sessions matched to those Marketo people, we'll start seeing the touchpoints counted in Bizible.

##### Can I only have my people downloaded from Marketo and cut off the CRM connection? {#can-i-only-have-my-people-downloaded-from-marketo-and-cut-off-the-crm-connection}

At this time, no. We’ll have this option in the future, but we need to build out other phases of this Marketo integration so that we can connect the programs, opportunities and deals from Marketo to Bizible.

##### Do you import ALL of my Marketo people? {#do-you-import-all-of-my-marketo-people}

At the moment, the earliest we will import people is from 1/1/2018 so that we have a minimum of 2 years of data, which is the same behavior we enforce from CRM downloads. We will implement improved behavior to download a rolling 2 year window once the Marketo connection has been established.

We also don’t filter for any people types, so all people within the two-year window will get imported and are eligible for touchpoints.

##### What is SOLR and why do I need to have it enabled to use this feature? {#what-is-solr-and-why-do-i-need-to-have-it-enabled-to-use-this-feature}

Enabling SOLR for your Marketo instance is a trivial step that opens up hardware space in Marketo so that your subscription can utilize the Bizible integration. Without SOLR enabled, we don’t have access to certain calls that would otherwise allow us to download the appropriate people from your Marketo instance.

##### How long will it take to import all historical Marketo People? {#how-long-will-it-take-to-import-all-historical-marketo-people}

The time will vary depending on how many API credits are allocated to the Bizible integration. We recommend 20000 API calls out of the maximum of 50000 allocated to each Marketo instance. It also varies based on the number of Marketo People that we're importing. That said, we have seen it can range anywhere between 2-10 days.
