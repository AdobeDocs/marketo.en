---
unique-page-id: 11385579
description: Create Content Patterns - Marketo Docs - Product Documentation
title: Create Content Patterns
---

# Create Content Patterns {#create-content-patterns}

Create Content Patterns - Marketo Docs - Product Documentation

>[!NOTE]
>
>Depending on the purchase date, your Marketo subscription may include either Marketo Predictive Content or Content`<sup>AI</sup>`. For those using Predictive Content, Marketo is enabling Content`<sup>AI</sup>` Analytics features until April 30, 2018. To keep these features beyond that date, please contact your Marketo Customer Success Manager to upgrade to Marketo Content`<sup>AI</sup>`.

`When you set content patterns, content is auto-discovered when a web visitor clicks on the HTML web page relevant to the content pattern. It's used to add HTML pages (blog posts, press releases, news articles) as content pieces to the All Content page.`  When auto-discovering is based on content patterns, it discovers and tracks HTML pages that are related to the defined URL pattern when a web visitor views or clicks a link to the page. This content piece (the URL, page name and meta data–including the image URL and description) is added to the All Content page to prepare predictive content. For auto-discovering other content, such as PDFs and embedded video, you need to [enable content discovery](welcome-to-marketo-docs/product-docs/predictive-content/getting-started-(predictive-content-and-content-ai)/enable-content-discovery.md).

##### 1. Go to Content Settings.  {#createcontentpatterns-gotocontentsettings.}

![](assets/settings-dropdown-hand-2.png)

##### 2. Click URL Patterns. {#createcontentpatterns-clickurlpatterns.}

![](assets/click-url-patterns-hand.png)

##### 3. Click the + to open up a row where you can enter your information. {#createcontentpatterns-clickthe+toopenuparowwhereyoucanenteryourinformation.}

![](assets/content-settings-create-patterns-hand.png)

##### 4. Add the URL extension of the domain where the web page exists. Select the category (for example, Blog, Article, Data Sheet, Press Release). {#createcontentpatterns-addtheurlextensionofthedomainwherethewebpageexists.selectthecategory(forexample-blog-article-datasheet-pressrelease).}

![](assets/content-settings-create-content-patterns-dm-hands.png)

>[!NOTE]
>
>Items in the drop-down list on the right reflect the categories you set up when you [created categories](welcome-to-marketo-docs/product-docs/predictive-content/getting-started-(predictive-content-and-content-ai)/set-up-categories.md).

##### 5. Click + to add another path. {#createcontentpatterns-click+toaddanotherpath.}

![](assets/url-patterns-add2.png)

##### 6.  Add the extension and catagory for the additional path and click Save. {#createcontentpatterns-addtheextensionandcatagoryfortheadditionalpathandclicksave.}

![](assets/url-patterns-save.png)

#### Content Pattern Rules {#createcontentpatterns-contentpatternrules}

* You can use a wildcard anywhere in an expression (Example: *domain.com/&#42;*, *domain.com/&#42;blog&#42;*)

* We recommend using /&#42; at the end of an expression to continue pattern discovery (Example: *domain.com/blog/&#42;* discovers all posts in the Blog folder)
* Content patterns are not case sensitive (Example: *domain.com/Blog/&#42;* discovers all html pages on *domain.com/Blog* and *domain.com/blog*)

* URL parameters are not discovered (this avoids discovering multiple items with the same content URL but different parameters)

#### Examples {#createcontentpatterns-examples}

For *domain.com*:

<table class="confluenceTable"> 
 <tbody> 
  <tr> 
   <th>URL Pattern</th> 
   <th>Result</th> 
  </tr> 
  <tr> 
   <td>blog/*</td> 
   <td><p>Discovers all content that matches the pattern domain.com/blog/:</p><p>domain.com/blog/5-top-tricks</p><p>domain.com/blog/2017/new-year-solutions</p><p>domain.com/Blog/3-best-recipes</p></td> 
  </tr> 
  <tr> 
   <td>article/2017/*</td> 
   <td><p>Discovers all content that matches the pattern domain.com/article/2017/:</p><p>domain.com/article/2017/5-top-tricks</p></td> 
  </tr> 
  <tr> 
   <td><img class="confluence-embedded-image confluence-thumbnail" alt="--" width="80" src="assets/image2017-3-24-10-3a38-3a46.png" data-linked-resource-id="12976559" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="11385579" title="--"></td> 
   <td><p>Discovers any URL that contains the word "datasheets:"</p><p>domain.com/datasheets/5-top-tricks</p><p>domain.com/blog/5-top-datasheets</p></td> 
  </tr> 
  <tr> 
   <td>press-release</td> 
   <td><p>Only one exact match HTML page is discovered:</p><p>domain.com/press-release</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> </td> 
   <td colspan="1"><p>If the URL expression is empty, the URL pattern discovers only the home page:</p><p>domain.com</p></td> 
  </tr> 
 </tbody> 
</table>

