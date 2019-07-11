## Metadata Record -- Distribution Section
---
### Distribution Edit Window

![Distribution Edit Window](/assets/reference/edit-objects/metadata/distribution/distribution-editWindow.png){caption}

* <span class="md-element">Description</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1   A description of the resource being distributed.  This may be the main resource, a intermediate or derived product, raw data, a supporting document, or a zipped package of resources. 
 
* <span class="md-element">Liability Statement</span> 1{**type**: string; **max length**: none; **default**: empty}1   A statement of the liability assumed or exempted by the resource owner.
 
* [<span class="md-panel" style="font-size: larger">Distributor</span>](distributor-editWindow.md) 1{**type**: array (obj: <span class="md-panel"> Distributor</span>)}1  An array of <span class="md-panel">Distributor</span> objects.  Each distributor is person or organization authorized to distribute copies of the distribution package.  Details of the distribution package and method(s) of delivery are maintained within the <span class="md-panel">Distributor</span> object.

  When no <span class="md-panel">Distributors</span> have been defined for the <span class="md-panel">Distribution</span> a large blue bar is displayed on the page declaring "No Distributors found." Click the <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Distributor</strong> button to add the initial <span class="md-panel">Distributor</span>.  Afterwards you will be transferred to the <span class="md-panel">Distributor</span> <span class="md-window">Edit Window</span> where you can complete data entry for the distributor.  
  
  When one or more <span class="md-panel">Distributors</span> have been defined the <span class="md-panel">Distribution</span> <span class="md-window">Edit Window</span> will look similar to the image below.  
  
  ![Distribution Edit Window with Multiple Distributors Defined](/assets/reference/edit-objects/metadata/distribution/distribution-editWindow-2.png){caption}
  
  Click the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add</strong> button in the <span class="md-panel">Distributor</span> panel title bar to add the next <span class="md-panel">Distributor</span> or click the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> Edit</strong> button to open an existing <span class="md-panel">Distributor</span>'s <span class="md-window">Edit Window</span>.
