# Publish -- USGS ScienceBase
### Re-Publishing
---
Once you have published your records for the first time, updating and re-publishing them is straightforward.

#### How to Re-Publish

1. Load the desired mdEditor files into mdEditor.

1. Make necessary updates and changes to the metadata.

1. Go to the Publish tab and login to ScienceBase.

1. Select the records you want to re-publish and hit Publish.

1. Verify that the mdJSON file published to the ScienceBase page.

{% hint style='info' %}
  The mdJSON published to ScienceBase will always contain all of the updated information you published. sbJSON (and thus what is displayed on the ScienceBase page) will not always do so. Specifically, keywords that you delete in mdEditor will not be deleted from sbJSON. ScienceBase only adds to its "tags" and does not remove tags.
{% endhint %}

{% hint style='info' %}
  If you delete or change the metadata repository information in mdJSON, you must delete any obsolete or erroneous metadata repository tags directly on ScienceBase. These are called "Harvest Sets" on ScienceBase.
{% endhint %}
