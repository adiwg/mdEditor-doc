# Entering Basic Information
---

![Editing Window - Main - Basic Information](/assets/get-started/edit-window-main-basic.png){caption}

To help focus on the 'Basic Information' panel I isolated it by clicking the blue isolation dot ![](/assets/bullets/isolation-dot.png), this step is, of course, not required and totally your preference. 

As it turns out, all of the 'Basic Information' elements are required.  So let's step through each of them. 

### Record ID <i class="fa fa-asterisk required" title="Required"></i>

Let's skip editing the 'Record ID' for the moment.  It has the value automatically assigned when we created the record and we passed over an opportunity to change it at that time.  For this exercise, it's enough that there *is* a 'Record ID'.

{% hint style='danger' %}
  Use caution whenever changing the 'Record ID'!  In mdJSON records are related to each other through their IDs.  If any associations have be made between records, such as attaching contacts or dictionaries, changing an ID could cause the associations to be broken.
{% endhint %}

### Title <i class="fa fa-asterisk required" title="Required"></i>

{% hint style='working' %}
  'Title' was also entered when the new record was created.  We can, however, unlike 'Record ID', change the 'Title' without risk of breaking anything.  Change it now if you like, or leave it as is.  
{% endhint %}

{% hint style='info' %}
  Notice the Citation 'Title' is the same as the metadata record 'Title'.  This is because the Citation 'Title' *is* the record 'Title'. Changing one will always change the other.
{% endhint %}

### Status <i class="fa fa-asterisk required" title="Required"></i>

The 'Status' element identifies the current status of the resource or project described by this metadata record.  The status is entered using a multi-select control.  Clicking on the control will produce a list of pre-loaded (and recommended) values for the 'Status' element.  If none of these values work for you, just type in your own and press 'enter' when done.  This type of control is used frequently throughout mdEditor.

{% hint style='danger' %}
  Avoid using spaces and other symbols when creating personal selection list items.  These can cause problems in some output metadata formats.
{% endhint %}

{% hint style='working' %}
  * Choose 'complete' and 'final' from the 'Status' control's list.  These two tags will show in the control's display.
  * After deciding these sound a bit redundant, click the 'x' on 'final' tag to drop it from the list. 
  * Add another status item not in the list.  Type 'releaseHold' in the status field and press enter.  A 'releaseHold' tag will appear along side the 'completed' tag.
  * drop the 'releaseHold' tag also.
{% endhint %}

### Default Locale <i class="fa fa-asterisk required" title="Required"></i>

Notice that 'Default Locale' is actually another panel, yes a panel in a panel!  This is another technique used throughout mdEditor.  'Default Locale' refers to the language and encoding system of the resource defined by this metadata record.  Each of the elements ('Language', 'Character Set', 'Country') is supported by a standard drop-down selection lists which allows only one value to be selected at a time.  As with 'Status' above, you can enter your own value if needed.  

For these three elements there are literally hundreds of values in the lists making it rather awkward to find what you need.  Further, the values themselves are the short ISO standard codes whose meaning may not be immediately obvious.  Therefore, we attached descriptions which are accessible by hovering over the dark-gray question mark ![](/assets/bullets/question-dark.png) next to the list item.  

The standard drop-down controls also supports a search feature.  Click in the control and a search box will appear at the top of the list. Start typing what you are looking for and the list automatically refines to include only items that match you entry.  If nothing matches your search criteria just click 'enter' and it is accepted as your custom entry.

{% hint style='working' %}
  Change the country from United States to Canada.
  * Click in the country control
  * Type 'ca'
  * Hover over the question mark to next to 'CAN' to confirm it is indeed the code for Canada
  * Press 'Enter'
  * You can leave the leave the 'Language' and 'Character Set' as they are or change them if you like
{% endhint %}
