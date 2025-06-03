---
description: Connect New Admin to Marketo - Marketo Docs - Product Documentation
title: Connect New Admin to Marketo
exl-id: ef405bca-a29a-40fc-9efa-eccff5f45956
feature: Sales Insight Actions
---
# Connect New Admin to Marketo {#connect-new-admin-to-marketo}

If the other Admin is already connected to Marketo, they only need to do Step 1.

If the second Admin is not connected to Marketo as Admin...

1. The primary Admin needs to disconnect the second Admin from Marketo from Settings > Marketo > User Access.

1. The secondary Admin logs in to their MSC account, goes to Settings > Marketo, and clicks **Connect**.

1. Now the secondary user is connected to Marketo as an Admin.

1. The primary Admin can now log in and disconnect themselves from Marketo.

>[!NOTE]
>
>The other users will stay connected as long as User B is connected as an Admin before User A disconnects.

## Update Your Marketo Connection {#update-your-marketo-connection}

If you decide you want to remove the Admin who set up the Marketo integration, review this article to learn how.

The Marketo integration will be tied to a Sales Connect/Actions Admin user. Typically, this is the Admin that first clicked the “Connect” button on the Marketo connection page and established the connection.

To remove the Admin who established the Marketo connection, a new connection must first be established by another Admin user. We've listed the tasks below that will need to be completed in order to do this.

For the purpose of simplifying the instructions, we'll refer to the currently connected Admin as Admin A and the Admin you want to establish a new connection to Marketo with as Admin B:

1. Admin A (currently connected Admin) will need to remove access to the integration with Marketo from Admin B (new Admin).

1. Have Admin B (new Admin) establish a new connection to Marketo.

1. Disconnect Admin A (originally connected Admin).

>[!NOTE]
>
>The original Admin responsible for the Marketo integration will see a “Disconnect” option that is clickable when navigating to the Marketo integration page. Other Admins (who have not established a connection) will not. Additionally, Admins who have been granted access to the Marketo integration will not be able to click Connect, which is why you must follow the steps to remove access to the integration first.

**Remove Marketo Access from Admin B**

Admin A (Admin originally responsible for the connection) should follow these steps.

1. In the web application, click the gear icon and select **Settings**.

1. Click **Marketo**.

1. Click **User Access**.

1. Search for the Admin you want to establish the new Marketo connection for.

1. Remove access.

**Establish New Connection for Admin B**

These steps should be followed by Admin B (new admin)

1. In the web application, click the gear icon and select **Settings**.

1. Click **Marketo**.

1. Click **Disconnect**.

**Disconnect Marketo Integration for Admin A**

These steps should be followed by Admin A (originally connected Admin).

1. In the web application, click the gear icon and select **Settings**.

1. Click **Marketo**.

1. Click **Disconnect**.

Now that a new Admin has established a connection to Marketo, and the original Admin has been disconnected, the originally connected Admin can safely be removed from the Sales Connect/Actions instance.
