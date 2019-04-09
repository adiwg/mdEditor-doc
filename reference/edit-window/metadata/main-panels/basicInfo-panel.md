## Metadata Record -- Main Section
---

### Basic Information Panel

<span class="md-panel" style="font-size: larger">Basic Information</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  The <span class="md-panel">Basic Information</span> panel holds a collection of elements that identify and describe the main resource.

![Basic Information Panel](/assets/reference/edit-objects/metadata/main/basicInfo-main.png){caption}

* <span class="md-element">Record ID</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: string; **max length**: none; **default**: UUID}1 A unique identifier (ID) for the metadata record. 

  <strong class="btn btn-warning btn-xs"> <i class="fa fa-pencil"> </i> Edit</strong> Click 'Edit' to change the <span class="md-element">Record ID</span>.

  {% hint style='danger' %}
  Use caution when editing the <span class="md-element">Record ID</span>.  This ID must be unique among ALL your metadata records.  If this ID was used to link with other metadata records, changing it may break the link.
  {% endhint %}

* <span class="md-element">Title</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 A user-provided title for the resource.  This was required when the metadata record was created but may be edited at any time.

* <span class="md-element">Status</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (ISO MD_ProgressCode, ADIwg codes); **multi-value**: YES; **extensible**: YES; **multi-value**: YES; **default**: empty}1 The current status of the main resource.

* <span class="md-element">Default Locale</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: object (<span class="md-panel">Locale</span>); **default** (eng, UTF-8, USA)}1 The default or primary language and character encoding for the main resource. 2{[See object details](#locale-object)}2 

---

{% include "../../../include-objects/locale-obj.md" %}
