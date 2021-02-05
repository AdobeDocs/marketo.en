---
unique-page-id: 11382815
description: Marketo Outlook Plugin Installation by IT - Marketo Docs - Product Documentation
title: Marketo Outlook Plugin Installation by IT
---

# Marketo Outlook Plugin Installation by IT {#marketo-outlook-plugin-installation-by-it}

Sometimes corporate policies require that their IT Team installs all software on their employees’ computers. In these cases, IT often does this remotely using their own deployment software. This doc provides the command lines you would use as inputs during the deployment process to remotely install the outlook plug-in.

>[!PREREQUISITES]
>
>[Set up](http://docs.marketo.com/display/DOCS/Install+the+Marketo+Add-in+for+Outlook+with+an+Enterprise+Key) the Enterprise Key.

Run the following command line as the as ‘System’ or an Administrative user account with the /i switch to install.  `<pre>msiexec.exe /i [File Name] /qn REG=[Enterprise Key]</pre>`  

>[!NOTE]
>
>**Example**
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn REG=ABC9-123y-WXYZ-4321</pre>`

For troubleshooting, you can enable logging to create an output log file.  `<pre>msiexec.exe /i [File Name] /qn /L*v MarketoAddin.log REG=[Enterprise Key]</pre>`  

>[!NOTE]
>
>**Example**
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn /L*v MarketoAddin.log REG=ABC9-123y-WXYZ-4321</pre>`

To specify a location of the log files, you can specify the file path in the command line.  `<pre>msiexec.exe /i [File Name] /qn /L*v [File Path]MarketoAddin.log REG=[Enterprise Key]</pre>`  

>[!NOTE]
>
>**Example**
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddin.log REG=ABC9-123y-WXYZ-4321</pre>`

>[!CAUTION]
>
>The storage location of the log file must exist or the installation will be aborted.

Please refer to [Microsoft’s complete list of switches](https://support.microsoft.com/en-us/kb/227091) if you would like to try different logging levels or user interface levels. 

>[!MORELIKETHIS]
>
>[Marketo Outlook Plugin Uninstall by IT](marketo-outlook-plugin-uninstall-by-it.md)

