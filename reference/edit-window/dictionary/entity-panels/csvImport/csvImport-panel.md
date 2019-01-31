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

![CSV Entity Import Target](/assets/reference/edit-objects/dictionary/entities/csvImport1.png){caption}

You are presented with a large blue target to drag and drop a CSV entity file onto or to click then navigate to a CSV entity file. 
 
{% hint style='info' %}
  When using drag and drop method the target will turn green when mdEditor is ready to receive the CSV file.
{% endhint %}

If the sample CSV entity file illustrated above ("STATE") is dropped onto the target or selected for import the following entity will be STAGED FOR IMPORT in mdEditor.
 
![Entity Staged for Import](/assets/reference/edit-objects/dictionary/entities/csvImport2.png){caption}

{% hint style='info' %}
  It is important to note that the entity including its domains and attributes are not yet created at this juncture.  They are only STAGED for import. Additional information must be added and existing information reviewed prior to actual import. 
{% endhint %}

On the above import window there several things that must be completes and/or considers before clicking the <strong><span class="btn btn-info btn-xs"> <i class="fa fa-sign-in"> </i> Do Import </span> </strong> button:

1. <span class="md-element">Entity Identifier</span>  A default <span class="md-element">Entity Identifier</span> was assigned.  *[See the Entity Information Panel for more detail](../entityInfo-panel.md)*

1. <span class="md-element">Entity Code Name</span> <i class="fa fa-asterisk required" title="Required"> </i>  <span class="md-element">Entity Code Name</span> is empty and must be filled in.  *[See the Entity Information Panel for more detail](../entityInfo-panel.md)*

1. <span class="md-element">Entity Definition</span> <i class="fa fa-asterisk required" title="Required"> </i>  <span class="md-element">Entity Definition</span> is empty and must be filled in.  *[See the Entity Information Panel for more detail](../entityInfo-panel.md)*

1. The <span class="md-panel">Entity Setup</span> panel lists the attributes derived from reading the CSV file. From this panel you can change attribute names and some of the basic attribute properties and even declare a domain form the attribute's values.

   * To include the <span class="md-panel">Attribute</span> in the <span class="md-panel">Entity</span> be sure the <span class="md-element">Import</span> checkbox is checked.
    
   * In the <span class="md-element">Name</span> column you can change the <span class="md-panel">Attribute</span> name.  The CSV header column name is shown in the next column.
    
   * In the <span class="md-element">Data Type</span> column you can change the <span class="md-panel">Attribute's</span> datatype.  The datatype show was detected during mdEditor's scan of the CSV file and many cases may need to be changed.  It was just a guess!
    
   * If the values associated with this <span class="md-panel">Attribute</span> constitute a domain, place a check the <span class="md-element">Domain</span> column and one will be generated using the attribute's values. A preview of the detected domain values can be displayed by rolling the mouse over the <strong class="btn btn-info btn-xs"> <i class="fa fa-eye" title="Required"> </i> Example</strong> button.
    
   * Place a check in the <span class="md-element">Allow Nulls</span> column column if the <span class="md-panel">Attribute</span> permits null (empty) values. 

   * Place a check in the <span class="md-element">Min/Max</span> column column if ... 
