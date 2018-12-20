# Settings
### Defaults
---

Default values will pre-fill elements in mdEditor as new records and objects are created.  The default values can be overridden during normal editing as necessary.  

{% hint style='info' %}
  If a default value is cleared (no default value provided) no default value will be set for new elements and objects.
{% endhint %}

![General Settings](/assets/reference/settings/settings-default.png)

* <span class="md-element">Language</span> 1{**type**: codelist (ISO 639 Part 2); **extensible**: YES}1 Identifies the primary language of the main resource.  
 
* <span class="md-element">Character Set</span> 1{**type**: codelist (IANA - Internet Assigned Numbers Authority); **extensible**: YES}1 Name of the character coding standard used in the main resource. 
 
* <span class="md-element">Country</span> 1{**type**: codelist (ISO 3166-1 alpha-3); **extensible**: YES}1 Three letter country code. 

* <span class="md-element">Import URL</span> 1{**type**: URL}1  This value will pre-fill the <span class="md-element">Import from Online URL</span> element on the <span class="md-window">Import</span> window.  This can be useful if many of your imports come from the same remote location.

* <span class="md-element">mdTranslator API URL</span> 1{**type**: URL}1  This provides the URL of the mdTranslator for the <span class="md-window">Translate</span> function.  If you have hosted a local version of mdTranslator that you wish to use, provide its location here.  Otherwise, leave this value as the publicly hosted ADIwg mdTranslator.  

  {% hint style='tip' %}
  If you have delete the ADIwg translator location and wish to restore it, click <span class="btn btn-warning btn-xs">Default</span>.
  {% endhint %}

* <span class="md-element">Metadata Repositories</span> ???

---
  