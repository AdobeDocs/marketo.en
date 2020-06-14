---
unique-page-id: 10094404
description: Create Custom Field Groups Using the Field Organizer - Marketo Docs - Product Documentation
title: Create Custom Field Groups Using the Field Organizer
---

# Create Custom Field Groups Using the Field Organizer {#create-custom-field-groups-using-the-field-organizer}

Create Custom Field Groups Using the Field Organizer - Marketo Docs - Product Documentation

Before you can enable custom field groups for reporting in the Model Performance Analysis (Leads) Area of Revenue Cycle Explorer, you must categorize standard or custom fields into groups for reporting via the Field Organizer in Marketo Lead Management. This only applies to lead and company attributes.

### What's in this article? {#what-s-in-this-article}

[Create Custom Field Group – String Editor](#createcustomfieldgroupsusingthefieldorganizer-createcustomfieldgroup–stringeditor)  
[Create Custom Field Group – Integer Editor](#createcustomfieldgroupsusingthefieldorganizer-createcustomfieldgroup–integereditor)  
[Create Custom Field Group – Date Editor](#createcustomfieldgroupsusingthefieldorganizer-createcustomfieldgroup–dateeditor)  
When you select a standard or custom field from the Field drop-down in the New Field Organizer dialog box, the system maps the Marketo Lead Management data type associated with the field you want to group with one of three available editors in the Field Organizer: string, integer, or date. 

| Marketo Lead Management Data Type |Field Organizer Editor Data Type |
|---|---|
| String |String |
| Email |String |
| Integer |Integer |
| Text |String |
| URL |String |
| Reference |Not Supported |
| Currency |Integer |
| DateTime |Date |
| Boolean |Not Supported |
| Phone |String |
| Date |Date |
| Float |Integer |
| Calculated |Not Supported |

The next three sections describe how to create a custom field group for a string, integer, or date type.

#### Create Custom Field Group – String Editor {#createcustomfieldgroupsusingthefieldorganizer-createcustomfieldgroup–stringeditor}

##### 1. Click Lead Database. {#createcustomfieldgroupsusingthefieldorganizer-clickleaddatabase.}

![](assets/one.png)

##### 2. Click New, and select New Field Organizer. {#createcustomfieldgroupsusingthefieldorganizer-clicknew-andselectnewfieldorganizer.}

![](assets/two.png)

##### 3. Click Field and select a standard or custom field with a data type that maps to the string editor (see table in previous section). Country is used here. {#createcustomfieldgroupsusingthefieldorganizer-clickfieldandselectastandardorcustomfieldwithadatatypethatmapstothestringeditor(seetableinprevioussection).countryisusedhere.}

![](assets/three.png)

##### 4. Click Create. {#createcustomfieldgroupsusingthefieldorganizer-clickcreate.}

![](assets/four.png)

The new custom group displays in the Lead Database tree represented as Field Name > Field Name Group (example: Country > Country Group).

![](assets/4.5.png)

##### 5. Click the pencil icon to customize the name. For example, you might rename "Country Group" to "Continent". Type the desired new name and click away from the box to auto-save. {#createcustomfieldgroupsusingthefieldorganizer-clickthepencilicontocustomizethename.forexample-youmightrename"countrygroup"to"continent".typethedesirednewnameandclickawayfromtheboxtoauto-save.}

![](assets/five.png)

##### 6. By default, all data values are placed in the "Other" sub-group. To categorize the data values, click Add Group to create a sub-group and give it a name. {#createcustomfieldgroupsusingthefieldorganizer-bydefault-alldatavaluesareplacedinthe"other"sub-group.tocategorizethedatavalues-clickaddgrouptocreateasub-groupandgiveitaname.}

>[!NOTE]
>
>You can add up to ten sub-groups to categorize the data values. Each sub-group created is assigned an ID number.

In this example, groups have been created for most of the continents.

![](assets/six.png)

>[!NOTE]
>
>To delete a sub-group, simply click the red X next to the sub-group name. If there are any data values in the group, the data values will be moved to the default group of Other.

##### 7. Highlight a data value(s) in the canvas and drag and drop the data value(s) into the appropriate sub-group. {#createcustomfieldgroupsusingthefieldorganizer-highlightadatavalue(s)inthecanvasanddraganddropthedatavalue(s)intotheappropriatesub-group.}

![](assets/seven.png)

>[!NOTE]
>
>To remove a data value from a sub-group, reassign the data value to the default group of Other.

##### 8. Use the filter option in the upper left corner directly above the canvas to select and view the data values in one or more sub-groups. The data values based on your filter selection display in the canvas. {#createcustomfieldgroupsusingthefieldorganizer-usethefilteroptionintheupperleftcornerdirectlyabovethecanvastoselectandviewthedatavaluesinoneormoresub-groups.thedatavaluesbasedonyourfilterselectiondisplayinthecanvas.}

![](assets/eight.png)

>[!NOTE]
>
>After the groups are defined, you can enable the custom field group for reporting in Model Performance Analysis (Leads) via the Revenue Cycle Analytics tab in Marketo Lead Management.

#### Create Custom Field Group – Integer Editor {#createcustomfieldgroupsusingthefieldorganizer-createcustomfieldgroup–integereditor}

##### 1. Click Lead Database. {#createcustomfieldgroupsusingthefieldorganizer-clickleaddatabase..1}

![](assets/one.png)

##### 2. Click New, and select New Field Organizer. {#createcustomfieldgroupsusingthefieldorganizer-clicknew-andselectnewfieldorganizer..1}

![](assets/two.png)

##### 3. Click Field and select a standard or custom field with a data type that maps to the string editor (see table in previous section). Annual Revenue is used here. {#createcustomfieldgroupsusingthefieldorganizer-clickfieldandselectastandardorcustomfieldwithadatatypethatmapstothestringeditor(seetableinprevioussection).annualrevenueisusedhere.}

![](assets/nine.png)

##### 4. Click Create. {#createcustomfieldgroupsusingthefieldorganizer-clickcreate..1}

![](assets/9.5.png)

The new custom group displays in the Lead Database tree represented as Field Name > Field Name Group (example: Annual Revenue > Annual Revenue Group).

![](assets/9.6.png)

##### 5. Click the default custom group name above the integer editor to customize the name. For example, you might rename "Annual Revenue Group" to "Annual Revenue by Size". Click Save. {#createcustomfieldgroupsusingthefieldorganizer-clickthedefaultcustomgroupnameabovetheintegereditortocustomizethename.forexample-youmightrename"annualrevenuegroup"to"annualrevenuebysize".clicksave.}

![](assets/eleven.png)

The integer editor allows you create multiple sub-groups to define each sub-group by size. In this example, three groups will be created for Small, Medium, and Enterprise businesses.

##### 6. To add your first group, enter a name in the Group Name field (example: Small) and enter a max value in the Group Range field (example: 200000). Click Add Group. {#createcustomfieldgroupsusingthefieldorganizer-toaddyourfirstgroup-enteranameinthegroupnamefield(example-small)andenteramaxvalueinthegrouprangefield(example-200000).clickaddgroup.}

![](assets/twelve.png)

An empty group entry displays below the group just entered. The example below shows an entry for Small, Medium, and Enterprise businesses.

>[!NOTE]
>
>You can add up to ten sub-groups to categorize the data values. Each Group Range entry builds upon the previous entry. If you leave the last Group Range entry blank for the last custom sub-group you create, a maximum data value is not set.

##### 7. Click the Summary tab to save and review your settings. {#createcustomfieldgroupsusingthefieldorganizer-clickthesummarytabtosaveandreviewyoursettings.}

![](assets/thirteen.png)

>[!NOTE]
>
>To delete a sub-group, click the red X next to the sub-group name.

##### 8. On the Summary page, review your settings. {#createcustomfieldgroupsusingthefieldorganizer-onthesummarypage-reviewyoursettings.}

![](assets/13.5.png)

>[!NOTE]
>
>After the groups are defined, you can enable the custom field group for reporting in Model Performance Analysis (Leads) via the Revenue Cycle Analytics tab in Marketo Lead Management.

#### Create Custom Field Group – Date Editor {#createcustomfieldgroupsusingthefieldorganizer-createcustomfieldgroup–dateeditor}

##### 1. Click Lead Database. {#createcustomfieldgroupsusingthefieldorganizer-clickleaddatabase..2}

![](assets/one.png)

##### 2. Click New, and select New Field Organizer. {#createcustomfieldgroupsusingthefieldorganizer-clicknew-andselectnewfieldorganizer..2}

![](assets/two.png)

##### 3. Click Field and select a standard or custom field with a data type that maps to the string editor (see table in previous section). Acquisition Date is used here. {#createcustomfieldgroupsusingthefieldorganizer-clickfieldandselectastandardorcustomfieldwithadatatypethatmapstothestringeditor(seetableinprevioussection).acquisitiondateisusedhere.}

![](assets/fourteen.png)

##### 4. Click Create. {#createcustomfieldgroupsusingthefieldorganizer-clickcreate..2}

![](assets/14.5.png)

The new custom group displays in the Lead Database tree represented as Field Name > Field Name Group (example: Acquisition Date > Acquisition Date Group).

![](assets/14.6.png)

##### 5. Click the default custom group name above the date editor to customize the name. For example, you might rename "Acquisition Date Group" to "Acquisition Date Categories". Click Save. {#createcustomfieldgroupsusingthefieldorganizer-clickthedefaultcustomgroupnameabovethedateeditortocustomizethename.forexample-youmightrename"acquisitiondategroup"to"acquisitiondatecategories".clicksave.}

![](assets/fifteen.png)

The date editor allows you create multiple sub-groups and define each sub-group by date. In this example, three groups will be created: Q1-15 Leads, Q2-15 Leads, and Q3-15 Leads.

##### 6. To add your first group, enter a name in the Group Name field (example: Q1-15 Leads) and enter a date in the date field that represents the date the lead was acquired on or before (example: 3/31/2015 for the last day of Q1-15). Click Add Group. {#createcustomfieldgroupsusingthefieldorganizer-toaddyourfirstgroup-enteranameinthegroupnamefield(example-q1-15leads)andenteradateinthedatefieldthatrepresentsthedatetheleadwasacquiredonorbefore(example-3/31/2015forthelastdayofq1-15).clickaddgroup.}

![](assets/sixteen.png)

>[!NOTE]
>
>You can add up to ten sub-groups to categorize the data values. Each Group Range entry builds upon the previous entry. If you leave the last Group Range entry blank for the last custom sub-group you create, an end date value is not set.

The example below shows an entry for Q1 2015 leads through Q3.   ![](assets/16.5.png)

And that's it! Good job.
