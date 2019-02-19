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

  * **Use limitations** caution on the limitations of the fitness of data, findings, or metadata in various use cases.  i.e. What the data should NOT be used for.  Limitations are not legally binding nor deal with security concerns.
  
  * **Legal constraints** enumerate any legally binding restrictions and prerequisites for accessing and using the resource or metadata including copyrights and intellectual property rights.
  
  * **Security constraints** define any handling restrictions imposed on the resource or metadata for national security or similar security concerns.

---

 * [<span class="md-panel" style="font-size: larger">Use Limitations</span>](useLimitation-panel.md)

 * [<span class="md-panel" style="font-size: larger">Legal</span>](legal-panel.md)

 * [<span class="md-panel" style="font-size: larger">Security</span>](security-panel.md)

 * [<span class="md-panel" style="font-size: larger">Responsible Parties</span>](responsibleParty-panel.md)

 * [<span class="md-panel" style="font-size: larger">Graphic or Logo</span>](graphic-panel.md)

---