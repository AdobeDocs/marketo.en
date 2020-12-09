---
unique-page-id: 2950578
description: Manage Social Profile Data - Marketo Docs - Product Documentation
title: Manage Social Profile Data
---

# Manage Social Profile Data {#manage-social-profile-data}

When someone interacts with a Marketo [social app](../../../../product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md), or authorizes their social network to prefill a Marketo form with [social form fill](../../../../product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md), Marketo captures all the data available from their social profile. You can view this information on the [Person Details page](http://docs.marketo.com/display/DOCS/Using+the+Person+Detail+Page), or add it as a column in a [custom view of a smart list](http://docs.marketo.com/display/DOCS/Create+and+Change+Views+for+Lists+and+Smart+List).

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Social form fill and social apps capture slightly different sets of fields; see the section for each below.

>[!NOTE]
>
>**Availability**
>
>Not all customers have purchased this functionality. Contact your sales rep for details.

## Captured via Social App {#captured-via-social-app}

Depending on the network's and user's privacy settings, one or more of these fields are retrieved:

>[!NOTE]
>
>The additional information from social networks appears on the Person Details page about five minutes after the person authorizes.

## From Twitter: {#from-twitter}

* First Name (parsed from Display Name)
* Last Name (parsed from Display Name)
* Profile photo URL
* Profile page URL
* Social reach (number of followers)

>[!NOTE]
>
>Social apps do not fetch the person's email address.

## From Facebook: {#from-facebook}

* First Name
* Last Name
* Profile URL
* Profile photo URL
* Gender
* Social reach (number of friends)

### Captured via Social Form Fill {#captured-via-social-form-fill}

Depending on the network's and user's privacy settings, one or more of these fields are retrieved:

>[!CAUTION]
>
>Data captured by social form fill overwrites matching fields unless you [block updates to those fields at the form level](../../../../product-docs/administration/field-management/block-updates-to-a-field.md).

## From Twitter: {#from-twitter-1}

* First Name (parsed from Display Name)
* Last Name (parsed from Display Name)
* Email

## From Facebook: {#from-facebook-1}

* First Name
* Last Name
* Email
* Date of Birth
* Job Title
* Company

>[!NOTE]
>
>Social form fill captures the email address *only* if the person enters it in the form. If you need the email address, you should [make it a required field in your form](../../../../product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md).

>[!MORELIKETHIS]
>
>To capture this information from forms, enable [social form fill](../../../../product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md).

>[!NOTE]
>
>**Deep Dive**
>
>Learn more about working with forms in the [Forms](http://docs.marketo.com/display/docs/forms) deep dive.

