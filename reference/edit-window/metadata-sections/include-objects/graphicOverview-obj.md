#### Graphic Overview Object

![Graphic Overview](/assets/reference/edit-objects/main/graphicOverview.png)

* <span class="md-element">Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 Name of the file containing the overview graphic.  

* <span class="md-element">File Type</span> 1{**type**: string; **max length**: none; **default**: empty}1 MIME type (Multipurpose Internet Mail Extension) of the overview graphic.  e.g. jpeg, gif, pdf, png, bmp, etc.
  
* <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty; **max length**: 500 characters}1 A short description of the overview graphic.
 
* <span class="md-element">Online Graphic Resource</span> 1{**type**: array (obj: <span class="md-panel">Online Graphic Resource</span>); **default**: empty}1 <span class="md-panel"> Online Graphic Resource</span> objects that define internet links to the <span class="md-panel">Graphic Overview</span> file. 2{[See object details](../main-panels/onlineGraphicResource-panel.md)}2
