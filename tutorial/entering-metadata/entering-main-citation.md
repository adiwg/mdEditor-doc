# Entering Citations 
---

The <span class="md-panel">Citation</span> we are editing in this step is the citation for the primary subject of this metadata record, aka the "main resource."   

![Edit Window - Main - Main Resource Citation](/assets/get-started/edit-window-main-citation-1.png){caption}

As you can see, something is different with this panel. The <span class="md-panel">Citation</span> panel does not have any editable element controls.  Instead the panel is showing us a view of some the citation's elements.  Why is this?

A full metadata record can have many citations.  These will be scattered throughout the various <span class="md-window">Edit Window</span> sections and each will reference a different resource and/or context.  So you can expect to see <span class="md-panel">Citation</span> panels appear throughout mdEditor.  With that in mind, mdEditor's designers implemented a separate window for editing citations that is shared by all <span class="md-window">Edit Window</span> <span class="md-panel">Citation</span> panels.  Therefore, when editing a <span class="md-panel">Citation</span> object, you will leave the <span class="md-window">Edit Window</span> section you are on, edit the citation, then return to the <span class="md-window">Edit Window</span> section where you began. 

To edit the <span class="md-panel">Citation</span> object we just need to click the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> Edit</strong> button on the <span class="md-window">Panel Title Bar</span> or the one at the bottom of the <span class="md-panel">Citation</span> panel.  mdEditor will take you to the <span class="md-panel">Citation</span> editing window automatically, and bring you back when finished.  

{% hint style='info' %}
  <span class="md-panel">Citation</span> has only one required element in mdJSON, <span class="md-element">Title</span>.  Since the main resource <span class="md-panel">Citation</span> <span class="md-element">Title</span> is also the metadata record <span class="md-element">Title</span> and that has already been defined, technically there are no missing <span class="md-panel">Citation</span> elements.  We could skip editing <span class="md-panel">Citation</span> and still meet minimal requirements; however <span class="md-panel">Citation</span> is so widely used throughout mdEditor let's jump in and edit a non-required element.
{% endhint %}  

{% hint style='working' %}
  Edit the main resource <span class="md-panel">Citation</span>
  * Click either the <strong class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> Edit</strong> button on the <span class="md-window">Panel Title Bar</span> or the one at the bottom of the panel.
{% endhint %}

![Edit Window - Citation](/assets/get-started/edit-window-main-citation-2.png){caption}

You should now be looking at the <span class="md-section">Citation</span> edit window as shown in the above image.  Notice the <span class="md-window">Edit Window</span> title has changed from "Editing *My First Metadata Record*" to "Editing Citation"; also the path on the <span class="md-window">Breadcrumb Bar</span> confirms that you have navigated to the <span class="md-section">Citation</span> branch of the <span class="md-section">Main</span> <span class="md-window">Edit Window</span>.  

From working with <span class="md-panel">Resource Types</span> earlier in this exercise you are already familiar with the array-panel control used for entering <span class="md-element">Alternate Title</span> elements, so let's enter a few <span class="md-element">Alternate Titles</span> now.

{% hint style='working' %}
  Enter <span class="md-element">Alternate Titles</span>
  * Click either <strong class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Alternate Title</strong> button
  * Enter an <span class="md-element">Alternate Title</span>. I entered "First Alternate."
  * Enter a second <span class="md-element">Alternate Title</span>
  * Click the <strong class="btn btn-primary btn-xs"><i class="fa fa-arrow-left"> </i> Back to Main</strong> button in the <span class="md-window">Secondary Sidebar</span> when you have finish entering your <span class="md-element">Alternate Titles</span>.  
{% endhint %}

Clicking <strong class="btn btn-primary btn-xs"><i class="fa fa-arrow-left"> </i> Back to Main</strong> ends editing of the <span class="md-panel">Citation</span> object and, as expected, returns you to <span class="md-window">Edit Window</span> <span class="md-section">Main</span>.

{% hint style='tip' %}
  There are several other ways to return to <span class="md-window">Edit Window</span> <span class="md-section">Main</span>. 
  * Click <span class="md-section">Main</span> in the <span class="md-window">Breadcrumb Bar</span> path.
  * Click the browser's "back" button (you may also need to refresh the window before seeing your changes).
  * Click the <strong class="btn btn-warning btn-xs"> <i class="fa fa-pencil"> </i></strong> button for "My First Metadata Record" in the <span class="md-window">Primary Sidebar</span>.
   
  All three of these methods, as well as the <strong class="btn btn-primary btn-xs"><i class="fa fa-arrow-left"> </i> Back to Main</strong> button, will preserve your entries as you navigate away from the <span class="md-window">Edit Window</span> <span class="md-section">Citation</span> section.
{% endhint %}

So let's see what happened back in <span class="md-section">Main</span> ...
