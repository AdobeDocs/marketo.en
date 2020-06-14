---
unique-page-id: 14745730
description: Salesforce Diagnostics - Marketo Docs - Product Documentation
title: Salesforce Diagnostics
---

# Salesforce Diagnostics {#salesforce-diagnostics}

Salesforce Diagnostics - Marketo Docs - Product Documentation

Part of our Salesforce integration includes a Salesforce Diagnostic page within the web application. This page captures errors from failed data logging to Salesforce. The errors can be helpful, but are not always readable. As such, we put together a cheat sheet that helps explain the error messages.

**Error: **API_CURRENTLY_DISABLED  
**Category:** Access/Validation  
**Message:** API is disabled for this user  
**What is Happening:** User doesn't have API Access  
**Troubleshooting Steps:** Salesforce Admin needs to grant the user API Access.

** **

**Error:** AUTHENTICATION_FAILURE  
**Category:** Authentication  
**Message:** invalid_grant: authentication failure  
**What is Happening:** Authentication failed  
**Troubleshooting Steps:** Disconnect from Salesforce and then reconnect.

** **

**Error:** CANNOT_INSERT_UPDATE_ACTIVATE_ENTITY  
**Category:** Access/Validation  
**Message:** {"errorCode":"INVALID_SESSION_ID","message":"Session expired or invalid"}  
**What is Happening:**&nbsp;  
1) Trigger code is causing update to fail.  
2) User does not have object level write permissions on the given object.  
**Troubleshooting Steps:  **1) Review trigger that is failing.  
2) Either grant write access to the user for the object OR disable the feature that is trying to write to the object.

** **

**Error:** CANNOT_UPDATE_CONVERTED_LEAD  
**Category:** Other  
**Message:** cannot reference converted lead  
**What is Happening:** We are trying to log to a converted lead during Most Recent Activity Logging for Contacts and Leads. Also seen a couple of these for pitches.  
**Troubleshooting Steps:** Please report any instances of this to our [support team](http://nation.marketo.com/community/support_solutions).

** **

**Error:** ENTITY_IS_LOCKED  
**Category:** Access/Validation  
**Message:** the entity is locked for editing  
**What is Happening:** The record is in an approval process where it is locked from any additional edits until it is either approved or denied by a person who owns the approval.  
**Troubleshooting Steps:** See above.

** **

** Error: ** EXPIRED_ACCESS** Category: ** Authentication** Message: ** invalid_grant: expired access/refresh token** What is Happening: ** The access or refresh token has expired. Tokens expire based on [session settings in Salesforce](http://salesforce.stackexchange.com/questions/10759/invalid-grant-expired-access-refresh-token-error-when-authenticating-access-via).** Troubleshooting Steps:&nbsp; **You'll need to re-authenticate. Disconnect the Salesforce connection and re-connect.

** **

**Error:** FAILED_WRITE  
**Category:** Intermittent  
**Message:** end of file reached  
**What is Happening:** Performance issue with Salesforce, likely due to sub-optimal triggers on the customer side.  
**Troubleshooting Steps:** Retry logic should handle this. If it's still not working, work with your Salesforce admin to troubleshoot a problematic trigger.

** **

** Error:  ** FIELD_CUSTOM_VALIDATION_EXCEPTION** Category:  ** Access/Validation** Message:  ** Varies from customer to customer.** What is Happening:  ** Failing a custom validation rule for the object.** Troubleshooting Steps:  ** Check the custom validation rule that's causing this error. Since this is a custom rule the error must be dealt with on a one-off basis.

** **

**Error:** FIELD_FILTER_VALIDATION_EXCEPTION  
**Category:** Access/Validation  
**Message:** Value does not exist or does not match filter criteria  
**What is Happening:** Existing bad data in Salesforce getting enforced upon update.  
**Troubleshooting Steps:** See above.

** **

**Error:** FIELD_INTEGRITY_EXCEPTION  
**Category:** Access/Validation  
**Message:** The existing country/territory doesn't recognize the state value for field: State/Province Code  
**What is Happening:** Existing bad data in Salesforce getting enforced upon update.  
**Troubleshooting Steps:** See above.

** **

**Error:** INACTIVE_ORGANIZATION  
**Category:** Authentication  
**Message:&nbsp;**invalid_grant: inactive organization  
**What is Happening:&nbsp;**Your Salesforce organization is no longer active.   
**Troubleshooting Steps:** Disconnect then reconnect from Salesforce.

** Error: ** INACTIVE_USER** Category: ** Authentication** Message: ** invalid_grant: inactive user** What is Happening: ** The Salesforce user is no longer active**. Troubleshooting Steps:&nbsp;**Disconnect then reconnect from Salesforce.

**Error:** INSERT_UPDATE_DELETE_NOT_ALLOWED_DURING_MAINTENANCE  
**Category:** Intermittent  
**Message:** (no additional message)  
**What is Happening:** Salesforce instance is in maintenance mode.  
**Troubleshooting Steps:** Wait until system maintenance is done then retry logging.

** Error:   ** INSUFFICIENT_ACCESS_ON_CROSS_REFERENCE_ENTITY** Category:   ** Access/Validation** Message:   ** insufficient access rights on object id** What is Happening:   ** No access to the parent record for a task.** Troubleshooting Steps: **See above.

** **

**Error:** INSUFFICIENT_ACCESS_OR_READONLY  
**Category:** Access/Validation** ** 
**Message:** insufficient access rights on object id** ** 
**What is Happening:** Most Recent Activity logging can't edit the specific record because the user doesn't have write-to access.  
**Troubleshooting Steps:** Grant the user access in Salesforce OR disable Most Recent Activity logging for that object for that user.

**Error:** INVALID_FIELD  
**Category:** Intermittent  
**Message:** Net::ReadTimeout  
**What is Happening:** Request is timing out. This is likely a result of too many slow transactions.  
**Troubleshooting Steps: **Review existing customizations for potential culprits to the latency issues and/or disable Most Recent Activity logging for one or all objects to reduce the load.

**Error:** INVALID_FIELD_FOR_INSERT_UPDATE  
**Category:** Access/Validation  
**Message:** Unable to create/update fields: ToutApp__Tout_Last_Replied__c. Please check the security settings of this field.&nbsp;   
**What is Happening:** Users don't have write access to the Tout custom fields needed to perform the Most Recent Activity logging transaction. Team may have installed package but has not enabled the correct fields for the users.  
**Troubleshooting Steps:** Salesforce Admin needs to grant access to the custom fields OR turn off Most Recent Activity logging.

**Error:** INVALID_GRANT  
**Category:** Authentication  
**Message:** invalid_grant: ip restricted  
**What is Happening:** We are trying to access your Salesforce, but you have IP Restrictions in place that are preventing us from doing so.  
**Troubleshooting Steps:** `Your Salesforce Admin will need to whitelist our IPs. Users should reach out to Support to get the IP addresses.   
`

**Error:** INVALID_TYPE  
**Category:** Access/Validation  
**Message:&nbsp;**CreatedDate, (SELECT Id FROM Tasks) FROM Lead WHERE Email='emailid'^ERROR at Row:1:Column:53sObject type 'Lead' is not supported. If you are attempting to use a custom object, be sure to append the '__c' after the entity name. Please reference your WSDL or the describe call for the appropriate names  
**What is Happening:** We are trying to query an object type from Salesforce that the user doesn't have access to. This is most likely related to the user has not having the right access to the Lead Object.  
**Troubleshooting Steps:** Either grant Read and Update access to the Lead object in Salesforce, or turn off email logging and Most Recent Activity logging to lead records.

**Error:** QUERY_TIMEOUT  
**Category:** Intermittent  
**Message:** Your query request was running too long  
**What is Happening:** See above.  
**Troubleshooting Steps:** Retry logic should handle this. If it's still not working, work with your Salesforce Admin to troubleshoot a problematic trigger.

**Error:** REQUEST_LIMIT_EXCEEDED  
**Category:** Intermittent  
**Message:** 
1) ConcurrentPerOrgLongTxn Limit exceeded  
2) TotalRequests Limit exceeded  
3) ConcurrentRequest  
**What is Happening:** 
1) Concurrent request limit exceeded, likely due to inefficient trigger code.  
2) Too many integrations put the org past the 24-hour rolling window.  
**Troubleshooting Steps:** 
1) Review existing triggers on the impacted objects. Potentially disable roll-up logging for one or more objects.  
2) Buy more API calls from Salesforce. Potentially disable roll-up logging for one or more objects.

**Error:** REQUIRED_FIELD_MISSING  
**Category:** Access/Validation  
**Message:** Required fields are missing: [Amount_Committed_Private_Capital__c]  
**What is Happening:** This generally happens for Most Recent Activity logging. Custom fields were set up to be required but have empty values in them. This can happen if the record was created with an empty value of the custom field, and was then made to be required. Requiredness is enforced when we are trying to update the record, even though we aren't touching the custom field.  
**Troubleshooting Steps:** Manually update the values of the missing fields. You can then retry the message from ToutApp.

**Error:** SERVER_UNAVAILABLE  
**Category:** Intermittent  
**Message:** server too busy  
**What is Happening:** Performance issue with Salesforce, likely due to sub-optimal triggers by the customer  
**Troubleshooting Steps:** Retry logic should handle this. If it's still not working, work with your Salesforce Admin to trouble shoot a problematic trigger.

**Error:** TXN_SECURITY_NO_ACCESS  
**Category:** Access/Validation  
**Message:** The operation you requested isn't allowed due to a security policy in your organization. Contact your administrator.   
**What is Happening:** Some kind of security restriction has been set up - see `https://developer.salesforce.com/forums/?id="record` ID"  
**Troubleshooting Steps:** Talk to your Salesforce Admin and see what the specific restriction might be.

**Error:** UNABLE_TO_LOCK_ROW  
**Category:** Intermittent  
**Message:** unable to obtain exclusive access to this record or 1 records: "record ID"  
**What is Happening:** Likely there is a trigger that is causing multiple attempts to access the same record, possibly in the case of a group email.  
**Troubleshooting Steps:** Retry logic should handle this. If it's still not working, work with your Salesforce Admin to troubleshoot a problematic trigger.

**Error:&nbsp;**UNKNOWN_EXCEPTION   
**Category:** Other  
**Message:** Unknown Exception occurred  
**What is Happening:** Unhandled exception in Salesforce.  
**Troubleshooting Steps:** File a case with Salesforce and copy the numeric values in the error message. This is Salesforce code not handling an error properly.
