![Online Resource](/assets/reference/edit-objects/metadata/onlineResource.png)

* <span class="md-element">Name</span> {**type**: string; **default**: nil} - The name of the online resource. 

* <span class="md-element">URI</span> <i class="fa fa-asterisk required" title="Required"></i> {**type**: URI; **default**: nil} - The internet location (address) for online access to the resource using the URI format - a.k.a URL. 

* <span class="md-element">Protocol</span> **type**: string; **default**: nil} - The online connection protocol used to access the resource.  e.g. ftp, http, https, etc.

* <span class="md-element">Description</span> {**type**: string; **default**: nil; **max length**: 500 characters} - A text description with additional details of what the resource is or describes. 

* <span class="md-element">Function</span> {**type**: codelist (ISO CI_OnLineFunctionCode, ADIwg codes); **extensible**: YES; **default**: nil} - A code declaring the intended function or the resource. 
