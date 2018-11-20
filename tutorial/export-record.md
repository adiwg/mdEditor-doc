# Tutorial -- Exporting a Metadata Record
---

Now that our very minimal metadata record can be translated into a valid, but equally minimal, ISO metadata record, it's time to preserve our hard work.  By that I mean copy the records from browser cache to your local storage.  

{% hint style='info' %}
  Local storage can be a folder on your hard drive or anywhere on your local network, preferably a location that is backed-up periodically.    
{% endhint %}
 
{% hint style='working' %}
  Open the <span class="md-window">Export Window</span>.
  * Click "Export" on the <span class="md-window">Primary Navigation Bar</span>.
{% endhint %}

![Export Window](/assets/tutorial/export-record-1.png){caption}

The <span class="md-window">Export Window</span> is showing two panels; one for <span class="md-panel">Metadata Records</span> and a second for <span class="md-panel">Contacts</span>.  

{% hint style='info' %}
  If we had defined a "Dictionary" there would also be a <span class="md-panel">Dictionaries</span> panel on the <span class="md-window">Export Window</span>.  Instead a banner is displayed proclaiming "No Dictionaries Found." 
{% endhint %}

### Selecting Records for Export

To select records (Metadata Records, Contacts, and/or Dictionaries) for export, simply click the checkbox in the left-hand column next to the items you wish to export.  The selected records will all be bundled into a single export file.  Bottom line, any record that is checked when you click "Export" will be exported.  

It is not uncommon for a list of records to become too long to fit on a screen, particularly a list of contacts.  To help refine a list, search controls have been added to the panels.  Typing a string into one of these search controls will cause the panel to display only items with a match to the string.  The search controls located below column names refine the list based on the column's contents.  The search control located under the panel's <span class="md-window">Panel Title Bar</span> refines the list based on a match in ANY of the panel's columns. 

{% hint style='info' %}
  Search criteria can also be entered into more than one search control.  The multiple search criteria are applied as a logical "AND" not an "OR".  This means the selected items will need to match ALL the search criteria, not merely ANY of the criteria.
{% endhint %}

A checkbox in the panel's label row - identified as "Select All Items" in the screenshot above - will check or uncheck all items in the panel.  

{% hint style='danger' %}
  If you refine a list using search criteria, the "Check All Items" checkbox will still check or uncheck ALL rows in the panel, even those excluded by the search criteria. 
{% endhint %}

### <strong class="btn btn-primary btn-xs"> <i class="fa fa-sign-out"> </i> Export All</strong> Export All Items

The "Easy Button."  Export all items in the <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> panels, checked or not.

### <strong class="btn btn-info btn-xs"> <i class="fa fa-check-square-o"> </i> Export Selected</strong> Export Selected Items

Export all **Checked** items in the <span class="md-panel">Metadata Records</span>, <span class="md-panel">Contacts</span>, and <span class="md-panel">Dictionaries</span> panels.

---

{% hint style='working' %}
  Export all records.
  * Click the <strong class="btn btn-primary btn-xs"> <i class="fa fa-sign-out"> </i> Export All</strong> button.
{% endhint %}

No questions asked!  mdEditor just exported all the records we created.  If you missed it, a file was just dropped into the "Downloads" folder on your hard drive.  

{% hint style='info' %}
  The file was given a name using a format of "mdeditor-{date}-{time}.json".  For example, my file was named "mdeditor-20180907-150907.json"; the date being September 7, 2018 and time 1:09:07 pm. 
{% endhint %} 

{% hint style='tip' %}
  Placing files in the "Downloads" folder is the default setting of your internet browser.  If you prefer you can usually change this location in your browser settings.  Most browser preferences will even let you set a flag to ask for a file location and file name each time download a file. 
{% endhint %}

It's now up to you.  Move the download file to a safe location and give it proper name.  
