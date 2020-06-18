---
unique-page-id: 35586134
description: Data Warehouse V2 to V3 Changes - Bizible - Product Documentation
title: Data Warehouse V2 to V3 Changes
---

# Data Warehouse V2 to V3 Changes {#data-warehouse-v-to-v-changes}

Data Warehouse V2 to V3 Changes - Bizible - Product Documentation

From time to time, we make changes to our Data Warehouse schema, which includes adding or removing tables/columns. We want to make sure you're fully aware of these updates. Below is a list of changes we've made between Version 2 (Redshift) and Version 3 (Snowflake), organized by table.

### What's in this article? {#what-s-in-this-article}

[BIZ_ACCOUNTS](#datawarehousev2tov3changes-biz-accounts)  
[BIZ_ACCOUNT_TO_EMAILS](#datawarehousev2tov3changes-biz-account-to-emails)  
[BIZ_ADS](#datawarehousev2tov3changes-biz-ads)  
[BIZ_ADVERTISERS](#datawarehousev2tov3changes-biz-advertisers)  
[BIZ_AD_ACCOUNTS](#datawarehousev2tov3changes-biz-ad-accounts)  
[BIZ_AD_CAMPAIGNS](#datawarehousev2tov3changes-biz-ad-campaigns)  
[BIZ_AD_GROUPS](#datawarehousev2tov3changes-biz-ad-groups)  
[BIZ_AD_PROVIDERS](#datawarehousev2tov3changes-biz-ad-providers)  
[BIZ_ATTRIBUTION_TOUCHPOINTS](#datawarehousev2tov3changes-biz-attribution-touchpoints)  
[BIZ_CAMPAIGN_MEMBERS](#datawarehousev2tov3changes-biz-campaign-members)  
[BIZ_CHANNELS](#datawarehousev2tov3changes-biz-channels)  
[BIZ_CHAT_ACTIVITIES](#datawarehousev2tov3changes-biz-chat-activities)  
[BIZ_CONTACTS](#datawarehousev2tov3changes-biz-contacts)  
[BIZ_COSTS](#datawarehousev2tov3changes-biz-costs)  
[BIZ_CREATIVES](#datawarehousev2tov3changes-biz-creatives)  
[BIZ_CRM_EVENTS](#datawarehousev2tov3changes-biz-crm-events)  
[BIZ_CRM_TASKS](#datawarehousev2tov3changes-biz-crm-tasks)  
[BIZ_CUSTOMER_AB_TESTS](#datawarehousev2tov3changes-biz-customer-ab-tests)  
[BIZ_CUSTOM_LANDING_PAGES](#datawarehousev2tov3changes-biz-custom-landing-pages)  
[BIZ_CUSTOMER_EVENTS](#datawarehousev2tov3changes-biz-customer-events)  
[BIZ_EMAIL_TO_VISITOR_IDS](#datawarehousev2tov3changes-biz-email-to-visitor-ids)  
[BIZ_FACTS](#datawarehousev2tov3changes-biz-facts)  
[BIZ_FORM_SUBMITS](#datawarehousev2tov3changes-biz-form-submits)  
[BIZ_IMPRESSIONS](#datawarehousev2tov3changes-biz-impressions)  
[BIZ_KEYWORDS](#datawarehousev2tov3changes-biz-keywords)  
[BIZ_LANDING_PAGES](#datawarehousev2tov3changes-biz-landing-pages)  
[BIZ_LEADS](#datawarehousev2tov3changes-biz-leads)  
[BIZ_LEAD_STAGE_TRANSITIONS](#datawarehousev2tov3changes-biz-lead-stage-transitions)  
[BIZ_OPPORTUNITIES](#datawarehousev2tov3changes-biz-opportunities)  
[BIZ_OPP_STAGE_TRANSITIONS](#datawarehousev2tov3changes-biz-opp-stage-transitions)  
[BIZ_PAGE_VIEWS](#datawarehousev2tov3changes-biz-page-views)  
[BIZ_PLACEMENTS](#datawarehousev2tov3changes-biz-placements)  
[BIZ_SESSIONS](#datawarehousev2tov3changes-biz-sessions)  
[BIZ_SITES](#datawarehousev2tov3changes-biz-sites)  
[BIZ_SITE_LINKS](#datawarehousev2tov3changes-biz-site-links)  
[BIZ_STAGE_DEFINITIONS](#datawarehousev2tov3changes-biz-stage-definitions)  
[BIZ_TOUCHPOINTS](#datawarehousev2tov3changes-biz-touchpoints)  
[BIZ_URLS](#datawarehousev2tov3changes-biz-urls)  
[BIZ_USER_TOUCHPOINTS](#datawarehousev2tov3changes-biz-user-touchpoints)

#### BIZ_ACCOUNTS {#datawarehousev2tov3changes-biz-accounts}

* Created_Date_CRM is now CREATED_DATE
* Modified_Date_CRM is now MODIFIED_DATE
* ENGAGEMENT_SCORE is now type Number(38,19)
* New column:&nbsp;CUSTOM_PROPERTIES

#### BIZ_ACCOUNT_TO_EMAILS {#datawarehousev2tov3changes-biz-account-to-emails}

* New column: MODIFIED_DATE
* New column: CREATED_DATE
* New column: IS_DELETED

#### BIZ_ADS {#datawarehousev2tov3changes-biz-ads}

* New table: BIZ_ADS

#### BIZ_ADVERTISERS {#datawarehousev2tov3changes-biz-advertisers}

* New table: BIZ_ADVERTISERS

#### BIZ_AD_ACCOUNTS {#datawarehousev2tov3changes-biz-ad-accounts}

* New table: BIZ_AD_ACCOUNTS

#### BIZ_AD_CAMPAIGNS {#datawarehousev2tov3changes-biz-ad-campaigns}

* New table: BIZ_AD_CAMPAIGNS

#### BIZ_AD_GROUPS {#datawarehousev2tov3changes-biz-ad-groups}

* New table: BIZ_AD_GROUPS

#### BIZ_AD_PROVIDERS {#datawarehousev2tov3changes-biz-ad-providers}

* New table: BIZ_AD_PROVIDERS

#### BIZ_ATTRIBUTION_TOUCHPOINTS {#datawarehousev2tov3changes-biz-attribution-touchpoints}

* New column: MODIFIED_DATE
* Categories have been broken out into separate columns:

    * CATEGORY1
    * CATEGORY2
    * CATEGORY3
    * CATEGORY4
    * CATEGORY5
    * CATEGORY6
    * CATEGORY7
    * CATEGORY8
    * CATEGORY9
    * CATEGORY10
    * CATEGORY11
    * CATEGORY12
    * CATEGORY13
    * CATEGORY14
    * CATEGORY15

* New column: LANDING_PAGE_RAW
* New column: REFERRER_PAGE_RAW
* FIRST_CLICK_PERCENTAGE is now type Number(22,19)
* LAST_ANON_CLICK_PERCENTAGE is now type Number(22,19)
* U_SHAPE_PERCENTAGE is now type Number(22,19)
* W_SHAPE_PERCENTAGE is now type Number(22,19)
* FULL_PATH_PERCENTAGE is now type Number(22,19)
* CUSTOM_MODEL_PERCENTAGE is now type Number(22,19)
* New column: ROW_KEY
* New column: OPPORTUNITY_ROW_KEY

#### BIZ_CAMPAIGN_MEMBERS {#datawarehousev2tov3changes-biz-campaign-members}

* Modified_Date_CRM is now MODIFIED_DATE
* Created_Date_CRM is now CREATED_DATE
* New column:&nbsp;CUSTOM_PROPERTIES

#### BIZ_CHANNELS {#datawarehousev2tov3changes-biz-channels}

* New table: BIZ_CHANNELS

#### BIZ_CHAT_ACTIVITIES {#datawarehousev2tov3changes-biz-chat-activities}

* Deleted table: BIZ_CHAT_ACTIVITIES

    * Refer to BIZ_FORM_SUBMITS and use FORM_SOURCE to get web chats

#### BIZ_CONTACTS {#datawarehousev2tov3changes-biz-contacts}

* Modified_Date_CRM is now MODIFIED_DATE
* Created_Date_CRM is now CREATED_DATE
* Account_Id is now ACCOUNTID
* ODDS_OF_CONVERSION is now type Number(38,19)
* New column: BIZIBLE_COOKIE_ID
* New column: IS_DUPLICATE
* New column: ROW_KEY
* New column: SOURCE_SYSTEM
* New column: OTHER_SYSTEM_ID
* New column:&nbsp;CUSTOM_PROPERTIES

#### BIZ_COSTS {#datawarehousev2tov3changes-biz-costs}

* New column: MODIFIED_DATE
* COST_IN_MICRO is now type number(38,0)
* CLICKS is now type number(38,0)
* IMPRESSIONS is now type number(38,0)
* ESTIMATED_TOTAL_POSSIBLE_IMPRESSIONS is now type number(38,0)
* New column: AD_PROVIDER

#### BIZ_CREATIVES {#datawarehousev2tov3changes-biz-creatives}

* New table: BIZ_CREATIVES

#### BIZ_CRM_EVENTS {#datawarehousev2tov3changes-biz-crm-events}

* Created_Date_CRM is now CREATED_DATE
* Modified_Date_CRM is now MODIFIED_DATE
* BIZIBLE_HOST_ID has been renamed to BIZIBLE_COOKIE_ID
* New column: ACTIVITY_TYPE
* New column:&nbsp;CUSTOM_PROPERTIES

#### BIZ_CRM_TASKS {#datawarehousev2tov3changes-biz-crm-tasks}

* Created_Date_CRM is now CREATED_DATE
* Modified_Date_CRM is now MODIFIED_DATE
* BIZIBLE_HOST_ID has been renamed to BIZIBLE_COOKIE_ID
* New column:&nbsp;CUSTOM_PROPERTIES

#### BIZ_CUSTOMER_AB_TESTS {#datawarehousev2tov3changes-biz-customer-ab-tests}

* New table: BIZ_CUSTOMER_AB_TESTS

#### BIZ_CUSTOM_LANDING_PAGES {#datawarehousev2tov3changes-biz-custom-landing-pages}

* New table: BIZ_CUSTOM_LANDING_PAGES

#### BIZ_CUSTOMER_EVENTS {#datawarehousev2tov3changes-biz-customer-events}

* New table: BIZ_CUSTOMER_EVENTS

#### BIZ_EMAIL_TO_VISITOR_IDS {#datawarehousev2tov3changes-biz-email-to-visitor-ids}

* New column: MODIFIED_DATE
* New column: CREATED_DATE
* New column: IS_DELETED

#### BIZ_FACTS {#datawarehousev2tov3changes-biz-facts}

* New table: BIZ_FACTS

#### BIZ_FORM_SUBMITS {#datawarehousev2tov3changes-biz-form-submits}

* New column: MODIFIED_DATE
* New column: CURRENT_PAGE_RAW
* New column: TYPE
* New column: USER_AGENT_STRING
* New column: CLIENT_SEQUENCE
* New column: CLIENT_RANDOM
* New column: IS_DUPLICATED
* New column: IS_PROCESSED
* Email_in_Form has been renamed to EMAIL
* New column: FORM_TYPE
* New column: FORM_SOURCE
* New column: FORM_IDENTIFIER
* New column: ROW_KEY
* Deleted column: CITY
* Deleted column: REGION
* Deleted column: COUNTRY
* Deleted column: ISP_NAME
* Deleted column: IS_DELETED

#### BIZ_IMPRESSIONS {#datawarehousev2tov3changes-biz-impressions}

* New column: MODIFIED_DATE
* New column: CURRENT_PAGE_RAW
* New column: TYPE
* New column: USER_AGENT_STRING
* New column: CLIENT_SEQUENCE
* New column: CLIENT_RANDOM
* New column: IS_DUPLICATED
* New column: IS_PROCESSED
* New column: REFERRER_PAGE_RAW
* Deleted column: REFERRER_NAME
* Deleted column: WEB_SOURCE
* Deleted column: DEVICE
* New column: BROWSER_NAME
* New column: BROWSER_VERSION
* New column: PLATFORM_NAME
* New column: PLATFORM_VERSION
* New column: ROW_KEY
* Deleted column: CAMPAIGN
* Deleted column: MEDIUM
* Deleted column: SOURCE
* Deleted column: TERM
* Deleted column: CONTENT
* Deleted column: IS_DELETED

#### BIZ_KEYWORDS {#datawarehousev2tov3changes-biz-keywords}

* New table: BIZ_KEYWORDS

#### BIZ_LANDING_PAGES {#datawarehousev2tov3changes-biz-landing-pages}

* New table: BIZ_LANDING_PAGES

#### BIZ_LEADS {#datawarehousev2tov3changes-biz-leads}

* Created_Date_CRM is now CREATED_DATE
* Modified_Date_CRM is now MODIFIED_DATE
* ODDS_OF_CONVERSION is now type number(38,19)
* New column: IS_DUPLICATE
* New column: SOURCE_SYSTEM
* New column: OTHER_SYSTEM_ID
* New column: BIZIBLE_COOKIE_ID
* New column: ROW_KEY
* New column:&nbsp;CUSTOM_PROPERTIES

#### BIZ_LEAD_STAGE_TRANSITIONS {#datawarehousev2tov3changes-biz-lead-stage-transitions}

* New column: LAST_INDEX

#### BIZ_OPPORTUNITIES {#datawarehousev2tov3changes-biz-opportunities}

* Created_Date_CRM is now CREATED_DATE
* Modified_Date_CRM is now MODIFIED_DATE
* AMOUNT is now type number(38,8)
* ODDS_OF_CONVERSION is now type number(38,19)
* New column: ROW_KEY
* New column:&nbsp;CUSTOM_PROPERTIES

#### BIZ_OPP_STAGE_TRANSITIONS {#datawarehousev2tov3changes-biz-opp-stage-transitions}

* New column: LAST_INDEX

#### BIZ_PAGE_VIEWS {#datawarehousev2tov3changes-biz-page-views}

* New column: MODIFIED_DATE
* New column: CURRENT_PAGE_RAW
* New column: TYPE
* New column: USER_AGENT_STRING
* New column: CLIENT_SEQUENCE
* New column: CLIENT_RANDOM
* New column: IS_DUPLICATED
* New column: IS_PROCESSED
* New column: REFERRER_PAGE_RAW
* New column: EMAIL
* New column: ROW_KEY
* Deleted column: Referrer_Name
* Deleted column: Search_Phrase
* Deleted column: Web_Source
* Deleted column: Has_Form
* Deleted column: Has_Chat
* Deleted column: Has_Email
* Deleted column: Has_Crm_Activity
* Deleted column: Device
* Deleted column: Ad_Provider
* Deleted column: Account_Name
* Deleted column: Account_Unique_ID
* Deleted column: Advertiser_Name
* Deleted column: Advertiser_Unique_ID
* Deleted column: Site_Name
* Deleted column: Site_Unique_ID
* Deleted column: Placement_Name
* Deleted column: Placement_Unique_ID
* Deleted column: Campaign_Name
* Deleted column: Campaign_Unique_ID
* Deleted column: Ad_Group_Name
* Deleted column: Ad_Group_Unique_ID
* Deleted column: Ad_Name
* Deleted column: Ad_Unique_ID
* Deleted column: Creative_Name
* Deleted column: Creative_Unique_ID
* Deleted column: Creative_Description_1
* Deleted column: Creative_Description_2&nbsp; &nbsp;
* Deleted column: Creative_Destination_URL
* Deleted column: Creative_Display_URL
* Deleted column: Keyword_Name
* Deleted column: Keyword_Unique_ID
* Deleted column: Keyword_Match_Type
* Deleted column: Campaign
* Deleted column: Medium
* Deleted column: Source
* Deleted column: Term
* Deleted column: Content
* Deleted column: City
* Deleted column: Region
* Deleted column: Country
* Deleted column: ISP_name
* Deleted column: Is_deleted

#### BIZ_PLACEMENTS {#datawarehousev2tov3changes-biz-placements}

* New table: BIZ_PLACEMENTS

#### BIZ_SESSIONS {#datawarehousev2tov3changes-biz-sessions}

* New column: COOKIE_ID
* Session_Date has been renamed to EVENT_DATE
* New column: MODIFIED_DATE
* New column: PAGE_TITLE
* New Column: LANDING_PAGE_RAW
* New Column: REFERRER_PAGE_RAW
* New column: REFERRER_NAME
* New column: HAS_FORM
* New column: HAS_CHAT
* New column: HAS_EMAIL
* New column: HAS_CRM_ACTIVITY
* New column: DEVICE
* New column: CAMPAIGN
* New column: SOURCE
* New column: TERM
* New column: CONTENT
* New column: ISP_NAME
* New column: IP_ADDRESS
* New column: ROW_KEY
* Deleted column: CATEGORIES
* Deleted column: BROWSER_NAME
* Deleted column: BROWSER_VERSION
* Deleted column: PLATFORM_NAME
* Deleted column: PLATFORM_VERSION
* Deleted column: LANDING_PAGE
* Deleted column: FORM_PAGE
* Deleted column: FORM_DATE
* Deleted column: MODIFIED_DATE
* Deleted column: MARKETING_TOUCH_TYPE
* Deleted column: IS_FORM_SUBMISSION_TOUCH
* Deleted column: IS_IMPRESSION_TOUCH

#### BIZ_SITES {#datawarehousev2tov3changes-biz-sites}

* New table: BIZ_SITES

#### BIZ_SITE_LINKS {#datawarehousev2tov3changes-biz-site-links}

* New table: BIZ_SITE_LINKS

#### BIZ_STAGE_DEFINITIONS {#datawarehousev2tov3changes-biz-stage-definitions}

* New table: BIZ_STAGE_DEFINITIONS

#### BIZ_TOUCHPOINTS {#datawarehousev2tov3changes-biz-touchpoints}

* New column: MODIFIED_DATE
* Deleted column: LEAD_SOURCE
* Categories have been broken out into separate columns:

    * CATEGORY1
    * CATEGORY2
    * CATEGORY3
    * CATEGORY4
    * CATEGORY5
    * CATEGORY6
    * CATEGORY7
    * CATEGORY8
    * CATEGORY9
    * CATEGORY10
    * CATEGORY11
    * CATEGORY12
    * CATEGORY13
    * CATEGORY14
    * CATEGORY15

* New column: LANDING_PAGE_RAW
* New column: REFERRER_PAGE_RAW
* FIRST_CLICK_PERCENTAGE is now type number(22,19)
* LAST_ANON_CLICK_PERCENTAGE is now type number(22,19)
* U_SHAPE_PERCENTAGE is now type number(22,19)
* W_SHAPE_PERCENTAGE is now type number(22,19)
* FULL_PATH_PERCENTAGE is now type number(22,19)
* CUSTOM_MODEL_PERCENTAGE is now type number(22,19)
* New column: ROW_KEY
* New column: CONTACT_ROW_KEY
* New column: LEAD_ROW_KEY

#### BIZ_URLS {#datawarehousev2tov3changes-biz-urls}

* New table: BIZ_URLS

#### BIZ_USER_TOUCHPOINTS {#datawarehousev2tov3changes-biz-user-touchpoints}

* New column: MODIFIED_DATE
* New column: IMPRESSION_ID
* New column: LANDING_PAGE_RAW
* New column: REFERRER_PAGE_RAW
* New column: FORM_PAGE_RAW
* New column: IS_FIRST_TOUCH
* New column: IS_LEAD_CREATION_TOUCH
* New column: IS_OPP_CREATION_TOUCH
* New column: IS_CLOSED_TOUCH
* New column: STAGES_TOUCHED
* New column: FIRST_CLICK_PERCENTAGE
* New column: LAST_ANON_CLICK_PERCENTAGE
* New column: U_SHAPE_PERCENTAGE
* New column: W_SHAPE_PERCENTAGE
* New column: FULL_PATH_PERCENTAGE
* New column: CUSTOM_MODEL_PERCENTAGE
* New column: ROW_KEY&nbsp;&nbsp;&nbsp;

