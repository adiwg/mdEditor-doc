# Contact Record -- Phones
---

![Contact Phone Numbers](/assets/reference/edit-objects/contact/contact-phone.png){caption}

* <span class="md-element">Name</span> 1{**type**: string; **max length**: none; **default**: empty}1 User assigned name to phone or phone's location.

* <span class="md-element">Number</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: NANP phone number; **max length**: none; **default**: empty}1 Phone number.  

  {% hint style='info' %}
  Currently the phone number control only supports the format for USA, Canada, and other NANP (North American Numbering Plan) countries.  This <span class="md-element">Number</span> must be 10 numeric characters and include an area code.  Spaces and hyphens ("-") are allowed as separators.  The area code may optionally be enclosed in parenthesis.  Other country formats are accepted but marked as invalid. 
  {% endhint %}
  
* <span class="md-element">Services</span> 1{**type**: codelist (ISO MD_TelephoneTypeCode, ADIwg codes); **extensible**: YES; **multi-value**: YES; **default**: empty}1 A list of services available at this number. 
