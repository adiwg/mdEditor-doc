## Dictionary Record -- CSV Import Process
---

### Prepare the Entity for Import

![Entity Staged for Import](/assets/reference/edit-objects/dictionary/entities/csvImport2.png){caption}

On the above import window several items need to be completed and/or considered before clicking the <strong><span class="btn btn-info btn-xs"> <i class="fa fa-sign-in"> </i> Do Import </span> </strong> button in the <span class="md-window">Secondary Sidebar</span>.

  {% hint style='info' %}
  Any items not completed here may be edited later using the mdEditor <span class="md-panel">Entity</span>, <span class="md-panel">Attribute</span>, and <span class="md-panel">Domain</span> edit windows.
  {% endhint %}

1. <span class="md-element">Entity Identifier</span>  A default <span class="md-element">Entity Identifier</span> was assigned.  *[See the Entity Information Panel for more detail](../entityInfo-panel.md)*

1. <span class="md-element">Entity Code Name</span> <i class="fa fa-asterisk required" title="Required"> </i>  <span class="md-element">Entity Code Name</span> is empty and must be filled in.  *[See the Entity Information Panel for more detail](../entityInfo-panel.md)*

1. <span class="md-element">Entity Definition</span> <i class="fa fa-asterisk required" title="Required"> </i>  <span class="md-element">Entity Definition</span> is empty and must be filled in.  *[See the Entity Information Panel for more detail](../entityInfo-panel.md)*

1. The <span class="md-panel">Entity Setup</span> panel lists all the attributes derived from reading the CSV file. From this panel you can change attribute names and some of the basic attribute properties and even declare a domain be created from an attribute's values.

   * To include the <span class="md-panel">Attribute</span> in the <span class="md-panel">Entity</span> be sure the <span class="md-element">Import</span> checkbox is checked.  Likewise, uncheck the <span class="md-element">Import</span> checkbox to exclude the <span class="md-panel">Attribute</span> from the <span class="md-panel">Entity</span>.
    
   * In the <span class="md-element">Name</span> column you can change the <span class="md-panel">Attribute</span> name.  The original CSV header column name is shown in the next column wrapped in parenthesis.
    
   * While reading the CSV file, mdEditor attempted to identify the datatype of <span class="md-panel">Attributes</span> and placed its best guess in the <span class="md-element">Data Type</span> column of the <span class="md-panel">Setup</span> panel. Review mdEditor's decision and change it if necessary.  It was just a guess!
    
   * If the values associated with an <span class="md-panel">Attribute</span> constitute a domain, place a check in the <span class="md-element">Domain</span> element checkbox and a new <span class="md-panel">Domain</span> will be generated using the attribute's values. A list of the unique domain values detected by mdEditor can be previewed by rolling the mouse over the <strong class="btn btn-info btn-xs"> <i class="fa fa-eye" title="Required"> </i> Example</strong> button.
    
   * Place a check in the <span class="md-element">Allow Nulls</span> checkbox if the <span class="md-panel">Attribute</span> is permitted to have null (empty) values. 

   * Place a check in the <span class="md-element">Min/Max</span> checkbox if the <span class="md-panel">Attribute</span>'s value is to be restricted by these bounds.  The minimum and maximum values shown will be transferred to <span class="md-element">Minimum Value</span> and <span class="md-element">Maximum Value</span> elements of the <span class="md-panel">Attribute</span> *[See the Attribute Information Panel for more detail](../../attribute-panels/attributeInfo-panel.md)*. 
   
![Entity Ready for Import](/assets/reference/edit-objects/dictionary/entities/csvImport3.png){caption}
