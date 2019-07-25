## Metadata Record -- Extent Section
---
### Geographic Extent Edit Window

![Geographic Extent Edit Window](/assets/reference/edit-objects/metadata/extent/geographic-editWindow.png){caption}

* <span class="md-element">Bounding Box</span> 1{**type**: collection}1 The general geographic position of the resource defined by bounding latitudes and longitudes.  

  * <span class="md-element">North</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: real; **min**: -90.0; **max** +90.0; **default**: empty}1  Northern-most coordinate of the limit of the dataset extent or area of interest expressed in latitude, in decimal degrees.

  * <span class="md-element">South</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: real; **min**: -90.0; **max** +90.0; **default**: empty}1  Southern-most coordinate of the limit of the dataset extent or area of interest expressed in latitude, in decimal degrees.

  * <span class="md-element">East</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: real; **min**: -180.0; **max** +180.0; **default**: empty}1  Eastern-most coordinate of the limit of the dataset extent or area of interest expressed in longitude, in decimal degrees.

  * <span class="md-element">West</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: real; **min**: -180.0; **max** +180.0; **default**: empty}1  Western-most coordinate of the limit of the dataset extent or area of interest expressed in longitude, in decimal degrees.
  
  * <strong class="btn btn-primary btn-xs"> <i class="fa fa-calculator"> </i> Calculate</strong> If <span class="md-panel">Features</span> have been added to the <span class="md-panel">Geographic Extent</span> the button may be clicked to compute <span class="md-element">Bounding Box</span> values for the collection of <span class="md-panel">Features</span>. 
  
    {% hint style='info' %}
  Bounding box coordinates are not automatically recalculated when <span class="md-panel">Features</span> are added, edited, or deleted.  Click the <strong class="btn btn-primary btn-xs"> <i class="fa fa-calculator"> </i> Calculate</strong> button again after making changes to the <span class="md-panel">Feature</span> collection.
    {% endhint %}

  * <strong class="btn btn-danger btn-xs"> <i class="fa fa-trash"> </i> Clear</strong> Clear all <span class="md-element">Bounding Box</span> elements.

* <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1  A short description of the geographic areal domain of the data set. Examples include, "Manistee River watershed", "extent of 7½ minute quads containing any property belonging to Yellowstone National Park", or "ponds and reservoirs larger than 2 acres in Jefferson County, Colorado".

* <span class="md-element">Contains Data</span> 1{**type**: Boolean; **default**: TRUE}1  Indicates the <span class="md-panel">Geographic Extent</span> encompasses some or all the data for this <span class="md-panel">Extent</span>. 

* [<span class="md-panel" style="font-size: larger">Features</span>](features-editWindow.md) 1{**type**: array (obj: <span class="md-panel">Feature</span>)}1  An array of objects each describing a geographic boundary or location comprising all or a portion of the resource.  

  When no <span class="md-panel">Features</span> have been defined for the <span class="md-panel">Geographic Extent</span> a large blue bar is displayed on the page declaring "No Features to display."  Click the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> Add Features</strong> button to transfer to the <span class="md-panel">Feature</span> <span class="md-window">Edit Window</span> where you can import or manually add and edit<span class="md-panel">Features</span>. 
  
  After one or more <span class="md-panel">Features</span> have been added to the <span class="md-panel">Geographic Extent</span> a map will be displayed showing the features.  See the image below.
  
  ![Geographic Extent Edit Window with Features](/assets/reference/edit-objects/metadata/extent/geographic-editWindow-2.png){caption}

  * <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> Edit Features</strong> Click to transfer to the <span class="md-panel">Feature</span> <span class="md-window">Edit Window</span> where you can add new and edit existing <span class="md-panel">Features</span>. 
  
  * <strong class="btn btn-danger btn-xs"> <i class="fa fa-trash"> </i> Clear Features</strong> Remove all <span class="md-panel">Features</span> from the <span class="md-panel">Geographic Extent</span>. 
    