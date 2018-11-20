![Online Graphic Resource](/assets/reference/edit-objects/main/onlineGraphicResource.png)

* <span class="md-element">Name</span> {**type**: string; **default**: empty} - The name of the online graphic resource. 

* <span class="md-element">URI</span> <i class="fa fa-asterisk required" title="Required"></i> {**type**: URI; **default**: empty} - The internet location (address) for online access to the graphic resource using the URI format - a.k.a URL. 

  * <span class="btn btn-info btn-xs"> <i class="fa fa-bullseye"> </i> Click to Select or Drop Image</span> Use this drop target to drop local graphics and logos that are less than 50K Bytes in size.  The graphic will be converted to a 'data:image/...' URI and placed into the <span class="md-element">URI</span> element.  These graphics will remain embedded in the mdJson file and do not need an additional internet accessible URI to access the graphic.
  
    For graphics larger that 50K Bytes an internet accessible file is required.  Place the URI to the graphic file in the <span class="md-element">URI</span> element.  mdEditor will then access the graphic file and build thumbprint image for the <span class="md-window">Edit Window</span> page.  
    
    {% hint style='info' %}
 The thumbprint image is not saved with the mdJson or mdEditor files.  The thumbprint is rebuilt each time the mdJson file is edited.
    {% endhint %}

* <span class="md-element">Protocol</span> **type**: string; **default**: empty} - The online connection protocol used to access the graphic resource.  e.g. ftp, http, https, etc.

* <span class="md-element">Description</span> {**type**: string; **default**: empty; **max length**: 500 characters} - A text description with additional details of what the graphic resource is or describes. 

* <span class="md-element">Function</span> {**type**: codelist (ISO CI_OnLineFunctionCode, ADIwg codes); **extensible**: YES; **default**: empty} - A code declaring the intended function or the graphic resource. 
