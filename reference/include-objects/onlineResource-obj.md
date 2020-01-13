![Online Resource](/assets/reference/edit-objects/metadata/metadata/onlineResource.png)

* <span class="md-element">Name</span> 1{**type**: string; **max length**: none; **default**: empty}1 The name of the online resource. 

* <span class="md-element">URI</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: URI; **default**: empty}1 The internet location (address) for online access to the resource using the URI format - a.k.a URL. 

* <span class="md-element">Protocol</span> 1{**type**: string; **max length**: none; **default**: empty}1 The online connection protocol used to access the resource.  e.g. ftp, http, https, etc.

* <span class="md-element">Description</span> 1{**type**: string; **max length**: 500 characters; **default**: empty}1 A text description with additional details of what the resource is or describes. 

* <span class="md-element">Function</span> 1{**type**: codelist (ISO CI_OnLineFunctionCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1 - A code declaring the intended function of the resource. 
