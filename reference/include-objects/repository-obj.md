### Metadata Repository Object

* <span class="md-element">Repository</span> 1{**type**: codelist (ADIwg MetadataRepository); **extensible**: YES; **multi-value**: NO; **default**: empty}1 Repository Name 

* <span class="md-element">Collection Title</span> 1{**type**: string; **max length**: none; **default**: empty}1 A text string to identify a set of resources in the repository.

  {% hint style='info' %}
  The mdJSON <span class="md-panel">Metadata Repository</span> object has a full <span class="md-panel">Citation</span> to describe the repository.  Currently this is not fully implemented in mdEditor.  The <span class="md-element">Collection Title</span> is inserted into the <span class="md-element">Title</span> element of that citation.
  {% endhint %}
