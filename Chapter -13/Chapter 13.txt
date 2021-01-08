
### Practice Questions:-

1. What does the openpyxl.load_workbook() function return?

**Answers**

```It returns the workbook object.```

2. What does the wb.sheetnames workbook attribute contain?

**Answers**

```It contain sheetnames of that file.```

3. How would you retrieve the Worksheet object for a sheet named 'Sheet1'?

**Answers**

```wb['Sheet1']```

4. How would you retrieve the Worksheet object for the workbook’s active sheet?

**Answers**

```wb.get_active_sheet()```

5. How would you retrieve the value in the cell C5?

**Answers**

```sheet['C5'].value```

6. How would you set the value in the cell C5 to "Hello"?

**Answers**

```sheet['C5'] = 'Hello'```

7. How would you retrieve the cell’s row and column as integers?

**Answers**

```cell.row and cell.column```

8. What do the sheet.max_column and sheet.max_row sheet attributes hold, and what is the data type of these attributes?

**Answers**

```The hold highest rows and highest column.
They are Integers```

9. If you needed to get the integer index for column 'M', what function would you need to call?

**Answers**

```openpyxl.cell.column_index_from_string('M')```

10. If you needed to get the string name for column 14, what function would you need to call?

**Answers**

```openpyxl.cell.get_column_letter(14)```

11. How can you retrieve a tuple of all the Cell objects from A1 to F1?

**Answers**

```sheet['A1':'F1']```

12. How would you save the workbook to the filename example.xlsx?

**Answers**

```wb.save('example.xlsx’)```

13. How do you set a formula in a cell?

**Answers**

```Formula is same as value, set the cell value to string of formula text.```

14. If you want to retrieve the result of a cell’s formula instead of the cell’s formula itself, what must you do first?

**Answers**

```We retrieve the value of cell in which we assigned formula.```
15. How would you set the height of row 5 to 100?

**Answers**

```sheet.row_dimensions[5].height = 100```

16. How would you hide column C?

**Answers**

```sheet.column_dimensions['C'].hidden = True```

17. What is a freeze pane?

**Answers**

```Rows and columns which appears in screen always are known as the freeze panes.```

18. What five functions and methods do you have to call to create a bar chart?

**Answers**
```
openpyxl.charts.Reference()
chartObj.append(seriesObj)
openpyxl.charts.BarChart()
add_chart()
openpyxl.charts.Series()
```