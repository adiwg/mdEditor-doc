# Metadata Record -- Spatial Section
---

The <span class="md-section">Spatial</span> section of the <span class="md-window">Edit Window</span> is used to document the spatial parameters of the main resource.     

![Spatial Edit Window](/assets/reference/edit-objects/metadata/spatial/spatial-editWindow.png)

* <span class="md-element">Spatial Representation Type</span> 1{**type**: codelist (ISO MD_SpatialRepresentationTypeCode, ADIwg codes); **extensible**: YES; **multi-value**: YES; **default**: empty}1  The geographic format of the main resource such as grid, vector, textTable, video, etc.

* [<span class="md-panel" style="font-size: larger">Spatial Reference System</span>](referenceSystem-panel.md) 1{**type**: object (<span class="md-panel">Spatial Reference System</span>); **default** empty}1  The spatial reference system of the main source. 

* [<span class="md-panel" style="font-size: larger">Spatial Resolution</span>](spatialResolution-panel.md) 1{**type**: object (<span class="md-panel">Spatial Resolution</span>); **default** empty}1  Information about the scale of the geographic extent of the main resource. 
