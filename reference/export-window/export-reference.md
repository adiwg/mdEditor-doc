# Reference -- Export Record 
---

The export function allows the contents of the currently loaded metadata records, contacts, and dictionaries to be saved either as an mdEditor file or mdJSON file. These files can then be shared with collaborators or saved to a local workstation for backup and/or archiving. 

By default, exported files will be saved in your computer's "downloads" folder.  This default location can be changed in your browser's settings, generally under the "Downloads" topic.  

{% hint style='info' %}
  Because mdEditor is a web application (runs in an internet browser) exports from mdEditor are treated as downloads even though the metadata records are already on your computer.  The download process is actually copying the metadata records from browser cache to the computer's file system
{% endhint %} 

The file name assigned to an exported file follows the form "mdEditor-" (for an mdEditor file export) or "mdJson-" (for an mdJson file export) followed by a timestamp and type of ".json".  For example an mdEditor file exported at 2:14 p.m. on November 21, 2018 would have the name "mdEditor-20181121-141126.json".  Note the timestamp is written in two sections using the format YYYYMMDD-hhmmss.  The files can be freely moved and renamed to fit your requirements.  Just make the sure to keep the MIME type suffix of ".json".  It is not necessary to keep the default file name in order to re-import the file to mdEditor at a later time.  
  
![Export Window](/assets/reference/export/export.png){caption}

The <span class="md-window">Export</span> window is divided into three panels: <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel"> Dictionaries</span>.  Each of these panels has identical controls and behavior.  So, what is discussed for one applies to all.  In the image above the <span class="md-panel"> Dictionaries</span> panel is not shown; there is no difference in behavior from the two which are shown. 

* [Search](#search)
* [Select](#select)
* [Export](#export)
* [View](#view)

--- 

{% include "../include-objects/search-obj.md" %}

{% include "../include-objects/select-obj.md" %}

### Export

There are four Export action buttons in the <span class="md-window">Secondary Sidebar</span> to tailor your export.  They control both the items set to be exported and the export file format.

  * #### <strong class="btn btn-primary btn-xs"> <i class="fa fa-sign-out"> </i> Export All</strong> Export All Items
  
    Click this button to export all items in the <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> panels regardless of whether they are checked or not.  All items will be exported into a single file in the mdEditor file format.  
 
  * #### <strong class="btn btn-info btn-xs"> <i class="fa fa-check-square-o"> </i> Export Selected</strong> Export Selected Items
  
    Use this export button to export only the <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> that have been individually checked.  If no items are checked, the button will be disabled.  All selected items will be exported into a single file in the mdEditor file format.
 
  * #### <strong class="btn btn-success btn-xs"> <i class="fa fa-check-square-o"> </i> Export mdJson</strong> Export Items in mdJson Format
    
    Use this export button to export <span class="md-panel"> Metadata Records</span> in mdJSON file format.  If no <span class="md-panel">Metadata Records</span> are checked, the button will be disabled.  All checked <span class="md-panel">Metadata Records</span> will be exported into a single, composite mdJSON file.
    
   {% hint style='info' %}
   Only <span class="md-panel">Metadata Records</span> can be exported in mdJSON file format.  During the export operation mdEditor will automatically collect and bundle all referenced <span class="md-panel"> Contacts</span> and <span class="md-panel"> Dictionaries</span>.
   {% endhint %}
    
   {% hint style='danger' %}
   It is not recommended that you export more than one <span class="md-panel">Metadata Record</span> into an mdJSON file.  mdTranslator can only process one mdJSON file at a time, so individual mdJSON files will need to be extracted from the composite mdJSON file prior to translation.  Although not complicated, this will require specialized editing software.  
   
   Further, while mdEditor can import composite mdJSON files, <span class="md-panel">Contacts</span> and <span class="md-panel"> Dictionaries</span> will be duplicated once for each record in which they are used.  Records will remain invalid until the duplicate <span class="md-panel">Contacts</span> and <span class="md-panel">Dictionaries</span> are manually deleted.
   {% endhint %}
   
  * #### ![](/assets/bullets/switch-left.png) Include Settings
   
    Setting the 'Include Settings' switch to "Yes" will embed a copy of your mdEditor settings into an mdEditor file output.  The option can be useful when you need to switch browsers or send your metadata to another person for review or edit.  This option is not available for mdJSON file exports.
  
    ---

{% include "../include-objects/view-obj.md" %}
    
  * #### <span class="btn btn-info btn-xs"> <i class="fa fa-eye"> </i> Show</span> Show Record View
  
     The 'Show' button exits the <span class="md-window"> Export</span> window and displays a view of the record with more detail than shown in the <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> panels.  Since the view does exit the <span class="md-window"> Export</span> window, you will need to return by using the browser's "back" button or by clicking <span class="btn btn-default btn-xs"><i class="fa fa-sign-out"> </i> Export</span> in the <span class="md-window">Primary Navigation Bar</span>. 
