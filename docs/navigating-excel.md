---
layout: default
title: Navigating Excel
nav_order: 2
---
# Navigating Excel

This guide expects users to have some experience with Microsoft office already. If you have worked with Word or Powerpoint, then Excel's GUI will not be too different. 

This section will cover some of the basics like making insert a chart. We will explore some basic functions that excel offers and create your first table.

## Table of Contents
---
{: .no_toc .text-delta }
* TOC
{:toc} 

## Before We Start - GUI
---

Before we jump into making our first table, chart, and start using functions, let us get familiar with the general layout of Excel and it's important buttons.

Here is Excel's toolbar. Currently we are in the <b> Home </b> tab. This is where can format our text and do some basic manipulation. 

![Toolbar](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Excel-Toolbar.png?raw=true "Excel Toolbar")

Notice the <b> Number </b> section of the toolbar. This is where you can format your data (eg. percentages, dollars, commas).

![Numbers](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Number-Section.png?raw=true "Numbers Section")

The <b>Cells</b> section allows you to add, delete, and format rows. For now, you will just be adding and deleting rows.

![Cells](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Cells-Section.png?raw=true "Cells Section")

Currently, we are working in one spreadsheet. The <b>Sheets</b> tab at the bottom allows you to add, delete, and rename any additional sheets you may need.

![Sheets](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Sheets.png?raw=true "Sheets")

Here is an overview of the Excel GUI with labels. You will get used to most of these buttons and functions as you progress through the guide.

![Overview](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Excel-Screen-Overview.png?raw=true "Overview")

## What Are Functions?
---
A function in excel are predefined formulas that perform calculations in a specific order. This is very powerful as we don't have to implement everything manually and Excel has plenty of them for us! 

As we go along, we will explain any functions used.

Below are some common functions.

| Function      | Description                                                |
| ------------- |:-----------------------------------------------------------|
| SUM           | adds the total of a series of numbers                      |
| AVERAGE       | calculates the average of a series of numbers              |
| PRODUCT       | multiplies all numbers of a series of numbers              |
| IF            | checks if a condition is met and returns True or False     |
| AND           | checks if all conditions are met and returns True or False |
| YEAR          | Extracts the year from a given date (eg. 01/01/2000)       |

<b>Note: </b> This is not an exhaustive list. Refer to the official Microsoft list of built-in functions [here.](https://support.microsoft.com/en-us/office/excel-functions-alphabetical-b3944572-255d-4efb-bb96-c6d90033e188)



## Creating A Table and Charts
---

There are many applications for Excel like accounting and finance. This instruction set will help you create your first table and charts.

Let's create a simple grocery list.

1. Type in these values to start. You can bold the headers by highlight the cells and clicking on the <b>B</b> button. Right now we have left total blank.

![Grocery-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-1.png?raw=true "Grocery-1")


2. Highlight Column B by click on the <b> B column. </b> We want to make these dollars so click on the <b> $ </b> symbol under the numbers section.

![Grocery-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-1.png?raw=true "Grocery-1")

3. Now we want to calculate the total. Use the <b> SUM </b> function. Click on the cell, and type `=SUM()`. Highlight the costs by holding <b>Shift</b> on your keyboard and clicking cell <b>B2</b> then <b>B5</b>.

![Grocery-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-3.png?raw=true "Grocery-3")
