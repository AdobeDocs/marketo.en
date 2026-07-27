---
description: Learn how Marketo's 25-month and 90-day data retention policies affect Analytics reports, with a per-report breakdown and tips for retaining data longer.
title: Data retention
feature: Reporting
---
# Marketo activity data retention policy - Impact on reporting

Marketo retains marketing activity data on a rolling basis. Activity and Campaign Membership data is stored for a rolling 25 months past the activity date, and high-volume activity data is retained for a rolling period of 90 days past the activity date by default, which can be adjusted per user. Beyond these retention periods, the data is no longer available through the Marketo UI.

## Marketo Analytics reports

Because activity data is retained for up to 25 months, some Marketo Analytics reports are affected by this policy while others are not. Reports that draw data from person activity logs will only show data for up to 25 months. Reports that do not reference person activity at all are unaffected.

However, even reports that do not reference person activity by default can be affected if filters are added to the report's smart list. Filters that reference person attributes (information in fields on the person record) do not cause any change to the report. Filters that look for activities the person has taken can only access activities within the retention window, so if the activity occurred longer ago than that, the results of the report will be altered.

The table below summarizes how each report behaves, including common filter scenarios.

## Report reference

| Report Type | Filter Scenario | Affected by Retention Policy? |
|---|---|---|
| **Revenue Cycle Explorer Reports** | No filters available | No: Revenue Cycle Explorer and Advanced Analytics users are fully exempt from these retention limits. RCE data is sent overnight into a separate database server that manages RCE reporting. Because it is housed separately, and not in person activity logs, these reports are not affected by this policy. Revenue Cycle Explorer does not pull data from the person database directly, so filters are not available. |
| **People Performance Report** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **People by Status** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **People by Revenue Stage** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **Success Path Analyzer** | Does not include Smart Lists | N/A |
| **Social Influence Report** | No Smart List filters | Yes |
| | Filters on person attributes (Ex: First Name) | Yes |
| | Filters on person activities within the last 25 months | Yes |
| | Filters on person activities with no date constraint | Yes |
| **Opportunity Influence Analyzer** | Does not include Smart Lists | No |
| **Email Performance** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **Email Link Performance** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **Email Insights** | Does not use Smart Lists | No |
| **Sales Insight Email Performance** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **Landing Page Performance** | No Smart List filters | No: Landing Page Performance data is retained indefinitely and is not subject to the retention policy. |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | No |
| **Web Page Activity** | No Smart List filters | Yes: Subject to the 90-day default retention period (adjustable per user) |
| | Filters on person attributes (Ex: First Name) | Yes |
| | Filters on person activities within the last 25 months | Yes |
| | Filters on person activities with no date constraint | Yes |
| **Company Web Activity** | No Smart List filters | Yes |
| | Filters on person attributes (Ex: First Name) | Yes |
| | Filters on person activities within the last 25 months | Yes |
| | Filters on person activities with no date constraint | Yes |
| **Program Performance** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **Engagement Stream Performance** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **Program Analyzer** | Does not use Smart Lists | No |
| **Campaign Activity** | No Smart List filters | No |
| | Filters on person attributes (Ex: First Name) | No |
| | Filters on person activities within the last 25 months | No |
| | Filters on person activities with no date constraint | Yes |
| **Campaign Email Performance** | No Smart List filters | Yes |
| | Filters on person attributes (Ex: First Name) | Yes |
| | Filters on person activities within the last 25 months | Yes |
| | Filters on person activities with no date constraint | Yes |

## Reporting workarounds

Activity data older than the retention window may be considered stale by many users. However, you may have a use case where this information is needed. Below are ways to retain this data beyond the standard retention period.

## Export the data

Marketo offers the [Bulk Extract REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/bulk-extract/bulk-extract), which lets you export person activities and house them locally. Once the data is extracted over the API, you can store and sort it however you need for your use case.

>[!TIP]
>
>Export your person data on a regular schedule, not just one time. The person activities are retained on a rolling 25-month cycle. Set a reminder to export again _before_ the end of that 25-month timeframe.

## Use custom fields

Person field values are not affected by the Data Retention Policy. You can use Smart Campaigns to populate custom fields with values based on activities your people take. This lets you filter people by these person attributes (not subject to the retention policy) rather than by the activities themselves (which are subject to the retention policy).

An additional benefit of this approach is that searching by person attributes is faster than searching through person activity logs.
