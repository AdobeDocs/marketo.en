---
unique-page-id: 10092969
description: Microsoft Dynamics Sync Filter -Merge - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync Filter -Merge
exl-id: f8da9c3c-0f04-4f61-be03-7e7953d25afe
---
# [!DNL Microsoft] Dynamics Sync Filter: Merge {#microsoft-dynamics-sync-filter-merge}

Merging leads in [!DNL Microsoft Dynamics] uses the Two Options type - Sync filter = Yes (TRUE) and Sync filter = No (FALSE). When you merge two records, the result varies, depending on which record is True and which is False.

The lead records become true or false based on the workflow rules defined by the admin to determine the winner. The sync filter for the winning record is what ultimately determines if the [!DNL MS Dynamics] record syncs with Marketo.

It's when one record is true and one is false that it gets tricky.

| If the sync filter for the losing record is: |and the sync filter for the winning record is: |This is the result in Marketo |
|---|---|---|
| [!UICONTROL True] |[!UICONTROL True] |The winning record continues syncing with Marketo |
| [!UICONTROL False] |[!UICONTROL False] |The winning record continues to **not** sync with Marketo |
| [!UICONTROL False] |[!UICONTROL True] |The winning record will sync with Marketo |
| [!UICONTROL True] |[!UICONTROL False] |The winning record will not sync with Marketo |
