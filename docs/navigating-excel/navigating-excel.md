---
layout: default
title: Navigating Excel
nav_order: 2
has_children: true
---

# Navigating Excel
{: .no_toc }

This guide expects users to have some experience with Microsoft office already. If you have worked with Word or Powerpoint, then Excel's GUI will not be too different.

This section will cover some of the basics like making insert a chart. We will explore some basic functions that excel offers and create your first table.

---

## Table of Contents
{: .no_toc .text-delta }

* TOC
{:toc}

---

## Before We Start - GUI

Before we jump into making our first table, chart, and start using functions, let us get familiar with the general layout of Excel and it's important buttons.

Here is Excel's toolbar. Currently we are in the <b> Home </b> tab. This is where can format our text and do some basic manipulation. 

![Toolbar](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Excel-Toolbar.png?raw=true "Excel Toolbar")

Notice the **Number** section of the toolbar. This is where you can format your data (eg. percentages, dollars, commas).

![Numbers](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Number-Section.png?raw=true "Numbers Section")

The **Cells** section allows you to add, delete, and format rows. For now, you will just be adding and deleting rows.

![Cells](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Cells-Section.png?raw=true "Cells Section")

Currently, we are working in one spreadsheet. The <b>Sheets</b> tab at the bottom allows you to add, delete, and rename any additional sheets you may need.

![Sheets](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Sheets.png?raw=true "Sheets")

Here is an overview of the Excel GUI with labels. You will get used to most of these buttons and functions as you progress through the guide.

![Overview](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Excel-Screen-Overview.png?raw=true "Overview")

For now, the main areas you will be using are the **Rows, Columns, Active Cell, Toolbar Ribbon.**

---

## What Are Functions?

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

**Note:** This is not an exhaustive list. Refer to the official Microsoft list of built-in functions [here.](https://support.microsoft.com/en-us/office/excel-functions-alphabetical-b3944572-255d-4efb-bb96-c6d90033e188)

---

## Creating A Table and Charts

There are many applications for Excel like accounting and finance. This instruction set will help you create your first table and charts.

Let's create a simple grocery list.

**1.** Type in these values to start. You can bold the headers by highlight the cells and clicking on the **B** button. Right now we have left total blank.

![Grocery-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-1.png?raw=true "Grocery-1")

**2.** Highlight Column B by click on the **B column.**  We want to make these dollars, so click on the **$** symbol under the numbers section.

![Grocery-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-2.png?raw=true "Grocery-2")

**3.** Now, calculate the total. Use the **SUM** function. Click on the cell, and type `=SUM()`. Highlight the costs by holding **Shift** on your keyboard and clicking cell **B2** then **B5**. Press **Enter** on your keyboard to get the sum! 

You can do other things like calculate the average price by following this procedure.

![Grocery-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-3.png?raw=true "Grocery-3")

**4.** Highlight the entire table by Shift-Clicking cells A1 to B6. Navigate to the **Insert** tab and click **Insert Table**. Click **Ok** on the prompt. Now we have a table where we can sort and filter data.

![Grocery-4](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-4.png?raw=true "Grocery-4")

**5.** Click on the drop down arrow on the **Cost** header. Click on **Sort Smallest to Largest**. Now our prices are sorted. 

You can perform other actions like filtering your numbers using equations. 

![Grocery-5](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-5.png?raw=true "Grocery-5")

**6.** With the table highlighted, navigate to **Recommended Charts** button. Choose a graph of your choice.

Excel recommends the most common but you can choose whatever graph make sense to you beside the **Recommended Charts** button. For this example, we will use a pie chart.

![Grocery-6](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-6.png?raw=true "Grocery-6")

**7.** Click on your graph. Click on the **Chart Elements**  button, check **Data Values** and choose where you want it appear. By default, Excel does not show the data values.

![Grocery-7](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Grocery-7.png?raw=true "Grocery-7")

Now, you know how to populate and create simple table. You also know how to generate a chart from your data.

Next, you will learn about [conditional formatting.]() 