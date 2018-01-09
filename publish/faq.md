# FAQ

1. Is moving the record in the mdEditor outline also moving the record in ScienceBase, or just overwriting the existing record?

   > Moving a record in mdEditor will overwrite the record in Science Base. If you have a record in SB already, then it is not advisable to move items in the publishing outline structure.
   >
   > If you want to move the item on ScienceBase via mdEditor, then edit the parent identifier in the record located in Metadata-&gt;Parent Metadata-&gt;Identifier.

2. If I have a project on ScienceBase already, one or more intermediate organizing folders, and then have a product, will the product record go back to the same place?

   > It will go back to the exact same place as long as you don't change the parent ID in the metadata record itself or drag it around in the publishing outline.

3. Once you use mdEditor for editing items, you have to keep using mdEditor. If you go back to DEPTH or SB directly to edit items, your edits will not be reflected in the attached mdJSON, so your edits will be lost \(overwritten\) the next time you publish from mdEditor.”

4. When you publish from mdEditor to SB, it runs through mdTranslator twice. First is to create sbJSON to create SB record. Second time is to create ISO XML. The item will have an mdJSON attachment, which must be edited in mdEditor. Anytime you update in mdEditor it will update in SB\(after you re-publish\). ScienceBase stores items in sbJSON format.

5. What if we are working on files remotely for same project? Will these merge?

   Files and contact lists will not merge. The new import will overwrite the older version.

   > ![](/assets/BestPracticeSmall.png)**Best Practice**: Maintain a master contacts list that is accessible by multiple editors.
   >
   > ![](/assets/BestPracticeSmall.png)**Best Practice**: It is recommend that only one person edit the same project/product at the same time to help with version control.



