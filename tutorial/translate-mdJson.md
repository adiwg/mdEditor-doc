# Tutorial -- Translate a Metadata Record
---

Now that we have entered our minimal mdJSON metadata record let's see how easy it is to translate the record into other metadata formats.  With mdEditor open on the metadata record you wish to translate - in this example "My First Metadata Record" -  click the "Translate" button in the <span class="md-window">Primary Navigation Bar</span>.  This will take you to the Translate Record window show below.

![Translate Record Window](/assets/tutorial/translate-mdjson-1.png){caption}

{% hint style='info' %}
  The "Translate" button on the <span class="md-window">Primary Navigation Bar</span> is only accessible when you have a metadata record open in mdEditor; and the open record is the one that will be translated. 
{% endhint %}

{% hint style='tip' %}
  You can verify which metadata record will be translated by checking the name of the record in the <span class="md-window">Breadcrumb Bar</span> path.
{% endhint %}

As you can see there are few controls on this page since translating from mdJSON to other formats is pretty straightforward.  Let's try it now. 

{% hint style='working' %}
  Translate "My First Metadata Record" to HTML
  * Choose "HTML" from the <span class="md-element">Choose Format</span> control
  * Click the <span class="btn btn-primary btn-xs"> <i class="fa fa-retweet"> </i> Translate</span> button.
{% endhint %}

{% hint style='info' %}
  Translation may take a minute or two.  The mdTranslator is hosted by a website that swaps mdTranslator out of memory when it is not being actively used.  If it was swapped out you may need to wait while mdTranslator is loaded again before it runs your task. 
{% endhint %}

That's about all there is to it!

When you click <span class="btn btn-primary btn-xs"> <i class="fa fa-retweet"> </i> Translate</span> button, the mdJSON record being edited in mdEditor (the record in memory) will be packaged up and sent to mdTranslator for translation into the format you requested, in this case "HTML".  The "Translate Record" window will then wait for a response from mdTranslator and display the result in a small <span class="md-panel">Result</span> preview panel as shown in the image below. 

![Translate Record Window - Preview Window](/assets/tutorial/translate-mdjson-2.png){caption}

The <span class="md-panel">Result</span> preview panel is pretty small for viewing your record comfortably.  You can expand this into a full window by clicking the expand window button in the upper-right corner of the <span class="md-panel">Result</span> preview panel. 

{% hint style='working' %}
  Expand the <span class="md-panel">Result</span> preview panel to full size.
  * Click the expand window button in the upper-right corner of the <span class="md-panel">Result</span> preview panel.
  * Search the window for all the metadata you entered. 
  * Shrink the <span class="md-window">Result</span> window by clicking the expand window button again.
{% endhint %} 

{% hint style='tip' %}
  The HTML output window is an excellent way to review the full content of your metadata record.  The HTML output presents all your entries in an organized easy-to-read format.  It can also be exported by clicking the <span class="btn btn-success btn-xs"> <i class="fa fa-floppy-o"> </i> Save Result</span> button, making this a handy way for others to review your metadata or embed it in websites.  
{% endhint %}

{% hint style='tip' %}
  Notice that the report generation date-time is shown in UTC (Coordinated Universal Time or Greenwich Mean Time).  
{% endhint %}

Let's try the ISO 19115-2 format next ...
