---
unique-page-id: 18874606
description: UTM Parameters - Bizible - Product Documentation
title: UTM Parameters
---

# UTM Parameters {#utm-parameters}

UTM Parameters - Bizible - Product Documentation

Tagging URLs is a simple and effective way to capture data about your digital marketing efforts. It is the process of adding parameters to the end of URLs that gather and record data. The most commonly used parameters are Urchin Tracking Modules (UTMs), which are supported by Google. There are five main UTMs parameters available: Medium, Source, Campaign, Content, and Term. These are discussed in more detail in the next section.

UTM parameters can be added manually to URLs or appended through auto-tagging with certain platforms, such as AdWords for example. Auto-tagging automates the process of appending parameters to URLs. There is also the option of [URL builders](http://ga-dev-tools.appspot.com/campaign-url-builder/) to speed up tagging URLs manually. With a URL builder, you simply need to specify the values to be used for each parameters and the builder will format the URL for you.

#### What are UTM Parameters? {#what-are-utm-parameters}

To understand how UTM parameters work, let’s look at a typical URL without UTMs:

* `http://www.bizible.com`*

Now, let’s check out a URL with UTMs:

* `http://www.bizible.com` `/`?utm_medium=socialmedia&utm_source =facebook&utm_campaign=seasonal-sale&utm_content=photo-400x700px*

As you can see, the second link contains much more text. UTM parameters always go after the top-level domain (.com in this example) and begin with a question mark. After this, the order of the parameters don't matter, but following a consistent naming convention is advised. Ampersands need to be placed between each parameter to separate each UTM. Now we can go into more detail about what each parameter represents.

Learn about [best practices for setting up UTM parameters](http://docs.marketo.com/x/bAEgAQ).

##### utm_medium {#utm-medium}

* Medium identifies the vehicles you are using to market your company.
* It answers the question: "How are they getting to you?"
* It denotes the highest level channel.
* Social media, email, organic search, and paid search are all examples of potential Medium values.
* This parameter maps data to the Bizible ‘Medium’ field. 
* *Bizible Best Practice:* Do not use this field to call out a subchannel, otherwise, you may experience difficulties generating reports on the actual channel. Use it to identify your marketing vehicle or channel. For example, if you want to use email to market your product, the medium is email.

##### utm_source {#utm-source}

* Source identifies the subchannel that is the source of your traffic.
* It answers the question: "Where is this person coming from?" 
* In a social media example, the source of traffic is the social media platform being used.

    * In this example, Facebook is the Source Value. Other examples are Twitter and Instagram. If the UTM Medium is Paid Search, on the other hand, the UTM Source could be AdWords or BingAds.

* This parameter maps to the Bizible 'Touchpoint Source' field in SFDC.
* Bizible Best Practice: This parameter tracks the source of your traffic, so it is not suitable to use it to indicate the ad type, E.g. retargeting, sponsored, etc. It is best used to track the higher level subchannel. Remember, you are answering the question “where is my traffic coming from?” You are looking for the referrer. In this example, UTM Source is the place where your ad is located (not the actual webpage, as that is automatically tracked outside of tags). If you are tracking a drip-email campaign, then drip email is the source.

##### utm_campaign {#utm-campaign}

* Campaign is used to identify a specific marketing campaign. 
* It answers the question: “Why are they coming to you?” 
* Use this tag to denote the name of the ad campaign as it exists in Google AdWords or BingAds, or to indicate the name by which you identify the campaign internally. You can even use this tag to specify other information such as geolocation or ad network type.
* This parameter maps to the Bizible 'Ad Campaign Name field' in SFDC.
* *Bizible Best Practice:* When determining campaign names, avoid using punctuation marks or empty spaces between the words, because using them can lead to browser encoding errors. For best results, use underscores instead.

##### utm_content {#utm-content}

* Use the UTM Content parameter when you want to track more than one marketing piece existing on a single web page. For example, if you have a “Request a Demo” button and a “Sign Up for Our Weekly Newsletter” button, and wanted to know which one is generating the most traffic, you would name each one and use a UTM Content tag to track them. The name of each piece of “content” is the tag’s value. 
* This parameter maps to the Bizible 'Ad Content' field in SFDC.
* *Bizible Best Practice:* This is an optional value but Bizible recommends using it. This tag is associated with the title of the ad or marketing piece you want to track. If you use an image ad, be sure to write the dimensions of the image in its title.

##### utm_term {#utm-term}

* Term is similar to the UTM Content parameter. Term is great for identifying keywords in ads for paid campaigns. If you use the auto-tagging feature, this is done for you. If you are not using your ad platform’s auto-tagging feature, be sure to carefully add all the keywords you would like to track.
* This parameter maps to the Bizible 'Keyword Text' field in SFDC. 
* *Bizible Best Practice*: The UTM Term tag is optional but great for tracking keywords. Double check spelling and avoid using special characters. If more than one word is needed, try to use underscores or no spaces at all.

Each parameter gathers information relevant to the value assigned. The value of each tag allows you to track and sort all of your digital campaigns and answer the questions: where, how, and why?

Here's a chart of the UTM parameters Bizible parses and the corresponding Touchpoint field they are tied to:

| **UTM Parameter** |**Corresponding Bizible Field** |
|---|---|
| utm_medium |Medium |
| utm_source |Touchpoint Source |
| utm_campaign |Ad Campaign Name |
| utm_content |Ad Content |
| utm_term |Keyword Text |

>[!NOTE]
>
>**Related Articles**
>
>[Bizible University: Online Channel Setup](https://universityonline.marketo.com/courses/bizible-fundamentals-channel-management/#/page/5c63007334d9f0367662b753)
>
>[Bizible University: Creating Channels & Subchannels](https://universityonline.marketo.com/courses/bizible-fundamentals-channel-management/#/page/5c63007334d9f0367662b747)

