---
title: Filtering by condition
permalink: /user-guide/filtering-by-condition
---

# Filtering by condition

The conditional filter allows filtering members of a field based on the specified condition. You can filter by condition in both the pivot and the flat table.

Note that the conditional filters are available only for the fields that contain numbers or text.

You can apply a conditional filter and a member filter to the same field.

## Available conditions

The conditions you can choose from depend on the kind of data the field holds.

### Numbers

<table>
<thead>
<tr><th>Condition</th><th>What it shows</th></tr>
</thead>
<tbody>
<tr><td>**Equal**</td><td>Numbers equal to the value you specify.</td></tr>
<tr><td>**Not equal**</td><td>Numbers not equal to the value you specify.</td></tr>
<tr><td>**Greater**</td><td>Numbers greater than the value you specify.</td></tr>
<tr><td>**Greater or equal**</td><td>Numbers greater than or equal to the value you specify.</td></tr>
<tr><td>**Less**</td><td>Numbers less than the value you specify.</td></tr>
<tr><td>**Less or equal**</td><td>Numbers less than or equal to the value you specify.</td></tr>
<tr><td>**Between**</td><td>Numbers inside the range you specify, including the range boundaries.</td></tr>
<tr><td>**Not between**</td><td>Numbers outside the range you specify, excluding the range boundaries.</td></tr>
</tbody>
</table>

### Text

<table>
<thead>
<tr><th>Condition</th><th>What it shows</th></tr>
</thead>
<tbody>
<tr><td>**Equal**</td><td>Text equal to the value you specify.</td></tr>
<tr><td>**Not equal**</td><td>Text not equal to the value you specify.</td></tr>
<tr><td>**Begin**</td><td>Text that begins with the value you specify.</td></tr>
<tr><td>**Not begin**</td><td>Text that doesn't begin with the value you specify.</td></tr>
<tr><td>**End**</td><td>Text that ends with the value you specify.</td></tr>
<tr><td>**Not end**</td><td>Text that doesn't end with the value you specify.</td></tr>
<tr><td>**Contain**</td><td>Text that contains the value you specify.</td></tr>
<tr><td>**Not contain**</td><td>Text that doesn't contain the value you specify.</td></tr>
</tbody>
</table>

## Configure the filter

**Step 1.** Open the filter view by selecting the field’s name.

**Step 2.** Select **Add condition**. As a result, the **Conditional filters** section will appear.

**Step 3.** Choose a condition from the dropdown menu and enter a value in the input field. The **Between** and **Not between** conditions take two values that define the range.

Check out an example of a filter configuration:

![Conditional filter config](../assets/images/data-shaping/conditional_filter.png)

**Step 4.** *(Optional)* To filter by more than one condition, select **Add condition** again and configure the next one.

**Step 5.** Once the filter is configured, select **Apply** to save your configuration.

## Clear the filter

To clear a specific conditional filter, select ![Clear condition](../assets/icons/ui_close.svg) next to the necessary filter configuration:

![Clear one condition](../assets/images/data-shaping/clear_one_condition.png)

To clear all conditional filters at once, select **Clear filter**:

![Clear all conditions](../assets/images/data-shaping/clear_all_conditions.png)

Then, select **Apply** to save your changes.