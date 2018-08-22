# Add a Quick Individual Contact 
---

If you haven't already done so, click the plus sign next to 'Contacts' on the 'Primary Sidebar' to create a new contact.  Your screen should look similar to the image below.

![Create New Contact Window](/assets/get-started/new-contact-ind-1.png){caption}

{% hint style='info' %}
  In mdJSON, contacts are maintained separately from metadata records and dictionaries.  No contact information is ever entered in a metadata record in mdEditor.  This important feature allows you to reuse the contacts multiple times within a single metadata record or on multiple metadata records without the necessity of reentering his/her data each time the contact is referenced.  Whenever a contact is needed for a metadata or dictionary record you will simply select the appropriate contact(s) from a list and mdEditor and mdTranslator will gather up all the pertinent information from the contact record for you, simple!  
{% endhint %}

The 'Create New Contact' window has three standard text elements and something new.  On this window 'Contact Type' is entered via a switch control ![](/assets/bullets/switch-left.png).  Clicking the control will move the switch indicator to the right ![](/assets/bullets/switch-right.png) and change the 'Contact Type' from 'Individual' to 'Organization'.  Click it again and the original state is restored.  

{% hint style='working' %}
  * Click the switch control to change the 'Contact Type' to 'Organization'
  * Click the control again to change 'Contact Type' back to 'Individual'
{% endhint %} 

{% hint style='tip' %}
  Notice that when you change the 'Contact Type' from 'Individual' to 'Organization' the icon in the 'Primary Sidebar' changes from a single person to a group.  
{% endhint %}

## Individual Contact

An 'Individual' contact record collects all pertinent contact information for a person such as name, address, phone numbers, email addresses, etc.  There are three required elements: 'Contact ID', 'Name', and 'Position Name'.

### Contact ID <i class="fa fa-asterisk required" title="Required"></i>

Each contact is assigned a unique ID.  This is the ID used to link this contact with one of more of your metadata and dictionary records.  When you create a new contact record a UUID is assigned to 'Contact ID' automatically.  However, if you prefer to use your own system for contact IDs, this would be the best time and place to change the ID. 

### Name <i class="fa fa-asterisk required" title="Required"></i>

'Name' is the full name of the individual.  

{% hint style='info' %}
  In mdJSON names are not partitioned into first, middle, last, etc.  There is only one name, so include all the parts you want to see in your records including any prefix or suffix.
{% endhint %} 

### Position Name <i class="fa fa-asterisk required" title="Required"></i>

'Position Name' is the position or office title the individual may hold. 

{% hint style='working' %}
  Create an 'Individual' contact record
  * Enter 'CID001' as the 'Contact ID'
  * Enter your name in 'Name'
  * Enter your position or title in 'Position Name'
  * Click 'Save'.
{% endhint %}

{% hint style='info' %}
  You probably noticed that when you entered your name in the 'Name' element the 'Position Name' element suddenly became optional.  The same would be true of 'Name' if you entered the 'Position Name' first.  This is because one or the other is required, but not both.  
{% endhint %}

![Create New Contact Window](/assets/get-started/new-contact-ind-2.png){caption}

After clicking 'Save' you are transferred to the mdEditor window for contact records.  Notice that the individual contact your just enter is colored green in the 'Primary Sidebar'.  This is because the record is clean!  There are no additional required elements.  To be sure, there are still a lot of contact elements that can be entered to further define our contact, but what we have is sufficient to return to editing our metadata record.  

Although we could return to entering metadata, let's add another contact first just so we have a few.  This time we will make it an 'Organization' contact. 
