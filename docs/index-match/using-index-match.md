---
layout: default
title: Using INDEX MATCH
parent: INDEX MATCH
nav_order: 6
---

# How to Use INDEX MATCH

Before you begin, make sure you are still using the [sample student dataset](https://drive.google.com/drive/folders/1MX3XusQiBKHx3X8Kf6P3lRY2Q1pZcjB9?usp=sharing) to
follow along.

We will continue focusing on the same section.

![INDEXMATCH-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-1.png?raw=true "INDEXMATCH-1")

## Combining INDEX and MATCH

Now that you know how to use INDEX and MATCH separately, let's try combining them to create an INDEX MATCH formula. We will be using this formula to
find Frieda's Major.

**1.** Start by entering "Frieda" into cell H2 and "Major" into cell H3. We will be using two MATCH functions to grab the row number of "Frieda" and the
column number of "Major".

![INDEXMATCH-2](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-2.png?raw=true "INDEXMATCH-2")

**2.** By now you should know how to use the formula bar. Start by selecting cell I2 and typing "=INDEX(A1:F20" to select all cells from A1 to F20.

![INDEXMATCH-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-3.png?raw=true "INDEXMATCH-3")

**3.** As discussed in the "Using INDEX" section, we can pass in a row number and column number into the INDEX function. This will allow us to get the value
inside the cell where the row and column numbers intersect. To combine INDEX and MATCH, we will be passing in two MATCH formulas for the row and column numbers.
The first MATCH formula will take in three arguments. The first argument will be cell H2 containing "Frieda", the second argument will be the array "A1:A20", and
the third argument will be 0 for an exact match. Remember that the array must contain cells in the same column if you wish to return a row number.

![INDEXMATCH-4](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-4.png?raw=true "INDEXMATCH-4")

**4.** The third argument we will pass into our INSERT function will be a second MATCH function. The second match function will take in the following arguments:
cell H3 containing "Major", the array "A1:F1", and 0 for an exact match. Remember that the array must contain cells in the same row if you wish to return a column number.

![INDEXMATCH-5](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-5.png?raw=true "INDEXMATCH-5")

**5.** The INDEX function that has been written now has three arguments. The first is the array we want to retrieve a value from, the second is a MATCH function that
returns the row number "Frieda" is on, and the third is a MATCH function that returns the column number "Major" is on. When you press enter, "Music" will appear in cell I2.
If you look at the cell where "Frieda" and "Major" intersect, you can see that Frieda's Major is Music.

![INDEXMATCH-6](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-6.png?raw=true "INDEXMATCH-6")

This is an example of what you can do using INDEX MATCH. Imagine that you are working with an extremely large dataset. Using INDEX MATCH will allow you to easily pull
the data you are looking for, no matter the size of the table. As Nintendo said in their ad for the Nintendo Entertainment System, "Now You're Playing With Power".
