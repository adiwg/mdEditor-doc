## Dictionary Record -- Domain Section
---

### Domain Item Array & Short Form

<span class="md-panel" style="font-size: larger">Domain Item</span> 1{**type**: array (obj: <span class="md-panel"> Domain Item</span>)}1   An array of defined <span class="md-panel">Domain Item</span> objects. 

![Domain Item Array](/assets/reference/edit-objects/dictionary/domains/domainItem-array.png){caption}

The array allows editing of the three required <span class="md-panel">Domain Item</span> elements.  Click the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More ...</strong> button to access all the <span class="md-panel">Domain Item</span> object elements.

* <span class="md-element">Name</span> <i class="fa fa-asterisk required" title="Required"> </i>  2{[See object details](#domain-item-object)}2.

* <span class="md-element">Value</span> <i class="fa fa-asterisk required" title="Required"> </i> 2{[See object details](#domain-item-object)}2.

* <span class="md-element">Definition</span> <i class="fa fa-asterisk required" title="Required"> </i> 2{[See object details](#domain-item-object)}2.

---

### Domain Item Object

![Domain Item Edit Window](/assets/reference/edit-objects/dictionary/domains/domainItem.png){caption}

* <span class="md-element">Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 A descriptive name associated with the <span class="md-panel">Domain Item</span> value.

* <span class="md-element">Value</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  The <span class="md-panel">Domain Item</span> value.  

  {% hint style='info' %}
  For the metadata, all domain values are entered as strings.  The intent of the metadata is strictly to inform.  This value in a database 'look-up' table will likely be strongly typed as required (e.g. character, integer, real, Boolean, etc.)
  {% endhint %}

* <span class="md-element">Definition</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  A brief definition of the <span class="md-panel">Domain Item</span>. 

* <span class="md-panel">Item Reference</span> 1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1 Reference to a definition for this <span class="md-panel">Domain Item</span> or to a standard which contains the definition for this domain <span class="md-panel">Domain Item</span>.

* <strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to Domain</strong> Click to return to the <span class="md-section">Domain</span> <span class="md-window">Edit Window</span>.
