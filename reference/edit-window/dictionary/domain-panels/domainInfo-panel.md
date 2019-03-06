## Dictionary Section -- Domain Section
--- 

### Domain Information Panel

<span class="md-panel" style="font-size: larger">Domain Information</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  The <span class="md-panel">Domain Information</span> panel holds a collection of elements that identify and describe the domain.

![Domain Information Panel](/assets/reference/edit-objects/dictionary/domains/domainInfo.png){caption}

* <span class="md-element">Domain Identifier</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: UUID}1 A unique identifier for the domain record. 
                                             
  {% hint style='danger' %}
  Use caution when editing the <span class="md-element">Domain Identifier</span>.  This identifier must be unique among your <span class="md-panel">Dictionary</span> domains.  If this identifier was used to link with <span class="md-panel">Dictionary</span> <span class="md-panel">Attributes</span>, changing it may break the link(s).
  {% endhint %}
  
* <span class="md-element">Code Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 The code name for the <span class="md-panel">Domain</span> used in the dictionary schema.

* <span class="md-element">Common Name</span> 1{**type**: string; **max length**: none; **default**: empty}1 A common or conversational name for the <span class="md-panel">Domain</span>. 

* <span class="md-element">Description</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  A brief description of the <span class="md-panel">Domain</span> including identification of any established sources used in creating the list of domain items.
