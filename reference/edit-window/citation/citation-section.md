# Reference -- Citation Section
---

The <span class="md-section">Citation</span> <span class="md-window">Edit Window</span> is accessed from many locations throughout mdEditor.  This is because a typical metadata record will reference many different resources.  For example, these resources might be of earlier or referenced works, data domains, or taxonomic systems in addition to a required main resource for the metadata record.  Each of these resources is represented by a separate <span class="md-panel">Citation</span> object each having identical structure and complement of elements.  

How you actually arrive at the <span class="md-section">Citation</span> <span class="md-window">Edit Window</span> will vary, but the mdEditor elements and rules outlined in this reference section will apply in all situations. 

![Graphic Array](/assets/reference/edit-objects/citation/citation-editWindow.png)

{% hint style='info' %}
  If you clicked <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i>Edit</strong> to gain access to the <span class="md-panel">Citation</span> object there will be a <strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to ...</strong> button in the <span class="md-window">Secondary Sidebar</span>.  Click this button to end editing of the <span class="md-panel">Citation</span> and return to the mdEditor section you were on before entering the <span class="md-section">Citation</span> <span class="md-window">Edit Window</span>.
{% endhint %} 

 * [<span class="md-panel" style="font-size: larger">Basic Information</span>](basicInfo-panel.md)  <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  A collection of elements that describe the citation.

 * [<span class="md-panel" style="font-size: larger">Responsible Party</span>](responsibleParty-panel.md)  1{**type**: array (obj: <span class="md-panel"> Responsible Party</span>)}1 Identification of, and means of communication with, person(s) and organization(s) associated with the cited resource.

 * [<span class="md-panel" style="font-size: larger">Online Resource</span>](onlineResource-panel.md)  1{**type**: array (obj: <span class="md-panel">Online Resource</span>)}1 An array of links to online information about the cited reference.

 * [<span class="md-panel" style="font-size: larger">Identifier</span>](identifier-panel.md)  1{**type**: array (obj: <span class="md-panel">Identifier</span>)}1  An array of identifiers for the cited resource.  

 * [<span class="md-panel" style="font-size: larger">Series](series-panel.md)  1{**type**: object (<span class="md-panel">Series</span>); **default**: empty}1 Information about the series, publication, or aggregate resource to which a resource belongs.

 * [<span class="md-panel" style="font-size: larger">Other Details</span>](otherDetails-panel.md)  1{**type**: array (string); **max length**: none; **default**: empty}1  An array of additional details required to complete the citation that are not recorded elsewhere. 

 * [<span class="md-panel" style="font-size: larger">Graphic</span>](graphic-panel.md)  1{**type**: array (obj: <span class="md-panel">Graphic</span>)}1  An array of file descriptions for images, maps, flow charts, models, logos, etc. associated with the citation.
 
 * [<span class="md-panel" style="font-size: larger">Online Graphic Resource</span>](onlineGraphicResource-panel.md) 1{**type**: array (obj: <span class="md-panel">Online Graphic Resource</span>); **default**: empty}1 An array of <span class="md-panel">Online Graphic Resource</span> objects that describe internet links to graphic files. 
