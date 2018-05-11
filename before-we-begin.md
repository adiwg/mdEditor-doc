# Before We Begin
---
Before we actually begin entering and editing metadata in mdEditor, let's spend a few moments discussing the architecture of mdEditor so we have an understanding of how and where our metadata is being managed. 

### Where is my metadata?
Because mdEditor is a web application (runs in your internet browser) you may quite naturally assume your data is being processed and saved in some far away cloud.  It is not.  All your data is being processed and stored on *your* computer.  mdEditor is deployed as a web application primarily to avoid deployment and installation issues.  Each time you open your browser to mdEditor you are guaranteed to load the most recent version of the software - you are always up-to-date. 

mdEditor exploits a feature of modern browsers to manage your data called [browser cache](glossary.md).  Think of the browser cache as a temporary working space for your metadata.  Although we are calling browser cache *temporary* it is not cleared unless you specifically request it to be cleared.  This would be done similar to the process you use to clear your browser history or reinstalling the browser software.  

For more permanent storage of metadata records after they have be polished to your satisfaction, mdEditor provides two facilities appropriately named 'Export' and 'Import'.  Export moves metadata from browser cache to a folder/file you specify on your hard-drive or SSD.  Import does the opposite, moves metadata records from your hard-drive or SSD into the browser cache for mdEditor to have access.  Of course these folder/file locations may be a network server or other networked storage device if you desire.

### What format is my metadata?
mdEditor saves metadata in a metadata format we call '[mdJson](https://mdtools.adiwg.org)'.  This is a metadata format we designed specifically for mdEditor although its features make it applicable to other uses as well.  First, mdJson is written in JavaScript Object Notation ([JSON](https://www.json.org)) format.  JSON is the native data structure for JavaScript, and thus of internet browsers, and is how all browsers move and data across the internet and process it internally.  It is also has broad support in programming languages, and can be read by humans with little difficulty making it our natural choice. 

It was necessary for us to create a the new mdJson standard because we chose to support output to multiple national and international standards.  No existing standard possessed the breadth of elements to encompass all the standards we have chosen to support.  mdJson is also extensible (generally without breaking existing records) and will grow over time as additional output formats are supported.  

### How does my metadata get translated?
We call the process of converting mdJson into another metadata data standard 'translation'.  To assist you in translating mdJson into ISO or other metadata standards, mdEditor provides a 'Publish' feature which connects with our public translation service.  The mdTranslator is a publicly hosted web service which integrates with mdEditor.  Ask mdEditor to publish an ISO 19115-2 metadata record for instance, and it will connect with mdTranslator, send your mdJson metadata record, wait for, and catch the returned ISO metadata record.  And all in one step for you!

OK, let's start this thing up!