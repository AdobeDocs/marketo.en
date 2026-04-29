---
unique-page-id: 2951259
description: "Reference for custom field types in Marketo including Boolean, Currency, Date, Email, Formula, and more."
title: Custom Field Type Glossary
exl-id: 495d4deb-28f1-4044-98d3-27c20756fe73
feature: Field Management
---
# Custom Field Type Glossary {#custom-field-type-glossary}

When you create a custom field in Marketo, you have a list of types to choose from.

>[!PREREQUISITES]
>
>[Create a Custom Field in Marketo](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

>[!TIP]
>
>Depending on field type, filter/trigger [operators](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md) will be different.

>[!NOTE]
>
>Most fields do not max out at the number of characters, but instead at the amount of bytes. Because of that, Marketo is unable to provide a definitive character limit for each field. The exception is **String**, which maxes out at 255 characters.

## Boolean {#boolean}

**Example Name:** Is Customer - Tag people as customers

**Example Values:** True (checked) / False (unchecked)

**Operators**: None

## Currency {#currency}

**Example Name:** Budget - Store a number value for a company's budget

**Example Values:** 100

**Operators**: is, is not, between, greater than, less than, at least, at most, is empty, is not empty

## Date {#date}

**Example Name:** Renewal Date - Store your customers' renewal dates

**Example Values:** 8/19/14

**Operators**: is, is not, between, in past, in past before, in future, in future after, in time frame, after, before, on or after, on or before, is empty, is not empty

## Datetime {#datetime}

**Example Name:** Created Date - Store the date and time at which a person is created

**Example Values:** 8/19/14 2:00

**Operators**: is, is not, between, in past, in past before, in future, in future after, in time frame, after, before, on or after, on or before, is empty, is not empty

## Email {#email}

**Example Name:** Alternate Email - Keep an alternate email address for people (cannot actually send emails to this field like the default email address field)

**Example Values:** <name@company.com>

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## Float {#float}

**Example Name:** Grade Point Average - Keep a person's grade point average or any other numeric value that has decimals

**Example Values:** 2.47

**Operators**: between, greater than, less than, at least, at most, is empty, is not empty

## Formula {#formula}

**Example Name:** Salutations - Use this special field in a [solution to get the right salutation](/help/marketo/product-docs/administration/field-management/create-and-use-a-concatenated-string-formula-field.md) based on gender

**Example Values:** Check the linked solution

## Integer {#integer}

**Example Name:** Number of Employees - Store a number value that does not require decimals

**Example Values:** 600

**Operators**: is, is not, between, greater than, less than, at least, at most, is empty, is not empty

## Percent {#percent}

**Example Name:** Likely To Buy - Store a percentage value (calculated in the CRM)

**Example Values:** 85%

**Operators**: is, is not, between, greater than, less than, at least, at most, is empty, is not empty

## Phone {#phone}

**Example Name:** Alternate Phone - Store an additional phone number for people

**Example Value:** 650-555-5555

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## Score {#score}

**Example Name:** Behavioral Score / Demographic Score - Create multiple score fields to keep track of different attributes

**Example Value:** 14

**Operators**: is, is not, between, greater than, less than, at least, at most, is empty, is not empty

## String {#string}

**Example Name:** Middle Name - Store an additional text attribute

**Example Value:** Rose

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## Text Area {#text-area}

**Example Name:** Comments - Add a comments field to your forms to allow multi-line text entry

**Example Value:** This article is fantastic!

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## URL {#url}

**Example Name:** Blog - Create a field to store person blog URLs

**Example Value:** <www.myblog.com>

**Operators**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty
