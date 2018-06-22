# Add a New Metadata Record

---

<!-- tasks -->

1. ## Create a New Record
Click the plus  <span class="btn btn-sm btn-primary"><i class="fa fa-plus"></i></span> button on the left menu-bar next to '*Metadata Records*' to create a new metadata record.  The same behavior applies to 'Contacts' and 'Dictionaries' which we will create later.  For now just add a new metadata record.

  ![Adding a new record](/assets/get-started/add-record.png){caption}

  You should see something like this ...

  ![The newly created, unsaved record](/assets/get-started/new-record.png){caption}

  The 'Create New Record' form collects the minimal information mdEditor requires to save a new metadata record.  This minimal information is, of course, not sufficient to meet the minimum of any metadata standard, but just enough that you and mdEditor can find it for editing.

1. ## Record ID <i class="fa fa-star required" title="Required"></i>
  Notice that mdEditor has filled in a Record ID for you.  By default mdEditor assigns a [UUID](https://tools.ietf.org/html/rfc4122) (Universally Unique Identifier) as the Record ID.

  {% hint style='info' %}
  You may change the record identifier later if you like; but it must be unique among all your metadata records otherwise there may be some confusion later on when using more advanced mdEditor features or publishing the metadata.  If you have a reliable record identification system, use it, otherwise best to keep the UUID.
  {% endhint %}

1. ## Record Title <i class="fa fa-star required" title="Required"></i>
    This is the name you assign to the main resource described by this metadata record.  In addition to becoming part of your metadata record, the name will be used in the left side-bar to identify your record .

  {% hint style='working' %}
  Enter your Record Title.
  {% endhint %}

  {% hint style='info' %}
  Notice the record title appears in the left side-bar as you type the name in the edit panel.  The left side-bar is where you may find and gain access to this record when you want to continue editing.
  {% endhint %}

1. ## Resource Types <i class="fa fa-star required" title="Required"></i>
Choose a resource type for the main resource described by this metadata record.  You may optionally provide a name for the resource.

  {% hint style='working' %}
  Enter a Resource Type and Resource Name.
  {% endhint %}

  {% hint style='info' %}
  Notice the Resource Type block has a <span class="btn btn-info btn-sm"><i class="fa fa-plus"></i> Add Resource Type</span> button.  Click this button to enter another resource type in cases where the resource is in multiple formats such as 'tabularDataset' and 'map'.
  {% endhint %}

1. ## Save the Record
We are ready to save the metadata record.  The <span class="btn btn-sm btn-success">Save</span> button at the bottom of the panel should have become active and turned a darker shade of green.

  {% hint style='working' %}
  Click the <span class="btn btn-success">Save</span> button.
  {% endhint %}

<!-- endtasks -->

Wow! Now there's a lot more stuff on the screen. Let's spend a few minutes getting oriented before we enter more content into our new metadata record.
