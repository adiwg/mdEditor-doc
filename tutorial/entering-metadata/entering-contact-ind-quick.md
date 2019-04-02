# Tutorial -- Add a Quick Individual Contact 
---

If you haven't already done so, click the plus sign next to Contacts on the <span class="md-window">Primary Sidebar</span> to create a new contact.  Your screen should look similar to the image below.

![Create New Contact Window](/assets/tutorial/new-contact-ind-1.png){caption}

{% hint style='info' %}
  In mdJSON, contacts are maintained separately from metadata records and dictionaries.  No information about a contact is ever entered in a metadata record.  This important feature allows contacts to be reused multiple times within a single metadata record or across multiple metadata records without the necessity of reentering the contact's information each time the contact is referenced.  Or worse yet, trying to remember all the places a contact's data needs to be edited when information changes.  Whenever a contact is needed for a metadata or dictionary record you will simply select the appropriate contact(s) from a list and mdEditor and mdTranslator will gather up all the pertinent information from the contact record for you - simple!  
{% endhint %}

The "Create New Contact" window has three standard text controls and something new.  On this window <span class="md-element">Contact Type</span> is entered via a switch control ![](/assets/bullets/switch-left.png).  Clicking the control will move the switch indicator to the right ![](/assets/bullets/switch-right.png) and change <span class="md-element">contact type</span> from "Individual" to "Organization".  Click it again and the original state is restored.  

{% hint style='working' %}
  * Click the switch control to change <span class="md-element">Contact Type</span> to "Organization"
  * Click the control again to change <span class="md-element">Contact Type</span> back to "Individual"
{% endhint %} 

{% hint style='tip' %}
  Notice that when you change the <span class="md-element">Contact Type</span> from "Individual" to "Organization" the icon in the <span class="md-window">Primary Sidebar</span> changes from a single person <i class="fa fa-user"> </i> to a group <i class="fa fa-users"> </i>.  
{% endhint %}

{% hint style='info' %}
  Once you have saved your contact, you cannot switch the <span class="md-element">Contact Type</span> from "Individual" to "Organization" or vice versa so be careful to select the correct option when you create the contact.
{% endhint %} 

## Individual Contact

An "Individual" contact record collects pertinent contact information for a person including a name, address, phone numbers, email addresses, etc.  There are three required elements: <span class="md-element">Contact ID</span>, <span class="md-element">Name</span>, and <span class="md-element">Position Name</span>.

### Contact ID <i class="fa fa-asterisk required" title="Required"> </i>

Each contact is assigned a unique ID.  This is the ID used to link this contact with one or more of your metadata and dictionary records.  When you create a new contact record a UUID is assigned to <span class="md-element">Contact ID</span> automatically.  However, if you prefer to use your own system for contact IDs, this would be the best time and place to change the ID. 

### Name <i class="fa fa-asterisk required" title="Required"> </i>

<span class="md-element">Name</span> is the full name of the individual.  

{% hint style='info' %}
  In mdJSON names are not partitioned into first, middle, last, etc.  There is only one name, so include all the parts you want to see in your records including any prefix or suffix.
{% endhint %} 

### Position Name <i class="fa fa-asterisk required" title="Required"> </i>

<span class="md-element">Position Name</span> is the position or official title the individual may hold. 

{% hint style='working' %}
  Create an 'Individual' contact record
  * Enter "CID001" as the <span class="md-element">Contact ID</span>
  * Enter your name in <span class="md-element">Name</span>
  * Enter your position or title in <span class="md-element">Position Name</span>
  * Click <strong><span class="btn btn-success btn-xs"> <i class="fa fa-floppy-o"> </i> Save</span></strong>.
{% endhint %}

{% hint style='info' %}
  You probably noticed that when you entered your name in the <span class="md-element">Name</span> element the <span class="md-element">Position Name</span> element suddenly became optional.  The same would be true of <span class="md-element">Name</span> if you entered the <span class="md-element">Position Name</span> first.  This is because one or the other is required, but not both.  
{% endhint %}

![Create New Contact Window](/assets/tutorial/new-contact-ind-2.png){caption}

After clicking <strong><span class="btn btn-success btn-xs"> <i class="fa fa-floppy-o"> </i> Save</span></strong> you are transferred to the mdEditor window for contact records.  Notice that the individual contact you just entered is colored green in the <span class="md-window">Primary Sidebar</span>.  This is because the record is clean!  There are no additional required elements.  To be sure, there are still a lot of contact elements that can be entered to further define our contact, but what we have is sufficient to return to editing our metadata record.  

Although we could return to entering metadata, let's add another contact first.  This time we will make an "Organization" contact. 
