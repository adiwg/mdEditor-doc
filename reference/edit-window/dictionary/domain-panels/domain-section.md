# Dictionary Record -- Domain Section
---

In data management and database design the term "domain" refers to a list of all the permissible values for a data element.  For example, if you have a table that collects information about people you may have a column for <span class="md-element">gender</span>.  The domain for <span class="md-element">gender</span> would likely be "M", "F".  In mdEditor <span class="md-panel">Domain</span> objects are described for a <span class="md-panel">Dictionary</span> in the <span class="md-section">Domains</span> section of the <span class="md-panel">Dictionary</span> <span class="md-window">Edit Window</span> and later attached to <span class="md-panel">Attributes</span> while defining or editing <span class="md-panel">Entities</span>.

When no <span class="md-panel">Domains</span> have yet been defined for a <span class="md-panel">Dictionary</span> the <span class="md-section">Domains</span> section will display a large blue box stating "No Domain Found".  

![Domain Edit Window with no Domains Defined](/assets/reference/edit-objects/dictionary/domains/dictionary-domain1.png){caption}

<strong class="btn btn-success btn-xs"> <i class="fa fa-plus"> </i> Add Domain</strong> To add the initial <span class="md-panel">Domain</span> click the 'Add Domain' button.

---

After one or more <span class="md-panel">Domains</span> are defined for the <span class="md-panel">Dictionary</span>, navigating to the <span class="md-section">Domains</span> section will display an array panel of the previously entered <span class="md-panel">Domains</span>.

![Domain Array Panel](/assets/reference/edit-objects/dictionary/domains/dictionary-domain3.png){caption}

From this array panel new <span class="md-panel">Domains</span> can be defined and existing <span class="md-panel">Domains</span> can be edited or deleted.  After entering a <span class="md-panel">Domain</span>, click <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> More...</strong> to access the remaining elements. 

![Domain Array Panel](/assets/reference/edit-objects/dictionary/domains/domain-editWindow.png){caption}

 * [<span class="md-panel" style="font-size: larger">Domain Information</span>](domainInfo-panel.md)  <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1  A collection of elements that identify and describe the domain. 

 * [<span class="md-panel" style="font-size: larger">Domain Items</span>](domainItem-panel.md)  1{**type**: array (obj: <span class="md-panel"> Domain Item</span>)}1   An array of defined <span class="md-panel">Domain Item</span> objects.
 
 * [<span class="md-panel" style="font-size: larger">Domain Reference</span>](domainReference-panel.md)  1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1  The domains's citation information.  
