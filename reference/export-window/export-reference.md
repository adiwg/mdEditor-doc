# Export Record 
DO NOT EDIT

The export function allows the contents of the currently loaded metadata records, contacts, and dictionaries to be saved either as an mdEditor file or mdJSON file. These files can then be shared with collaborators or saved to a local workstation for backup and/or archival. 

By default, exported files will be saved in your computers "downloads" folder.  This default location can be changed in your browser's settings generally under the "Downloads" topic.  

{% hint style='info' %}
  Because mdEditor is a web application (runs in an internet browser) exports from mdEditor are treated as downloads even though the metadata records are already on your computer.  The download process is actually copying the metadata records from browser cache to computer's file system
{% endhint %} 

The file name assigned to an exported file follows the form "mdEditor-" (for an mdEditor file export) or "mdJson-" (for an mdJson file export) followed by a timestamp and type of ".json".  For example an mdEditor file exported at 2:14 p.m. on November 21, 2018 would have the name "mdEditor-20181121-141126.json".  Note the timestamp is written in two sections using the format YYYYMMDD-hhmmss.  The files can be freely renamed to fit your requirements.  Just make the sure to keep the format suffix of ".json".  It is not necessary to keep the default file name in order to re-import the file to mdEditor at a later time.  
  
![Export Window](/assets/reference/export/export.png){caption}

The <span class="md-window">Export</span> window is divided into three panels: <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel"> Dictionaries</span>.  Each of these panes has identical controls and behavior.  So, what is discussed for one applies to all.  In the above image the <span class="md-panel"> Dictionaries</span> panel is not shown, but as previously stated, it is no different than the other two. 

--- 

### Search

When there are a large number of metadata records, contacts, or dictionaries loaded into the browser cache the search capabilities of the <span class="md-window">Export</span> page can help quickly narrow the number of items in consideration for export.  

  * #### Search ALL Columns 
    Text entered into "Search All Columns" control will be matched against the contents of each column.  If the contents match a column value, the item remains visible; otherwise the item is hidden.  
 
 * #### Search A Column
   Immediately under each column header is the "Search A Column" control.  Text entered into this control is matched against the contents of the column.  If the contents match the column value, the item remains visible; otherwise the item is hidden.  
 
   ---

### Select

For an item to be considered for export, it must have a checkmark in the checkbox at the head of the item's row.  

 * #### Select ALL Items
   To select all displayed items in the panel for export, place a checkmark in the "Select All Items" checkbox by clicking the checkbox in the table headings row.  Click it again to un-check all items in the panel.  
 
 * #### Select An Item
   To select a specific item for export, place a checkmark in a "Select An Item" checkbox by clicking the checkbox in the item row.  Click it again to un-check the item.
   
   ---

### Export

There are three Export action buttons in the <span class="md-window">Secondary Sidebar</span> to choose from.  They control both the items set to export and the export file format.

  * #### <strong class="btn btn-primary btn-xs"> <i class="fa fa-sign-out"> </i> Export All</strong> Export All Items
  
    Click this button to export all items in the <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> panels regardless if they are individually checked.  All items will be exported into a single file in the mdEditor file format.
 
  * #### <strong class="btn btn-info btn-xs"> <i class="fa fa-check-square-o"> </i> Export Selected</strong> Export Selected Items
  
    Use this export button to export only the <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> that have been individually checked.  If no items are checked, the button will be disabled.  All selected items will be exported into a single file in the mdEditor file format.
 
  * #### <strong class="btn btn-success btn-xs"> <i class="fa fa-check-square-o"> </i> Export mdJson</strong> Export Items in mdJson Format
    
    Use this export button to export <class="md-panel">Metadata Records</span> in mdJSON file format.  If no <span class="md-panel">Metadata Records</span> are checked, the button will be disabled.  All checked <span class="md-panel">Metadata Records</span> will be exported into a single, composite mdJSON file.
    
   {% hint style='info' %}
   Only <span class="md-panel">Metadata Records</span> can be exported in mdJSON file format.  During the export operation mdEditor will automatically collect and include all referenced <span class="md-panel"> Contacts</span> and <span class="md-panel"> Dictionaries</span>.
   {% endhint %}
    
   {% hint style='danger' %}
   It is not recommended to export more than one <span class="md-panel">Metadata Record</span> into a mdJSON file.  Multiple records cannot be processed by mdTranslator so individual records will need extracted from the composite mdJSON file before translation.  Also, while mdEditor can import multiple mdJSON files from a single file, <span class="md-panel">Contacts</span> will be duplicated and all links between <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> will be broken.
   {% endhint %}
   
  * #### ![](/assets/bullets/switch-left.png) Include Settings
   
    Setting 'Include Settings' to "Yes" will embed a copy of your mdEditor settings into an mdEditor file output.  The option can be useful when you need to switch browsers or send your metadata to another person to review or edit.  This option is not available for mdJSON file exports.
  
    ---

### View

---