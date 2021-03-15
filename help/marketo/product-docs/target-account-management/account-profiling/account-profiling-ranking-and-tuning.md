---
unique-page-id: 15695924
description: Account Profiling Ranking and Tuning - Marketo Docs - Product Documentation
title: Account Profiling Ranking and Tuning
---

# Account Profiling Ranking and Tuning {#account-profiling-ranking-and-tuning}

Account Profiling identifies your Ideal Customer Profile (ICP), ranks companies in your database based on the ICP, and adds ICP Indicator data to accounts promoted as Named Accounts.

## Model Results {#model-results}

The results show you all of your known accounts broken down by grade. A is the highest grade, D is the lowest.

![](assets/results.png)

While optional, we recommend selecting the Automatically promote checkbox, as it will save you a ton of time. However, if you'd like to go through each account and [add them manually](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md#discover-crm-accounts), simply leave the box unchecked.

<table> 
 <tbody> 
  <tr> 
   <td><strong>Rank</strong></td> 
   <td> 
    <div>
      Account rank based on the Ideal Customer Profile. A is the best fit, D is the least fit. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Propensity</strong></td> 
   <td> 
    <div>
      Estimated increase in conversion rate compared to a non-ICP based selection of accounts. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Accounts (%)</strong></td> 
   <td> 
    <div>
      Percentage of accounts in model input that have this rank. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>% of Model Basis</strong></td> 
   <td> 
    <div>
      Percentage of accounts in model basis that have this rank. 
    </div></td> 
  </tr> 
 </tbody> 
</table>

## Model Tuning {#model-tuning}

In the Model tab, click the Tune Model button.

![](assets/two.png)

There are several tabs to choose from, allowing for in-depth customization.

![](assets/tuning-page.png)

**Indicator Categories**

<table> 
 <tbody> 
  <tr> 
   <td><strong>Compliance</strong></td> 
   <td> 
    <div>
      Certifications, compliance-related positions/hiring. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Operations</strong></td> 
   <td> 
    <div>
      Operations-related positions/hiring. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>HR</strong></td> 
   <td> 
    <div>
      HR or Payroll software, HR-related positions/hiring.
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Engineering</strong></td> 
   <td> 
    <div>
      Technologies, frameworks, engineering-related positions/hiring. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Sales</strong></td> 
   <td> 
    <div>
      Solutions and software for sales, sales-related positions/hiring. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Intent</strong></td> 
   <td> 
    <div>
      Intent indicators. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>IT</strong></td> 
   <td> 
    <div>
      Hardware and software solutions, technologies, IT-related positions/hiring.
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Finance</strong></td> 
   <td> 
    <div>
      Finance software, finance-related positions/hiring. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Marketing</strong></td> 
   <td> 
    <div>
      Marketing technologies and software, marketing-related positions/hiring. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Business</strong></td> 
   <td> 
    <div>
      Forbes or Inc listings or business partnerships. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>Customer Experience & Relations</strong></td> 
   <td> 
    <div>
      Customer success and customer relations positions/hiring.
    </div></td> 
  </tr> 
 </tbody> 
</table>

Hover over the tool tips for a description of each column.

![](assets/tool-tip.png)

Click the Add ICP Indicator drop-down to insert additional indicators into your model.

![](assets/add-icp.png)

Checking the Export box allows you to see the ICP indicator on the Named Account details page, as well as use the selected ICP indicator as constraints in [named account filters](/help/marketo/product-docs/target-account-management/engage/account-filters.md).

![](assets/export.png)

>[!NOTE]
>
>ICP indicators are included as constraints in **Member of Named Account** Filters and Triggers.

Indicator Weightage is what controls the level of importance each indicator receives in your model.

![](assets/weightage.png)

Click Refresh Model in order for those changes to take effect.

![](assets/refresh-button.png)

When you're done tuning your model (after you refresh it), go back to the Model Results tab and click **Save & Apply Ranks**.

![](assets/ranks.png)
