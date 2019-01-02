# Contact Record -- Basic Information
---

The <span class="md-panel">Contact</span> <span class="md-window">Edit Window</span> does not have an actual "Basic Information" panel.  The elements defined on this page are the elements NOT embedded in the other panels.

![Contact Basic Information](/assets/reference/edit-objects/contact/contact-basicInfo.png){caption}

* <span class="md-element">Contact ID</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: UUID}1 A unique identifier for the contact record. 
                                             
  <strong class="btn btn-warning btn-xs"> <i class="fa fa-pencil"> </i> Edit</strong> Click 'Edit' to change the <span class="md-element">Contact ID</span>.
                                             
  {% hint style='danger' %}
  Use caution when editing the <span class="md-element">Contact ID</span>.  This ID must be unique among ALL your contact records.  If this ID was used to link with other metadata records, changing it may break the link.
  {% endhint %}
  
* <span class="md-element">Individual Name</span> or <span class="md-element">Organization Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 Name of the individual or organization.

  If the <span class="md-panel">Contact</span> is designated as "Individual" the element <span class="md-element">Individual Name</span> will appear here.  If the <span class="md-panel">Contact</span> is designated as "Organization", this element will be replaced by <span class="md-element">Organization Name</span>.  
  
  {% hint style='info' %}
  When the <span class="md-panel">Contact</span> object was first defined it was designated as either an "Individual" or "Organization" contact record.  This designation cannot be changed.  
  {% endhint %}

* <span class="md-element">Position Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 The position name or title of the individual.  

  For "Individual" contact records <span class="md-element">Position Name</span> is required when <span class="md-element">Individual Name</span> is empty.  For "Organization" contact records <span class="md-element">Position Name</span> is hidden on the <span class="md-window">Edit Window</span>.
  
* <span class="md-element">Contact Type</span> 1{**type**: codelist (ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1 A user assigned type for the contact. 

* <span class="md-element">Member of Organization</span> 1{**type**: codelist (Organization <span class="md-panel">Contact</span>); **extensible**: NO; **multi-value**: YES; **default**: empty}1 A list of "Organization" <span class="md-panel">Contacts</span> the "Individual" or "Organization" <span class="md-panel">Contact</span> record being edited is affiliated with.  

  {% hint style='info' %}
  The parent <span class="md-panel">Contact</span> of the affiliation must also be defined in mdEditor in order to be selected.
  {% endhint %}

* <span class="md-element">Contact Instructions</span> 1{**type**: string; **max length**: none; **default**: empty}1 Any supplemental instructions regarding contacting this "Individual" or "Organization" may be provided here.
