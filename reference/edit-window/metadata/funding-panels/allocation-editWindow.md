## Metadata Record -- Funding Section
---
### Allocations Edit Window

![Allocation Edit Window](/assets/reference/edit-objects/metadata/funding/funding-allocation.png){caption}

* <span class="md-element">Amount</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: real; **min**: 0.00; **max** none; **default**: 0.00}1  Amount of the allocation in the indicated currency.

* <span class="md-element">Currency</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist (Swiss Association for Standards); **extensible**: NO; **multi-value**: NO; **default**: "USD"}1  Type of currency in which the allocation was made.

* <span class="md-element">Award ID</span> 1{**type**: string; **max length**: none; **default**: empty}1 The identifier used by the source contact to reference this allocation. 

* <span class="md-element">Source</span> 1{**type**: codelist (Contacts loaded in browser cache); **extensible**: NO; **multi-value**: NO; **default**: empty}1 The <span class="md-panel">Contact</span> providing the allocation.

* <span class="md-element">Recipient</span> 1{**type**: codelist (Contacts loaded in browser cache); **extensible**: NO; **multi-value**: NO; **default**: empty}1 The <span class="md-panel">Contact</span> receiving the allocation. 

* <span class="md-panel">Other Contacts</span> 1{**type**: array (obj: <span class="md-panel">Responsible Party</span>)}1 An array of individuals and/or organizations other than source and recipient that serve as contact points or other roles related to the allocation.  2{[See object details](#responsible-party)}2

* <span class="md-element">Matching</span> 1{**type**: Boolean; **default**: FALSE}1 Indicates whether the funds are to be considered matching funds.

* <span class="md-element">Comment</span> 1{**type**: string; **max length**: none; **default**: empty}1 Additional information relevant to the allocation.

* <span class="md-panel">Online Resource</span> 1{**type**: array (obj: <span class="md-panel">Online Resource</span>)}1 An array of online resources related to the allocation.  2{[See object details](#online-resource)}2

---

### Responsible Party

{% include "../../../include-objects/responsibleParty-obj.md" %}

---

### Online Resource

{% include "../../../include-objects/onlineResource-obj.md" %}
