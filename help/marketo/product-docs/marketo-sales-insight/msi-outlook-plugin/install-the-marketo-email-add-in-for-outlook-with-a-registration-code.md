---
unique-page-id: 2949711
description: Install the Marketo Email Add-in for [!DNL Outlook] with a Registration Code - Marketo Docs - Product Documentation
title: Install the Marketo Email Add-in for [!DNL Outlook] with a Registration Code
exl-id: d7a877c2-f71e-44da-b323-04f6cdb44eb0
---
# Install the Marketo Email Add-in for [!DNL Outlook] with a Registration Code {#install-the-marketo-email-add-in-for-outlook-with-a-registration-code}

If users can access the admin settings on their laptops, you can send a registration code to them directly.

If you haven't received an invite email, ask your Marketo administrator to invite you.

>[!PREREQUISITES]
>
>You must be [issued a Marketo Email Add-in License](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/issue-a-marketo-email-add-in-license.md).

>[!IMPORTANT]
>
>Installation is not supported on PCs where the Windows User folder contains non-English characters. This folder is generated automatically by Windows under `<System Root>\Users\` based on the Windows User name and may contain non-English characters if the Windows User name is a non-English name. Please work with your IT team to verify if you're encountering installation issues.

>[!NOTE]
>
>On 10/1/20, the latest version of the [!DNL Outlook] plug-in stopped supporting offline mode.

## Download Installer {#download-installer}

1. Identify your [[!DNL Microsoft Outlook] version](https://support.office.com/en-us/article/what-version-of-outlook-do-i-have-b3a9568c-edb5-42b9-9825-d48d82b2257c)

1. Click the link to download the installer appropriate for your version of [!DNL Microsoft Outlook].

   >[!NOTE]
   >
   >At this time, the links below are only working in [!DNL Microsoft Edge], or by right-clicking in [!DNL Chrome]. Sorry for any inconvenience.

   | [!DNL Outlook] Version |32-bit [!DNL Outlook] |64-bit [!DNL Outlook] |
   |---|---|---|
   | [!DNL Outlook] 2000 |Not Supported |N/A |
   | [!DNL Outlook] 2003 | [Download](https://munchkin.marketo.net/MarketoAddInSetup32.msi) |N/A |
   | [!DNL Outlook] 2007 | [Download](https://munchkin.marketo.net/MarketoAddInSetup32.msi) |N/A |
   | [!DNL Outlook] 2010 | [Download](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Download](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | [!DNL Outlook] 2013 | [Download](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Download](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | [!DNL Outlook] 2016 | [Download](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Download](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | [!DNL Outlook] 2019 | [Download](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Download](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | [!DNL Outlook] for Mac |Not Supported |Not Supported |
   | [!DNL Outlook] Web App |Not Supported |Not Supported |
   | [!DNL Office] 365* | [Download](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [Download](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |

   *[!DNL Office] 365 version: Windows client only (on [!DNL Windows] 10, [!DNL Enterprise] or [!DNL Pro]).

## Copy Your Registration Code {#copy-your-registration-code}

1. Copy the registration code from the invite email you received.

   ![](assets/image2016-7-22-10-3a45-3a10.png)

1. Close [!DNL Microsoft Outlook].

   ![](assets/ent-key-close-outlook-hand.png)

## Install {#install}

1. Run the installer.

   ![](assets/image2016-7-25-10-3a23-3a33.png)

   >[!NOTE]
   >
   >If you get a security warning, don't worry! Just click **Run**.

1. Click **[!UICONTROL Next]**.

   ![](assets/welcome-to-the-setup-wizard-hand.png)

1. Fill in **[!UICONTROL First Name]**, **[!UICONTROL Last Name]**, **[!UICONTROL Email Address]**, then copy and paste the **[!UICONTROL Registration code]** from the email into the form and click **[!UICONTROL Next]**.

   ![](assets/enter-your-information-hands.png)

   >[!TIP]
   >
   >If the install fails, check with your IT department to ensure that HTTPS traffic is not blocked. The installer requires HTTPS traffic to be open.

1. Click **[!UICONTROL Next]** to install in the default location.

   ![](assets/select-installation-folder-hand.png)

1. Click **[!UICONTROL Next]**.

   ![](assets/confirm-installation-hand.png)

   >[!NOTE]
   >
   >If you get a security prompt about an unknown publisher, click **[!UICONTROL Yes]**.

1. The installation is now complete, click **[!UICONTROL Close]**.

   ![](assets/image2014-9-23-15-3a52-3a11.png)

1. Now open [!DNL Microsoft Outlook] and see the Marketo buttons.

   ![](assets/image2016-8-24-15-3a47-3a38.png)

   Excellent! Now the Marketo buttons are in a better place.

Learn more about using the Marketo Message and Log With Marketo actions.

>[!MORELIKETHIS]
>
>* [Send and Track an Email with the Marketo Email Add-in for [!DNL Outlook]](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-an-email-with-the-email-add-in-for-outlook.md)
>* [Send and Track from [!DNL Outlook] Using a Marketo Template](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md)
