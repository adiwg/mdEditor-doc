# Publish -- USGS ScienceBase

---

Metadata is published to ScienceBase in your community's project folder. You must have a ScienceBase user account with write access to this folder. Once the mdJSON metadata is published in ScienceBase, the records will be synced with the USGS Science Catalog \(the Science Catalog updates overnight with new/updated mdJSON\).

![Date Settings](/assets/reference/publish/publish-sciencebase.png)

Click the large "ScienceBase" button to begin the process.

Please read through sections [Requirements for Publishing]() and [Testing Publishing]() before trying to publish any real records.

---

### Overview of Publishing to the Science Catalog

The following describes what happens when you publish from mdEditor to ScienceBase:

1. mdEditor outputs an mdJSON file.
2. The mdJSON file is transmitted via a web service to mdTranslator.
3. mdTranslator translates the mdJSON file into sbJSON and XML.
4. ScienceBase imports the sbJSON and attaches the XML and mdJSON files to the ScienceBase item.
5. The record is sent to data.doi.gov and the USGS Science Catalog if the requisite metadata repositories are specified.

---



