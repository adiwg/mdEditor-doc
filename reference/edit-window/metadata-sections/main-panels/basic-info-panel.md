## Metadata Record -- Main Section
### Basic Information
DO NOT EDIT

<span class="md-panel" style="font-size: larger">Basic Information</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: collection} The <span class="md-panel">Basic Information</span> panel holds a collection of elements that identify and describe the main resource.

![Basic Information Panel](/assets/reference/edit-objects/basic-info-main.png)

* <span class="md-element">Record ID</span> <i class="fa fa-asterisk required" title="Required"></i> {**type**: string; **default**: UUID} - A unique identifier for the metadata record. 
* <span class="md-element">Title</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: string; **default**: nil} - A user provided title for the resource.  This was required when the metadata record was created but may be edited at any time.
* <span class="md-element">Status</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: codelist (ISO MD_ProgressCode, ADIwg codes); **multi-value**: YES; **default**: nil} - The current status of the main resource.
* <span class="md-element">Default Local</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: object ([<span class="md-panel">Default Locale</span>](locale-panel.md))} - The default or primary language and character encoding for the main resource. 

{% hint style='danger' %}
  Use caution when editing the <span class="md-element">Record ID</span>.  This ID must be unique among ALL your metadata records.  If this ID was used to link with other metadata records, changing it may break the link.
{% endhint %}

---
