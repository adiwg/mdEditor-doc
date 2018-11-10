# Tutorial -- Clearing Browser Cache
---

Since we just exported our metadata records to local storage it stands to reason we should also be able to import metadata records into the mdEditor's browser cache. And we can.  

Exporting metadata records to local storage does not clear them from browser cache, they are still there.  To have a meaningful import exercise we should first clear the browser cache. 

{% hint style='danger' %}
  Although this is just an exercise built upon meaningless metadata, it is an essential practice to be sure you have exported all the data you wish to keep and that you know where you put it before clearing browser cache.  Have you?  And can you find it?
{% endhint %}

Time to clear browser cache ...

{% hint style='working' %}
  Open the <span class="md-window">Settings Window</span>.
  * Click the <i class="fa fa-cog"> </i> "Settings" button in the <span class="md-window">Primary Navigation Bar</span>.
{% endhint %}

![Settings Window](/assets/tutorial/settings-clear-cache.png){caption}

{% hint style='working' %}
  Clear browser cache.
  * Click the <span class="btn btn-danger btn-xs"> <i class="fa fa-times"> </i> Clear Storage Cache</span> button.
  * Confirm the delete of ALL records.
{% endhint %}

mdEditor will reset and when it restarts there will be no "Metadata Records", "Contacts", or "Dictionaries" found in browser cache.  This is verified by no records being indexed in the <span class="md-window">Primary Sidebar</span>.  Browser cache is empty.

{% hint style='info' %}
  Browser cache can also be emptied by functions built into every browser.  Where this function is found is browser dependent.  It is generally grouped with other tools that clear browser history and cookies.  Make it a practice of saving your metadata records to local storage regularly to avoid unintended loss.  
{% endhint %}

With browser cache now empty, let's reload our saved metadata records ...
