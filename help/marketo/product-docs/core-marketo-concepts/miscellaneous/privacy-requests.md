---
description: Privacy Requests - Marketo Docs - Product Documentation
title: Privacy Requests
---
# Privacy Requests {#privacy-requests}

This document provides an overview of managing individual data privacy requests that you can send to Marketo Engage through the Privacy Service UI and the **Privacy Service API**.

You can submit individual requests to access and delete consumer data from Marketo Engage in two ways:

* Through the [Privacy Service UI](https://privacyui.cloud.adobe.io/). See the documentation [here](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html#!api-specification/markdown/narrative/tutorials/privacy_service_tutorial/privacy_service_ui_tutorial.md).
* Through the **Privacy Service API**. See the documentation [here](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html#!api-specification/markdown/narrative/tutorials/privacy_service_tutorial/privacy_service_api_tutorial.md) and the API reference [here](https://www.adobe.io/apis/experiencecloud/gdpr/api-reference.html#!acpdr/swagger-specs/privacy-service.yaml).

The [Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) supports two types of requests: data access and data deletion.

Note: Privacy requests submitted through Privacy Service UI or API for Marketo Engage apply only to customers who have Marketo Engage + RT-CDP, B2B and B2P Editions.

Let’s see how you can create Access and Delete requests.

## Required setup to send requests for Marketo Engage {#required-setup-to-send-requests-for-marketo-engage}

To make requests to access and delete data for Marketo Engage, you must:

1. Identify the following:

   a. IMS Org ID<br/>
   b. Email Address of the person you want to act on

   An IMS Org ID is a 24-character alphanumeric string appended with @AdobeOrg. If your marketing team or internal Adobe system administrator doesn’t know your organization’s IMS Org ID, contact Adobe Customer Care at gdprsupport@adobe.com. You need the IMS Org ID to submit requests to the Privacy API.

1. In Privacy Service, you can submit Access and Delete requests to Marketo Engage, and check the status of existing requests.

## Required field values in Marketo Engage JSON requests {#required-field-values-in-marketo-engage-json-requests}

“companyContexts”:

* “namespace”: **imsOrgID**
* “value”: <Your IMS Org ID Value>

“users”:

* “key”: <Your Request Tracking Key>   (optional)
* “action”: either **access** or **delete**
* “userIDs”:
  * “namespace”: **email**
  * “type”: **standard**
  * “value”: <Data Subject’s Email Address>

“include”:

* **marketo** (which is the Adobe product that applies to the request)

“regulation”:

* **gdpr**, **ccpa**, **pdpa**, **lgpd**, or **nzpa**  (which is the privacy regulation that applies to the request)

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
      "key": "AAGDPRO1", 
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
          "key": "AAGDPRO1",
          "action": [
            "delete"
          ],
          "userIDs": [
            {
              "namespace": "email",
              "value": " john.doe@adobe.com",
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
      "key": "AAGDPRO1",
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
      "jobId": " 3115e42d-011b-47ab-a2b0-ed4356af4d3e",
      "customer": {
        "user": {
          "key": "AAGDPRO1",
          "action": [
            "access"
          ],
          "userIDs": [
            {
              "namespace": "email",
              "value": " john.doe@adobe.com",
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