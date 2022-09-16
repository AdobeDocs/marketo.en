---
description: Privacy Requests - Marketo Docs - Product Documentation
title: Privacy Requests
exl-id: ae61eabc-ad8f-4c7b-8097-838e89c1a3ec
---
# Privacy Requests {#privacy-requests}

This document provides an overview of managing individual data privacy requests that you can send to Marketo Engage through the Privacy Service UI and the Privacy Service API.

>[!NOTE]
>
>Privacy requests submitted through Privacy Service UI or API for Marketo Engage apply only to the following:
>
>* Marketo Engage users that have onboarded to Adobe Identity Management System
>
>**-or-**
>
>* Marketo Engage users utilizing another Experience Cloud product that's already on the Adobe Identity Management System (e.g., RT-CDP, B2B and B2P Editions, Audience Manager).

You can submit individual requests to access and delete consumer data from Marketo Engage in two ways:

* Through the [Privacy Service UI](https://privacyui.cloud.adobe.io/). See the documentation [here](https://experienceleague.adobe.com/docs/experience-platform/privacy/ui/user-guide.html){target="_blank"}.
* Through the Privacy Service API. See the documentation [here](https://developer.adobe.com/experience-platform-apis/references/privacy-service/){target="_blank"} and API information [here](https://developer.adobe.com/experience-platform-apis/){target="_blank"}.

The [Privacy Service](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html){target="_blank"} supports two types of requests: data access and data deletion.

Let’s see how you can create Access and Delete requests.

## Required setup to send requests for Marketo Engage {#required-setup-to-send-requests-for-marketo-engage}

To make requests to Access and Delete data for Marketo Engage, you must:

1. Identify the following:

   a. IMS Org ID<br/>
   b. Email Address of the person you want to act on

   An IMS Org ID is a 24-character alphanumeric string appended with @AdobeOrg. If your marketing team or internal Adobe system administrator doesn’t know your organization’s IMS Org ID, contact Adobe Customer Care at gdprsupport@adobe.com. You need the IMS Org ID to submit requests to the Privacy API.

1. In Privacy Service, you can submit Access and Delete requests to Marketo Engage, and check the status of existing requests.

## Required field values in Marketo Engage JSON requests {#required-field-values-in-marketo-engage-json-requests}

“companyContexts”:

* “namespace”: **imsOrgID**
* “value”: `<Your IMS Org ID Value>`

“users”:

* “action”: either **access** or **delete**
* “userIDs”:
  * “namespace”: **email**
  * “type”: **standard**
  * “value”: `<Data Subject’s Email Address>`

“include”:

* **marketo** (which is the Adobe product that applies to the request)

“regulation”:

* **gdpr**, **ccpa**, **pdpa**, **lgpd_bra**, or **nzpa_nzl**  (which is the privacy regulation that applies to the request)

## Example One: GDPR Delete Request {#gdpr-delete-request}

JSON Request

```text
{
  "companyContexts": [
    {
      "namespace": "imsOrgID",
      "value": "1231659F56A68A8B7F000101@AdobeOrg"
    }
  ],
  "users": [
    {
      "action": [
        "delete"
      ],
      "userIDs": [
        {
          "namespace": "email",
          "type": "standard",
          "value": "john.doe@adobe.com"
        }
      ]
    }
  ],
  "include": [
    "marketo"
  ],
  "regulation": "gdpr",
}
```

JSON Response

```text
{
  "requestId": "16331241037112570RX-245",
  "totalRecords": 1,
  "jobs": [
    {
      "jobId": "997b01e3-9568-402c-904b-b4e60a437875",
      "customer": {
        "user": {
          "action": [
            "delete"
          ],
          "userIDs": [
            {
              "namespace": "email",
              "value": "john.doe@adobe.com",
              "type": "standard",
              "namespaceId": 6,
              "isDeletedClientSide": false
            }
          ]
        }
      }
    }
  ]
}
```

## Example Two: CCPA Access Request {#ccpa-access-request}

JSON Request

```text
{
  "companyContexts": [
    {
      "namespace": "imsOrgID",
      "value": "1231659F56A68A8B7F000101@AdobeOrg"
    }
  ],
  "users": [
    {
      "action": [
        "access"
      ],
      "userIDs": [
        {
          "namespace": "email",
          "type": "standard",
          "value": "john.doe@adobe.com"
        }
      ]
    }
  ],
  "include": [
    "marketo"
  ],
  "regulation": "ccpa",
}
```

JSON Response

```text
{
  "requestId": "16329573462631890RX-207",
  "totalRecords": 1,
  "jobs": [
    {
      "jobId": "3115e42d-011b-47ab-a2b0-ed4356af4d3e",
      "customer": {
        "user": {
          "action": [
            "access"
          ],
          "userIDs": [
            {
              "namespace": "email",
              "value": "john.doe@adobe.com",
              "type": "standard",
              "namespaceId": 6,
              "isDeletedClientSide": false
            }
          ]
        }
      }
    }
  ]
}
```

>[!MORELIKETHIS]
>
>[Privacy Management](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/privacy-management.md)
