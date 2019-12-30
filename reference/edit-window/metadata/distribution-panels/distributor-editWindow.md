## Metadata Record -- Distribution Section
---
### Distributor Edit Window

![Distributor Edit Window](/assets/reference/edit-objects/metadata/distribution/distributor-editWindow.png){caption}

* <span class="md-element">Contacts</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (Contacts loaded in browser cache); **extensible**: NO; **multi-value**: YES; **default**: empty}1 The organization and/or person(s) to contact with questions about obtaining or using the distribution.  

  {% hint style='tip' %}
This is the contact information for a single distributor.  You may include multiple contacts within a distributor's organization, or multiple means of contacting the distributor.  However, if there are multiple distributors for the distribution it is best to identify each in separate <span class="md-panel">Distributor</span> objects.
  {% endhint %}
  
* <span class="md-element">Role</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (ISO CI_RoleCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1 Identifies the function or responsibility assigned to the person(s) or organization(s). 

  {% hint style='tip' %}
The <span class="md-element">Role</span> value is generally "distributor" although other values can be chosen.  However, remember there is only one role allowed for the <span class="md-panel">Distributor</span> <span class="md-element">Contact</span>. 
  {% endhint %}
  
* [<span class="md-panel" style="font-size: larger">Transfer Option</span>](transferOption.md)  1{**type**: array (obj: <span class="md-panel">Transfer Option</span>)}1  A description of the method and media by which a resource is obtained from the distributor.

  When no <span class="md-panel">Transfer Options</span> have been defined for the <span class="md-panel">Distributor</span> a large blue bar is displayed on the page declaring "No Transfer Options found."  

  Click the <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Transfer Option</strong> button to add the initial <span class="md-panel">Transfer Option</span>.  Afterwards you will be transferred to the <span class="md-panel">Transfer Option</span> <span class="md-window">Edit Window</span> where you can complete data entry.  
  
  When one or more <span class="md-panel">Transfer Options</span> have been defined the <span class="md-panel">Transfer Option</span> array will look similar to the image below.  

  ![Distributor Edit Window with Multiple Transfer Options](/assets/reference/edit-objects/metadata/distribution/distributor-editWindow-2.png){caption}

  Click the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add</strong> button in the <span class="md-panel">Transfer Option</span> panel title bar to add the next <span class="md-panel">Transfer Option</span>. 
  
  Click the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More ...</strong> button to open the <span class="md-panel">Transfer Option</span> <span class="md-window">Edit Window</span>. 

* [<span class="md-panel" style="font-size: larger">Order Process</span>](orderProcess.md)  1{**type**: object (<span class="md-panel">Order Process</span>)}1  Provides information about how the resource may be obtained and related instructions and fee information.
