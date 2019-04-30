# Metadata Record -- Main Section
---

The <span class="md-section">Main</span> section of the <span class="md-window">Edit Window</span> collects general information about the main resource.

![Main Edit Window](/assets/reference/edit-objects/metadata/main/main-editWindow.png){caption}


 * [<span class="md-panel" style="font-size: larger">Basic Information</span>](basicInfo-panel.md) <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  The <span class="md-panel">Basic Information</span> panel holds a collection of elements that identify and describe the main resource.

 * [<span class="md-panel" style="font-size: larger">Resource Types</span>](resourceType-panel.md)  <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: array (obj: <span class="md-panel">Resource Type</span>)}1 Identifies the general class or kind for the main resource of this metadata record. 

 * [<span class="md-panel" style="font-size: larger">Points of Contact</span>](poc-panel.md) <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: array (obj: <span class="md-panel">Responsible Party</span>)}1  The <span class="md-panel">Responsible Parties</span> identify persons and organizations to contact regarding the main resource. 

 * [<span class="md-panel" style="font-size: larger">Citation</span>](citation-panel.md)  <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1  The <span class="md-panel">Citation</span> for the main resource. 

 * [<span class="md-panel" style="font-size: larger">Description</span>](description-panel.md)  <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1 <span class="md-panel">Description</span> is a collection of independent elements that hold various text descriptions of the main resource. 

 * [<span class="md-panel" style="font-size: larger">Time Period</span>](timePeriod-panel.md)  1{**type**: object (<span class="md-panel">Time Period</span>)}1 The <span class="md-panel">Time Period</span> describes a period of time over which the resource is relevant.  

 * [<span class="md-panel" style="font-size: larger">Maintenance</span>](maintenance-panel.md)  1{**type**: array (obj: <span class="md-panel">Maintenance</span>)}1 An array of <span class="md-panel">Maintenance</span> objects describing one or more maintenance schedules for the resource.

 * [<span class="md-panel" style="font-size: larger">Graphic Overview</span>](graphicOverview-panel.md)  1{**type**: array (obj: <span class="md-panel"> Graphic</span>)}1 An array of file descriptions for images, maps, flow charts, models, logos, etc. that help illustrate the resource.
 
 * [<span class="md-panel" style="font-size: larger">Online Graphic Resource</span>](onlineGraphicResource-panel.md)  1{**type**: array (obj: <span class="md-panel">Online Graphic Resource</span>); **default**: empty}1 An array of <span class="md-panel">Online Graphic Resource</span> objects that describe internet links to graphic files. 

 * [<span class="md-panel" style="font-size: larger">Credits</span>](credits-panel.md)  1{**type**: array (string)}1 An array of additional persons and organizations that contributed to the resource. 
