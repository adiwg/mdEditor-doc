# Reference -- Contact Records
---

In mdEditor, <span class="md-panel">Contacts</span> are maintained separately from <span class="md-panel">Metadata Records</span> and <span class="md-panel">Dictionaries</span>.  This object or normalized approach allows a <span class="md-panel">Contact</span> object's information to be used many time across a single <span class="md-panel">Metadata Record</span> or even by multiple <span class="md-panel">Metadata Records</span> without reentering the contact's information.  Instead of entering contact information in a <span class="md-panel">Metadata Records</span>, mdEditor places a simple reference to the <span class="md-panel">Contact</span> object.  When the <span class="md-panel">Metadata Records</span> are translated into final output format, mdTranslator will distribute the <span class="md-panel">Contact</span> object's information according to the selected standard's rule set.  

{% hint style='tip' %}
  With a little planning you can build a reusable library of <span class="md-panel">Contact</span> objects to use across many <span class="md-panel">Metadata Records</span>.
{% endhint %} 

![Contact Edit Window](/assets/reference/edit-objects/contact/contact.png){caption}

 * To open a <span class="md-panel">Contact</span> object for editing, either create a new <span class="md-panel">Contact</span> by clicking the <span class="btn btn-primary btn-xs"> <i class="fa fa-plus"> </i></span> button or open an existing <span class="md-panel">Contact</span> by clicking it's <span class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i></span> button in the <span class="md-window">Primary Sidebar</span>. 
 
   {% hint style='info' %}
 The <span class="md-panel">Contact</span>'s <span class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i></span> button does not need to be green to edit.  A <span class="md-panel">Contact</span> object can be edited in any state of completeness.
   {% endhint %}
   
 * The <span class="md-panel">Contact</span>'s name is displayed at the top of the <span class="md-window">Edit Window</span>.
 
 * The <span class="md-window">Edit Window</span> opens with all panels closed.  There is a small <span class="btn btn-default btn-xs">Show</span> button in the <span class="md-window">Bread Crumb Bar</span> that will open a view with all the <span class="md-panel">Contact</span> object's information. This may be helpful to determine if you have selected the correct contact for editing.  

---
