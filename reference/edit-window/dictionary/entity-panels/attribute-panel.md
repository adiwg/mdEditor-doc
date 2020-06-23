## Dictionary Section -- Entity Section
--- 

### Attribute Array

<span class="md-panel" style="font-size: larger">Attributes</span> 1{**type**: array (obj: <span class="md-panel">Attribute</span>)}1  The array panel displays a list of the defined <span class="md-panel">Entity</span> <span class="md-panel">Attribute</span> objects and provides an <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add</strong> button for creating additional <span class="md-panel">Attributes</span>.  The array allows editing of the four required <span class="md-panel">Attribute</span> object elements. The message icons at the end of each <span class="md-panel">Attribute</span> object will provide users with alerts for required fields for the each <span class="md-panel">Attribute</span> object, and if the <span class="md-panel">Attribute</span> object has an associated <span class="md-panel">Domain</span>. Click the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More ...</strong> button to access the full set of <span class="md-panel">Attribute</span> elements.

![Attributes Array](/assets/reference/edit-objects/dictionary/entities/attribute-array.png){caption}

---

### Attribute Object (partial)

* <span class="md-element">Code Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty;**required**:TRUE}1 The code name of the <span class="md-panel">Attribute</span> used in the dictionary schema.

* <span class="md-element">Data Type</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty;**required**:TRUE}1 The data type for this attribute (e.g. character, integer, real).

* <span class="md-element">Definition</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty;**required**:TRUE}1 A short narrative definition of the attribute.

* <span class="md-element">Allow Null?</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: Boolean; **default**: TRUE;**required**:TRUE}1 TRUE if this attribute can be left empty.  FALSE if a value for the attribute is required. 

See the [<span class="md-panel">Attributes</span> <span class="md-window">Edit Window</span>](../attribute-panels/attribute-section.md) for full documentation of the <span class="md-panel">Attribute</span> object.
