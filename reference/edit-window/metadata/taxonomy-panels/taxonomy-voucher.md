## Metadata Record -- Taxonomy Section
---
### Taxonomy Voucher

<span class="md-panel" style="font-size: larger">Voucher</span> 1{**type**: array (obj: <span class="md-panel">Voucher</span>)}1  An array of specimen vouchers identifying the specimens used in species determination and where they are being preserved. 

![Taxonomy Voucher Array](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-voucher-array.png) {caption}

---

![Taxonomy Voucher Edit Window](/assets/reference/edit-objects/metadata/taxonomy/taxonomy-voucher-panel.png) {caption}

* <span class="md-element">Specimen</span>  1{**type**: string; **max length**: none; **default**: empty}1   Word or phrase describing the type of specimen collected (e.g. 'herbarium specimens', 'blood samples', 'photographs', 'individuals', or 'batches').

* <span class="md-panel" style="font-size: larger">Repository</span> 1{**type**: object (<span class="md-panel">Responsible Party</span>); **default** empty}1   Information about the curator or contact person and/or agency responsible for the specimens.  2{See below for details}2

---

### Responsible Party Object (Repository)

{% include "../../../include-objects/responsibleParty-obj.md" %}



