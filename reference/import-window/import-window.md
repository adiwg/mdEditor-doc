# Import Records 
### Import Window
--- 

![Import Panel](/assets/reference/import/import-panel.png)

The <span class="md-window">Import</span> window is divided into four panels: <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, <span class="md-panel"> Dictionaries</span>, and <span class="md-panel">Settings</span>.  Each of these panes has identical controls and behavior.  So, what is discussed for one applies to all.  In the above image the <span class="md-panel"> Dictionaries</span> and <span class="md-panel"> Settings</span> panels are not shown, but as previously stated, there is no difference in behavior from the two which are shown. 

--- 

### Search

When there are many metadata records, contacts, or dictionaries loaded into the browser cache, the search capabilities of the <span class="md-window">Import</span> page can help quickly narrow the number of items being considered for import.  

 * #### Search Column
   Immediately under each column header is the "Search A Column" control.  Text entered into this control is matched against the contents of that column only.  If the column value matches the search text, the item remains visible, otherwise the item is hidden.  All items in the browser cache will be searched not just those currently visible panel.  
 
 * #### Search ALL Columns 
    Text entered into "Search All Columns" control will be matched against the contents of each column.  If the column value matches the search text, the item remains visible, otherwise the item is hidden.  All items in the browser cache will be searched not just those currently visible panel. 
 
   ---

### Select

For an item to be considered for import, it must have a checkmark in the checkbox at the head of its row.  

 * #### Select Item
   To select an item for import, place a checkmark in a "Select An Item" checkbox by clicking the checkbox in the item's row.  Click it again to un-check the item.
   
 * #### Select ALL Items
   To select all displayed items in the panel for import, place a checkmark in the "Select All Items" checkbox by clicking the checkbox in the table headings row.  All items in the browser cache will be checked not just those currently visible panel.  Click it again to un-check all items. 
 
   ---

### Import

There are three Import action buttons in the <span class="md-window">Secondary Sidebar</span> to taylor your import.  They control both the items set to be imported and the import file format.

  * #### <strong class="btn btn-success btn-xs"> <i class="fa fa-sign-out"> </i> Click to Import Data</strong> Import All Items
  
 
  * #### <strong class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Cancel Import</strong> Cancel Import
  
   
  * #### ![](/assets/bullets/switch-right.png) Merge Records
   
  
  ---

### View

Each import panel has built in support for navigating long lists of <span class="md-panel">Metadata Records</span>, <span class="md-panel"> Contacts</span>, and <span class="md-panel"> Dictionaries</span>.  The following functions are available for each panel.

  * #### Number of Items to Display
  
    This select list allows you to set the maximum number of items to display in the panel.  The default is 10 items with options for 25, 50, and 500.  You cannot set your own number of items.
    
  * #### Record Controls
  
    The 'Record Controls' manage which set of items are visible in the panel.  The controls become active when there are more items in browser cache than displayed in the panel given the limit set using the 'Number of Items to Display' control (above).

    * ##### <i class="fa fa-forward"> </i> Next Page
  
    * ##### <i class="fa fa-backward"> </i> Previous Page
  
    * ##### <i class="fa fa-fast-forward"> </i> Last Page
  
    * ##### <i class="fa fa-fast-backward"> </i> First Page
    
  * #### Select Columns to Display
  
    Clicking this control presents a list of columns that can be displayed in the panel.  By default all available columns are displayed.  You can hide a column - or return it to visible again - by checking or unchecking the column name in the control's list.  The list of columns is naturally different between the <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> panels.
    
  * #### <span class="btn btn-primary btn-xs"> <i class="fa fa-binoculars"> </i> Preview JSON</span> Show mdEditor JSON
  

---
  