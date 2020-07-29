---
unique-page-id: 2360189
description: Customize Your Landing Page URLs With a CNAME (Administration) - Marketo Docs - Product Documentation
title: Customize Your Landing Page URLs With a CNAME (Administration)
---

# Customize Your Landing Page URLs With a CNAME (Administration) {#customize-your-landing-page-urls-with-a-cname-administration}

Even though Marketo hosts your landing pages, the URL should be customized for your company.

>[!NOTE]
>
>**Example**
>
>No CNAME:
>
>http://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html
>
>Branded CNAME:
>
>http://go.**YourCompany**.com/UnsuscribePage.html

>[!NOTE]
>
>**Admin Permissions Required**

Let's get you set up!

### What's in this article? {#whats-in-this-article}

[1. Choose a CNAME](#choose-a-cname)  
[2. Find your Account String](#find-your-account-string)  
[3. Send Request to IT](#send-request-to-it)  
[4. Complete CNAME Setup](#complete-cname-setup)

1. Choose a CNAME

   It's the front part of the URL. Examples:

    * **go**.YourCompany.com/NameOfPage.html
    * **info**.YourCompany.com/NameOfPage.html
    * **pages**.YourCompany.com/NameOfPage.html

   The one word (plus YourCompany.com) is called a CNAME. You will need this later so make a note of it.

1. Find your Account String
1. Go to the **Admin** area and click on **Landing Pages**.

   ![](assets/image2014-9-16-13-3a9-3a44.png)

1. Under the **Landing Pages **tab, copy the Account String from the Settings section.

   ![](assets/image2014-9-16-13-3a9-3a57.png)

1. You will also need this later, so make a note of it.
1. Send Request to IT
1. Ask your IT staff to setup the following CNAME (replace the word [CNAME] and [ACCOUNT STRING] with the text from the previous step):

   [CNAME].YourCompany.com > [ACCOUNT STRING].mktoweb.com

1. Complete CNAME Setup
1. Once your IT has created the CNAME, go to **Admin** and click on **Landing Pages**.

   ![](assets/image2014-9-16-13-3a10-3a14.png)

1. Under the **Settings** section, click **Edit**.

   ![](assets/image2014-9-16-13-3a10-3a31.png)

1. Enter your CNAME in **Domain name for Landing Pages**, enter your **Fallback page**, enter your **Homepage**, and click **Save**.

   ![](assets/image2014-9-16-13-3a10-3a45.png)

   Your fallback page is where people will be redirected if your Marketo landing page is unavailable.
   Nice job! Your landing pages are now branded with your company domain.

