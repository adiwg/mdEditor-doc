## Dictionary Section -- Entity Section
--- 

### Attribute Information Panel

<span class="md-panel" style="font-size: larger">Attribute Information</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  The <span class="md-panel">Attribute Information</span> panel holds a collection of elements that identify and describe the entity attribute.

![Attribute Information Panel](/assets/reference/edit-objects/dictionary/attribute/attributeInfo.png){caption}

* <span class="md-element">Code Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 The code used to identify this attribute.  Most often this will be the table or spreadsheet column name.   
                                             
  {% hint style='danger' %}
  Note, this element is the same as the <span class="md-element">Name</span> element on the <span class="md-panel">Attribute</span> array panel on the <span class="md-panel">Entity</span> <span class="md-window">Edit Window</span>.
  {% endhint %}
  
* <span class="md-element">Definition</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 A succinct but comprehensive definition for the attribute.

* <span class="md-element">Data Type</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  The datatype for the attribute. 

  {% hint style='info' %}
  Names for datatypes vary widely by database management system.  The names included are the more common names employed by SQL database systems.  Use the datatype name associated with the database system that implemented the entity.  If this name is not included in the select list, you may type it in.
  {% endhint %}

* <span class="md-element">Allow Null?</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: Boolean; **default**: FALSE}1  Indicates whether null values are permitted as the attribute value.

* <span class="md-element">Common Name</span> 1{**type**: string; **max length**: none; **default**: empty}1   The name by which the <span class="md-panel">Attribute</span> is commonly referred as opposed to its code.

* <span class="md-element">Domain</span> 1{**type**: codelist (domains defined for this <span class="md-panel">Dictionary Record</span>); **extensible**: NO; **multi-value**: NO; **default**: empty}1  The <span class="md-panel">Domain</span> <span class="md-element">Code Name</span> for the dictionary domain containing the list of permissible values for this <span class="md-panel">Attribute</span>.

* <span class="md-element">Aliases</span> 1{**type**: array (string)}1  An array of strings providing alternate names by which the attribute is known.

* <span class="md-element">Units</span> 1{**type**: string; **max length**:none; **default**: empty}1  A unit-of-measure for the attribute. E.g. 'meters', 'atmospheres', 'liters'.

* <span class="md-element">Units Resolution</span> 1{**type**: real; **min**: 0.0; **max** none; **default**: empty}1  The smallest unit increment to which an attribute value is measured.

* <span class="md-element">Case Sensitive?</span> 1{**type**: Boolean; **default**: FALSE}1  Indicates if the content of the data set is encoded in case-sensitive ASCII.

* <span class="md-element">Field Width</span> 1{**type**: integer; **min**: 0; **max** none; **default**: empty}1  The number of characters in the data field.

* <span class="md-element">Missing Value</span> 1{**type**: string; **max length**:none; **default**: empty}1  The code which represents missing data.

* <span class="md-element">Minimum Value</span> 1{**type**: string; **max length**:none; **default**: empty}1  The minimum range value permissible for this attribute.  The minimum value may be either numeric or character.

* <span class="md-element">Maximum Value</span> 1{**type**: string; **max length**:none; **default**: empty}1  The maximum range value permissible for this attribute.  The maximum value may be either numeric or character.
