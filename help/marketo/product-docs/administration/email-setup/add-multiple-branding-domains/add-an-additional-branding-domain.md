---
unique-page-id: 11377395
description: Add an Additional Branding Domain - Marketo Docs - Product Documentation
title: Add an Additional Branding Domain
exl-id: df6e5afe-dbb0-4fbe-bf06-79d92a91b986
feature: Email Setup
---
# Add an Additional Branding Domain {#add-an-additional-branding-domain}

Add an additional branding domain when you're running multiple brands out of a single Marketo instance and want them each to have their own branded tracking links.

>[!PREREQUISITES]
>
>You must [replace the generic tracking link](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md){target="_blank"} with a branded domain before adding additional branded domains.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/add-an-additional-branding-domain-1.png)

1. Click **[!UICONTROL Email]**.

   ![](assets/add-an-additional-branding-domain-2.png)

1. Click **[!UICONTROL Add]** to add an additional branding domain.

   ![](assets/add-an-additional-branding-domain-3.png)

1. Enter the name of your new branding domain, select _Make Primary Domain_ and/or _Generate SSL Certificate_ (both optional), and click **[!UICONTROL Save]**.

   ![](assets/add-an-additional-branding-domain-4.png)

>[!NOTE]
>
>* _Make Primary Domain_: Make this your primary domain, and all existing unsent emails set to "Default" and all newly created emails will default to the primary domain. You can [overwrite this on a per-email basis](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/overwrite-primary-domain-for-emails.md){target="_blank"}.
>
>* _Generate SSL Certificate_: You can create a Secure Sockets Layer (SSL) with the creation of the domain. The first tracking domain will initiate a one-time set up of infrastructure that may take a few hours. You will be notified upon completion, and you can then set up the first domain. To add SSL to your existing domains, please reach out to [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

## Error Messages {#error-messages}

<table><thead>
  <tr>
    <th>Error</th>
    <th>Details</th>
  </tr></thead>
<tbody>
  <tr>
    <td><i>Unexpected error encountered while creating a domain. Please contact Support for assistance.</i></td>
    <td>An unexpected error has occurred. Please gather logs and error details, and escalate the issue to <a href="https://nation.marketo.com/t5/support/ct-p/Support" target="_blank">Marketo Support</a>.</td>
  </tr>
  <tr>
    <td><i>SSL certificate has already been issued.</i></td>
    <td>An SSL certificate already exists for this custom domain. No further action is needed unless the certificate has expired or needs to be reissued.</td>
  </tr>
  <tr>
    <td><i>Domain is not mapped to the default domain.</i></td>
    <td>The custom domain is not correctly mapped to the default domain. Please verify the domain mapping settings and ensure the DNS configuration points to the correct default domain.</td>
  </tr>
  <tr>
    <td><i>The Cloudflare setup has been initiated. Please try again later.</i></td>
    <td>When you create the first tracking domain for the instance, a one-time infrastructure setup in Cloudfare occurs. This message indicates the setup has been initiated and can take up to three hours.</td>
  </tr>
  <tr>
    <td><i>The Cloudflare setup is still in progress. Please try again later.</i></td>
    <td>see above</td>
  </tr>
  <tr>
    <td><i>The Cloudflare setup failed due to an unexpected error. Please contact customer support.</i></td>
    <td>The initial Cloudfare infrastructure setup failed. Please reach out to <a href="https://nation.marketo.com/t5/support/ct-p/Support" target="_blank">Marketo Support</a> for assistance.</td>
  </tr>
</tbody></table>

## Things to Note {#things-to-note}

* **DNS mapping for domain to Marketo Engage**: Before adding adding domains in the UI, you must [map CNAMEs to a Marketo-provided domain](https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/initial-setup/setup-steps#customize-your-landing-page-urls-with-a-cname){target="_blank"}.

* **Custom SSLs**: If you need a custom SSL, please submit a [Support ticket](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}. Do not use the self-service checkbox for SSL creation.

* **Pre-existing SSLs**: While adding a domain, the system checks for pre-existing SSLs, which may have been manually created prior. If you encounter this validation, create your domain without selecting SSL creation, and we will connect them for you. [Contact Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} more additional details/options.

* **First-time tracking domain**: First-time creation of email tracking link domains will need manual intervention by [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}. Subsequent subdomain creation under the same domain is allowed in the UI.

* **Adding certs to existing domains**: Adding certs to existing domains is not supported at this time. For pre-existing domains, or for cases where you missed checking the SSL certificate box, you must reach out to [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} to get the certificate added.

* **Editing or removing certs on existing domains**: If you need to update or remove an existing SSL, please reach out to [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

* **Deletion of domains**: Deleting a domain does not automatically delete the SSL certificate at this time. This will be addressed in a future release.

>[!MORELIKETHIS]
>
>[Edit Your Default Branding Domain](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md){target="_blank"}
