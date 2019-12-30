## Metadata Record -- Keyword Section
---
### Custom Keyword Lists

When the keywords you need are not found in one of the predefined keyword thesauri you may build your own <span class="md-panel">Keyword</span> list using mdEditor's "Custom Thesaurus" page.  With custom thesauri you can site established and standardized keyword lists not included in mdEditor's predefined list or create new lists with your own keywords.   

{% hint style='tip' %}
  Since mdEditor allows more than one custom thesaurus, keywords can be organized into groups by common topic or theme.  Each group can then be entered as a separate custom <span class="md-panel">Keyword</span> list.  This will help make the lists more manageable. 
{% endhint %}

{% hint style='info' %}
  A keyword may appear in more than one list without causing any complications.
{% endhint %}

The left side of the <span class="md-window">Custom Thesaurus Edit Window</span> contains element that define the keyword thesaurus.  The right side provides for entry and maintenance of the keywords.  

![Custom Keyword List Edit Window](/assets/reference/edit-objects/metadata/keyword/keyword-custom.png){caption}

---

### Custom Keyword Thesaurus

{% hint style='info' %}
  The <span class="md-panel">Keyword</span> thesaurus is a <span class="md-panel">Citation</span> object.  All <span class="md-panel">Keyword</span> thesaurus elements except <span class="md-element">Type</span> belong to this <span class="md-panel">Citation</span>.  

  All of the <span class="md-panel">Citation</span> object's elements are supported by mdJSON and mdTranslator for a thesaurus citation, however only the subset listed below are supported by mdEditor at this time.  
  
  A complete definition for the <span class="md-panel">Citation</span> object may be found at [Citation](../../citation/citation-section.md).  
{% endhint %}

* <span class="md-element">Title</span> <i class="fa fa-asterisk required" title="Required"> </i>  1{**type**: string; **max length**: none; **default**: empty}1  A name for the custom <span class="md-panel">Keyword</span> list.  

  {% hint style='tip' %}
  Custom <span class="md-panel">Keyword</span> lists may share the same <span class="md-element">Title</span>, however this is not best practice.  Try to give each custom list a unique <span class="md-element">Title</span>.
  {% endhint %}

* <span class="md-element">Date</span>  1{**type**: date, datetime (ISO 8601); **default**: empty}1  A date or datetime associated with the <span class="md-panel">Keyword</span> list.  

* <span class="md-element">Date Type</span> 1{**type**: codelist (ISO CI_DateTypeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: empty}1  Type of date.  

* <span class="md-element">Type</span>  1{**type**: codelist (ISO MD_KeywordTypeCode, ADIwg codes); **extensible**: YES; **multi-value**: NO; **default**: theme}1   A code or concept that defines the subject matter used to group similar keywords.  

* <span class="md-element">Edition</span> 1{**type**: string; **max length**: none; **default**: empty}1  A version identifier for the <span class="md-panel">Keyword</span> list.  

* <span class="md-element">URL</span> 1{**type**: string; **max length**: none; **default**: empty}1  This entry provides a link to any online information realted to the <span class="md-panel">Keyword</span> list. The valie is placed in the <span class="md-element">URI</span> element of the <span class="md-panel">Online Resource</span> object impedded in the thesaurus <span class="md-panel">Citation</span> object.   

---

### Custom Keyword List

When a custom <span class="md-panel">Keyword</span> list is first created or the list has no keywords assigned, the phrase "Add some keywords" will appear at the top of the list.

* <strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Keywords</strong> Click to add a new <span class="md-panel">Keyword</span> object to the <span class="md-panel">Keyword</span> list. 

* <strong class="btn btn-info btn-xs"> <i class="fa fa-eye"> </i> Toggle Thesaurus</strong> Click to hide or show the right side of the <span class="md-window">Custom Thesaurus Edit Window</span> window (thesaurus) to make more room for entering longer words or phrases as keywords. 

---

### Keyword Object

![Custom Keyword List Edit Window](/assets/reference/edit-objects/metadata/keyword/keyword-custom-list.png){caption}

* <span class="md-element">Keyword</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  Commonly used word, formalized word, or phrase used to describe the subject.

* <span class="md-element">ID</span> 1{**type**: string; **max length**: none; **default**: empty}1  A number or code used to identify the keyword within the thesaurus domain.
