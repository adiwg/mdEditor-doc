## Dictionary Record -- Entity Section
---

### CSV Import Process

New <span class="md-panel">Entities</span> can be created using the mdEditor CSV Import process.  The process is able to create an entity, along with it's associated attributes and domains, in a single step.  However not all of the entity, attribute, and domain elements can be can be created using this process.  Even some of their required elements cannot be captured from a CSV file, so additional editing is always required.  

{% hint style='info' %}
  Only one entity can be imported per CSV file.
{% endhint %}

{% hint style='tip' %}
  The CSV import process will save you time, and typos, if your entities are already in a tabular file such as a spreadsheet.  Otherwise building a preliminary CSV file may be more work than just entering the entities using the standard mdEditor entry panels.
{% endhint %}

### Step 1. Create or Prepare the CSV File

Start by creating a CSV file for your entity.  This is easily done by building the entity in spreadsheet software such as Microsoft Excel and then exporting it as a Comma Separated Value (CSV) file. Use the following rules when building your CSV file:

 * Rows represent data records
 * Each columns is an attributes
 * The first row is expected to be a header row (containing <span class="md-panel">Attribute</span> <span class="md-element">Code Name</span>)

Below is an example of a CSV file showing a table of a few State statistics (name, state abbreviation, capital city, and population).  For expediency, only four attributes and five entity instances (data rows) were added to the table, but the maximum number is not limited by mdEditor.
 
![Example CSV File](/assets/reference/edit-objects/dictionary/entities/sampleCSV.png){caption}

### Step 2. Import the CSV File


![Entity Edit Window with no Entities Defined](/assets/reference/edit-objects/dictionary/entities/dictionary-entity1.png){caption}

Instead of clicking the <strong><span class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Entity</span> </strong> button to create a new <span class="md-panel">Entity</span>, click the <strong><span class="btn btn-success btn-xs"> <i class="fa fa-sign-in"> </i> Import CSV</span> </strong> button in the <span class="md-window">Secondary Sidebar</span>. 
