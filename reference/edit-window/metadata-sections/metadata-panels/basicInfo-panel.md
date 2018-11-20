## Metadata Record -- Metadata Section
### Basic Information
---

<span class="md-panel" style="font-size: larger">Basic Information</span> {**type**: collection} - The <span class="md-panel">Basic Information</span> panel holds a collection of elements that describe the metadata for this metadata record. 

![Basic Information Panel](/assets/reference/edit-objects/metadata/basicInfo-metadata.png)

* <span class="md-element">Metadata Status</span> {**type**: codelist (ISO MD_ProgressCode, ADIwg codes); **multi-value**: YES; **default**: empty} - The current status of the metadata record.

* <span class="md-element">Dates</span> {**type**: array (<span class="md-panel">Date</span>); **default**: empty} - Dates and datetimes related to creation and status of this metadata record.
  
  <strong class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Delete</strong> Click 'Delete' to remove the <span class="md-panel">Date</span> object from the array.
    
  #### Date Object
  
  {% include "../include-objects/date-obj.md" %}
  ---

---
