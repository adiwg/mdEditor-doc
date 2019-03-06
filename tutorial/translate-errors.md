# Tutorial -- Handling Translation Errors
---

Let's run another translation on "My First Metadata Record".  This time choose the output format as "ISO 19115-2."

{% hint style='working' %}
  Translate "My First Metadata Record" to ISO 19115-2
  * Choose "ISO 11915-2" from the <span class="md-element">Choose Format</span> control
  * Click the <span class="btn btn-primary btn-xs"> <i class="fa fa-retweet"> </i> Translate</span> button.
{% endhint %}

![Translate Record Window with Warnings](/assets/tutorial/translate-mdjson-3.png){caption}

This time things did not go quite so well.  A "Translation Warning" panel has popped up along with the expected <span class="md-panel">Result</span> panel.  You are being warned that although you have met the requirements for a minimal mdJSON record, there are still one or more additional requirements needed to generate a valid ISO 19115-2 record.  

No problem.  The message informs us that we are missing a date for the main resource citation.  Let's break the message down by parts before we add the date.

#### Message Level

The message level can be either Error, Warning, or Notice.  In general, all message levels will still generate a metadata record.  The message's level speaks more to how well the generated metadata record conforms to the requested standard.  We will have more to say on this topic when we discuss translation in detail.  For now, the best approach is to fill in all missing data identified by either an Error or Warning message.  

#### Message

The message.  In this case "citation dates are missing."

#### Issued From

The "Issued From" indicator tells which mdTranslator module issued the message.  This will be one of the mdTranslator readers or writers.  In our example the message was issued by the "ISO 19115-2 writer."  

#### Context

A message context is provided to help you find the offending section of your metadata record. For instance, as discussed earlier, <span class="md-panel">Citation</span> is used in many place throughout the metadata record.  It would be insufficient to simply say "citation dates are missing".  For which citation?  

Context tells us the offending citation is the "main resource citation".  Which is not surprising since it's the only <span class="md-panel">Citation</span> we have entered so far.  

---

Let's add the missing date.  

{% hint style='working' %}
  Enter a main resource citation date.
  * Click the <span class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> </span> button next to the "My First Metadata Record" in the <span class="md-window">Primary Sidebar</span>.
  * Click "Citation" on the <span class="md-window">Fast Scrolling</span> section of the <span class="md-window">Secondary Sidebar</span> to scroll <span class="md-panel">Citation</span> to the top.
  * Click the <span class="btn btn-success btn-xs"> <i class="fa fa-pencil"> </i> Edit</span> button on the <span class="md-panel">Citation</span> <span class="md-window">Panel Title Bar</span>.
  * On the <span class="md-panel">Dates</span> panel click the <span class="btn btn-info btn-xs"> <i class="fa fa-plus"> </i> Add Date</span> button
  * Add a date
  * Choose a date type
  * Save your edit if "AutoSave" is not "On"
{% endhint %}

With our citation date entered let's go back and try the translation to ISO one more time ...

{% hint style='working' %}
  Translate "My First Metadata Record" to "ISO 19115-2"
  * Click "Translate" on the <span class="md-window">Primary Navigation Bar</span>
  * Choose "ISO 11915-2" from the <span class="md-element">Choose Format</span> control
  * Click the <span class="btn btn-primary btn-xs"> <i class="fa fa-retweet"> </i> Translate</span> button.
{% endhint %}

Worked for me!  How about you?

With a valid ISO 19115-2 record in the <span class="md-panel">Result</span> preview panel let's export the metadata ISO record so it can be sent to a clearinghouse, repository, or publisher of our choice.  

{% hint style='working' %}
  Save the ISO 19115-2 metadata record.
  * Click the <span class="btn btn-success btn-xs"> <i class="fa fa-floppy-o"> </i> Save Result</span> button.
  * Check your computer's "Downloads" folder for the metadata record.
  * Move the file to a safe location on your computer.
  * Rename the file if you like.
{% endhint %}

{% hint style='info' %}
  The downloaded metadata file will have a filename format of {recordName}_{date}.{ext}.  As an example, the file I downloaded was named "My First Metadata Record_20180907.xml".
{% endhint %}

---

{% hint style='working' %}
  Extra Credit!
  * Translate "My First Metadata Record" to "FGDC CSDGM"
{% endhint %}

Now there are a lot of missing elements!  FGDC CSDGM has more required elements than either mdJSON or ISO.  But we don't need to add all those missing elements for this exercise.  Let's just move on to "Exporting Records."

{% hint style='info' %}
  Each standard format has its own set of requirements.  Getting your record ready for one standard will not guarantee it is ready for another.  Thankfully mdTranslator can sort that out for you by pointing out any missing required elements.
{% endhint %}
   