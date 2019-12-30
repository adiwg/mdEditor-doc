## Metadata Record -- Taxonomy Section
---
### Editing the Classification Hierarchy

Editing a <span class="md-panel">Classification</span> (taxonomic hierarchy) is the same whether it was created manually or imported from ITIS.  Editing is permitted at each node (line) of the hierarchy.  To enable the edit buttons for a particular node simply roll the cursor over that line and the buttons will illuminate.  

![Classification Hierarchy Edit Buttons](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-edit-buttons.png){caption}

<strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> Edit </strong>  Clicking the 'Edit' button will navigate to the same window used to <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add New Taxa </strong> where you may change the <span class="md-element">Taxonomic Level</span>, <span class="md-element">Taxonomic Name</span>, <span class="md-element">Taxonomic ID</span>, and <span class="md-element">Common Name</span> for the node.  After editing, click <strong class="btn btn-info btn-xs"> <i class="fa fa-check"> </i> OK </strong> to save your changes or click anywhere off the edit window to return without saving any changes you may have made.  

<strong class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Delete </strong>  Click 'Delete' to remove the node from the hierarchy.  

{% hint style='danger' %}
  When a level is deleted all lower nodes (child nodes) will also be deleted.
{% endhint %}

{% hint style='tip' %}
  To delete an entire <span class="md-panel">Classification</span> hierarchy simply delete the highest node.
{% endhint %}

<strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add Child </strong>  Clicking 'Add Child' will branch the current node.  In this way many species can be represented in the same hierarchy without recreating the entire structure.
