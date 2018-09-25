## Resource Types
### Metadata Record -- Main Section
DO NOT EDIT

<span class="md-panel" style="font-size: larger">Resource Types</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: array} Identifies the general class or kind of the main resource for this metadata record. An initial resource type was required when the metadata record was created.  The <span class="md-panel">Resource Type</span> may be changed and other resource types added.

![Resource Types Panel](/assets/reference/edit-objects/resource-type.png)
* <span class="md-element">Type</span> <i class="fa fa-asterisk required" title="Required"></i> {**type**: codelist (ISO MD_ScopeCode, ADIwg codes, user provided); **multi-value**: NO; **default**: nil} - Identifies the type of resource(s), such as dataset, study, publication, project, etc.  
* <span class="md-element">Name</span> {**type**: string; **default**: nil} - A user provided name for the resource.  This may be helpful particularly when multiple resource types are identified.
---
