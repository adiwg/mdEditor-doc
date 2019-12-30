## Metadata Record -- Taxonomy Section
---
### Add Custom Classification Hierarchy

Clicking the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add New Taxa </strong> button will add a new, top-level node to the <span class="md-panel">Classification</span> array. 

![Custom Classification Edit Window](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-classification-custom.png){caption}

* <span class="md-element">Taxonomic Level</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  Name of the taxonomic level (rank) for which the <span class="md-element">Taxonomic Name</span> is provided. Example: "Kingdom", "Division", "Phylum", "Subphylum", "SuperClass", "Class", "SubClass", "InfraClass", "Superorder", "Order", "Suborder", "Infraorder", "Superfamily", "Family", "Subfamily", "Tribe", "Subtribe", "Genus", "Species".  

* <span class="md-element">Taxonomic Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  The agreed to scientific or other official name for the taxon being described.   

* <span class="md-element">Taxonomic ID</span> 1{**type**: string; **max length**: none; **default**: empty}1  The ID assigned by the <span class="md-panel">Taxonomic System</span> to this taxon.  

* <span class="md-panel">Common Name</span> 1{**type**: array (string)}1 Specification of applicable common names. These common names may be general descriptions of a group of organisms if appropriate (e.g. insects, vertebrate, grasses, waterfowl, vascular plants, etc.). 

<strong class="btn btn-info btn-xs"> <i class="fa fa-check"> </i> OK </strong> Click 'OK' when the entry is complete to return to the <span class="md-panel">Taxonomic Collection</span> <span class="md-window">Edit Window</span>.  The first node of a new <span class="md-panel">Classification</span> hierarchy will be displayed in the <span class="md-panel">Classification</span> array panel.

---

![New High-level node for Classificaton](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-classification-custom-2.png){caption}

Once the high-level node has been added, it may be edited and extended using the buttons on the individual nodes of the hierarchy.  See [Editing the Hierarchy](classification-edit.md) for details.
