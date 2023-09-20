---
description: Transactional Sales Email Templates - Marketo Docs - Product Documentation
title: Transactional Sales Email Templates
hide: yes
hidefromtoc: yes
feature: Sales Insight Actions
---
# Transactional Sales Email Templates {#transactional-sales-email-templates}

If your team is sending out transactional or non-commercial emails, you can mark an email template as non-commercial so it can bypass unsubscribes.

## Things to Note {#things-to-note}

* Non-commercial emails will bypass sales unsubscribes and [Marketo Engage unsubscribe check](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/marketo-unsubscribe-check.md){target="_blank"}, but will not bypass [blocked domains](/help/marketo/product-docs/marketo-sales-insight/actions/admin/blocked-domains.md){target="_blank"}.

* Unsubscribe messages will not be automatically appended to non-commercial emails, even if the [append unsubscribe message admin setting](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/auto-append-unsubscribe-message-setting.md){target="_blank"} is enabled. However, the `{{team_unsubscribe}}`[dynamic field](/help/marketo/product-docs/marketo-sales-insight/actions/templates/dynamic-fields.md){target="_blank"} will still populate your team unsubscribe message.

## Configure an Email Template for Non-commercial Use {#configure-an-email-template-for-non-commercial-use}

Navigate to the template section.

Search for the template you want to update.

Select the template.

Enable the non-commercial email toggle under Template Settings.

Send a non-commercial email

When an unsubscribed person is selected they will be highlighted orange.

In the compose window select the non-commercial template you want to see.

Users will see a banner showing them that they have currently selected a non-commercial email template.

Click send and the email will still be sent even if the person is unsubscribed.
