# Tutorial -- Entering Time Periods 

{% hint style='working' %}
  Navigate to the <span class="md-window">Edit Window</span> <span class="md-section">Main</span>
  * Click <span class="md-section">Main</span> on the <span class="md-window">Secondary Navigation Bar</span>
  * Open the <span class="md-panel">Time Period</span> panel
{% endhint %}

![Edit Window - Main - Time Period](/assets/tutorial/edit-window-main-time-1.png){caption}

{% hint style='info' %}
  Notice that there are required elements on the <span class="md-panel">Time Period</span> panel that we have not entered and yet there are no errors telling us our metadata record is incomplete.  Also notice that there is no <i class="fa fa-asterisk required" title="Required"> </i> on the <span class="md-window">Panel Title Bar</span> following the panel's title.  What's up? 
  
  When a <i class="fa fa-asterisk required" title="Required"> </i> is on the <span class="md-window">Panel Title Bar</span>, it means that one or more elements of the panel are *always* required for a valid record.  When the red asterisk is absent from the <span class="md-window">Panel Title Bar</span>, the panel's required elements are only required when the panel's object is included in the metadata record.  Therefore the panel's icons are informing us a <span class="md-panel">Time Period</span> object is not required for a valid metadata record; however, if a <span class="md-panel">Time Period</span> is included, <span class="md-element">Dates</span> will be required. 
{% endhint %}

### Dates  <i class="fa fa-asterisk required" title="Required"> </i>

The main resource <span class="md-panel">Time Period</span> specifies a date-time range for the data resource or project described by the metadata record.  The <span class="md-panel">Time Period</span> must have a <span class="md-element">Start Date</span>, <span class="md-element">End Date</span>, or both.  

Continue the exercise by first entering the optional <span class="md-element">Description</span> element for <span class="md-panel">Time Period</span>.

{% hint style='working' %}
  Add a <span class="md-panel">Time Period</span> <span class="md-element">Description</span>
  * Enter a text string in the <span class="md-element">Description</span> element of the <span class="md-panel">Time Period</span> object.
{% endhint %}

{% hint style='info' %}
  Typing the <span class="md-element">Description</span> - or any other element - in the <span class="md-panel">Time Period</span> panel caused mdEditor to create a new <span class="md-panel">Time Period</span> object.  Validation took place immediately.  Notice the ![](/assets/bullets/bang-orange.png) has returned to the window title and the record name in the <span class="md-window">Primary Sidebar</span> is once again orange indicating missing elements are required.  
{% endhint %}

{% hint style='working' %}
  Enter the <span class="md-panel">Time Period</span> <span class="md-element">Start Date</span>
  * Click the calendar <span class="btn btn-default btn-xs"> <i class="fa fa-calendar"> </i></span> button on the <span class="md-element">Start Date</span> control
  * Choose the desired date. 
{% endhint %}

As you have just experienced, there are lots of options connected with the date and time picker controls.  Let's go through these on the next page ...
