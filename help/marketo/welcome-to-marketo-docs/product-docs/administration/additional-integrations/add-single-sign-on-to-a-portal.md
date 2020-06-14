---
unique-page-id: 2360356
description: Add Single Sign-On to a Portal - Marketo Docs - Product Documentation
title: Add Single Sign-On to a Portal
---

# Add Single Sign-On to a Portal {#add-single-sign-on-to-a-portal}

Add Single Sign-On to a Portal - Marketo Docs - Product Documentation

If you have a directory service that authenticates users, you can allow single sign-on (SSO) into Marketo. We support this feature using Security Assertion Markup Language (SAML) version 2.0 and higher.

Marketo functions as a SAML Service Provider (SP), and depends on an external Identity Provider (IdP) to authenticate users.

Once SSO is enabled, the IdP can validate a user’s credentials. When a user wishes to use Marketo software, the IdP then sends a signed SAML message to Marketo, acting as the SP. This message vouchsafes to Marketo that the user is authorized to use Marketo software.

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>Are you a Microsoft Azure user? Check out their [integration tutorial](https://azure.microsoft.com/en-us/documentation/articles/active-directory-saas-marketo-tutorial/).

### What's in this article? {#what-s-in-this-article}

[How to Send the Request](#addsinglesign-ontoaportal-howtosendtherequest)  
[Additional Notes](#addsinglesign-ontoaportal-additionalnotes)  
[Update SAML Settings](#addsinglesign-ontoaportal-updatesamlsettings)  
[Update Redirect Page Settings](#addsinglesign-ontoaportal-updateredirectpagesettings)

#### How to Send the Request {#addsinglesign-ontoaportal-howtosendtherequest}

* Send the SSO request, which is a SAML response, to https://login.marketo.com/saml/assertion/<your-munchkin-id>
* As the SP’s Audience URL. Use [http://saml.marketo.com/sp](http://saml.marketo.com/sp)
* If you are using the SPNameQualifier attribute, set the NameID element for Subject to [http://saml.marketo.com/sp](http://saml.marketo.com/sp)
* If you are federating multiple Marketo subscriptions to the same SSO provider, you can use unique SP urls for each Marketo sub with the format http://saml.marketo.com/sp/<munchkin_id>

>[!NOTE]
>
>Marketo only supports Identity Provider-initiated (also known as IdP-initiated), in which the user first launches the Idp login page, authenticates, then navigates to My Marketo.

#### Additional Notes {#addsinglesign-ontoaportal-additionalnotes}

* **Sync-up time** - For a new user, there is about a 10 minute delay before an initial SSO request is processed. 
* **User Provisioning** - Users are provisioned manually by Marketo.
* **Authorization** - User permissions are maintained within Marketo.
* **OAuth support** - Marketo does not currently support OAuth.

>[!NOTE]
>
>`Before starting, have your Identity Provider Certificate in X.509 format and in .crt, .der, or .cer extension.`

#### Update SAML Settings {#addsinglesign-ontoaportal-updatesamlsettings}

SSO is disabled by default. Follow these steps to enable SAML and configure it.

##### 1. Go to Admin and click Single Sign-On. {#addsinglesign-ontoaportal-gotoadminandclicksinglesign-on.}

![](assets/image2014-9-24-14-3a36-3a50.png)

>[!NOTE]
>
>If you don't see **Single Sign-On** under **Admin**, contact [ `[email protected]`](http://mailto:support@marketo.com).

##### 2. Under the SAML Settings section, click on Edit. {#addsinglesign-ontoaportal-underthesamlsettingssection-clickonedit.}

![](assets/image2014-9-24-14-3a37-3a3.png)  

##### 3. Change SAML Single Sign-On to Enabled. {#addsinglesign-ontoaportal-changesamlsinglesign-ontoenabled.}

![](assets/image2014-9-24-14-3a37-3a17.png)  

##### 4. Enter your Issuer ID, Entity ID, select the User ID Location, then click Browse. {#addsinglesign-ontoaportal-enteryourissuerid-entityid-selecttheuseridlocation-thenclickbrowse.}

![](assets/image2014-9-24-14-3a37-3a32.png)  

##### 5. Select your Identity Provider Certificate file. {#addsinglesign-ontoaportal-selectyouridentityprovidercertificatefile.}

![](assets/image2014-9-24-14-3a38-3a8.png)  

##### 6. Click Save. {#addsinglesign-ontoaportal-clicksave.}

![](assets/image2014-9-24-14-3a38-3a22.png) 

#### Update Redirect Page Settings {#addsinglesign-ontoaportal-updateredirectpagesettings}

##### 1. Under the Redirect Pages section, click Edit. {#addsinglesign-ontoaportal-undertheredirectpagessection-clickedit.}

![](assets/seven.png)

>[!NOTE]
>
>Customers using Universal ID along with SSO must enter the login URL of the Identity Provider in the **Login URL** field.

##### 2. Enter a Logout URL. This is the URL you want the user to be directed to when they log out of Marketo. {#addsinglesign-ontoaportal-enteralogouturl.thisistheurlyouwanttheusertobedirectedtowhentheylogoutofmarketo.}

![](assets/eight.png)  

##### 3. Enter an Error URL. This is the URL you want the user to be directed to in case logging into Marketo fails. Click Save. {#addsinglesign-ontoaportal-enteranerrorurl.thisistheurlyouwanttheusertobedirectedtoincaseloggingintomarketofails.clicksave.}

![](assets/nine.png)

>[!NOTE]
>
>Both these pages must be publicly available.

