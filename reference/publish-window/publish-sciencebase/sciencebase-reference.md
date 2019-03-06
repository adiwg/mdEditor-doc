# Publish -- USGS ScienceBase

---

ScienceBase has its own metadata schema called sbJSON. If you publish from mdEditor to ScienceBase, the mdJSON created in mdEditor will update the sbJSON for the ScienceBase item and mdJSON and XML metadata files will be attached to the ScienceBase item. mdJSON contains more metadata fields than sbJSON so what will display on the ScienceBase item will not include everything in the mdJSON. 

Metadata is published to ScienceBase in your community's project folder. You must have a ScienceBase user account with write access to this folder. Once you have successfully published from mdEditor to ScienceBase, the corresponding ScienceBase Item\(s\) will be immediately updated.

![Date Settings](/assets/reference/publish/publish-sciencebase.png)

Click the large "ScienceBase" button to begin the process.

Please read through sections [Requirements for Publishing]() and [Testing Publishing]() before trying to publish any real records.

---

### Overview of Publishing to ScienceBase

The following describes what happens when you publish from mdEditor to ScienceBase:

1. mdEditor outputs an mdJSON file.
2. The mdJSON file is transmitted via a web service to mdTranslator.
3. mdTranslator translates the mdJSON file into sbJSON and XML.
4. ScienceBase imports the sbJSON and attaches the XML and mdJSON files to the ScienceBase item.
5. The XML metadata record is sent to data.doi.gov if the requisite metadata repository is specified. Note: metadata repositories are called Harvest Sets in ScienceBase.
