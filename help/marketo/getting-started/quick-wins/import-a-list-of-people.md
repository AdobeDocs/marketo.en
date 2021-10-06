---
unique-page-id: 2359418
description: Import a List of People - Marketo Docs - Product Documentation
title: Import a List of People
exl-id: a85ec787-7b22-4666-84fd-d7bf23d32cd4
---
# Import a List of People {#import-a-list-of-people}

## Mission: Import a spreadsheet list of trade show attendees into your database {#mission-import-a-spreadsheet-list-of-trade-show-attendees-into-your-database}

>[!PREREQUISITES]
>
>[Get Set Up and Add a Person](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)

In this tutorial, you'll learn how to import people from a spreadsheet file into Marketo.

## Step 1: Download and Edit a Spreadsheet {#step-download-and-edit-a-spreadsheet}

1. To start, download our practice spreadsheet file ([**tradeshow-attendees.csv**](/help/marketo/getting-started/assets/tradeshow-attendees.csv)) to your computer.

   ![](assets/image2014-9-24-12-3a5-3a0.png)

   >[!NOTE]
   >
   >When importing a date, use this format: **9/21/20** (Month/Day/Year).

   >[!NOTE]
   >
   >Any date/time fields being imported are treated as Central Time. If you have date/time fields in a different time zone, you can use an Excel formula to transform it to Central Time (America/Chicago).

1. Add your own first name, last name, email address, and job title, then save the file on your computer.

   ![](assets/image2014-9-24-12-3a5-3a30.png)

>[!NOTE]
>
>Enter your real email address in the CSV file so you can receive the nurturing emails you'll send in the next mission.

## Step 2: Create a Program {#step-create-a-program}

1. Go to the **Marketing Activities** area.

   ![](assets/ma-2.png)

1. Select your **Learning** folder, then under **New** click **New Program**.

   ![](assets/image2014-9-24-12-3a21-3a13.png)

1. **Name** the program "My Tradeshow Program" and select "Event" for the **Program Type**.

   ![](assets/image2014-9-24-12-3a21-3a25.png)

1. Select **Tradeshow** for the **Channel** and click **Create**.

   ![](assets/image2014-9-24-12-3a21-3a39.png)

>[!NOTE]
>
>Event programs occur on specific dates. Learn more about [**Events**](/help/marketo/product-docs/demand-generation/events/understanding-events/understanding-event-programs.md).

## Step 3: Import Your Spreadsheet into Marketo {#step-import-your-spreadsheet-into-marketo}

1. In **My Tradeshow Program**, click **New** and select **New Local Asset**.

   ![](assets/seven-3.png)

1. Click **List**.

   ![](assets/image2014-9-24-12-3a22-3a56.png)

1. **Name** the list "Tradeshow Attendees" and click **Create**.

   ![](assets/image2014-9-24-12-3a23-3a9.png)

1. In your **Tradeshow Attendees** list, click **List Actions** and select **Import List**.

   ![](assets/ten-2.png)

   >[!CAUTION]
   >
   >If you are using your own CSV file, make sure that it is encoded UTF-8, UTF-16, Shift-JIS, or EUC-JP.

   >[!NOTE]
   >
   >The size limit for CSV files is 100MB.

1. **Browse** to the **tradeshow-attendees.csv** spreadsheet file on your computer and click **Next**.

   ![](assets/eleven-2.png)

   >[!NOTE]
   >
   >In List Import Mode, choosing **Skip new people and updates** means you will not impact existing person records or log any activities. Use this mode if you want a quick, pre-filtered static list of existing people for use in your marketing activities. Selecting this mode will:
   >
   > * Skip new person creation
   > * Skip person field updates
   > * Skip activity logging

1. Map your List Column fields to their respective Marketo Field and click **Next**.

   ![](assets/image2014-9-24-12-3a24-3a49.png)

   >[!TIP]
   >
   >Column headers should always match the field exactly (case sensitive) in order to achieve the best auto-mapping results. If you're using custom fields and don't see them in the drop-down, go back and [create them](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md) so they can become options.

   >[!NOTE]
   >
   >If there are any fields you don't want to import, select **Ignore** in the Marketo Field drop-down menu.

1. Select **My Tradeshow Program** for the **Acquisition Program**, then click **Import**.

   ![](assets/image2014-9-24-12-3a25-3a1.png)

1. Wait for your people to import, then close the import progress pop-up.

   ![](assets/image2014-9-24-12-3a25-3a13.png)

1. Back in **My Tradeshow Program**, click the **Members** tab. You'll see all the people you just imported.

   ![](assets/fifteen-1.png)

>[!NOTE]
>
>You can analyze the success of your program by tracking program membership. Learn more about [**Programs**](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md).

## Mission Complete {#mission-complete}

Your tradeshow attendees are now members of your Marketo program!

<br>&nbsp;

[◄ Mission 4: Email Auto Response](/help/marketo/getting-started/quick-wins/email-auto-response.md)

[Mission 6: Drip, Drip, Nurture ►](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)
