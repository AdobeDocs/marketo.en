---
unique-page-id: 2359798
description: Add Additional Landing Page CNAMEs - Marketo Docs - Product Documentation
title: Add Additional Landing Page CNAMEs
---

# Add Additional Landing Page CNAMEs {#add-additional-landing-page-cnames}

You may want to add landing page CNAMEs to allow different URLs to point to your Marketo landing pages. Following the steps below will help you manage multiple domains.

>[!CAUTION]
>
>Cookies are not shareable across domains.

>[!TIP]
>
>**Same top level domain - Good! Cookies are shared.go**.mycompany.com > **info**.mycompany.com**Different top level domains - Bad! Cookies are not shared.** 
>go.**mycompany**.com > go.**mynewcompany**.com

>[!NOTE]
>
>**Admin Permissions Required**

### What's in this article? {#whats-in-this-article}

[Find Your Account String](#find-your-account-string)  
[Send Request to IT](#send-request-to-it)  
[Add a New CNAME](#add-a-new-cname)

#### Find Your Account String {#find-your-account-string}

1. Go to the **Admin** area and click **Landing Pages**.

   ![](assets/image2014-9-16-15-3a19-3a54.png)

1. Copy the **Account String** from the **Settings** section.

   ![](assets/image2014-9-16-15-3a20-3a2.png)

1. Make a note of it for the next step.

#### Send Request to IT {#send-request-to-it}

1. Ask your IT department to setup the following CNAME: (Replace the word [CNAME] with the CNAME of your choice and [ACCOUNT STRING] with the text from the previous step).

   [CNAME].YourCompany.com > [ACCOUNT STRING].mktoweb.com

#### Add a New CNAME {#add-a-new-cname}

1. Once your IT department has created the CNAME, go to&nbsp;**Admin**&nbsp;then click **Landing Pages**.

   ![](assets/image2014-9-16-15-3a20-3a20.png)

1. Click **New**&nbsp;then select **New Domain Alias**.

   ![](assets/image2014-9-16-15-3a20-3a28.png)

1. Enter your&nbsp;**Domain Alias.**&nbsp;The&nbsp;**Default Page**&nbsp;is displayed if the visitor does not put in a URL. Enter where they should go in that case.

   >[!NOTE]
   >
   >For the Default Page, you can select a landing page or an external URL, such as your public website.

   ![](assets/image2014-9-16-15-3a20-3a36.png)

1. Enter your&nbsp;**Default Page**&nbsp;and click&nbsp;**Create**.

   ![](assets/image2014-9-16-15-3a20-3a43.png)

Nice! Now you know what to do if you ever want to add a&nbsp;CNAME.
