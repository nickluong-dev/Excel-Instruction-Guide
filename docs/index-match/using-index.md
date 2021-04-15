---
layout: default
title: Using INDEX
parent: INDEX MATCH
nav_order: 4
---

# How to use INDEX MATCH

Before you begin, make sure you are using the [sample student dataset](https://drive.google.com/drive/folders/1MX3XusQiBKHx3X8Kf6P3lRY2Q1pZcjB9?usp=sharing) to follow along.

The image below is the section of the table we will be focusing on.

![INDEXMATCH-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-match-1.png?raw=true "INDEXMATCH-1")

## Using INDEX

Let's try out the INDEX function to grab **Awilda**'s age.

**1.** Select the cell you want the return value of **INDEX** to appear in. In this example, cell **H2** will be used.

![INDEX-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-1.png?raw=true "INDEX-1")

**2.** Select an empty cell then click on the **Formula Bar**. Anything typed into this bar will appear in the selected cell. This will make it easier to type in formulas that are much longer than a selected cell.

![INDEX-2](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-2.png?raw=true "INDEX-2")

**3.** Type ```=INDEX``` in the formula bar, a dropdown autocomplete menu appears. This shows all functions that match what you are typing in. You can select the function you are typing to type with the up and down arrow keys. If you press tab, the formula bar will autofill with the selected function.

![INDEX-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-3.png?raw=true "INDEX-3")

**4.** Pass three arguments to **INDEX**: The array **A1:F20** represents all cells from **A1** to **F20**, **10** is **Awilda**'s row, and **2** is **Age**'s column.

You can see how there is a blue outline around the cells we have selected and each selected cell is now blue. The second argument is the row number **Awilda** is in. The third argument is the column number **Age** is in.

![INDEX-4](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-4.png?raw=true "INDEX-4")

**5.** Press **Enter** after entering your function. The number 23 will appear in cell **H2**.

With our INDEX function, we selected **Awilda**'s row and the **Age** column. The intersection of the selected row and column is a cell containing the number **23**.

![INDEX-5](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/index-5.png?raw=true "INDEX-5")

Using **INDEX**, we were able to quickly find **Awilda**'s age. If the table we were working with was much larger, it would be harder to scroll through the table to find this data. **INDEX** allows us to find values within a cell if we know the row and column we wish to look within.
