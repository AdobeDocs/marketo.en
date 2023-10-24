---
unique-page-id: 2360219
description: Set up a Custom DKIM Signature - Marketo Docs - Product Documentation
title: Set up a Custom DKIM Signature
exl-id: a7c6429e-14ee-439e-9f47-1b25b98d41e7
feature: Deliverability
---
# Set up a Custom DKIM Signature {#set-up-a-custom-dkim-signature}

In order to ensure top-notch deliverability, we automatically sign all outbound mail with a shared Marketo DKIM signature.

>[!NOTE]
>
>You may need the help of your IT team to complete some of the steps in this article.

You can personalize the DKIM signature to reflect the domain(s) of your choice. Here's how.

1. Go to the **Admin** section.

   ![](assets/set-up-a-custom-dkim-signature-1.png)

   >[!NOTE]
   >
   >If you set up a custom DKIM signature the old-fashioned way, it will continue to work and should show up here.

1. Click **Email**.

   ![](assets/set-up-a-custom-dkim-signature-2.png)

1. Click the **SPF/DKIM** tab, then **Add Domain**.

   ![](assets/set-up-a-custom-dkim-signature-3.png)

1. Enter the domain you'll be using in Marketo emails as the From Address. Choose a Selector and a Key Size. Click **Add** when done.

   ![](assets/set-up-a-custom-dkim-signature-4.png)

   >[!TIP]
   >
   >* We recommend a Key Size of 2048.
   >* If you use a different domain in your From Address, we'll use the Marketo shared DKIM signature.

   <table> 
   <tr>
   <td width="20%"><b>Selector</b></td>
   <td>A unique string/identifier that's used to locate the public key portion of the DKIM record. It can be an arbitrary string, or a a unique identifier to separate out and identify the purpose of that DKIM key/record.</td>
   </tr>
   <tr> 
   <td width="20%"><b>Key Size</b></td>
   <td>The level of security you want your DKIM signature to be encrypted with.</td>
   </tr>
   </tbody>
   </table>

   <p>

1. Send the **Host Record** and **TXT Value** to your IT. Ask them to create the record for you and make sure it propagates to all nameservers associated with the from domain. Marketo's DKIM verification requires that the DKIM key is propagated to all nameservers associated with the domain being DKIM-signed.

   ![](assets/set-up-a-custom-dkim-signature-5.png)

1. Once they confirm they've created the record, come back to Marketo, select your domain, and click **Check DNS**.

   ![](assets/set-up-a-custom-dkim-signature-6.png)

   >[!NOTE]
   >
   >If the confirmation fails and your IT has created the record correctly, it may be a matter of DNS propagation. Try again later.

   >[!CAUTION]
   >
   >Modifying/removing the corresponding DNS record will result in harmed deliverability. Make sure to delete the entry in Marketo before making DNS changes.

   This will absolutely help with your email deliverability. You should get validation that the record is there and correct.
