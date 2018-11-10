![Maintenance Panel](/assets/reference/edit-objects/maintenance-panel.png)

* <span class="md-element">Frequency</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: string; **default**: nil} - The frequency period for maintenance of this resource.  

* <span class="md-element">Dates</span> {**type**: array (<span class="md-panel">Date</span>); **default**: empty} - Dates and datetimes related to maintenance of this resource.
  
  <strong class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Delete</strong> Click 'Delete' to remove the <span class="md-panel">Date</span> object from the array.
    
  #### Date Object
  
  {% include "../include-objects/date-obj.md" %}
  ---

* <span class="md-element">Contacts</span> {**type**: array (<span class="md-panel">Responsible Party</span>); **default**: empty} - Persons and organizations to contact for information regarding maintenance of this resource.
    
  <strong class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Delete</strong> Click 'Delete' to remove the <span class="md-panel">Contact</span> object from the array.
  
  #### Responsible Party Object
  
  {% include "../include-objects/responsibleParty-obj.md" %}
  ---
  
* <span class="md-element">Notes</span> {**type**: array; **default**: empty} - An array of notes or comments to provide additional information about this maintenance cycle.  Each note is a character string.

* <span class="md-element">Scope</span> {**type**: codelist (ISO MD_ScopeCode, ADIwg codes); **extensible**: YES; **multi-value**: YES; **default**: nil} - A code to describe the class or context for which the maintenance cycle applies.
