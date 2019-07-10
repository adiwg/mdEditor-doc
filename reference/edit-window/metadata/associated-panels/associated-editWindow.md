## Metadata Record -- Associated Resource Section
---
### Edit Window

![Associated Resource Edit Window](/assets/reference/edit-objects/metadata/associated/associated-editWindow.png){caption}

<strong class="btn btn-info btn-xs"> <i class="fa fa-check"> </i> Select a Record </strong> Click this button to see a list of <span class="md-panel">Metadata Records</span> available to import as an <span class="md-panel">Associated Resource</span>.   *See ["Select a Resource"](selectResource-panel.md)* for details.

<strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to Resource List</strong> Click to return to the list of defined <span class="md-panel">Associated Resources</span>. 

* <span class="md-element">Association Type</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: codelist (ISO DS_AssociationTypeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  Justification for the correlation of two resources. 

* <span class="md-element">Initiative Type</span> 1{**type**: codelist (ISO DS_InitiativeTypeCode); **extensible**: YES; **multi-value**: NO; **default**: empty}1  The type of initiative under which the resource was produced - the activity that resulted in the resource. 

* <span class="md-panel" style="font-size: larger">Resource Types</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: array (obj: <span class="md-panel">Resource Type</span>)}1 Identifies the general class or kind of <span class="md-panel">Additional Document</span> being documented.  2{[See object details](#resource-type-object)}2 

* <span class="md-panel" style="font-size: larger">Remaining Panel Elements</span> 1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1 The remaining panel elements comprise the <span class="md-panel">Associated Resource</span> citation.  This <span class="md-panel">Citation</span> object refers to the resource being associated with the main resource.
  
  See the [Citation Reference](../../citation/citation-section.md) for documentation on specific <span class="md-panel">Associated Resource Citation</span> panels.

---

{% include "../../../include-objects/resourceType-obj.md" %}
