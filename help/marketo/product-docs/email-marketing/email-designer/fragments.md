---
title: Fragments
description: Learn how to create and use visual content fragments as reusable components for emails and email templates.
hide: yes
hidefromtoc: yes
exl-id: abc065a0-cd2f-4f0f-a5f2-228b833b99a8
---
# Fragments

A fragment is a reusable component that can be referenced in one or more emails and email templates. It is usually a block of content (text, image, or both) that can be created and quickly inserted into your project. With this functionality, you can prebuild multiple custom content blocks for use by your marketing team members to assemble email content for an improved design process. Common use cases include header/footer content blocks for email, event invite banners, seasonal messages, and more.

To make the best use of fragments in your workflows:

* _Create your own fragments_ - Create visual fragments, either from scratch or by saving content as a fragment from the visual content editor.
* _Reuse fragments_ - Use them as many times as needed in your content.

## Visual fragments {#visual-fragments}

Visual fragments are predefined visual blocks built using the visual content editor that you can reuse across multiple emails or email templates.

## Access and manage fragments {#access-and-manage-fragments}

To access visual fragments, go to the left navigation and click **[!UICONTROL Content Management]** > **[!UICONTROL Fragments]**. This action opens a listing page with all the fragments created in the instance listed in a table.

SCREENSHOT

The table is sorted by the _[!UICONTROL Modified]_ column, with the most recently updated fragments at the top by default. Click the column title to change between ascending and descending.

### Fragment status and lifecycle

The fragment status determines its availability for use in an email or email template, and the changes that you can make to it. 

<table>
<tbody>
  <tr>
    <td><b>Draft</b></td>
    <td>When you create a fragment, it is in draft status. It remains a draft until you publish it for use in an email or email template.
    <p>Available actions:
    <li>Edit all details</li>
    <li>Edit in visual designer</li>
    <li>Publish</li>
    <li>Duplicate</li>
    <li>Delete</li>
  </td>
  <tr>
    <td><b>Published</b></td>
    <td>When you publish a fragment, it becomes available for use in an email or email template. Published fragment content cannot be modified in the visual designer.
    <p>Available actions:
    <li>Edit description</li>
    <li>Add to an email or template</li>
    <li>Create draft version</li>
    <li>Duplicate</li>
    <li>Delete (if not in-use)</li>
    </td>
  </tr>
  <tr>
    <td><b>Published with draft</b></td>
    <td>When you create a draft from a published fragment, the published version remains available for use in an email or email template, and the draft content can be modified in the visual designer. If you publish the draft version, it replaces the current published version and the content is updated in <i>all</i> the emails and email templates where it is in use. 
    <p>Available actions:
    <li>Edit description</li>
    <li>Add to an email or template</li>
    <li>Edit draft version in visual designer</li>
    <li>Publish draft version</li>
    <li>Duplicate</li>
    <li>Delete (if not in-use)</li>
    </td>
  </tr>
</tbody></table>

SCREENSHOT

### Filter the fragments list {#filter-the-fragments-list}

Use the search bar to find a fragment by name. Click the _Filter_ icon ( ![Show or hide filters icon](assets/icon-filter.svg) ) to show the available filter options and choose the desired settings.

SCREENSHOT

### Customize the column display {#customize-the-column-display}

Customize the columns you want to display in the table by clicking the _Customize table_ icon ( ![Customize table icon](assets/icon-column-settings.svg) ) at the top right.

In the dialog, select the desired columns and click **[!UICONTROL Apply]**.

SCREENSHOT

## Create fragments {#create-fragments}

Create a new visual fragment by clicking **[!UICONTROL Create fragment]** at the top right.

1. In the _[!UICONTROL Create fragment]_ dialog, enter a **[!UICONTROL Name]** and an optional **[!UICONTROL Description]**.

   Fragment requirements:

   * Name - 100 characters max, must be unique, case-insensitive
   * Description - 300 characters max
   * Alpha, numeric, and special characters are okay
   * Reserved characters are **_not allowed_**: `\ / : * ? " < > |`

SCREENSHOT

1. Click **[!UICONTROL Create]**.

   The visual designer opens with an empty canvas.

1. Use the content design tools to create the visual fragment content:

   * [Add structure and content](#add-structure-and-content)
   * [Add Assets](#add-assets)
   * [Navigate the layers, settings, and styles](#navigate-the-layers-settings-and-styles)
   * [Personalize content](#personalize-content)
   * [Edit linked URL tracking](#edit-linked-url-tracking)

1. Click **[!UICONTROL Save]** at any time to save the draft fragment.

1. When you are ready to make the fragment available for use in an email or email template, click **[!UICONTROL Publish]**.

### Add structure and content {#add-structure-and-content}

>[!CONTEXTUALHELP]
>id="ajo-b2b_structure_components_fragment"
>title="Add Structure components"
>abstract="Structure components define the layout of the fragment. Drag and drop a **Structure** component into the canvas to start designing the content of your fragment."

>[!CONTEXTUALHELP]
>id="ajo-b2b_content_components_fragment"
>title="About Content components"
>abstract="Content components are empty content placeholders that you can use to create the layout of a fragment."

{{$include /help/_includes/content-design-components.md}}

### Add assets

{{$include /help/_includes/content-design-assets.md}}

### Navigate the layers, settings, and styles

{{$include /help/_includes/content-design-navigation.md}}

### Personalize content

{{$include /help/_includes/content-design-personalization.md}}

### Edit linked URL tracking

{{$include /help/_includes/content-design-links.md}}

## View fragment details {#view-fragment-details}

Click the name of any fragment in the list page to open the fragment details page. You can choose to edit the fragment, rename the fragment, or update the fragment description. Make updates and click outside of the name or description field to auto-save changes.

>[!NOTE]
>
>If a published fragment is in use by an email or email template, you cannot change its name or edit the content. You can create a draft version if you want to make changes to the fragment.

SCREENSHOT

Click **[!UICONTROL Edit fragment]** to open the fragment in the visual content editor.

Exit the view at any time by clicking the _Back_ arrow at the top left, which returns you to the _Fragments_ list page.

## View fragment used-by references {#view-fragment-used-by-references}

In the fragment details page, click the **[!UICONTROL Used By]** tab to view details of where the fragment is being used within Marketo Engage.

>[!IMPORTANT]
>
>A fragment that is currently in use by an email or email template cannot be deleted.

References are displayed according to category: _Email_ or _Email template_. Emails in Journey Optimizer B2B Edition are embedded and authored within account journeys, so the parent journey of the email that uses the fragment is displayed in references. <--- WHAT ABOUT THIS PART, NILESH

SCREENSHOT

Click the link to open the corresponding email or email template where the fragment is used.

## Delete fragments {#delete-fragments}

Because a fragment that is currently in use by an email or email template cannot be deleted, be sure to check the _used-by_ references before initiating a fragment removal. Also, a removal cannot be undone, so check before initiating a delete action.

You can delete a fragment using either of the following methods:

* From the fragment details on the right, click **[!UICONTROL Delete]**.
* From the _[!UICONTROL Fragments]_ listing page, click the ellipsis next to the fragment and choose **[!UICONTROL Delete]**.

This action opens a confirmation dialog. You can abort the process by clicking **[!UICONTROL Cancel]**, or click **[!UICONTROL Delete]** to confirm deletion.

SCREENSHOT

## Edit fragments

Edits to a fragment depend on its current status:

* When a fragment is in _Draft_ status, you can edit any of its details and the visual content.
* When a fragment is in _Published_ status, you can edit the fragment description, but not the name. You cannot edit the visual content.
* When a fragment is in _Published with draft_ status, editing the details is limited to the description. You can also edit the visual content for the draft version.

>[!BEGINTABS]

>[!TAB Draft]

1. From the _[!UICONTROL Fragments]_ listing page, click the fragment name to open it.

   A preview of the visual content is displayed, with the fragment details on the right.

1. Make the desired edits.

SCREENSHOT

1. To make changes to the content in the visual designer, click **[!UICONTROL Edit fragment]**.

   Use the visual designer tools as needed:

   * [Add structure and content](#add-structure-and-content)
   * [Add Assets](#add-assets)
   * [Navigate the layers, settings, and styles](#navigate-the-layers-settings-and-styles)
   * [Personalize content](#personalize-content)
   * [Edit linked URL tracking](#edit-linked-url-tracking)

   Click **[!UICONTROL Save]**, or **[!UICONTROL Save & close]** to return to the fragment details.

1. When the fragment meets your criteria and you want to make it available for use in an email or email template, click **[!UICONTROL Publish]**.

>[!TAB Published]

1. From the _[!UICONTROL Fragments]_ listing page, click the fragment name to open it.

   A preview of the visual content is displayed, with the fragment details on the right.

1. Modify the description, if needed.

   For a published fragment, all other details cannot be changed.

1. If you want to update the content, click **[!UICONTROL Create draft version]** at the top right.

   Click **[!UICONTROL OK]** in the dialog to open the draft version in the visual designer. You can change the `image source` KG - LINK HERE if needed. 

SCREENSHOT

   Use the visual designer tools as needed:

   * [Add structure and content](#add-structure-and-content)
   * [Add Assets](#add-assets)
   * [Navigate the layers, settings, and styles](#navigate-the-layers-settings-and-styles)
   * [Personalize content](#personalize-content)
   * [Edit linked URL tracking](#edit-linked-url-tracking)

   Click **[!UICONTROL Save]**, or **[!UICONTROL Save & close]** to return to the fragment details.

1. When the draft fragment meets your criteria and you want to make the changes available for use in an email or email template, click **[!UICONTROL Publish]**.

   When you publish the draft version, it replaces the current published version and the content is updated in the emails and email templates where it is already in use.

>[!TAB Published with draft]

There are two ways to open the draft version for editing from the _[!UICONTROL Fragments]_ listing page:

* Click the _More_ icon (**...**) next to the fragment name and choose **[!UICONTROL Open draft version]**.

SCREENSHOT

* Click the fragment name to open it. Then, click **[!UICONTROL Open draft version]** at the top right.

   A preview of the visual content for the draft version is displayed, with the fragment details on the right.

To update the content:

1. Click **[!UICONTROL Edit fragment]** at the top right. Use the visual designer tools as needed:

   * [Add structure and content](#add-structure-and-content)
   * [Add Assets](#add-assets)
   * [Navigate the layers, settings, and styles](#navigate-the-layers-settings-and-styles)
   * [Personalize content](#personalize-content)
   * [Edit linked URL tracking](#edit-linked-url-tracking)

   Click **[!UICONTROL Save]**, or **[!UICONTROL Save & close]** to return to the fragment details.

1. When the draft fragment meets your criteria and you want to make the changes available for use in an email or email template, click **[!UICONTROL Publish]**.

   When you publish the draft version, it replaces the current published version and the content is updated in the emails and email templates where it is already in use.

>[!ENDTABS]

## Duplicate fragments {#duplicate-fragments}

You can duplicate a fragment using either of the following methods:

* From the _[!UICONTROL Fragments]_ listing page, click the _More_ icon (**...**) next to the fragment name and choose **[!UICONTROL Duplicate]**.
* At the top right of the fragment details page, click **[!UICONTROL ... More]** and choose **[!UICONTROL Duplicate]**.

SCREENSHOT

In the dialog, enter a unique name and optional description. Click **[!UICONTROL Duplicate]** to complete the action.

SCREENSHOT

The duplicated fragment then appears in the _Fragments_ listing.

## Save a new fragment from email or template content {#save-a-new-fragment-from-email-or-template-content}

When you are creating/editing an email or email template in the visual content editor, you can choose to save all or parts of the content as a fragment so that it is available for reuse.

1. To save content as a fragment, click **[!UICONTROL More]** and choose **[!UICONTROL Save as Fragment]**.

1. Select the different elements to be included in the fragment.

   Select multiple structures by holding the Shift or Control button.

   You can only select structures that are adjacent to each other and the interface does not allow you to select non-adjacent elements.

1. With the content selected, click **[!UICONTROL Create]** at the top right.

1. In the dialog, enter a name and optional description for the fragment. Then click **[!UICONTROL Create]**.

   The fragment is then displayed in the _Fragments_ listing page and is also available for use within emails and email templates.

## Add visual fragments to your email or template content {#add-visual-fragments-to-your-email-or-template-content}

Fragments are designed for reuse and you can add up to 30 in an email or email template. Fragments can be nested up to one level only.

>[!BEGINTABS]

>[!TAB Add fragments to an email]

1. Navigate to **[!UICONTROL Account Journeys]** and open an existing journey or create a new journey. <--- DOUBLE-CHECK THIS

----------STOPPED EDITING HERE---------

1. Create a [_[!UICONTROL Send Email]_ node](./email-authoring.md#add-an-email-action-in-an-account-journey).

1. Create or edit [email content for the node](./email-authoring.md#create-the-email-content).

1. Drag and drop an item from the **[!UICONTROL Components]** menu to provide a _structure_ for the fragment.

1. To open the listing of published fragments, click the _Fragments_ icon.

   You can:
   * Sort the listing.
   * Browse, search, and filter the listing.
   * Switch between card (thumbnail) and list views.
   * Refresh the list to reflect any of the recently created fragments.

SCREENSHOT

1. Drag and drop any of the fragments into the structure component placeholder.

   The editor renders the fragment within the section/element of the email structure.

The content of the fragment is dynamically updated within the structure to render a visual of how the content appears in the email.

>[!TIP]
>
>If you want the fragment to occupy the entire horizontal layout within the email, add a [!UICONTROL 1:1 column] structure and then drag and drop the fragment into it.

After the email is saved, it appears in the fragment details page when the _[!UICONTROL Used By]_ tab is selected. Fragments added to an email are not editable within the email or template -- the published source fragment defines the content.

>[!TAB Add fragments to an email template]

1. From the left navigation, click **[!UICONTROL Content Management]** > **[!UICONTROL Templates]**.

1. Create a new template, or open an existing email template and click **[!UICONTROL Edit Email Template]**.

1. Drag and drop an item from the **[!UICONTROL Components]** menu to provide a _structure_ for the fragment.

1. To open the fragments listing, click the _Fragments_ icon.

   You can:
   * Sort the listing.
   * Browse, search, and filter the listing.
   * Switch between card (thumbnail) and list views.
   * Refresh the list to reflect any of the recently created fragments.

SCREENSHOT

1. Drag and drop any of the fragments into the structure component placeholder.

   The editor renders the fragment within the section/element of the email template structure.

1. Drag and drop any of the fragments into the structure component placeholder.

   The editor renders the fragment within the section/element of the email template structure.

>[!TIP]
>
>If you want the fragment to occupy the entire horizontal layout within the email template, add a _[!UICONTROL 1:1 column]_ structure and then drag and drop the fragment into it.

After the email template is saved, it appears in the fragment details page when the _[!UICONTROL Used By]_ tab is selected. Fragments added to an email template are not editable within the template -- the published source fragment defines the content.

>[!ENDTABS]

## Fragment actions during email and template authoring

When a fragment is added to an email or email template, the fragment content cannot be edited within the email or template. However, you can apply the following actions:

* **[!UICONTROL Delete]** - This action removes the fragment from the current email or email template content (the fragment source is unaffected).
* **[!UICONTROL Refresh]** - This action refreshes the content of the fragment in the current email or email template. Refreshing is useful when you want to reflect any recent edits to the fragment after the addition to the email or email template.
* **[!UICONTROL Duplicate]** - This action duplicates the fragment within the same email or email template within the editor, with the same dimensions and added just below it.
* **[!UICONTROL Open Fragment]** - This action opens a new browser tab with the fragment editor page and details.
* **[!UICONTROL Break inheritance]** - This action breaks the inheritance of the fragment (and its changes) from the source. Use this action to make the fragment content available as independent and editable content within the email or email template. This action also removes the email or email template from the _Used By_ reference for the original fragment.

When you select the fragment on the editor page, these actions are available from the context toolbar and the properties panel on the right.

SCREENSHOT
