---
layout: default
title: Using INDEX MATCH
parent: INDEX MATCH
nav_order: 6
---

# How to Use INDEX MATCH

If you haven't done so already, make sure you are still using the [sample student dataset](https://drive.google.com/drive/folders/1MX3XusQiBKHx3X8Kf6P3lRY2Q1pZcjB9?usp=sharing) to
follow along.

We will continue focusing on the same section.

![INDEXMATCH-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-1.png?raw=true "INDEXMATCH-1")

## Combining INDEX and MATCH

Now that you know how to use INDEX and MATCH separately, let's try combining them to create an INDEX MATCH formula. We will be using this formula to
find Frieda's Major.

**1.** Enter **Frieda** into cell H2 and **Major** into cell H3. We will be using two MATCH functions to grab the row number of **Frieda** and the
column number of **Major**.

![INDEXMATCH-2](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-2.png?raw=true "INDEXMATCH-2")

**2.** Select cell I2 and type ```=INDEX(A1:F20``` to select all cells from **A1** to **F20**.

![INDEXMATCH-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-3.png?raw=true "INDEXMATCH-3")

**3.** Give the **INSERT** function the second argument, a **MATCH** function returning a row number.

The **MATCH** function will take in the following arguments: cell **H2** containing **Frieda**, the array **A1:A20**, and **0** for an exact match.

![INDEXMATCH-4](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-4.png?raw=true "INDEXMATCH-4")

**4.** Give the **INSERT** function the next argument, a second **MATCH** function returning a column number.

The second **MATCH** function will take in the following arguments: cell **H3** containing **"Major"**, the array **A1:F1**, and **0** for an exact match.

![INDEXMATCH-5](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-5.png?raw=true "INDEXMATCH-5")

<img src="https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/note.png?raw=true" alt="note" width="40px" height="40px" style="vertical-align:middle;"> ***Note**: Remember that the array must contain cells in the same row if you wish to return a column number.

**5.** Press **[Enter].** We have index matched **Frieda**'s **Major** to **Music.**

The INDEX function now has three arguments: the array we want to retrieve a value from, a MATCH function that returns the row number **Frieda** is on, and a MATCH function that returns the column number **Major** is on.

![INDEXMATCH-6](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-6.png?raw=true "INDEXMATCH-6")

This is an example of what you can do using INDEX MATCH. Imagine that you are working with an extremely large dataset. Using INDEX MATCH will allow you to easily pull the data you are looking for, no matter the size of the table. As Nintendo said in their ad for the Nintendo Entertainment System, "Now You're Playing With Power".
