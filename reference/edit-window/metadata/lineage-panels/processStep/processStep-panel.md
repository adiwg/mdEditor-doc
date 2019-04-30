## Metadata Record -- Lineage Section
---

### Process Step Array

![Process Step Array](/assets/reference/edit-objects/metadata/lineage/processStep-array.png) 

 * <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1  A brief description of the process step.  After entering a <span class="md-element">Description</span>, click <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More...</strong> to access the remaining <span class="md-panel">Process Step</span> elements. 
 
---

### Process Step Object

<span class="md-panel" style="font-size: larger">Process Step</span> 1{**type**: object (<span class="md-panel">Process Step</span>); **default** empty}1   The panel collects the elements of the <span class="md-panel">Process Step</span> object.  Each <span class="md-panel">Process Step</span> object identifies and describes a single, non-trivial step in the evolution of developing the resource. 

![Lineage Process Step Panel](/assets/reference/edit-objects/metadata/lineage/processStep-panel.png)

* <span class="md-element">Step ID</span> 1{**type**: string; **max length**: none; **default**: empty}1  A alphanumeric string uniquely identifying the <span class="md-panel">Process Step</span>.  

  {% hint style='tip' %}
  It is recommended to use <span class="md-element">Step IDs</span> that communicate the order in which the individual steps were applied.
  {% endhint %}

* <span class="md-element">Description</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: string; **max length**: none; **default**: empty}1  A brief description of the process step.  
 
  {% hint style='info' %}
  The <span class="md-element">Description</span> element is the same "Description" element available on the *[Lineage Edit Window](../lineage-section.md)* and likely was entered in a preceding step.  The <span class="md-element">Description</span> element may be edited from either <span class="md-window">Edit Window</span>
  {% endhint %} 

* [<span class="md-panel" style="font-size: larger">Step Sources</span>](stepSource-panel.md) 1{**type**: array (<span class="md-panel">obj: String</span>)}1  An array listing <span class="md-panel">Source</span> data or other resources serving as input to the <span class="md-panel">Process Step</span>.

* [<span class="md-panel" style="font-size: larger">Step Products</span>](stepProduct-panel.md) 1{**type**: array (<span class="md-panel">obj: String</span>)}1  An array listing <span class="md-panel">Source</span> data or other resources produced by the <span class="md-panel">Process Step</span>. 

  {% hint style='info' %}
  Source and product resources are both documented as <span class="md-panel">Source</span>.  Simply, a product of one process step may be the source of the next process step. 
  {% endhint %}

* [<span class="md-panel" style="font-size: larger">Step Processor</span>](stepProcessor-panel.md) 1{**type**: array (<span class="md-panel">obj: Responsible Party</span>)}1  An array persons and/or organizations involved in executing the <span class="md-panel">Process Step</span>. 

* [<span class="md-panel" style="font-size: larger">Step Reference</span>](stepCitation-panel.md) 1{**type**: array (<span class="md-panel">obj: Citation</span>)}1  An array of citations for the resources used in the <span class="md-panel">Process Step</span>. 

* [<span class="md-panel" style="font-size: larger">Time Period</span>](stepTime-panel.md) 1{**type**: object (<span class="md-panel">Time Period</span>); **default** empty}1  The time period over which the <span class="md-panel">Process Step</span> was performed. 

* <span class="md-element">Scope</span> 1{**type**: codelist (ISO MD_ScopeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  The type of resource this <span class="md-panel">Process Step</span> describes. 
