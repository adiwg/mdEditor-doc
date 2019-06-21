# Metadata Record -- Taxonomy Section
---

The <span class="md-section">Taxonomy</span> section of the <span class="md-window">Edit Window</span> is used to define taxonomic information for the resource.  The taxonomy is described in a hierarchy to any number of desired levels from Kingdom to Subspecies.  The mdEditor implementation allows multiple entities to be defined at each hierarchy level.  Additionally, branching is permitted at any level of the hierarchy. 

{% hint style='tip' %}
  Although the <span class="md-section">Taxonomy</span> section was developed to define biological hierarchies it may also be used to define stratigraphic hierarchies for geology or archaeology, temporal periods, or other hierarchies that may describe the resource.
{% endhint %}

When no <span class="md-panel">Taxonomic Collections</span> have been defined for the <span class="md-panel">Metadata Record</span> a large blue bar is displayed on the page declaring "No taxonomic collections found."  

![Taxonomy Section with no Taxonomic Collections Defined](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-start.png) {caption}

<strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Collection</strong> Click either button to add a <span class="md-panel">Taxonomic Collection</span>.  

---

![Taxonomy Collection Edit Window](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-editWindow.png){caption}

<strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add New Taxa </strong> Click to add a new custom <span class="md-panel">Classification</span> to the <span class="md-panel">Taxonomic Collection</span>.  
  
<strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Taxa from ITIS</strong> Click to find and import a <span class="md-panel">Classification</span> from Integrated Taxonomic Information System (USGS ITIS) to the <span class="md-panel">Taxonomic Collection</span>.  
   
<strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to Resource List</strong> Click to return to the list of defined <span class="md-panel">Taxonomic Classifications</span>. 

---

* <strong class="btn btn-info btn-xs"> <i class="fa fa-check"> </i> Add Taxonomic System </strong> <i class="fa fa-asterisk required" title="Required"> </i> Click this button to add a new <span class="md-panel">Taxonomic System</span> to the <span class="md-panel">Taxonomic Classification</span>.   *See ["Taxonomic System"](taxonomy-system.md)* for details.

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
