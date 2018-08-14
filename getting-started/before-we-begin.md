# Before We Begin

---

Before we actually begin entering and editing metadata in mdEditor, let's spend a few moments discussing the architecture of mdEditor so we have an understanding of how and where our metadata is being managed.

## Where is my metadata?

Because mdEditor is a web application \(runs in your internet browser\) you may quite naturally assume your data is being processed and saved in some far away cloud.  It is not.  All your data is being processed and stored on _your_ computer.  mdEditor is deployed as a web application primarily to avoid deployment and installation issues.  Each time you open your browser to mdEditor you are guaranteed to load the most recent version of the software - you are always up-to-date.

mdEditor exploits a feature in modern browsers to manage your data called browser cache.  Think of the browser cache as a temporary working space for your metadata.  Although we are calling browser cache _temporary_ it is not cleared unless you specifically request it to be cleared.  This can be done similar to the process you use to clear your browser history.

For more permanent storage of your metadata records after they have been polished to your satisfaction, mdEditor provides two facilities appropriately named 'Export' and 'Import'.  Export moves metadata from browser cache to a local storage folder/file of your specification on your hard-drive or SSD.  Import does the opposite, moves metadata records from your hard-drive or SSD back into browser cache for mdEditor to have access.  Of course these local storage locations may be a network server or another networked storage device if you desire.

## What format is my metadata?

mdEditor saves metadata in a format we call '[mdJSON](https://mdtools.adiwg.org)'.  This is a metadata format we designed specifically for mdEditor although its features make it applicable to other uses as well.  First, [mdJSON](https://mdtools.adiwg.org) is written in JavaScript Object Notation \([JSON](https://www.json.org)\) format.  JSON is the native data structure for JavaScript, and thus of internet browsers, and is how all browsers move data across the internet and process it internally.  It is also has broad support among programming languages, and can be read by humans with little difficulty all making it a natural choice.

It was necessary for us to create a the new metadata standard because we chose to support output to multiple national and international standards.  No existing standard possessed the breadth of elements to encompass all the standards we have chosen to support.  [mdJ](https://mdtools.adiwg.org)SON is also extensible \(generally without breaking existing records\) and will grow over time as additional output formats are supported.

## How does my metadata get translated?

We call the process of converting [mdJSON](https://mdtools.adiwg.org) into another metadata data standard 'translation'.  To assist you in translating [mdJSON](https://mdtools.adiwg.org) into ISO or other metadata standards, mdEditor provides a 'Translate' feature, 'mdTranslator'.  The mdTranslator is a publicly hosted web service which seamlessly integrates with mdEditor.  Ask mdEditor to translate your metadata record into ISO 19115-2 metadata for instance, and it will connect with mdTranslator, forward your [mdJSON](https://mdtools.adiwg.org) metadata record, wait for, and catch the returned ISO metadata record.  And all in one step for you!

OK, let's start this thing up!
