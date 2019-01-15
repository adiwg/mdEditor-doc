## Dictionary Record -- Entity Section
---

### CSV Import Process

New <span class="md-panel">Entities</span> can be created using the mdEditor CSV Import process.  The process is able to create an entity along with it's attributes and domains in a single step.  However not all of the entity, attribute, and domain elements can be can be created using this process.  Even some required elements cannot be captured, so some additional editing is always required.  

{% hint style='info' %}
  Only one entity can be imported per CSV file.
{% endhint %}

### Step 1. Create the CSV File

Start by creating a CSV file for your entity.  This is easily done by building the entity in spreadsheet software such as Microsoft Excel and then exporting it as a Comma Separated Value (CSV) file. Use the following rules when building your CSV file:

 * Rows are data records
 * Columns are attributes
 * The first row is reserved for headers (<span class="md-panel">Attribute</span> <span class="md-element">Code Name</span>)

Below is an example of a CSV file showing a table of a few State statistics (name, state abbreviation, capital city, and population).  For expediency, only five entity instances (data rows) were added to the table, but the number of rows is not limited by mdEditor.
 
![Example CSV File](/assets/reference/edit-objects/dictionary/entities/sampleCSV.png){caption}



![Entity Edit Window with no Entities Defined](/assets/reference/edit-objects/dictionary/entities/dictionary-entity1.png){caption}
