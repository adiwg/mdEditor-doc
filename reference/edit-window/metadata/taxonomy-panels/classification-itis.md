## Metadata Record -- Taxonomy Section
---
### Import Classifications from ITIS

After clicking the <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Taxa from ITIS</strong> button the Integrated Taxonomic Information System (ITIS) search window will display.

![Searching ITIS](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-itis-search.png){caption} 

* <span class="md-element">Search Value</span>  1{**type**: string; **max length**: none; **default**: empty}1   Word or phrase to search for in the ITIS database.  Typical searches are for scientific names, common names, or an ITIS Taxonomic Serial Number (TSN).

* <span class="md-element">Kingdom (optional)</span>  1{**type**: codelist (ITIS Kingdom); **extensible**: NO; **multi-value**: NO; **default**: empty}1  A search may optionally be narrowed by selecting an ITIS Kingdom as a filter.  

Enter a search value and click <strong class="btn btn-primary btn-xs"> <i class="fa fa-search"> </i> Search</strong>

---

![Select ITIS Items](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-itis-select.png){caption}

ITIS will return a list of all taxa that meet the search criteria.  Generally there will be more items returned than desired.  Select the taxon(taxa) to import by clicking the <strong class="btn btn-success btn-xs"> Add </strong> button next to the desired taxon which will move it to the "Taxa Selected" column.

---

![Import ITIS Items](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-itis-import.png){caption}

When ready to import the taxa moved to the "Taxa Selected" column, click the <strong class="btn btn-primary btn-xs"> Import Taxa </strong> button and the taxonomic hierarchy(ies) will be imported directly into mdEditor. 

<strong class="btn btn-primary btn-xs"> Import Taxa </strong> The 'Import Taxa' button will import all the Taxon in the "Taxa Selected" list.  If a particular taxon has been previously imported it will not be re-imported.  

A <span class="md-panel">Taxonomic System</span> object for ITIS will also be created and inserted in the <span class="md-panel">Taxonomy Collection</span> if one does not already exist.  Only one ITIS <span class="md-panel">Taxonomic System</span> will be added regardless of how many taxa are imported or how many times <strong class="btn btn-primary btn-xs"> Import Taxa </strong> is clicked.

<strong class="btn btn-danger btn-xs"> Remove </strong>  Click 'Remove' to remove a taxon from the "Taxa Selected" list and exclude it from import.  Note that <strong class="btn btn-danger btn-xs"> Remove </strong> will not remove a previously imported taxon.  To removed an unwanted taxonomic hierarchy see [Editing the Classification Hierarchy](classification-edit.md).

<strong class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Back to List </strong> To view the added ITIS taxa, return to the <span class="md-panel">Taxonomic Collection</span> <span class="md-window">Edit Window</span> by clicking the 'Back to List' button.  

---

![ITIS Hierarchy](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-itis-panel.png){caption}

After adding the ITIS taxon a <span class="md-panel">Taxonomic System</span> reference for ITIS was added to the <span class="md-panel">Taxonomic System</span> array. 

And a new taxonomic hierarchy was added to the <span class="md-panel">Classifications</span> array for the imported taxon.

---

When a second or subsequent taxon from ITIS is imported, mdEditor will attempt to merge the hierarchies.  In doing so the common taxa layers are not repeated.  In the example below "Canada Goose", was merged with the "Sandhill Crane" <span class="md-panel">Classification</span> shown above.

![ITIS Hierarchy](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-itis-panel-2.png){caption}
