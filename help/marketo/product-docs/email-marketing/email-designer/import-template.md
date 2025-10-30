---
solution: Marketo Engage
product: marketo
title: Template import
description: Learn how to import your existing email templates from the classic editor into the new Email Designer.
level: Beginner, Intermediate
feature: Email Designer
badge: Beta
hide: yes
hidefromtoc: yes
---
# Template import {#template-import}

Seamlessly import your existing email templates from the classic editor into the new Email Designer, preserving your designs and accelerating template creation with familiar, reusable structures. Review [best practices](#best-practices) and learn about [limitations and remedies](#limitations-and-remedies).

1. Go to the **Design Studio**.

   SCREENSHOT

1. Click **Email Templates** and select **Email Templates (New)**.

   SCREENSHOT

1. Click **Create Template**.

   SCREENSHOT

1. Enter a _Name_ and (optional) _Description_.

   SCREENSHOT

1. Click the **Marketo Templates** and choose the existing Templates created in the classic email editor. 

   SCREENSHOT

   >[!NOTE]
   >
   >Only approved templates and templates that have been shared with the current workspace are available to import.

1. Select the desired template.

   SCREENSHOT

1. Click Use this template.

   SCREENSHOT

1. The imported template opens in the Email Designer. 

1. Review the components for correct conversion and make any desired adjustments using the Designer. When you are happy with the template, approve it for use in emails.

## Create fragments {#create-fragments}

It is a good idea to create fragments of repeatable sections for later use. 

1. Click the **...More** button on top and select **Save as fragment**.

   SCREENSHOT

1. Select a component or structure and click **Create**.

   SCREENSHOT

1. Enter a name (and optional description) and click **Save**.

   SCREENSHOT

## Best practices {#best-practices}

* Since freestyle HTML can vary significantly, the importer may not always interpret every component perfectly. Review your imported templates to ensure all sections are editable and correctly mapped. If a part is not selectable, simply recreate that section for the best results.

* After import, you can save reusable sections as fragments and approve them for use by email authors. Apply brand themes to maintain consistency and compliance.

* You can continue using Velocity scripting, and consider reimplementing older snippets using a combination of fragments and conditional content for improved flexibility and control.

## Limitations and remedies {#limitations-and-remedies}

<table><thead>
  <tr>
    <th>Limitation</th>
    <th>Reason</th>
    <th>Remedy</th>
  </tr></thead>
<tbody>
  <tr>
    <td>The variables defined in the classic email editor are not available at the email level.</td>
    <td>The variables were originally designed to simplify email editing when the editor did not yet offer WYSIWYG capabilities. In the Email Designer, users can achieve similar flexibility through the available controls. The importer maintains the structure and components of your existing template, helping you recreate it efficiently in the Email Designer.</td>
    <td>Users should be able to achieve this in the Designer. <p>
    For modules, you can save different segments as fragments. Approved fragments will be available for use at the email level.</td>
  </tr>
  <tr>
    <td>If the source HTML contains nested blocks, the deeper layers are not addressable in the Designer.</td>
    <td>The Email Designer does not support nested comments.</td>
    <td>Even though the Designer does not allow the editing of nested structures, it should render accurately. Be sure to test the template first.<p>
    Recreate the structure using Grid.</td>
  </tr>
  <tr>
    <td>Sometimes buttons are imported as simple containers with text inside.</td>
    <td>Some of the implementation styles using HTML can be misconstrued during import.</td>
    <td>Recreate the button in the Designer.</td>
  </tr>
  <tr>
    <td>Buttons may sometimes be oversized.</td>
    <td>Conflict between Marketo email's CSS with other lower level elements (<code>&lt;span&gt;</code>)</td>
    <td>Try adjusting margins and paddings of the button in the Designer.</td>
  </tr>
  <tr>
    <td>Bullet points are not natively supported.</td>
    <td>The Email Designer does not offer bullet points at this time.</td>
    <td>Consider reimplementing bullets using alternative techniques.</td>
  </tr>
  <tr>
    <td>Vertical alignment is distorted where the container's content does not respect the valign attribute value.</td>
    <td><code>valign</code> does not function inside containers defined in the template.</td>
    <td>Try adjusting margins and paddings of the button in the Email Designer.</td>
  </tr>
  <tr>
    <td>Program-level Personalization Tokens (My Tokens) at the template level may run into validation errors.</td>
    <td>Email templates do not support program level tokens.</td>
    <td>Replace them with other token types inside templates, and replace them with My Tokens inside of the individual emails.</td>
  </tr>
  <tr>
    <td>Divider components may not be selectable.</td>
    <td>Divider components are not covered in the release.</td>
    <td>n/a</td>
  </tr>
  <tr>
    <td>If the original HTML has any ill-formed structures, they are likely to be carried over.</td>
    <td>Issues with the original HTML.</td>
    <td>The issues would need to be fixed prior to import.</td>
  </tr>
  <tr>
    <td>For the imported content, the use of content preview is not reliable indicator.</td>
    <td>The Designer's preview function does not support custom HTML.</td>
    <td>It is recommended to test your email using the <b>Send proof</b> option in the <i>Simulate content</i> screen.</td>
  </tr>
  <tr>
    <td>The snippets in the old template will not function in the Email Designer.</td>
    <td>The Email Designer does not support snippets.</td>
    <td>Reimplement your snippets as fragments coupled with conditional content.</td>
  </tr>
</tbody></table>
