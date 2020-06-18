---
unique-page-id: 18874608
description: Bizible Parameters - Bizible - Product Documentation
title: Bizible Parameters
---

# Bizible Parameters {#bizible-parameters}

Bizible Parameters - Bizible - Product Documentation

### What's in this article? {#what-s-in-this-article}

[Bizible Parameters Explained](#bizibleparameters-bizibleparametersexplained)  
[AdWords Parameters](#bizibleparameters-adwordsparameters)  
[Bing Ads Parameters](#bizibleparameters-bingadsparameters)  
[Facebook Parameters](#bizibleparameters-facebookparameters)

#### Bizible Parameters Explained {#bizibleparameters-bizibleparametersexplained}

To gain further insight from the use of UTMs, Bizible appends custom parameters to your ads in Google AdWords, Bing Ads and Facebook Ads. Bizible integrates with these platforms to automate most of the setup process. If you select to use auto-tagging, Bizible will automatically append its parameters to the URLs of your ads.&nbsp;Bizible will also automatically download your marketing costs from the platforms and load them into the Bizible app.&nbsp;&nbsp;

Example of a URL without parameters:

* [http://bizible.com/landing-page?myParam=foo](http://bizible.com/landing-page?myParam=foo)

Example of a URL with Bizible parameters:

* http://bizible.com/landing-page?myParam=foo&_bt={creative}&_bk={keyword}&_bm={matchtype}&_bn={network}&_bg={adgroupid}

#### AdWords Parameters {#bizibleparameters-adwordsparameters}

* _bk={keyword}&nbsp;
* `<li>Represents the keyword the person used in the search engine.</li>` `<li>It is similar to the&nbsp;UTM term parameter.</li>`

* _bt={creative}&nbsp;
* `<li>Represents the creative ID or name. &nbsp;</li>` `<li><span>It is similar to the UTM content parameter.<br><br></span></li>` 

* _bm={matchtype}
* `<li>Represents how closely the keyword was matched. &nbsp;</li>` `<li>Keyword match types help control which searches trigger your ad. For example, you could use broad match to show your ad to a wide audience or you could use exact match to hone in on specific groups of customers.</li>` `<li>The three match types are: broad, fuzzy and exact.</li>`

>[!NOTE]
>
>For more information on match types,&nbsp; [here's a relevant AdWords article.](http://support.google.com/adwords/answer/2497836?hl=en)

* _bn={network}
* `<li>Represents the ad network type -&nbsp;<a href="http://support.google.com/adwords/answer/1752334?hl=en" rel="nofollow">display or search</a>. &nbsp;</li>` `<li>This is similar to the UTM Source parameter.</li>`

* _bg={adgroupID}

    * Represents the ID of the Ad Group the ad belongs to

#### Bing Ads Parameters {#bizibleparameters-bingadsparameters}

* `_bt={adid}`
* utm_medium=cpc
* utm_source=bing
* utm_term={keyword}

#### Facebook Parameters {#bizibleparameters-facebookparameters}

* `_bf ={creative}`

    * `This represents the creative ID or name`

