---
unique-page-id: 18874586
description: Glossary of Bizible Fields - Bizible - Product Documentation
title: Glossary of Bizible Fields
---

# Glossary of Bizible Fields {#glossary-of-bizible-fields}

Glossary of Bizible Fields - Bizible - Product Documentation

This article provides a glossary of all the Bizible Fields that are added to your Salesforce from the Bizible Base Package. You will also find information on which Object the Field can be found on and how each Field is populated with information.   
  
For a map of which Object each Bizible Field relates to, please [click here](http://docs.marketo.com/x/2AAgAQ).

##### A · [B](#b) · [C](#c) · [D](#d) · [E](#e) · [F](#f) · [G](#g) · H · I · J · [K](#k) · [L](#l) · [M](#m) · N · [O](#o) · [P](#p) · Q · [R](#r) · [S](#s) · [T](#t) · [U](#u) · [V](#v) · W · X · Y · Z  {#a-b-c-d-e-f-g-h-i-j-k-l-m-n-o-p-q-r-s-t-u-v-w-x-y-z}

#### A {#a}

**Account** | Found on Bizible Attribution Touchpoint   
  
This field populates with the Account name that is associated to the BAT.  
  
**Ad Campaign Id** | Found on Bizible Touchpoint, Bizible Attribution Touchpoint  
  
There are three ways this field can be populated:  
  
1) If the touchpoint comes from a paid search effort (either AdWords or BingAds), the Ad Campaign Id from the ad platform will be surfaced here.   
  
2) If the touchpoint did not come from paid search, the field will be populated using the utm_campaign value from the landing page URL.  
  
e.g. `http://info.bizible.com/adwords-for-lead-generation?utm_source=Event&utm_medium=booth&utm_campaign=Marketo%20Virtual%20Event%20sep2014`  
  
In this example, Ad Campaign Id would display: __GAId__ Marketing Virtual Event sept2014  
  
3) If the touchpoint comes from an offline Salesforce Campaign (a conference, dinner, etc.), Ad Campaign Id will surface the Salesforce Campaign Id  
  
If none of the above, this field will be blank.  
  
**Ad Campaign Name** | Bizible Touchpoint, Bizible Attribution Touchpoint   
  
1) If the touchpoint comes from paid search (AdWords/Bing Ads), the ad campaign name from the ad platform will be displayed here.  
  
2) If the touchpoint did not come from paid search, and the landing page URL contains a value for utm_campaign, that value will be populated here.  
  
3) If the touchpoint came from a Salesforce Campaign, the name of the Salesforce Campaign will be displayed here.  
  
4) This will populate with the Campaign Name defined for Touchpoints generated from Activities as built within your Bizible Account.  
  
If none of the above, this field will be blank.  
  
**Ad Campaign Name (FT)** | Bizible Touchpoint   
  
This field is populated the same way as Ad Campaign Name. However, this field specifically shows you the name of the ad campaign that generated the First Touch touchpoint.  
  
**Ad Campaign Name (LC)** | Bizible Touchpoint   
  
This field is populated the same way as Ad Campaign Name. However, this field specifically shows you the name of the ad campaign that generated the Lead Creation touchpoint.  
  
**Ad Content** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
1) If the touchpoint is from paid search (AdWords/Bing Ads), the field will display the full ad copy from the ad platform.   
  
2) If the touchpoint is not from paid search, this field will display the utm_content value in the landing page URL.  
  
3) This will populate with the Subject value from the related Activity that generated the Touchpoint.  
  
If neither of the above, this field will be blank.  
  
**Ad Destination URL** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
1) If the touchpoint is from paid search, this field will display the URL destination you are directed to after clicking on the ad from the search engine.  
  
If the touchpoint is not from paid search, the field will be blank.  
  
**Ad Group Id** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
1) If the touchpoint came from paid search, the Ad Group Id from AdWords/Bing Ads will be displayed here.   
  
If the touchpoint did not come from paid search, the field will be blank.   
  
**Ad Group Name** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
1) If the touchpoint came from paid search, the Ad Group Name from AdWords/Bing Ads will be displayed here.   
  
If the touchpoint did not come from paid search, the field will be blank.  
  
**Ad Id** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
1) If the touchpoint came from paid search, the Ad Id from AdWords/Bing Ads will be displayed here.  
  
2) This will populate with the Activity external ID if the Touchpoint is generated from a CRM Activity.  
  
If the touchpoint did not come from paid search, the field will be blank.  
  
**Attribution % Custom Model** | Bizible Attribution Touchpoint  
  
If you are using a Custom Attribution Model, this field displays the percentage of revenue attributed to a touchpoint according to the values set in your Custom Model.  
  
If you are not using a Custom Model, this field will be blank.  
  
**Attribution % First Touch** | Bizible Attribution Touchpoint  
  
This field will display the percentage of revenue attributed to a touchpoint according to a First Touch Model.  
  
**Attribution % Full** | Bizible Attribution Touchpoint  
  
This field will display the percentage of revenue attributed to a touchpoint according to a Full Path Model.  
  
**Attribution % Lead Creation** | Bizible Attribution Touchpoint  
  
This field will display the percentage of revenue attributed to a touchpoint, according to a Lead Creation Model.  
  
**Attribution % U-Shaped** | Bizible Attribution Touchpoint  
  
This field will display the percentage of revenue attributed to a touchpoint according to a U-Shaped Model.  
  
**Attribution % W-Shaped** | Bizible Attribution Touchpoint  
  
This field will display the percentage of revenue attributed to a touchpoint according to a W-Shaped Model.

[Click here to return to the top of the page](#top)

####  B {#b}

**Bizible Opportunity Amount** | Salesforce Opportunity   
  
If you are using a custom Amount field to report Opportunity revenue, Bizible is unable to read these custom Amount fields. The Bizible Opportunity Amount is a hidden field that is used to create a workflow that enables Bizible to read custom Amount fields on the Opportunity.  
  
**Browser** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the type of web browser used during the web session (Chrome, Safari, Firefox, etc.).

[Click here to return to the top of the page](#top)

####  C {#c}

**Contact** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
The field displays the Contact the touchpoint belongs to.  
  
**Count - Custom Model** | Bizible Attribution Touchpoint  
  
If you are using a Custom Attribution Model, this field shows, in decimal form, the percentage of revenue credit given to a touchpoint according to the values set in your Custom Model.  
  
If you are not using a custom model, this field will be blank.  
  
**Count - Custom Model** | Bizible Touchpoint  
  
If you are using a Custom Attribution Model, this field shows, in decimal form, the percentage of attribution credit given to a touchpoint according to the values set in your Custom Model. Since this field relates to the Bizible Touchpoint Object, it is not a reflection of revenue credit, solely just attribution credit.   
  
If you are not using a custom model, this field will be blank.  
  
**Count - First Touch** | Bizible Attribution Touchpoint  
  
This field shows, in decimal form, the percentage of revenue credit given to a touchpoint according to a First Touch Model.   
  
**Count - First Touch** | Bizible Touchpoint  
  
This field shows, in decimal form, the percentage of attribution credit given to a touchpoint according to a First Touch Model. If the touchpoint is the First Touch, this field will always be 1.0 (indicating 100% attribution credit). If the touchpoint is not the First Touch, this field will always be 0 (indicating 0 % attribution credit).  
  
Since this field relates to the Bizible Touchpoint Object, it is not a reflection of revenue credit, solely just attribution credit.  
  
**Count - Full Path** | Bizible Attribution Touchpoint  
  
This field shows, in decimal form, the percentage of revenue given to a touchpoint according to a Full Path Model.  
  
**Count - Lead Creation Touch** | Bizible Attribution Touchpoint  
  
This field shows, in decimal form, the percentage of revenue credit given to a touchpoint according to a Lead Creation Model.  
  
**Count - Lead Creation Touch** | Bizible Touchpoint  
  
This field shows, in decimal form, the percentage of attribution credit given to a touchpoint according to a Lead Creation Model. If the touchpoint is the Lead Creation touch, this field will always be 1.0 (indicating 100% attribution credit). If the touchpoint is not the Lead Creation touch, this field will always be 0 (indicating 0% attribution credit).   
  
Since this field relates to the Bizible Touchpoint Object, it is not a reflection of revenue credit, solely just attribution credit.  
  
**Count - U-Shaped** | Bizible Attribution Touchpoint  
  
This field shows, in decimal form, the percentage of revenue credit given to a touchpoint according to a U-Shaped Model.  
  
**Count - U-Shaped** | Bizible Touchpoint  
  
This field shows, in decimal form, the percentage of attribution credit given to a touchpoint according to a U-Shaped Model. In the U-Shaped Model, credit is divided between the First Touch, the Lead Creation Touch, and any intermediary form submissions that occurred between the First Touch and Lead Creation Touch.   
  
Since this field relates to the Bizible Touchpoint Object, it is not a reflection of revenue credit, solely just attribution credit.   
  
**Count - W-Shaped** | Bizible Attribution Touchpoint  
  
This field shows, in decimal form, the percentage of credit given to a touchpoint according to a W-Shaped Model.

[Click here to return to the top of the page](#top)

####  D {#d}

Date Reported | Bizible ABTest, Bizible Event  
  
Bizible Event - the date when a user took a specific action on your website, activating an Event  
  
Bizible ABTest - the date when a user participated in an A/B Test on your website

[Click here to return to the top of the page](#top)

####  E {#e}

**Event Name** | Bizible Event  
  
This field displays the name of the action that triggered the event (i.e. Page View).   
  
**Event Value** | Bizible Event  
  
The description for the event (i.e. Homepage)   
  
**Experiment Name** | Bizible ABTest  
  
This field displays the name of the experiment (i.e. Trial Button)  
  
**Experiment ID** |Bizible AB Test  
  
The unique identification code for each experiment

[Click here to return to the top of the page](#top)

####  F {#f}

Form URL | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field will display a shortened version of a page's URL where the form fill occurred (no UTM parameters)  
  
Form URL - Raw | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the entire page URL where the form fill occurred, including UTM parameters

[Click here to return to the top of the page](#top)

####  G {#g}

Geo City | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the name of the city where the lead/contact visited your website. This is done via reverse IP lookup.   
  
Geo Country | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays where the country where the lead/contact visited your website. This is done via reverse IP lookup.   
  
Geo Region | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the region or state where the lead/contact visited your website. This is done via reverse IP lookup.

[Click here to return to the top of the page](#top)

####  K {#k}

**Keyword Id** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
If the touchpoint comes from paid search, this field will display the keyword ID from the ad platform (Adwords/BingAds).  
  
If this touchpoint did not come from paid search, this field will be blank.  
  
**Keyword MatchType** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
If the touchpoint comes from paid search, this field will display the matchtype from the ad platform (Adwords/Bing).   
  
**Keyword Text** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
1) If the touchpoint comes from paid search, this field will display the keyword text from the ad platform (Adwords/BingAds) OR the value from the _bk parameter in the landing page URL.   
  
e.g. `http://info.bizible.com/intro-guide-b2b-marketing-attribution?_bt=12345678&_bk=marketing%20attribution&_bm=p&gclid=ABc123def456ghi789jkl`  
  
2) If the touchpoint does not come from paid search, this field will display the utm_term value from the landing page URL.   
  
[http://www.bizible.com/blog/lead-generation?utm_source=linkedin&utm_medium=Social&utm_campaign=ABC%20Blog&utm_content=Lead%20Gen&utm_term=lead%20gen](http://www.bizible.com/blog/lead-generation?utm_source=linkedin&utm_medium=Social&utm_campaign=ABC%20Blog&utm_content=Lead%20Gen&utm_term=lead%20gen).  
  
If the touchpoint did not come from paid search, or there is no utm_term value, this field will be blank.

[Click here to return to the top of the page](#top)

####  L {#l}

**Landing Page** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the a shortened version of the URL (no UTM parameters) of the first web page visited during a web session.   
  
**Landing Page - Raw** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the entire URL (including UTM parameters) of the first web page visited during a web session.   
  
**Lead** | Bizible Touchpoint, Bizible Person  
  
This field displays the name of the lead a touchpoint belongs to.

[Click here to return to the top of the page](#top)

####  M {#m}

**Marketing Channel** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field shows you the general group of marketing activity or marketing channel the touchpoint belongs to (i.e. Paid Search, Direct, Social, etc.). Touchpoints are grouped according to how your channels have been set up in the Bizible App. For more information about marketing channels, or how to set up your channels, please [click here](http://docs.marketo.com/x/5AAgAQ).  
  
**Marketing Channel - Path** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field shows you the marketing channel, and the sub-channel that a touchpoint belongs to. In the example below, Marketing Channel - Path is Social.Linkedin, where the marketing channel is Social, and the sub-channel is LinkedIn.   
  
![](assets/1-3.png)  
  
**Medium** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
1) If the touchpoint comes from paid search, the medium from Adwords/BingAds will be displayed here (i.e. CPC).  
  
2) If the touchpoint does not come from paid search, this field displays the utm_medium value from the landing page URL.  
  
3) If the touchpoint comes from an offline campaign, this field will display the 'Type' field in the Salesforce Campaign.  
  
4) This will populate with the Activity Type value from the related Activity that generated the Touchpoint.  
  
If none of the above, Bizible automatically set a Medium value.

[Click here to return to the top of the page](#top)

O

**Opportunity** | Bizible Attribution Touchpoint  
  
This field displays the opportunity the BAT belongs to.

[Click here to return to the top of the page](#top)

P

**Platform** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the type of computer or phone and the type of operating system that was used during the web session.

[Click here to return to the top of the page](#top)

R

**Referrer Page** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the URL (without UTM parameters) of the last webpage the Lead/Contact was on that directed them to your website.   
  
For example:  
  
- If the touchpoint came from Paid/Organic search, the field will show the URL of the search engine  
  
- If the touchpoint came from Social, the field will show the URL of the social website (i.e. LinkedIn)  
  
**Referrer Page - Raw** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the same information as Referrer Page, except this field will display the entire referring URL (including UTM parameters).   
  
**Revenue - Custom Model** | Bizible Attribution Touchpoint  
  
If you are using a Custom Attribution Model, this field shows the dollar revenue amount attributed to a touchpoint according to the attribution percentage set in your Custom Model.  
  
If you are not using a custom model, the dollar amount will be 0.  
  
**Revenue - First Touch** | Bizible Attribution Touchpoint  
  
This field shows the dollar revenue amount attributed to a touchpoint according to the attribution percentage in the First Touch Model.  
  
**Revenue - Full Path** | Bizible Attribution Touchpoint  
  
This field shows the dollar revenue amount attributed to a touchpoint according to the attribution percentage in the Full Path Model.  
  
**Revenue - Lead Creation Touch** | Bizible Attribution Touchpoint  
  
This field shows the dollar revenue amount attributed to a touchpoint according to the attribution percentage in the Lead Creation Model.  
  
**Revenue - U-Shaped** | Bizible Attribution Touchpoint  
  
This field shows the dollar revenue amount attributed to a touchpoint according to the attribution percentage in the U-Shaped Model.  
  
**Revenue - W-Shaped** | Bizible Attribution Touchpoint  
  
This field shows the dollar revenue amount attributed to a touchpoint according to the attribution percentage in the W-Shaped Model.

[Click here to return to the top of the page](#top)

S

**Salesforce Campaign** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the Salesforce Campaign the touchpoint belongs to.   
  
**Search Phrase** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
If the touchpoint came from paid or organic search, this field will display the search phrase typed into the search engine. However, due to privacy reasons, this information is usually unavailable.   
  
**Segment** | Bizible Attribution Touchpoint  
  
This field will display the segments that the touchpoint belongs to. This will depend on how you have configured your segmentation rules in the Bizible app.

[Click here to return to the top of the page](#top)

T

**Touchpoint Date** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
1) If the touchpoint came from an online source, this field will display the date and time the touchpoint occurred.  
  
2) If the touchpoint came from an offline event, this field will display the date and time set in the Salesforce Campaign or from the date field selected in the Campaign Sync Rules.  
  
3) If the touchpoint came from an Activity, this field will display the date and time of the field selected as the Touchpoint Date in the Activity rules.  
  
**Touchpoint Date (FT)** | Bizible Touchpoint  
  
This is the same field as Touchpoint Date, however this field specifically displays the date and time the First Touch touchpoint occurred.   
  
**Touchpoint Date (LC)** | Bizible Touchpoint  
  
This is the same field as Touchpoint Date, however this field specifically displays the date and time the Lead Creation touchpoint occurred.   
  
**Touchpoint Position** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
This field displays the position of the touchpoint. The position of the touchpoint reflects the major milestone touchpoints in the customer journey (i.e. FT, Form, LC, OC, Closed). The position of the touchpoint depends on when it occurred in the customer journey, and a single touchpoint can have more than one position. The different touchpoint positions are as follows:  
  
First Touch (FT) - The very first marketing interaction someone has with your brand  
  
Lead Creation (LC) - The very first known marketing interaction (typically a form submission or a Salesforce Campaign inclusion)  
  
Form - When a visitor fills out an online form  
  
Opportunity Creation (OC) - The marketing interaction closest to when the Opp is Created  
  
Closed - The marketing interaction closest to when the Opp is Closed (Won or Lost)  
  
**Touchpoint Source** | Bizible Touchpoint, Bizible Attribution Touchpoint   
  
1) If the touchpoint came from paid search, this field will display the name of the ad platform (AdWords/BingAds)  
  
2) If the touchpoint came from organic search, this field will display the name of the search engine  
  
3) If not #1 or #2, and the utm_source value is present in the landing page URL for the touchpoint, that value will be displayed here  
  
4) This will populate as CRM Campaign if the Touchpoint is generated from a CRM Campaign.  
  
5) This will populate as CRM Activity if the Touchpoint is generated from a CRM Activity.  
  
If none of the above, this field will be populated as 'Web Direct' or 'Web'.   
  
**Touchpoint Source (FT)** | Bizible Touchpoint  
  
This is the same field as Touchpoint Source however this field specifically displays the source of the First Touch touchpoint.  
  
**Touchpoint Source (LC)** | Bizible Touchpoint  
  
This is the same field as Touchpoint Source however this field specifically displays the source of the Lead Creation touchpoint.

**Touchpoint Type** | Found on the Bizible Touchpoint and Bizible Attribution Touchpoint.  
  
This field will display the type of interaction of the Touchpoint. It will display as: Web Visit, Web Form, or Web Chat for JavaScript touchpoints. For CRM Campaign Touchpoints, it will display as CRM. It will populate with the Task or Event Type for Activity Touchpoints.

[Click here to return to the top of the page](#top)

U

**UniqueId** | Bizible Touchpoint, Bizible Attribution Touchpoint  
  
The unique id associated to each touchpoint  
  
**User ID** | Bizible ABTest  
  
Optimizely's unique identification code for each use

[Click here to return to the top of the page](#top)

####  V {#v}

**Variation** | Bizible ABTest  
  
The name of the variation of the A/B test   
  
**Variation ID** | Bizible ABTest  
  
The unique identification code for each A/B Test variation.

[Click here to return to the top of the page](#top)

