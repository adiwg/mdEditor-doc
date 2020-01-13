### Online Graphic Resource Object

![Online Graphic Resource](/assets/reference/edit-objects/metadata/main/onlineGraphicResource.png)

* <span class="md-element">Name</span> 1{**type**: string; **max length**: none; **default**: empty}1 The name of the online graphic resource. 

* <span class="md-element">URI</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: URI; **default**: empty}1 - The internet location (address) for online access to the graphic resource, using the URI format - a.k.a URL. 

  <span class="btn btn-info btn-xs"> <i class="fa fa-bullseye"> </i> Click to Select or Drop Image</span> Use this drop target to drop local graphics and logos that are less than 50K Bytes in size.  The graphic will be converted to a 'data:image/...' URI and placed into the <span class="md-element">URI</span> element.  These graphics will remain embedded in the mdJson file and do not need an additional internet accessible URI to access the graphic.
  
  For graphics larger than 50K Bytes an internet accessible file is required.  Place the URI to the graphic file in the <span class="md-element">URI</span> element.  mdEditor will then access the graphic file and build a thumbprint image for the <span class="md-window">Edit Window</span> page.  
    
    {% hint style='info' %}
 The thumbprint image is not saved with the mdJson or mdEditor files.  The thumbprint is rebuilt each time the mdJson file is edited.
    {% endhint %}

* <span class="md-element">Protocol</span> 1{**type**: string; **max length**: none; **default**: empty}1 The online connection protocol used to access the graphic resource.  e.g. ftp, http, https, etc.

* <span class="md-element">Description</span> 1{**type**: string; **max length**: 500 characters; **default**: empty}1 A text description with additional details of what the graphic resource is or describes. 

* <span class="md-element">Function</span> 1{**type**: codelist (ISO CI_OnLineFunctionCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1 A code declaring the intended function of the graphic resource. 
