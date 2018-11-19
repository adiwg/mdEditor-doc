## Metadata Record -- Citation Section
### Basic Information
---

<span class="md-panel" style="font-size: larger">Basic Information</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: collection} - The <span class="md-panel">Basic Information</span> panel holds a collection of elements that describe the citation. 

![Basic Information Panel](/assets/reference/edit-objects/citation/basicInfo-citation.png)

* <span class="md-element">Title</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: string; **default**: nil} - A user provided title for the resource.  This was required when the metadata record was created but may be edited at any time.

* <span class="md-element">Alternate Titles</span> {**type**: array (string); **default**: empty} - Other titles, alias, by which the resource may be known.

* <span class="md-element">Dates</span> {**type**: array (<span class="md-panel">Date</span>); **default**: empty} - Dates and datetimes related to creation and status of this metadata record.
  
  <strong class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Delete</strong> Click 'Delete' to remove the <span class="md-panel">Date</span> object from the array.
    
  #### Date Object
  
  {% include "../include-objects/date-obj.md" %}
  ---

* <span class="md-element">Edition</span> {**type**: string; **default**: nil} - Version identifier for the resource.

* <span class="md-element">Presentation Form</span> {**type**: codelist (ISO CI_PresentationFormCode, ADIwg codes); **multi-value**: YES; **extensible**: YES; **default**: nil} - The form that the resource is presented, such as: digital map, digital document, etc.

---
