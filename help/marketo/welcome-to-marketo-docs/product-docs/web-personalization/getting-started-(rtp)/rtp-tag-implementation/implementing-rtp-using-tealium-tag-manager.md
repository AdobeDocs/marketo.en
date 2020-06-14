---
unique-page-id: 9437340
description: Implementing RTP using Tealium Tag Manager - Marketo Docs - Product Documentation
title: Implementing RTP using Tealium Tag Manager
---

# Implementing RTP using Tealium Tag Manager {#implementing-rtp-using-tealium-tag-manager}

Implementing RTP using Tealium Tag Manager - Marketo Docs - Product Documentation

To implement your RTP tag please follow the installation instructions below.

##### 1. Log in to your Tealium Tag Manager account.  {#implementingrtpusingtealiumtagmanager-logintoyourtealiumtagmanageraccount.}

##### 2. Navigate to the Tags tab and add the Tealium Custom Container Tag, located under the Misc tab of the Tags marketplace. {#implementingrtpusingtealiumtagmanager-navigatetothetagstabandaddthetealiumcustomcontainertag-locatedunderthemisctabofthetagsmarketplace.}

##### 3. In the Title field, enter Marketo RTP and click Finish. {#implementingrtpusingtealiumtagmanager-inthetitlefield-entermarketortpandclickfinish.}

##### 4. Save your changes. {#implementingrtpusingtealiumtagmanager-saveyourchanges.}

>[!NOTE]
>
>There's no need to publish the new container yet.

##### 5. After the profile is saved, click your name/email address in the upper right corner of the Tealium iQ console. {#implementingrtpusingtealiumtagmanager-aftertheprofileissaved-clickyourname/emailaddressintheupperrightcornerofthetealiumiqconsole.}

##### 6. On the Admin menu, click Manage Templates under Account Admin. {#implementingrtpusingtealiumtagmanager-ontheadminmenu-clickmanagetemplatesunderaccountadmin.}

##### 7. Select Tealium Custom Container: Marketo RTP from the drop-down list to open the Tag template.  {#implementingrtpusingtealiumtagmanager-selecttealiumcustomcontainer-marketortpfromthedrop-downlisttoopenthetagtemplate.}

##### 8. Log in to your RTP account. {#implementingrtpusingtealiumtagmanager-logintoyourrtpaccount.}

##### 9. Go to Account Settings. {#implementingrtpusingtealiumtagmanager-gotoaccountsettings.}

>[!NOTE]
>
>If you've already received your JavaScript tag from Support, continue to Step 11.

##### 10. Under Domain, locate the relevant domain and click Generate Tag. {#implementingrtpusingtealiumtagmanager-underdomain-locatetherelevantdomainandclickgeneratetag.}

##### 11. Copy the RTP JavaScript tag and paste it between Start Tag Library Code and End Tag Library Code in your Tealium Profile Template. {#implementingrtpusingtealiumtagmanager-copythertpjavascripttagandpasteitbetweenstarttaglibrarycodeandendtaglibrarycodeinyourtealiumprofiletemplate.}

>[!NOTE]
>
>**Important Steps**
>
>Remove the <!-- RTP tag --> and <!-- End of RTP tag --> tags from the code you place in this file.
>
>Remove any <script type='text/javascript'> and </script> tags from the code you place in this file.

##### 12. Click Save Profile Template and publish your new profile. {#implementingrtpusingtealiumtagmanager-clicksaveprofiletemplateandpublishyournewprofile.}

