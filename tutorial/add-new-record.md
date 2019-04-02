# Tutorial -- Add a New Metadata Record
---

![Adding a new record](/assets/tutorial/add-record.png){caption}

{% hint style='working' %}
  Create a New Record.
  * Click the plus <span class="btn btn-xs btn-primary"><i class="fa fa-plus"> </i></span> button on the left menu-bar next to "Metadata Records"
{% endhint %}

You should see something like this ...
  
![The newly created, unsaved record](/assets/tutorial/new-record.png){caption}

The "Create New Record" form collects the minimal information mdEditor requires to save a new metadata record.  This minimal information is, of course, not sufficient to meet the minimum of any metadata standard, but just enough that you and mdEditor can find the record for editing.

{% hint style='info' %}
"Contacts" and "Dictionaries" are added in a similar manner.  We'll discuss these items later. For now, just add a new metadata record.
{% endhint %}

#### Record ID <i class="fa fa-asterisk required" title="Required"> </i>
Notice that mdEditor has filled in a Record ID for you.  By default mdEditor assigns a [UUID](https://tools.ietf.org/html/rfc4122) (Universally Unique Identifier) as the Record ID.

{% hint style='info' %}
  You may change the Record ID later if you like, but it must be unique among all your metadata records otherwise there may be some confusion later on when using more advanced mdEditor features or publishing the metadata.  If you have a reliable record identification system, use it, otherwise best to keep the UUID.
{% endhint %}

#### Record Title <i class="fa fa-asterisk required" title="Required"> </i>
Here is where you will assign a title that will describe the main resource of this metadata record.  In addition to becoming part of your metadata record, this title will also be used in the left side-bar to identify and access your record.

{% hint style='working' %}
  Enter your Record Title.
{% endhint %}

{% hint style='info' %}
Notice the record title appears in the left side-bar as you type the title in the edit panel.  When you want to access the record in the future, you'll do that from the left side-bar.
{% endhint %}

#### Resource Types <i class="fa fa-asterisk required" title="Required"> </i>
Choose a resource type for the main resource described by this metadata record.  Resource type describes the broad category of the main resource, e.g. "dataset", "project", "software", or "sciencePaper".  The select control will provide these and other resource types for you to choose from.   You may optionally provide a name for the resource.

{% hint style='working' %}
  Enter a Resource Type and Resource Name.
{% endhint %}

{% hint style='info' %}
  Notice the Resource Type block has a <span class="btn btn-info btn-xs"><i class="fa fa-plus"> </i> Add Resource Type</span> button.  Click this button to enter another resource type in cases where the resource is in multiple formats such as "tabularDataset" and "map".
{% endhint %}

---

We are ready to save the metadata record.  The <span class="btn btn-xs btn-success">Save</span> button at the bottom of the panel should have become active and turned a darker shade of green.

{% hint style='working' %}
  Click the <span class="btn btn-success btn-xs">Save</span> button.
{% endhint %}

Wow! Now there's a lot more stuff on the screen. Let's spend a few minutes getting oriented before we enter more content into our new metadata record.
