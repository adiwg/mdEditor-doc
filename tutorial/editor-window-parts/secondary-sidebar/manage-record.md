# Tutorial -- Record Management
---

The <span class="md-window">Record Management</span> buttons provide a means of managing the movement of your currently active record between memory and browser cache.  

{% hint style='default' %}
  If you are unsure about the differences between memory, browser cache, and local storage please read the Getting Started Section "Before We Begin", again :).
{% endhint %} 

### <span class="btn btn-success btn-sm"> <i class="fa fa-floppy-o"> </i> Save</span> Save to Browser Cache

The 'Save' button will copy the active record in memory into browser cache. 

{% hint style='info' %}
  If the AutoSave option is set to 'On' the 'Save' button will be deactivated.  This is because all changes are automatically saved to browser cache for you, so there is nothing else to save!  This is the default mode and can be overridden on the 'Settings' panel.
{% endhint %} 

### <span class="btn btn-warning btn-sm"> <i class="fa fa-undo"> </i> Cancel</span> Cancel Unsaved Changes

The 'Cancel' button will undo all changes made to your active metadata record since the last 'Save', i.e. will reload the active record from browser cache into memory replacing any changes made since it was last saved.  

{% hint style='info' %}
  If the AutoSave option is set to 'On' the 'Cancel' button will be deactivated.  This is because all changes were automatically saved to browser cache for you; the record in memory and the browser cache are identical.
{% endhint %} 

### <span class="btn btn-info btn-sm"> <i class="fa fa-copy"> </i> Copy</span> Copy Record

Clicking 'Copy' will make a copy of the active record be it metadata, contact, or dictionary.  The copied record will be added to browser cache and displayed in the 'Create New Record' window to provide an opportunity to change the record name.

{% hint style='working' %}
  * Click 'Copy' for the current record.
  * Change the Record Title to My Second Metadata Record'
  * Click 'Save' - you are now editing the copied record.
  * Click 'Delete' - we don't need to save this record.
  * Click 'Confirm' - to complete the delete
  * The Dashboard for Metadata Records is displayed.  Click 'Edit' to return to editing 'My First Metadata Record'.
{% endhint %}

### <span class="btn btn-danger btn-sm"> <i class="fa fa-times"> </i> Delete</span> Delete Record

Delete will delete the active record from memory and browser cache.   Clicking 'Delete' will change the button to <span class="btn btn-danger btn-xs"> <i class="fa fa-question"> </i> Confirm</span> to give you a chance to reconsider or recover from an errant click. There is no 'Undo' for the delete function.