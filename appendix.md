# Appendix:

## Overall Science Catalog System Architecture

![](/assets/Science_Catalog_System_Architecture.png)

* Items are imported from a database \(like ScienceBase\), or created directly in mdEditor.
* mdJSON files can also be stored in a local repository and then transmitted via a web service to ScienceBase. Alternately, the  local files can be exported to a web accessible folder and then harvested by ScienceBase.

* The mdTranslator converts the mdJSON files into sbJSON \(the ScienceBase JSON format\), and XML.

* Items are exported from ScienceBase to: Data.gov as XML; the LCC Science Catalog website as Projects and Products; or into mdEditor as mdJSON.



