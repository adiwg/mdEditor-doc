# Import Records -- Import File Formats
---

mdEditor can import metadata records in mdEditor, mdJSON, and FGDC CSDGM file formats.  Although the import process is the same for each format there are differences that can influence your workflow.

* [mdEditor File Format](#mdeditor-file-format)
* [mdJSON FIle Format](#mdjson-file-format)
* [FGDC CSDGM File Format](#fgdc-csdgm-file-format)

---

### mdEditor File Format

The mdEditor file format is organized to optimize editing in mdEditor.  And similar to mdEditor's screen organization, the file format stores <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> separately.  These items are then linked to each other via the mdEditor's internal 'IDs'.  This organization allows users to define a  <span class="md-panel">Contact</span> or <span class="md-panel">Dictionary</span> once and use it across many <span class="md-panel">Metadata Records</span>. 

The mdEditor file format keeps these internal 'IDs' when a file is exported.  Then when importing an mdEditor file it can do positive item matching with items already loaded in browser cache regardless of whether titles or names have changed.  This provides for a safe merge. 
  
When importing you are allowed to choose which <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> to import.  mdEditor will not automatically gather all <span class="md-panel">Contacts</span> and <span class="md-panel">Dictionaries</span> referenced by an imported <span class="md-panel">Metadata Record</span>.  It is up to you to know which of your <span class="md-panel">Contacts</span> and <span class="md-panel">Dictionaries</span> to include to fully support the <span class="md-panel">Metadata Records</span> you retain after import. 

---

### mdJSON File Format

The mdJSON file format stores a metadata record in a standard independent format developed by ADIwg.  Each metadata record is complete and can stand alone in that all contacts and dictionaries needed by the metadata record are bundled with the record.  This is the format used by mdTranslator to prepare metadata in one of the supported standard metadata formats such as CSDGM or ISO. 

{% hint style='tip' %}
  The mdJSON file format is a great archive format for metadata records once editing has been concluded.  It will not only save all contacts and dictionaries for the complete metadata record, the metadata record and parts will maintain their state at the time the record was saved.  For example, later changes to a reused <span class="md-panel">Contact</span> will not alter the contents of the archived mdJSON file.
{% endhint %} 

Internal item 'IDs' are NOT saved with the mdJSON format.  Thus when importing mdJSON files, item matching cannot be done.  So when an import is requested to be MERGED, all items will be ADDED.  Further, because the imported items do not have internal 'IDs', new 'IDs' are assigned as the items are added to browser cache.  This can create duplicates of items already in browser cache that will need to be manually removed.  

An mdJSON file format is capable of storing multiple metadata records.  Each of these metadata records is a complete metadata record with all its contacts and dictionaries.  Thus when importing multiple mdJSON metadata records any contact or dictionary that was used by more than one of the metadata records will create a duplicate that will need to be manually removed.

{% hint style='tip' %}
  The mdJSON file format performs best when working with a single metadata record at a time.
{% endhint %}

---

### FGDC CSDGM File Format

The FGDC CSDGM (Federal Geographic Data Committee Content Standard for Digital Geospatial Metadata) file format stores a complete, standalone metadata record with all contacts and dictionaries.  The FGDC CSDGM format cannot accommodate multiple metadata records in a single file. 

Internal item 'IDs' are NOT saved with the FGDC CSDGM format.  Thus when importing FGDC CSDGM files item matching cannot be done.  So when an import is requested to be MERGED, all items will be ADDED.  Further, because the imported items do not have internal 'IDs', new 'IDs' are assigned as the items are added to browser cache.  This can create duplicates of items already in browser cache that will need to be manually removed.   

In FGDC CSDGM, each time a contact is referenced in the metadata the author must restate all the contact's information.  Since not all contact elements are required by the standard, or often completed, each reference to a contact which was used multiple times within the metadata record may contain different or even conflicting information.  

{% hint style='danger' %}
  Use caution when deleting duplicate contacts or dictionaries to be sure all pertinent information is saved in the retained contact or dictionary.  
{% endhint %}
