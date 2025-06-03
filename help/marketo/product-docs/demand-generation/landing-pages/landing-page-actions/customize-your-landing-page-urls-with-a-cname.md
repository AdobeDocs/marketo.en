---
unique-page-id: 2359746
description: Customize Your Landing Page URLs with a CNAME - Marketo Docs - Product Documentation
title: Customize Your Landing Page URLs with a CNAME
exl-id: 2cd87785-61e5-46cd-b1e0-6fbc145014d4
feature: Landing Pages
---
# Customize Your Landing Page URLs with a CNAME {#customize-your-landing-page-urls-with-a-cname}

Even though Marketo hosts your landing pages, the URL can be totally customized. What it looks like without a CNAME:

`https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html`

The way it should look:

`https://go.YourCompany.com/UnsubscribePage.html`

## Choose a CNAME {#choose-a-cname}

Pick a word to go at the beginning of the URL for your landing pages. It's just one word and should be relatively short. Examples:

* go.YourCompany.com/NameOfPage.html
* info.YourCompany.com/NameOfPage.html
* pages.YourCompany.com/NameOfPage.html

The one word (plus YourCompany.com) is called a CNAME. You'll need this later so make a note of it.

## Find your Munchkin ID {#find-your-munchkin-id}

1. Go to the **Admin** area.

   ![](assets/customize-your-landing-page-urls-with-a-cname-1.png)

1. Click **My Account**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-2.png)

   >[!NOTE]
   >
   >**Admin Permissions Required**

1. Scroll down to "Support Information" and copy your Munchkin ID.

   ![](assets/customize-your-landing-page-urls-with-a-cname-3.png)

## Send Request to IT {#send-request-to-it}

Ask your IT staff to setup the following CNAME: (Replace the word [CNAME] and [Munchkin ID] with the text from the previous step.)

[CNAME].YourCompany.com > [Munchkin ID].mktoweb.com

## Complete CNAME Setup {#complete-cname-setup}

1. Once your IT has created the CNAME, go to the **Admin** area.

   ![](assets/customize-your-landing-page-urls-with-a-cname-4.png)

1. Click **Landing Pages**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-5.png)

1. Under the **Settings** section, click **Edit**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-6.png)

1. Enter your CNAME in **Domain name for Landing Pages**, enter your **Fallback page**, enter your **Homepage** and click **Save**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-7.png)

>[!NOTE]
>
>Your fallback page will be the page leads will get redirected to if your Marketo Landing Page is unavailable.

Nice job! Your landing pages are now branded with your company domain.
