# Metadata Record -- Constraints Section
---

The <span class="md-section">Constraints</span> section of the <span class="md-window">Edit Window</span> is used to document constraints of any kind regarding the distribution and use of the main resource.  Constraints can describe copyright requirements, intellectual property, limitation of data use, security concerns, and more.   

When no <span class="md-panel">Constraints</span> have been defined for the <span class="md-panel">Metadata Record</span> the <span class="md-panel">Constraint</span> array will be empty.

![Constraints Section with no Constraints Defined](/assets/reference/edit-objects/metadata/constraint/constraint-start.png)

<strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add</strong> and <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Constraint</strong>  To add a new <span class="md-panel">Constraint</span> click either button, they serve the same function.  After clicking one of these buttons the <span class="md-panel">Constraint</span> object panel will open in isolation mode. 
  
<strong class="btn btn-info btn-xs"> <i class="fa fa-check"> </i> OK </strong> Complete data entry for the <span class="md-panel">Constraint</span> then click "OK" to save your constraint.

---

![Constraint Edit Window](/assets/reference/edit-objects/metadata/constraint/constraint-panel.png)

* <span class="md-element">Constraint Type</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: codelist (ADIwg enumerated list); **extensible**: NO; **multi-value**: NO; **default**: empty}1  The type of constraint: use, legal, security.  

  * **Use limitations** caution on the limitations of the fitness of data, findings, or metadata in various use cases.  i.e. What the data should NOT be used for.  Limitations are not legally binding and do not deal with security concerns.
  
  * **Legal constraints** enumerate any legally binding restrictions and prerequisites for accessing and using the resource or metadata including copyrights and intellectual property rights.
  
  * **Security constraints** define any handling restrictions imposed on the resource or metadata for national security or similar security concerns.

  {% hint style='tip' %}
  A <span class="md-panel">Constraint</span> can have only one <span class="md-element">Constraint Type</span>.  When the type is "use" complete <span class="md-panel">Use Limitations</span>, when "legal" complete <span class="md-panel">Legal</span>, and when "security" complete <span class="md-panel">Security</span>. 
  {% endhint %}

* [<span class="md-panel" style="font-size: larger">Use Limitations</span>](useLimitation-panel.md) 1{**type**: array (obj: <span class="md-panel">Use Limitation</span>)}1  An array of limitations or cautions regarding the fitness of this data or findings for various uses.  e.g. "Not to be used for ..."  Each limitation is a text string.

* [<span class="md-panel" style="font-size: larger">Legal</span>](legal-panel.md) 1{**type**: object (<span class="md-panel">Legal</span>); **default** empty}1  Describes legally binding constraints on the use and distribution of the main resource and its metadata.

* [<span class="md-panel" style="font-size: larger">Security</span>](security-panel.md) 1{**type**: object (<span class="md-panel">Security</span>); **default** empty}1  Handling instructions imposed on the resource or metadata for national security or similar security concerns. 

* [<span class="md-panel" style="font-size: larger">Responsible Parties</span>](responsibleParty-panel.md) 1{**type**: array (<span class="md-panel">obj: Responsible Party</span>)}1  An array of persons and/or organizations responsible for assigning and/or defining the <span class="md-panel">Constraint</span>.

* [<span class="md-panel" style="font-size: larger">Graphic or Logo</span>](graphic-panel.md) 1{**type**: array (<span class="md-panel">obj: Graphic</span>)}1  An array of file descriptions for images and logos associated with the constraint.
