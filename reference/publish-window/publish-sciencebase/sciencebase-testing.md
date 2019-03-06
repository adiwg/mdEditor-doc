# Publish -- USGS ScienceBase
### Testing
---

{% hint style='danger' %}
  Please use a testing folder before you update your real records.
{% endhint %}

 1. Determine your workflow for testing:
 
    If you DO NOT already have items on ScienceBase, choose a project and its products to test.
    
    BEST MANAGEMENT PRACTICE: It's recommended that you export a project and its products into its own mdEditor file. Set the default parent identifier as a ScienceBase folder.
    
     If you DO already have items on ScienceBase, choose one of the following approaches. Note that it will be harder to test without it affecting your real records.
     
     Approach 1 - Take a simple project and product set, and make a copy of the mdEditor records. In the test version, delete all ScienceBase IDs (SBIDs) and parent IDs. The SBID will either be located in the citation, or if you imported the record from SB, the SBID will be the record identifier. Set the default parent identifier as a folder.
     
    Approach 2- Publish directly to a real record if you are okay with the risk it presents.
    
 1. Set your Default Parent Identifier in Settings.
 
 1. Select one project with its associated products to test.
 
 1. Follow the publishing instructions above for the scenario that applies to you.
 
 1. Look for any errors in the third column. If you see an error that is 400 and red, it’s a problem that you can address. However, if it’s a 500 level error in red, that is a ScienceBase error that is outside the scope of the mdEditor.

 1. Verify that your test records have published as expected in your folder on ScienceBase (or to the real record if that’s how you are testing).

 1. After you are satisfied with how your test records published to ScienceBase, you can proceed with publishing your real record.

 1. Update your mdEditor settings to your real Default Parent Identifier.
 
 1. Using the record you just tested, proceed with publishing to the real location on ScienceBase.
 
 1. Make sure any test SBIDs are removed entirely from the record you want to actually publish.
 
 1. Verify that the real records have updated as expected.
 
 1. Proceed with publishing your other records to their real locations.
