# Metadata Record -- Taxonomy Section
---

The <span class="md-section">Taxonomy</span> section of the <span class="md-window">Edit Window</span> is used to define taxonomic information for the resource.  A <span class="md-panel"> Taxonomic Collection </span> in mdEditor is described using a hierarchy or 'Classification' consisting of a discretionary number of levels from Kingdom to Subspecies.  The mdEditor's implementation also allows multiple entities to be ascribed to each level of the hierarchy which effectively supports branching the hierarchy.  The <span class="md-panel"> Taxonomic Collection </span> further includes information about observers, specimens, and how the species identification was made. 

{% hint style='tip' %}
  Although the <span class="md-section">Taxonomy</span> section was originally developed to define biological hierarchies, it may also be used to define hierarchies in other disciplines.  
{% endhint %}

{% hint style='tip' %}
  While not strictly a hierarchy, taxonomy could be used to document layered systems or stratigraphic resource.
{% endhint %}

When no <span class="md-panel">Taxonomic Collections</span> have been defined for the <span class="md-panel">Metadata Record</span> a large blue bar is displayed on the page declaring "No taxonomic collections found."  

![Taxonomy Section with no Taxonomic Collections Defined](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-start.png) {caption}

To add the first taxonomic description to the <span class="md-panel"> Metadata Record </span> click either <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Collection </strong> button.  mdEditor will navigate to the <span class="md-panel"> Taxonomic Collection </span> <span class="md-window"> Edit Window </span>.

---

![Taxonomy Collection Edit Window](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-editWindow.png){caption}

<strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add New Taxa </strong> Click to add a new custom <span class="md-panel">Classification</span> to the <span class="md-panel">Taxonomic Collection</span>.  
  
<strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Taxa from ITIS</strong> Click to find and import a <span class="md-panel">Classification</span> from the U.S. Geological Survey's Integrated Taxonomic Information System (USGS ITIS) to the <span class="md-panel">Taxonomic Collection</span>.  
   
<strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to Resource List</strong> Click to return to the list of defined <span class="md-panel">Taxonomic Classifications</span> for the current <span class="md-panel"> Metadata Record </span>. 

---

* <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Taxonomic System </strong> <i class="fa fa-asterisk required" title="Required"> </i> Click this button to add a new <span class="md-panel">Taxonomic System</span> to the <span class="md-panel">Taxonomic Classification</span>.   *See ["Taxonomic System"](taxonomy-system.md)* for details.

* [<span class="md-panel" style="font-size: larger">Classification</span>](taxonomy-classification.md) 1{**type**: array (obj: <span class="md-panel">Classification</span>)}1 <i class="fa fa-asterisk required" title="Required">  </i> An array of taxonomic hierarchies that describe the levels (taxon rank), scientific names (latin name), and common names for species referenced in the metadata resource. 

* <span class="md-panel" style="font-size: larger">Observers</span> 1{**type**: array (obj: <span class="md-panel">Responsible Party</span>)}1 Each <span class="md-panel">Observer</span> identifies a person or organization involved in making the determination of species.  2{See below for details}2

* <span class="md-element">General Scope</span> 1{**type**: string; **max length**: none; **default**: empty}1   A description of the range of taxa addressed in dataset or collection.  For example "All vascular plants were identifier to family or species." 

* <span class="md-element">Modification Procedure</span> 1{**type**: string; **max length**: none; **default**: empty}1   Description of the methods used for taxonomic identification. Could include specimen processing, comparison with museum materials, keys, and key characters, chemical or genetic analyses, etc. 

* <span class="md-element">Identification Completeness</span> 1{**type**: string; **max length**: none; **default**: empty}1   Information concerning the proportions and treatment of unidentified materials (i.e. materials sent to experts, and not yet determined); estimates of the importance, and identities of misidentifications, uncertain determinations, synonyms or other incorrect usages; taxa not well treated or requiring further work; and expertise of field workers. 

* [<span class="md-panel" style="font-size: larger">Voucher</span>](taxonomy-voucher.md) 1{**type**: array (obj: <span class="md-panel">Voucher</span>)}1  An array of specimen vouchers identifying the specimens used in species determination and where they are being preserved. 

---

### Responsible Party Object (Observer)

![Taxonomy Observer Array](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-observer-array.png){caption}

{% include "../../../include-objects/responsibleParty-obj.md" %}
