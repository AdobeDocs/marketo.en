---
description: Update Activity Type Field When Logging Activities to Salesforce - Marketo Docs - Product Documentation
title: Update Activity Type Field When Logging Activities to Salesforce
exl-id: 800323cb-2b99-42f1-ae30-0f87a9a1b4be
---
# Update Activity Type Field When Logging Activities to Salesforce {#update-activity-type-field-when-logging-activities-to-salesforce}

Actions can automatically sync your email and call activities to Salesforce to be used for reporting and increase visibility into activity history. When logging activities, make sure the Activity Type field is properly updated to Email, Call, or Reply, depending on what type of activity is being logged.

>[!NOTE]
>
>Logging emails via BCC will not look to the Task Type picklist, and will instead automatically populate the type field as "email" since they're being delivered to Salesforce through your BCC address.

## Things to Know {#things-to-know}

* A connection with Salesforce is required for the Task Type to update.
* There should be no default Type value selected on the Task Type picklist.
* Call, Reply, and Email must all exist in the Task Type picklist (capitalization matters).
* Workflows or Triggers in Salesforce that update the Task Type field may interfere with this process.

## Setup {#setup}

First check that you have the correct picklist values in place. You'll need the help of your Salesforce Admin to make any changes to your picklist.

First check which values you're missing in your Task Type Picklist (out of Email, Call, and Reply). You may need the help of your Salesforce Admin to review this and make changes to your Activity Type picklist. To make these changes, your Salesforce Admin can follow the steps below.

### In Salesforce Lightning {#salesforce-lightning}

1. Navigate to [Salesforce.com](https://salesforce.com){target="_blank"}.
1. Click the gear icon in the top right corner and select **Setup** > **Object Manager**.
1. Type "task" in the 'Quick Find' box.
1. In the left panel, click **Fields & Relationships**.
1. Click field label **Type**.
1. Under Task Type Picklist Value, click **New**.
1. Type the name of the Task Type Picklist Values that are missing ("Email, "Call", "Reply").
1. Click **Save**.

### In Salesforce Classic {#salesforce-classic}

1. Navigate to [Salesforce.com](https://salesforce.com){target="_blank"}.
1. Click **Setup** > **Build** > **Customize** > **Activities** > **Task Fields**.
1. Click **Type**.
1. Under Task Type Picklist Value, click **New**.
1. Type the name of the Task Type Picklist Values that are missing ("Email, "Call", "Reply").
1. Click **Save**.

Now that this is in place, you'll begin to see the Type field populate the corresponding value for logged Emails, Calls, and Replies. These values will _not_ be populated on Sales Insight Actions reminder tasks.

>[!NOTE]
>
>If you don't see 'Reply' as a value, add it by clicking **New**. 'Reply' is not a standard value in Salesforce.

>[!MORELIKETHIS]
>
>* [Logging Sales Activity Attributes to Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"}
>* [Configure Salesforce Activity Detail Customization](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md){target="_blank"}
>* [Sync Sales Activities to Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md){target="_blank"}
