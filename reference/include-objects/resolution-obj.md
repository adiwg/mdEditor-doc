![Spatial Resolution Edit Window](/assets/reference/edit-objects/metadata/spatial/resolution-panel.png)

{% hint style='info' %}
  It is required to have at least one of the three <span class="md-panel">Spatial Resolution</span> elements, but multiple are permitted.
{% endhint %}

* <span class="md-element">Scale Factor</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: integer; **min**: 0; **max** none; **default**: empty}1    The geographic scale for the resource expressed as map scale (e.g. 1:24000) or fraction (1/24000); enter the denominator (e.g. 24000).

* <span class="md-element">Level of Detail</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: string; **max length**: none; **default**: empty}1   A brief textual description of the spatial resolution of the  resource.

* <span class="md-panel" style="font-size: larger">Measure</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: object (<span class="md-panel">Measure</span>); **default** empty}1  Scale of the geographic extent expressed in distance, length, or angle parameters.  2{[See object details](#measure-object)}2 

---

{% include "measure-obj.md" %}
