## Dictionary Record -- Entity Section
---

### Indices Array

<span class="md-panel" style="font-size: larger">Entity Indices</span> 1{**type**: array (obj: <span class="md-panel"> Entity Index</span>)}1  The panel contains a list of <span class="md-panel">Entity Index</span> objects used to define alternate keys (keys in addition to the <span class="md-element">Primary Key</span>) for the <span class="md-panel">Entity</span>.  Alternate keys are generally used to speed data retrievals and provide alternate retrieval paths in large datasets.  

  {% hint style='info' %}
  Alternate key constraints work entirely within an <span class="md-panel">Entity</span> whereas foreign key constraints rely on a reference to another (foreign) <span class="md-panel">Entity</span>.
  {% endhint %}

![Entity Indices Panel](/assets/reference/edit-objects/dictionary/entities/indices.png){caption}
  
---

###  Entity Index Object

* <span class="md-element">Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1   The code name of the <span class="md-panel">Index</span> used in the dictionary schema.

* <span class="md-element">Attributes</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (<span class="md-panel">Attributes</span> defined in the current <span class="md-panel">Entity</span>); **extensible**: YES; **multi-value**: YES; **default**: empty}1 Choose the attribute (or collection of attributes) from the current entity that will act as the alternate key. 

* <span class="md-element">Duplicates</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: Boolean; **default**: FALSE}1 TRUE if duplicates are permitted in the index.  FALSE if duplicates are not permitted. 
