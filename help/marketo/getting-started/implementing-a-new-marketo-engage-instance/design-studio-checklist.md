---
description: Set up the Design Studio section for your new Marketo Engage instance.
title: New Instance Best Practices - Design Studio Checklist
feature: Getting Started
exl-id: 070ee235-dad0-4627-bac0-14bf0174bb03
TQID: https://experienceleague.adobe.com/RBppQJwjVVJ-5eQDWh-990TJDXF4c7EPEja7uHRlI6I
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: a1d50dda-6d94-4e16-8c30-5eb7181c4650
    internal-label: Segmentation
  - id: df8eb12b-4f82-491f-acbb-d74012ca5654
    internal-label: Snippets
  - id: ea6641cb-8461-4151-a8a9-9faaa44a928a
    internal-label: Global Assets
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
---
# New Instance Best Practices: Design Studio Checklist {#new-instance-best-practices-design-studio-checklist}

The Design Studio section is where the reusable 'global assets' should reside. Create the global assets that your organization plans to use in programs, use a consistent naming convention, and organize them in the subfolders for easy searches.

Remember to [download the checklists](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) and track your progress.

## Landing Pages {#landing-pages}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Global Landing Pages</td>
    <td><li>Create <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/understanding-free-form-vs-guided-landing-pages#product-docs" target="_blank">global Landing Pages (free-form/guided)</a>.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-test-groups" target="_blank">Create a test page</a> to A/B test the winning Landing Page template (if applicable).</li></td>
  </tr>
  <tr>
    <td>Templates</td>
    <td><li>Create a design for global Landing Pages.</li></td>
  </tr>
  <tr>
    <td>Privacy & Compliance</td>
    <td><li>Create a footer using <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/personalizing-landing-pages/add-a-snippet-to-a-landing-page" target="_blank">Snippets</a> or <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/personalizing-landing-pages/add-text-and-tokens-to-a-landing-page#add-a-token-to-your-landing-page" target="_blank">Tokens</a> in your Landing Pages for privacy compliance.</li></td>
  </tr>
</tbody>
</table>

## Forms {#forms}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Global Forms</td>
    <td><li>Set up <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/forms/creating-a-form/create-a-form#product-docs" target="_blank">global forms</a> for use cases such as subscription preferences, gated content downloads, demo requests, webinar registrations, etc.</li></td>
  </tr>
  <tr>
    <td>Privacy & Compliance</td>
    <td><li>Keep your forms <a href="https://business.adobe.com/resources/ebooks/the-gdpr-and-the-marketer.html" target="_blank">General Data Protection Regulation (GDPR)</a> compliant.</li></td>
  </tr>
  <tr>
    <td>Data Standardization</td>
    <td><li>Consider applying picklists to the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/forms/creating-a-form/add-a-field-to-a-form#product-docs" target="_blank">form fields</a> instead of open text fields to prevent messy data.</li></td>
  </tr>
</tbody>
</table>

## Emails {#emails}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Global Emails</td>
    <td><li>Create global emails.</li></td>
  </tr>
  <tr>
    <td>Templates</td>
    <td><li>Design a module-based <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/general/email-editor-2/create-an-email-template" target="_blank">email template</a> with a designer/developer, or use your own HTML.</li>
    <li>Create a tested email template to A/B test the winning template (if applicable).</li></td>
  </tr>
  <tr>
    <td>Privacy & Compliance</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email" target="_blank">Add Snippets</a> to your email templates to control reusable blocks such as copyright year, global location, and compliance-specific language.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/general/using-tokens/add-an-email-script-token-to-your-email" target="_blank">Add Tokens</a> to personalize content based on the target audience.</li></td>
  </tr>
</tbody>
</table>

## Snippets {#snippets}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Snippets</td>
    <td><li>Create <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/snippets/create-a-snippet#product-docs" target="_blank">Snippets</a> to have reusable content blocks that can be used for multiple use cases, such as contact information, social media links, brand information, and privacy and compliance notes in your emails and Landing Pages.</li></td>
  </tr>
</tbody>
</table>

## Images & Files {#images-and-files}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Naming Conventions</td>
    <td><li>Use consistent naming conventions for images and files.</li>
    <br>Examples:
    <br><ul><li>File Naming Convention: Asset Type-Asset Name (Ex: White-Paper-Evaluating-Cloud-Computing-Get-Your-Board-on-Board)</li>
    <p><li>Image Naming Convention: Image Type-Asset Type-Asset Name (Ex: Thumbnail-White-Paper-Evaluating-Cloud-Computing-Get-Your-Board-on-Board)</li></td>
  </tr>
</tbody>
</table>

## Organization {#organization}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Folder Structure </td>
    <td><li>Create subfolders for each type of asset and <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/images-and-files/organize-your-images-and-files-using-folders" target="_blank">organize global assets</a> (e.g., conversational flows, email templates, emails, forms, images and files, Landing Pages, Landing Page templates, snippets, etc.) appropriately.</li></td>
  </tr>
</tbody>
</table>
