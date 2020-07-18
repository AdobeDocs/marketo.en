---
unique-page-id: 18874574
description: Bizible Fields on Standard Salesforce Objects - Bizible - Product Documentation
title: Bizible Fields on Standard Salesforce Objects
---

# Bizible Fields on Standard Salesforce Objects {#bizible-fields-on-standard-salesforce-objects}

Bizible Fields on Standard Salesforce Objects - Bizible - Product Documentation

Learn about the various Bizible fields that are added to Salesforce's standard objects.

### What's in this article? {#whats-in-this-article}

[Account](#account)  
[Case](#case)  
[Campaign](#campaign)  
[Campaign Member](#campaign-member)  
[Contact](#contact)  
[Lead](#lead)  
[Account](#account)  
[Opportunity](#opportunity)  
[Activity](#activity)

#### Account {#account}

Predictive Engagement Score: This field is used with our ABM feature to provide a score related to how engaged the Account is and takes into consideration many factors such as the recency of page views, how many contacts are associated to the account, is there a closed opp, etc.

#### Case {#case}

We add fields to the Case object related to the First touch and Lead Creation touch milestones. This is for customers that use the Case object in lieu of the Lead or Contact and also serves the purpose of another way to view the data in case a customer didn't want us to create Touchpoint records.

Touchpoint Source (FT): This is the source of the first touch interaction.

Touchpoint Source (LC): This is the source of the lead creation touch interaction.

Marketing Channel (FT): This is the marketing channel of the first touch interaction.

Marketing Channel (LC): This is the marketing channel of the lead creation touch interaction.

Ad Campaign Name (FT): This is the UTM Campaign, Ad Campaign from the Ad networks, or Salesforce Campaign of the first touch interaction.

Ad Campaign Name (LC): This is the UTM Campaign, Ad Campaign from the Ad networks, or Salesforce Campaign of the lead creation touch interaction.

Landing Page (FT): This is the landing page of the first touch interaction.

Landing Page (LC): This is the landing page of the lead creation touch interaction.

Touchpoint Date (FT): This is the date of the first touch interaction.

Touchpoint Date (LC): This is the date of the lead creation touch interaction.

#### Campaign {#campaign}

There are only 4 fields added, 1 button, and 1 validation rule.

UniqueID: This field is used internally for us to track the different Campaigns that are synced with Bizible.

Enable Bizible Touchpoints: This field is for the actual syncing of Campaigns for offline attribution inclusion and historical data.

Touchpoint Start Date: This field is used for setting a start date of applying touchpoints to historical campaigns.

Touchpoint End Date: This field is used for setting an end date for applying touchpoints to historical campaigns. A common example would the inclusion of digital campaigns pre-Bizible and then setting the end date as the day the script was applied.

Bulk Update Touchpoint Date (Button): This button is used to manage the touchpoint date of the Campaign members when the Campaign is synced as we will reference either the Campaign Membership date or the first response date out of the box. In the event that those date fields aren't an accurate representation of the actual touchpoint date, we would use this button to set the touchpoint date.

Update Bizible Attribution (Validation Rule): This rule is deprecated after package version 6.0.

#### Campaign Member {#campaign-member}

There are 5 fields and 1 Apex Trigger added with the package.

Touchpoint Status (Lead): This is a diagnostic field related to a feature that isn't turned on out of the box. We use this to understand whether a Touchpoint was created against the related Lead record or if not, why.

Touchpoint Status (Contact): This is a diagnostic field related to a feature that isn't turned on out of the box. We use this to understand whether a Touchpoint was created against the related Contact record or if not, why.

Touchpoint Status (Opportunity): This is a diagnostic field related to a feature that isn't turned on out of the box. We use this to understand whether a Touchpoint was created against the related Opportunity record or if not, why.

Touchpoint Status Date: This is the date the diagnostic fields were populated.

Bizible Touchpoint Date: This is related to the Bulk Update Touchpoint date button from the Campaign object. When that is used, we apply the defined Touchpoint date to the Campaign Member.

OnCampaignMemberDelete: Out of the box, Salesforce doesn't surface when Campaign Members are deleted which can cause issues with accurate attribution reporting. When a Campaign Member is deleted, this is triggered to inform Bizible to remove Touchpoints related to that non-existent Campaign Member.

#### Contact {#contact}

We add fields to the Contact object related to the First touch and Lead Creation touch milestones. This is for customers that would rather have attribution reported directly to fields instead of creating Touchpoint records. Most of our customers go with the Touchpoint record route, but also use these fields within their automation platform.

Touchpoint Source (FT): This is the source of the first touch interaction.

Touchpoint Source (LC): This is the source of the lead creation touch interaction.

Marketing Channel (FT): This is the marketing channel of the first touch interaction.

Marketing Channel (LC): This is the marketing channel of the lead creation touch interaction.

Ad Campaign Name (FT): This is the UTM Campaign, Ad Campaign from the Ad networks, or Salesforce Campaign of the first touch interaction.

Ad Campaign Name (LC): This is the UTM Campaign, Ad Campaign from the Ad networks, or Salesforce Campaign of the lead creation touch interaction.

Landing Page (FT): This is the landing page of the first touch interaction.

Landing Page (LC): This is the landing page of the lead creation touch interaction.

Touchpoint Date (FT): This is the date of the first touch interaction.

Touchpoint Date (LC): This is the date of the lead creation touch interaction.

BizibleID: This is used in relation to our activities attribution and calltrackingmetrics integration for Contact association to the touchpoint.

#### Lead {#lead}

We add fields to the Lead object related to the First touch and Lead Creation touch milestones. This is for customers that would rather have attribution reported directly to fields instead of creating Touchpoint records. Most of our customers go with the Touchpoint record route, but also use these fields within their automation platform.

Touchpoint Source (FT): This is the source of the first touch interaction.

Touchpoint Source (LC): This is the source of the lead creation touch interaction.

Marketing Channel (FT): This is the marketing channel of the first touch interaction.

Marketing Channel (LC): This is the marketing channel of the lead creation touch interaction.

Ad Campaign Name (FT): This is the UTM Campaign, Ad Campaign from the Ad networks, or Salesforce Campaign of the first touch interaction.

Ad Campaign Name (LC): This is the UTM Campaign, Ad Campaign from the Ad networks, or Salesforce Campaign of the lead creation touch interaction.

Landing Page (FT): This is the landing page of the first touch interaction.

Landing Page (LC): This is the landing page of the lead creation touch interaction.

Touchpoint Date (FT): This is the date of the first touch interaction.

Touchpoint Date (LC): This is the date of the lead creation touch interaction.

BizibleID: This is used in relation to our activities attribution and calltrackingmetrics integration for Lead association to the touchpoint.

#### Account {#account-1}

This is used for our Lead to Account mapping for our ABM feature. We populate this field to create the look-up relationship between the two objects.

#### Opportunity {#opportunity}

Bizible Opportunity Amount: This field is used in the scenario where a custom amount field is leveraged on the Opportunity. We map that custom field value to Bizible Opportunity Amount using a workflow and then read this field for our Revenue attribution fields on the Bizible Attribution Touchpoint object.

#### Activity {#activity}

BizibleID: This is for us to relate a touchpoint to activities for our activity attribution and calltracking metrics integration.

Bizible Touchpoint Date: This is a field that can be populated via a workflow to use as the date for activities attribution and will be populated for our calltrackingmetrics integration to know when the interaction occurred.
