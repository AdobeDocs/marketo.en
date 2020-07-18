---
unique-page-id: 18874608
description: Bizible Parameters - Bizible - Product Documentation
title: Bizible Parameters
---

# Bizible Parameters {#bizible-parameters}

Bizible Parameters - Bizible - Product Documentation

### What's in this article? {#whats-in-this-article}

[Bizible Parameters Explained](#bizible-parameters-explained)  
[AdWords Parameters](#adwords-parameters)  
[Bing Ads Parameters](#bing-ads-parameters)  
[Facebook Parameters](#facebook-parameters)

#### Bizible Parameters Explained {#bizible-parameters-explained}

To gain further insight from the use of UTMs, Bizible appends custom parameters to your ads in Google AdWords, Bing Ads and Facebook Ads. Bizible integrates with these platforms to automate most of the setup process. If you select to use auto-tagging, Bizible will automatically append its parameters to the URLs of your ads. Bizible will also automatically download your marketing costs from the platforms and load them into the Bizible app.

Example of a URL without parameters:

* [http://bizible.com/landing-page?myParam=foo](http://bizible.com/landing-page?myParam=foo)

Example of a URL with Bizible parameters:

* http://bizible.com/landing-page?myParam=foo&_bt={creative}&_bk={keyword}&_bm={matchtype}&_bn={network}&_bg={adgroupid}

#### AdWords Parameters {#adwords-parameters}

* _bk={keyword}

    * Represents the keyword the person used in the search engine.
    * It is similar to the UTM term parameter.

* _bt={creative}

    * Represents the creative ID or name. 
    * `It is similar to the UTM content parameter.  
  
      `

* _bm={matchtype}

    * Represents how closely the keyword was matched. 
    * Keyword match types help control which searches trigger your ad. For example, you could use broad match to show your ad to a wide audience or you could use exact match to hone in on specific groups of customers.
    * The three match types are: broad, fuzzy and exact.

>[!NOTE]
>
>For more information on match types, [here's a relevant AdWords article.](http://support.google.com/adwords/answer/2497836?hl=en)

* _bn={network}

    * Represents the ad network type - [display or search](http://support.google.com/adwords/answer/1752334?hl=en). 
    * This is similar to the UTM Source parameter.

* _bg={adgroupID}

    * Represents the ID of the Ad Group the ad belongs to

#### Bing Ads Parameters {#bing-ads-parameters}

* `_bt={adid}`
* utm_medium=cpc
* utm_source=bing
* utm_term={keyword}

#### Facebook Parameters {#facebook-parameters}

* `_bf ={creative}`

    * `This represents the creative ID or name`

