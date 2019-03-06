## Metadata Record -- Constraint Section
---

### Legal Constraint

<span class="md-panel" style="font-size: larger">Legal Constraint</span> 1{**type**: collection}1  A collection of elements describing legally binding constraints on the use and distribution of the main resource and its metadata. 

{% hint style='info' %}
  While none of the elements on this panel are required, at least one must be filled in when the <span class="md-element">Constraint Type</span> is "legal". 
{% endhint %}

![Legal Constraint Panel](/assets/reference/edit-objects/metadata/constraint/legal.png)
  
---

* <span class="md-element">Access Constraint</span> 1{**type**: codelist (ISO MD_RestrictionCode, ADIwg codes); **extensible**: NO; **multi-value**: YES; **default**: empty}1   These are access constraints applied to assure the protection of privacy of individuals or intellectual property as well as any restrictions or limitations on obtaining the resource or metadata. 

* <span class="md-element">Use Constraint</span> 1{**type**: codelist (ISO MD_RestrictionCode, ADIwg codes); **extensible**: NO; **multi-value**: YES; **default**: empty}1   These are use constraints applied to assure the protection or privacy of individuals or intellectual property as well as any restrictions or limitations on using the resource or metadata.  

* <span class="md-panel">Other Constraints</span> 1{**type**: array (string)}1  Any other restrictions and legal prerequisites for accessing and using the resource or metadata.  Each limitation is a text string.
