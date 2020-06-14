---
unique-page-id: 14352484
description: How to Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce - Marketo Docs - Product Documentation
title: How to Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce
---

# How to Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce {#how-to-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

How to Fix "We Were Unable to Authenticate Your Request" When Connecting to Salesforce - Marketo Docs - Product Documentation

If you receive the error message "We were unable to authenticate your request" when trying to connect Sales Connect to Salesforce, there might be a restriction on your access to Salesforce's API. Check with your Salesforce Admin to make sure the following things are in place.

#### Enable API in User Permissions {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-enableapiinuserpermissions}

##### 1. Have a Salesforce Admin log into SFDC. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-haveasalesforceadminlogintosfdc.}

##### 2. Select Setup. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-selectsetup.}

##### 3. Select Manage Users. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-selectmanageusers.}

##### 4. Select Profiles. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-selectprofiles.}

##### 5. Find the Profile that the ToutApp users are under and click Edit. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-findtheprofilethatthetoutappusersareunderandclickedit.}

##### 6. Scroll down to Administrative Permissions and make sure API Enabled is checked. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-scrolldowntoadministrativepermissionsandmakesureapienabledischecked.}

#### Check if Salesforce is Blocking Sales Connect from Connecting {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-checkifsalesforceisblockingsalesconnectfromconnecting}

##### 1. Have a Salesforce Admin log in to SFDC. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-haveasalesforceadminlogintosfdc..1}

##### 2. Select Setup. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-selectsetup..1}

##### 3. Select Manage Apps. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-selectmanageapps.}

##### 4. Select Connected Apps OAuth Usage. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-selectconnectedappsoauthusage.}

##### 5. Make sure that Sales Connect shows "Block" next to it. If you see "Unblock", click the button to unblock Sales Connect's access to Salesforce. {#howtofix"wewereunabletoauthenticateyourrequest"whenconnectingtosalesforce-makesurethatsalesconnectshows"block"nexttoit.ifyousee"unblock"-clickthebuttontounblocksalesconnect'saccesstosalesforce.}

