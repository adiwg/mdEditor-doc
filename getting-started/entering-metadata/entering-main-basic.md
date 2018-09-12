# Entering Basic Information
---

![Editing Window - Main - Basic Information](/assets/get-started/edit-window-main-basic.png){caption}

To help focus on the <span class="md-panel">Basic Information</span> panel I isolated it by clicking the blue isolation dot ![](/assets/bullets/isolation-dot.png), this step is, of course, not required and totally your preference. 

As it turns out, all of the <span class="md-panel">Basic Information</span> elements are required.  So let's step through each of them. 

### Record ID <i class="fa fa-asterisk required" title="Required"> </i>

Let's skip editing the <span class="md-element">Record ID</span> for the moment.  Its value was assigned automatically when we created the record and we passed over an opportunity to change it at that time.  For this exercise, it's enough that there *is* a <span class="md-element">record id</span>.

{% hint style='danger' %}
  Use caution whenever changing any <span class="md-element">Record ID</span>!  In mdJSON records are related to each other through their IDs.  If any associations have be made between records, such as attaching contacts to records, changing an ID could cause the associations to be broken.
{% endhint %}

### Title <i class="fa fa-asterisk required" title="Required"> </i>

<span class="md-element">Title</span> was also entered when the new record was created.  We can, however, unlike <span class="md-element">record id</span>, change the <span class="md-element">title</span> without risk of breaking anything.  Change it now if you like.  Or leave it as is, I did. 
{% hint style='working' %}
   Change the record title.
{% endhint %}

{% hint style='info' %}
  Notice the <span class="md-panel">Citation</span> <span class="md-element">Title</span> is the same as the metadata record <span class="md-element">title</span>.  This is because the record title actually *is* the <span class="md-panel">Citation</span> <span class="md-element">title</span>. Changing one will always change the other.
{% endhint %}

### Status <i class="fa fa-asterisk required" title="Required"> </i>

The <span class="md-element">Status</span> element identifies the current status of the resource or project described by this metadata record.  The status is entered using a multi-select control.  Clicking on the control will produce a list of pre-loaded (and recommended) values for the <span class="md-element">status</span> element.  If none of these values work for you, just type in your own and press 'Enter' when done.  This type of control is used frequently throughout mdEditor.

{% hint style='danger' %}
  Avoid using spaces and other symbols when creating personal list items.  These can cause problems when translated into some metadata formats.
{% endhint %}

{% hint style='working' %}
  Enter a status for metadata resource
  * Choose 'complete' from the <span class="md-element">Status</span> control's list. 
  * Now add 'final' from the <span class="md-element">Status</span> control's list.  Both tags will show in the control's display.
  * After deciding these sound a bit redundant, click the 'x' on 'final' tag to drop it from the list. 
  * Add another status item not in the list.  Type 'releaseHold' in the status field and press enter.  A 'releaseHold' tag will appear alongside the 'completed' tag.
  * drop the 'releaseHold' tag also.
{% endhint %}

### Default Locale <i class="fa fa-asterisk required" title="Required"> </i>

Notice that <span class="md-panel">Default Locale</span> is actually a sub-panel, yes a panel in a panel!  This is another technique used throughout mdEditor.  <span class="md-panel">Default Locale</span> refers to the language, country, and encoding system of the metadata's resource.  Each of the elements (<span class="md-element">Language</span>, <span class="md-element">Country</span>, <span class="md-element">Encoding System</span>) is supported by a standard drop-down selection list that allows one value to be selected.  As with <span class="md-element">status</span> above, you can enter your own value if needed.  

For these three elements there are literally hundreds of values in the lists making it rather awkward to find what you need.  Further, the values themselves are short ISO standard codes whose meaning may not be immediately obvious.  Therefore, we attached descriptions to each item which are accessible by hovering over the dark-gray question mark ![](/assets/bullets/question-dark.png) next to the list item.  

The standard drop-down controls also support a search feature.  Click in the control and a search box will appear at the top of the list. Start typing what you are looking for and the list automatically refines to include only items that match you entry.  If nothing matches your search criteria just click 'Enter' and your custom entry will be accepted.

{% hint style='working' %}
  Change the country from 'United States' to 'Canada'.
  * Click in the country control
  * Type 'ca'
  * Hover over the question mark to next to 'CAN' to confirm it is indeed the code for Canada
  * Press 'Enter'
  * You can leave the leave the 'Language' and 'Character Set' as they are or change them if you like.
{% endhint %}
