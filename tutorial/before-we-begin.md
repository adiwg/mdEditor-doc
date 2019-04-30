# Tutorial -- Before We Begin

---

Before we actually begin entering and editing metadata in mdEditor, let's spend a few moments discussing the architecture of mdEditor so you have an understanding of how and where your metadata is being managed.

## Where is my metadata?

Because mdEditor runs in your internet browser you may quite naturally assume your data is being processed and saved in some far away cloud.  It is not.  All your data is being processed and stored on _your_ computer.  mdEditor is deployed as a web application primarily to avoid deployment and installation issues.  Each time you open your browser to mdEditor you are guaranteed to load the most recent version of the software -- you are always up-to-date.

mdEditor exploits a feature in modern internet browsers called browser cache.  Think of the browser cache as a temporary workspace for your metadata that is accessible to browser applications like mdEditor.  Although we call browser cache _temporary_ it is not cleared unless it is specifically requested to be cleared.  The process used to clear the browser cache is very similar to the process you use to clear your browser history and the two are generally co-located.

For more permanent storage of your metadata records after they have been polished to your satisfaction, mdEditor provides two facilities appropriately named 'Export' and 'Import'.  Export moves metadata from browser cache to a local storage folder/file of your specification on your hard-drive or SSD.  Import does the opposite and moves metadata records from your hard-drive or SSD back into the browser cache for mdEditor to access.  Of course these local storage locations may be a network server or another networked storage device if you desire.

{% hint style='tip' %}
  Because browser cache is a property of the *browser*, if you change browsers (e.g., from Chrome to Microsoft Edge) you will likely not have access to your metadata record since each browser manages its cache separately.  Don't worry.  Records can be exported to local storage and then imported to the new browser.
{% endhint %}

## What format is my metadata?

mdEditor saves metadata in a format we call '[mdJSON](https://mdtools.adiwg.org)'.  This is a metadata format we designed specifically for the Alaska Data Integration Working Group Metadata Toolkit ([ADIwg Metadata Toolkit](http://www.adiwg.org)) although its features make it attractive to other uses as well.  First, mdJSON is written in JavaScript Object Notation ([JSON](https://www.json.org)) format.  JSON is the native data structure for JavaScript, and thus of internet browsers, and is how all browsers move data across the internet and process it internally.  It also has broad support among programming languages, and can be read by humans with little difficulty, all making it a natural choice.

It was necessary for us to create the new mdJSON metadata standard because we needed to support translation to multiple national and international adopted standards.  To do this successfully we need a base standard that possesses a breadth of elements that encompasses all the other standards.  We also need the freedom to extend the base standard to support new versions of adopted standards as they are issued.  mdJSON also uses the extensible JSON format that can generally be modified without breaking your older mdJSON records.

## How does my metadata get translated?

We call the process of converting mdJSON into another metadata standard 'translation'.  To assist you in translating mdJSON into ISO or other metadata standards, mdEditor provides a translate feature, 'mdTranslator'.  mdTranslator is another tool in the ADIwg Metadata Toolkit that resides as a publicly hosted web service seamlessly integrated with mdEditor.  Ask mdEditor to translate your metadata record into ISO 19115-2 format, for instance, and it will connect with mdTranslator, forward your mdJSON metadata record, wait for, and catch the returned ISO metadata record.  And all in one step for you!
