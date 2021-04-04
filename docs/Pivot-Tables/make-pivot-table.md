---
layout: default
title: Making a Pivot Chart
parent: Pivot Tables
nav_order: 3
---

# Your First Pivot Table

Before you begin, make sure you are using the [sample student dataset](https://drive.google.com/drive/folders/1MX3XusQiBKHx3X8Kf6P3lRY2Q1pZcjB9?usp=sharing) to follow along.

**1.** Make sure at least one cell of the dataset is highlighted. Navigate to the **Insert** tab and click **PivotTable** on the top left. A prompt will appear for you to select a range for the table. Excel should autopopulate this section for you if you had one cell in the dataset highlighted. Click **OK**.

![Pivot-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Pivot-1.png?raw=true "Pivot-1")

<img src="https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/note.png?raw=true" alt="note" height="50px"> **Note:** You can click on **Recommended PivotTables** if you want to quickly make something.

A new sheet has now been created on the bottom left. Navigate to that sheet as we will continue using it from now on.

**2.** Highlight one of the cells in within the new PivotTable workspace.

![Pivot-2-1](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Pivot-2-1.png?raw=true "Pivot-2-1")

A new window on the right side should now have appeared. This is where we will manipulate our data.

![Pivot-2-2](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Pivot-2-2.png?raw=true "Pivot-2-2")

**Warning:** If the fields pane on the right does not appear or you accidently close it, navigate to the **PivotTable Analyze** tab and click **Field List.**

**3.** Click and drag the fields to the appropiate boxes in the **PivotTable Fields** section like the image below.

![Pivot-3](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Pivot-3.png?raw=true "Pivot-3")

**Note:** To remove a field, just drag it back out or press **CTRL+Z**.

Now we have a table that shows us the sum of the of ages by student Majors bucketed by their ages. But this isn't very useful is it?

**4.** Click on **Sum of Ages** and select **Value Field Settings.**

![Pivot-4](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Pivot-4.png?raw=true "Pivot-4")

**5.** Select **Count** as we want to show the counts of students by age. But take a look at what other functions you can apply.

![Pivot-5](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Pivot-5.png?raw=true "Pivot-5")

**Note:** You can also change the value format (eg. dollars) by clicking **Number Format.**

**6.** Now drag **Year** to the **Filters**. A new row above your table has been populated. Click the dropdown and now select a year. Now we can filter our results based on the student years!

![Pivot-6](https://github.com/nickluong-dev/Excel-Instruction-Guide/blob/gh-pages/assets/images/Pivot-6.png?raw=true "Pivot-6")

**7.**