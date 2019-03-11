## Dictionary Record -- CSV Import Process
---

### Create or Prepare the CSV File

Start by creating a CSV file for your entity.  This is easily done by building the entity in spreadsheet software such as Microsoft Excel or LibreOffice Calc then exporting it as a Comma Separated Value (CSV) file. Use the following rules for building your CSV file:

 * Rows represent data records
 * Each column is an attribute
 * mdEditor expects the first row to be a header row (contains the <span class="md-panel">Attribute</span> <span class="md-element">Code Names</span>)

Below is an example of a CSV file showing a table with a few U.S. State statistics (name, state abbreviation, capital city, and population).  For expediency, only four attributes and five entity instances (data rows) were added to the table, but the maximum number is not limited by mdEditor.
 
![Example CSV File](/assets/reference/edit-objects/dictionary/entities/sampleCSV.png){caption}
