---
description: Connect New Admin to Marketo - Marketo Docs - Product Documentation
title: Connect New Admin to Marketo
hide: yes
hidefromtoc: yes
exl-id: ef405bca-a29a-40fc-9efa-eccff5f45956
---
# Connect New Admin to Marketo {#connect-new-admin-to-marketo}

If the other Admin is already connected to Marketo, they only need to do Step 1.

If the second Admin is not connected to Marketo as Admin...

1. The primary Admin needs to disconnect the second admin from Marketo from Settings > Marketo > User Access

1. Secondary Admin logs into their MSC account, goes to Settings > Marketo and clicks **Connect**.

1. Now the secondary user is connected to Marketo as an Admin.

1. Primary Admin can now login and disconnect themselves from Marketo.

>[!NOTE]
>
>The other users will stay connected as long as User B is connected as Admin before User A disconnects.

## Update Your Marketo Connection {#update-your-marketo-connection}

If you decide you want to remove the admin who set up the Marketo integration, review this article to learn how.

The Marketo integration will be tied to a Sales Connect/Actions admin user. Typically, this is the admin that first clicked the “Connect” button on the Marketo connection page and established the connection.

To remove the admin who established the Marketo connection, a new connection must first be established by another admin user. We've listed the tasks below that will need to be completed in order to do this.

For the purpose of simplifying the instructions, we'll refer to the currently connected admin as Admin A and the admin you want to establish a new connection to Marketo with as Admin B:

1. Admin A (currently connected admin) will need to remove access to the integration with Marketo from Admin B (new admin).

1. Have Admin B (new admin) establish a new connection to Marketo.

1. Disconnect Admin A (originally connected admin).

>[!NOTE]
>
>The original admin responsible for the Marketo integration will see a “Disconnect” option that is clickable when navigating to the Marketo integration page. Other admins (who have not established a connection) will not. Additionally, admins who have been granted access to the Marketo integration will not be able to click Connect, which is why you must follow the steps to remove access to the integration first.

**Remove Marketo Access from Admin B**

Admin A (admin originally responsible for the connection) should follow these steps.

1. Navigate to settings.

1. Click **Marketo**.

1. Click **User Access**.

1. Search for the admin you want to establish the new Marketo connection for.

1. Remove access.

**Establish New Connection for Admin B**

These steps should be followed by Admin B (new admin)

1. Navigate to settings.

1. Click **Marketo**.

1. Click **Disconnect**.

**Disconnect Marketo Integration for Admin A**

These steps should be followed by Admin A (originally connected admin)

1. Navigate to settings.

1. Click **Marketo**.

1. Click **Disconnect**.

Now that a new admin has established a connection to Marketo, and the original admin has been disconnected, the originally connected admin can safely be removed from the Sales Connect/Actions instance.
