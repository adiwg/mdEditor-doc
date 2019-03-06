## Dictionary Section -- Entity Section
--- 

### Entity Information Panel

<span class="md-panel" style="font-size: larger">Entity Information</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  The <span class="md-panel">Entity Information</span> panel holds a collection of elements that identify and describe the entity.

![Entity Information Panel](/assets/reference/edit-objects/dictionary/entities/entityInfo.png){caption}

* <span class="md-element">Entity Identifier</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: UUID}1 A unique identifier for the entity. 
                                             
  {% hint style='danger' %}
  Use caution when editing the <span class="md-element">Entity Identifier</span>.  This identifier must be unique among your <span class="md-panel">Dictionary</span> entities.  If this identifier was used to link with <span class="md-panel">Dictionary</span> <span class="md-panel">Attributes</span>, changing it may break the link(s).
  {% endhint %}
  
* <span class="md-element">Code Name</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 The code name for the <span class="md-panel">Entity</span> used in the dictionary schema.

* <span class="md-element">Definition</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1  A brief definition for the <span class="md-panel">Entity</span>.

* <span class="md-element">Common Name</span> 1{**type**: string; **max length**: none; **default**: empty}1 A common or conversational name for the <span class="md-panel">Entity</span>. 

* <span class="md-panel">Aliases</span> 1{**type**: array (string)}1 An array of additional names that are used to refer to this <span class="md-panel">Entity</span>. Each <span class="md-element">alias</span> is a text string.
