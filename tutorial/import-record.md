# Tutorial -- Importing Metadata Records
---

{% hint style='working' %}
  Open the <span class="md-window">Import Window</span>.
  * Click "Import" on the <span class="md-window">Primary Navigation Bar</span>.
{% endhint %}

![Import Window - Home Page](/assets/tutorial/import-record-1.png){caption}

The absence of records showing in the <span class="md-window">Primary Sidebar</span> confirms that there are no records loaded in browser cache.  However, before proceeding with this exercise be sure the browser cache is clear so your experience will parallel this dialog.  

{% hint style='info' %}
  It is not a requirement that browser cache be empty before importing metadata records; an empty cache will just make this exercise simpler.  mdEditor does allow you to import and merge multiple metadata record files to create a set or collection of metadata records that match your organizational needs. 
{% endhint %}

---

As identified on the <span class="md-window">Import Window</span>, mdEditor supports import of metadata records in three formats:
 * mdEditor (.json) 
 * mdJSON (.json)
 * FGDC CSDGM (.xml)
 
#### mdEditor format

The mdEditor export format can contain multiple records, contacts, and dictionaries.  This is useful for organizing a collection of records in mdEditor that are related in some meaningful way, perhaps by project, organization, or principal investigator.  

#### mdJSON format

An mdJSON record may contain only a single metadata record complete with all its contacts and dictionaries attached.  

#### FGDC CSDGM format 

The FGDC CSDGM (Federal Geographic Data Committee - Content Standard for Digital Geospatial Metadata) is a widely used but retiring standard.  Support for importing this standards was provided to help those involved in migrating CSDGM records to newer ISO standards.

---
 
The record we exported in [Exporting Metadata Records](export-record.md) was written using the mdEditor record format.  This format was chosen for us when we clicked the <strong class="btn btn-primary btn-xs"> <i class="fa fa-sign-out"> </i> Export All</strong> button.  Although we only had one record - with two contacts), <strong class="btn btn-primary btn-xs"> <i class="fa fa-sign-out"> </i> Export All</strong> always writes the entire contents of browser cache to the output file. 

To load the exported file back into mdEditor's browser cache just drag and drop it on the big blue target on the <span class="md-window">Import Window</span>.

{% hint style='working' %}
  Import the mdEditor file.
  * Drag the file exported earlier in this exercise over the blue target.
  * When the target turns green, release.
{% endhint %}

{% hint style='info' %}
  You can also enter a link to a file at a remote location and click <strong class="btn btn-primary btn-xs"> <i class="fa fa-cloud-download"> </i> Import</strong>.
{% endhint %}

The <span class="md-window">Import Window</span> should now look similar to the following image: 

![Import Window - Choose Records to Import](/assets/tutorial/import-record-2.png){caption}

You can use the <span class="md-window">Import Window</span> selection panels to choose just the records you wish to import.  These selection panels work identically to those discussed for the <span class="md-window">Export Window</span>, [Exporting Metadata Records](export-record.md), so nothing new here.

Now let's import the entire mdEditor file using just a single click!

{% hint style='working' %}
  Import all metadata records in the import file.
  * Leave all record items checked.  If you unchecked any, re-check them now.
  * Click the <strong class="btn btn-success btn-xs"> <i class="fa fa-sign-in"> </i> Click to Import Data</strong> button.
{% endhint %}

![Import Window - Import Results](/assets/tutorial/import-record-3.png){caption}

As you can see from the records now listed in the <span class="md-window">Primary Sidebar</span>, the browser cache has been reloaded with all the records we exported earlier.  
