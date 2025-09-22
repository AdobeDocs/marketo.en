---
description: "Product Usage Dashboards - Marketo Docs - Product Documentation"
title: Product Usage Dashboards
hide: yes
hidefromtoc: yes
feature: Administration
exl-id: a0fa5cd0-a61d-4383-88c0-9f2a4b2c717a
---
# Product Usage Dashboards {#product-usage-dashboards}

Marketo Engage Product Usage Dashboards provide the ability to view product and platform usage against certain limits or backlog of data through-put, usage against daily quota, and key metrics in your subscription. Infrastructure is allocated to provide performance limits defined for product levels for particular attributes. Some of these limits, like API usage, are contracted limits purchased as part of your package or Product Tier.

## How to Access {#how-to-access}

1. In Marketo Engage, click **Admin**.

   ![](assets/product-usage-dashboards-1.png)

1. In the tree on the left, scroll down and select **Product Usage Dashboards**.

   ![](assets/product-usage-dashboards-2.png)

## Activity Usage Dashboard {#activity-usage-dashboard}

### Average Weekly Activities {#average-weekly-activities}

The Weekly Activity Usage dashboard provides a weekly count of Activity Types over a rolling 52-week period. Weekly activities produced are a good indicator of how much marketing you're doing in Marketo Engage. Activities serve as a proxy for the various system processes and trackable events that take place within Marketo.

Activity Types include both counts of activities captured when people/leads interact with marketing events as well as system-based activities triggered by Flow Actions. Some examples of person-initiated activities are when a recipient opens an email you sent them, or clicks on a link in an email. An example of a system-based activity triggered by a Flow Action is _Send to SFDC_ when the trigger is initiated.

>[!TIP]
>
>To view a count of activity types for a particular week, hover over the desired week and the count appears.

#### FAQ {#faq}

**Which Activity Types are counted?**

It's contingent upon what activities are included in the pipeline.

**Is both known and anonymous person/lead activity included?**

Only known people/leads.

**How often is the data refreshed?**

Activity counts are refreshed every morning.

## Activity Breakdown {#activity-breakdown}

Here we get counts of activities over the previous seven days based on meaningful slices of the data. Group activities by the most common activity types seen in the last seven days. This may include categories like _Change Data Value_, _Add to List_, or _Send Email_. This lets you see what types of activities are happening most often in the system. Activity Type usage is a key indicator of determining growth, or if optimizations are needed to reduce usage.

>[!NOTE]
>
>* All the breakdowns below are a rolling seven-day sum and do **not** include the current day. So think of it as "yesterday + six days before that."
>
>* The dashboard only shows the top 20 activity types, while the rest are sorted into a category titled "Other."

Activity usage shows you how much marketing is being conducted, and helps visualize growth against identified for the level of product contracted for. Dashboards can also be used as a guide to determine how much optimization can/should be done by reducing the fields being updated.

### By Type {#by-type}

Group activities by the most common activity types seen in the last seven days. This may include categories like _Change Data Value_, _Add to List_, or _Send Email_. This lets you see what types of activities are happening the most often in your Marketo Engage account.

### By Change Data Value Attribute {#by-change-data-value-attribute}

_Change Data Value_ is the most common activity type. It indicates when a piece of information on a person/lead record is updated. Here, we group by the fields that are changed most often so you can determine what information is useful for your marketing operations, if there are opportunities to optimize platform usage, etc.

### By Campaign {#by-campaign}

Group by which campaigns are producing the most activities. This allows you to see if you have any particularly "noisy" campaigns that create more activity than necessary. Quickly learn about campaigns that should be decommissioned, or campaigns that are doing more work than intended.
