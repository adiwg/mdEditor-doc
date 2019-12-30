# Dictionary Record -- Entities Section
---

In data management and database design the term "entity" refers to a person, place, thing, or concept about which information is collected and organized.  Entities are most often implemented as tables in a database where the tables consist of numerous rows and columns.  Each row represents an instance of the entity and each column stores a single fact about the instance such as "name" or "ID".

When no <span class="md-panel">Entities</span> have yet been defined for a <span class="md-panel">Dictionary</span> the <span class="md-section">Entities</span> section will display a large blue box stating "No Entity Found".  

![Entity Edit Window with no Entities Defined](/assets/reference/edit-objects/dictionary/entities/dictionary-entity1.png){caption}

<strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Entity</strong> To add the initial <span class="md-panel">Entity</span> click the 'Add Entity' button.

---

After one or more <span class="md-panel">Entities</span> have been defined for the <span class="md-panel">Dictionary</span>, navigating to the <span class="md-section">Entities</span> section will display an array panel of the previously entered <span class="md-panel">Entities</span>.  

![Entity Array Panel](/assets/reference/edit-objects/dictionary/entities/dictionary-entity3.png){caption}

Click <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More...</strong> to continue editing the <span class="md-panel">Entity</span> and gain access to all its elements. 

![Entity Edit Panel](/assets/reference/edit-objects/dictionary/entities/entity-editWindow.png){caption}

{% hint style='tip' %}
  <span class="md-panel">Entities</span> can also be entered via CSV (Comma Separated Value) files.  See the [Import CSV](csvImport/csvImport-process.md) section for details. 
{% endhint %}
 
 * [<span class="md-panel" style="font-size: larger">Entity Information</span>](entityInfo-panel.md) <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  A collection of elements that identify and describe the entity.

 * [<span class="md-panel" style="font-size: larger"> Attributes</span>](attribute-panel.md)  1{**type**: array (obj: <span class="md-panel">Attribute</span>)}1  The array panel displays a list of the defined <span class="md-panel">Entity</span> <span class="md-panel">Attributes</span>.

 * [<span class="md-panel" style="font-size: larger">Entity Structure</span>](structure-panel.md)  1{**type**: collection}1  The <span class="md-panel">File Structure</span> elements provide file descriptions for <span class="md-panel">Entities</span> which are represented as spreadsheets or text files.

 * [<span class="md-panel" style="font-size: larger">Entity Keys</span>](key-panel.md)  1{**type**: collection}1  The <span class="md-panel">Entity Keys</span> panel contains elements that specify keys (primary and foreign keys) used to enforce integrity of the entity's data. 

 * [<span class="md-panel" style="font-size: larger">Entity Indices</span>](index-panel.md)  1{**type**: array (obj: <span class="md-panel"> Entity Index</span>)}1  An array of <span class="md-panel">Entity Index</span> objects used to define alternate keys (keys in addition to the <span class="md-element">Primary Key</span>) for the <span class="md-panel">Entity</span>.  

 * [<span class="md-panel" style="font-size: larger">Entity Reference</span>](entityReference-panel.md)  1{**type**: array (obj: <span class="md-panel"> Citation</span>)}1  The <span class="md-panel">Entity Reference</span> array lists <span class="md-panel">Citations</span> which reference additional information about the <span class="md-panel">Entity</span>.
