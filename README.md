# ExelSample-Python-exercise1
How to work with Excel by Python as a beginner

1. import openpyxl as xl                       ----->"import excel to project

2. wb = xl.load_workbook("file.xlsx")          ----->"load the file in project"

3. sheet = wb["Sheet1"]                        ----->"select the sheet"

4. cell = sheet.cell(1,1)                      ----->"access to a cell"

5. cell.value                                  ----->"access to a value of a cell"
