# Publish

---

The mdEditor allows you to  publish records to an online platform. The current option is ScienceBase, a collaborative data cataloging and data management platform developed by the United States Geological Survey. It provides a centralized, searchable, and publicly-available repository for data. You must have a ScienceBase user account with publishing rights in order to publish to ScienceBase.

![](/assets/publish_screenshot.png)

## Before You Begin

> ![](/assets/note_small.png)Please read through ALL instructions before you begin the publishing proecess. After you understand how the publishing function works, please read the[** testing instructions**](/publish/instructions-for-testing-publishing.md) and proceed with testing a record before you try to publish any of your real records.

---

## Overall Science Catalog System Architecture

_The following diagram describes the science catalog system architecture._

> ![](/assets/note_small.png)Currently the mdEditor is used primarily with ScienceBase, a collaborative scientific data and information management platform developed and run by the USGS and used directly by science teams. The mdEditor can work with other databases, but in this manual, ScienceBase will be used as the primary example of a database.
>
> For more information, see ScienceBase in the glossary of terms.

![](/assets/science_catalog_system_architecture.png)

* Items are imported from a database \(like ScienceBase\), or created directly in mdEditor.
* mdJSON files can also be stored in a local repository and then transmitted via a web service to ScienceBase. Alternately, the  local files can be exported to a web accessible folder and then harvested by ScienceBase.

* The mdTranslator converts the mdJSON files into sbJSON \(the ScienceBase JSON format\), and XML.

* Items are exported from ScienceBase to: Data.gov as XML; the LCC Science Catalog website as Projects and Products; or into mdEditor as mdJSON.



