## Contact Record -- Address
---

### Address Array

<span class="md-panel" style="font-size: larger">Address</span> 1{**type**: array (obj: <span class="md-panel">Address</span>)}1 An array of <span class="md-panel">Address</span> objects associated with the individual or organization contact.

![Contact Address Array Panel](/assets/reference/edit-objects/contact/contact-address-1.png){caption}

Click <span class="btn-info btn-xs"> <i class="fa fa-plus"> </i>Add</span> or <span class="btn-success btn-xs"> <i class="fa fa-pencil"> </i>Edit</span> to open the <span class="md-panel">Address</span> object for edit. 

---

### Address Object

![Contact Address Panel](/assets/reference/edit-objects/contact/contact-address-2.png){caption}

* <span class="md-element">Address Type</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (ADIwg codes); **extensible**: YES; **multi-value**: YES; **default**: empty}1 The type of address, generally mailing and/or physical.  

* <span class="md-element">Street Lines</span> 1{**type**: array (string)}1 An array of address lines.  Add a new <span class="md-element">Street Line</span> for each line of the address. 

* <span class="md-element">City</span> 1{**type**: string; **max length**: none; **default**: empty}1 City Name.

* <span class="md-element">State/Province</span> 1{**type**: string; **max length**: none; **default**: empty}1 State or Province Name.

* <span class="md-element">Postal Code</span> 1{**type**: string; **max length**: none; **default**: empty}1 Postal or Zip code.

* <span class="md-element">Country</span> 1{**type**: codelist (ISO 3166-1 alpha-3); **extensible**: NO; **multi-value**: NO; **default**: empty}1 Country Name. 

  {% hint style='info' %}
  The country is selected from the list by "country name" not "code".  However, mdTranslator may convert the country name to code during writing of metadata output.  
  {% endhint %}

* <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1 Any additional detail regarding the address may be placed in the <span class="md-element">Description</span> element.
