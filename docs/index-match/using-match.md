---
layout: default
title: Using MATCH
parent: INDEX MATCH
nav_order: 5
---

# How to use MATCH

Before you begin, make sure you are still using the [sample student dataset](https://drive.google.com/drive/folders/1MX3XusQiBKHx3X8Kf6P3lRY2Q1pZcjB9?usp=sharing) to
follow along.

We will continue focusing on the same section.

![INDEXMATCH-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-1.png?raw=true "INDEXMATCH-1")

## Using MATCH to return a row number

Let's try using MATCH to return a row number.

**1.** Start by entering "Ignacio" into cell H2 and "Year" into cell H3. The reason is that MATCH takes in an argument called "lookup_value". We will pass the value in cell H2 and cell H3 into two separate MATCH formulas to show how MATCH can return a row number or column number.

![MATCH-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-1.png?raw=true "MATCH-1")

**2.** Our first usage of MATCH will be used to determine the row number "Ignacio" is on. We will start by selecting cell I2 and entering in "=MATCH" into the formula bar.

![MATCH-2](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-2.png?raw=true "MATCH-2")

**3.** We will be passing three arguments to this MATCH function. The first argument is the value we are looking up. We pass in H2 because that cell contains "Ignacio"
which is the name we want to look up. The second argument is an array and "A1:A20" represents all cells from A1 to A20. The third argument is the match_type and
we give it 0 which represents an exact match.

![MATCH-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-3.png?raw=true "MATCH-3")

<img src="https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/warning.png?raw=true" alt="warning" width="40px" height="40px" style="vertical-align:middle;"> ***Warning**: The array passed into this MATCH function must contain only cells from the same column. The reason is that we are searching
a single column for a matching value to return a row number.

**4.** Now that you have written your function, press enter. The number 17 will appear in cell I2. With our MATCH function, we searched the "Name" column for
"Ignacio" and returned the matching row number.

![MATCH-4](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-4.png?raw=true "MATCH-4")

## Using MATCH to return a column number

Let's try finding a column number with MATCH.

**1.** Our second usage of MATCH will be used to determine the column number "Year" is on. We will start by selecting cell I3 and entering "=Match" into the formula bar.

![MATCH-5](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-5.png?raw=true "MATCH-5")

**2.** We will pass another three arguments to this new MATCH function. The first argument will be H3 because we are looking up "Year". The second argument is an array and
 "A1:F1" represents all cells from A1 to F1. The third argument will be 0 again to lookup an exact match.

![MATCH-6](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-6.png?raw=true "MATCH-6")

<img src="https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/warning.png?raw=true" alt="warning" width="40px" height="40px" style="vertical-align:middle;"> ***Warning**: The array passed into this MATCH function must contain only cells from the same row. The reason is that we are searching
a single row for a matching value to return a column number.

**3.** Now that you have written your function, press enter. The number 3 will appear in cell I3. With our MATCH function, we searched the first or "Header" row for
"Year" and returned the matching column number.

![MATCH-7](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-7.png?raw=true "MATCH-7")

Using MATCH, we were able to quickly find the row number for Ignacio and column number for Year. Once again, if the table was much larger, it would take longer
to manually look for this data. MATCH allows us to quickly find the position of a cell.
