---
unique-page-id: 15695874
description: Connect BrightTALK to Marketo - Marketo Docs - Product Documentation
title: Connect BrightTALK to Marketo
---

# Connect BrightTALK to Marketo {#connect-brighttalk-to-marketo}

Learn how to connect your BrightTALK channel to your Marketo instance. In order to do this, you must be an Admin for both.

>[!NOTE]
>
>**Admin Permissions Required**

## Steps in BrightTALK {#steps-in-brighttalk}

1. Log-in to [business.brighttalk.com/demandcentral](http://business.brighttalk.com/demandcentral/login) and click **Connect Now**.
1. Under Advanced Marketo Connector, click **Connect**.
1. You will come to the credentials screen, asking for: Client ID, Client Secret, Identity Service URL, and Rest Service URL. To get this information, log-in to Marketo.

   ## Steps in Marketo {#steps-in-marketo}

   >[!NOTE]
   >
   >At this point you'll be required to set up an API Only User Role and API User in order to restrict what permissions BrightTALK will have in your Marketo instance. Because we already have articles for those steps, we'll link you to them.

1. Create an [API Only User Role](http://docs.marketo.com/x/iwMk).
1. [Create an API User](http://docs.marketo.com/x/jwMk), using the BrightTALK API Role you created during Step 4.
1. Go back to the Admin area.

   ![](assets/one.png)

1. Under Integration, click **LaunchPoint**.

   ![](assets/two.png)

1. Click the **New** drop-down and select **New Service**.

   ![](assets/three.png)

1. Enter a Display Name of your choice. Click the Service drop-down and select **Custom** (do **not** select BrightTALK).

   ![](assets/four.png)

   >[!CAUTION]
   >
   >Remember to not select BrightTALK in the drop-down. It is a field we are in the process of removing, and selecting it could create significant issues with your Marketo/BrightTALK integration.

1. Enter a Description of your choice. Click the API Only User drop-down and select the BrightTALK API User you created during Step 5. Click **Create**.

   ![](assets/five.png)

1. Click **View Details** for the custom service you just created.

   ![](assets/six.png)

1. Copy (and save) the **Client ID** and **Client Secret**. Click **Close**.

   ![](assets/eight-1.png)

1. Under Integration, select **Web Services**.

   ![](assets/nine-1.png)

1. Under Rest API, copy (and save) the **Endpoint** and **Identity**.

   ![](assets/ten.png)

   ## Steps in BrightTALK {#steps-in-brighttalk-1}

1. Return to the BrightTALK connector set-up screen from Step 3, and enter the credentials you saved from Steps 12 and 14.

   After the credentials are authenticated, you've officially connected BrightTALK to Marketo. The next step is to determine [which data fields you'd like to sync](http://support.brighttalk.com/hc/en-us/articles/115005131274-BrightTALK-Connector-for-Marketo-Choose-the-Fields-to-Sync).

