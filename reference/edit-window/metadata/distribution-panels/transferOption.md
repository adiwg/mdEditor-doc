## Metadata Record -- Distribution Section
---
### Transfer Option

![Transfer Option Edit Window](/assets/reference/edit-objects/metadata/distribution/transferOption.png){caption}

* <span class="md-element">Transfer Size</span> 1{**type**: integer; **min**: 0; **max** none; **default**: empty}1  Estimated size of the distribution package, expressed in megabytes.  If the distribution is made available in units, <span class="md-element">Transfer Size</span> would be the average size of a unit.  Specify the type of such units in <span class="md-element">Distribution Units</span>.

* <span class="md-element">Distribution Units</span> 1{**type**: string; **max length**: none; **default**: empty}1  The tiles, layers, geographic areas, etc., in which data are available. 

* <span class="md-panel">Online Option</span>  1{**type**: array (obj: <span class="md-panel">Online Resource</span>)}1  Each <span class="md-panel">Online Option</span> contains information about an online source for the distribution.  2{[See object details](#online-resource)}2

* [<span class="md-panel" style="font-size: larger">Offline Option</span>](offlineOption.md)  1{**type**: array (obj: <span class="md-panel">Offline Option</span>)}1  Each <span class="md-panel">Offline Option</span> object contains information about an option for offline medium on which the distribution and be obtained.

* [<span class="md-panel" style="font-size: larger">Distribution Formats <span>](format.md)  1{**type**: array (obj: <span class="md-panel">Distribution Format</span>)}1  Provides information about the format(s) used by the distributor.

* <span class="md-panel">Transfer Frequency</span> 1{**type**: object (<span class="md-panel">Time Duration</span>); **default** empty}1  The rate of occurrence of distribution.  2{[See object details](#time-duration-object)}2

---

### Online Resource 

{% include "../../../include-objects/onlineResource-obj.md" %}

---

{% include "../../../include-objects/timeDuration-obj.md" %}
