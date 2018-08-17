# Entering Basic Information
---

![Editing Window - Main - Basic Information](/assets/get-started/edit-window-main-basic.png){caption}

I isolated the 'Basic Information' panel by clicking the isolation dot ![](/assets/bullets/isolation-dot.png) to help the panel stand out from the rest of the window, this step is totally your preference. 

As it turns out, ll the elements of the 'Basic Information' panel are required.  So we will step through each of them. 

### Record ID

Let's skip editing the 'Record ID' for the moment.  This one was assigned automatically when we first created the new record and we had an opportunity to change it at that time.  For now, it is enough that there *is* a 'Record ID'.

{% hint style='danger' %}
  Use caution whenever changing a 'Record ID'.  In mdJSON records are related to each other using their IDs.  If any associations have be made between records, such as attaching contacts or dictionaries, changing an ID could cause the association to be broken.
{% endhint %}

### Title

{% hint style='working' %}
  'Title' was entered when the new record was created.  We can, however, unlike 'Record ID', change the 'Title' without risk of breaking any associations.  Change it now if you like, or leave it as is.  
{% endhint %}

{% hint style='info' %}
  Notice the Citation 'Title' is the same as the metadata record 'Title'.  Yes, these two are the identical and will be kept in sync.  Changing one will always change the other.
{% endhint %}

### Status

The 'Status' element identifies the current status of the resource or project defined by this metadata record.  The status is entered using a multi-select control.  Click on the control and a list of pre-loaded (and recommended) values for 'Status' will pop up.  If none of these values work for you, just type in your own.  This type of control is used frequently throughout mdEditor.

{% hint style='working' %}
  * Choose 'complete' and 'final' from the 'Status' control's list.  These two tags will show in the control's display.
  * After deciding these sound a bit redundant, click the 'x' on 'final' tag to drop it from the list. 
  * Add another status item not in the list.  Type 'releaseHold' in the status field and press enter.  A 'releaseHold' tag will appear along side the 'completed' tag.
{% endhint %}

{% hint style='danger' %}
  Avoid using spaces and other symbols when creating selection list items.  These can cause problems in some output metadata formats.
{% endhint %}

### Default Locale

The 'Default Locale' is a panel, a panel in a panel!  This is another technique used throughout mdEditor.  'Default Locale' refers to the language and encoding of the resource defined by this metadata record.  Each of the elements ('Language', 'Character Set', 'Country') is supported by a standard drop-down selection lists which allows only one value to be selected at a time.  As with 'Status' above, you can enter your own value if needed.  

For these three elements there are literally hundreds of values in the lists making it awkward to find what you need.  Further, the values are short, ISO standard codes whose meaning may not be immediately obvious.  Therefore, we attached descriptions which are accessible by hovering over the dark-gray question mark ![](/assets/bullets/question-dark.png) next to the list item.  

The standard drop-down controls also support a search feature.  Start typing what you are looking for and the list automatically refines itself to include only items that match the search criteria. 

{% hint style='working' %}
  Change the country from United States to Canada.
  * Click in the country control
  * Type 'ca'
  * Hover over the question mark to next to 'CAN' to confirm you are selection Canada
  * Press 'Enter'
{% endhint %}
