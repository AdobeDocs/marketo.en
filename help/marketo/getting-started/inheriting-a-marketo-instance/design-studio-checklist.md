---
description: Inherited Instance Design Studio Checklist - Marketo Docs - Product Documentation
title: Inherited Instance Design Studio Checklist
hide: yes
hidefromtoc: yes
---
# Inherited Instance: Design Studio Checklist {#inherited-instance-design-studio-checklist}

Structuring templates and creating global forms, Snippets, and images & files will help minimize data errors as well as streamline the workflow of your program build.

## Landing Pages {#landing-pages}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Global Landing Pages</td> 
   <td><li>How many global <a href="/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/understanding-free-form-vs-guided-landing-pages.md" target="_blank">Landing Pages</a> are there? Are they being used by programs?</li></td>
  </tr>
  <tr> 
   <td>Templates</td> 
   <td><li>How many <a href="/help/marketo/product-docs/demand-generation/landing-pages/landing-page-templates/create-a-free-form-landing-page-template.md" target="_blank">Landing Page templates</a> are there? Are they being leveraged?</li></td>
  </tr>
  <tr> 
   <td>Test Groups</td> 
   <td><li>How many <a href="/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-test-groups.md" target="_blank">Landing Page test groups</a> are they? Are they all still relevant?</li></td>
  </tr>
   <tr> 
   <td>Privacy & Compliance</td> 
   <td><li>Do all your Landing Pages have the appropriate footers?</li></td>
  </tr>
 </tbody> 
</table>

## Images & Files {#images-and-files}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Naming Conventions</td> 
   <td><li>Do <a href="/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md" target="_blank">images and files</a> have consistent naming conventions?</li></td>
  </tr>
  <tr> 
   <td>Folder Structure</td> 
   <td><li>Are images and files <a href="/help/marketo/product-docs/demand-generation/images-and-files/organize-your-images-and-files-using-folders.md" target="_blank">organized appropriately</a> and easy to search?</li></td>
  </tr>
  <tr> 
   <td>Images & Files</td> 
   <td><li>Do any images or files <a href="/help/marketo/product-docs/demand-generation/images-and-files/find-the-url-of-an-uploaded-image-or-file.md" target="_blank">referenced on web pages</a> need to be updated? 
   <p>Example: The hardcoded URL structure <a href="https://nation.marketo.com/t5/product-documents/upcoming-changes-to-design-studio-urls/ta-p/306632#_Toc54870361" target="_blank">may need to be updated</a>, such as <code>http://na-sj01.marketo.com/rs/123-ABC-456/images/puppy.png</code>. 
   <p>Please work with your web developer to determine where you may need to make updates.</li></td>
  </tr>
 </tbody> 
</table>

## Forms {#forms}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Global Forms</td> 
   <td><li>How many global <a href="/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md" target="_blank">forms</a> are there?</li>
<li>Do most programs use global or local forms?</li>
<li>Are all forms gathering the right data for Marketing and Sales?</li>
<li>Are hidden values leveraged appropriately?</li>
<li>Are any Marketo Engage forms being used on non-Marketo Engage Landing Pages? How are they being referenced?</li>
<p><img src="assets/tip-icon.png" alt="tip icon">TIP: Update pages where you embed Marketo Engage forms with the new embed code introduced (requires secured landing pages).
<br/><pre><script src="//example.marketo.com/js/forms2/js/forms2.min.js"></script></pre>
<br/><pre><form id="mktoForm_1"></form><script>MktoForms2.loadForm("//example.marketo.com", "123-ABC-456", 1);</script></pre>
</td>
  </tr>
  <tr> 
   <td>Data Standardization</td> 
   <td><li>Are your <a href="/help/marketo/product-docs/demand-generation/forms/form-fields/add-a-fieldset-to-a-form.md" target="_blank">form fields</a> primarily picklists or open text fields?</li>
<p><img src="assets/tip-icon.png" alt="tip icon">TIP: If they're open text fields, consider switching them to picklists to prevent messy data.</td>
  </tr>
  <tr> 
   <td>Privacy & Compliance</td> 
   <td><li>Does your form strategy align with your corporate data privacy and opt-in requirements? 
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Consider <a href="https://business.adobe.com/resources/ebooks/the-gdpr-and-the-marketer.html" target="_blank">General Data Protection Regulation (GDPR)</a>, Canada's Anti-Spam Law (CASL), the Controlling the Assault of Non-Solicited Pornography and Marketing Act of 2003 (CAN-SPAM), California Consumer Privacy Act (CCPA), etc., for regulation compliance.</li>
<p><img src="assets/tip-icon.png" alt="tip icon">TIP: Remember to always consult your Legal team on these issues. Ask your team about previous initiatives to maintain compliance before making any changes.</td>
  </tr>
 </tbody> 
</table>

## Emails {#emails}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Global Emails</td> 
   <td><li>How many global <a href="/help/marketo/product-docs/email-marketing/general/creating-an-email/create-an-email.md" target="_blank">emails</a> are there? Are they being used by programs?</li></td>
  </tr>
  <tr> 
   <td>Templates</td> 
   <td><li>How many <a href="/help/marketo/product-docs/email-marketing/general/email-editor-2/create-an-email-template.md" target="_blank">email templates</a> are there? Are they being leveraged?</li></td>
  </tr>
  <tr> 
   <td>Email Testing</td> 
   <td><li>How are you using <a href="/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/understanding-email-testing-options.md" target="_blank">email testing</a>? Is your method still effective?</li></td>
  </tr>
  </tr>
  <tr> 
   <td>Privacy & Compliance</td> 
   <td><li>Do all your emails have the appropriate footers? Consider GDPR, CASL, CAN-SPAM, CCPA, etc. for compliance implications.</li>
<p><img src="assets/tip-icon.png" alt="tip icon">TIP: Remember to always consult your Legal team on these compliance issues. Ask your team about previous initiatives to maintain compliance before making any changes.</td>
  </tr>
 </tbody> 
</table>

## Snippets {#snippets}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Snippets</td> 
   <td><li>How many <a href="/help/marketo/product-docs/personalization/segmentation-and-snippets/snippets/create-a-snippet.md" target="_blank">snippets</a> are there? Are they being used? 
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If not, consider using them for <a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email.md" target="_blank">email</a> and <a href="/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/add-a-snippet-to-a-landing-page.md" target="_blank">Landing Page</a> footer content, logos, and more.</li></td>
  </tr>
 </tbody> 
</table>

## All Assets {#all-assets}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Asset Status</td> 
   <td><li>How many assets are in <i>Draft</i> and <i>Approved with Draft</i> status (e.g., e.g., <a href="/help/marketo/product-docs/email-marketing/general/creating-an-email/approve-an-email.md" target="_blank">emails</a>, <a href="/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md#approve-a-landing-page" target="_blank">Landing Pages</a>, <a href="/help/marketo/product-docs/demand-generation/forms/creating-a-form/approve-a-form.md" target="_blank">forms</a>, <a href="/help/marketo/product-docs/personalization/segmentation-and-snippets/snippets/approve-a-snippet.md" target="_blank">snippets</a>)?
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If there are many, consider deleting or approving them.</li></td>
  </tr>
  <tr> 
   <td>Asset Sharing</td> 
   <td><li>Which assets are <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.md#sharing-across-workspaces" target="_blank">shared across Workspaces</a>?</li>
   <p><img src="assets/note-icon.png" alt="note icon"> NOTE: It's important to know this as actions taken in one Workspace might lead to an inaccessible asset in a different Workspace for another user.</td>
  </tr>
 </tbody> 
</table>

<br>&nbsp;

[◄ Audit an Inherited Instance: Marketing Activities](/help/marketo/getting-started/inheriting-a-marketo-instance/marketing-activities-checklist.md)

[Audit an Inherited Instance: Document Your Inherited Instance Setup ►](/help/marketo/getting-started/inheriting-a-marketo-instance/document-your-setup.md)
