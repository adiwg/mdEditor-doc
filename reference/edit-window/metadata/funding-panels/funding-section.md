# Metadata Record -- Funding Section
---

The <span class="md-section">Funding</span> section collects information about funding the development and/or maintenance of the main resource.  

In mdEditor individual funding allocations for a resource are grouped into funding periods.  After defining the boundaries of a funding period the individual allocations are added to the period.

When no <span class="md-panel">Funding Periods</span> have been defined for the resource a large blue bar is displayed on the page declaring "No Funding Periods found."  

![Funding Section with no Funding Periods Defined](/assets/reference/edit-objects/metadata/funding/funding-start.png)

To add the first funding period to the <span class="md-panel"> Metadata Record </span> click either <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Funding Period </strong> button.  mdEditor will then navigate to the <span class="md-panel"> Funding Period</span> <span class="md-window"> Edit Window</span> as shown below.

---

![Funding Period Edit Window](/assets/reference/edit-objects/metadata/funding/funding-editWindow.png)

* <span class="md-panel">Allocation</span> 1{**type**: array (obj: <span class="md-panel">Allocation</span>)}1  An array of <span class="md-panel">Allocation</span> objects documenting individual contributions of funds made available for development and/or maintenance of the resource during the period.  
 
  Click either the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add Allocation</strong> button or the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add </strong> button to insert a new <span class="md-panel">Allocation</span> object and navigate to the <span class="md-panel">Allocation</span> <span class="md-window">Edit Window</span>.  

* <span class="md-panel">Time Period</span> 1{**type**: object (<span class="md-panel">Time Period</span>); **default** empty}1  The beginning and ending dates for the funding period.  2{[See object details](#time-period)}2

* <span class="md-element">Description</span>  1{**type**: string; **max length**: none; **default**: empty}1   A description of the funding period and significant goals and accomplishments of the period.

---

### Time Period

{% include "../../../include-objects/timePeriod-obj.md" %}
