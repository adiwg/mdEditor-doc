## Dictionary Record -- CSV Import Process
---

### Prepare the Entity for Import

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
