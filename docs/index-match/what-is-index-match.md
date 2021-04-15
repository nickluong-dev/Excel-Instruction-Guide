---
layout: default
title: What is INDEX MATCH?
parent: INDEX MATCH
nav_order: 2
---

# What is INDEX MATCH?

INDEX MATCH is a combination of two functions in EXCEL called INDEX and MATCH. Combined, these two formulas can look up and return the value of a cell

vertically and/or horizontally. Together, INDEX and MATCH are referred to as INDEX MATCH.

## What is INDEX?

INDEX is a formula that returns the value of a cell in a table based on the column and row number. The arguments passed into this function are:

**1.** array: a range of cells or an array reference. The format will be "start:end" eg. "A1:F20"

**2.** row_num: the row position in the reference or array.

**3.** col_num(optional): the column position in the reference or array.

**4.** area_num(optional): the range in reference that should be used.

## What is MATCH?

MATCH is a formula that returns the position of a cell in a row or column. The arguments passed into this function are:

**1.** lookup_value: the value to match in lookup_array.

**2.** lookup_array: a range of cells or an array reference. The format will be "start:end" eg. "A1:F20"

**3.** match_type(optional): 1 is for exact or next smallest matches(default), 0 is for exact matches, and -1 is for exact or next largest matches.

## How do you combine INDEX and MATCH?

To combine INDEX and MATCH, you pass the return values of two MATCH formulas into row_num and col_num. There will be a step-by-step guide, with visuals, showing you

how to use INDEX MATCH in a later section.
