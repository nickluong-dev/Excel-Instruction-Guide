---
layout: default
title: Troubleshooting
nav_order: 8
---
# Troubleshooting

| Error                       | Action to Take  |
|:----------------------------|:----------------|
| Target cells are not affected by conditional formatting | Ensure all of your target cells were highlighted before applying conditional formatting. Then, ensure that the data in your selected cells fall into the range you have set for your conditional formatting. |
| **[PivotTable]** Fields tab does not appear | Navigate to the **[PivotTable Analyze]** tab and click **[Field List]**. |
| My **MATCH** function returns the value **#N/A** | Ensure that only cells from one single row or one single column have been selected as the second parameter. |
| **#REF!** appears in the cell when I type my formula | A cell being referred to in the formula is not valid. Adjust the formula to refer to a valid cell. |
| **#NAME?** appears in the cell when I type my formula | Excel does not recognize the text in the formula. Make sure that the formula is typed correctly and text in enclosed in quotation marks. |
| **#VALUE!** appears in the cell when I type my formula | Your formula was passed an incorrect type of argument. Try using functions instead of operators and check that the proper cells are being referenced. |
| Recorded macro does not appear in list of available macros | Macros are saved by worksheet to worksheet basis. After recording a macro, remember to save the sheet as this will automatically save the macro. This also means that the macro will not appear on other worksheets unless you have the worksheet you saved the macro to open.
