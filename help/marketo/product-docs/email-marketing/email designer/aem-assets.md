---
title: Work with Experience Manager Assets
description: Learn how you can use image assets from a connected AEM Assets repository when authoring content in Adobe Marketo Engage.
hide: yes
hidefromtoc: yes
---
# Work with Experience Manager assets

When Adobe Experience Manager Assets as a Cloud Service is integrated with Adobe Marketo Engage, you can easily discover and access digital assets for use in your marketing content. As you author your content, the assets are accessible from the _[!UICONTROL Assets]_ item on the left navigation, and when authoring email content for an account journey. You can also upload assets to connected AEM Assets as a Cloud Service repository directly from Adobe Journey Optimizer B2B Edition.

>[!NOTE]
>
>Currently, only image assets from Adobe Experience Manager Assets are supported in Adobe Journey Optimizer B2B Edition. Changes to the assets must be done from the Adobe Experience Manager Assets central repository. [Learn more](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/manage/manage-digital-assets)

When you use these digital assets, the latest changes in Assets as a Cloud Service automatically propagate to live email campaigns through linked references. If images are deleted in Adobe Experience Manager Assets as a Cloud Service, the images appear with a broken reference in the emails. When assets that are currently used within account journeys are modified or deleted, the journey authors are notified about the image changes and the list of journeys using the image. All changes to the assets must be done in the Adobe Experience Manager Assets central repository.

## Use AEM Assets as the image source

If your environment has one or more Assets repositories connections, you can designate AEM Assets as the source for assets when you create or view details for an email, email template, or visual fragment.

* When you create a new content, choose `AEM Assets` as the **[!UICONTROL Image Source]** item in the dialog.

SCREENSHOT

* When you open an existing content resource, choose `AEM Assets` in the _[!UICONTROL Body]_ panel on the right.

SCREENSHOT

## Access assets for authoring

>[!IMPORTANT]
>
>An administrator must add users who need access to Assets to the Assets Consumer Users or/and Assets Users Product profiles. [Learn more](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/security/ims-support#managing-products-and-user-access-in-admin-console)

In the visual content editor, click the _Asset selector_ icon in the left sidebar. This changes the tools panel to a list of available assets in the selected repository.

SCREENSHOT

If you have more than one connected AEM repositories, click the menu arrow for **[!UICONTROL Repository]** to choose the repository you want to use.

SCREENSHOT

There are multiple methods for adding an image asset to the visual canvas:

* Drag and drop an image thumbnail from the left navigation.

SCREENSHOT

* Add an image component to the canvas and click **[!UICONTROL Browse]** to open the _[!UICONTROL Select Assets]_ dialog. 

   From the dialog, you can choose an image from the selected repository. 
   
   There are multiple tools available to help you locate the asset that you need.

SCREENSHOT
   
   * Change the **[!UICONTROL Repository]** at the top right.

   * Click **[!UICONTROL Manage assets]** at the top right to open the Assets repository in another browser tab and use AEM Assets management tools.

   * Click the _View type_ selector at the top right to change the display to **[!UICONTROL List View]**, **[!UICONTROL Grid View]**, **[!UICONTROL Gallery View]**, or **[!UICONTROL Waterfall View]**.

   * Click the _Sort order_ icon to change the sort order between ascending and descending.

   * Click the **[!UICONTROL Sort by]** menu arrow to change the sort criteria to **[!UICONTROL Name]**, **[!UICONTROL Size]**, or **[!UICONTROL Modified]**.

   * Click the _Filter_ icon on the top left to filter the displayed items according to your criteria.

   * Enter text in the Search field to filter the displayed items for a match of the asset name.

SCREENSHOT
