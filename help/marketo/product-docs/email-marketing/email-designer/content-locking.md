---
solution: Marketo Engage
product: marketo engage
title: Lock content in email templates
description: Learn how to lock content in your email templates.
hide: yes
hidefromtoc: yes
level: Beginner, Intermediate
exl-id: 7ccff4f0-5db5-4dd7-91e0-d2081b74ad18
---
# Lock content in email templates {#lock-content-email-templates}

Marketo Engage allows you to lock content in email templates, either by locking the entire template or specific structures/components. This allows you to prevent unintentional edits or deletions, giving you greater control over template customization, and improving the efficiency and reliability of your email campaigns.

>[!AVAILABILITY]
>
>Users with permissions to create content templates can enable content locking.

Content locking can be applied either at the **structure** level, or at the **component** level.

* When a structure is locked:

    * All content within that structure is also locked.
    * No content can be added to the structure.
    * By default, you cannot delete the structure. You can override this restriction by enabling the "Allow delete" option.
    * Individual content components within the locked structure can be set as editable.

* When a structure is editable (structure not locked):

    * Individual content components can be locked inside that structure.
    * By default, you cannot delete a component if it is locked, or if the "Editable content lock only" is selected. You can override this restriction by enabling the "Allow delete" option.

## Lock an email template {#lock-an-email-template}

### Enable content locking {#enable-content-locking}

You can enable content locking for an email template directly in the Email Designer, whether you are creating a new template or editing an existing one.

---STOPPED EDITING HERE---

1. Open or create an email template and access the content editing screen in the Email Designer.

1. In the **[!UICONTROL Body]** pane on the right, toggle on the **[!UICONTROL Governance]** option.

1. From the **[!UICONTROL Mode]** drop-down list, select the desired locking mode for the template:
    
    * **[!UICONTROL Content locking]**: Lock specific sections of content within the template. By default, all structures and components become editable. You can then selectively lock individual elements.
    * **[!UICONTROL Read only]**: Lock the entire content of the template, preventing any modifications.

    ![](assets/content-locking-1.png){width="800" zoomable="yes"}

1. If you selected the **[!UICONTROL Content locking]** mode, you can further define how users can interact with the template. Toggle on the **[!UICONTROL Enable content edition]** option and choose one of the following:

    * **[!UICONTROL Allow structure & content addition]**: Users can add structures between existing ones and add content components or fragments within editable structures.

    * **[!UICONTROL Allow content addition only]**: Users can add content components or fragments within editable structures but cannot add or duplicate structures.

1. After selecting the locking mode, you can define which structures and/or components to lock if you have selected the **[!UICONTROL Content locking]** mode:

    * [Learn how to lock structures](#lock-structures)
    * [Learn how to lock components](#lock-components)

    If you chose the **[!UICONTROL Read only]** mode, you can proceed with finalizing and saving your template as usual.

You can adjust the **[!UICONTROL Governance]** settings at any time when designing your template by selecting the template body. To do this, click the **[!UICONTROL Body]** link in the navigation rail located at the top of the right hand-side pane.

![](assets/content-locking-2.png){width="800" zoomable="yes"}

### Lock structures {#lock-structures}

To lock a structure within your template:

1. Select the structure you want to lock.

1. In the **[!UICONTROL Lock type]** drop-down list, choose **[!UICONTROL Locked]**.

    ![](assets/content-locking-3.png){width="800" zoomable="yes"}

    >[!NOTE]
    >
    >By default, users cannot delete locked structures. You can override this restriction by enabling the **[!UICONTROL Allow delete]** option.

After locking a structure, no further content components or fragments can be duplicated or added inside it. All components within a locked structure are also locked by default. To make a component editable within a locked structure:

1. Select the component you want to unlock.

1. Toggle on the **[!UICONTROL Use specific locking]** option.

1. In the **[!UICONTROL Lock type]** drop-down list, choose **[!UICONTROL Editable]**. To allow content editing while locking styles, select **[!UICONTROL Editable content only]**. [Learn how to lock components](#lock-components)

    ![](assets/content-locking-4.png){width="800" zoomable="yes"}

### Lock components {#lock-components}

To lock a specific component within a structure:

1. Select the component and enable the **[!UICONTROL Use specific locking]** option in the right pane.

1. From the **[!UICONTROL Lock type]** drop-down list, select your preferred locking option:

    ![](assets/content-locking-5.png){width="800" zoomable="yes"}
    
    * **[!UICONTROL Editable content lock only]**: Lock the component's styles but allows content editing.
    * **[!UICONTROL Locked]**: Fully lock both the content and styles of the component.

    >[!NOTE]
    >
    >The **[!UICONTROL Editable]** lock type allows users to edit a component, even within a locked structure. [Learn how to lock structures](#lock-structures)

1. By default, users cannot delete locked components. You can enable deletion by activating the **[!UICONTROL Allow delete]** option.

### Identify locked content {#identify-locked-content}

To easily identify locked structures and components within your template, use the **[!UICONTROL Navigation tree]** located in the left hand side menu. This menu provides a visual overview of all template elements, highlighting locked items with a lock icon and editable items with a pencil icon.

In the example below, governance is enabled for the template body. *Structure 2* is locked with *Component 1* editable, while *Structure 3* is entirely locked.

![](assets/content-locking-6.png){width="800" zoomable="yes"}

## Use templates with locked content {#use-templates-with-locked-content}

When using a template with locked content, the **[!UICONTROL Governance enabled]** message displays in the right pane.

Depending on the type of locking applied to the template, you can perform different actions on the template's structures and components. To quickly identify all editable areas within the template, toggle on the **[!UICONTROL Highlight editable areas]** option.

For example, in the template below, all areas are editable, except for the top image that has been locked, meaning that you cannot edit nor remove it.

![](assets/content-locking-7.png){width="800" zoomable="yes"}

Detailed information on the different types of locking that can applied, refer to these sections:

* [Lock structures](#lock-structures)
* [Lock components](#lock-components)

Here are some examples of emails edition and the associated content locking configuration that has been setup:

<table>
<thead>
  <tr>
    <th>Content locking type</th>
    <th>Template configuration</th>
    <th>Email edition</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Read-only content template</td>
    <td><img src="assets/locking-sample-read-only-conf.png" width="166" height="60" class="modal-image"></td>
    <td><img src="assets/locking-sample-read-only.png" width="92" height="34" class="modal-image"></td>
  </tr>
  <tr>
    <td>Full content is editable but users cannot add any structure or component</td>
    <td><img src="assets/locking-sample-no-addition-conf.png" width="166" height="68" class="modal-image"></td>
    <td><img src="assets/locking-sample-no-addition.png" width="92" height="36" class="modal-image"></td>
  </tr>
  <tr>
    <td>Locked structure that cannot be deleted</td>
    <td><img src="assets/locking-sample-structure-locked-conf.png" width="166" height="45" class="modal-image"></td>
    <td><img src="assets/locking-sample-structure-locked.png" width="92" height="25" class="modal-image"></td>
  </tr>
  <tr>
    <td>Component with locked styles and that cannot be deleted. Users can only modify the content.</td>
    <td><img src="assets/locking-sample-content-only-conf.png" width="166" height="61" class="modal-image"></td>
    <td><img src="assets/locking-sample-content-only.png" width="92" height="33" class="modal-image"></td>
  </tr>
  <tr>
    <td>Editable component within a locked structure.</td>
    <td><img src="assets/locking-sample-editable-component-conf.png" width="166" height="43" class="modal-image"></td>
    <td><img src="assets/locking-sample-editable-component.png" width="92" height="23" class="modal-image"></td>
  </tr>
</tbody>
</table>
