# Import Records -- Import File Formats
---

mdEditor can import metadata records in mdEditor file, mdJSON file, FGDC CSDGM file formats.  Although the import process is the same for each format there are differences that can influence your workflow.

* [mdEditor File Format](#mdeditor-file-format)
* [mdJSON FIle Format](#mdjson-file-format)
* [FGDC CSDGM File Format](#fgdc-csdgm-file-format)

---

### mdEditor File Format

The mdEditor file format is organized to best support editing in mdEditor.  And similar to mdEditor's screen organization, the file format stores <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> as separate item.  These individual items are linked to each other via mdEditor's internal 'IDs'.  This organization allows users to reuse their <span class="md-panel">Contacts</span> and <span class="md-panel">Dictionaries</span> across many <span class="md-panel">Metadata Records</span>. 

The mdEditor file format keeps the internal 'IDs' when exported.  Thus when importing an mdEditor file can do positive item matching with items already loaded in browser cache regardless if titles or names have changed.  This provides a safe merge. 
  
When importing an mdEditor file you are allowed to choose which <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> you choose to import.  It is up to you to know which of your <span class="md-panel">Contacts</span> and <span class="md-panel">Dictionaries</span> to include to fully support the <span class="md-panel">Metadata Records</span> you retain after import. 

---

### mdJSON File Format

The mdJSON file format stores a single, complete standalone metadata record in a standard independent format.  All contacts and dictionaries needed are bundled into the mdJSON metadata record.  This is the format used by mdTranslator to prepare metadata in one of the supported standard metadata formats such as FGDC or ISO. 

Internal item 'IDs' are NOT saved with the mdJSON format.  Thus when importing mdJSON files item matching cannot be done.  When merging the import all items are ADDED.  Further, when an item is added it is assigned a new internal 'ID'.  This can create duplicate items with items already in browser cache that need to be manually removed.  



---

### FGDC CSDGM File Format

---
