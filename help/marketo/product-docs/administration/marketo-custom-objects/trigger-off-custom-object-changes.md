---
unique-page-id: 11378713
description: Trigger Off Custom Object Changes - Marketo Docs - Product Documentation
title: Trigger Off Custom Object Changes
---

# Trigger Off Custom Object Changes {#trigger-off-custom-object-changes}

>[!NOTE]
>
>This feature is available only:
>
>* For customers on the Orion infrastructure
>* For use only with Marketo custom objects, not custom objects synced through the native Salesforce or Microsoft Dynamics integration
>* As a trigger, not a filter
>
>Please contact [Marketo Support](http://support.marketo.com) to have Custom Object Change Triggers enabled.

In a smart campaign's smart list, you can trigger a flow action when a custom object is added to a person or company. You can also create a smart list that uses a *change* in a custom object as a trigger. For example, use it to send an email when a course name is updated. 

>[!NOTE]
>
>An activity log entry is not created when a custom object record is changed. 

1. In Marketo, go to **Marketing Activities.**

   ![](assets/image2016-7-25-15-3a49-3a52.png)

1. Create or open an existing Smart Campaign, and select the Smart List.

   ![](assets/image2016-7-25-16-3a9-3a19.png)

1. Search for the trigger you need and drag it onto the canvas.

   ![](assets/image2016-7-25-16-3a16-3a43.png)

1. Select the trigger attribute.

   ![](assets/image2016-7-25-16-3a21-3a42.png)

1. Optionally, set a constraint.

   ![](assets/image2016-9-6-14-3a25-3a22.png)

1. And there you are. The change is automatically saved.

   ![](assets/image2016-9-6-14-3a25-3a54.png)

   >[!NOTE]
   >
   >**Related Articles**
   >
   >    
   >    
   >    * [Create a Smart List](../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)
   >    * [Understanding Marketo Custom Objects](understanding-marketo-custom-objects.md)
   >    
   >

