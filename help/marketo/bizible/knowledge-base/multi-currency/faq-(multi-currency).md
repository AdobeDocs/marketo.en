---
unique-page-id: 27656745
description: FAQ (Multi-Currency) - Bizible - Product Documentation
title: FAQ (Multi-Currency)
---

# FAQ (Multi-Currency) {#faq-multi-currency}

FAQ (Multi-Currency) - Bizible - Product Documentation

### What's in this article? {#what-s-in-this-article}

[How do I know which feature bit to enable?](#faq(multi-currency)-howdoiknowwhichfeaturebittoenable?)  
[Why is my ads account giving me a warning message?](#faq(multi-currency)-whyismyadsaccountgivingmeawarningmessage?)  
[What does “Mixed Currencies” mean on my dashboard tile?](#faq(multi-currency)-whatdoes“mixedcurrencies”meanonmydashboardtile?)  
[How can I add a new currency or conversion rate?](#faq(multi-currency)-howcaniaddanewcurrencyorconversionrate?)  
[The currency isn’t displaying in the correct format. How can I change this?](#faq(multi-currency)-thecurrencyisn’tdisplayinginthecorrectformat.howcanichangethis?)  
[Why can’t you display the currency symbol for my selected currency?](#faq(multi-currency)-whycan’tyoudisplaythecurrencysymbolformyselectedcurrency?)  
[What will my customer see if they don’t have multi-currency enabled?](#faq(multi-currency)-whatwillmycustomerseeiftheydon’thavemulti-currencyenabled?)  
[How does this feature affect touchpoint-based reports in the CRM?](#faq(multi-currency)-howdoesthisfeatureaffecttouchpoint-basedreportsinthecrm?)  
[If my customer used a workflow to populate a converted field, how should they use this field moving forward?](#faq(multi-currency)-ifmycustomerusedaworkflowtopopulateaconvertedfield-howshouldtheyusethisfieldmovingforward?)

##### How do I know which feature bit to enable? {#faq(multi-currency)-howdoiknowwhichfeaturebittoenable?}

Keep in mind that there are two different feature bits for this feature. Both are located in the General tab of the CRM section in Settings: Multiple Currencies and Advanced Currencies. Multiple Currencies should be enabled if the customer utilizes more than a single currency, whereas the additional feature bit Advanced Currencies can be enabled if the customer uses Salesforce’s “Advanced Currency Management” feature where the user can set a time-based range for conversion rates.&nbsp;

Unfortunately, we do not know when a customer switches between Simple or Advanced if Advanced has already been turned on. Because of that, the customer needs to keep the Advanced Currencies setting aligned with their CRM setting manually. This should be apparent to the customer if the conversions are incorrect, which means we didn’t know which level of conversion to apply.

##### Why is my ads account giving me a warning message? {#faq(multi-currency)-whyismyadsaccountgivingmeawarningmessage?}

We will display a warning message next to your ads account that may have currencies coming in from an unsupported currency. If this happens, your dashboards will contain tiles with a “Mixed Currencies” message. We advise that you work with your CRM Admin to make sure this unknown currency contains a conversion in your CRM.&nbsp;

##### What does “Mixed Currencies” mean on my dashboard tile? {#faq(multi-currency)-whatdoes“mixedcurrencies”meanonmydashboardtile?}

If you have a tile that has a “Mixed Currencies” message at the bottom, that means we have imported some costs that are mapped to a currency that we don't recognize. Because all of our conversions must come from the CRM with an actual conversion rate, it means your CRM is missing this currency. We advise that you work with your CRM Admin to make sure this unknown currency contains a conversion in your CRM.

##### How can I add a new currency or conversion rate? {#faq(multi-currency)-howcaniaddanewcurrencyorconversionrate?}

Declaring a new currency or conversion rate can only be done in Salesforce or Dynamics so that there is only a single source of truth for these values. Once a new currency or conversion rate is detected, Bizible will download that and make it available to you. We do not offer an area to enter these rates.

##### The currency isn’t displaying in the correct format. How can I change this? {#faq(multi-currency)-thecurrencyisn’tdisplayinginthecorrectformat.howcanichangethis?}

We understand that some countries have a different way of formatting amounts (e.g., 1,234.00, 1.234, 1 234). But we introduce another level of complexity if we have to not only determine a user’s currency, but their country of origin, since different countries and currencies can be handled differently. The consistent format we have chosen is 1,234.00. This cannot be changed.

##### Why can’t you display the currency symbol for my selected currency? {#faq(multi-currency)-whycan’tyoudisplaythecurrencysymbolformyselectedcurrency?}

Salesforce and Dynamics display their amounts with the 3-letter Conversion Code. So for consistency, our converted amounts also display with the 3-letter Conversion Code and not the symbol.&nbsp;

##### What will my customer see if they don’t have multi-currency enabled? {#faq(multi-currency)-whatwillmycustomerseeiftheydon’thavemulti-currencyenabled?}

If the customer doesn't have the multi-currency feature, we will default to their Currency Locale from the CRM and change all ISO codes that show their spend and revenue in the corporate currency. If this is incorrect and the customer has a mixed use of currency, the solution would be to upgrade to get the multi-currency feature.

##### How does this feature affect touchpoint-based reports in the CRM? {#faq(multi-currency)-howdoesthisfeatureaffecttouchpoint-basedreportsinthecrm?}

For Dynamics and Salesforce customers that use just the basic (non-advanced) currency management, touchpoint revenue amounts should be correctly converted, so CRM reports should work as expected.

There is unfortunately some nuance to how this works for users of Salesforce Advanced Currency Management, due to a longstanding limitation of Salesforce.&nbsp; The short answer to “what do we do in this case” is that we convert revenue amounts using the flat rates that are defined in the basic (i.e. non-advanced) “Manage Currencies” tab.&nbsp; In other words, we ignore the dated exchange rates altogether despite the fact that the customer has defined dated exchange rates.

For the interested reader, here’s why it works this way.&nbsp; Our touchpoints use formula fields to calculate revenue (derived from the associated opportunity amount).&nbsp; Salesforce natively supports currency conversion for these formula calculations, but only for their basic flavor of currency support.&nbsp; It’s impossible for us to define a formula field that references the dated exchange rates. Salesforce simply does not support that capability, so we have no way to reference the dated rates in our revenue calculations despite the fact that those dated rates exist in Salesforce (it sounds crazy but that’s how it works.)

##### If my customer used a workflow to populate a converted field, how should they use this field moving forward? {#faq(multi-currency)-ifmycustomerusedaworkflowtopopulateaconvertedfield-howshouldtheyusethisfieldmovingforward?}

Since our offering will now handle the conversions for the customer, we recommend they remove the workflows and custom field and allow us to import their raw Amount value.

