---
description: Delivery Channel Overview - Marketo Docs - Product Documentation
title: Delivery Channel Overview
exl-id: 8dd6fe3e-86ae-4361-bc0a-6488dc1df9fa
---
# Delivery Channel Overview {#delivery-channel-overview}

Marketo Sales gives you multiple options to deliver emails. This article will review the delivery channels you can leverage, how to select them, and when to pick one over another.

## Recommended: Gmail or Exchange via Email Connection {#recommended-gmail-or-exchange-via-email-connection}

Marketo Sales allows for a streamlined setup and the enhanced deliverability through our Email Connection service. The Email Connection allows each user to connect to their [Gmail](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md) or [[!DNL Exchange]](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md) account to Marketo Sales to be utilized as the delivery channel of choice for all Marketo Sales emails.

Utilizing Gmail or [!DNL Exchange] comes with some distinct advantages over other delivery channel options:

* This is a proven delivery channel with an established reputation which helps to keep deliverability high.
* Authentication methods such as SPF and DKIM are already configured and managed by your IT team, so there is no additional setup.
* Sending emails within a given email network (i.e., sending an email as an [!DNL Exchange] user to a company that receives emails through [!DNL Exchange]) can help further increase deliverability.

It's important to note that these delivery channels have their own sending limits which are enforced by Microsoft and Google. To combat this, we utilize a throttling mechanism to help users stay within those limits. Learn more about [email throttling here](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

>[!NOTE]
>
>By default, the O365 plugin will always use your exchange delivery channel and the Gmail plugin will always utilize your Gmail delivery channel to deliver emails from the plugins.

**Bounce Tracking**: Marketo Sales can detect bounces for Exchange Online or Gmail users by detecting the bounce message that is sent to the sender's inbox. These bounce notifications will be rolled up into Template analytics, Campaign analytics, and Live Feed notifications for users. Bounce tracking is not supported for Exchange On-Prem customers.

## Custom Delivery Channel via SMTP {#custom-delivery-channel-via-smtp}

Marketo Sales offers the additional option of connecting a third-party SMTP server to be used as your sales team's preferred delivery channel.

Utilizing a third-party SMTP provider is a great option for sales teams in which email volume is the number one priority. SMTP providers such as Sendgrid and Sparkpost are optimized to service the needs of bulk email delivery and can scale to meet the needs of those looking to deploy high volumes of email.

Additionally, third party SMTP providers offer a plethora of features to help support your team's deliverability needs (such as email delivery reports and dedicated IP addresses), making this a great option for those looking for more granular controls and visibility around their sales email delivery channel.

## Marketo Sales Servers (Legacy) {#marketo-sales-servers-legacy}

Marketo Sales servers are only available for some Legacy ToutApp customers. Those customers will see Marketo Sales servers available in their email settings. All non-legacy customers will not see Marketo Sales as an option and should connect their Gmail or [!DNL Outlook] account to Marketo Sales to unlock a delivery channel.

Marketo Sales servers do not support DKIM and SPF authentication methods, which can lower the deliverability rate. Due to this we recommend that all customers connect to Gmail or [!DNL Outlook] for the best deliverability.

## MSC Servers (Legacy) {#msc-servers-legacy}

MSC servers are only available for some Legacy ToutApp customers. Those customers will see MSC servers available in their email settings. All non-legacy customers will not see MSC as an option and should connect their Gmail or Outlook account to Sales Connect to unlock a delivery channel.

MSC servers do not support DKIM and SPF authentication methods, which can lower the deliverability rate. Due to this we recommend that all customers connect to Gmail or [!DNL Outlook] for the best deliverability.

## Marketo Servers {#marketo-servers}

Marketo email servers do not integrate with Marketo Sales. Marketo servers are optimized for bulk delivery to allow them to scale with the needs of marketers. However, Gmail and [!DNL Exchange] have a higher success rate for 1:1 sales communication, which is why we recommend using these servers for your sales communication.

>[!MORELIKETHIS]
>
>* [Email Connection for Gmail Users](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [Email Connection for [!DNL Outlook] Users](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
>* [Setting up a Custom Delivery Channel](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/setting-up-a-custom-delivery-channel.md)
>* [Email Connection Throttling](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md)
