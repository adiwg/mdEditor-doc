## Citation Section -- Basic Information
---

### Basic Information Panel

<span class="md-panel" style="font-size: larger">Basic Information</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1 The <span class="md-panel">Basic Information</span> panel holds a collection of elements that describe the citation. 

![Basic Information Panel](/assets/reference/edit-objects/citation/basicInfo-citation.png)

* <span class="md-element">Title</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 A user-provided title for the resource. 

* <span class="md-element">Alternate Titles</span> 1{**type**: array (string); **default**: empty}1 Other titles, or aliases, by which the resource may be known.

* <span class="md-element">Dates</span> 1{**type**: array (obj: <span class="md-panel">Date</span>); **default**: empty}1 Dates and datetimes related to the creation and status of the resource referenced by this <span class="md-panel">Citation</span>. 2{[See object details](#date-object)}2 
      
* <span class="md-element">Edition</span> 1{**type**: string; **max length**: none; **default**: empty}1 Version identifier for the resource.

* <span class="md-element">Presentation Form</span> 1{**type**: codelist (ISO CI_PresentationFormCode, ADIwg codes); **multi-value**: YES; **extensible**: YES; **multi-value**: YES; **default**: empty}1 The form that the resource is presented in, such as: digital map, digital document, etc.

---

{% include "../../include-objects/date-obj.md" %}
