---
layout: default
title: Macros
nav_order: 6
---
# Macros

Macros are built-in tools within Excel that allow you to automate tasks based on pre-determined conditions. Their functions include but are not limited to:

* Applying styles and formats.
* Manipulating data and text.
* Communicating with external and internal data sources.
* Creating entirely new documents.

It is also possible to combine any number of functions into a single macro, saving the time it would take to perform them individually. This section will teach you how to record a macro that combines manipulating data and conditional formatting into one macro.

## Pre-requisites

Before moving forward, make sure you have the [data set](https://drive.google.com/drive/folders/1MX3XusQiBKHx3X8Kf6P3lRY2Q1pZcjB9?usp=sharing) provided here. In the following examples, we will be recording a macro that orders the students in the Student Data.xlsx file by their name and highlighting any field where the tuition is over a certain threshold.

## Instructions

**1.** Open your data set. In this example, we will be using the **Student Data.xlsx** file.

You should now have your spreadsheet open.


**2.** Click on the **[File]** tab at the top left of your window. From there, go to **[Options] > [Customize Ribbon]**.



![Macros-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-1.png?raw=true "Macros-1")

The above menu should appear.


**3.** Enable the **[Developer]** option under **[Main Tabs]**. Press **[OK]**. 

![Macros-2](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-2.png?raw=true "Macros-2")

Tada! The **[Developer]** tab is now added to your ribbon and you can record your first macro.

**4.** Go to the **[Developer]** tab and click **[Record Macro]**. Press **[OK]**.

![Macros-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-3.png?raw=true "Macros-3")

<img src="https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/note.png?raw=true" alt="note" width="40px" height="40px" style="vertical-align:middle;"> ***Note**: It is recommended that you name the macro something that clearly describes what it does. In this case, we have named ours Alphabetize_Name_Descending_Highlight_Tuition_Above_40k”. Setting a shortcut key allows you to use the macro later without going into the menu. Storing the macro in “This Workbook” will allow you to use the macro whenever this specific spreadsheet is open.*

**5.** Click on the column you would like to order using your mouse (in this case, the **Name** column), then go to the **[Data]** tab. 

![Macros-4](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-4.png?raw=true "Macros-4")

**6.** Click the top left button that has **[A on top and Z on the bottom with a downwards arrow]** under the **[Sort & Filter]** section of the ribbon. This orders the names in descending order.

![Macros-5](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-5.png?raw=true "Macros-5")

**7.** Click on the column you would like to highlight cells fulfilling a certain criterion using your mouse (in this case, column **E** above **Program Tuition** column), then go to the **[Home]** tab. Hold **[CTRL]** and **[left click]** the header (**[Program Tuition]**) to deselect it from the conditional formatting.

![Macros-6](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-6.png?raw=true "Macros-6")

<img src="https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/warning.png?raw=true" alt="warning" width="40px" height="40px" style="vertical-align:middle;"> ***Warning**: Make sure the entire column except the **Program Tuition** header is highlighted or conditional formatting will not work!

**8.** Click on **[Conditional Formatting]** under the **[Styles]** section of the ribbon. Hover over **[Highlight Cells Rules]** then click on **[Greater Than…]**.

![Macros-7](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-7.png?raw=true "Macros-7")

**9.** Enter the value in which you would like to highlight then press **[OK]**,

![Macros-8](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-8.png?raw=true "Macros-8")

**10.** Go back to the **[Developer]** tab and press **[Stop Recording]**. Your macro is now complete! Remember to save your work by pressing **[CTRL]+[S]** on your keyboard.

![Macros-9](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-9.png?raw=true "Macros-9")

**11.** To use your macro, go to the **[Developer]** tab and click **[Macros]**.

![Macros-10](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-10.png?raw=true "Macros-10")

**12.** The macro you recorded is now there for use for this workbook! Highlight the macro you would like to use with your mouse, click **[Run]** and the macro will perform all the steps you recorded automatically.

![Macros-11](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-11.png?raw=true "Macros-11")

---

If you have been following the provided data set, the following image should be your result.

![Macros-12](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Macros-12.png?raw=true "Macros-12")
