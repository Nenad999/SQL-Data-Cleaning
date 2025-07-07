# SQL-Data-Cleaning
This project demonstrates a complete data cleaning workflow using a real-world Excel dataset related to sales.

The main steps of the project include:
- Importing raw Excel data
- Removing duplicates
- Eliminating empty and null rows
- Standardizing inconsistent values
- Removing unnecessary columns or rows
- Loading clean data into a SQL table

---

 Tools and Technologies Used
- Microsoft Excel 
- SQL (tested on MySQL)


  Cleaning Process

1. **Import Data**
   - The original Excel file (`layoffs.csv`) was imported into the SQL environment.

2. **Remove Duplicates**
   - All duplicated rows were removed 

3. **Remove Null or Empty Rows**
   - Records with missing essential fields  were deleted:
     
   

4. **Standardize Values**
   - Formatting dates, fixing typos(UnitedStates/UnitedStates.)

5. **Drop Unnecessary Columns**
   - Columns that were irrelevant for analysis were excluded from the final table.

6. **Load to Final Table**
   - The cleaned dataset was saved as  table in the SQL database.
