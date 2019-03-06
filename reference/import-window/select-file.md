# Reference -- Import Records 
### Select Import File
---

The first step in the import process is to identify the metadata file to import.  mdEditor can import mdEditor, mdJSON, and FGDC CSDGM metadata records from local storage or from remote locations via the internet.  

![Import File Panel](/assets/reference/import/import-file.png)

#### Import Local File

 * <span class="btn btn-info btn-xs"> <i class="fa fa-bullseye"> </i> Click or Drop a file here to import data</span> To import a local file, drag the file from your computer's desktop or file explorer over the large blue drop zone.  When mdEditor becomes ready to receive the file, the target zone will turn green.  Note that mdEditor has not read the file at this point and does yet know if the file is valid.  mdEditor is only ready to read the file if it is dropped.
 
   Once the file is dropped mdEditor will immediately proceed to read it.  If the file is not in mdEditor format, mdJSON format, or FGDC CSDGM format it will be rejected.  It will also be rejected if there is a structural error within the file that prevents it from being interpreted.  If the file is rejected a note will pop up on the window informing you of the rejection.  If the file can be read, mdEditor will read it and transfer you to the <span class="md-window">Import</span> window.
   
   {% hint style='info' %}
   The import file can have any name.  The name does not need to be in the same pattern as assigned to exported files.  Also, the file extension is ignored by mdEditor.  However, it is best practice to keep mdEditor and mdJSON file extensions as .json and FGDC CSDGM file extensions as .xml.
   {% endhint %}
   
 * <span class="btn btn-info btn-xs"> <i class="fa fa-bullseye"> </i> Click or Drop a file here to import data</span> The file drop zone is also a button.  Click the button to launch your computer's file explorer and seach for an import file. Once found, select the file and click "Open".  mdEditor will proceed to process the file as outlined above. 
 
--- 

#### Import Online File

* <span class="md-element">Import from Online URL</span> To load a metadata file from an online source, type the complete URL into the control and click <span class="btn btn-primary btn-xs"> <i class="fa fa-cloud-download"> </i> Import</span>.  mdEditor will proceed to process the file as outlined above. 
