---
unique-page-id: 10098379
description: Use Quick Sync with Microsoft Dynamics for a New Custom Field - Marketo Docs - Product Documentation
title: Use Quick Sync with Microsoft Dynamics for a New Custom Field
---

# Use Quick Sync with Microsoft Dynamics for a New Custom Field {#use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field}

Use Quick Sync with Microsoft Dynamics for a New Custom Field - Marketo Docs - Product Documentation

Marketing or Sales wants a new field. Or, maybe you forgot one in your initial field selection. Or, your needs changed. In any case, you can use Quick Sync to resync specific fields.

Normally, you’ll use Quick Sync to add a new field and have values refreshed. However, there are cases where you might want to sync an existing field. You can restrict the field sync based on an updated or created date range. See [Advanced Sync Options](#UseQuickSyncwithMicrosoftDynamicsforaNewCustomField-Advanced_Sync_Options) below for details.

Quick Sync can sync null values. For example, if you are using values A and B, and change a B value in Dynamics to null, it will sync the null value to Marketo.

### What's in this article? {#what-s-in-this-article}

[Quick Sync for All Records](#usequicksyncwithmicrosoftdynamicsforanewcustomfield-quicksyncforallrecords)  
[Advanced Sync Options](#usequicksyncwithmicrosoftdynamicsforanewcustomfield-advanced-sync-optionsadvancedsyncoptions)  
[Fixing Out of Sync Fields](#usequicksyncwithmicrosoftdynamicsforanewcustomfield-fixingoutofsyncfields)

#### Quick Sync for All Records {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-quicksyncforallrecords}

Here's how to use Quick Sync to resync for new fields.

##### 1. In Marketo, click Admin. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-inmarketo-clickadmin.}

![](assets/image2016-8-19-11-3a14-3a5.png)

##### 2. Click Microsoft Dynamics. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-clickmicrosoftdynamics.}

![](assets/image2016-8-19-11-3a15-3a8.png)

##### 3. On Field Sync Details, click Edit. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-onfieldsyncdetails-clickedit.}

![](assets/image2016-8-19-11-3a16-3a22.png)

##### 4. Select the fields to quick sync and click Save. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-selectthefieldstoquicksyncandclicksave.}

![](assets/image2016-8-25-15-3a26-3a11.png)

>[!NOTE]
>
>You can select fields from multiple entities.

##### 5. You'll receive a notification when the sync is complete. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-you'llreceiveanotificationwhenthesynciscomplete.}

![](assets/field-sync-update-notification.png)

>[!CAUTION]
>
>The sync runs side-by-side with other syncs, and depending on the size of the database, can take a long time to complete. When a field is in a queue for syncing, you can't deselect it.

#### Advanced Sync Options {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-advanced-sync-optionsadvancedsyncoptions}

What if you want to sync an existing field, but only do so for a limited set of data? Here's how.

##### 1. Clear the checkbox for an existing field. Click Save. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-clearthecheckboxforanexistingfield.clicksave.}

![](assets/image2016-8-25-16-3a16-3a32.png)

##### 2. Open the pop-up again and reselect the field. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-openthepop-upagainandreselectthefield.}

![](assets/select-field-reselect-hand.png)

##### 3. Click Advanced Sync. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-clickadvancedsync.}

![](assets/image2016-8-25-15-3a52-3a9.png)

##### 4. Choose Updated and select a date range using the date pickers. Click Save. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-chooseupdatedandselectadaterangeusingthedatepickers.clicksave.}

![](assets/image2016-8-25-16-3a0-3a3.png)

Only records updated between 8/19/16 and 9/19/16 will be Quick Synced for the field.

#### Fixing Out of Sync Fields {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-fixingoutofsyncfields}

In the rare case where a Dynamics and Marketo field are out of sync, there's a quick and easy way to resync them.

##### 1. Deselect the field and click Save. {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-deselectthefieldandclicksave.}

![](assets/image2016-8-25-16-3a16-3a32-1.png)

##### 2. Reselect the field and click Save. That's all! {#usequicksyncwithmicrosoftdynamicsforanewcustomfield-reselectthefieldandclicksave.that'sall!}

![](assets/image2016-8-25-16-3a20-3a45.png)

That should fix it!
