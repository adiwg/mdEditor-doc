## Metadata Record -- Lineage Section
---

### Source Array

![Source Array](/assets/reference/edit-objects/metadata/lineage/source-array.png) 

 * <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1  A brief description of the source data.  After entering a <span class="md-element">Description</span>, click <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More...</strong> to access the remaining <span class="md-panel">Source</span> elements.  See [Sources](source-panel.md) for documentation on the specific <span class="md-panel">Source</span> elements.
 
---
 
### Source Object

![Associated Resource Edit Window](/assets/reference/edit-objects/metadata/associated/associated-editWindow.png)

* <span class="md-element">Association Type</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: codelist (ISO DS_AssociationTypeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  Justification for the correlation of two resources. 

* <span class="md-element">Initiative Type</span> 1{**type**: codelist (ISO DS_InitiativeTypeCode); **extensible**: YES; **multi-value**: NO; **default**: empty}1  The type of initiative under which the resource was produced - the activity that resulted in the resource. 

* <span class="md-panel" style="font-size: larger">Resource Types</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: array (obj: <span class="md-panel">Resource Type</span>)}1 Identifies the general class or kind of <span class="md-panel">Additional Document</span> being documented. 

* <span class="md-panel" style="font-size: larger">Associated Resource Citation</span> 1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1 The <span class="md-panel">Associated Resource Citation</span> object is a <span class="md-panel">Citation</span> which references the resource being linked with the main resource.
  
  See the [Citation Reference](../../../../citation/citation-section.md) for documentation on specific <span class="md-panel">Additional Document</span> panels.

---

{% include "../../../../include-objects/resourceType-obj.md" %}

---
