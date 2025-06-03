---
unique-page-id: 11385579
description: Create Content Patterns - Marketo Docs - Product Documentation
title: Create Content Patterns
exl-id: 963529fb-1b30-486c-b97d-3ff697f91258
feature: Predictive Content
---
# Create Content Patterns {#create-content-patterns}

When you set content patterns, content is auto-discovered when a web visitor clicks on the HTML web page relevant to the content pattern. It's used to add HTML pages (blog posts, press releases, news articles) as content pieces to the All Content page. When auto-discovering is based on content patterns, it discovers and tracks HTML pages that are related to the defined URL pattern when a web visitor views or clicks a link to the page. This content piece (the URL, page name and meta data-including the image URL and description) is added to the All Content page to prepare predictive content. For auto-discovering other content, such as PDFs and embedded video, you need to [enable content discovery](/help/marketo/product-docs/predictive-content/getting-started/enable-content-discovery.md).

1. Go to **Content Settings**.

   ![](assets/settings-dropdown-hand-2.png)

1. Click **URL Patterns**.

   ![](assets/click-url-patterns-hand.png)

1. Click the **+** to open up a row where you can enter your information.

   ![](assets/content-settings-create-patterns-hand.png)

1. Add the URL extension of the domain where the web page exists. Select the category (for example, Blog, Article, Data Sheet, Press Release).

   ![](assets/content-settings-create-content-patterns-dm-hands.png)

   >[!NOTE]
   >
   >Items in the drop-down list on the right reflect the categories you set up when you [created categories](/help/marketo/product-docs/predictive-content/getting-started/set-up-categories.md).

1. Click **+** to add another path.

   ![](assets/url-patterns-add2.png)

1. Add the extension and catagory for the additional path and click **Save**.

   ![](assets/url-patterns-save.png)

## Content Pattern Rules {#content-pattern-rules}

* You can use a wildcard anywhere in an expression (Example: _domain.com/&#42;_, _domain.com/&#42;blog&#42;_)

* We recommend using /&#42; at the end of an expression to continue pattern discovery (Example: _domain.com/blog/&#42;_ discovers all posts in the Blog folder)
* Content patterns are not case sensitive (Example: _domain.com/Blog/&#42;_ discovers all html pages on _domain.com/Blog_ and _domain.com/blog_)

* URL parameters are not discovered (this avoids discovering multiple items with the same content URL but different parameters)

## Examples {#examples}

For _domain.com_:

<table> 
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
   <td><img alt="--" width="80" src="assets/image2017-3-24-10-3a38-3a46.png" data-linked-resource-id="12976559" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="11385579" title="--"></td> 
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
