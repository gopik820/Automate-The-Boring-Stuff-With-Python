### Practice Questions:-

1. What three files do you need for EZSheets to access Google Sheets?

**Answers**
```
credentials-sheets.json, token-sheets.pickle and token-drive.pickle
```
2. What two types of objects does EZSheets have?

**Answers**
```
ezsheets.Spreadsheet and ezsheets.Sheet
```
3. How can you create an Excel file from a Google Sheet spreadsheet?

**Answers**
```
downloadAsExcel() 

```
4. How can you create a Google Sheet spreadsheet from an Excel file?

**Answers**
```
ezsheets.upload() function and pass the filename
```

5. The ss variable contains a Spreadsheet object. What code will read data from the cell B2 in a sheet titled “Students”?

**Answers**

```ss.title = 'Students'```

6. How can you find the column letters for column 999?

**Answers**

``` ezsheets.getColumnLetterOf(999)```

7. How can you find out how many rows and columns a sheet has?

**Answers**

``` sheet.rowCount and sheet.columnCount```

8. How do you delete a spreadsheet? Is this deletion permanent?

**Answers**

```ss.delete()

The delete() method will move your spreadsheet to the Trash folder on your Google Drive.
```
9. What functions will create a new Spreadsheet object and a new Sheet object, respectively?

**Answers**

```ezsheets.Spreadsheet()```

10. What will happen if, by making frequent read and write requests with EZSheets, you exceed your Google account’s quota?

**Answers**
```
Attempting to exceed this quota will raise the googleapiclient.errors.HttpError “Quota exceeded for quota group” exception.
```