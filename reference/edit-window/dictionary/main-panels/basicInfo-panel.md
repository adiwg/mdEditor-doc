## Dictionary Record -- Main Section
---

### Basic Information Panel

<span class="md-panel" style="font-size: larger">Basic Information</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  The <span class="md-panel">Basic Information</span> panel holds a collection of elements that identify and describe the dictionary.

![Dictionary Basic Information Panel](/assets/reference/edit-objects/dictionary/main/basicInfo-main.png){caption}

* <span class="md-element">Title</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 A user-provided title for the resource.  This was required when the dictionary record was created but may be edited at any time.

* <span class="md-element">Subject</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (ISO MD_ScopeCode, ADIwg codes); **extensible**: YES; **multi-value**: YES; **default**: empty}1  One or more codes that describe the scope or content of the information in the dictionary.

* <span class="md-entity">Responsible Party</span> 1{**type**: object (<span class="md-panel">responsibleParty</span>); **default** empty}1 The person or organization having primary responsibility for the intellectual content and structure of this dictionary. 2{[See object details](#responsible-party-object)}2 

* <span class="md-element">Description</span> 1{**type**: markdown text; **default**: empty; **max length**: unlimited}1 A free text description of the contents of the data dictionary.  See *[Markdown Control](../../controls/markdown-control.md)*.

* <span class="md-element">Dictionary Included?</span> 1{**type**: Boolean; **default**: FALSE}1 TRUE is the dictionary included with the resource materials.  FALSE if the dictionary is unavailable or available via another link or resource.

* <span class="md-element">Functional Language</span> 1{**type**: string; **max length**: none; **default**: empty}1 Formal functional language used in writing the dictionary schema. 

----

### Responsible Party Object 

{% include "../../../include-objects/responsibleParty-obj.md" %}
