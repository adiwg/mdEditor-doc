# Settings
### Defaults
---

Default values will pre-fill elements in mdEditor as new records and objects are created.  The default values can be overridden during normal editing as necessary.  

{% hint style='info' %}
  If a default value is cleared (no default value provided) no default value will be set for new elements and objects.
{% endhint %}

![General Settings](/assets/reference/settings/settings-default.png)

* <span class="md-element">Language</span> 1{**type**: codelist (ISO 639 Part 2); **extensible**: YES **multi-value**: NO; **default**: "eng"}1 Identifies the primary language of the main resource.  
 
* <span class="md-element">Character Set</span> 1{**type**: codelist (IANA - Internet Assigned Numbers Authority); **extensible**: YES **multi-value**: NO;; **default**: "UTF-8"}1 Name of the character coding standard used in the main resource. 
 
* <span class="md-element">Country</span> 1{**type**: codelist (ISO 3166-1 alpha-3); **extensible**: YES **multi-value**: NO;; **default**: "USA"}1 Three letter country code. 

* <span class="md-element">Import URL</span> 1{**type**: URL}1  This value will pre-fill the <span class="md-element">Import from Online URL</span> element on the <span class="md-window">Import</span> window.  This can be useful if many of your imports come from the same remote location.

* <span class="md-element">mdTranslator API URL</span> 1{**type**: URL}1  This provides the URL of the mdTranslator for the <span class="md-window">Translate</span> function.  If you have hosted a local version of mdTranslator that you wish to use, provide its location here.  Otherwise, leave this value as the publicly hosted ADIwg mdTranslator.  

  {% hint style='tip' %}
  If you have deleted the ADIwg translator location and wish to restore it, click <span class="btn btn-warning btn-xs">Default</span>.
  {% endhint %}

* <span class="md-element">Metadata Repositories</span> 1{**type**: array (obj: <span class="md-panel"> Metadata Repository</span>)}1  Add a <span class="md-panel">Metadata Repository</span> object to set a default <span class="md-element">Collection Title</span> for a <span class="md-element">Repository</span>.  When the <span class="md-element">Repository</span> is selected on an <span class="md-window">Edit Window</span> the <span class="md-element">Collection Title</span> will auto fill. 2{[See object details](#metadata-repository-object)}2 

---

{% include "../include-objects/repository-obj.md" %}
