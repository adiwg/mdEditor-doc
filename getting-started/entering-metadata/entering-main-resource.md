# Entering Resource Types 
---

![Editing Window - Main - Resource Types](/assets/get-started/edit-window-main-resource-1.png){caption}

As you can see, not all panels have the isolation capability.  In general, this feature was not added to panels with just a few elements. <span class="md-panel">Resource Types</span> has only a single element.  

However, this single element is an *object* that has several elements of its own.  This is our first encounter with an *array-panel*; a panel that supports multiple objects of the same type.  So to get started, we need to 'Add' an object.

{% hint style='working' %}
  Add a <span class="md-panel">Resource Type</span> object to the array.
  * Click the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add</strong> button to add a new object to the array.
{% endhint %}

A <span class="md-panel">Resource Type</span> object with its two elements was created and is ready for you to edit.  Notice that the first of these, <span class="md-element">type</span> is required and the second, <span class="md-element">name</span> is optional.  

{% hint style='info' %}
  Notice that the control for the <span class="md-element">type</span> element uses a ![](/assets/bullets/bang-red.png) to indicate the element is required rather than the red asterisk used by mdEditor.  This is a feature of the control software library used by mdEditor and not something we can easily change.  Sorry for any confusion. 
{% endhint %}

{% hint style='tip' %}
  The ![](/assets/bullets/count-red.png) on the <span class="md-window">Panel Title Bar</span> has changed to ![](/assets/bullets/count-blue.png) indicating the array-panel now has one object.  Note that the object is counted even though the object is not meeting the standard for a valid object. In this case the required element <span class="md-element">type</span> is missing.  The count includes ALL objects, not just valid objects!
{% endhint %}

![Editing Window - Main - Resource Type new object](/assets/get-started/edit-window-main-resource-2.png){caption}

### Type <i class="fa fa-asterisk required" title="Required"> </i>

<span class="md-element">type</span> is the type of resource described by this metadata record.  Clicking on the <span class="md-element">type</span> control will pop up a list for you to select one of the standard resource types or allow you to create a custom resource type.

{% hint style='working' %}
  Enter a <span class="md-element">type</span> of 'tabularDataset'
{% endhint %}

{% hint style='tip' %}
  Notice that when you assigned or change the resource <span class="md-element">type</span>, the icon preceding the record name in the <span class="md-window">Primary Sidebar</span> also changes.  In this instance it changes to a table or grid <i class="fa fa-table"> </i> to represent a tabular dataset.  Most resource types are assigned an icon; although some may require a little imagination to visualize the association.  The icons are provided to help jog your mind when scanning lists of records or contacts you may not have seen in a while.  
{% endhint %}

### Name 
<span class="md-element">name</span> is an optional element that provides a name for resource referred to by <span class="md-element">type</span>.  

{% hint style='working' %}
  Enter <span class="md-element">name</span> as "My Dataset Name" (or anything else you like).
{% endhint %}

{% hint style='tip' %}
  <span class="md-element">name</span> is optional and may seem a little redundant if only one resource type is described by the metadata record.  In such cases the metadata record <span class="md-element">name</span> might overlap with the <span class="md-panel">Citation</span> <span class="md-element">title</span>.  However, when a resource is prepared in multiple formats or multiple resources are combined under a single metadata record, <span class="md-element">name</span> can be helpful.
{% endhint %}

{% hint style='working' %}
  Add a second <span class="md-panel">Resource Type</span> object to the panel.  We don't need the second object to fulfill the minimum metadata requirement, this is just to observe mdEditor behavior.
  * click the <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add</strong> button
  * fill in the new object
  * click the <strong class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Delete</strong> button next to the newly created object. 
{% endhint %}

![Editing Window - Main - Resource Type complete object](/assets/get-started/edit-window-main-resource-3.png){caption}