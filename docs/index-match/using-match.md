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

Let's try using **MATCH** to return a row number.

**1.** Enter **Ignacio** into cell **H2** and **Year** into cell **H3**. The reason is that **MATCH** takes in an argument called **lookup_value**. We will pass the value in cells **H2** and **H3** into two separate **MATCH** formulas to show how **MATCH** can return a row number or column number.

![MATCH-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-1.png?raw=true "MATCH-1")

**2.** Select cell **I2** and enter ```=MATCH``` into the [**formula bar**]. This will determine the row number **Ignacio** is on.

![MATCH-2](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-2.png?raw=true "MATCH-2")

**3.** We will be passing three arguments to this **MATCH** function: cell **H2** containing **Ignacio**, the array **A1:A20** representing all cells from **A1** to **A20**, and **0** for an exact match.

![MATCH-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-3.png?raw=true "MATCH-3")

<img src="https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/warning.png?raw=true" alt="warning" width="40px" height="40px" style="vertical-align:middle;"> ***Warning**: The array passed into this **MATCH** function must contain only cells from the same column. The reason is that we are searching a single column for a matching value to return a row number.


**4.** Press **[Enter]** on your keyboard after writing the function. The number 17 will appear in cell **I2**. With our **MATCH** function, we searched the **Name** column for **Ignacio** and returned the matching row number.

![MATCH-4](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-4.png?raw=true "MATCH-4")

## Using MATCH to return a column number

Let's try finding a column number with **MATCH**.

**1.** Start by selecting cell **I3** and enter ```=Match``` into the **[Formula Bar]**. Our second usage of **MATCH** will be used to determine the column number **Year** is on.

![MATCH-5](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-5.png?raw=true "MATCH-5")

**2.** Pass three arguments to this new **MATCH** function: cell **H3** containing **Year**, the array **A1:F1** representing all cells from A1 to F1, and **0** for an exact match.

![MATCH-6](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-6.png?raw=true "MATCH-6")

<img src="https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/warning.png?raw=true" alt="warning" width="40px" height="40px" style="vertical-align:middle;"> ***Warning**: The array passed into this **MATCH** function must contain only cells from the same row. The reason is that we are searching a single row for a matching value to return a column number.

**3.** Press **[Enter]** on your keyboard after writing the function. The number 3 will appear in cell **I3**. With our **MATCH** function, we searched the first or "Header" row for **Year** and returned the matching column number.

![MATCH-7](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/match-7.png?raw=true "MATCH-7")

Using **MATCH**, we were able to quickly find the row number for **Ignacio** and column number for **Year**. Once again, if the table was much larger, it would take longer to manually look for this data. **MATCH** allows us to quickly find the position of a cell.
