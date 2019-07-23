# Metadata Record -- Extent Section
---

The <span class="md-section">Extent</span> section of the <span class="md-window">Edit Window</span> is used to define geographic, temporal, and vertical extents for the main resource.  The <span class="md-panel">Geographic Extent</span> sets spatial boundaries which encompass data collection and/or areas of interest for the main resource.  The boundaries can be defined as a bounding box, points, lines, or complex polygons.  <span class="md-panel">Temporal Extent</span> set time periods or specific instants for which the main resource is relevant.  <span class="md-panel">Vertical Extents</span> define the vertical span of the main resource as altitude, elevation, or depth.

When no <span class="md-panel">Extents</span> have been defined for the <span class="md-panel">Metadata Record</span> a large blue bar is displayed on the page declaring "No Extents found."  

{% hint style='info' %}
  Note only geographic extents are implemented in this release of mdEditor.  Temporal and vertical extents are coming soon.
{% endhint %}

![Extent Section with no Extents Defined](/assets/reference/edit-objects/metadata/extent/extent-start.png)

Click either <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Extent</strong> button to add the initial <span class="md-panel">Extent</span> to the <span class="md-panel">Metadata Record</span>.  Afterwards you will be transferred to the <span class="md-panel">Extent</span> <span class="md-window">Edit Window</span> where you can complete data entry for the extent.  

When one or more <span class="md-panel">Extents</span> have been defined the <span class="md-section">Extent</span> window will look similar to the image below.  

![Extent Section with one Extent Defined](/assets/reference/edit-objects/metadata/extent/extent-start-2.png)

{% hint style='info' %}
  The <span class="md-panel">Extent</span> <span class="md-window">Edit Window</span> opens with one empty <span class="md-panel">Geographic Extent</span> initiated.  Multiple <span class="md-panel">Geographic Extents</span> are permitted in mdJSON, however only one <span class="md-panel">Geographic Extents</span> is supported by mdEditor at this time.  To include multiple <span class="md-panel">Geographic Extents</span> in the <span class="md-panel">Extent</span> you will need to generate the mdJSON manually.
{% endhint %}