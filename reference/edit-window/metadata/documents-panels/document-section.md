# Metadata Record -- Additional Documents Section
---

The <span class="md-section">Documents</span> section of the <span class="md-window">Edit Window</span> supports references to documents relevant to the main resource.  These might include documents such as fact-sheets, data catalog pages, award documents, proposals, informational websites, or referenced research.  

When no <span class="md-panel">Additional Documents</span> have been defined for the <span class="md-panel">Metadata Record</span> a large blue bar is displayed on the page declaring "No Additional Documents found."  

![Documents Section with no Additional Documents Defined](/assets/reference/edit-objects/metadata/documents/document-start.png){caption}

<strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Additional Document</strong> and <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Document</strong>  To add an <span class="md-panel">Additional Document</span> click either button, they serve the same function.  

---

After clicking one of the buttons you will be transferred to the <span class="md-panel">Additional Document</span> <span class="md-window">Edit Window</span> where you can complete data entry for the reference.  

![Additional Documents Edit Window](/assets/reference/edit-objects/metadata/documents/document-editWindow.png){caption}

The <span class="md-panel">Additional Document</span> object is basically a <span class="md-panel">Resource Type</span> array concatenated to a full <span class="md-panel">Citation</span> object.  In other words, the <span class="md-panel">Additional Document</span> is a citation to some external document that is qualified by one or more <span class="md-panel">Resource Types</span>.  

<strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to Document List</strong> Click to return to the list of defined <span class="md-panel">Additional Documents</span>. 

* <span class="md-panel" style="font-size: larger">Resource Types</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: array (obj: <span class="md-panel">Resource Type</span>)}1 Identifies the general class or kind of <span class="md-panel">Additional Document</span> being described.  2{[See object details](#resource-type-object)}2 

* <span class="md-panel" style="font-size: larger">Remaining Panel Elements</span> 1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1 The remaining panel elements comprise the <span class="md-panel">Additional Document</span> citation.  This <span class="md-panel">Citation</span> object references the external document being linked with the main resource.
  
  See the [Citation Reference](../../citation/citation-section.md) for documentation on specific <span class="md-panel">Additional Document Citation</span> panels.

---

{% include "../../../include-objects/resourceType-obj.md" %}
