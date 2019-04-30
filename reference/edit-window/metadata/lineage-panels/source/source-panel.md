## Metadata Record -- Lineage Section
---

### Source Array

![Source Array](/assets/reference/edit-objects/metadata/lineage/source-array.png) 

 * <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1  A brief description of the source data.  After entering a <span class="md-element">Description</span>, click <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More...</strong> to access the remaining <span class="md-panel">Source</span> elements.  
 
---
 
### Source Object

![Source Edit Window](/assets/reference/edit-objects/metadata/lineage/source-panel.png)

* <span class="md-element">Source ID</span> 1{**type**: string; **max length**: none; **default**: UUID}1  An alphanumeric string uniquely identifying the <span class="md-panel">Source</span>.  

* <span class="md-element">Description</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: string; **max length**: none; **default**: empty}1  A brief description of the <span class="md-panel">Source</span>.  
 
  {% hint style='info' %}
  The <span class="md-element">Description</span> element is the same "Description" element available on the *[Lineage Edit Window](../lineage-section.md)* and likely was entered in a preceding step.  The <span class="md-element">Description</span> element may be edited from either <span class="md-window">Edit Window</span>
  {% endhint %} 

* <span class="md-element">Scope</span> 1{**type**: codelist (ISO MD_ScopeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  The type of resource that most closely defines this <span class="md-panel">Source</span>. 


* [<span class="md-panel" style="font-size: larger">Source Citation</span>](sourceCitation-panel.md) 1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1   A reference to information about the source data or resource.

* [<span class="md-panel" style="font-size: larger">Metadata Citation</span>](metadataCitation-panel.md) 1{**type**: array (<span class="md-panel">obj: Citation</span>)}1  An array of <span class="md-panel">Citations</span> providing references to the <span class="md-panel">Source</span>.

* [<span class="md-panel" style="font-size: larger">Spatial Reference System</span>](referenceSystem-panel.md) 1{**type**: object (<span class="md-panel">Spatial Reference System</span>); **default** empty}1  The spatial reference system used by the source. 

* [<span class="md-panel" style="font-size: larger">Spatial Resolution</span>](spatialResolution-panel.md) 1{**type**: object (<span class="md-panel">Spatial Resolution</span>); **default** empty}1  Information about the geographic scale of the source. 
