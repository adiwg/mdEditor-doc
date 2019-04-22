## Metadata Record -- Main Section
---

### Description Panel

<span class="md-panel" style="font-size: larger">Description</span> <i class="fa fa-asterisk required" title="Required"> </i> 1{**type**: collection}1 <span class="md-panel">Description</span> is a collection of independent elements that hold various text descriptions for the main resource. 

![Description Panel](/assets/reference/edit-objects/metadata/main/description.png)

* <span class="md-element">Abstract</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: markdown text; **default**: empty; **max length**: unlimited}1 A brief narrative summary of the main resource contents.  The <span class="md-element">Abstract</span> is entered in plain text with the option to format the text using a Markdown syntax.  See [Markdown Control].(../../controls/markdown-control.md)

* <span class="md-element">Short Abstract</span> 1{**type**: markdown text; **default**: empty; **max length**: 300 characters}1 A short description of the main resource contents. 
 
  The <span class="md-element">Short Abstract</span> is useful for summary pages, lists, and web pages built by repository and search software.  The <span class="md-element">Short Abstract</span> should be meaningful, not just the first 300 characters of the full <span class="md-element">Abstract</span>.

* <span class="md-element">Purpose</span> 1{**type**: string; **max length**: none; **default**: empty}1 A summary of the intentions for which the resource was created.  

* <span class="md-element">Supplemental Information</span> 1{**type**: string; **max length**: none; **default**: empty}1 Any other descriptive information about the resource.  

* <span class="md-element">Environment Description</span> 1{**type**: string; **max length**: none; **default**: empty}1 Description of the resource in the producer's processing environment, including items such as the software, the computer, the computer operating system, file name, and the resource size.  
