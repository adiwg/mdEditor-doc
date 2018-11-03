## Metadata Record -- Main Section
### Description
DO NOT EDIT

<span class="md-panel" style="font-size: larger">Description</span> <i class="fa fa-asterisk required" title="Required"> </i> {**type**: collection} <span class="md-panel">Description</span> is a collection of independent elements that hold various text descriptions for the main resource. 

![Description Panel](/assets/reference/edit-objects/description.png)

* <span class="md-element">Abstract</span> <i class="fa fa-asterisk required" title="Required"></i> {**type**: markdown text; **default**: nil} - A brief narrative summary of the main resource contents.  The <span class="md-element">Abstract</span> is entered in plain text with the option to format the text using a Markdown syntax.  See [Markdown Control](../../controls/markdown-control.md)

* <span class="md-element">Short Abstract</span> {**type**: markdown text; **default**: nil} - A short description of the main resource contents limited to 300 characters or less.  

{% hint style='info' %}
  The <span class="md-element">Short Abstract</span> is useful for summary pages, lists, and web-pages built by repository and search software.  The <span class="md-element">Short Abstract</span> should be meaningful, not just the first 300 characters of the full <span class="md-element">Abstract</span>
{% endhint %}

* <span class="md-element">Purpose</span> {**type**: string; **default**: nil} - A summary of the intentions for which the resource ase created.  

* <span class="md-element">Supplemental Information</span> {**type**: string; **default**: nil} - Any other descriptive information about the dataset.  

* <span class="md-element">Environment Description</span> {**type**: string; **default**: nil} - Description of the dataset in the producer's processing environment, including items such as the software, the computer, the computer operating system, file name, and the dataset size.  

---
