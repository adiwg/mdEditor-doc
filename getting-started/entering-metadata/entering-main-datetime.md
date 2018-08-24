# Entering Time Periods 
---

{% hint style='working' %}
  Navigate to the 'Main' Edit Window section
  * Click 'Main' on the Secondary Navigation bar
  * Open the 'Time Period' panel
{% endhint %}

![Editing Window - Main - Time Period](/assets/get-started/edit-window-main-time-1.png){caption}

{% hint style='info' %}
  Notice that there are required elements on the 'Time Period' panel that we have not entered and yet no errors telling us our metadata record is incomplete.  Also notice that there is no <i class="fa fa-asterisk required" title="Required"></i> on the panel title bar following the panel's title.  What's up? 
  
  When there is a <i class="fa fa-asterisk required" title="Required"></i> on the panel title bar, it means that one or more elements of the panel are always required for a valid record.  When the red asterisk is absent from the panel title bar the panel's required elements are only required when the panel's object is included in the metadata record.  In this instance, a 'Time Period' object is not required for a valid metadata record; however, if one is included, 'Dates' become required. 
{% endhint %}

### Dates  <i class="fa fa-asterisk required" title="Required"></i>

The resource 'Time Period' specifies the date-time range of the data resource or project described by the metadata record.  The period must define a starting, ending date, or both; but only one is required.  

Start the exercise by adding an optional 'Description' element to the 'Time Period'.

{% hint style='working' %}
  Add a 'Time Period' 'Description'
  * Enter a text string in the 'Description' element of the 'Time Period' object.
{% endhint %}

{% hint style='info' %}
  Typing the 'Description' - or any other element - in the 'Time Period' panel caused mdEditor to create a new 'Time Period' object.  Validation took place immediately.  Notice the ![](/assets/bullets/bang-orange.png) has returned in the window title and the record name in the Primary Sidebar is once again orange.  We now have missing required elements.  
{% endhint %}

{% hint style='working' %}
  Enter the 'Time Period' 'Start Date'
  * Click the calendar <span class="btn btn-default btn-xs"> <i class="fa fa-calendar"></i></span> button on the 'Start Date' control
  * Choose the desired date. 
{% endhint %}

As you have just experienced, there are lots of options connected to the date and time picker controls.  Those will be discussed on the next page ...
