---
unique-page-id: 8783322
description: Validate Microsoft Dynamics Sync - Marketo Docs - Product Documentation
title: Validate Microsoft Dynamics Sync
exl-id: 00297a8d-36c3-42f6-a9b8-4a8dd7c1f30d
feature: Microsoft Dynamics
---
# Validate Microsoft Dynamics Sync {#validate-microsoft-dynamics-sync}

>[!CAUTION]
>
>If you have Multi-Factor Authentication (MFA) enabled for your Dynamics Sync, you must disable it in order for Dynamics to properly sync with Marketo. For additional information, please contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}.

## Run Validate Sync in Marketo {#run-validate-sync-in-marketo}

It's very important to run the Validate Sync tool to make sure your Microsoft Dynamics Sync with Marketo is set up correctly before making the final connection between them. The process generates a checklist of seven setup steps that pinpoint where issues exist. Verifying these were done correctly can save a lot of time later.

1. Click the **[!UICONTROL Admin]** tab and then the **[!DNL Microsoft Dynamics]** link in the Integration area.

   ![](assets/image2015-9-28-16-3a7-3a51.png)

1. Select **[!DNL Microsoft]**.

   ![](assets/image2015-9-28-16-3a10-3a47.png)

1. Click the **[!UICONTROL Validate Sync Setup]** tab.

   ![](assets/image2015-9-28-16-3a11-3a45.png)

1. Enter your Username, Password, and URL (Client Id and Client Secret are optional). Click **[!UICONTROL Next]** when done.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >If you've synced before, **[!UICONTROL CRM]** in the left tree will read **[!DNL Microsoft Dynamics]**, and the data in the above form may be prepopulated.

1. If everything is fine, the Validate Sync generates a checklist full of green checkmarks ![--](assets/check.png).

   ![](assets/image2015-9-22-15-3a58-3a12.png)

1. If you see an ![--](assets/delete.png), then that step has an issue. See [Fix Dynamics Validation Sync Issues](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md){target="_blank"} to identify and fix the problem. Then rerun the sync validation steps until the result looks like the image above.

   >[!CAUTION]
   >
   >We do not currently support sandbox refresh for Marketo Dynamics Sync. If you need to refresh your Dynamics CRM sandbox, a new Marketo sandbox will be required. Please contact the Adobe Account Team (your Account Manager) for additional details.

>[!MORELIKETHIS]
>
>[Fix Dynamics Validation Sync Issues](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md){target="_blank"}
