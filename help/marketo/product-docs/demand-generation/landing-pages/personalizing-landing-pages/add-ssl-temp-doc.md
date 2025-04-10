---
description: Add SSL to Your Landing Pages - Marketo Docs - Product Documentation
title: Add SSL to Your Landing Pages
hide: yes
hidefromtoc: yes
feature: Landing Pages
exl-id: 00ec2d91-3d4f-4671-af9d-9750c1642d40
---
# Add SSL to Your Landing Pages {#add-ssl-to-your-landing-pages}

SSL (Secure Socket Layer) encryption lets you make all of your Landing Pages for a Marketo Engage instance secure.

When you fill out a web form or visit a Landing Page that's hosted by Marketo Engage, by default, the information is sent over non-secure protocol (HTTP). Per your company's policy, you may want to secure the information submitted to Marketo over (HTTPS). For example, when you visit `http://info.mydomain.com/` it will now be `https://info.mydomain.com/`.

Marketo Engage tracks "Visited Web Page" and "Click Link on Web Page" by default over non-secure HTTP protocol. If you want to have your tracking links secured with their own certificate, you need to have Marketo build a separate non-shared server to enable it. To secure all aspects of a contact's interaction with you typically means securing both Landing Pages and tracking links.

## Enable SSL certification {#enable-ssl-certification}

Automatically add SSL for all the domain aliases you create as part of the Landing Page rules.

1. Go to the **Admin** area.

   ![](assets/add-ssl-to-your-landing-pages-1.png)

1. Select **Landing Pages** from the tree. In the **Rules** tab, click the **New** drop-down and select **New Domain Alias**.

   ![](assets/add-ssl-to-your-landing-pages-2.png)

1. Enter your _Domain Alias_ and _Default Page_. Select the **Generate SSL Certificate** checkbox. Click **Create** when done.

   ![](assets/add-ssl-to-your-landing-pages-3.png)

This automatically adds an SSL certificate for this domain.

## Enable SSL for your default domain {#enable-ssl-default-domain}

Follow the steps below to enable SSL for your default domain.

1. Still in the **Admin** section, select **Landing Pages**. Click the orange **Edit** button next to _Settings_.

   ![](assets/add-ssl-to-your-landing-pages-4.png){width="800" zoomable="yes"}

   >[!NOTE]
   >
   >If desired, you can also modify the domain name here (valid domain required).

1. Select the "Generate SSL Certificate" checkbox and click Save.

   ![](assets/add-ssl-to-your-landing-pages-5.png)

>[!NOTE]
>
>* The SSL Certificate column in the listing shows certificate status for all the domain alias created after this feature is released (DATE). If you had the SSL enabled for a domain through Marketo Support, the certificate will continue to exist, but won't show in the table. This table only reflects SSL certificates for domains added using the steps in this article. 
>
>* It can take up to three minutes for the SSL to be in READY state. You must refresh the page for the changes to appear.
