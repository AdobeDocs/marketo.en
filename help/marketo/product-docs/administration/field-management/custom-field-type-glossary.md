---
unique-page-id: 2951259
description: Custom Field Type Glossary - Marketo Docs - Product Documentation
title: Custom Field Type Glossary
exl-id: 495d4deb-28f1-4044-98d3-27c20756fe73
---
# Custom Field Type Glossary {#custom-field-type-glossary}

When you create a custom field in Marketo you have a list of types to choose from.

>[!PREREQUISITES]
>
>[Create a Custom Field in Marketo](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

>[!TIP]
>
>Depending on field type, filter/trigger [operators](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md) will be different.

>[!NOTE]
>
>Most fields don’t max out at number of characters, but instead at amount of bytes. Because of that, we’re unable to provide a definitive character limit for each field. The exception is **String**, which maxes out at 255 characters.

## Boolean {#boolean}

**Example Name:** Is Customer - Tag your people as customers

**Example Values:** True (checked) / False (unchecked)

**Operators**: None

## Currency {#currency}

**Example Name:** Budget - Store a number value for a company's budget

**Example Values:** 100

**Operators**: is, is not, between, greater than, less than, at least, at most, is empty, is not empty

## Date {#date}

**Example Name:** Renewal Date - Store your customers renewal dates

**Example Values:** 8/19/14

**Operators**: is, is not, between, in past, in past before, in future, in future after, in time frame, after, before, on or after, on or before, is empty, is not empty

## Datetime {#datetime}

**Example Name:** Created Date - Store the date and time at which a person is created

**Example Values:** 8/19/14 2:00

**Operators**: is, is not, between, in past, in past before, in future, in future after, in time frame, after, before, on or after, on or before, is empty, is not empty

## Email {#email}

**Example Name:** Alternate Email - Keep an alternate email address for your people (cannot actually send emails to this field like the default email address field, that one is special)

**Example Values:** name@company.com

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## Float {#float}

**Example Name:** Grade Point Average - Keep a person's grade point average or any other numeric value that has decimals

**Example Values:** 2.47

**Operators**: between, greater than, less than, at least, at most, is empty, is not empty

## Formula {#formula}

**Example Name:** Salutations - use this special field in a [solution to get the right salutation](/help/marketo/product-docs/administration/field-management/create-and-use-a-concatenated-string-formula-field.md) based on gender

**Example Values:** check the linked solution

## Integer {#integer}

**Example Name:** Number of Employees - store a number value that does not require decimals

**Example Values:** 600

**Operators**: is, is not, between, greater than, less than, at least, at most, is empty, is not empty

## Percent {#percent}

**Example Name:** Likely To Buy - store a percentage value (perhaps calculated on the CRM side)

**Example Values:** 85%

**Operators**: is, is not, between, greater than, less than, at least, at most, is empty, is not empty

## Phone {#phone}

**Example Name:** Alternate Phone - store an additional phone number for your people

**Example Value:** 650-555-5555

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## Score {#score}

**Example Name:** Behavioral Score / Demographic Score - create multiple score fields to keep track of different attributes.

**Example Value:** 14

**Operators**: is, is not, between, greater than, less than, at least, at most, is empty, is not empty

## String {#string}

**Example Name:** Middle Name - store an additional text attribute

**Example Value:** Rose

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## Text Area {#text-area}

**Example Name:** Comments - add a comments field to your forms to allow multi-line text entry

**Example Value:** This article is fantastic!

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## URL {#url}

**Example Name:** Blog - create a field to store person blog urls

**Example Value:** www.myblog.com

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty
