# Tutorial -- Entering Dates and Times 
---

## Date Picker

![Edit Window - Date Picker](/assets/tutorial/edit-window-date-picker.png){caption}

### <span><strong class="fa fa-angle-double-left"> <strong class="fa fa-angle-double-right"></span> Previous Month / Next Month

These buttons decrement or increment the month by one.  

### Month Picker

If you need to jump backwards or forwards by more than a few months, click the "Month" button.  The control will display buttons for all the months of the current year.  Click the desired month.

But what if you need the month to be in a different year?  Notice that the "Month" button has now become a "Year" button.  The same rules will apply.  You can increment or decrement the year by one before selecting the correct year.  

Need to jump even farther back or ahead in time?  Click the "Year" button and a range of years is displayed and the "Year" button becomes a "Year-Range" button.  

### <i class="fa fa-clock-o"> </i> Time Picker

If you want to enter a time along with the date, click the <i class="fa fa-clock-o"> </i> at the bottom of the date-time control.  Refer to the "Time Picker" section below for how to use this control.

{% hint style='info' %}
  The <i class="fa fa-clock-o"> </i> will only appear on elements that support both a date and time.  Some elements only allow for a date.  
{% endhint %}

### <i class="fa fa-trash"> </i> Clear Date and Time

This button will clear both the date and time.

---

## Time Picker

![Edit Window - Time Picker](/assets/tutorial/edit-window-time-picker.png){caption}

### <i class="fa fa-calendar"> </i> Return to Calendar

This button returns control to the calendar.  The time displayed on the time control will be attached to the date upon exiting, even if none of the time buttons were touched while the time control was open.  

### Hours, Minutes, and Seconds 

Numbers inside the dashed rectangle represent the hours, minutes, and seconds.  These can be incremented or decremented using the up and down arrows.  The numbers are actually buttons themselves.  Click on the hour for instance, and a table of the 24 possible hours is displayed for you to select from.  Click on the minute or second buttons and numbers from 00 to 55 are displayed in increments of 5.  

### <span><strong class="fa fa-angle-up"> <strong class="fa fa-angle-down"></span> Increase / Decrease

These up and down arrows increment and decrement the hours, minutes, and seconds by one.  

### <i class="fa fa-trash"> </i> Clear Date and Time

This button will clear both the date and time, not just the time.

---

{% hint style='working' %}
  * Set a <span class="md-element">Start Date</span> and time for the main resource <span class="md-panel">Time Period</span>.
  * You can also set an <span class="md-element">End Date</span> and time if you like.
{% endhint %}

{% hint style='tip' %}
  Entering an <span class="md-element">End Date</span> that occurs before the <span class="md-element">Start Date</span> will be flagged as an error by mdEditor.  
{% endhint %}

We will cover the other elements of the <span class="md-panel">Time Period</span> object in a later section.  For now, we can rejoice in that we have completed our minimal mdJSON metadata record, and learned quite a bit about how mdEditor functions in the process.  Now it's time to see some of what we can do with it!

{% hint style='info' %}
  Date and time may be entered manually in a year, month, day, hour, minute, second string. Most delimiters are accepted by the control.  e.g. Entering "2014-03-15 10:45" is 10:45 a.m. on the Ides of March for 2014, as is "2014 03 15 10 45".
{% endhint %}
