**Description**

Execution of a test case can result in a passed or failed test case. Here we are seeing the flow for a _**passed**_ test case.

**Pre-requisite** 

Test&Feedback extension should be installed. [Click here](https://dev.azure.com/evsitapps/EVA/_wiki/wikis/EVA.wiki/155/Test-Feedback-Extension-Installation) to check instructions on how to install.

**Sequence for execution of test case**
- Select the correct test plan and go the correct test suite
- Ensure you are in Execute tab in your test suite
- Select one or more test cases to execute
- Select "Run for web application" on top right or right click and select Run -> Run for web application
- A test runner opens for the selected tests in sequence with all test steps
- Execute the test cases manually going through the steps side by side with application open aside.
- If the test case is successful pass the step and repeat the same for all the steps
- Check where screenshots are essential and attach the screenshot by simply clicking the camera icon in the test runner.
- Click next, if there are multiple tests selected for test execution.
- Once complete, right select the next test case -> click edit test case -> mark the field State "Ready for Test". This will trigger an email to the next person assigned to test and they can pick it up for execution accordingly.


**Video (Test Execution - Pass flow)**

![2023-05-22_11-18-36.gif](/.attachments/2023-05-22_11-18-36-4577fad9-77a1-4845-b51b-d34cf21590c5.gif)
