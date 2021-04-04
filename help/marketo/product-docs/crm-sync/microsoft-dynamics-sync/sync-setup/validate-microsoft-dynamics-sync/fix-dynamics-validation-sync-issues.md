---
unique-page-id: 10095429
description: Fix Dynamics Validation Sync Issues - Marketo Docs - Product Documentation
title: Fix Dynamics Validation Sync Issues
exl-id: 1a300249-65b7-49b1-bf50-82236916298f
---
# Fix Dynamics Validation Sync Issues {#fix-dynamics-validation-sync-issues}

## Validate Sync Tool Results {#validate-sync-tool-results}

When you run the Dynamics Validate Sync, it generates this report. If there's an ![delete](assets/delete.png) next to a step, see below to identify and fix the problem. Then rerun the sync validation steps until the result shows nothing but checkmarks.

![](assets/image2015-9-22-15-3a58-3a12.png)

## URL is valid {#url-is-valid}

If you have an ![delete](assets/delete.png) here, verify that the URL is valid. Find it here in Developer Resources and look at Organization Service. The URL could be invalid for a number of reasons.

1. Log-in to Dynamics. Click the Settings icon and select **Advanced Settings**.

   ![](assets/one.png)

1. Click Settings and select **Customizations**.

   ![](assets/two.png)

1. Click **Developer Resources**.

   ![](assets/three.png)

1. The Organization Service URL can be found under Service Endpoints.

   ![](assets/four.png)

## Username and password are valid {#username-and-password-are-valid}

If you have an ![--](assets/delete.png) here, verify that your Microsoft Dynamics username and password are valid.

## Sync user is assigned to the Marketo Sync User role {#sync-user-is-assigned-to-the-marketo-sync-user-role}

If you have an ![--](assets/delete.png) here, you need to verify that the Marketo Sync User role is checked in Microsoft Dynamics. See Step 2 of the MIcrosoft Dynamics installation documentation.

1. In Dynamics, click the Settings icon and select **Advanced Settings**.

   ![](assets/one.png)

1. Click **Settings** and select **Security**.

   ![](assets/six.png)

1. Click **Users.**

   ![](assets/image2015-9-24-9-3a47-3a25.png)

1. Click the link for the sync user.

   ![](assets/seven.png)

1. Click **Manage Roles**.

   ![](assets/eight.png)

1. Verify that the Marketo Sync User role is checked. If not, check it and click **OK.**

   ![](assets/image2015-9-24-9-3a59-3a21.png)

## Marketo solution is properly installed {#marketo-solution-is-properly-installed}

If you have an ![--](assets/delete.png) here, Go to Microsoft Dynamics to verify the Marketo installation is there. See Step 1 of the MIcrosoft Dynamics setup documentation.

1. In Dynamics, click the Settings icon and select **Advanced Settings**.

   ![](assets/one.png)

1. Click **Settings** and select **Solutions.**

   ![](assets/eleven.png)

1. Verify the solution is listed.

   ![](assets/twelve.png)

## All steps in the solution are enabled {#all-steps-in-the-solution-are-enabled}

If you have an ![--](assets/delete.png) here, verify that none of the default steps have been deactivated. All steps are automatically enabled at installation, but they could be deactivated during a customization.

## Sync user is assigned to the Marketo solution {#sync-user-is-assigned-to-the-marketo-solution}

If you have an ![--](assets/delete.png) here, make sure the Sync user is assigned on the Marketo Default page in Microsoft Dynamics.

1. In Dynamics, click the Settings icon and select **Advanced Settings**.

   ![](assets/one.png)

1. Click **Settings** and select **Marketo Config**.

   ![](assets/thirteen.png)

1. Verify that the sync user is assigned as the default.

   ![](assets/fourteen.png)

## Sync user matches username and password {#sync-user-matches-username-and-password}

If you have an ![--](assets/delete.png) here, be sure to assign the proper sync user in the Marketo User field in the Marketo Config Default setup step in Microsoft Dynamics.

>[!MORELIKETHIS]
>
>[Validate Microsoft Dynamics Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md)
