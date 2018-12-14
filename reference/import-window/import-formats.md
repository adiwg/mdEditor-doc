# Import Records -- Import File Formats
---

mdEditor can import metadata records in mdEditor file, mdJSON file, FGDC CSDGM file formats.  Although the import process is the same for each format there are differences that can influence your workflow.

* [mdEditor File Format](#mdeditor-file-format)
* [mdJSON FIle Format](#mdjson-file-format)
* [FGDC CSDGM File Format](#fgdc-csdgm-file-format)

---

### mdEditor File Format

The mdEditor file format is organized to optimize editing in mdEditor.  And similar to mdEditor's screen organization, the file format stores <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> separately.  These items are then linked to each other via the mdEditor's internal 'IDs'.  This organization allows users to define a  <span class="md-panel">Contact</span> or <span class="md-panel">Dictionary</span> once and use it across many <span class="md-panel">Metadata Records</span>. 

The mdEditor file format keeps these internal 'IDs' when exported.  Thus when importing an mdEditor file it can do positive item matching with items already loaded in browser cache regardless if titles or names have changed.  This provides for a safe merge. 
  
When importing you are allowed to choose which <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> to import.  mdEditor will not automatically gather all <span class="md-panel">Contacts</span> and <span class="md-panel">Dictionaries</span> referenced by an imported <span class="md-panel">Metadata Record</span>.  It is up to you to know which of your <span class="md-panel">Contacts</span> and <span class="md-panel">Dictionaries</span> to include to fully support the <span class="md-panel">Metadata Records</span> you retain after import. 

---

### mdJSON File Format

The mdJSON file format stores a single, complete standalone metadata record in a standard independent format developed by ADIwg.  All contacts and dictionaries needed by the metadata record are bundled into the mdJSON file.  This is the format used by mdTranslator to prepare metadata in one of the supported standard metadata formats such as FGDC or ISO. 

{% hint style='tip' %}
  The mdJSON file format is a great archive format for completed metadata records.  It will not only store all needed parts for a complete metadata record, the metadata record and all parts will maintain their state at the time of publication.  For example, later changes to a reused <span class="md-panel">Contact</span> will not alter the contents of the archived mdJSON file.
{% endhint %} 

Internal item 'IDs' are NOT saved with the mdJSON format.  Thus when importing mdJSON files item matching cannot be done.  So when the import is MERGED, all items will be ADDED.  Further, because the imported items do not have an internal 'ID', new 'IDs' are assigned as they are added to browser cache.  This can create duplicates of items already in browser cache that will need to be manually removed.  

The mdJSON file format can accommodate multiple metadata records although this can complicate import.  Again since mdEditor's internal 'IDs' are not saved with the format, a contact shared with multiple metadata records will be loaded into browser case once for each use. 

{% hint style='tip' %}
  The mdJSON file format is best used when working with a single metadata record at a time.
{% endhint %}

---

### FGDC CSDGM File Format

---
