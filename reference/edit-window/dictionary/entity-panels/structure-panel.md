## Dictionary -- Entity Section
---

### File Structure

<span class="md-panel" style="font-size: larger">File Structure</span> 1{**type**: collection}1 The <span class="md-panel">File Structure</span> elements primarily support <span class="md-panel">Entities</span> which are represented as spreadsheets or text files.  

![File Structure Panel](/assets/reference/edit-objects/dictionary/entities/structure.png){caption}

* <span class="md-element">File Separator Character</span> 1{**type**: string; **max length**: none; **default**: empty}1 Enter the character used to indicate the end of one attribute's content and the beginning of the next.  This is generally a comma or tab character.  

  {% hint style='tip' %}
  When a separator character would not be visible in the edit control you can enter a name for the character (e.g. "tab" or "space") .
  {% endhint %}
  
* <span class="md-element"># Header Lines</span> 1{**type**: integer; **min**: 0; **max** none; **default**: empty}1  Enter the number of lines at the top of the entity file that do not contain data.  

* <span class="md-element">Quote Character</span> 1{**type**: string; **max length**: none; **default**: empty}1   Enter the character used to enclose an attribute's value in quotes: either a single quote or double quote.  

  {% hint style='tip' %}
  You can also enter the word "single" or "double".
  {% endhint %}
