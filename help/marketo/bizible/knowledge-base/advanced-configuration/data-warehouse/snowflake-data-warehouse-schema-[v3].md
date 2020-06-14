---
unique-page-id: 35586140
description: Snowflake Data Warehouse Schema [V3] - Bizible - Product Documentation
title: Snowflake Data Warehouse Schema [V3]
---

# Snowflake Data Warehouse Schema [V3] {#snowflake-data-warehouse-schema-v}

Snowflake Data Warehouse Schema [V3] - Bizible - Product Documentation

Data Warehouse allows you to track as much as you want, report on your attribution data wherever you want, and plug it in to other data sets.

### What's in this article? {#what-s-in-this-article}

[BIZ_ACCOUNTS](#snowflakedatawarehouseschema[v3]-biz-accounts)  
[BIZ_ACCOUNT_TO_EMAILS](#snowflakedatawarehouseschema[v3]-biz-account-to-emails)  
[BIZ_ADS](#snowflakedatawarehouseschema[v3]-biz-ads)  
[BIZ_ADVERTISERS](#snowflakedatawarehouseschema[v3]-biz-advertisers)  
[BIZ_AD_ACCOUNTS](#snowflakedatawarehouseschema[v3]-biz-ad-accounts)  
[BIZ_AD_CAMPAIGNS](#snowflakedatawarehouseschema[v3]-biz-ad-campaigns)  
[BIZ_AD_GROUPS](#snowflakedatawarehouseschema[v3]-biz-ad-groups)  
[BIZ_AD_PROVIDERS](#snowflakedatawarehouseschema[v3]-biz-ad-providers)  
[BIZ_ATTRIBUTION_TOUCHPOINTS](#snowflakedatawarehouseschema[v3]-biz-attribution-touchpoints)  
[BIZ_CAMPAIGN_MEMBERS](#snowflakedatawarehouseschema[v3]-biz-campaign-members)  
[BIZ_CHANNELS](#snowflakedatawarehouseschema[v3]-biz-channels)  
[BIZ_CONVERSION_RATES](#snowflakedatawarehouseschema[v3]-biz-conversion-rates)  
[BIZ_CONTACTS](#snowflakedatawarehouseschema[v3]-biz-contacts)  
[BIZ_COSTS](#snowflakedatawarehouseschema[v3]-biz-costs)  
[BIZ_CREATIVES](#snowflakedatawarehouseschema[v3]-biz-creatives)  
[BIZ_CRM_EVENTS](#snowflakedatawarehouseschema[v3]-biz-crm-events)  
[BIZ_CRM_TASKS](#snowflakedatawarehouseschema[v3]-biz-crm-tasks)  
[BIZ_CURRENCIES](#snowflakedatawarehouseschema[v3]-biz-currencies)  
[BIZ_CUSTOMER_AB_TESTS](#snowflakedatawarehouseschema[v3]-biz-customer-ab-tests)  
[BIZ_CUSTOMER_EVENTS](#snowflakedatawarehouseschema[v3]-biz-customer-events)  
[BIZ_CUSTOM_LANDING_PAGES](#snowflakedatawarehouseschema[v3]-biz-custom-landing-pages)  
[BIZ_DISCOVERED_FORM](#snowflakedatawarehouseschema[v3]-biz-discovered-form)  
[BIZ_DISCOVERED_PAGE](#snowflakedatawarehouseschema[v3]-biz-discovered-page)  
[BIZ_EMAIL_TO_VISITOR_IDS](#snowflakedatawarehouseschema[v3]-biz-email-to-visitor-ids)  
[BIZ_FACTS](#snowflakedatawarehouseschema[v3]-biz-facts)  
[BIZ_FORM_SUBMITS](#snowflakedatawarehouseschema[v3]-biz-form-submits)  
[BIZ_IMPRESSIONS](#snowflakedatawarehouseschema[v3]-biz-impressions)  
[BIZ_KEYWORDS](#snowflakedatawarehouseschema[v3]-biz-keywords)  
[BIZ_LANDING_PAGES](#snowflakedatawarehouseschema[v3]-biz-landing-pages)  
[BIZ_LEADS](#snowflakedatawarehouseschema[v3]-biz-leads)  
[BIZ_LEAD_STAGE_TRANSITIONS](#snowflakedatawarehouseschema[v3]-biz-lead-stage-transitions)  
[BIZ_OPPORTUNITIES](#snowflakedatawarehouseschema[v3]-biz-opportunities)  
[BIZ_OPP_STAGE_TRANSITIONS](#snowflakedatawarehouseschema[v3]-biz-opp-stage-transitions)  
[BIZ_PAGE_VIEWS](#snowflakedatawarehouseschema[v3]-biz-page-views)  
[BIZ_PLACEMENTS](#snowflakedatawarehouseschema[v3]-biz-placements)  
[BIZ_SEGMENTS](#snowflakedatawarehouseschema[v3]-biz-segments)  
[BIZ_SESSIONS](#snowflakedatawarehouseschema[v3]-biz-sessions)  
[BIZ_SITES](#snowflakedatawarehouseschema[v3]-biz-sites)  
[BIZ_SITE_LINKS](#snowflakedatawarehouseschema[v3]-biz-site-links)  
[BIZ_STAGE_DEFINITIONS](#snowflakedatawarehouseschema[v3]-biz-stage-definitions)  
[BIZ_TOUCHPOINTS](#snowflakedatawarehouseschema[v3]-biz-touchpoints)  
[BIZ_URLS](#snowflakedatawarehouseschema[v3]-biz-urls)  
[BIZ_USER_TOUCHPOINTS](#snowflakedatawarehouseschema[v3]-biz-user-touchpoints)  
[Sample Queries](#snowflakedatawarehouseschema[v3]-samplequeries)

#### BIZ_ACCOUNTS {#snowflakedatawarehouseschema[v3]-biz-accounts}

All CRM Accounts that are imported, along with custom Bizible fields.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p></td> 
   <td><p>varchar</p></td> 
   <td><p> CRM AccountId</p></td> 
   <td><p>0013100001kpAZxAAM</p></td> 
   <td>X</td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE &nbsp;</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The created date of the Account from the CRM</p></td> 
   <td><p>2016-08-28 00:32:55.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the Account from the CRM</p></td> 
   <td><p>2018-08-01 17:38:30.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Account Name, as recorded in the CRM</p></td> 
   <td><p>bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>WEB_SITE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Website that is entered for the Account, used for Lead2Account mapping</p></td> 
   <td><p>www.bizible.com</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENGAGEMENT_RATING</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A letter grade (A, B, C, D, N/A) that is generated from Bizible’s Machine Learning model. This will be null if ABM is disabled.</p></td> 
   <td><p>B</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENGAGEMENT_SCORE</p></td> 
   <td><p>number(38,19)</p></td> 
   <td><p>A numerical score calculated by Bizible’s Machine Learning to generate the Predictive Engagement Score (Engagement_Rating). This will be null if ABM is disabled.</p></td> 
   <td><p>0.1417350147058800000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>DOMAIN</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The parsed down version of the website, only storing the domain.</p></td> 
   <td><p>bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the record is deleted in the CRM.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CUSTOM_PROPERTIES</td> 
   <td>varchar</td> 
   <td>Custom CRM properties that Bizible has imported from the CRM in JSON format</td> 
   <td> 
    <div class="content-wrapper"> 
     <pre>{"Account_Type__c": "Security", "Foo":"Bar"}</pre> 
    </div></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_ACCOUNT_TO_EMAILS {#snowflakedatawarehouseschema[v3]-biz-account-to-emails}

Lead and Contact email addresses that are mapped and known under CRM Accounts. This table will be empty if ABM is disabled.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ACCOUNT_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>CRM AccountId</p></td> 
   <td><p>0013100001phrBAAAY</p></td> 
   <td>X</td> 
   <td><p>BIZ_ACCOUNTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Any email address that has been mapped to the Account, whether through Contact relationships or from Lead2Account mapping</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the Account from the CRM</p></td> 
   <td><p>2018-08-31 23:53:39.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE &nbsp;</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The created date of the Account from the CRM</p></td> 
   <td><p>2018-08-18 22:01:32.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the record is considered deleted</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_ADS {#snowflakedatawarehouseschema[v3]-biz-ads}

Table that stores all ads downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique identifier for the ad</p></td> 
   <td><p>fb.106851586409075.6052044288804.6052044290004.6053457066804</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>DISPLAY_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ad id?</p></td> 
   <td><p>6053457066804</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the connected ads account for the ad</p></td> 
   <td><p>fb.106851586409075</p></td> 
   <td><br></td> 
   <td>BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_ACCOUNT_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the connected ads account for the ad</p></td> 
   <td><p>Bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the advertiser for the ad, specifically for Doubleclick.</p></td> 
   <td><p>300181641</p></td> 
   <td><br></td> 
   <td>BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the advertiser for the ad, specifically for Doubleclick.</p></td> 
   <td><p>Bizible Marketing Analytics</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the ad group for the ad</p></td> 
   <td><p>fb.106851586409075.6052044288804.6052044290004</p></td> 
   <td><br></td> 
   <td>BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ad group for the ad</p></td> 
   <td><p>US - 18+</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the campaign for the ad</p></td> 
   <td><p>fb.106851586409075.6052044288804</p></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the campaign for the ad</p></td> 
   <td><p>Lead generation Campaign</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_ACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the ad is still active in the ads account</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the ad has been deleted in the ads account</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><p>2018-08-02 06:35:59.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the ad was first downloaded by Bizible</p></td> 
   <td><p>2018-08-02 06:35:59.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ad</p></td> 
   <td><p>Ad 2</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the ad needs to get updated to get Bizible tagging</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>fb.106851586409075.6052044288804.6052044290004</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “Ad”</p></td> 
   <td><p>Ad</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads provider for the ad</p></td> 
   <td><p>Facebook</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_CURRENT</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_OLD</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_REQUESTED</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_ALTENATIVES</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td colspan="1"><p>6008900572523230000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_FACTS.AD_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_ADVERTISERS {#snowflakedatawarehouseschema[v3]-biz-advertisers}

Table that stores all advertisers downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique identifier for the advertiser</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>DISPLAY_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_ACCOUNT_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the advertiser, specifically for Doubleclick.</p></td> 
   <td><p>300181641</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the advertiser, specifically for Doubleclick.</p></td> 
   <td><p>Bizible Marketing Analytics</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Group above the Advertiser in any ads hierarchy</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td>BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Group above the Advertiser in any ads hierarchy</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Campaign above the Advertiser in any ads hierarchy</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Campaign above the Ad Advertiser in any ads hierarchy</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_ACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the advertiser is still active in the ads platform</p></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the advertiser has been deleted in the ads platform</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><p>2018-08-02 06:35:59.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date and time that this row was first added to the table</p></td> 
   <td><p>2018-08-02 06:35:59.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the advertiser</p></td> 
   <td><p>Bizible Marketing Analytics</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not this row needs to have Bizible update its tags</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “Advertisers”</p></td> 
   <td><p>Advertisers</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ad provider for the advertiser</p></td> 
   <td><p>Doubleclick</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>6008900572523230000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.ADVERTISER_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_AD_ACCOUNTS {#snowflakedatawarehouseschema[v3]-biz-ad-accounts}

Table that stores all ads accounts downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique identifier for the ad account</p></td> 
   <td colspan="1"><p>aw.6601259029</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>6601259029</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Advertiser above the Ad Accounts in any ads hierarchy</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Advertiser above the Ad Accounts in any ads hierarchy</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Ad Group above the Ad Accounts in any ads hierarchy</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Ad Group above the Ad Accounts in any ads hierarchy</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Ad Campaign above the Ad Accounts in any ads hierarchy</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Ad Campaign above the Ad Accounts in any ads hierarchy</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_ACTIVE</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the advertiser is still active in the ads platform</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DELETED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the advertiser has been deleted in the ads platform</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><p>2018-09-06 12:54:37.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date and time that this row was first added to the table</p></td> 
   <td><p>2018-08-02 06:35:58.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ad account</p></td> 
   <td><p>Bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the tagging needs to get updatedfor this ads account.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “Account”</p></td> 
   <td><p>Account</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads provider for the ad account</p></td> 
   <td><p>AdWords</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNT_CURRENCY_UNIT</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The currency code that is used for the ads account.</p></td> 
   <td><p>USD</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>COMPANY_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>SOURCE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MEDIUM</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LAST_30_DAYS_COST</p></td> 
   <td><p>number(38,19)</p></td> 
   <td><p>The amount of spend imported for the last 30 days.</p></td> 
   <td><p>17260.000000000000000000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LAST_30_DAYS_IMPRESSIONS</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The number of impressions from the last 30 days</p></td> 
   <td><p>730060</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LAST_30_DAYS_CLICKS</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The number of clicks from the last 30 days</p></td> 
   <td><p>3400</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LAST_30_DAYS_CONVERSIONS</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The number of conversions reported from the last 30 days</p></td> 
   <td><p>180</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>http://cdn.bizible.com/redir?lp={lpurl}&amp;_bt={creative}&amp;_bk={keyword}&amp;_bm={matchType}</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_OLD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_REQUESTED</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_APPLIED</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The tracking template added on the Ad Account level for AdWords or Bing for tagging landing pages.</p></td> 
   <td><p>http://cdn.bizible.com/redir?lp={lpurl}&amp;_bt={creative}&amp;_bk={keyword}&amp;_bm={matchType}</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>-4609512587744160000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.AD_ACCOUNT_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_AD_CAMPAIGNS {#snowflakedatawarehouseschema[v3]-biz-ad-campaigns}

Table that stores all campaigns downloaded from any connected ads accounts or UTM campaigns.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique identifier for the campaign</p></td> 
   <td><p>aw.6601259029.285114995</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>285114995</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the connected ads account for the campaign</p></td> 
   <td colspan="1"><p>aw.6601259029</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the connected ads account for the campaign</p></td> 
   <td colspan="1"><p>Bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the advertiser for the campaign, specifically for Doubleclick.</p></td> 
   <td colspan="1"><p>300181641</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the advertiser for the campaign, specifically for Doubleclick.</p></td> 
   <td colspan="1"><p>Bizible Marketing Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Group above the Campaign in any ads hierarchy</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td>BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Group above the Campaign in any ads hierarchy</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the campaign</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the campaign</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_ACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the campaign is still active in the ads account</p></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the campaign has been deleted in the ads account</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><p>2018-08-02 06:35:58.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the campaign was first downloaded by Bizible</p></td> 
   <td><p>2018-08-02 06:35:58.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the campaign</p></td> 
   <td><p>Partner Retargeting</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the campaign needs to get updated to get Bizible tagging</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>aw.6601259029</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “Campaign”</p></td> 
   <td><p>Campaign</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads provider for the campaign</p></td> 
   <td><p>AdWords</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>DAILY_BUDGET</p></td> 
   <td><p>number(38,19)</p></td> 
   <td><p>The daily budget that’s set in the ad platform for the campaign.</p></td> 
   <td><p>0.0000000000000000000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_OLD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_REQUESTED</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_APPLIED</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The tracking template added on the Ad Campaign level for AdWords or Bing for tagging landing pages.</p></td> 
   <td><p>http://cdn.bizible.com/redir?lp={lpurl}&amp;_bt={creative}&amp;_bk={keyword}&amp;_bm={matchType}</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td colspan="1"><p>-6008900572523230000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_FACTS.CAMPAIGN_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_AD_GROUPS {#snowflakedatawarehouseschema[v3]-biz-ad-groups}

Table that stores all ad groups downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique identifier for the ad group</p></td> 
   <td colspan="1"><p>aw.6601259029.317737955.23105326115</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>23105326115</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the connected ads account for the ad group</p></td> 
   <td colspan="1"><p>aw.6601259029</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_AD_ACCOUNTS.ID</span></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the connected ads account for the ad group</p></td> 
   <td colspan="1"><p>Bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Ad Group in the Doubleclick ads hierarchy.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_ADVERTISERS.ID</span></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Ad Group in the Doubleclick ads hierarchy.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the ad group for the ad group</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ad group for the ad group</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the campaign for the ad group</p></td> 
   <td><p>aw.6601259029.317737955</p></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the campaign for the ad group</p></td> 
   <td><p>Revenue Attribution</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_ACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the ad group is still active in the ads account </p></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the ad group has been deleted in the ads account</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><p>2018-08-02 06:36:14.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the ad group was first downloaded by Bizible</p></td> 
   <td><p>2018-08-02 06:36:14.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ad group</p></td> 
   <td><p>Revenue Attribution - Account Based</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the ad group needs to get updated to get Bizible tagging</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>aw.6601259029.317737955</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “AdGroup”</p></td> 
   <td><p>AdGroup</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads provider for the ad group</p></td> 
   <td><p>AdWords</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_NETWORK_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The medium(s) that the Ad Group is running on</p></td> 
   <td><p>Search, Display, YouTube_Search, YouTube_Watch</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_OLD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_REQUESTED</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_APPLIED</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The tracking template added on the Ad Account level for AdWords or Bing for tagging landing pages.</p></td> 
   <td><p>http://cdn.bizible.com/redir?lp={lpurl}&amp;_bt={creative}&amp;_bk={keyword}&amp;_bm={matchType}</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>-5594512713562690000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.AD_GROUP_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_AD_PROVIDERS {#snowflakedatawarehouseschema[v3]-biz-ad-providers}

Table that stores all ad providers recognized from any connected ads accounts. This includes an entry for “SelfReported” costs so that it can link to the costs table.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique identifier for the ad provider</p></td> 
   <td><p>Bing</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ad provider</p></td> 
   <td><p>Bing</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>4783788151269206864</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.AD_PROVIDER_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_ATTRIBUTION_TOUCHPOINTS {#snowflakedatawarehouseschema[v3]-biz-attribution-touchpoints}

All touchpoints that are associated with an Opportunity. This table will be empty if Opportunity Touchpoints is disabled.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique Id for the touchpoint</p></td> 
   <td colspan="1"><p>BAT2_0060Z00000lFHtOQAW_</p><p>0030Z00003K5bpKQAR_2017-06-20:01-05-20-6193330.0b5c5678807c</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><p>2018-09-01 04:53:53.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>USER_TOUCHPOINT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Biz_User_Touchpoints table to select columns such as email, campaignmember_id, session_id</p></td> 
   <td colspan="1"><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_USER_TOUCHPOINTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>OPPORTUNITY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Biz_Opportunities table to select columns such as Amount or Close Date</p></td> 
   <td colspan="1"><p>0060Z00000lFHtOQAW</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_OPPORTUNITIES.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CONTACT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Biz_Contacts table to select columns such as Created Date</p></td> 
   <td colspan="1"><p>0030Z00003K5bpKQAR</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Biz_Accounts table to select columns such as Website or Engagement Rating</p></td> 
   <td colspan="1"><p>0013100001otbIAAAY</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_ACCOUNTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>TOUCHPOINT_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date of the recorded touchpoint, which is the date that the session occurred</p></td> 
   <td colspan="1"><p>2017-06-20 01:05:20.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MARKETING_TOUCH_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Touchpoint Type.” This records the type of activity, whether it was a Web Visit, Web Form, Web Chat, Phone Call, [CRM] Campaign, or [CRM] Activity</p></td> 
   <td colspan="1"><p>Web Form</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CHANNEL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Marketing Channel - Path.” This is the channel that the touchpoint falls into, as defined in the custom channel definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>Social.LinkedIn</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY1</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 1st Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>ABC, or NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY2</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 2nd Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>Yes, or NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY3</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 3rd Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>SMB, or NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY4</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 4th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>New Business, or NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY5</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 5th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY6</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 6th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY7</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 7th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY8</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 8th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY9</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 9th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY10</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 10th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY11</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 11th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY12</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 12th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY13</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 13th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY14</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 14th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY15</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 15th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>BROWSER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected browser that the user was on during the session. For example, Chrome or Internet Explorer.</p></td> 
   <td colspan="1"><p>Chrome</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>BROWSER_VERSION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected version of the browser that the user was on during the session. For example, Chrome or Internet Explorer.</p></td> 
   <td colspan="1"><p>58</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLATFORM_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected platform that the user was on during the session. For example, Mac or Windows.</p></td> 
   <td colspan="1"><p>Mac</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLATFORM_VERSION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected version of the platform that the user was on during the session. For example, Mac or Windows.</p></td> 
   <td colspan="1"><p>10_12</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LANDING_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Landing Page” This is the first landing page of the session that resulted in a touchpoint.</p></td> 
   <td colspan="1"><p><span class="nolink">http://www.bizible.com/blog/uncover- truth-behind-cost-per-lead</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LANDING_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Landing Page - Raw.” This is the first landing page of the session that resulted in a touchpoint. A raw landing page will contain all query parameters in the URL.</p></td> 
   <td colspan="1"><p><span class="nolink">http://www.bizible.com/blog/uncover-truth -behind-cost-per-lead?utm_content=27322869&amp;utm_</span></p><p><span class="nolink">medium=social&amp;utm_source=linkedin</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Referrer Page” This is the usually the external landing page immediately before the user comes onto the website.</p></td> 
   <td colspan="1"><p>https://www.linkedin.com/</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Referrer Page - Raw.” This is the usually the external landing page immediately before the user comes onto the website. A raw referrer page may contain query parameters in the URL.</p></td> 
   <td colspan="1"><p>https://www.linkedin.com/</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FORM_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Form URL.” This is the first form that is recorded in a session that resulted in a touchpoint. Subsequent form submissions will not show up in the Biz_Attribution_Touchpoints table, but rather in the Biz_Form_Submits table.</p></td> 
   <td colspan="1"><p><span class="nolink">http://info.bizible.com/intro-guide-b2b-marketing-attribution</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FORM_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Form URL - Raw.” This is the first form that is recorded in a session that resulted in a touchpoint. Subsequent form submissions will not show up in the Biz_Attribution_Touchpoints table, but rather in the Biz_Form_Submits table. A raw form page may contain query parameters in the URL.</p></td> 
   <td colspan="1"><p><span class="nolink">http://info.bizible.com/intro-guide-b2b-marketing-attribution</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FORM_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date that the form submission occurred.</p></td> 
   <td colspan="1"><p>2017-06-20 01:06:41.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CITY </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, Seattle or Vancouver.</p></td> 
   <td colspan="1"><p>San Francisco</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REGION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, Washington or British Columbia.</p></td> 
   <td colspan="1"><p>California</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>COUNTRY</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, United States or Canada.</p></td> 
   <td colspan="1"><p>United States</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MEDIUM</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Used to define the medium that resulted in the touchpoint. This can either be parsed out from the URL from utm_medium or if Bizible is able to resolve an ad, it may be values such as “cpc” or “display.”</p></td> 
   <td colspan="1"><p>social</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>WEB_SOURCE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Touchpoint Source.” Used to define the source that resulted in the touchpoint. This can be parsed out from the URL from utm_source or generically set as “CRM Campaign” if it was synced from the CRM or if Bizible is able to resolve an ad, it may be values such as “Google AdWords” or “Facebook.”</p></td> 
   <td colspan="1"><p>linkedin</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>SEARCH_PHRASE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The value that the user entered in the browser to search for and end up on the website. Depending on the keyword buys, this may or may not match the keywords purchased from the Paid Search platform.</p></td> 
   <td><p>google bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_PROVIDER</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ad platform that Bizible was able to resolve from, typically one of our integration partners.</p></td> 
   <td><p>Google</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNT_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the ads account in which the ad was resolved from.</p></td> 
   <td><p>aw.6601259029</p></td> 
   <td><br></td> 
   <td>BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNT_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads account in which the ad was resolved from, such as Bizible-US.</p></td> 
   <td><p>Bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_UNIQUE_ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the advertiser from the ads accounts in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td><p>300181641</p></td> 
   <td><br></td> 
   <td>BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the advertiser from the ads account in which the ad was resolved from, such as Bizible Inc. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td><p>Bizible Marketing Analytics</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>SITE_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the site from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td><p>1695651</p></td> 
   <td><br></td> 
   <td>BIZ_SITES.ID</td> 
  </tr> 
  <tr> 
   <td><p>SITE_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The site name from the ads account in which the ad was resolved from, such as Quantcast or TechCrunch. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td><p>Quora.com</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PLACEMENT_UNIQUE_ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id placement from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td><p>120839827</p></td> 
   <td><br></td> 
   <td>BIZ_PLACEMENTS.ID</td> 
  </tr> 
  <tr> 
   <td><p>PLACEMENT_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The placement name from the ads account in which the ad was resolved from, such as 300x250 or Home Page Takeover. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td><p>roadblock</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the campaign from the ads account in which the ad was resolved from.</p></td> 
   <td><p>aw.6601259029.317738075</p></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The campaign name from the ads account in which the ad was resolved from, such as Winter Promotion 2018 or Planning Your Budget Webinar.</p></td> 
   <td><p>Marketing Attribution</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the ad group from the ads account in which the ad was resolved from. This only applies to Google Adwords.</p></td> 
   <td><p>aw.6601259029.317738075.23105327435</p></td> 
   <td><br></td> 
   <td>BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ad group name from the ads account in which the ad was resolved from. This only applies to Google AdWords.</p></td> 
   <td><p>Marketing Attribution - General</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The id of the ad from the ads account in which the ad was resolved from. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td>BIZ_ADS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ad name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CREATIVE_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The id of the creative from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td><p>aw.6601259029.317738075.23105327435.182716179597</p></td> 
   <td><br></td> 
   <td>BIZ_CREATIVES.ID</td> 
  </tr> 
  <tr> 
   <td><p>CREATIVE_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The creative name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td><p>B2B Marketing Attribution</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CREATIVE_DESCRIPTION_1</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The first line of the creative from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td><p>Download The CMOs Guide</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_2 &nbsp;&nbsp;</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The second line of the creative from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Learn how attribution measures ROI by connecting marketing activities to revenue</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESTINATION_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The landing page that clicks through from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p><span class="nolink">http://info.bizible.com/cmos-guide-to-b2b-marketing-attribution</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DISPLAY_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The friendly URL name that’s shown on the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p><span class="nolink">http://info.bizible.com/CMOs-Guide</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the keyword that was purchased from the Paid Search buy, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads</p></td> 
   <td colspan="1"><p>aw.6601259029.317738075.23105327435.4838421670</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_KEYWORDS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The keyword that was purchased from the Paid Search buy, which is pulled from the ads account in which the ad was resolved from, such as Software Discount or Annual Budget. This applies to Google AdWords and Bing Ads (search)</p></td> 
   <td colspan="1"><p>"marketing attribution"</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_MATCH_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The type of match that was found between the search phrase and the purchased keyword, such as “broad” or “exact”</p></td> 
   <td colspan="1"><p>Phrase</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_FIRST_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the first touch of the opportunity journey</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_LEAD_CREATION_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the lead creation &nbsp;touch of the opportunity journey</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_OPP_CREATION_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the opportunity creation touch of the opportunity journey</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_CLOSED_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the closed touch of the opportunity journey</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>STAGES_TOUCHED</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The stages that the touchpoint has gone through</p></td> 
   <td colspan="1"><p>Qualified Discovery, Demo Scheduled</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_FORM_SUBMISSION_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint had a form fill during the session</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_IMPRESSION_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the first impression touch of the opportunity journey</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FIRST_CLICK_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s a first touch (See Is_First_Touch)</p></td> 
   <td colspan="1"><p>0.0000000000000000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LAST_ANON_CLICK_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s a lead creation touch (See Is_Last_Anon_Click_Percentage)</p></td> 
   <td colspan="1"><p>0.0000000000000000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>U_SHAPE_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a u-shaped touch (See Is_First_Touch and Is_Lead_Creation_Touch)</p></td> 
   <td colspan="1"><p>0.0000000000000000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>W_SHAPE_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a w-shaped touch (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, and Is_Opp_Creation_Touch)</p></td> 
   <td colspan="1"><p>0.0153374234214425</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FULL_PATH_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19) </p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a full path model (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, Is_Opp_Creation_Touch, </p><p>Is_Closed_Touch)</p></td> 
   <td colspan="1"><p>0.0143061513081193</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CUSTOM_MODEL_PERCENTAGE &nbsp;&nbsp;&nbsp;&nbsp;</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a full path model (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, Is_Opp_Creation_Touch, Is_Closed_Touch, Stages_Touched)</p></td> 
   <td colspan="1"><p>0.0143061513081193</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DELETED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether this touchpoint is deleted or not. Used for diagnostics to see if a record was deleted in CRM.</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td colspan="1"><p>-2712935512233520000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_FACTS.ATP_KEY</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>OPPORTUNITY_ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>-2712935512233520000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">LANDING_PAGE_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">REFERRER_PAGE_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">FORM_PAGE_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ACCOUNT_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ADVERTISER_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">SITE_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_ROW_KEY</p></td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CAMPAIGN_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_GROUP_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CREATIVE_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">KEYWORD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CAMPAIGN_MEMBERS {#snowflakedatawarehouseschema[v3]-biz-campaign-members}

All CRM Campaign Members that are imported, along with custom Bizible fields. This table will be empty if Campaign Sync is disabled.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>CRM CampaignMember Id</p></td> 
   <td colspan="1"><p>00v0Z00001VVzdLQAT</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the Campaign Member from the CRM</p></td> 
   <td><p>2018-08-31 20:49:54.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The created date of the Campaign Member from the CRM</p></td> 
   <td><p>2018-08-31 20:49:54.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_TOUCH_POINT_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>(optional) The date and time that the customer sets to override the campaign date and use this value for the Touchpoint Date instead</p></td> 
   <td><p>2018-08-30 18:00:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id for the related Lead that this Campaign Member is tied to</p></td> 
   <td><p>00Q0Z000013dw4GUAQ</p></td> 
   <td><br></td> 
   <td><p>BIZ_LEADS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email for the related Lead that this Campaign Member is tied to</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CONTACT_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id for the related Contact that this Campaign Member is tied to</p></td> 
   <td><p>00331000032hMxRAAU</p></td> 
   <td><br></td> 
   <td><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>CONTACT_EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email for the related Contact that this Campaign Member is tied to</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>STATUS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Campaign Member’s status, usually set to Sent or Responded or another custom value. This status is tied to the Campaign_Sync_Type to determine which Campaign Members to create touchpoints for</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>HAS_RESPONDED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>A true/false value that tells if the Campaign Member was marked as “Responded” from the Status picker</p></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_RESPONDED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>A date field that is automatically populated if Has_Responded is marked as true</p></td> 
   <td><p>2018-08-30 07:00:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name for the related Campaign that this Campaign Member is apart of</p></td> 
   <td><p>Fast CMO Interviews</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id for the related Campaign that this Campaign Member is apart of</p></td> 
   <td><p>7010Z000001TcKlQAK</p></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Type that’s selected on the related Campaign that this Campaign Member is apart of. The Type is used to map the Marketing Channel.</p></td> 
   <td><p>Offline</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN_SYNC_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Used to determine which Campaign Members to create touchpoints for. The possible values are: Include All Campaign Members, Include “Responded” Campaign Members, Exclude All Campaign Members</p></td> 
   <td><p>Include_All</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_SYNC_STATUS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Used as an audit field to tell whether or not a touchpoint was generated for this Lead as a Bizible Touchpoint and if not, the reason why it didn’t qualify</p></td> 
   <td><p>No Touchpoint: Date outside model</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CONTACT_SYNC_STATUS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Used as an audit field to tell whether or not a touchpoint was generated for this Contact as a Bizible Touchpoint and if not, the reason why it didn’t qualify</p></td> 
   <td><p>Touchpoint Created</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>OPP_SYNC_STATUS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Used as an audit field to tell whether or not a touchpoint was generated for this Contact as a Bizible Attribution Touchpoint and if not, the reason why it didn’t qualify</p></td> 
   <td><p>Touchpoint Created</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Finds whether or not the Campaign Member that was in the system is deleted. Used for diagnostics to see if a record was deleted in CRM.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><span>CUSTOM_PROPERTIES</span></td> 
   <td>varchar</td> 
   <td><span>Custom CRM properties that Bizible has imported from the CRM in JSON format</span></td> 
   <td>{"Campaign_Type__c":"Dinners","Foo":"Bar"}</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CHANNELS {#snowflakedatawarehouseschema[v3]-biz-channels}

Table that stores all marketing channels, as created by the customer.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique identifier for each marketing channel</p></td> 
   <td><p>Paid Search</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of each marketing channel, as created by the customer</p></td> 
   <td><p>Paid Search</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>2018-08-30 07:00:00.000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.CHANNEL_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CONVERSION_RATES {#snowflakedatawarehouseschema[v3]-biz-conversion-rates}

Currency conversion rate data from the CRM.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td>ID</td> 
   <td>number(38,0)</td> 
   <td>A unique value for each currency and start_date combination</td> 
   <td><br></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CURRENCY_ID</td> 
   <td>number(38,0)</td> 
   <td>The unique id value for the currency</td> 
   <td>7493833133899044458</td> 
   <td><br></td> 
   <td>BIZ_CURRENCIES.ID</td> 
  </tr> 
  <tr> 
   <td>SOURCE_ISO_CODE</td> 
   <td>varchar</td> 
   <td>The currency ISO code from the CRM source</td> 
   <td>USD</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>START_DATE</td> 
   <td>timestamp_ntz</td> 
   <td>The start date of the conversion rate</td> 
   <td><p>2018-11-01 00:00:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>END_DATE</td> 
   <td>timestamp_ntz</td> 
   <td>The next start date for the conversion rate (i.e. the end date for the conversion rate is end_date minus 1 day)</td> 
   <td><p>2018-09-01 00:00:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CONVERSION_RATE</td> 
   <td>number(38,0)</td> 
   <td>The rate used to convert the currency to the corporate currency</td> 
   <td>0.76728300</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CREATED_DATE</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><p>2019-03-30 00:54:50.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>MODIFIED_DATE</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><p>2019-03-30 00:54:50.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>IS_DELETED</td> 
   <td>boolean</td> 
   <td>Used to determine if the row/value was deleted from the CRM</td> 
   <td>FALSE</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CONTACTS {#snowflakedatawarehouseschema[v3]-biz-contacts}

All CRM Contacts that are imported, along with custom Bizible fields.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>CRM Contact Id</p></td> 
   <td><p>0030Z00003OzioeQAB</p></td> 
   <td>X</td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the Contact from the CRM</p></td> 
   <td><p>2018-09-05 05:17:53.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The created date of the Contact from the CRM</p></td> 
   <td><p>2018-09-05 05:17:51.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email address of the Contact from the CRM</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNTID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the related Account that this Contact is tied to</p></td> 
   <td><p>0013100001b44aGAAQ</p></td> 
   <td><br></td> 
   <td><p>BIZ_ACCOUNTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_SOURCE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The source in which the contact was created</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_STAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The current stage that the Contact is sitting in, recognized as a custom stage that can be created in Bizible’s application.</p></td> 
   <td><p>Demo Scheduled</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_STAGE_PREVIOUS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A string of all stages that the Contact had previously gone through, recognized as custom stages that can be created in Bizible’s application.</p></td> 
   <td><p>Open - Contact</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ODDS_OF_CONVERSION</p></td> 
   <td><p>number(38,19)</p></td> 
   <td><p>Bizible’s algorithm of estimating whether a contact will help an opportunity close based on the age and stage</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_COOKIE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Bizible’s CookieId value that is used to populate from an integration partner to map an offline Event to a web session. Requirement: Enable Call Tracking: True</p></td> 
   <td><p>08c1063cb0a64349ad0d2d862f5cc700</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Finds whether or not the Contact that was in the system is deleted</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY<br></p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>3263982503087870000</p></td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td>CUSTOM_PROPERTIES</td> 
   <td>varchar</td> 
   <td><span>Custom CRM properties that Bizible has imported from the CRM in JSON format</span></td> 
   <td>{"Contact_Type__c":"CMO", "Foo":"Bar"}</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">IS_DUPLICATE</td> 
   <td colspan="1">boolean</td> 
   <td colspan="1">Default is 'FALSE'. This column exists to mark any persons (leads, contacts) that exist in both Marketo and CRM as duplicate true. If there are duplicates, the Marketo Source lead will be marked IS_DUPLICATE = true (see BIZ_LEADS)</td> 
   <td colspan="1">FALSE / TRUE</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">SOURCE_SYSTEM</td> 
   <td colspan="1">varchar</td> 
   <td colspan="1">Default is 'Crm'. This column exists to capture the 'source' (Marketo&nbsp;or&nbsp;Crm) from where a contact was imported into our system.</td> 
   <td colspan="1"><p>CRM /&nbsp;Marketo&nbsp;</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>OTHER_SYSTEM_ID</p></td> 
   <td colspan="1">varchar</td> 
   <td colspan="1"><p>Default is 'NULL'. This column exists to map a person from&nbsp;Marketo&nbsp;with a Contact from&nbsp;Crm. The value would be the corresponding ID (from&nbsp;Marketo&nbsp;or CRM)&nbsp;</p></td> 
   <td colspan="1"><p>1234 / 00Q0Z00001OohgTUAR&nbsp;</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_COSTS {#snowflakedatawarehouseschema[v3]-biz-costs}

All cost data, either from third party integrations or self reported marketing spend, segmented by various dimensions like Account, Channel, Campaign, Creative, Keyword, AdGroup, Site, Placement.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique Id for the cost record</p></td> 
   <td><p>aw.6601259029.285114995.21703163075.[AdWords Display]_2018-09-06</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><p>2018-09-06 12:22:45.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>COST_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the cost was reported on</p></td> 
   <td><p>2018-09-06 00:00:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>SOURCE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The source of the reported cost</p></td> 
   <td><p>[AdWords Display]</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>COST_IN_MICRO</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The reported cost of the day in millions. User will need to divide the value by 1000000 before using this column.</p></td> 
   <td><p>1410000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CLICKS</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The number of clicks reported for the group for the day</p></td> 
   <td><p>4</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IMPRESSIONS</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The number of impressions reported for the group for the day</p></td> 
   <td><p>4187</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ESTIMATED_TOTAL_POSSIBLE_IMPRESSIONS</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The total number of impressions that are estimated from DCM for the group for the day</p></td> 
   <td><p>5024</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_PROVIDER</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The known provider (Google, Bing, Facebook, LinkedIn, SelfReported) in which the cost was pulled from, which could include costs uploaded through Marketing Spend</p></td> 
   <td><p>Google</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CHANNEL_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id for the marketing channel, created by Bizible</p></td> 
   <td><p>Display.Google</p></td> 
   <td><br></td> 
   <td>BIZ_CHANNELS.ID</td> 
  </tr> 
  <tr> 
   <td><p>CHANNEL_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name for the marketing channel, created by the customer in the Bizible application</p></td> 
   <td><p>Display.Google</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CHANNEL_IS_AGGREGATABLE_COST</p></td> 
   <td><p>boolean</p></td> 
   <td><p>If rolling up costs and summarizing by the channel, filter this column by “TRUE”</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the advertiser pulled from the ads connection, specifically for Doubleclick connections</p></td> 
   <td><p>300181641</p></td> 
   <td><br></td> 
   <td>BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the advertiser pulled from the ads connection, specifically for Doubleclick connections</p></td> 
   <td><p>Bizible Marketing Analytics</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_IS_AGGREGATABLE_COST</p></td> 
   <td><p>boolean</p></td> 
   <td><p>If rolling up costs and summarizing by the advertiser, filter this column by “TRUE”</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNT_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the ads account pulled from the ads connection</p></td> 
   <td><p>aw.6601259029</p></td> 
   <td><br></td> 
   <td>BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNT_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads account pulled from the ads connection</p></td> 
   <td><p>Bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNT_IS_AGGREGATABLE_COST</p></td> 
   <td><p>boolean</p></td> 
   <td><p>If rolling up costs and summarizing by the ads account, filter this column by “TRUE”</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the campaign pulled from the ads connection</p></td> 
   <td><p>aw.6601259029.285114995</p></td> 
   <td><br></td> 
   <td><span>BIZ_AD_CAMPAIGNS.ID</span></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the campaign pulled from the ads connection</p></td> 
   <td colspan="1"><p>Partner Retargeting</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_IS_AGGREGATABLE_COST</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the campaign, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ad group pulled from the ads connection</p></td> 
   <td colspan="1"><p>aw.6601259029.285114995.21703163075</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ad group pulled from the ads connection</p></td> 
   <td colspan="1"><p>ClosedOpp</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_IS_AGGREGATABLE_COST</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the ad group, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ad pulled from the ads connection</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ad pulled from the ads connection</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_IS_AGGREGATABLE_COST</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the ad, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the creative pulled from the ads connection</p></td> 
   <td colspan="1"><p>aw.6601259029.285114995.51749608028.266050115160</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_CREATIVES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the creative pulled from the ads connection</p></td> 
   <td colspan="1"><p>Ad name: Ad3-320x50.gif; 320 x 50</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_IS_AGGREGATABLE_COST</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the creative, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the keyword pulled from the ads connection</p></td> 
   <td colspan="1"><p>aw.6601259029.669328935.39419128772.99608705795</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_KEYWORDS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the keyword pulled from the ads connection</p></td> 
   <td colspan="1"><p>sfdc marketing attribution</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_IS_AGGREGATABLE_COST</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the keyword, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the placement pulled from the ads connection</p></td> 
   <td colspan="1"><p>120839827</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_PLACEMENTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the placement pulled from the ads connection</p></td> 
   <td colspan="1"><p>roadblock</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_IS_AGGREGATABLE_COST</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the placement, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the site pulled from the ads connection</p></td> 
   <td colspan="1"><p>1695651</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_SITES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the site pulled from the ads connection</p></td> 
   <td colspan="1">quora.com</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_IS_AGGREGATABLE_COST</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the site, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DELETED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the record was deleted, used as an audit trail.</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_FACTS.COST_KEY</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_ROW_KEY</p></td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ADVERTISER_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">SITE_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">PLACEMENT_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CAMPAIGN_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_GROUP_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CREATIVE_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">KEYWORD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ISO_CURRENCY_CODE</td> 
   <td colspan="1">varchar</td> 
   <td colspan="1">The ISO currency code as imported from costs data source.</td> 
   <td colspan="1">USD</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CURRENCY_ID</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_CURRENCIES.ID</td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CREATIVES {#snowflakedatawarehouseschema[v3]-biz-creatives}

Table that stores all creatives downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique identifier for the creative</p></td> 
   <td colspan="1"><p>ba.3284209.132855866.4556709270.10426699711</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>10426699711</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the connected ads account for the creative</p></td> 
   <td colspan="1"><p>ba.3284209</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the connected ads account for the creative</p></td> 
   <td colspan="1"><p>Bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the advertiser for the creative, specifically for Doubleclick.</p></td> 
   <td colspan="1"><p>300181641</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the advertiser for the creative, specifically for Doubleclick.</p></td> 
   <td colspan="1"><p>Bizible Marketing Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the ad group for the creative</p></td> 
   <td colspan="1"><p>ba.3284209.132855866.4556709270</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ad group for the creative</p></td> 
   <td colspan="1"><p>PipelineMarketing.com - General</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the campaign for the creative</p></td> 
   <td colspan="1"><p>ba.3284209.132855866</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the campaign for the creative</p></td> 
   <td colspan="1"><p>PipelineMarketing.com</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_ACTIVE</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the creative is still active in the ads account</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DELETED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the creative has been deleted in the ads account</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><p>2018-08-02 06:36:25.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FIRST_IMPORTED</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date that the creative was first downloaded by Bizible</p></td> 
   <td colspan="1"><p>2018-08-02 06:36:25.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the creative</p></td> 
   <td colspan="1"><p>PipelineMarketing.com</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>NEEDS_UPDATE</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the creative needs to get updated to get Bizible tagging</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>GROUPING_KEY</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>ba.3284209.132855866.4556709270</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ENTITY_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The main object or entity for this table. In this case, “Creative”</p></td> 
   <td colspan="1"><p>Creative</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PROVIDER_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ads provider for the creative</p></td> 
   <td colspan="1"><p>BingAds</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_CURRENT</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The current version of the URL including all tags</p></td> 
   <td colspan="1"><p>cdn.bizible.com/redir?lp=http%3a%2f%2fwww.pipelinemarketing.com%2f&amp;_bt={creative}&amp;_bk={keyword}&amp;_bm={matchType}&amp;utm_content={adid}&amp;utm_term={keyword}&amp;utm_campaign=PipelineMarketing.com&amp;utm_source=bing&amp;utm_medium=cpc</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_DISPLAY</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The shortened and friendly URL that’s displayed on the creative</p></td> 
   <td colspan="1"><p>PipelineMarketing.com</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_OLD</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_REQUESTED</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_SHORTENED</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The type of creative, which could be Text or Display</p></td> 
   <td colspan="1"><p>Text</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_UPGRADED_URL</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the creative is using Upgraded URLs</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>HEADLINE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The top line (headline) of the creative</p></td> 
   <td><p>PipelineMarketing.com</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>DESCRIPTION_LINE_1</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The copy from the first line of the creative</p></td> 
   <td><p>Connect &amp; Learn From Revenue-Driven B2B Marketers. Join the Community.</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>DESCRIPTION_LINE_2</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The copy from the second line of the creative</p></td> 
   <td><p>Have You Used Analytics? Leave a Review Today!</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_OLD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_REQUESTED</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_APPLIED</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The URL tracking template that Bizible added to the creative</p></td> 
   <td><p><span class="nolink">http://cdn.bizible.com/redir?lp={lpurl}&amp;_bt={creative}&amp;_bk={keyword}&amp;_bm={matchType</span>}</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>SHARE_URN</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The share Id, used for LinkedIn ads only.</p></td> 
   <td><p>urn:li:share:6376987561897848832</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>4609512587744160000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.CREATIVE_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CRM_EVENTS {#snowflakedatawarehouseschema[v3]-biz-crm-events}

All CRM Events that are imported, along with custom Bizible fields.

Requirements: Enable Activities Sync: True

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>CRM Event Id</p></td> 
   <td><p>00U3100000VLUnEEAX</p></td> 
   <td>X</td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The created date of the Event from the CRM</p></td> 
   <td><p>2016-12-12 19:32:53.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the Event from the CRM</p></td> 
   <td><p>2018-09-03 08:39:51.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the related Lead that this Event is tied to</p></td> 
   <td><p>00Q0Z000013eVrxUAE</p></td> 
   <td><br></td> 
   <td><p>BIZ_LEADS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email of the related Lead that this Event is tied to</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CONTACT_ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the related Contact that this Event is tied to</p></td> 
   <td><p>0030Z00003OyjbOQAR</p></td> 
   <td><br></td> 
   <td><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>CONTACT_EMAIL </p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email of the related Contact that this Event is tied to</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_COOKIE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Bizible’s CookieId value that is used to populate from an integration partner to map an offline Event to a web session. Requirement: Enable Call Tracking: True</p></td> 
   <td><p>08c1063cb0a64349ad0d2d862f5cc700</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ACTIVITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Type value that’s pulled from the CRM for the Event</p></td> 
   <td><p>Email</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EVENT_START_DATE </p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The start date of the Event record, one of the options used to determine the Bizible Touchpoint Date</p></td> 
   <td><p>2016-12-16 19:30:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EVENT_END_DATE </p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The end date of the Event record, one of the options used to determine the Bizible Touchpoint Date</p></td> 
   <td><p>2016-12-16 21:30:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Finds whether or not the Event that was in the system is deleted</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CUSTOM_PROPERTIES</td> 
   <td>varchar</td> 
   <td><span>Custom CRM properties that Bizible has imported from the CRM in JSON format</span></td> 
   <td><span>{"Contact_Type__c":"CMO","Foo":"Bar"}</span></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CRM_TASKS {#snowflakedatawarehouseschema[v3]-biz-crm-tasks}

All CRM Tasks that are imported, along with custom Bizible fields.

Requirements: Enable Activities Sync: True OR Enable Call Tracking: True

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>CRM Task Id</p></td> 
   <td><p>00T0Z00004Rf62rUAB</p></td> 
   <td>X</td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The created date of the Task from the CRM</p></td> 
   <td><p>2018-08-27 18:30:25.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the Task from the CRM</p></td> 
   <td><p>2018-08-27 18:31:53.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the related Lead that this Task is tied to</p></td> 
   <td><p>00Q0Z000013eVrxUAE</p></td> 
   <td><br></td> 
   <td><p>BIZ_LEADS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email of the related Lead that this Task is tied to</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CONTACT_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the related Contact that this Task is tied to</p></td> 
   <td><p>00331000038uGfhAAE</p></td> 
   <td><br></td> 
   <td><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>CONTACT_EMAIL </p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email of the related Contact that this Task is tied to</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_COOKIE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Bizible’s CookieId value that is used to populate from an integration partner to map an offline Task to a web session. Requirement: Enable Call Tracking: True</p></td> 
   <td><p>08c1063cb0a64349ad0d2d862f5cc700</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ACTIVITY_TYPE </p></td> 
   <td><p>varchar</p></td> 
   <td><p>Used to describe the type of Task, usually along the lines of Call or Email or any other custom value. For Activities, this value is used to populate the Touchpoint Type and Medium.</p></td> 
   <td><p>Call</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ACTIVITY_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the Task occurred, one of the options used to determine the Bizible Touchpoint Date</p></td> 
   <td><p>2018-08-27 07:00:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Finds whether or not the Task that was in the system is deleted</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CUSTOM_PROPERTIES</td> 
   <td>varchar</td> 
   <td><span>Custom CRM properties that Bizible has imported from the CRM in JSON format</span></td> 
   <td><span>{"Contact_Type__c":"CMO", "Foo":"Bar"}</span></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CURRENCIES {#snowflakedatawarehouseschema[v3]-biz-currencies}

Table of all ISO currencies.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col style="width: 165.0px;"> 
  <col style="width: 118.0px;"> 
  <col style="width: 379.0px;"> 
  <col style="width: 181.0px;"> 
  <col style="width: 106.0px;"> 
  <col style="width: 149.0px;"> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td>number(38,0)</td> 
   <td>A unique Id for the currency record</td> 
   <td>139474809945095870</td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>ISO_CODE</td> 
   <td>varchar</td> 
   <td>The ISO code for the currency</td> 
   <td>USD</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>IS_CORPORATE</td> 
   <td>boolean</td> 
   <td>Designates if the currency is the corporate currency</td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>IS_ENABLED</td> 
   <td>boolean</td> 
   <td>Designates if the currency is enabled in the CRM or not</td> 
   <td>FALSE</td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td>MODIFIED_DATE</td> 
   <td>timestamp_ntz</td> 
   <td>The last modified date from Bizible</td> 
   <td><span>2018-08-27 18:30:25.000</span></td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td>MODIFIED_DATE_CRM</td> 
   <td>timestamp_ntz</td> 
   <td>The last modified date of the currency from the CRM</td> 
   <td><span>2018-08-27 18:30:25.000</span></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CREATED_DATE</td> 
   <td>timestamp_ntz</td> 
   <td>The created date from Bizible</td> 
   <td><span>2018-08-27 18:30:25.000</span></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CREATED_DATE_CRM</td> 
   <td>timestamp_ntz</td> 
   <td>The created date of the currency from the CRM</td> 
   <td><span>2018-08-27 18:30:25.000</span></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>ISO_NUMERIC</td> 
   <td>number(38,0)</td> 
   <td>The ISO standard numeric code</td> 
   <td>048</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>EXPONENT</td> 
   <td>number(38,0)</td> 
   <td><br></td> 
   <td>2</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>NAME</td> 
   <td>varchar</td> 
   <td>The name of the currency</td> 
   <td>Argentine Peso</td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CUSTOMER_AB_TESTS {#snowflakedatawarehouseschema[v3]-biz-customer-ab-tests}

AB Tests that have been recorded which contain a VisitorId and is related to a Biz_Session. This will contain the experiment and variation that the user was shown.

Requirement: Enable AB Tests: Yes

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>VISITOR_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The first cookie of the related visitor Id</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_EMAIL_TO_VISITOR_IDS.VISITOR_ID</td> 
  </tr> 
  <tr> 
   <td><p>COOKIE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded cookie Id at the time the chat was logged.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EVENT_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date and time that the chat was logged.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>MODIFIED_DATE</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>IP_ADDRESS</td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded IP address at the time the experiment was logged.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EXPERIMENT_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the experiment that’s pulled from the AB test platform.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EXPERIMENT_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the experiment that’s pulled from the AB test platform.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>VARIATION_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the experiment’s variation that’s pulled from the AB test platform.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>VARIATION_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the experiment’s variation that’s pulled from the AB test platform.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ABTEST_USER_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the user that was served the experiment that’s pulled from the AB test platform.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the record was deleted, used for diagnostics and auditing.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CUSTOMER_EVENTS {#snowflakedatawarehouseschema[v3]-biz-customer-events}

Web events that have been recorded using custom events in the Javascript which contain a VisitorId and is related to a Biz_Session.

Requirement: Enable Bizible Events: True

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>VISITOR_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The first cookie of the related visitor Id</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_EMAIL_TO_VISITOR_IDS.VISITOR_ID</td> 
  </tr> 
  <tr> 
   <td><p>COOKIE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded cookie Id at the time the event was triggered from the javascript.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EVENT_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date and time that the event was triggered from the custom javascript.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>MODIFIED_DATE</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IP_ADDRESS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded IP address at the time the event was triggered from the custom javascript.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name given to the event that was triggered from the custom javascript. For example, “Video View”</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>VALUE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A value that’s given from the event that was triggered from the custom javascript. For example, “75% viewed”</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the record was deleted, used for diagnostics and auditing.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_CUSTOM_LANDING_PAGES {#snowflakedatawarehouseschema[v3]-biz-custom-landing-pages}

Table that stores all landing pages downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique Id for the row</p></td> 
   <td><br></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the advertiser for the landing page, specifically for Doubleclick.</p></td> 
   <td colspan="1">300181641</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_ADVERTISERS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the advertiser for the landing page, specifically for Doubleclick.</p></td> 
   <td colspan="1"><p>Bizible Marketing Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_ACTIVE</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DELETED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FIRST_IMPORTED</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>NEEDS_UPDATE</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>GROUPING_KEY</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ENTITY_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PROVIDER_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_CURRENT</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>URL_OLD</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_DISCOVERED_FORM {#snowflakedatawarehouseschema[v3]-biz-discovered-form}

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td>ID</td> 
   <td>varchar</td> 
   <td><br></td> 
   <td><br></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>BIZ_DIAG</td> 
   <td><span>varchar</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>DOMAIN</td> 
   <td><span>varchar</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>MODIFIED_DATE</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>URL</td> 
   <td><span>varchar</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>BIZIBLE_JS_ATTACHED</td> 
   <td>boolean</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>BIZIBLE_EXCLUDE_ON_LOGIN</td> 
   <td>boolean</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>LAST_FORM_SUBMIT</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>IS_DELETED</td> 
   <td>boolean</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>LAST_CRAWLED</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>LAST_FOUND_ON_EDGECASTLOG_DATE</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>URL_ROW_KEY</td> 
   <td>number(38,0)</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_DISCOVERED_PAGE {#snowflakedatawarehouseschema[v3]-biz-discovered-page}

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td>DOMAIN</td> 
   <td>varchar</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>MODIFIED_DATE</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>URL</td> 
   <td>varchar</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>LAST_CRAWLED</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>BIZIBLE_JS_PRESENT</td> 
   <td>boolean</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>BIZIBLE_ACCT_PRESENT</td> 
   <td><span>boolean</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>HAS_IFRAME</td> 
   <td><span>boolean</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>ERROR_LOADING_PAGE</td> 
   <td>varchar</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>HAS_OPTIMIZELY</td> 
   <td><span>boolean</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>HAS_GOOGLE_EXPERIMENTS</td> 
   <td><span>boolean</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>HAS_FORM</td> 
   <td><span>boolean</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>TIME_TO_LOAD</td> 
   <td>number(22,19)</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>HAS_GOOGLE_TAG_MANAGER</td> 
   <td><span>boolean</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>IS_LANDING_PAGE</td> 
   <td><span>boolean</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>HAS_BIZIBLE_JS_IN_HEAD</td> 
   <td><span>boolean</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>REFERRER</td> 
   <td>varchar</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>LAST_FOUND_BIZIBLE_JS</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>LAST_PAGEVIEW</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>LAST_FOUND_ON_EDGECASTLOG_DATE</td> 
   <td>timestamp_ntz</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">IS_DELETED</td> 
   <td colspan="1"><span>boolean</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">QUERY_PARAMETERS</td> 
   <td colspan="1">varchar</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ROW_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_EMAIL_TO_VISITOR_IDS {#snowflakedatawarehouseschema[v3]-biz-email-to-visitor-ids}

Email addresses mapped to the Visitor_Id.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>EMAIL </p></td> 
   <td><p>varchar</p></td> 
   <td><p>A known email address that’s tied to a given visitor Id from a session</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>VISITOR_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The first cookie of the related visitor Id</p></td> 
   <td><p>v_36ec805b4db344d6e92c972c86aee34a</p></td> 
   <td>X</td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><p>2018-08-14 23:55:03.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The created date of the row</p></td> 
   <td><p>2018-08-14 23:55:03.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the record was deleted, used for diagnostics and auditing.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>IS_IGNORED</td> 
   <td>boolean</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_FACTS {#snowflakedatawarehouseschema[v3]-biz-facts}

The biz_facts table unions together Impressions, Page Views, Visits, Form Submits, User Touchpoints, Touchpoints (BT), Attribution Touchpoints (BAT), and Cost data. It is used internally to support Bizible reporting in Discover.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col style="width: 75.0px;"> 
  <col style="width: 91.0px;"> 
  <col style="width: 102.0px;"> 
  <col style="width: 109.0px;"> 
  <col style="width: 106.0px;"> 
  <col style="width: 149.0px;"> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td>COST_KEY</td> 
   <td>number(38,0)</td> 
   <td>The key that relates this table to the BIZ_COSTS table to join the dimensions</td> 
   <td><span>2672629811884560039</span></td> 
   <td><br></td> 
   <td>BIZ_COSTS.ROW_KEY</td> 
  </tr> 
  <tr> 
   <td><p>ATP_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_ATTRIBUTION_TOUCHPOINTS table to join the dimensions</p></td> 
   <td><p>2672629811884560039</p></td> 
   <td><br></td> 
   <td><p>BIZ_ATTRIBUTION_TOUCHPOINTS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>TP_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_TOUCHPOINTS table to join the dimensions</p></td> 
   <td><p>5028390208679093800</p></td> 
   <td><br></td> 
   <td><p>BIZ_TOUCHPOINTS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>PAGE_VIEW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_PAGE_VIEWS table to join the dimensions</p></td> 
   <td><p>-8044063242541720607</p></td> 
   <td><br></td> 
   <td><p>BIZ_PAGE_VIEWS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>SESSION_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_SESSIONS table to join the dimensions</p></td> 
   <td><p>8817975702393619368</p></td> 
   <td><br></td> 
   <td><p>BIZ_SESSIONS_ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>VISITOR_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id that relates this table to the BIZ_EMAIL_TO_VISITOR_IDS table to join the dimensions</p></td> 
   <td><p>v_530d8334c455460df0d48f48270a4b23</p></td> 
   <td><br></td> 
   <td><p>BIZ_EMAIL_TO_VISITOR_IDS.VISITOR_ID </p></td> 
  </tr> 
  <tr> 
   <td>COOKIE_ID</td> 
   <td>varchar</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FORM_SUBMIT_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FORM_SUBMITS table to join the dimensions</p></td> 
   <td><p>-8659572802702769670</p></td> 
   <td><br></td> 
   <td><p>BIZ_FORM_SUBMITS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>IMPRESSION_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_IMPRESSIONS table to join the dimensions</p></td> 
   <td><p>8817975702393619368</p></td> 
   <td><br></td> 
   <td><p>BIZ_IMPRESSIONS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>CURRENT_PAGE_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><br></td> 
   <td><p>4079876040770132443</p></td> 
   <td><br></td> 
   <td>BIZ_URLS.ROW_KEY</td> 
  </tr> 
  <tr> 
   <td><p>REFERRER_PAGE_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><br></td> 
   <td><p>8817975702393619368</p></td> 
   <td><br></td> 
   <td>BIZ_URLS.ROW_KEY</td> 
  </tr> 
  <tr> 
   <td><p>FORM_PAGE_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><br></td> 
   <td><p>8817975702393619368</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_PROVIDER_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_AD_PROVIDERS table to join the dimensions</p></td> 
   <td><p>8817975702393619368</p></td> 
   <td><br></td> 
   <td><p>BIZ_AD_PROVIDERS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>CHANNEL_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_CHANNELS table to join the dimensions</p></td> 
   <td><p>-1921844114032355934</p></td> 
   <td><br></td> 
   <td><p>BIZ_CHANNELS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_AD_CAMPAIGNS table to join the dimensions</p></td> 
   <td><p>252687814634577606</p></td> 
   <td><br></td> 
   <td><p>BIZ_AD_CAMPAIGNS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>KEYWORD_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_KEYWORDS table to join the dimensions</p></td> 
   <td><p>8817975702393619368</p></td> 
   <td><br></td> 
   <td><p>BIZ_KEYWORDS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>AD_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_ADS table to join the dimensions</p></td> 
   <td><p>8817975702393619368</p></td> 
   <td><br></td> 
   <td><p>BIZ_ADS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_AD_GROUPS table to join the dimensions</p></td> 
   <td><p>8817975702393619368</p></td> 
   <td><br></td> 
   <td><p>BIZ_AD_GROUPS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td><p>CREATIVE_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_CREATIVES table to join the dimensions</p></td> 
   <td><p>-2333871387956621113</p></td> 
   <td><br></td> 
   <td><p>BIZ_CREATIVES.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_SITES table to join the dimensions</p></td> 
   <td colspan="1"><p>8817975702393619368</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_SITES.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_ADVERTISERS table to join the dimensions</p></td> 
   <td colspan="1"><p>8817975702393619368</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_ADVERTISERS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_AD_ACCOUNTS table to join the dimensions</p></td> 
   <td colspan="1"><p>1825012532740770032</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_AD_ACCOUNTS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_PLACEMENTS table to join the dimensions</p></td> 
   <td colspan="1"><p>8817975702393619368</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_PLACEMENTS.ROW_KEY</p></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_01_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_SEGMENTS.ROW_KEY</td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_02_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_03_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_04_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_05_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_06_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_07_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_08_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_09_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_10_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_11_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_12_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_13_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_14_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1">CATEGORY_15_KEY</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><span>BIZ_SEGMENTS.ROW_KEY</span></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>TYPE</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>Maps the row to the category it belongs to:</p><p><span>TPOpp = 1,</span><span><br></span><span>Cost = 2,</span><span><br></span><span>TPLead = 3,</span><span><br></span><span>TPUser = 4,</span><span><br></span><span>PageView = 5,</span><span><br></span><span>Session = 6,</span><span><br></span><span>FormSubmit = 7,</span><span><br></span><span>Impression = 8</span></p></td> 
   <td colspan="1"><p>3</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DATE</p></td> 
   <td colspan="1"><p>date</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>2018-08-28</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>TIMESTAMP</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>2018-08-28 19:39:15.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date and time the row was last modified</p></td> 
   <td colspan="1"><p>2018-08-29 00:46:47.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>COST_IN_MICRO</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The reported cost of the day in millions. User will need to divide the value by 1000000 before using this column.</p></td> 
   <td colspan="1"><p>27370000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IMPRESSIONS</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The number of impressions reported for the day</p></td> 
   <td colspan="1"><p>340</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CLICKS</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The number of clicks reported for the day</p></td> 
   <td colspan="1"><p>4</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FIRST_CLICK_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s a first touch (See Is_First_Touch)</p></td> 
   <td colspan="1"><p>100.0000000000000000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LAST_ANON_CLICK_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s a lead creation touch (See Is_Last_Anon_Click_Percentage)</p></td> 
   <td colspan="1"><p>100.0000000000000000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>U_SHAPE_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a u-shaped touch (See Is_First_Touch and Is_Lead_Creation_Touch)</p></td> 
   <td colspan="1"><p>100.0000000000000000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>W_SHAPE_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a w-shaped touch (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, and Is_Opp_Creation_Touch)</p></td> 
   <td colspan="1"><p>0.0000000000000000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FULL_PATH_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a full path model (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, Is_Opp_Creation_Touch, </p><p>Is_Closed_Touch)</p></td> 
   <td colspan="1"><p>0.0000000000000000000 &nbsp;</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CUSTOM_MODEL_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a full path model (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, Is_Opp_Creation_Touch, Is_Closed_Touch, Stages_Touched)</p></td> 
   <td colspan="1"><p>0.0000000000000000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AMOUNT</p></td> 
   <td colspan="1"><p>number(38,8)</p></td> 
   <td colspan="1"><p>The deal amount that is expected or closed from the Opportunity</p></td> 
   <td colspan="1"><p>42000.00000000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_WON</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the Opportunity has been moved to a stage that is considered Won</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_OPP_CLOSED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the Opportunity has been moved to a stage that is considered closed, which can either be Won or Lost</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>OPPORTUNITY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id that relates this table to the BIZ_OPPORTUNITIES table to join the dimension</p></td> 
   <td colspan="1"><p>0060Z00000nFEfEQAW</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_OPPORTUNITIES.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>OPP_CREATED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The created date of the Opportunity from the CRM</p></td> 
   <td colspan="1"><p>2018-08-31 15:45:47.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>OPP_CLOSE_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The anticipated or actual Close Date set on the Opportunity</p></td> 
   <td colspan="1"><p>2018-12-31 07:00:00.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CONTACT_CREATED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The created date of the Contact from the CRM</p></td> 
   <td colspan="1"><p>2018-08-07 20:49:07.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CONTACT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id that relates this table to the BIZ_CONTACTS table to join the dimensions</p></td> 
   <td colspan="1"><p>0030Z00003ORVJmQAP</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1">EMAIL</td> 
   <td colspan="1">varchar</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LEAD_CREATED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The created date of the Lead from the CRM</p></td> 
   <td colspan="1"><p>2017-04-28 00:21:52.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LEAD_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id that relates this table to the BIZ_LEADS table to join the dimensions</p></td> 
   <td colspan="1"><p>00Q3100001GMPIsEAP</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_LEADS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_AD</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the ad, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_ADVERTISER</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the advertiser, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_AD_ACCOUNT</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the ad account, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_AD_GROUP</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the ad group, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_CAMPAIGN</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the campaign, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_CHANNEL</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the channel, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_CREATIVE</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the creative, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_KEYWORD</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the keyword, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_PLACEMENT</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the placement, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_AGGREGATABLE_COST_SITE</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>If rolling up costs and summarizing by the site, filter this column by “TRUE”</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DELETED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the record was deleted, used as an audit trail.</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ISO_CODE</td> 
   <td colspan="1">varchar</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CURRENCY_ID</td> 
   <td colspan="1">number(38,0)</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_CURRENCIES.ID</td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_FORM_SUBMITS {#snowflakedatawarehouseschema[v3]-biz-form-submits}

All form submissions that occurred which contain a VisitorId and is related to a Biz_Session.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique Id for the form submission</p></td> 
   <td><p>2018-08-06:01-35-21-927280.9bc63c34482f4</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>COOKIE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded cookie Id at the time the form was submitted</p></td> 
   <td><p>9bc63c34482f4de8c2e3b9d8d9f0df56</p></td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>VISITOR_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The first cookie of the related visitor Id</p></td> 
   <td colspan="1"><p>v_9bc63c34482f4de8c2e3b9d8d9f0df56</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_EMAIL_TO_VISITOR_IDS.VISITOR_ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SESSION_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The recorded session Id at the time the form was submitted</p></td> 
   <td colspan="1"><p>2018-08-06:01-35-24-1231230.9bc63c34482f</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_SESSIONS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>EVENT_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date and time that form was submitted</p></td> 
   <td colspan="1"><p>2018-08-06 01:35:21.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><p>2018-08-07 23:09:52.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CURRENT_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The URL where the form was submitted without query parameters.</p></td> 
   <td colspan="1"><p><span class="nolink">https://info.bizible.com/webinar-marketo-bizible-impact</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CURRENT_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The URL where the form was submitted. The current page may contain query parameters in the URL.</p></td> 
   <td colspan="1"><p><span class="nolink">https://info.bizible.com/webinar-marketo-bizible-impact?utm_source=partner&amp;mkt_tok=eyJpIjoiTnpBeE1EVml PV0UyWlRObSIsInQiOiI3MEFIek04ZVJiWm9renc1Z29RXC9kXC92YkxycFRYclE0MVhOaH<br>Nwdml3YTZBZDdPdXh4Q0RmcnBJWXhwZTF1Z0RrbXlDVmxJNzIwNkhWOExxNFZLRmphc</span></p><p><span class="nolink">ThVXC9xc3FvR2pET2lXT1ZOMjlKZXEyd3lSMVU3YmljeWdZVWUyZU5iWiJ9</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IP_ADDRESS</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The recorded IP address at the time the form was submitted</p></td> 
   <td colspan="1"><p>174.127.184.158</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>FormSubmit</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>USER_AGENT_STRING</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The device and browser that the person is using at the time of the form submit.</p></td> 
   <td><p>Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_6) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/11.1.2 Safari/605.1.15</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CLIENT_SEQUENCE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>4</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CLIENT_RANDOM</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>20042b6b7af44512b43f6244d86faf4c</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DUPLICATED</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_PROCESSED</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email address provided that’s pulled directly from the form, as captured from the javascript.</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FORM_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>Form</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FORM_SOURCE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The method in which the form was recognized, such as onSubmit or AjaxIntercept</p></td> 
   <td><p>onSubmit</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FORM_IDENTIFIER</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>-956012665</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>-6255315750913680000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.FORM_SUBMIT_KEY</p></td> 
  </tr> 
  <tr> 
   <td>CURRENT_PAGE_KEY</td> 
   <td>number(38,0)</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_IMPRESSIONS {#snowflakedatawarehouseschema[v3]-biz-impressions}

All impressions that have been fired and recorded which contain a VisitorId and is related to the Biz_Touchpoints. This will contain the resolved ads information of the served impression.

Requirements: Enable View Through: True, Doubleclick by Google: True

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique Id for the impression</p></td> 
   <td><br></td> 
   <td>X</td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>COOKIE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded cookie Id at the time of the impression</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>VISITOR_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The first cookie of the related visitor Id</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><p>BIZ_EMAIL_TO_VISITOR_IDS.VISITOR_ID</p></td> 
  </tr> 
  <tr> 
   <td><p>SESSION_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded session Id at the time of the impression.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><p>BIZ_SESSIONS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>EVENT_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date and time that the impression was served</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CURRENT_PAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The URL where the impression was served without query parameters.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CURRENT_PAGE_RAW</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The URL where the form was submitted. The current page may contain query parameters in the URL.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IP_ADDRESS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded IP address at the time of the impression</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>USER_AGENT_STRING</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The device and browser that the person is using at the time of the form submit.</p></td> 
   <td><p>Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_6) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/11.1.2 Safari/605.1.15</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CLIENT_SEQUENCE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>4</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CLIENT_RANDOM</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>20042b6b7af44512b43f6244d86faf4c</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DUPLICATED</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_PROCESSED</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>REFERRER_PAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Referred to in the CRM as “Referrer Page” This is the usually the external landing page immediately before the user comes onto the website. </p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>REFERRER_PAGE-RAW</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Referred to in the CRM as “Referrer Page - Raw.” This is the usually the external landing page immediately before the user comes onto the website. A raw referrer page may contain query parameters in the URL.</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CITY</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The resolved city from the IP address. For example, Seattle or Vancouver.</p></td> 
   <td><p>Seattle</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>REGION</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The resolved region from the IP address. For example, Washington or British Columbia.</p></td> 
   <td><p>Washington</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>COUNTRY</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The resolved country from the IP address. For example, United States or Canada.</p></td> 
   <td colspan="1"><p>United States</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ISP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the internet service provider, used by customers with advanced Geo IP tracking.</p></td> 
   <td colspan="1"><p>AT&amp;T U-verse</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_PROVIDER</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad platform that Bizible was able to resolve from, typically one of our integration partners.</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ads account in which the ad was resolved from.</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ads account in which the ad was resolved from, such as Bizible-US.</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the advertiser from the ads accounts in which the ad was resolved from, specifically for Doubleclick connections.</p></td> 
   <td colspan="1"><p>300181641</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the advertiser from the ads account in which the ad was resolved from, specifically for Doubleclick connections.</p></td> 
   <td colspan="1"><p>Bizible Marketing Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the site from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>1695651</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_SITES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The site name from the ads account in which the ad was resolved from, such as Quantcast or TechCrunch. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>Quora.com</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_UNIQUE_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id placement from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>120839827</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_PLACEMENTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The placement name from the ads account in which the ad was resolved from, such as 300x250 or Home Page Takeover. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>roadblock</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the campaign from the ads account in which the ad was resolved from.</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The campaign name from the ads account in which the ad was resolved from, such as Winter Promotion 2018 or Planning Your Budget Webinar.</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Ad Group in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Ad Group in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The id of the ad from the ads account in which the ad was resolved from. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td colspan="1"><p>68035923</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td colspan="1"><p>centurylink_banner_98121</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_CREATIVES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_1</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_2 &nbsp;&nbsp;</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESTINATION_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DISPLAY_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_KEYWORDS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_MATCH_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Creative in the Doubleclick hierarchy for impressions</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>BROWSER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected browser that the user was on during the session. For example, Chrome or Internet Explorer.</p></td> 
   <td colspan="1"><p>Chrome</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>BROWSER_VERSION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected version of the browser that the user was on during the session. For example, Chrome or Internet Explorer.</p></td> 
   <td colspan="1"><p>58</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLATFORM_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected platform that the user was on during the session. For example, Mac or Windows.</p></td> 
   <td colspan="1"><p>Mac</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLATFORM_VERSION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected version of the platform that the user was on during the session. For example, Mac or Windows.</p></td> 
   <td colspan="1"><p>10_12</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td colspan="1"><p>-2712935512233520000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_FACTS.IMPRESSION_KEY</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CURRENT_PAGE_KEY</p></td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">REFERRER_PAGE_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ACCOUNT_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ADVERTISER_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">SITE_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">PLACEMENT_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CAMPAIGN_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_GROUP_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CREATIVE_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">KEYWORD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_KEYWORDS {#snowflakedatawarehouseschema[v3]-biz-keywords}

Table that stores all keywords downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique identifier for the keyword</p></td> 
   <td colspan="1"><p>ba.3284209.132630532.3646889365.39464932147</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>39464932147</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the connected ads account for the keyword</p></td> 
   <td colspan="1"><p>ba.3284209</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the connected ads account for the keyword</p></td> 
   <td colspan="1"><p>Bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Keyword in the Doubleclick ads hierarchy.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Expected to be NULL since there is no Keyword in the Doubleclick ads hierarchy.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the ad group for the keyword</p></td> 
   <td colspan="1"><p>ba.3284209.132630532.3646889365</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ad group for the keyword</p></td> 
   <td colspan="1"><p>Revenue Attribution - B2B</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the campaign for the keyword</p></td> 
   <td colspan="1"><p>ba.3284209.132630532</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the campaign for the keyword</p></td> 
   <td colspan="1"><p>Revenue Attribution</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_ACTIVE</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the keyword is still active in the ads account</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DELETED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the keyword has been deleted in the ads account</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><p>2018-08-02 06:37:29.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FIRST_IMPORTED</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date that the keyword was first downloaded by Bizible</p></td> 
   <td colspan="1"><p>2018-08-02 06:37:29.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the keyword</p></td> 
   <td colspan="1"><p>[revenue attribution b2b]</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the keyword needs to get updated to get Bizible tagging</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>ba.3284209.132630532.3646889365</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “Keyword”</p></td> 
   <td><p>Keyword</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads provider for the keyword</p></td> 
   <td><p>BingAds</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>URL_CURRENT</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>URL_OLD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_UPGRADED_URL</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>WORD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>revenue attribution b2b</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MATCH_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The type of match that was found between the search phrase and th</p></td> 
   <td><p>Exact</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_OLD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_REQUESTED</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TRACKING_URL_TEMPLATE_APPLIED</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p><span class="nolink">http://cdn.bizible.com/redir?lp={lpurl}&amp;_bt={creative}&amp;_bk={keyword}&amp;_bm={matchType</span>}</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.KEYWORD_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_LANDING_PAGES {#snowflakedatawarehouseschema[v3]-biz-landing-pages}

Table that stores all landing pages downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique Id for the touchpoint</p></td> 
   <td><br></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the advertiser for the landing page, specifically for Doubleclick.</p></td> 
   <td><span>300181641</span></td> 
   <td><br></td> 
   <td><p>BIZ_ADVERTISERS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the advertiser for the landing page, specifically for Doubleclick.</p></td> 
   <td><span>Bizible Marketing Analytics</span></td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_ACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>URL_CURRENT</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>URL_OLD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>URL_REQUESTED</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_LEADS {#snowflakedatawarehouseschema[v3]-biz-leads}

All CRM Leads that are imported, along with custom Bizible fields.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>CRM Lead Id</p></td> 
   <td><p>00Q0Z00001MZcj8UAD</p></td> 
   <td>X</td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the Lead from the CRM</p></td> 
   <td><p>2018-08-27 21:52:10.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CREATED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The created date of the Lead from the CRM</p></td> 
   <td><p>2018-08-27 21:47:05.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email address of the Lead from the CRM</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>WEB_SITE </p></td> 
   <td><p>varchar</p></td> 
   <td><p>Website that is entered for the Lead, used for Lead2Account mapping</p></td> 
   <td><p>bizible.com</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>COMPANY</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The company name that is entered for the Lead, used for Lead2Account mapping</p></td> 
   <td><p>Bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_SOURCE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The value of the Lead Source, as entered in the CRM</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_CONVERTED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the Lead has been converted to a Contact</p></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CONVERTED_OPPORTUNITY_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the related Opportunity once the Lead has been converted, if applicable</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td>BIZ_OPPORTUNITIES.ID</td> 
  </tr> 
  <tr> 
   <td><p>CONVERTED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the Lead was converted to a Contact, if applicable</p></td> 
   <td><p>2018-08-27 07:00:00.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CONVERTED_CONTACT_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the related Contact once the Lead has been converted, if applicable</p></td> 
   <td><p>0030Z00003Oyp25QAB</p></td> 
   <td><br></td> 
   <td>BIZ_CONTACTS.ID</td> 
  </tr> 
  <tr> 
   <td><p>ACCOUNTID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the mapped Account based off of domain and company name matching. </p><p>Requirements: Enable ABM</p></td> 
   <td><p>0010Z0000236F9GQAU</p></td> 
   <td><br></td> 
   <td><p>BIZ_ACCOUNTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_STAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The current stage that the Lead is sitting in, recognized as a custom stage that can be created in Bizible’s application.</p></td> 
   <td><p>Demo Scheduled</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_STAGE_PREVIOUS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A string of all stages that the Lead had previously gone through, recognized as custom stages that can be created in Bizible’s application.</p></td> 
   <td><p>MQL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ODDS_OF_CONVERSION</p></td> 
   <td><p>number(38,19)</p></td> 
   <td><p>Bizible’s algorithm of estimating if a Lead will convert based on the age and stage</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_SCORE_MODEL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>(deprecated)</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LEAD_SCORE_RESULTS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>(deprecated)</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_COOKIE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Bizible’s CookieId value that is used to populate from an integration partner to map an offline Event to a web session. Requirement: Enable Call Tracking: True</p></td> 
   <td><p>08c1063cb0a64349ad0d2d862f5cc700</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Finds whether or not the Lead that was in the system is deleted</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td colspan="1"><p>4609512587744160000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1">CUSTOM_PROPERTIES</td> 
   <td colspan="1">varchar</td> 
   <td colspan="1"><span>Custom CRM properties that Bizible has imported from the CRM in JSON format</span></td> 
   <td colspan="1">{"Lead_Type__c":"Sales Created"<span>, "Foo":"Bar"</span>}</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DUPLICATE</p></td> 
   <td colspan="1">boolean</td> 
   <td colspan="1"><p>Default is 'FALSE'. This column exists to mark any persons (leads) that exists in both&nbsp;Marketo&nbsp;and CRM as duplicate true. If there are duplicates, the&nbsp;Marketo&nbsp;Source lead will be marked IS_DUPLICATE = true&nbsp;</p></td> 
   <td colspan="1"><p>FALSE / TRUE&nbsp;</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SOURCE_SYSTEM&nbsp;</p></td> 
   <td colspan="1">varchar</td> 
   <td colspan="1"><p>Default is 'Crm'. This column exists to capture the 'source' (Marketo&nbsp;or&nbsp;Crm) from where a contact was imported into our system.&nbsp;</p></td> 
   <td colspan="1"><p>CRM /&nbsp;Marketo</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>OTHER_SYSTEM_ID&nbsp;</p></td> 
   <td colspan="1">varchar</td> 
   <td colspan="1"><p>Default is 'NULL'. This column exists to map a person from&nbsp;Marketo&nbsp;with a Contact from&nbsp;Crm. The value would be the corresponding ID (from&nbsp;Marketo&nbsp;or CRM)&nbsp;</p></td> 
   <td colspan="1"><p>1234 / 00Q0Z00001OohgTUAR&nbsp;</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_LEAD_STAGE_TRANSITIONS {#snowflakedatawarehouseschema[v3]-biz-lead-stage-transitions}

Stores all stage transitions that occur on the Lead or Contact, tying it to a touchpoint to generate funnels and velocity calculations.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique identifier for the transition</p></td> 
   <td colspan="1"><p>ST_0030Z00003FhkRXQAZ__bizible_FT-1_TP2_Person_0030Z00003FhkRXQAZ_2018-08-27:17-05-45-9474800.0d5c18c29d7b</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>EMAIL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The provided email address for the related Lead/Contact</p></td> 
   <td colspan="1"><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection#5037223138313d1032392a39323c357e333f3d" class="external-link" rel="nofollow"><span class="__cf_email__">[email&nbsp;protected]</span></a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LEAD_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Lead Id to get data such as created date.</p></td> 
   <td colspan="1"><p>00Q3100001Fx6AlEAJ</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_LEADS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CONTACT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Contact Id to get data such as created date.</p></td> 
   <td colspan="1"><p>0033100003Aq9grAAB</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>TOUCHPOINT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Touchpoint Id to get data such as channel or count.</p></td> 
   <td colspan="1"><p>TP2_Person_00Q3100001Fx6AlEAJ_2018-08-28:14-41-06-1674260.d00ceb09fbd3</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_TOUCHPOINTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>TRANSITION_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the record transitioned into the stage.</p></td> 
   <td><p>2018-08-27 16:05:34.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>STAGE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>An identifier for the stage, which can either be a position value or external Id. It will be a value if it’s a custom stage, otherwise it will be an Id from the CRM if it’s a Lead Status or Opportunity Stage.</p></td> 
   <td><p>_bizible_FT</p></td> 
   <td><br></td> 
   <td>BIZ_STAGE_DEFINITIONS.ID</td> 
  </tr> 
  <tr> 
   <td><p>STAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>An entry for the current stage and current transition that’s being recorded.</p></td> 
   <td><p>FT</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>RANK</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The numerical rank of the stage, as ordered in Bizible’s Stage Mapping settings.</p></td> 
   <td><p>1</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>INDEX</p></td> 
   <td><p>varchar(1)</p></td> 
   <td><p>For the occurrence of the stage (to be used later for Rebound Stages)</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LAST_INDEX</p></td> 
   <td><p>varchar(1)</p></td> 
   <td><br></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_PENDING</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the touchpoint is considered “pending” and not yet closed lost or closed won. This only appears for customers with Full Path.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_NON_TRANSITIONAL</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the row is tied to a milestone stage transition. For example, if there are 3 stages/entries (FT, LC, MQL) and 4 touchpoints, the 1 touchpoint without a stage on it is considered “non-transitional” so the value would be FALSE.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PREVIOUS_STAGE_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The transition date for the previous stage, according to the stage rank.</p></td> 
   <td><p>2017-11-28 21:26:44.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEXT_STAGE_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The transition date for the next stage, according to the stage rank.</p></td> 
   <td><p>2017-12-11 22:39:17.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last time the entry or record was modified</p></td> 
   <td><p>2018-08-28 15:31:10.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the record exists in the source table, primarily used for auditing.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_OPPORTUNITIES {#snowflakedatawarehouseschema[v3]-biz-opportunities}

All CRM Opportunities that are imported, along with custom Bizible fields.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>CRM Opportunity Id</p></td> 
   <td colspan="1"><p>0060Z00000o89I4QAI</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the Opportunity from the CRM</p></td> 
   <td colspan="1"><p>2018-09-04 17:00:12.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The created date of the Opportunity from the CRM</p></td> 
   <td colspan="1"><p>2018-09-04 16:07:07.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the related Account that this Opportunity is tied to</p></td> 
   <td colspan="1"><p>001i000000qbyeoAAA</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_ACCOUNTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the Opportunity</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_WON</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the Opportunity has been moved to a stage that is considered Won</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_CLOSED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the Opportunity has been moved to a stage that is considered closed, which can either be Won or Lost</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CLOSE_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The anticipated or actual Close Date set on the Opportunity</p></td> 
   <td colspan="1"><p>2019-08-28 07:00:00.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_CUSTOM_MODEL_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>A custom close date, if Close_Date is not used in the CRM, set within the Bizible App to determine which custom Close Date field is being used</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AMOUNT</p></td> 
   <td><p>number(38,8)</p></td> 
   <td><p>The deal amount that is expected or closed from the Opportunity</p></td> 
   <td><p>8988.00000000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CONVERTED_FROM_LEAD_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the related Lead that had converted into this Opportunity </p></td> 
   <td><p>00Q0Z000013eVrxUAE</p></td> 
   <td><br></td> 
   <td><p>BIZ_LEADS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>CONVERTED_FROM_LEAD_EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The email of the related Lead that had converted into this Opportunity</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection#caadb8aba2aba78aa8a3b0a3a8a6afe4a9a5a7" class="external-link" rel="nofollow"><span class="__cf_email__">[email&nbsp;protected]</span></a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PRIMARY_CONTACT_ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>If Primary Contact Role is used, the Id of the related Contact that is listed as the primary contact role</p></td> 
   <td><p>00331000038uGfhAAE</p></td> 
   <td><br></td> 
   <td><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>PRIMARY_CONTACT_EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><p>If Primary Contact Role is used, the email d of the related Contact that is listed as the primary contact role</p></td> 
   <td><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection#f49386959c9599b4969d8e9d969891da979b99" class="external-link" rel="nofollow"><span class="__cf_email__">[email&nbsp;protected]</span></a></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ODDS_OF_CONVERSION</p></td> 
   <td><p>number(38,19)</p></td> 
   <td><p>Bizible’s algorithm of estimating whether an opportunity will close based on the age and stage</p></td> 
   <td><p>0.8225108385086060000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_STAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The current stage that the Contact is sitting in, recognized as a custom stage that can be created in Bizible’s application.</p></td> 
   <td><p>DM Demo</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>BIZIBLE_STAGE_PREVIOUS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>A string of all stages that the Contact had previously gone through, recognized as custom stages that can be created in Bizible’s application.</p></td> 
   <td><p>Qualified Discovery, Demo Scheduled</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Finds whether or not the Contact that was in the system is deleted</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>4609512587744160000</p></td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td>CURRENCY_ISO_CODE</td> 
   <td>varchar</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>CURRENCY_ID</td> 
   <td>number(38,0)</td> 
   <td><br></td> 
   <td><span>4609512587744160000</span></td> 
   <td><br></td> 
   <td>BIZ_CURRENCIES.ID</td> 
  </tr> 
  <tr> 
   <td>CUSTOM_PROPERTIES</td> 
   <td>varchar</td> 
   <td><span>Custom CRM properties that Bizible has imported from the CRM in JSON format</span></td> 
   <td><span>{"Opportunity_Location__c":"Seattle", "Foo":"Bar"}</span></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_OPP_STAGE_TRANSITIONS {#snowflakedatawarehouseschema[v3]-biz-opp-stage-transitions}

Stores all stage transitions that occur on the Opportunity, tying it to a touchpoint to generate funnels and velocity calculations.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique identifier for the transition</p></td> 
   <td colspan="1"><p>ST_0060Z00000nEgjlQAC_0030Z00003IjojKQAR_Demo Scheduled-1_BAT2_0060Z00000nEgjlQAC_0030Z00003IjojKQAR_2018-06-01:19-51-38-1685390.beec556e7757</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Account Id to get data such as created date or predictive engagement score (ABM)</p></td> 
   <td colspan="1"><p>0013100001b44nTAAQ</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_ACCOUNTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>OPPORTUNITY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Opportunity Id to get data such as record type or (opportunity) stage.</p></td> 
   <td colspan="1"><p>0060Z00000nEgjlQAC</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_OPPORTUNITIES.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CONTACT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Contact Id to get data such as created date.</p></td> 
   <td colspan="1"><p>0030Z00003IjojKQAR</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>TOUCHPOINT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Lead Id to get data such as channel or count.</p></td> 
   <td colspan="1"><p>BAT2_0060Z00000nEgjlQAC_0030Z00003IjojKQAR_2018-06-01:19-51-38-1685390.beec556e7757</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_ATTRIBUTION_TOUCHPOINTS.ID</p></td> 
  </tr> 
  <tr> 
   <td><p>TRANSITION_DATE </p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the record transitioned into the stage.</p></td> 
   <td><p>2018-05-26 07:29:43.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>STAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>An entry for the current stage and current transition that’s being recorded.</p></td> 
   <td><p>Demo Scheduled</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>STAGE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>An identifier for the stage, which can either be a position value or external Id. It will be a value if it’s a custom stage, otherwise it will be an Id from the CRM if it’s a Lead Status or Opportunity Stage.</p></td> 
   <td><p><br></p></td> 
   <td><br></td> 
   <td>BIZ_STAGE_DEFINITIONS.ID</td> 
  </tr> 
  <tr> 
   <td><p>RANK</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The numerical rank of the stage, as ordered in Bizible’s Stage Mapping settings.</p></td> 
   <td><p>4</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>INDEX</p></td> 
   <td><p>varchar(1)</p></td> 
   <td><p>For the occurrence of the stage (to be used later for Rebound Stages)</p></td> 
   <td><p>1</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>LAST_INDEX</p></td> 
   <td><p>varchar(1)</p></td> 
   <td><br></td> 
   <td><p>1</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_PENDING</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the touchpoint is considered “pending” and not yet closed lost or closed won. This would appear for customers with Full Path if a record is still open.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_NON_TRANSITIONAL</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the row is tied to a milestone stage transition. For example, if there are 3 stages/entries (FT, LC, MQL) and 4 touchpoints, the 1 touchpoint without a stage on it is considered “non-transitional” so the value would be FALSE.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PREVIOUS_STAGE_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The transition date for the previous stage, according to the stage rank.</p></td> 
   <td><p>2015-07-16 17:41:49.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEXT_STAGE_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The transition date for the next stage, according to the stage rank.</p></td> 
   <td><p>2018-08-27 19:40:52.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last time the entry or record was modified</p></td> 
   <td><p>2018-08-28 03:53:33.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the record exists in the source table, primarily used for auditing.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_PAGE_VIEWS {#snowflakedatawarehouseschema[v3]-biz-page-views}

Page views from web visits with a VisitorId and is related to Biz_Session. Multiple page views can compose of a single session.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique Id for the page view</p></td> 
   <td colspan="1"><p>2018-08-19:16-49-58-24340.277d79d0167849</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>COOKIE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The recorded cookie Id at the time of the page view</p></td> 
   <td colspan="1"><p>277d79d01678498fea067c9b631bf6df</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>VISITOR_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The first cookie of the related visitor Id</p></td> 
   <td colspan="1"><p>v_277d79d01678498fea067c9b631bf6df</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_EMAIL_TO_VISITOR_IDS.VISITOR_ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SESSION_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The recorded session Id at the time of the page view</p></td> 
   <td colspan="1"><p>2018-08-19:16-49-58-24340.277d79d0167849</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_SESSIONS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>EVENT_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date and time of the page view</p></td> 
   <td colspan="1"><p>2018-08-19 16:49:58.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last time the entry or record was modified</p></td> 
   <td><p>2018-08-19 16:55:37.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CURRENT_PAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The URL of the current page view without query parameters.</p></td> 
   <td><p><span class="nolink">https://info.bizible.com/demo</span></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CURRENT_PAGE_RAW</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The URL of the current page view. The current page may contain query parameters in the URL.</p></td> 
   <td><p><span class="nolink">https://info.bizible.com/demo?hsCtaTracking=207219e9-87b6-4105-8f4b-0a3b62ae1af8%7C48060522-3aeb-4c72-8ce5-fd4b1017f069</span></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IP_ADDRESS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded IP address at the time the form was submitted</p></td> 
   <td><p>174.127.184.158</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>PageView</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>USER_AGENT_STRING</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The device and browser that the person is using at the time of the form submit.</p></td> 
   <td><p>Mozilla/5.0 (X11; Linux x86_64; rv:52.0) Gecko/20100101 Firefox/52.0</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CLIENT_SEQUENCE</p></td> 
   <td><p>varchar(1)</p></td> 
   <td><p>The order in which the page view occurred in the user’s session</p></td> 
   <td><p>1</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CLIENT_RANDOM</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>103532</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DUPLICATED</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_PROCESSED</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>REFERRER_PAGE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The URL where page view originated from without query parameters</p></td> 
   <td><p><span class="nolink">http://info.bizible.com/cmos-guide-to-b2b-marketing-attribution</span></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>REFERRER_PAGE_RAW</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The URL where the page view originated from. The referrer page may contain query parameters in the URL.</p></td> 
   <td><p><span class="nolink">http://info.bizible.com/cmos-guide-to-b2b-marketing-attribution?utm_source=linkedin&amp;utm_medium=Social&amp;utm_campaign=SU%20-%20CMO%20JT&amp;utm_content=CMOs%20Guide&amp;utm_term=lisu05091601</span></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PAGE_TITLE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The title of the page view</p></td> 
   <td><p>The CMO's Guide to B2B Marketing Attribution Download</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>EMAIL</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>-6255315750913680000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.PAGE_VIEW_KEY</p></td> 
  </tr> 
  <tr> 
   <td>CURRENT_PAGE_KEY</td> 
   <td>number(38,0)</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_URLS.ROW_KEY</td> 
  </tr> 
  <tr> 
   <td>REFERRER_PAGE_KEY</td> 
   <td>number(38,0)</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_URLS.ROW_KEY</td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_PLACEMENTS {#snowflakedatawarehouseschema[v3]-biz-placements}

Table that stores all placements downloaded from any connected ads accounts, an object from the Doubleclick integration.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique Id for the placement</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>DISPLAY_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the connected ads account for the placement</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_ACCOUNT_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the connected ads account for the placement</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Group above the Placement in any ads hierarchy</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Group above the Placement in any ads hierarchy</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the campaign for the placement</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the campaign for the placement</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_ACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the placement is still active in the ads account</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the placement has been deleted in the ads account</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the placement was first downloaded by Bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the placement</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the placement needs to get updated to get Bizible tagging</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “Placement”</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads provider for the placement</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.PLACEMENT_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_SEGMENTS {#snowflakedatawarehouseschema[v3]-biz-segments}

Table that stores all segment values that the customer has created.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique Id for the segment name</p></td> 
   <td><p>New Business</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the segment created</p></td> 
   <td><p>New Business</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>1028715376434030000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.CATEGORY_01_KEY<br>BIZ_FACTS.CATEGORY_02_KEY<br>BIZ_FACTS.CATEGORY_03_KEY<br>BIZ_FACTS.CATEGORY_04_KEY<br>BIZ_FACTS.CATEGORY_05_KEY<br>BIZ_FACTS.CATEGORY_06_KEY<br>BIZ_FACTS.CATEGORY_07_KEY<br>BIZ_FACTS.CATEGORY_08_KEY<br>BIZ_FACTS.CATEGORY_09_KEY<br>BIZ_FACTS.CATEGORY_10_KEY<br>BIZ_FACTS.CATEGORY_11_KEY<br>BIZ_FACTS.CATEGORY_12_KEY<br>BIZ_FACTS.CATEGORY_13_KEY<br>BIZ_FACTS.CATEGORY_14_KEY<br>BIZ_FACTS.CATEGORY_15_KEY</p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_SESSIONS {#snowflakedatawarehouseschema[v3]-biz-sessions}

All recorded sessions associated with a VisitorId. Multiple sessions can be associated to a single visitor.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique Id for the session</p></td> 
   <td colspan="1"><p>2016-08-01:14-24-21-9079480.33163948f0a3</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>VISITOR_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The first cookie of the related visitor Id</p></td> 
   <td colspan="1"><p>v_33163948f0a34303f2f4759e5d31a620</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_EMAIL_TO_VISITOR_IDS.VISITOR_ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>COOKIE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The recorded cookie Id from the session</p></td> 
   <td colspan="1"><p>33163948f0a34303f2f4759e5d31a620</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>EVENT_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date and time of the session</p></td> 
   <td colspan="1"><p>2016-08-01 14:24:21.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><p>2018-09-01 03:49:10.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CHANNEL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Marketing Channel - Path.” This is the channel that the touchpoint falls into, as defined in the custom channel definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>Paid Search.AdWords</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PAGE_TITLE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the web page</p></td> 
   <td colspan="1"><p>Salesforce Google Analytics | Bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LANDING_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Landing Page” This is the first landing page of the session that resulted in a touchpoint. </p></td> 
   <td colspan="1"><p><span class="nolink">http://www.bizible.com/salesforce-google-analytics</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LANDING_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Landing Page - Raw.” This is the first landing page of the session that resulted in a touchpoint. A raw landing page will contain all query parameters in the URL.</p></td> 
   <td colspan="1"><p><span class="nolink">http://www.bizible.com/salesforce-google-analytics?_bt=83558988035&amp;_bk=google%20analytics%20salesforce&amp;_bm= p&amp;gclid=CMvd5YTLo84CFUI9gQodd-kLEQ</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Referrer Page” This is the usually the external landing page immediately before the user comes onto the website. </p></td> 
   <td colspan="1"><p>https://www.google.com/</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Referrer Page - Raw.” This is the usually the external landing page immediately before the user comes onto the website. A raw referrer page may contain query parameters in the URL.</p></td> 
   <td colspan="1"><p>https://www.google.com/</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the referrer web page</p></td> 
   <td colspan="1"><p>Google</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SEARCH_PHRASE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The value that the user entered in the browser to search for and end up on the website. Depending on the keyword buys, this may or may not match the keywords purchased from the Paid Search platform.</p></td> 
   <td colspan="1"><p>bizible google salesforce</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>WEB_SOURCE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Touchpoint Source.” Used to define the source that resulted in the touchpoint. This can be parsed out from the URL from utm_source or generically set as “CRM Campaign” if it was synced from the CRM or if Bizible is able to resolve an ad, it may be values such as “Google AdWords” or “Facebook.”</p></td> 
   <td colspan="1"><p>Google AdWords</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>HAS_FORM</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the session contained a form fill</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>HAS_CHAT</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the session contained a web chat</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>HAS_EMAIL</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the session had an email address</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>HAS_CRM_ACTIVITY</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the session came from a CRM activity record</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DEVICE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The browser and operating system the user is using during the web session</p></td> 
   <td colspan="1"><p>Chrome (65.0), Windows (6.1)</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_PROVIDER</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad platform that Bizible was able to resolve from, typically one of our integration partners.</p></td> 
   <td colspan="1"><p>Google</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ads account in which the ad was resolved from.</p></td> 
   <td colspan="1"><p>aw.6601259029</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ads account in which the ad was resolved from, such as Bizible-US.</p></td> 
   <td colspan="1"><p>Bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the advertiser from the ads accounts in which the ad was resolved from, specifically from Doubleclick connection.</p></td> 
   <td colspan="1"><p>300181641</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the advertiser from the ads account in which the ad was resolved from, such as Bizible Inc.</p></td> 
   <td colspan="1"><p>Bizible Marketing Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the site from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>1695651</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_SITES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The site name from the ads account in which the ad was resolved from, such as Quantcast or TechCrunch. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>Quora.com</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_UNIQUE_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id placement from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>120839827</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_PLACEMENTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The placement name from the ads account in which the ad was resolved from, such as 300x250 or Home Page Takeover. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>roadblock</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the campaign from the ads account in which the ad was resolved from.</p></td> 
   <td colspan="1"><p>aw.6601259029.321586235</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The campaign name from the ads account in which the ad was resolved from, such as Winter Promotion 2018 or Planning Your Budget Webinar.</p></td> 
   <td colspan="1"><p>Salesforce</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ad group from the ads account in which the ad was resolved from. This only applies to Google Adwords.</p></td> 
   <td colspan="1"><p>aw.6601259029.321586235.23182235435</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad group name from the ads account in which the ad was resolved from. This only applies to Google AdWords.</p></td> 
   <td colspan="1"><p>Salesforce - Google Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The id of the ad from the ads account in which the ad was resolved from. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The id of the creative from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>aw.6601259029.321586235.23182235435.83558988035</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_CREATIVES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The creative name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Integrate GA &amp; Salesforce</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_1</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The first line of the creative from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Integrate Salesforce &amp; Analytics To</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_2 &nbsp;&nbsp;</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The second line of the creative from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Optimize for Revenue. Learn How.</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESTINATION_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The landing page that clicks through from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p><span class="nolink">http://www.bizible.com/salesforce-google-analytics</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DISPLAY_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The friendly URL name that’s shown on the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Bizible.com/Salesforce-for-GA</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the keyword that was purchased from the Paid Search buy, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search</p></td> 
   <td colspan="1"><p>aw.6601259029.321586235.23182235435.35934468937</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_KEYWORDS.ID</td> 
  </tr> 
  <tr> 
   <td><p>KEYWORD_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The keyword that was purchased from the Paid Search buy, which is pulled from the ads account in which the ad was resolved from, such as Software Discount or Annual Budget. This applies to Google AdWords and Bing Ads (search)</p></td> 
   <td><p>google analytics salesforce</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>KEYWORD_MATCH_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The type of match that was found between the search phrase and the purchased keyword, such as “broad” or “exact”</p></td> 
   <td><p>Phrase</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CAMPAIGN</p></td> 
   <td><p>varchar</p></td> 
   <td><p>This is parsed out from the URL from utm_campaign</p></td> 
   <td><p>SU - ABC Accounts - Paid Media Skills</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>SOURCE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>This is parsed out from the URL from utm_source</p></td> 
   <td><p>linkedin</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MEDIUM</p></td> 
   <td><p>varchar</p></td> 
   <td><p>This is parsed out from the URL from utm_medium</p></td> 
   <td><p>Social</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>TERM</p></td> 
   <td><p>varchar</p></td> 
   <td><p>This is parsed out from the URL from utm_term</p></td> 
   <td><p>lisu07261601</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CONTENT</p></td> 
   <td><p>varchar</p></td> 
   <td><p>This is parsed out from the URL from utm_content</p></td> 
   <td><p>2016 AdWords Benchmark Report</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>CITY </p></td> 
   <td><p>varchar</p></td> 
   <td><p>From the javascript and IP address, the detected city that the user was in during the session. For example, Seattle or Vancouver.</p></td> 
   <td><p>Seattle</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>REGION</p></td> 
   <td><p>varchar</p></td> 
   <td><p>From the javascript and IP address, the detected city that the user was in during the session. For example, Washington or British Columbia.</p></td> 
   <td><p>Washington</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>COUNTRY</p></td> 
   <td><p>varchar</p></td> 
   <td><p>From the javascript and IP address, the detected city that the user was in during the session. For example, United States or Canada.</p></td> 
   <td><p>United States</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ISP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The internet service provider of the user</p></td> 
   <td><p>AT&amp;T U-verse</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IP_ADDRESS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The recorded IP address at the time the session</p></td> 
   <td><p>174.127.184.158</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Determines if this session was merged with another and should be deleted. </p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p>-251659132606672000</p></td> 
   <td><br></td> 
   <td><p>BIZ_FACTS.SESSION_KEY</p></td> 
  </tr> 
  <tr> 
   <td>LANDING_PAGE_KEY</td> 
   <td><span>number(38,0)</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>REFERRER_PAGE_KEY</td> 
   <td><span>number(38,0)</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>ACCOUNT_ROW_KEY</td> 
   <td><span>number(38,0)</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>ADVERTISER_ROW_KEY</td> 
   <td><span>number(38,0)</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>SITE_ROW_KEY</td> 
   <td><span>number(38,0)</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">PLACEMENT_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CAMPAIGN_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_GROUP_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CREATIVE_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">KEYWORD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_SITES {#snowflakedatawarehouseschema[v3]-biz-sites}

Table that stores all sites downloaded from any connected ads accounts, an object from the Doubleclick integration.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique identifier for the site</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the connected ads account for the site</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_ACCOUNT_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the connected ads account for the site</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The Id of the advertiser for the site, specifically for Doubleclick.</p></td> 
   <td><p>300181641</p></td> 
   <td><br></td> 
   <td>BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td><p>ADVERTISER_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the advertiser for the site, specifically for Doubleclick.</p></td> 
   <td><p>Bizible Marketing Analytics</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Group above the Site in any ads hierarchy</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>Expected to be NULL since there is no Ad Group above the Site in any ads hierarchy</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the campaign for the site</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the campaign for the site</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_ACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the site is still active in the ads account</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the site has been deleted in the ads account</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the site was first downloaded by Bizible</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the site</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the site needs to get updated to get Bizible tagging</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “Site”</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads provider for the site</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td><p><br></p></td> 
   <td><br></td> 
   <td><span>BIZ_FACTS.SITE_KEY</span></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_SITE_LINKS {#snowflakedatawarehouseschema[v3]-biz-site-links}

Table that stores all site links downloaded from any connected ads accounts.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique Id for the site link</p></td> 
   <td><p>aw.6601259029.285077795.1654234342</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>DISPLAY_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>1654234342</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ID of the connected ads account for the site link</p></td> 
   <td colspan="1"><p>aw.6601259029</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the connected ads account for the site link</p></td> 
   <td colspan="1"><p>Bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the advertiser for the site link, specifically for Doubleclick.</p></td> 
   <td colspan="1"><p>300181641</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the advertiser for the site link, specifically for Doubleclick.</p></td> 
   <td colspan="1"><p>Bizible Marketing Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the ad group for the site link</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td>BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_GROUP_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ad group for the site link</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_UNIQUE_ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The ID of the campaign for the site link</p></td> 
   <td><p>aw.6601259029.285077795</p></td> 
   <td><br></td> 
   <td>BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td><p>AD_CAMPAIGN_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the campaign for the site link</p></td> 
   <td><p>Brand</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_ACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the site link is still active in the ads account</p></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the site link has been deleted in the ads account</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><p>2018-08-02 06:36:50.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>FIRST_IMPORTED</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The date that the site link was first downloaded by Bizible</p></td> 
   <td><p>2018-08-02 06:36:50.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the site link</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>NEEDS_UPDATE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the site link needs to get updated to get Bizible tagging</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>GROUPING_KEY</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p>aw.6601259029.285077795</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ENTITY_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The main object or entity for this table. In this case, “SiteLink”</p></td> 
   <td><p>SiteLink</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PROVIDER_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the ads provider for the site link </p></td> 
   <td><p>AdWords</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>URL_CURRENT</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><p><a href="http://bizible.com/b2b-marketing-attribution?_bt" class="external-link" rel="nofollow">http://bizible.com/b2b-marketing-attribution?_bt</a> =</p><p>{creative}&amp;_bk={keyword}&amp;_bm={matchType}</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>URL_OLD</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>URL_REQUESTED</p></td> 
   <td><p>varchar</p></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_STAGE_DEFINITIONS {#snowflakedatawarehouseschema[v3]-biz-stage-definitions}

Lists all Lead Statuses and Opportunity Stages from the CRM, as well as any custom stages defined in Bizible Settings.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID </p></td> 
   <td><p>varchar</p></td> 
   <td><p>A unique identifier for the stage</p></td> 
   <td><p>01J3100000QE753EAD</p></td> 
   <td>X</td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>MODIFIED_DATE</p></td> 
   <td><p>timestamp_ntz</p></td> 
   <td><p>The last modified date of the row</p></td> 
   <td><p>2018-08-22 17:27:27.000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>STAGE_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The name of the stage</p></td> 
   <td><p>Verbal</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_INACTIVE</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_IN_CUSTOM_MODEL</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the stage has been selected to track in the custom attribution model</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_BOOMERANG</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the stage has been selected to track as a boomerang stage</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_TRANSITION_TRACKING</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>STAGE_STATUS</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The status of the stage, whether it’s an Open, Lost, or Won stage</p></td> 
   <td><p>Open</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_FROM_SALESFORCE</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the stage is pulled from Salesforce</p></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DEFAULT</p></td> 
   <td><p>boolean</p></td> 
   <td><br></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>RANK</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><p>The numerical rank of the stage that can be used to sort all stages</p></td> 
   <td><p>53</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the stage has been deleted</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_TOUCHPOINTS {#snowflakedatawarehouseschema[v3]-biz-touchpoints}

All touchpoints that are associated with a Lead and/or Contact. This table will be empty if Lead Touchpoints or Contact Touchpoints are disabled.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique Id for the touchpoint record</p></td> 
   <td colspan="1"><p>TP2_Person_00Q0Z000013e2PYUAY_2018-08-27:20-04-40-5655690.1ee8567c175a</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><p>2018-08-29 22:29:30.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>EMAIL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The known email address that’s tied to this touchpoint via a Lead or Contact</p></td> 
   <td colspan="1"><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CONTACT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Biz_Contacts table to select columns such as Created Date</p></td> 
   <td colspan="1"><p>0030Z00003Fhe7qQAB</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_CONTACTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Biz_Accounts table to select columns such as Website or Engagement Rating</p></td> 
   <td colspan="1"><p>0013100001lSLScAAO</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_ACCOUNTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LEAD_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Biz_Leads table to select columns such as Created Date</p></td> 
   <td colspan="1"><p>00Q0Z000013e2PYUAY</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_LEADS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>UNIQUE_ID_PERSON</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The parent person record that relates to a Lead or Contact</p></td> 
   <td colspan="1"><p>Person_00Q0Z000013e2PYUAY</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>USER_TOUCHPOINT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A lookup to the Biz_User_Touchpoints table to select columns such as session_id</p></td> 
   <td colspan="1"><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection" class="__cf_email__">[email&nbsp;protected]</a>_2018-08-29:18-14-53-8102030.10df92cbb414</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_USER_TOUCHPOINTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1">VISITOR_ID</td> 
   <td colspan="1">varchar</td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_EMAIL_TO_VISITOR_IDS.VISITOR_ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>TOUCHPOINT_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date of the recorded touchpoint, which is the date that the session occurred</p></td> 
   <td colspan="1"><p>2018-08-27 20:04:40.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MARKETING_TOUCH_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Touchpoint Type.” This records the type of activity, whether it was a Web Visit, Web Form, Web Chat, Phone Call, [CRM] Campaign, or [CRM] Activity</p></td> 
   <td colspan="1"><p>Web Form</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CHANNEL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Marketing Channel - Path.” This is the channel that the touchpoint falls into, as defined in the custom channel definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>Social.LinkedIn</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY1</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 1st Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>ABC, or NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY2</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 2nd Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>Yes, or NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY3</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 3rd Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>Other, or NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY4</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 4th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>Partner, or NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY5</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 5th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY6</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 6th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY7</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 7th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY8</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 8th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY9</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 9th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY10</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 10th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY11</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 11th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY12</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 12th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY13</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 13th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY14</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 14th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CATEGORY15</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Segments.” This is the segment value for the 15th Category that the touchpoint falls into, as defined in the segment definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>NULL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>BROWSER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected browser that the user was on during the session. For example, Chrome or Internet Explorer.</p></td> 
   <td colspan="1"><p>Chrome</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>BROWSER_VERSION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected version of the browser that the user was on during the session. For example, Chrome or Internet Explorer.</p></td> 
   <td colspan="1"><p>68</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLATFORM_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected platform that the user was on during the session. For example, Mac or Windows.</p></td> 
   <td colspan="1"><p>Windows</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLATFORM_VERSION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected version of the platform that the user was on during the session. For example, Mac or Windows.</p></td> 
   <td colspan="1"><p>6.1</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LANDING_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Landing Page.” This is the first landing page of the session that resulted in a touchpoint. </p></td> 
   <td colspan="1"><p><span class="nolink">https://info.bizible.com/definitive-guide-to-pipeline-marketing</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LANDING_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Landing Page - Raw.” This is the first landing page of the session that resulted in a touchpoint. A raw landing page will contain all query parameters in the URL.</p></td> 
   <td colspan="1"><p><span class="nolink">https://info.bizible.com/definitive-guide-to-pipeline-marketing?utm_source=linkedin&amp;utm_medium=Social&amp;utm_campaign=SU_COM_Demand_ Skills&amp;utm_content=DGPM&amp;utm_term=lisu03151846&amp;_bl=66452504</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Referrer Page.” This is the usually the external landing page immediately before the user comes onto the website.</p></td> 
   <td colspan="1"><p><span class="nolink">https://www.linkedin.com/feed</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Referrer Page - Raw.” This is the usually the external landing page immediately before the user comes onto the website. A raw referrer page may contain query parameters in the URL.</p></td> 
   <td colspan="1"><p><span class="nolink">https://www.linkedin.com/feed</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FORM_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Form - URL.” This is the first form that is recorded in a session that resulted in a touchpoint. Subsequent form submissions will not show up in the Biz_Attribution_Touchpoints table, but rather in the Biz_Form_Submits table.</p></td> 
   <td colspan="1"><p><span class="nolink">https://info.bizible.com/demo</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FORM_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date that the form submission occurred.</p></td> 
   <td colspan="1"><p><span class="nolink">https://info.bizible.com/demo?hsCtaTracking=98adcc2f-afe2-40c4-9d79-40dcc41663ee%7C3cfaa909-39cb-4f5d-93eb-be05de6b0180</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CITY </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, Seattle or Vancouver.</p></td> 
   <td colspan="1"><p>New York</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REGION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, Washington or British Columbia.</p></td> 
   <td colspan="1"><p>New York</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>COUNTRY</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, United States or Canada.</p></td> 
   <td colspan="1"><p>United States</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MEDIUM</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Used to define the medium that resulted in the touchpoint. This can either be parsed out from the URL from utm_medium or if Bizible is able to resolve an ad, it may be values such as “cpc” or “display.”</p></td> 
   <td colspan="1"><p>Social</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>WEB_SOURCE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Touchpoint Source.” Used to define the source that resulted in the touchpoint. This can be parsed out from the URL from utm_source or generically set as “CRM Campaign” if it was synced from the CRM or if Bizible is able to resolve an ad, it may be values such as “Google AdWords” or “Facebook.”</p></td> 
   <td colspan="1"><p>LinkedIn</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SEARCH_PHRASE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The value that the user entered in the browser to search for and end up on the website. Depending on the keyword buys, this may or may not match the keywords purchased from the Paid Search platform.</p></td> 
   <td colspan="1"><p>bizible attribution</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_PROVIDER</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad platform that Bizible was able to resolve from, typically one of our integration partners.</p></td> 
   <td colspan="1"><p>LinkedIn</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ads account in which the ad was resolved from.</p></td> 
   <td colspan="1"><p>li.502664737</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ads account in which the ad was resolved from, such as Bizible-US.</p></td> 
   <td colspan="1"><p>Bizible SC 2016_14605342_3/7-3/31/16</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the advertiser from the ads accounts in which the ad was resolved from, specifically for Doubleclick connections.</p></td> 
   <td colspan="1"><p>300181641</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the advertiser from the ads account in which the ad was resolved from, specifically for Doubleclick connections.</p></td> 
   <td colspan="1"><p>Bizible Marketing Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the site from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>1695651</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_SITES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The site name from the ads account in which the ad was resolved from, such as Quantcast or TechCrunch. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>Quora.com</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_UNIQUE_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id placement from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>120839827</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_PLACEMENTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The placement name from the ads account in which the ad was resolved from, such as 300x250 or Home Page Takeover. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>roadblock</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the campaign from the ads account in which the ad was resolved from.</p></td> 
   <td colspan="1"><p>li.502664737.138949954</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The campaign name from the ads account in which the ad was resolved from, such as Winter Promotion 2018 or Planning Your Budget Webinar.</p></td> 
   <td colspan="1"><p>SU - COM Accounts - Demand Skills</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ad group from the ads account in which the ad was resolved from. This only applies to Google Adwords.</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad group name from the ads account in which the ad was resolved from. This only applies to Google AdWords.</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The id of the ad from the ads account in which the ad was resolved from. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The id of the creative from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>li.502664737.138949954.66452504</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_CREATIVES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The creative name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>lisu03151846</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_1</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The first line of the creative from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Lead gen is dead </p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_2 &nbsp;&nbsp;</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The second line of the creative from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Download the definitive guide to pipeline marketing: <span class="nolink">https://lnkd.in/e9xYj5M</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESTINATION_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The landing page that clicks through from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p><span class="nolink">https://image-store.slidesharecdn.com/d29165c0-1e0b-4ffc-a494-d2c77e7cd4a6-large.jpeg</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DISPLAY_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The friendly URL name that’s shown on the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>bizible.com/guide</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the keyword that was purchased from the Paid Search buy, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search</p></td> 
   <td colspan="1"><p>__GAId__lisu03151846</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_KEYWORDS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The keyword that was purchased from the Paid Search buy, which is pulled from the ads account in which the ad was resolved from, such as Software Discount or Annual Budget. This applies to Google AdWords and Bing Ads (search)</p></td> 
   <td colspan="1"><p>lisu03151846</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_MATCH_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The type of match that was found between the search phrase and the purchased keyword, such as “broad” or “exact”</p></td> 
   <td colspan="1"><p>Broad</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_FIRST_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the first touch of the opportunity journey</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_LEAD_CREATION_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the lead creation &nbsp;touch of the opportunity journey</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_OPP_CREATION_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the opportunity creation touch of the opportunity journey. Because this is the lead model, this is expected to be 0.</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_CLOSED_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the closed touch of the opportunity journey. Because this is the lead model, this is expected to be 0.</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>STAGES_TOUCHED</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The stages that the touchpoint has gone through</p></td> 
   <td colspan="1"><p>Open, MQL</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_FORM_SUBMISSION_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint had a form fill during the session</p></td> 
   <td colspan="1"><p>TRUE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_IMPRESSION_TOUCH</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not this touchpoint is treated as the first impression touch of the opportunity journey</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FIRST_CLICK_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s a first touch (See Is_First_Touch)</p></td> 
   <td colspan="1"><p>100</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LAST_ANON_CLICK_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s a lead creation touch (See Is_Last_Anon_Click_Percentage)</p></td> 
   <td colspan="1"><p>100</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>U_SHAPE_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a u-shaped touch (See Is_First_Touch and Is_Lead_Creation_Touch)</p></td> 
   <td colspan="1"><p>100</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>W_SHAPE_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a w-shaped touch (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, and Is_Opp_Creation_Touch). Because this is the lead model, this is expected to be 0.</p></td> 
   <td colspan="1"><p>0</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FULL_PATH_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19) </p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a full path model (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, Is_Opp_Creation_Touch, Is_Closed_Touch). Because this is the lead model, this is expected to be 0.</p></td> 
   <td colspan="1"><p>0</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CUSTOM_MODEL_PERCENTAGE</p></td> 
   <td colspan="1"><p>number(22,19)</p></td> 
   <td colspan="1"><p>The calculated percentage that gets allocated to this touchpoint because it’s part of a custom model (See Is_First_Touch, &nbsp;Is_Lead_Creation_Touch, Is_Opp_Creation_Touch, Is_Closed_Touch, Stages Touch). Because this is the lead model, this is expected to be 0.</p></td> 
   <td colspan="1"><p>0</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IS_DELETED</p></td> 
   <td colspan="1"><p>boolean</p></td> 
   <td colspan="1"><p>Whether or not the record was deleted, used for diagnostics and auditing.</p></td> 
   <td colspan="1"><p>FALSE</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><p>The key that relates this table to the BIZ_FACTS table to fetch all the metrics</p></td> 
   <td colspan="1"><p>-9004910726709710000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_FACTS.TP_KEY</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CONTACT_ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>8817975702393610000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LEAD_ROW_KEY</p></td> 
   <td colspan="1"><p>number(38,0)</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>-2198155202365030000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">LANDING_PAGE_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">REFERRER_PAGE_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">FORM_PAGE_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ACCOUNT_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">ADVERISER_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">SITE_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">PLACEMENT_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">CAMPAIGN_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_ROW_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1">AD_GROUP_KEY</td> 
   <td colspan="1"><span>number(38,0)</span></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td>CREATIVE_ROW_KEY</td> 
   <td><span>number(38,0)</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>KEYWORD_ROW_KEY</td> 
   <td><span>number(38,0)</span></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_URLS {#snowflakedatawarehouseschema[v3]-biz-urls}

A table of all recognized URLs from landing pages or referrer pages or page visits, aggregated into a single table.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td><p>ID</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The full URL, from landing pages or referrer pages or page visits</p></td> 
   <td><p><span class="nolink">https://www.bizible.com/blog/strategic-marketing-plangoals</span></p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>SCHEME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The secure communication of the web page over the network, whether it’s HTTP or HTTPS</p></td> 
   <td><p>https</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>HOST</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The domain of the URL, with any subdomains</p></td> 
   <td><p>www.bizible.com</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PORT</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The port from an internet host, optional in a URL</p></td> 
   <td><p>NULL</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>PATH</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The part of the URL that points to a specific location on the host.</p></td> 
   <td><p>/blog/strategic-marketing-plangoals</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><br></td> 
   <td><p>5686109553536636820</p></td> 
   <td>X</td> 
   <td><p><br></p></td> 
  </tr> 
 </tbody> 
</table>

#### BIZ_USER_TOUCHPOINTS {#snowflakedatawarehouseschema[v3]-biz-user-touchpoints}

Any touchpoint recorded that can be tied to an email, so it can be a web visit, web form, chat, or offline event.

<table class="wrapped confluenceTable"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Column</th> 
   <th><p>Data Type</p></th> 
   <th>Description</th> 
   <th>Sample Data</th> 
   <th>Primary Key</th> 
   <th>Foreign Keys/Joins</th> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>A unique Id for the user touchpoint</p></td> 
   <td colspan="1"><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection#016d686d6d68606f4163687b68636d642f626e6c" class="external-link" rel="nofollow"><span class="__cf_email__">[email&nbsp;protected]</span></a>_2018-01-05:16-47-02-8803320.ddf67c101f58</p></td> 
   <td colspan="1">X</td> 
   <td colspan="1"><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MODIFIED_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The last modified date of the row</p></td> 
   <td colspan="1"><p>2018-09-05 23:30:53.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>EMAIL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The email address that this Touchpoint is created from</p></td> 
   <td colspan="1"><p><a href="http://docs.marketo.com/cdn-cgi/l/email-protection#fb97929797929a95bb9992819299979ed5989496" class="external-link" rel="nofollow"><span class="__cf_email__">[email&nbsp;protected]</span></a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SESSION_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the related Session that this Touchpoint is created from</p></td> 
   <td colspan="1"><p>2018-01-05:16-47-02-8803320.ddf67c101f58</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_SESSIONS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_MEMBER_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the related Campaign Member that this Touchpoint is created from</p></td> 
   <td colspan="1"><p>00v0Z00001VTgv1QAD</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_CAMPAIGN_MEMBERS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CRM_EVENT_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the related Event that this Touchpoint is created from</p></td> 
   <td colspan="1"><p>00U0Z00000pCZmyUAG</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_CRM_EVENTS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CRM_TASK_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the related Task that this Touchpoint is created from</p></td> 
   <td colspan="1"><p>00T0Z00004Qbd1jUAB</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_CRM_TASKS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>IMPRESSION_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the related Impression that this Touchpoint is created from</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><p>BIZ_IMPRESSIONS.ID</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>TOUCHPOINT_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date of the recorded touchpoint, which is the date that the session occurred</p></td> 
   <td colspan="1"><p>2018-01-05 16:47:02.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MARKETING_TOUCH_TYPE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Touchpoint Type.” This records the type of activity, whether it was a Web Visit, Web Form, Web Chat, Phone Call, [CRM] Campaign, or [CRM] Activity</p></td> 
   <td colspan="1"><p>Web Form</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CHANNEL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Marketing Channel - Path.” This is the channel that the touchpoint falls into, as defined in the custom channel definitions within the Bizible App.</p></td> 
   <td colspan="1"><p>Social.LinkedIn</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>BROWSER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected browser that the user was on during the session. For example, Chrome or Internet Explorer.</p></td> 
   <td colspan="1"><p>Firefox</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>BROWSER_VERSION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected version of the browser that the user was on during the session. For example, Chrome or Internet Explorer.</p></td> 
   <td colspan="1"><p>33</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLATFORM_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected platform that the user was on during the session. For example, Mac or Windows.</p></td> 
   <td colspan="1"><p>Mac</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLATFORM_VERSION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected version of the platform that the user was on during the session. For example, Mac or Windows.</p></td> 
   <td colspan="1"><p>10_12</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LANDING_PAGE </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Landing Page.” This is the first landing page of the session that resulted in a touchpoint. </p></td> 
   <td colspan="1"><p><a href="https://www.bizible.com/blog/budget-and-planning-maturity-model-b2b-marketing" class="external-link" rel="nofollow">https://www.bizible.com/blog/budget-and-planning-maturity-model-b2b-marketing</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>LANDING_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Landing Page - Raw.” This is the first landing page of the session that resulted in a touchpoint. A raw landing page will contain all query parameters in the URL.</p></td> 
   <td colspan="1"><p><span class="nolink"><a href="https://www.bizible.com/blog/budget-and-planning-maturity-model-b2b-marketing?utm_source=feedburner&amp;utm_medium=feed&amp;utm_campaign=Feed%3A+" class="external-link" rel="nofollow">https://www.bizible.com/blog/budget-and-planning-maturity-model-b2b-marketing?utm_source=feedburner&amp;utm_medium=feed&amp;utm_campaign=Feed%3A+</a> bizible+%28Bizible%27s+Pipeline+Marketing+Blog%29</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_PAGE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Referrer Page.” This is the usually the external landing page immediately before the user comes onto the website. </p></td> 
   <td colspan="1"><p><a href="https://www.google.com/" class="external-link" rel="nofollow">https://www.google.com/</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REFERRER_PAGE_RAW</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Referrer Page - Raw.” This is the usually the external landing page immediately before the user comes onto the website. A raw referrer page may contain query parameters in the URL.</p></td> 
   <td colspan="1"><p><a href="https://www.google.com/" class="external-link" rel="nofollow">https://www.google.com/</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FORM_PAGE </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Form Page” This is the first form that is recorded in a session that resulted in a touchpoint. Subsequent form submissions will not show up in the Biz_Attribution_Touchpoints table, but rather in the Biz_Form_Submits table.</p></td> 
   <td colspan="1"><p><a href="http://info.bizible.com/adwords-for-lead-generation" class="external-link" rel="nofollow">http://info.bizible.com/adwords-for-lead-generation</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FORM_PAGE_RAW </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Form Page - Raw.” This is the first form that is recorded in a session that resulted in a touchpoint. Subsequent form submissions will not show up in the Biz_Attribution_Touchpoints table, but rather in the Biz_Form_Submits table. A raw form page may contain query parameters in the URL.</p></td> 
   <td colspan="1"><p><span class="nolink"><a href="http://info.bizible.com/adwords-for-lead-generation?utm_source=linkedin&amp;utm_medium=paid&amp;utm_content=sfskill&amp;utm" class="external-link" rel="nofollow">http://info.bizible.com/adwords-for-lead-generation?utm_source=linkedin&amp;utm_medium=paid&amp;utm_content=sfskill&amp;utm</a> _campaign=Content%20-%20AdWords%20Guide</span></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>FORM_DATE</p></td> 
   <td colspan="1"><p>timestamp_ntz</p></td> 
   <td colspan="1"><p>The date that the form submission occurred.</p></td> 
   <td colspan="1"><p>2015-06-03 17:49:10.000</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CITY </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, Seattle or Vancouver.</p></td> 
   <td colspan="1"><p>Oakland</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>REGION</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, Washington or British Columbia.</p></td> 
   <td colspan="1"><p>California</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>COUNTRY</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>From the javascript and IP address, the detected city that the user was in during the session. For example, United States or Canada.</p></td> 
   <td colspan="1"><p>United States</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>MEDIUM</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Used to define the medium that resulted in the touchpoint. This can either be parsed out from the URL from utm_medium or if Bizible is able to resolve an ad, it may be values such as “cpc” or “display.”</p></td> 
   <td colspan="1"><p>paid</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>WEB_SOURCE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>Referred to in the CRM as “Touchpoint Source.” Used to define the source that resulted in the touchpoint. This can be parsed out from the URL from utm_source or generically set as “CRM Campaign” if it was synced from the CRM or if Bizible is able to resolve an ad, it may be values such as “Google AdWords” or “Facebook.”</p></td> 
   <td colspan="1"><p>linkedin</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SEARCH_PHRASE</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The value that the user entered in the browser to search for and end up on the website. Depending on the keyword buys, this may or may not match the keywords purchased from the Paid Search platform.</p></td> 
   <td colspan="1"><p>bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_PROVIDER</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad platform that Bizible was able to resolve from, typically one of our integration partners.</p></td> 
   <td colspan="1"><p>Google</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ads account in which the ad was resolved from.</p></td> 
   <td colspan="1"><p>aw.6601259029</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_ACCOUNTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ACCOUNT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the ads account in which the ad was resolved from, such as Bizible-US.</p></td> 
   <td colspan="1"><p>Bizible</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_UNIQUE_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the advertiser from the ads accounts in which the ad was resolved from, specifically for Doubleclick connections.</p></td> 
   <td colspan="1"><p>300181641</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_ADVERTISERS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>ADVERTISER_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The name of the advertiser from the ads account in which the ad was resolved from, specifically for Doubleclick connections.</p></td> 
   <td colspan="1"><p>Bizible Marketing Analytics</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the site from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>1695651</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_SITES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>SITE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The site name from the ads account in which the ad was resolved from, such as Quantcast or TechCrunch. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p><a href="http://Quora.com" class="external-link" rel="nofollow">Quora.com</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_UNIQUE_ID </p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id placement from the ads account in which the ad was resolved from. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>120839827</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_PLACEMENTS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>PLACEMENT_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The placement name from the ads account in which the ad was resolved from, such as 300x250 or Home Page Takeover. This only applies to Doubleclick Campaign Manager.</p></td> 
   <td colspan="1"><p>roadblock</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the campaign from the ads account in which the ad was resolved from.</p></td> 
   <td colspan="1"><p>aw.6601259029.208548635</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_CAMPAIGNS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CAMPAIGN_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The campaign name from the ads account in which the ad was resolved from, such as Winter Promotion 2018 or Planning Your Budget Webinar.</p></td> 
   <td colspan="1"><p>Brand</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the ad group from the ads account in which the ad was resolved from. This only applies to Google Adwords.</p></td> 
   <td colspan="1"><p>aw.6601259029.208548635.16750166675</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD_GROUPS.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_GROUP_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad group name from the ads account in which the ad was resolved from. This only applies to Google AdWords.</p></td> 
   <td colspan="1"><p>Brand - Core</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The id of the ad from the ads account in which the ad was resolved from. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_AD.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>AD_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The ad name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Doubleclick Campaign Manager and Facebook (display).</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The id of the creative from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>aw.6601259029.208548635.16750166675.195329631298</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_CREATIVES.ID</td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_NAME</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The creative name from the ads account in which the ad was resolved from, such as Winter Promo - Green button or Budget Webinar - sidebar. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Bizible Official Site</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_1</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The first line of the creative from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Revenue Planning &amp; Attribution</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESCRIPTION_2 &nbsp;&nbsp;</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The second line of the creative from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p>Learn why 250+ companies choose Bizible for marketing attribution. Get a demo!</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DESTINATION_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The landing page that clicks through from the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p><a href="http://info.bizible.com/demo" class="external-link" rel="nofollow">http://info.bizible.com/demo</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>CREATIVE_DISPLAY_URL</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The friendly URL name that’s shown on the search ad, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search).</p></td> 
   <td colspan="1"><p><a href="http://bizible.com/demo" class="external-link" rel="nofollow">bizible.com/demo</a></p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>KEYWORD_UNIQUE_ID</p></td> 
   <td colspan="1"><p>varchar</p></td> 
   <td colspan="1"><p>The Id of the keyword that was purchased from the Paid Search buy, which is pulled from the ads account in which the ad was resolved from. This applies to Google AdWords and Bing Ads (search</p></td> 
   <td colspan="1"><p>aw.6601259029.208548635.16750166675.46267805426</p></td> 
   <td colspan="1"><br></td> 
   <td colspan="1">BIZ_KEYWORDS.ID</td> 
  </tr> 
  <tr> 
   <td><p>KEYWORD_NAME</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The keyword that was purchased from the Paid Search buy, which is pulled from the ads account in which the ad was resolved from, such as Software Discount or Annual Budget. This applies to Google AdWords and Bing Ads (search)</p></td> 
   <td><p>[bizible]</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>KEYWORD_MATCH_TYPE</p></td> 
   <td><p>varchar</p></td> 
   <td><p>The type of match that was found between the search phrase and the purchased keyword, such as “broad” or “exact”</p></td> 
   <td><p>Exact</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_FORM_SUBMISSION_TOUCH</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not this touchpoint had a form fill during the session</p></td> 
   <td><p>TRUE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_IMPRESSION_TOUCH</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not this touchpoint is treated as the first impression touch of the opportunity journey</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>IS_DELETED</p></td> 
   <td><p>boolean</p></td> 
   <td><p>Whether or not the record was deleted, used for diagnostics and auditing.</p></td> 
   <td><p>FALSE</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td><p>ROW_KEY</p></td> 
   <td><p>number(38,0)</p></td> 
   <td><br></td> 
   <td><p>-5269090762570690000</p></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
 </tbody> 
</table>

#### Sample Queries {#snowflakedatawarehouseschema[v3]-samplequeries}

##### How many Leads had sessions from Paid Search in 1-month? {#snowflakedatawarehouseschema[v3]-howmanyleadshadsessionsfrompaidsearchin1-month?}

```
select
```

```
sum
```

```
(tp.first_click_percentage)
```

```
from
```

```
biz_leads leads
```

```
    
```

```
join
```

```
biz_touchpoints tp
```

```
        
```

```
on
```

```
leads.Id = tp.Lead_Id
```

```
    
```

```
join
```

```
biz_user_touchpoints utp
```

```
        
```

```
on
```

```
tp.User_Touchpoint_Id = utp.Id
```

```
where
```

```
utp.touchpoint_date >=
```

```
'2017-08-01'
```

```
and
```

```
utp.touchpoint_date <
```

```
'2017-09-01'
```

```
and
```

```
utp.Channel
```

```
like
```

```
'Paid Search%'
```

##### How many sessions are there per Opportunity in Custom Model? {#snowflakedatawarehouseschema[v3]-howmanysessionsarethereperopportunityincustommodel?}

```
select top
```

```
100
```

```
opps.Id, count(utp.*)
```

```
from biz_opportunities opps
```

```
    
```

```
inner join biz_attribution_touchpoints tp
```

```
        
```

```
on opps.Id = tp.Opportunity_Id
```

```
    
```

```
inner join biz_user_touchpoints utp
```

```
        
```

```
on tp.User_Touchpoint_Id = utp.Id
```

```
where tp.Custom_Model_Percentage >
```

```
0
```

```
group by opps.Id
```

##### What is the revenue per channel in Custom model per month? {#snowflakedatawarehouseschema[v3]-whatistherevenueperchannelincustommodelpermonth?}

```
select tp.Channel, extract(year from tp.Touchpoint_date) as year, extract(month from tp.Touchpoint_date) as month, sum(opps.Amount * tp.Custom_Model_percentage) as amountWithAttribution
```

```
from biz_opportunities opps
```

```
    
```

```
join biz_attribution_touchpoints tp
```

```
        
```

```
on opps.Id = tp.Opportunity_Id
```

```
group by tp.Channel, extract(year from tp.Touchpoint_date), extract(month from tp.Touchpoint_date) order by
```

```
1
```

```
,
```

```
2
```

```
,
```

```
3
```

##### How many anonymous sessions by channel? {#snowflakedatawarehouseschema[v3]-howmanyanonymoussessionsbychannel?}

```
select channel, count
```

```
from biz_sessions
```

```
group by channel
```

##### What is the top landing page for Leads? {#snowflakedatawarehouseschema[v3]-whatisthetoplandingpageforleads?}

```
select top
```

```
5
```

```
landing_page, count
```

```
from biz_sessions
```

```
group by landing_page
```

