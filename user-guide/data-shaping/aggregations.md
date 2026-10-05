---
title: Aggregation functions
permalink: /user-guide/aggregations
---

# Aggregation functions

An aggregation function defines how several data entries are combined into one summary value.

This guide explains the available aggregation functions and how to set them.

## Available aggregations

Not every aggregation suits every field—the **Applies to** column shows which kinds of data each one works with.

<table>
<thead>
<tr><th>Aggregation</th><th>What it does</th><th>Applies to</th></tr>
</thead>
<tbody>
<tr><td>**Sum**</td><td>Adds up the field values.</td><td>Numbers</td></tr>
<tr><td>**Average**</td><td>Calculates the average of the field values.</td><td>Numbers</td></tr>
<tr><td>**Count**</td><td>Counts the number of records.</td><td>Any field</td></tr>
<tr><td>**Distinct Count**</td><td>Counts the number of unique values.</td><td>Numbers, text, dates and times</td></tr>
<tr><td>**Median**</td><td>Calculates the median of the field values.</td><td>Numbers</td></tr>
<tr><td>**Product**</td><td>Multiplies the field values.</td><td>Numbers</td></tr>
<tr><td>**Min**</td><td>Returns the smallest field value.</td><td>Numbers, dates and times</td></tr>
<tr><td>**Max**</td><td>Returns the largest field value.</td><td>Numbers, dates and times</td></tr>
<tr><td>**First**</td><td>Returns the first field value in the records.</td><td>Text</td></tr>
<tr><td>**Last**</td><td>Returns the last field value in the records.</td><td>Text</td></tr>
<tr><td>**Or**</td><td>Returns `true` if at least one field value is `true`.</td><td>True/false values</td></tr>
<tr><td>**And**</td><td>Returns `true` only if all field values are `true`.</td><td>True/false values</td></tr>
<tr><td>**True Count**</td><td>Counts the number of `true` values.</td><td>True/false values</td></tr>
<tr><td>**False Count**</td><td>Counts the number of `false` values.</td><td>True/false values</td></tr>
</tbody>
</table>

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
