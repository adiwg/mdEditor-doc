# Entering Resource Types 
---

![Editing Window - Main - Resource Types](/assets/get-started/edit-window-main-resource-1.png){caption}

As you can see, not all panels have the isolation capability.  In general, this feature was not added to panels with only a few elements and 'Resource Types' has only a single element.  

However, this single element is an *object* which has several elements of its own.  This is our first encounter with an *array panel*; a panel that supports multiple objects of the same type.  So to get started we naturally need to 'Add' an object.

{% hint style='working' %}
  Add a 'Resource Type' object to the array.
  * Click the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"></i> Add</strong> button to 'Add' a new object to the array.
{% endhint %}

The two elements of the 'Resource Type' are now created and ready for you to edit.  Notice that the first of these, 'Type' is required and the second, 'Name' is optional.  

{% hint style='info' %}
  The control for 'Type' uses a ![](/assets/bullets/bang-red.png) to indicate a required field rather than the red asterisk used used elsewhere in mdEditor.  This is a feature of the control library used by mdEditor and not something we can easily change.  Sorry for the inconvenience. 
{% endhint %}

{% hint style='tip' %}
  The ![](/assets/bullets/count-red.png) on the panel title bar has changed to ![](/assets/bullets/count-blue.png) indicated the panel array now has one object.  Note that the object is counted even though the object is not meeting the standard for a valid object, in this case required elements are missing.  The count counts ALL objects, not just valid objects!
{% endhint %}

![Editing Window - Main - Resource Type new object](/assets/get-started/edit-window-main-resource-2.png){caption}

### Type <i class="fa fa-asterisk required" title="Required"></i>

'Type' is the type of resource described by this metadata record and is required.  Clicking on the 'Type' control will pop-up a list for you to select one of the standard types or allow you to create a custom resource type should it be needed.

{% hint style='working' %}
  Enter 'Type' of 'tabularDataset'
{% endhint %}

{% hint style='tip' %}
  Notice that when you assigned the 'Resource Type' the icon preceding the record name in the 'Primary Sidebar' changes.  In this instance it changes to a table or grid to represent a tabular dataset.  Most 'Resource Type' are assigned an icon; although some may require a little imagination to visualize the association.  The icons are provided to help jog your mind when scanning a long list of records or contacts you may not have worked with in a while.  
{% endhint %}

### Name 
'Name' is an optional element that provide a name for resource referred to by 'Type'.  

{% hint style='working' %}
  Enter 'Name' as "My Dataset Name" (or anything else you like)
{% endhint %}

{% hint style='tip' %}
  'Name' is optional and a little redundant if only one resource type is described by the metadata record.  In such cases the metadata record 'Resource Type Name' would likely overlap with the 'Record Title'('Citation Title').  However, when a resource is prepared in multiple forms or multiple resources are defined by the metadata record, 'Resource Type Name' can be helpful.
{% endhint %}

{% hint style='working' %}
  Add a second 'Resource Type' object to the panel.  We don't need the second object for this exercise, we just want to observe mdEditor behavior.
  * click the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"></i> Add</strong> button again
  * fill in the new object
  * click the <strong class="btn btn-danger btn-xs"> <i class="fa fa-times"></i> Delete</strong> button next to the newly created object. 
{% endhint %}

![Editing Window - Main - Resource Type complete object](/assets/get-started/edit-window-main-resource-3.png){caption}
