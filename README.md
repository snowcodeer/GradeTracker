# Grade Tracker

## Description
Currently a grade tracker for the Bioengineering department, including Biomedical Engineering and Molecular Bioengineering Streams.
Future updates will make it a general grade tracker applicable to any course.

## Instructions (WIP)
1. Run macro "ShowMainMenu" to open course selection form
2. Run macro "ShowElectiveSelection" to open elective selection form. This will open Y3 or Y4 selection depending on the active sheet.
  - Keyboard shortcut: Ctrl+Shift+S

## Current features
- Course selection menu
- Elective selection menu
- Tables available for first 3 years of MBE and BME. 
- Input grades and calculate weighted totals for a current average, displays average required to reach goals (firsr or 2:1).
- Conditional formatting for grade cutoffs. (Green for 1, light green for 2:1, yellow for 2:2, orange for 3, red for fail)
- Option to create new modules with entered information (select relevant rows) -> keyboard shortcut: Ctrl+Shift+M
- Module selection form works for both MBE and BME, and Y3 and Y4
- Option to select target visibility (1st, 2:1, 2:2, 3rd)
 
## Future updates
- Pop-up for electives only appears on first opening of sheet, and then option to change after 
- Auto-hide calculation columns
- Automatic conversion from document to spreadsheet, large conversions of multiple modules i.e. search headings and assign columns etc.
- Module creation
- Totals sheet: 
  - Provisional totals (update using existing data in sheet) and then have a column for final adjusted grades (user input) and then adjustment calculation, calculate all these totals using the module weight given 
  - Check overall for on track for first, second, etc 
- Form for new module?
- Developer mode for creating entirely new courses. For now just have an separate excel document for this 
