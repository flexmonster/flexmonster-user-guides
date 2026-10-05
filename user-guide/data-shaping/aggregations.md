---
title: Aggregation functions
permalink: /user-guide/aggregations
---

# Aggregation functions

An aggregation function defines how several data entries are combined into one summary value.

This guide explains the available aggregation functions and how to set them.

## Available aggregations

Not every aggregation suits every field—the **Applies to** column shows which kinds of data each one works with.

| Aggregation | What it does | Applies to |
| --- | --- | --- |
| **Sum** | Adds up the field values. | Numbers |
| **Average** | Calculates the average of the field values. | Numbers |
| **Count** | Counts the number of records. | Any field |
| **Distinct Count** | Counts the number of unique values. | Numbers, text, dates and times |
| **Median** | Calculates the median of the field values. | Numbers |
| **Product** | Multiplies the field values. | Numbers |
| **Min** | Returns the smallest field value. | Numbers, dates and times |
| **Max** | Returns the largest field value. | Numbers, dates and times |
| **First** | Returns the first field value in the records. | Text |
| **Last** | Returns the last field value in the records. | Text |
| **Or** | Returns `true` if at least one field value is `true`. | True/false values |
| **And** | Returns `true` only if all field values are `true`. | True/false values |
| **True Count** | Counts the number of `true` values. | True/false values |
| **False Count** | Counts the number of `false` values. | True/false values |

## Default aggregations

When you add a field to the grid without choosing an aggregation, Flexmonster picks one based on the kind of data the field holds:

- **Sum** for numbers.

- **Count** for text.

- **Min** for dates and times.

- **Or** for true/false values.

## How to change the aggregation for a field

### In the pivot table

**Step 1.** Open the field list.

**Step 2.** In the **Values** box, find the measure you need and select ![Edit measure](../assets/icons/edit_field.svg). As a result, the **Edit measure** dialog with the list of available aggregations will appear.

**Step 3.** Choose the aggregation you need, then select **Apply** in the dialog.

**Step 4.** Select **Apply** in the field list.

### In the flat table

**Step 1.** Open the field list.

**Step 2.** Find the field you need and select ![Edit field](../assets/icons/edit_field.svg). As a result, the **Edit field** dialog with the list of available aggregations will appear.

**Step 3.** Choose the aggregation you need, then select **Apply** in the dialog.

**Step 4.** Select **Apply** in the field list.
