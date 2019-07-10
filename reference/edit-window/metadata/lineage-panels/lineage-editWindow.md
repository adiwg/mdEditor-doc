## Metadata Record -- Lineage Section
---
### Edit Window

![Lineage Edit Window](/assets/reference/edit-objects/metadata/lineage/lineage-editWindow.png){caption}

<strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to Lineage List</strong> Click to return to the list of defined <span class="md-panel">Lineages</span>. 

* <span class="md-element">Statement</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  A description of the resource being described along with a general statement of the overall actions taken to verify, transform, filter, and integrate the resource.

* [<span class="md-panel" style="font-size: larger">Process Steps</span>](processStep/processStep-panel.md) 1{**type**: array (obj: <span class="md-panel">Process Step</span>)}1 An array of brief statements describing individual, non-trivial processes or methodologies taken in developing the resource. 

* [<span class="md-panel" style="font-size: larger">Sources</span>](source/source-panel.md) 1{**type**: array (obj: <span class="md-panel">Source</span>)}1 An array of information about source datasets used in creating the resource.

* [<span class="md-panel" style="font-size: larger">Citations</span>](citation-panel.md) 1{**type**: array (obj: <span class="md-panel"> Citation </span>)}1  An array of citations that describe the lineage process. 

* <span class="md-element">Scope</span> 1{**type**: codelist (ISO MD_ScopeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  The type of resource this lineage describes. 
