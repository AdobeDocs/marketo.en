---
unique-page-id: 18874732
description: Best Practices for Setting Up UTM Parameters - Bizible - Product Documentation
title: Best Practices for Setting Up UTM Parameters
---

# Best Practices for Setting Up UTM Parameters {#best-practices-for-setting-up-utm-parameters}

Best Practices for Setting Up UTM Parameters - Bizible - Product Documentation

UTM parameters are great way to slice and dice your marketing data. Bizible uses and captures all UTM parameters to populate fields in Salesforce and in the Bizible app. With this information, you'll be able to get a granular understanding of where your leads, opportunities, and closed/won deals are coming from.   
  
You can utilize the [Google URL Builder](http://support.google.com/analytics/answer/1033867?hl=en) to set up your UTM parameters and add them to your links within your marketing efforts. Use this [Google Spreadsheet](http://docs.google.com/spreadsheets/d/1QCIr1WUJQHE68cA4VTks2XE7nxuryaUymCEy_23-Oew/edit#gid=0) if you want an easier way of keeping track of all your UTM links.

#### High level values for each parameter {#bestpracticesforsettinguputmparameters-highlevelvaluesforeachparameter}

**utm_medium**: This field maps to the Medium field. Use utm_medium to denote the high level channel.  
  
e.g.: Social, CPC, email, web, organic  
  
Do not use this field to call out the subchannel.   
  
**utm_source**: This field maps to the Touchpoint Source field. Use utm_source to define the subchannel from which the lead originates.   
  
e.g.: Facebook, Twitter, Linkedin, Drip_email, Email_blast, newsletter.  
  
Keep it simple. Do not use this parameter to denote ad type, like retargeting, sponsored, etc. Do not add a utm_source = homepage, webdirect, website. Bizible will automatically fill out this information for you.  
  
**utm_campaign**: This field maps to Ad Campaign Name. Use utm_campaign to denote the title of the campaign as it exists in the ad platform, or as it's referred to internally.  
  
This is also a good parameter to denote Geolocation, Ad network type (display v. search), etc.  
  
We recommend using underscores instead of spaces, and avoid using punctuation. This reduces the chances of encoding errors by browsers when reading your parameters.  
  
e.g.: AU_Idea_for_an_App_50k  
  
**utm_content**: This maps to Ad Content. Use the Ad Title in the utm_content parameter. If it is an image ad, use ad title and include the ad dimensions.   
  
e.g.: [ad title] 200x400px  
  
**utm_term**: This maps to Keyword Text. Use this parameter to denote the keyword related to the firing of the ad.   
  
If there is no keyword related to the ad, leave this parameter blank.   
  
e.g.: iPhone App Ideas

#### Keep it simple and succinct. Do not duplicate efforts, terms, and channels. {#bestpracticesforsettinguputmparameters-keepitsimpleandsuccinct-donotduplicateefforts-terms-andchannels}

We imagine the UTM hierarchy as follows:  
  
Medium > Source > Campaign > Content/Term   
  
e.g.: If a display ad is placed on Facebook, we recommend the following:   
  
fakewebsite.com/  
  
?utm_medium=social  
  
&utm_source=facebook  
  
&utm_campaign=Display_campaign_ID  
  
&utm_content=content_of_campaign  
  
Notice that terms/channel are not duplicated and utm_term is not used in this case.  
  
If there are any questions, reach out to your dedicated Success Manager or [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#c4b7b1b4b4abb6b084a6adbeada6a8a1eaa7aba9).

