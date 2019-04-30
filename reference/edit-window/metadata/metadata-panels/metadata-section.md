# Metadata Record -- Metadata Section
---

The <span class="md-section">Metadata</span> section of the <span class="md-window">Edit Window</span> collects general information about the metadata record itself.  This is information about the metadata, not the resource described by the metadata.  Yes, this is metadata about metadata! 

![Metadata Edit Window](/assets/reference/edit-objects/metadata/metadata/metadata-editWindow.png)

 * [<span class="md-panel" style="font-size: larger">Basic Information</span>](basicInfo-panel.md)  1{**type**: collection}1  A collection of elements that describe the metadata for this record. 

 * [<span class="md-panel" style="font-size: larger">Metadata Contacts</span>](contacts-panel.md)  <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: array (obj: <span class="md-panel">Responsible Party</span>)}1 An array of persons or organizations to contact regarding the metadata record.

 * [<span class="md-panel" style="font-size: larger">Metadata Identifier</span>](identifier-panel.md)  1{**type**: object (<span class="md-panel">Identifier</span>); **default** UUID}1  A means to provide a unique identifier for this metadata record. 

 * [<span class="md-panel" style="font-size: larger">Parent Metadata</span>](parent-panel.md)  1{**type**: object (<span class="md-panel">Citation</span>); **default** empty}1  A citation for a parent resource or project. 

 * [<span class="md-panel" style="font-size: larger">Metadata Repositories</span>](repository-panel.md)  1{**type**: array (obj: <span class="md-panel">Repository</span>)}1  An array of metadata repositories or clearing houses where the metadata record has been cached.

 * [<span class="md-panel" style="font-size: larger">Online Resource</span>](onlineResource-panel.md)  1{**type**: array (obj: <span class="md-panel">Online Resource</span>)}1  An array of links to online locations where this metadata record can be retrieved.

 * [<span class="md-panel" style="font-size: larger">Metadata Maintenance</span>](maintenance-panel.md)  1{**type**: object (obj: <span class="md-panel">Maintenance</span>)}1 A description of the maintenance schedule for this metadata record. 

 * [<span class="md-panel" style="font-size: larger">Default Metadata Locale</span>](locale-panel.md)  1{**type**: object (<span class="md-panel">Locale</span>)}1  The default or primary language and character encoding for the metadata.
 
 * [<span class="md-panel" style="font-size: larger">Alternate Metadata Reference</span>](alternate-panel.md)  1{**type**: array (obj: <span class="md-panel">citation</span>)}1 An array of <span class="md-panel">Citation</span> references to other editions of this metadata record. 
