## Metadata Record -- Main Section
---

### Online Graphic Resource Array

<span class="md-panel" style="font-size: larger">Online Graphic Resource</span> 1{**type**: array (obj: <span class="md-panel">Online Graphic Resource</span>); **default**: empty}1 An array of <span class="md-panel">Online Graphic Resource</span> objects that describe internet links to graphic files.  

![Online Graphic Resource Array](/assets/reference/edit-objects/metadata/main/onlineGraphicResource-array.png)

Along with the file <span class="md-element">Name</span> and <span class="md-element">URI</span>, mdEditor attempts to provide a thumbnail of each graphic file listed in the <span class="md-panel">Online Graphic Resource</span> array.  If a thumbnail cannot be generated, a broken image link will be displayed like the one shown for the second array item above.  

{% hint style='info' %}
  If for some reason mdEditor does not produce a thumbnail preview, check for the following:
  * an invalid link 
  * the file's graphic format is not readable by mdEditor
  * the file is not a graphic file 
{% endhint %} 

---

{% include "../../../include-objects/onlineGraphicResource-obj.md" %}
