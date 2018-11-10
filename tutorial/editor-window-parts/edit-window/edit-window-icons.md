# Tutorial -- Edit Window Icons
---

![Edit Window Icons](/assets/tutorial/edit-window-icons.png){caption}

### <i class="fa fa-asterisk required"> </i> Panel has Required Elements

The red asterisk after a panel name indicates that one or more of its elements is required in order to meet the minimal standard for a valid metadata record - or contact or dictionary depending on which record type you are editing.  

{% hint style='tip' %}
  The red asterisk is also used within panels to identify the specific elements that are required.  
{% endhint %}

Many <span class="md-window">Edit Window</span> panels permit multiple instances of a panel's data.  These instances will be referred to as "objects" throughout the documentation.  <span class="md-panel">Points Of Contact</span> and <span class="md-panel">Credits</span> are examples of repeating objects found in the <span class="md-window">Edit Window's</span> <span class="md-section">Main</span> section.  These array-type panels are easily identified by two characteristics: first, for inserting new objects they have an <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add</strong> button on the right side of the panel title bar; and second, following the panel name they have a colored circle with an inscribed number indicating how many objects have been entered. The color of the circle provides information about the optionality of the objects.  The colors and their meaning are explained below.

### ![](/assets/bullets/count-red.png) Object Required - none found 

A red circle with a 0 indicates that at least one object for this panel is required and none have yet been entered.  

### ![](/assets/bullets/count-orange.png) Object Optional - none found 

An orange circle with a 0 indicates that objects for this panel are optional and none have yet been entered.

### ![](/assets/bullets/count-blue.png) Number of Objects Found

A blue circle indicates that at least one object has been entered.  The number of objects entered is displayed inside the circle.  

{% hint style='info' %}
  Once an object has been added to an array panel, the red or orange circle will change to blue and the inscribed number will be greater than zero, so the optionality of the panel's objects is no longer obvious. 
{% endhint %}

### <span><strong class="fa fa-angle-down"> <strong class="fa fa-angle-up"> </span> Expand & Collapse Panel

Click an up arrow icon <strong class="fa fa-angle-up"> </strong> to collapse an open panel.  Or click the down arrow icon <i class="fa fa-angle-down"> </i> on a collapsed panel to reveal its contents. 

---

At the top of each <span class="md-window">Edit Window</span> section there is a title line indicating what is being edited.  For example, in the image above the title is "Editing *My First Metadata Record*".  Following this title several icons may be present.  These are identified below.

### ![](/assets/bullets/bang-red.png) Record Not Saved

An exclamation mark inscribed in a red circle indicates the record has unsaved changes.  The icon also acts as a <strong class="btn btn-success btn-xs"> <i class="fa fa-floppy-o"> </i> Save</strong> button.  Clicking the icon will save your data to browser cache.

### ![](/assets/bullets/bang-orange.png) Record Has Error(s)

An exclamation mark inscribed in an orange circle indicates the record has detectable errors.  Clicking the icon will display a list of the detected errors. 
