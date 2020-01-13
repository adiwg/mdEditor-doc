### Identifier Object

![Identifier Edit Panel](/assets/reference/edit-objects/identifier/identifier-panel.png)

* <span class="md-element">Identifier</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: string; **max length**: none; **default**: empty}1 A cataloged and managed name or code for the resource. 

* <span class="md-element">Namespace</span> 1{**type**: string; **max length**: none; **default**: empty}1 A string which unambiguously defines the namespace to which the identifier belongs.

* <span class="md-element">Version</span> 1{**type**: string; **max length**: none; **default**: empty}1 The version number of the identifier.

* <span class="md-element">Description</span> 1{**type**: **max length**: none; string; **default**: empty}1 A description of the meaning of the identifier.  

* <span class="md-panel" style="font-size: larger">Authority</span> 1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1   A reference to information about the identifier. An <span class="md-panel">Authority</span> is an abbreviated version of the full <span class="md-panel">Citation</span> object. 2{[See object details](#citation-object)}2 
