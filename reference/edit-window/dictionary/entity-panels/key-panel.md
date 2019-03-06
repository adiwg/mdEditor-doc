## Dictionary Reference -- Entity Section
---

### Entity Keys Panel

<span class="md-panel" style="font-size: larger">Entity Keys</span> 1{**type**: collection}1  The <span class="md-panel">Entity Keys</span> panel contains elements that specify keys (a.k.a. constraints) used to enforce integrity of the entity's data.  

![Entity Keys Panel](/assets/reference/edit-objects/dictionary/entities/keys.png){caption}

* <span class="md-element">Primary Key</span> 1{**type**: codelist (<span class="md-panel">Attributes</span> defined in the current <span class="md-panel">Entity</span>); **extensible**: YES; **multi-value**: YES; **default**: empty}1 
The primary key is a field (or collection of fields), that allows each instance of the <span class="md-panel">Entity</span> to be uniquely identified. 

  {% hint style='info' %}
  Although the <span class="md-element">Primary Key</span> element is not required, it is highly recommended and is required for all SQL table definitions.
  {% endhint %}
  
* <span class="md-panel">Foreign Key</span> 1{**type**: array (obj: <span class="md-panel">Foreign Key</span>)}1  In data management a foreign key is a field (or collection of fields) in one <span class="md-panel">Entity</span> that refers to the primary key in another <span class="md-panel">Entity</span>.  2{[See object details](#foreign-key-object)}2 
  
  {% hint style='info' %}
  The foreign key constraint is used to prevent invalid data from being inserted into the foreign key column.  This is enforced by requiring the foreign key column(s) to use one of the values contained in the referenced table column(s).  In the above image foreign key column "state_id" for entity "CITY must match a "state code" in the "STATE" entity. 
  {% endhint %}
  
---

### Foreign Key Object

* <span class="md-element">Local Attributes</span> 1{**type**: codelist (<span class="md-panel">Attributes</span> defined in the current <span class="md-panel">Entity</span>); **extensible**: YES; **multi-value**: YES; **default**: empty}1 Choose the attribute (or collection of attributes) from the current entity that will be matched to the primary key of the referenced entity.  

* <span class="md-element">Referenced Entity</span> 1{**type**: codelist (<span class="md-panel">Entities</span> defined in the current <span class="md-panel">Dictionary</span>); **extensible**: YES; **multi-value**: NO; **default**: empty}1 Choose the <span class="md-panel">Entity</span> which will act as the reference table for permissible values for the local attribute (or collection of attributes). 

* <span class="md-element">Referenced Attributes</span> 1{**type**: codelist (<span class="md-panel">Attributes</span> defined in the referenced <span class="md-panel">Entity</span>); **extensible**: YES; **multi-value**: YES; **default**: empty}1 Choose the attribute (or collection of attributes) from the reference entity that represent its primary key. 

  {% hint style='danger' %}
  When a foreign key is defined with multiple attributes be sure to select <span class="md-element">Referenced Attributes</span> in the same order as <span class="md-element">Local Attributes</span> so there is a one-to-one correspondence based on entry order.
  {% endhint %} 
