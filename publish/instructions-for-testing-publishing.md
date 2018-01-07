# **Instructions for Testing Publishing**

For tracking issues, please use the github thread [here](https://github.com/adiwg/mdEditor/issues/128) and sign up for notifications via email.

1. Determine your workflow for testing:

   If You** do not already** have items on ScienceBase. Choose a project and its products to test.

   > ![](/assets/BestPracticeSmall.png)
   >
   > **Best Practice**: It's recommended that you export that project and its products into its own mdEditor file. Set default parent identifier as a test folder.

   If you** already have** items on SB, it is harder to test without affecting your real records.

   > ![](/assets/BestPracticeSmall.png)
   >
   > **Best Practice**:
   >
   > _Approach 1_ - Take a simple project and product set, then make a copy of the mdEditor records. In the test version, delete all SBIDs and parent IDs. The SBID will either be located in the citation or if you imported the record from SB, then the SBID will be the record identifier. Set default parent identifier as a test folder.
   >
   > _ Approach 2 _- Publish directly to a real record if you are okay with the risk it presents.

2. Set your** Default Parent Identifier **in Settings for a test folder.

3. Select one project with its associated products to test.

4. Before you publish anything, click F12 to bring up the error console to be able to track errors as they occur \(consult the [Troubleshooting Issues](/publish/troubleshooting-issues.md) section of this manual for more information\).

5. Follow the publishing instructions above for the Scenario that applies to you.

6. Verify that your test records have published as expected in your test folder on ScienceBase \(or to the real record if that’s how you are testing\).

7. After you are satisfied with how your test records published to ScienceBase, you can proceed with publishing your real record.
8. Update your mdEditor settings to your real Default Parent Identifier.
9. Using the record you just tested, proceed with publishing to the real location on ScienceBase.
10. Make sure any test SBIDs are removed entirely from the record you want to actually publish.
11. Verify the real records have updated as expected.
12. Proceed with publishing your other records to their real locations.



