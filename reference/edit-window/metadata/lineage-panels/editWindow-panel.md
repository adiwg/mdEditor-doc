## Metadata Record -- Lineage Section
---

### Edit Window

![Resource Lineage Edit Window](/assets/reference/edit-objects/metadata/lineage/lineage-editWindow.png)

* <span class="md-element">Statement</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  A description of the resource being described along with a general statement of the overall actions taken to verify, transform, filter, and integrate the resource.

* <span class="md-panel" style="font-size: larger">Process Step</span> 1{**type**: array (obj: <span class="md-panel">Process Step</span>)}1 An array of brief statements describing individual, non-trivial processes or methodologies taken in developing the resource. 2{[See object details](#process-step-array)}2 

* <span class="md-panel" style="font-size: larger">Source</span> 1{**type**: array (obj: <span class="md-panel">Source</span>)}1 An array of information about source datasets used in creating the resource. 2{[See object details](#source-array)}2 

* <span class="md-panel" style="font-size: larger">Citation</span> 1{**type**: array (obj: <span class="md-panel"> Citation </span>)}1  An array of citations that describe the lineage process. 2{[See object details](#citation-array)}2 

* <span class="md-element">Scope</span> 1{**type**: codelist (ISO MD_ScopeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  The type of resource this lineage describes. 

---

### Process Step Array

![Process Step Array](/assets/reference/edit-objects/metadata/lineage/processStep-array.png) 

 * <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1  A brief description of the process step.  After entering a <span class="md-element">Description</span>, click <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More...</strong> to access the remaining <span class="md-panel">Process Step</span> elements.  See [Process Steps](processStep-panel.md) for documentation on the specific <span class="md-panel">Process Step</span> elements.
 
---

### Source Array

![Source Array](/assets/reference/edit-objects/metadata/lineage/source-array.png) 

 * <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1  A brief description of the source data.  After entering a <span class="md-element">Description</span>, click <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More...</strong> to access the remaining <span class="md-panel">Source</span> elements.  See [Sources](source-panel.md) for documentation on the specific <span class="md-panel">Source</span> elements.
 
---
 
### Citation Array

 * <span class="md-panel" style="font-size: larger"> Citation</span>  See the [Citation Reference](../../citation/citation-section.md) for documentation on specific <span class="md-panel">Citation</span> panels.

---
