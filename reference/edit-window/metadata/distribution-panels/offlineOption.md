## Metadata Record -- Distribution Section
---
### Offline Transfer Option 

![Offline Transfer Option Edit Window](/assets/reference/edit-objects/metadata/distribution/transferOption-offline.png){caption}

* <span class="md-element">Medium Title</span> 1{**type**: string; **max length**: none; **default**: empty}1  Name of the offline medium on which the distribution can be obtained.  

* <span class="md-panel">Storage</span> 1{**type**: collection}1  A collection of elements that describe the physical characteristics of how the information was written to the medium.

  * <span class="md-element">Density</span>  1{**type**: number; **min**: 1; **max** none; **default**: empty}1  Density at which the data are recorded.
  
  * <span class="md-element">Density Units</span>  1{**type**: string; **max length**: none; **default**: empty}1  Units of measure for the recording density.
  
  * <span class="md-element">Number of Volumes</span>  1{**type**: integer; **min**: 1; **max** none; **default**: empty}1  The number of items identified in the media resource.
  
  * <span class="md-element">Storage Format</span>  1{**type**: codelist (ISO MD_MediumFormatCode); **extensible**: YES; **multi-value**: NO; **default**: empty}1  Method used by the resource provider to write to the medium, such as: tar, iso9660, etc.

* <span class="md-panel">Identifier</span> 1{**type**: collection}1  A unique identifier for an instance of the medium.  

  * <span class="md-element">Identifier</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: string; **max length**: ooo; **default**: empty}1  A unique identifier for an instance of the medium.
  
  * <span class="md-element">Namespace</span> 1{**type**: string; **max length**: ooo; **default**: empty}1  A string which unambiguously defines the namespace for the identifier.
  
  * <span class="md-element">Version</span> 1{**type**: string; **max length**: ooo; **default**: empty}1  The version of the identifier
  
  * <span class="md-element">Description</span> 1{**type**: string; **max length**: ooo; **default**: empty}1  A natural language description of the meaning of the identifier value.

* <span class="md-element">Note</span> 1{**type**: string; **max length**: ooo; **default**: empty}1  Description of other limitations or requirements for using the medium.
