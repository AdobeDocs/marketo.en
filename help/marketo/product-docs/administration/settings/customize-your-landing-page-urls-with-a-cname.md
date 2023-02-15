---
unique-page-id: 2360189
description: Customize Your Landing Page URLs With a CNAME (Administration) - Marketo Docs - Product Documentation
title: Customize Your Landing Page URLs With a CNAME (Administration)
exl-id: a5aa1c76-15f7-4e8c-a736-77c79f65c368
---
# Customize Your Landing Page URLs With a CNAME  {#customize-your-landing-page-urls-with-a-cname}

Even though Marketo hosts your landing pages, the URL should be customized for your company.

>[!NOTE]
>
>No CNAME:
>
>https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html
>
>Branded CNAME:
>
>https://go.**YourCompany**.com/UnsuscribePage.html

>[!NOTE]
>
>**Admin Permissions Required**

Let's get you set up!

1. Choose a CNAME.

   It's the front part of the URL. Examples:

    * **go**.YourCompany.com/NameOfPage.html
    * **info**.YourCompany.com/NameOfPage.html
    * **pages**.YourCompany.com/NameOfPage.html

   The one word (plus YourCompany.com) is called a CNAME. You will need this later so make a note of it.

1. Find your Account String.

1. Go to the **Admin** area. 

   ![](assets/customize-your-landing-page-urls-with-a-cname-1.png)

1. Click **Landing Pages**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-2.png)

1. Under the **Landing Pages** tab, copy the Account String from the Settings section.

   ![](assets/customize-your-landing-page-urls-with-a-cname-3.png)

1. You will also need this later, so make a note of it.

1. Send Request to IT.

1. Ask your IT staff to setup the following CNAME (replace the word [CNAME] and [ACCOUNT STRING] with the text from the previous step):

   [CNAME].YourCompany.com > [ACCOUNT STRING].mktoweb.com

1. Complete CNAME Setup.

1. Once your IT has created the CNAME, go back to the **Admin** area.

   ![](assets/customize-your-landing-page-urls-with-a-cname-4.png)

1. Click **Landing Pages**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-5.png)

1. Under the **Settings** section, click **Edit**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-6.png)

1. Enter your CNAME in **Domain name for Landing Pages**, enter your **Fallback page**, enter your **Homepage**, and click **Save**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-7.png)

Your fallback page is where people will be redirected if your Marketo landing page is unavailable.

Nice job! Your landing pages are now branded with your company domain.
