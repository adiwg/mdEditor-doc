## Metadata Record -- Constraint Section
---

### Security Constraint

<span class="md-panel" style="font-size: larger">Security Constraint</span> 1{**type**: collection}1  A collection of elements describing handling instructions imposed on the resource or metadata for national security or similar security concerns. 

![Security Constraint Panel](/assets/reference/edit-objects/metadata/constraint/security.png)
  
---

* <span class="md-element">Classification</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: codelist (ISO MD_ClassificationCode); **extensible**: NO; **multi-value**: NO; **default**: empty}1  Level of the security restrictions assigned to this resource or metadata.  

* <span class="md-element">Classification System Name</span> 1{**type**: string; **max length**: none; **default**: empty}1   Name of the Classification System.  

* <span class="md-element">Note</span> 1{**type**: string; **max length**: none; **default**: empty}1   Explanation for why this level of security classification was assigned to the resource or metadata.  

* <span class="md-element">Handling Description</span> 1{**type**: string; **max length**: none; **default**: empty}1   Any additional instructions for handling the resource or metadata.  
