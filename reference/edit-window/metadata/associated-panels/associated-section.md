# Metadata Record -- Associated Resource Section
---

The <span class="md-section">Associated Resource</span> section of the <span class="md-window">Edit Window</span> is used to connect related resources.  For instance, multiple resources may be related through inheritance where the main resource is a product of some larger program, or was a project that yielded sub-projects the metadata author wishes to note. These, as well as other association types, can all be linked by means of the <span class="md-panel">Associated Resource</span>.   

When no <span class="md-panel">Associated Resources</span> have been defined for the <span class="md-panel">Metadata Record</span> a large blue bar is displayed on the page declaring "No Associated Resource found."  

![Associated Section with no Associated Resources Defined](/assets/reference/edit-objects/metadata/associated/associated-start.png)

<strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Associated Resource</strong> and <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Resource</strong>  To add an <span class="md-panel">Associated Resource</span> click either button, they serve the same function.  After clicking one of the buttons you will be transferred to the <span class="md-panel">Additional Resource</span> <span class="md-window">Edit Window</span> where you can complete data entry for the resource.  

![Associated Resource Edit Window](/assets/reference/edit-objects/metadata/associated/associated-editWindow.png)

<strong class="btn btn-info btn-xs"> <i class="fa fa-check"> </i> Select a Record </strong> Click this button to see a list of <span class="md-panel">Metadata Records</span> available to import as an <span class="md-panel">Associated Resource</span>.   *See ["Select a Resource"](selectResource-panel.md)* for details.

<strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to Resource List</strong> Click to return to the list of defined <span class="md-panel">Associated Resources</span>. 

---

* <span class="md-element">Association Type</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: codelist (ISO DS_AssociationTypeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  Justification for the correlation of two resources. 

* <span class="md-element">Initiative Type</span> 1{**type**: codelist (ISO DS_InitiativeTypeCode); **extensible**: YES; **multi-value**: NO; **default**: empty}1  The type of initiative under which the resource was produced - the activity that resulted in the resource. 

* <span class="md-panel" style="font-size: larger">Resource Types</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: array (obj: <span class="md-panel">Resource Type</span>)}1 Identifies the general class or kind of <span class="md-panel">Additional Document</span> being documented.  2{[See object details](#resource-type-object)}2 

* <span class="md-panel" style="font-size: larger">Remaining Panel Elements</span> 1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1 The remaining panel elements comprise the <span class="md-panel">Associated Resource Citation</span> object is a <span class="md-panel">Citation</span> which references the resource being linked with the main resource.
  
  See the [Citation Reference](../../citation/citation-section.md) for documentation on specific <span class="md-panel">Associated Resource Citation</span> panels.

---

{% include "../../../include-objects/resourceType-obj.md" %}

---