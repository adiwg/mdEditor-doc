## Metadata Record -- Taxonomy Section
---
### Taxonomic System

The <span class="md-panel">Taxonomic System</span> is a reference to the system of taxa used by the <span class="md-panel">Classification</span> object(s).  

![Taxonomy System Panel with no Systems defined](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-systems.png) {caption}

<strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Taxonomic System</strong> When no <span class="md-panel">Taxonomic Systems</span> have been defined for the <span class="md-panel">Collection</span> a large blue box displaying an <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Taxonomic System</strong> button will occupy the <span class="md-panel">Taxonomic Systems</span> object array.  Click this button to add the initial <span class="md-panel">Taxonomic System</span> reference for the <span class="md-panel">Collection</span>.  

{% hint style='info' %}
  When creating or using an unpublished taxonomic <span class="md-panel">Collection</span> you still need to define a <span class="md-panel">Taxonomic System</span> reference for your <span class="md-panel">Classification</span>.  Technically, only the minimal element, <span class="md-element">Title</span>, needs to be entered.  However, additional detail is encouraged.
{% endhint %}

---

![Taxonomy System Array](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-systems-array.png) {caption}

* <span class="md-element">Title</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1   Title (or name) of the <span class="md-panel">Taxonomic System</span> being referenced.  

  {% hint style='tip' %}
 The <span class="md-element">Title</span> element is the <span class="md-panel">Taxonomic System</span>'s <span class="md-panel">Citation</span> element <span class="md-element">Title</span>.  It may also be edited within the <span class="md-panel">Citation</span> after clicking the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More</strong> button.
  {% endhint %}

* <span class="md-element">Modifications</span>  1{**type**: string; **max length**: none; **default**: empty}1   A description of any modifications or exceptions made to the classification system as described in the <span class="md-panel">Taxonomic System</span> reference.  

  {% hint style='tip' %}
 The <span class="md-element">Modifications</span> element may be edited both from the <span class="md-panel">Taxonomic Systems</span> panel array and <span class="md-window">Edit Window</span>
  {% endhint %}
  
<strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> Edit</strong>  Click this button to expand the <span class="md-panel">Classification</span> object making all elements available for edit.  

---

![Taxonomy System Edit Window](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-systems-panel.png) {caption}

* <span class="md-element">Modifications</span>  1{**type**: string; **max length**: none; **default**: empty}1   A description of any modifications or exceptions made to the classification system as described in the <span class="md-panel">Taxonomic System</span> reference.  

* The remaining elements are all <span class="md-panel">Citation</span> elements for the <span class="md-panel">Taxonomic System</span>.  See [Citation Section](../../citation/citation-section.md) for editing instructions.
