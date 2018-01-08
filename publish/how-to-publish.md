# How to Publish

> ![](/assets/BestPracticeSmall.png)**Best Practice:** always hit_ refresh_ in your browser before each work session \(and periodically throughout the day\) to ensure you are using the most updated version of mdEditor. Always refresh before you access the publishing menu. However, If you start moving items around in the publishing outline \(see below for details\), you may lose this information once you refresh.
>
> ![](/assets/NoteSmall.png)**Note: **Currently the  publishing service available through the mdEditor is ScienceBase. In the future, mdEditor will likely be able to work with other databases, such as data.gov. Instructions in this manual will use ScienceBase as an example..

---

#### Step One: Logging Into Science Base

* Click the **Publish** button from the top menu in mdEditor.

* You will be asked to select a _publishing service_. Click on Science Base.

* A login window will appear on the right side of the screen - enter your ScienceBase ID and password, and click **Login**. When you are logged in, the login window will display who you are logged in as. _The current user must have read/write permissions on ScienceBase for any items to be published \(including parent items\)_. You cannot publish until you are logged in.

* You will see a list of every valid record in mdEditor in the publishing outline with its ScienceBase Identifier \(if the record already exists on ScienceBase\) and its parent ScienceBase Identifier \(if present in the metadata\). This publishing outline shows records in a parent-child relationship and reflects what you would see when you publish in ScienceBase.

> ![](/assets/NoteSmall.png)Parent-child refers to how the records are organized and displayed on ScienceBase; this is different than the Project and Product associations that are embedded within the metadata records.

* Records without parent IDs already in their metadata will appear directly under the ScienceBase header, indicating that they will be published under the default parent identifier established in the settings \(which is also visible on the header - you can click it to follow a link to the record on ScienceBase\).
* Records that have parent IDs in the metadata record will appear below a thick blue line and will be published under the parent ID in their metadata \(which is visible in that record’s entry in the outline\).

> ![](/assets/NoteSmall.png) if you do not want these parent IDs to change,** do not** drag and drop these records in the publishing outline.

#### 

---

#### **How the publishing outline works:**

The publisher looks for the first identifier in a record that matches an existing one in mdEditor and then puts it under that record in the outline. If it doesn't find a matching identifier, it puts the record at the** **root level of the folder that you are uploading to. The root level being the uppermost folder of your organization.

Items directly below the ScienceBase header will be published under the ScienceBase item identified in your settings as “Default Parent Identifier.” Items below the blue line will be published under the parent ID specified in the metadata.

* For example, if the _Default Parent Identifier_ is your LCC Community, then projects at the _root level_ in the publishing outline will be added directly under your LCC Community.

* Products nested under a project in the outline will be added as a direct child item to the project item on ScienceBase.

* Items listed at the root level in the publishing outline don't have a parentID that correspond with a record loaded in mdEditor \(Note: you could have other parent IDs identified in those records, but those records aren't loaded in mdEditor\)

-You can drag and drop records to establish the parent-child relationship, eliminating the need to establish the relationship in ScienceBase. This will also allow you to move items around \(e.g., move a product from one project to another\) and have that change be reflected on ScienceBase. Remember, this is only about parent-child relationships on ScienceBase, not about project-product associations.

> ![](/assets/NoteSmall.png)If you move a product under a different project, it will update that product’s parent ID.
>
> Parent IDs established through the relationships in the publishing outline will overwrite existing parent IDs in the metadata.
>
> Dragging and dropping a record onto the ScienceBase header at the top will set that record’s parent ID to the default parent ID you identified in settings.
>
> If you have existing parent IDs in your metadata \(and want to keep them as is\), **DO NOT** drag and drop those records onto the ScienceBase header - this will erase the existing parent ID and insert whatever you have set as the default parent identifier.
>
> ![](/assets/BestPracticeSmall.png)**Best practice:** Make sure that if you have projects and associated products that you have them in mdEditor at the same time and manage them at the same time.

---

#### Step Two: Moving Records into Publishing Outline

Before you move records in the publishing outline please select your scenario below and follow the corresponding guidance.

**Scenario A: **You do not have items on ScienceBase yet, and your desired parent-child relationship is to have each product as a direct child of a project item on ScienceBase:

* Your records will all display under the ScienceBase header in the publishing outline. 
  * These items will be published as a direct child item under the SB item identified in your settings under “Default Parent Identifier.”
* You can drag and drop records in the publishing outline to establish parent-child relationships for ScienceBase.
* You can nest items in as many levels as you desire \(the most common is a product nested under a project\).
* To move a record back to the root level, drag and drop it on the top line that says “ScienceBase Default”.

---

**Scenario B**: You have existing parent-child relationships on ScienceBase and/or you have intermediate folder\(s\) between project items and products \(i.e., products are not direct child items of Project Items\).

* If you have parent-child relationships already established on ScienceBase \(and those IDs are reflected in the mdEditor records\), you likely do not want to move the records around in the publishing outline.
* If your products are housed in a “Products” folder on ScienceBase \(or other intermediate folders between the project item and the products\), then your products WILL NOT be nested under projects in the publishing outline. 
  * The parent ID for those products is the “Products” folder, which would not have a record in mdEditor. If this is your situation, do not change  the structure in the publishing outline and publish as is \(i.e., with every item organized at the root level in the outline\).

---

#### Step Three: Submitting for Publishing

* To select a record to publish, click on it and it will turn green \(click again to un-select it\).

  * You cannot publish a record without a parent ID.
  * Sending a non-existent parent ID to ScienceBase will return an error.
  * If records contain parent IDs in the metadata, you can choose to  publish products without publishing their parent projects.

* mdEditor publishes sequentially, starting with the top record \(it will publish the project first, then the products nested below it\).

  * If you are publishing to your default parent identifier or you have changed any project-product relationships in the publishing outline, you will see the updated parent IDs appear in the outline as publishing occurs \(if you’re publishing to the existing locations on SB, the IDs won’t change\).

  * These new/updated IDs will also be injected directly into the mdJSON file in mdEditor. However, these updated IDs will not be included in the mdJSON file that is attached to ScienceBase as part of the publishing process. You would have to publish the record a second time to update the mdJSON file attached on ScienceBase.

* Once publishing is done, refresh ScienceBase to ensure everything is showing up how you expected it would show up.

  * SB items should have an mdJSON and xml file attached.

  * SB items should be in the location reflected in the mdEditor publishing outline.

* You can re-publish records as needed \(e.g., after updating or correcting metadata\).



