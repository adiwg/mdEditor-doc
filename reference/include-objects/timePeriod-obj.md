![Time Period Panel](/assets/reference/edit-objects/metadata/main/timePeriod-main.png)

* <span class="md-element">Dates</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: collection}1 - A collection of elements to select and set the <span class="md-element">Start Date</span> and <span class="md-element">End Date</span> of a <span class="md-panel">Time Period</span>. 

* <span class="md-element">Start Date</span> <i class="fa fa-asterisk required" title="Required"></i> 1{**type**: date, datetime (ISO 8601); **default**: empty}1 Starting date and time of the <span class="md-panel">Time Period</span>.  <span class="md-element">Start Date</span> is not required if <span class="md-element">End Date</span> is present. 
  
* <span class="md-element">End Date</span> <i class="fa fa-asterisk required" title="Required"></i>1{**type**: date, datetime (ISO 8601); **default**: empty}1 Ending date and time of the <span class="md-panel">Time Period</span>.  <span class="md-element">End Date</span> is not required if <span class="md-element">Start Date</span> is present.  
 
* <span class="btn btn-primary btn-xs">Pick a Fiscal Year</span> Use this select control to set both the <span class="md-element">Start Date</span> and <span class="md-element">End Date</span> of a fiscal year.  To set both dates for a fiscal year use the control to select the desired starting year.  The <span class="md-element">Start Date</span> will be set to the first day of the month for the fiscal year and the <span class="md-element">End Date</span> will be the last day of the month twelve months later. The default starting month for the fiscal year is October.  The starting month can be changed on the Settings page and will used by mdEditor for all <span class="md-panel">Time Period</span> objects until changed.  Previously defined fiscal years will not be effected.

  See [Date-Time Control](../edit-window/controls/dateTime-control.md) for details on picking dates and times using the Date-Time control.

* <span class="md-element">Identifier</span> 1{**type**: string; **max length**: none; **default**: empty}1 - A unique identifier for this <span class="md-panel">Time Period</span>.  

  The identifier must be alphanumeric and not include special characters.  It need only be unique within the metadata record. 
  
  {% hint style='info' %}
  ISO metadata records require time period IDs.  If one is provided here it will be used by mdTranslator when writing ISO metadata.  If the <span class="md-element">Identifier</span> is left blank mdTranslator will generate a unique identifier for the <span class="md-panel">Time Period</span>.  Note that the generated time period ID may not be consistent across multiple translations by mdTranslator.
  {% endhint %}

* <span class="md-element">Description</span> 1{**type**: string; **max length**: none; **default**: empty}1 A brief description of any relevant information for this <span class="md-panel">Time Period</span>.  

* <span class="md-element">Time Period Names</span> 1{**type**: array (string); **max length**: none; **default**: empty}1 - An array of user-assigned names for this time period.  Each name is a character string.

* <span class="md-element">Interval</span> 1{**type**: object (<span class="md-panel">Time Interval</span>); **default**: empty}1 An object to specify a time interval for the resource.  2{[See object details](#time-interval-object)}2

* <span class="md-element">Duration</span> 1{**type**: object (<span class="md-panel">Time Duration</span>); **default**: empty}1 An object to specify a time duration for the resource. 2{[See object details](#time-duration-object)}2

---

{% include "../include-objects/timeInterval-obj.md" %}
  
---
 
{% include "../include-objects/timeDuration-obj.md" %}
