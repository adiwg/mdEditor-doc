## Dictionary Section -- Entity Section
--- 

### Attribute Value Ranges Panel

<span class="md-panel" style="font-size: larger">Value Ranges</span> 1{**type**: array (obj: <span class="md-panel">ValueRange</span>)}1  Values of an attribute may be restricted to one or more ranges of values.  These ranges may be declared using the <span class="md-panel">ValueRange</span> object. 

  {% hint style='info' %}
  Use the <span class="md-panel">Attribute's</span> <span class="md-element">Minimum Value</span> and <span class="md-element">Maximum Value</span> elements to define the overall range for the <span class="md-panel">Attribute</span>.  Use the <span class="md-panel">ValueRange</span> object to define sub-ranges within the overall range. 
  {% endhint %}

![Attribute Value Range Panel](/assets/reference/edit-objects/dictionary/attribute/valueRange.png){caption}

* <span class="md-element">Min Value</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 The least value that the attribute can be assigned within this range of values.

* <span class="md-element">Max Value</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: none; **default**: empty}1 The greatest value that the attribute can be assigned within this range of values.
