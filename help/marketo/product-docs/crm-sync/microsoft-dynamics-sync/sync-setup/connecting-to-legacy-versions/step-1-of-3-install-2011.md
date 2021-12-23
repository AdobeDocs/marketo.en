---
unique-page-id: 3571805
description: Step 1 of 3 -Install the Marketo Solution (2011 On-Premises) - Marketo Docs - Product Documentation
title: Step 1 of 3 -Install the Marketo Solution (2011 On-Premises)
exl-id: 6e559b10-5273-4dc2-b98d-49c509cbeff7
---
# Step 1 of 3: Install the Marketo Solution (2011 On-Premises) {#step-of-install-the-marketo-solution-on-premises}

Before you can sync Microsoft Dynamics On-Premises and Marketo, you need to first install the Marketo solution in Dynamics.

>[!NOTE]
>
>After you sync Marketo to a CRM, you cannot perform a new sync without replacing the instance.

>[!PREREQUISITES]
>
>You must have [Internet Facing Deployment](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) with [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0, 2.1 or 3.0 (ADFS) configured. **Note**: The IFD document downloads automatically when you click the link.
>
>[Download the Marketo Lead Management Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) before you start.

>[!NOTE]
>
>**Dynamics Admin Permissions required.**
>
>You need CRM administrator privileges to perform this sync.

1. Log in to **Dynamics**, select **Settings** in the bottom left menu.

   ![](assets/image2015-4-2-11-3a32-3a53.png)

1. Select **Solutions** in the tree.

   ![](assets/image2015-4-2-11-3a35-3a28.png)

1. Click **Import**.

   ![](assets/image2015-4-2-11-3a37-3a33.png)

1. Click **Browse**. Select the Marketo Lead Management solution you [downloaded](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Click **Next**.

   ![](assets/image2015-4-2-11-3a40-3a33.png)

1. View the Solution Information and click **View solution package details**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. When you're done checking all the details, click **Close**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Back on the Solution Information page, click **Next**.

   ![](assets/image2015-4-2-11-3a41-3a48.png)

1. Make sure the SDK message option checkbox is checked. Click **Next**.

   ![](assets/image2015-4-2-11-3a42-3a37.png)

   >[!TIP]
   >
   >You will need to enable pop-ups on your browser to complete the installation process.

1. Now wait for the import to finish. Get up and do some stretches.

   ![](assets/image2015-4-2-11-3a43-3a51.png)

1. Click **Close**.

   >[!NOTE]
   >
   >You may see a message saying "Marketo Lead Management completed with warning". This is fully expected.

   ![](assets/image2015-4-2-11-3a44-3a44.png)

1. Marketo Lead Management will now appear on the **All Solutions** page.

   ![](assets/image2015-4-2-11-3a46-3a55.png)

1. Select Marketo Lead Management and click **Publish All Customizations.**

   ![](assets/image2015-4-2-11-3a48-3a21.png)

Wasn't too bad right? Come on, I'll keep walking you through the rest.

>[!CAUTION]
>
>Disabling any of the Marketo SDK Messaging Processes will result in a broken install!

>[!MORELIKETHIS]
>
>[Step 2 of 3: Set Up Marketo Sync User in Dynamics (2011 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md)
