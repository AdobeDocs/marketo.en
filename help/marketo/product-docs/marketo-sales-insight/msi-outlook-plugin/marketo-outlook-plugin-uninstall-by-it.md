---
unique-page-id: 11382829
description: Learn how IT can uninstall the Marketo Outlook plugin. Remove the add-in from user machines when needed.
title: Marketo [!DNL Outlook] Plugin Uninstall by IT
exl-id: 678684da-3e99-462f-9950-504df1c1bb1e
feature: Marketo Sales Insights
TQID: https://experienceleague.adobe.com/p2CjKHycrJRHLpphyn2qsUEKP-dWh2OlTezwrOn9Ljw
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
topic_v2:
  - id: c1579802-ddd4-4214-8a91-97b2066abe11
    internal-label: Troubleshooting
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
---
# Marketo [!DNL Outlook] Plugin Uninstall by IT {#marketo-outlook-plugin-uninstall-by-it}

Here's how IT can uninstall the Marketo [!DNL Outlook] Plugin remotely.

Run the following command line as the as as ‘System’ or an Administrative user account with the /x switch to uninstall.

`<pre>msiexec.exe /x [File Name] /qn </pre>`

>[!NOTE]
>
>**Example**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn </pre>`

For troubleshooting you can enable logging to create an output log file.

`<pre>msiexec.exe /x [File Name] /qn /L*v MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**Example**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v MarketoAddinUninstall.log</pre>`

To specify a location of the log files, you can specify the file path in the command line.

`<pre>msiexec.exe /x [File Name] /qn /L*v [File Path]MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**Example**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddinUninstall.log</pre>`

>[!CAUTION]
>
>Uninstalling the plugin remotely will forcefully close [!DNL Outlook] on the user’s machine.

Please refer [Microsoft’s complete list of switches](https://support.microsoft.com/en-us/office/command-line-switches-for-microsoft-office-products-079164cd-4ef5-4178-b235-441737deb3a6) if you would like to try different logging levels or user interface levels.
