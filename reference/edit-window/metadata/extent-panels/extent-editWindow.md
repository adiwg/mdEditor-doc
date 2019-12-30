## Metadata Record -- Extent Section
---
### Extent Edit Window

![Extent Edit Window](/assets/reference/edit-objects/metadata/extent/extent-editWindow.png){caption}

* <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1   A narrative description of the <span class="md-panel">Extent</span> including its geographic, temporal, and vertical extents.  
 
* [<span class="md-panel" style="font-size: larger">Geographic Extent</span>](geographic-editWindow.md) 1{**type**: object (<span class="md-panel">Geographic Extent</span>); **default** empty}1  A geographic boundary which encompasses the resource data collection area and/or areas of interest for the resource.  The boundaries can be defined as a bounding box, points, lines, and/or complex polygons. 

* [<span class="md-panel" style="font-size: larger">Temporal Extent</span>]() 1{**type**: array (obj:<span class="md-panel">Temporal Extent</span>)}1   An array of <span class="md-panel">Temporal Extent</span> objects which define the time periods or specific time instants for which the main resource is relevant.  

  {% hint style='info' %}
 Not implemented in this release of mdEditor.
  {% endhint %} 

* [<span class="md-panel" style="font-size: larger">Vertical Extent</span>]() 1{**type**: array (obj:<span class="md-panel">Vertical Extent</span>)}1   An array of <span class="md-panel">Vertical Extent</span> objects which define the vertical span of the main resource as altitude, elevation, or depth.  
 
   {% hint style='info' %}
 Not implemented in this release of mdEditor.
   {% endhint %} 
 
{% hint style='danger' %}
  Although none of the elements are indicated required, one or more must be defined for the <span class="md-panel">Extent</span> to be valid. 
{% endhint %}
