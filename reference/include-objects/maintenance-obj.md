![Maintenance Panel](/assets/reference/edit-objects/metadata/main/maintenance.png)

* <span class="md-element">Frequency</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (ISO MD_MaintenanceFrequencyCode); **multi-value**: NO; **extensible**: YES; **multi-value**: NO; **default**: empty}1  The frequency period for maintenance of this resource.  

* <span class="md-element">Dates</span> 1{**type**: array (obj: <span class="md-panel">Date</span>); **default**: empty}1 - Dates and datetimes related to maintenance of this resource. 2{[See object details](#date-object)}2 
      
* <span class="md-element">Contacts</span> 1{**type**: array (obj: <span class="md-panel">Responsible Party</span>); **default**: empty}1 - Persons and organizations to contact for information regarding maintenance of this resource. 2{[See object details](#responsible-party-object-contacts)}2
      
* <span class="md-element">Notes</span> 1{**type**: array (string); **max length**: none; **default**: empty}1 - An array of notes or comments to provide additional information about this maintenance cycle.  Each note is a character string.

* <span class="md-element">Scope</span> 1{**type**: codelist (ISO MD_ScopeCode, ADIwg codes); **extensible**: YES; **multi-value**: YES; **default**: empty}1 - A code to describe the class or context for which the maintenance cycle applies.

---

{% include "../include-objects/date-obj.md" %}

---

### Responsible Party Object (Contacts)

{% include "../include-objects/responsibleParty-obj.md" %}
  
  
