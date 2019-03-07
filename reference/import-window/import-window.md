# Reference -- Import Records 
### Import Window
--- 

![Import Panel](/assets/reference/import/import-window.png)

The <span class="md-window">Import</span> window is divided into four panels: <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, <span class="md-panel"> Dictionaries</span>, and <span class="md-panel">Settings</span>.  Each of these panes has identical controls and behavior.  So, what is discussed for one applies to all.  In the above image the <span class="md-panel"> Dictionaries</span> and <span class="md-panel"> Settings</span> panels are not shown, but as previously stated, there is no difference in behavior from the two which are shown. 

* [Search](#search)
* [Select](#select)
* [Import](#import)
* [View](#view)

--- 

{% include "../include-objects/search-obj.md" %}

{% include "../include-objects/select-obj.md" %}

### Import

There are three Import action buttons in the <span class="md-window">Secondary Sidebar</span> to tailor your import.  They control both the items set to be imported and the import file format.

  * #### <strong class="btn btn-success btn-xs"> <i class="fa fa-sign-out"> </i> Click to Import Data</strong> Import All Items
  
    The action will import all items than have been selected for import.  The import process will either replace or merge the imported records according to the state of the 'Replace/Merge Records' switch described below.
 
  * #### <strong class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Cancel Import</strong> Cancel Import
  
    The action will cancel the current import and return the user to the <span class="md-window">Import</span> file selection window.  
   
  * #### ![](/assets/bullets/switch-right.png) Replace/Merge Records 
  
    * ##### Replace
    
      The replace action will remove all items of a type currently loaded in browser cache and replace them with the items selected for import.  For example, if even a single <span class="md-panel">Contact</span> is selected for import, ALL currently loaded contacts will be removed before the import <span class="md-panel">Contact</span> is loaded.  Import items of other types (<span class="md-panel">Metadata Records</span> and <span class="md-panel">Dictionaries</span>) are not effected.  This same process is applied when replacing <span class="md-panel">Metadata Records</span> and <span class="md-panel">Data Dictionaries</span>.  Dictionaries remove only dictionaries; Metadata records remove only metadata records.  <span class="md-panel">Settings</span> are always replaced in full. 
      
      {% hint style='danger' %}
  Remember to backup, <span class="md-window">Export</span>, currently loaded records before using the 'Replace' action.
      {% endhint %}
    
      {% hint style='danger' %}
  Use caution when replacing items.  Dependency links between <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span> and <span class="md-panel">Data Dictionaries</span> can be broken in scenarios where mdEditor files are only partially loaded.  
  
  For example, if the replace action selects a <span class="md-panel">Contact</span> and no <span class="md-panel">Metadata Records</span> or <span class="md-panel">Dictionaries</span>, mdEditor will delete only the loaded <span class="md-panel">Contacts</span> before the import contact is added.  If there are any <span class="md-panel">Metadata Records</span> or <span class="md-panel">Dictionaries</span> that depended on one of the removed <span class="md-panel">Contacts</span> those links will be broken until the missing <span class="md-panel">Contacts</span> are re-imported.
      {% endhint %}
      
  * ##### Merge (default)
   
    Unlike the replace action, merge will not remove items from browser cache prior to importing selected items.  The merge action will instead use the item's internal ID which was assigned by mdEditor as the record was created.  This ID is displayed in the <span class="md-element">ID</span> column of the three selection panels.  
      
    Import items that cannot be matched with an item currently loaded in browser cache are simply added to browser cache.
      
    {% hint style='danger' %}
  The ID shown is for the item to be imported.  Unfortunately, at this time there is no way to display the internal ID of items already loaded into browser cache.  Therefore there is no positive way to determine which loaded items will be matched and replaced by imported items.  The best that can be done at this point is to visually match <span class="md-panel">Metadata Record</span>, <span class="md-panel">Contact</span>, and <span class="md-panel">Dictionary</span> records by names or titles to understand what will happen on import. 
    {% endhint %}
        
  ---

{% include "../include-objects/view-obj.md" %}
    
  * #### <span class="btn btn-primary btn-xs"> <i class="fa fa-binoculars"> </i> Preview JSON</span> Show mdEditor JSON
  
  The 'Preview JSON' button opens a new window and displays the selected item's JSON.  The preview is neither in strict mdEditor JSON or mdJSON format, but somewhere in between.  You can use this preview to examine details of <span class="md-panel"> Metadata Records</span>, <span class="md-panel"> Contacts</span>, <span class="md-panel"> Data Dictionaries</span>, and <span class="md-panel"> Settings</span> prior to import. 
  
  ![Import Panel](/assets/reference/import/import-preview.png)
  
  * ##### Record ID
    
    The "Record ID" is the mdEditor record id of the item selected for JSON preview.  This will match the ID shown in the <span class="md-window"> Import</span> window's selection panels. 
      
  * ##### JSON Window
    
    In the above image the hierarchical JSON sections are shown collapsed (or folded).  To view the full record detail click the '+' (plus sign) on the "Expand/Collapse Sections" button.
    
  * ##### Expand/Collapse Sections
    
  * ##### Increase/Decrease Font/Size
  
  * ##### <span class="btn btn-primary btn-xs"> <i class="fa fa-arrow-left"> </i> Close Preview</span> Return to Import Window
  