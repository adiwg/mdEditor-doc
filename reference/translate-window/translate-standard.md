# Translate Records 
### Choose Metadata Standard
---

![Translate Window](/assets/reference/translate/translate.png)

* <span class="md-element">Choose Format</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: codelist ([metadata standards supported by ADIwg's mdTranslator](https://mdtranslator.adiwg.org/api/writers))**extensible**: NO; **multi-value**: NO; **default**: empty}1 Translate the <span class="md-panel">Metadata Record</span> using the selected metadata standard.   

* <span class="md-element">Force Valid Output</span> 1{**type**: Boolean; **default**: No}1  Applies to required elements of ISO and FGDC standards only.  If 'Yes', mdTranslator will attempt to force the output to conform with the selected standard by writing tags for missing required elements in accordance with the output standard's rules.  If 'No', mdTranslator will ignore missing required elements which may cause the output to fail validation.  

  {% hint style='info' %}
  For ISO standards, tags of missing required elements will be written with a 'nilReason="missing"' attributes.  For the FGDC CSDGM standard, tags of missing required elements will be written with a value of "missing".  No action is taken for HTML and sbJSON outputs.
  {% endhint %} 
  
  {% hint style='info' %}
  Not all missing requirements can be patched by mdTranslator.  In general, most missing elements can be replaced with some form of a 'missing tag'.  Missing sections in FGDC CSDGM outputs cannot be patched, such as a missing contact section.  Missing sections in ISO can be patched.
  {% endhint %}

* <span class="md-element">Show Empty Tags</span> 1{**type**: Boolean; **default**: No}1  Applies to non-required elements of ISO and FGDC standards only.  If 'Yes', mdTranslator will place an empty tag when values are missing.  If 'No', mdTranslator will take no action.  

  {% hint style='tip' %}
  Having an empty place holder tag rather than a missing tag may help some validators and repositories to validate the metadata record.  It can also be helpful when visually scanning metadata records to see what information could be supplied that was not.  Adding empty tags is also helpful in understand the structure of the standard.  But all this comes with the downside of creating a larger record.
  {% endhint %}
  
* <span class="btn btn-primary btn-sm"> <i class="fa fa-retweet"> </i> Translate</span> Initiate the translation process.  The active <span class="md-panel">Metadata Record</span> will be sent to a publicly hosted mdTranslator server, translated, and the result retuned to your mdEditor where it will be displayed in a <span class="md-window">Result</span> window. 

  {% hint style='info' %}
  You must be connected to the internet to translate a <span class="md-panel">Metadata Record</span>. 
  {% endhint %}
  
---

The <span class="md-panel">Metadata Record</span> to be translated must be saved prior to translation.  In cases where "AutoSave" has been turned "OFF" the <span class="md-panel">Metadata Record</span> may not have been saved when you access the <span class="md-window">Translate</span> window.  In this case the <span class="md-window">Translate</span> window will display a <span class="btn btn-danger btn-xs"> <i class="fa fa-exclamation-circle"> </i> </span> button to allow you to perform a 'Save' without returning to the <span class="md-window">Edit Window</span>

![Translate Window](/assets/reference/translate/translate-save.png)
