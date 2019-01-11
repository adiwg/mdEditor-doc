## Dictionary Section -- Entity Section
--- 

### Attribute Array

The <span class="md-panel">Attributes</span> array panel displays a list of defined <span class="md-panel">Entity</span> <span class="md-panel">Attribute</span> objects and provides the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add</strong> button for creating new ones.  The array allows editing of the four required <span class="md-panel">Attribute</span> object elements.  Click the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More ...</strong> button to access all the <span class="md-panel">Attribute</span> object elements.

![Attributes Array](/assets/reference/edit-objects/dictionary/entities/attribute-array.png){caption}

* <span class="md-element">Code Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 The code name for the <span class="md-panel">Attribute</span> used in the dictionary schema.

* <span class="md-element">Data Type</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1 The data type for this attribute (e.g. character, integer, real).

* <span class="md-element">Definition</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 A short narrative definition of the attribute.

* <span class="md-element">Allow Null?</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: Boolean; **default**: TRUE}1 TRUE if this attribute can be left empty.  FALSE if a value for the attribute is required. 

See the [<span class="md-panel">Attributes</span> <span class="md-window">Edit Window</span>](../attribute-panels/attribute-section.md) for full documentation of the <span class="md-panel">Attribute</span> object.

---