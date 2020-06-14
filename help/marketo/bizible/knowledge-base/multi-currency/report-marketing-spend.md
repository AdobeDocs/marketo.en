---
unique-page-id: 27656737
description: Report Marketing Spend - Bizible - Product Documentation
title: Report Marketing Spend
---

# Report Marketing Spend {#report-marketing-spend}

Report Marketing Spend - Bizible - Product Documentation

#### Marketing Spend Table {#reportmarketingspend-marketingspendtable}

The Marketing Spend table will now contain a new column to display the currency for each Channel, Subchannel, and Campaign row. This new column will display for all customers, even if they don’t have Multiple Currencies enabled.

The table will now contain a mix of different currencies. Please refer to the Marketing Spend dashboard if you need to get a sum of any Channels, Subchannels, or Campaigns in a single currency.

#### Upload Costs {#reportmarketingspend-uploadcosts}

When a user downloads the cost file, the file will also contain a new column with the currency for each row. The only acceptable currencies are those that have been set and stored in the CRM. You will need to know the 3-letter abbreviated code for your currency (i.e. USD, CAD, JPY, EUR) and if a file is uploaded with an unrecognized currency, the file upload will fail.

#### Costs from Ad Integrations {#reportmarketingspend-costsfromadintegrations}

When Bizible imports the cost from connected platforms such as AdWords, Bing, Facebook, or Doubleclick, we also use the reported currency. The currency will display alongside the Channel, Subchannel, and Campaign when displayed in the Marketing Spend table.

If the currency from the Ad Provider doesn’t match a currency that is pulled from the CRM, you may see a “Mixed Currencies” error in Bizible Discover because we were unable to make a conversion on that currency. To fix this, your CRM Admin needs to add a conversion for the unknown currency.

#### Migrate to Converted Marketing Spend {#reportmarketingspend-migratetoconvertedmarketingspend}

Because our marketing spend has historically only been in a single (USD) currency, there is a small amount of work needed to change all reported spend to the new currency. Even if your account doesn’t have Multiple Currencies enabled, if you have a single corporate currency other than USD, you will want to make this migration.

1. Download the current Spend file to a CSV
1. The currency column will display “USD” as the assumed currency. You can either manually replace all the occurrences of “USD” or use Find+Replace to change all the “USD” instances to your own corporate currency, such as “EUR” or “GBP” for example.
1. Save the file then upload it back into Bizible.
1. All of your reported costs will now display as the new currency.

