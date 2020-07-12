## Metadata Record -- Extent Section
---
### Import Geographic Features 
 
![Geographic Extent Features Edit Window](/assets/reference/edit-objects/metadata/extent/features-import.png){caption}

Some geographic features stored on your hard drive may be imported directly into mdEditor and saved as a geographic <span class="md-panel">Feature</span>.  To be eligible for import the file must be saved in one of the supported formats listed below.

<strong class="btn btn-warning btn-xs"> <i class="fa fa-upload"> </i> Import Features</strong> Click to import a feature file from your hard drive.  Your operating system's file explorer will open to a default file location (such as the 'Downloads' folder).  Select the file to import or navigate to the desired folder.  Select the file to import and click "Open".

  -or-

__Drag & Drop__  The map supports dragging a file from your file explorer and dropping the feature file on the map.  mdEditor will open the file and incorporate the feature(s).

---

{% hint style='info' %}
**Please Note:**  Imported data needs to utilize the World Geodetic System 1984 (WGS 84) [WGS84] coordinate reference system.  Longitude and latitude should be in units of decimal degrees. For more details on WGS84, please visit <a href="https://epsg.io/4326" target="_blank">the espg.io database website <sup class="fa fa-external-link"></sup></a>.
{% endhint %}




* __CSV__ (Comma or Tab delimited) text file
   
  The import process searches column heading names for clues to locating geographic and other information.  
    
  * A column name of "lat", "latitude", or "lat" + any other characters is assumed to contain the geographic latitude in decimal degrees.
  * A column name of "lon", "longitude", or "lon" + any other characters is assumed to contain the geographic longitude in decimal degrees.
  * A column name of "id" is assumed to contain the ID of the point and is saved in a editable field.
  * A column name of "name" is assumed to contain the name of the point and is saved in a editable field.
  * A column name of "description" is assumed to contain a description of the point and is saved in an editable field.
  * All other column values are saved in read-only fields. 
    
  {% hint style='info' %}
 The CSV file can only import points.
    {% endhint %} 
  
* __KLM__ (Keyhole Markup Language) - used by Google Earth and others applications.
  
  * A column name of "name" is assumed to contain the name of the feature and is saved in a editable field.
  * A column name of "description" is assumed to contain a description of the feature and is saved in an editable field.
  * All other column values are saved in read-only fields. 
    <br><br>

* __Shapefile__ (ESRI ArcGIS format) - A non-topological file format for storing the geometric location and attribute information of geographic features in XML structure.
  
  * Vector shapefiles are not supported. 
    <br><br>

* __GeoJSON__ (RFC 7946) - a geospatial data interchange format based in JavaScript Object Notation, JSON.
  
  * A column name of "id" is assumed to contain the ID of the feature and is saved in a editable field.
  * A column name of "name" is assumed to contain the name of the feature and is saved in a editable field.
  * A column name of "description" is assumed to contain a description of the feature and is saved in an editable field.
  * All other column values are saved in read-only fields.  
    <br>

* __GPX__ (the GPS eXchange Format) - a data format for exchanging GPS data between programs and users.
