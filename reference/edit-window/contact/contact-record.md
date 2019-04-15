# Reference -- Contact Records
---

In mdEditor, <span class="md-panel">Contacts</span> are edited and saved separately from <span class="md-panel">Metadata Records</span> and <span class="md-panel">Dictionaries</span>.  This normalized approach allows a <span class="md-panel">Contact</span> object's information to be used many time across a single <span class="md-panel">Metadata Record</span> or even by multiple <span class="md-panel">Metadata Records</span> without the necessity to reenter the contact's information.  Rather than entering a contact's information in a <span class="md-panel">Metadata Record</span>, mdEditor places a reference to the <span class="md-panel">Contact</span> object, most ofter as a <span class="md-panel">Responsible Party</span>.  Later, when the <span class="md-panel">Metadata Records</span> are translated into their final output format, mdTranslator will format the <span class="md-panel">Contact</span> object's information according to the selected standard's rule set.  

{% hint style='tip' %}
  With a little planning you can build a reusable library of <span class="md-panel">Contact</span> objects to use across many of your <span class="md-panel">Metadata Records</span>.
{% endhint %} 

![Contact Edit Window](/assets/reference/edit-objects/contact/contact.png){caption}

 * To open a <span class="md-panel">Contact</span> object for editing, either create a new <span class="md-panel">Contact</span> by clicking the <span class="btn btn-primary btn-xs"> <i class="fa fa-plus"> </i></span> button or open an existing <span class="md-panel">Contact</span> by clicking it's <span class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i></span> button in the <span class="md-window">Primary Sidebar</span>. 
 
   {% hint style='info' %}
 The <span class="md-panel">Contact</span>'s <span class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i></span> button does not need to be green to edit the record.  A <span class="md-panel">Contact</span> object can be edited in any state of completeness.
   {% endhint %}
   
 * The <span class="md-panel">Contact</span>'s name is displayed at the top of the <span class="md-window">Edit Window</span>.
 
 * There is a small <span class="btn btn-default btn-xs">Show</span> button in the <span class="md-window">Breadcrumb Bar</span> that will open a view with all of the <span class="md-panel">Contact</span>'s information displayed. This may be helpful when determining if you have selected the intended contact for editing or when you just want to see what information was entered for a contact.  

---

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
  
* <span class="md-element">Contact Type</span> 1{**type**: codelist (ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1 A user-assigned type for the contact. 

* <span class="md-element">Member of Organization</span> 1{**type**: codelist (Organization <span class="md-panel">Contact</span>); **extensible**: NO; **multi-value**: YES; **default**: empty}1 A list of "Organization" <span class="md-panel">Contacts</span> the "Individual" or "Organization" <span class="md-panel">Contact</span> record being edited is affiliated with.  

  {% hint style='info' %}
  The parent <span class="md-panel">Contact</span> of the affiliation must be predefined in mdEditor in order to be selected.
  {% endhint %}

* [<span class="md-panel" style="font-size: larger">Phone Numbers</span>](phones-panel.md)  1{**type**: array (obj: <span class="md-panel">phone</span>)}1  An array of <span class="md-panel">Phone</span> numbers associated with the individual or organization contact.

* [<span class="md-panel" style="font-size: larger">E-Mail Addresses</span>](email-panel.md)  1{**type**: array (string: email address)}1  An array of e-mail addresses associated with the individual or organization contact.

* [<span class="md-panel" style="font-size: larger">Addresses</span>](address-panel.md)  1{**type**: array (obj: <span class="md-panel">Address</span>)}1  An array of addresses associated with the individual or organization contact.
 
* [<span class="md-panel" style="font-size: larger">Online Resources</span>](onlineResource-panel.md)  1{**type**: array (obj: <span class="md-panel">Online Resource</span>)}1  An array of online resources associated with the individual or organization contact.

* [<span class="md-panel" style="font-size: larger">Logos</span>](logo-panel.md)  1{**type**: array (obj: <span class="md-panel">Graphic</span>)}1  An array of file descriptions for images and graphic files used as logos for the individual or organization contact.
 
* [<span class="md-panel" style="font-size: larger">Online Graphic Resource</span>](onlineGraphicResource-panel.md)  1{**type**: array (obj: <span class="md-panel">Online Graphic Resource</span>); **default**: empty}1  An array of online graphic files that describe internet links to graphic files.  

* [<span class="md-panel" style="font-size: larger">Available Times</span>](times-panel.md)  1{**type**: array (string)}1 An array of text strings that describe the best times to connect with the individual or organization contact.

* <span class="md-element">Contact Instructions</span> 1{**type**: string; **max length**: none; **default**: empty}1 Any supplemental instructions regarding contacting this "Individual" or "Organization" may be provided here.
