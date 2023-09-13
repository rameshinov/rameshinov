**Description**

Execution of a test case can result in a passed or failed test case. Here we are seeing the flow for a _**failed**_ test case.

**Pre-requisite** 

Test&Feedback extension should be installed. [Click here](https://dev.azure.com/evsitapps/EVA/_wiki/wikis/EVA.wiki/155/Test-Feedback-Extension-Installation) to check instructions on how to install.

**Sequence for execution of test case**
- Select the correct test plan and go the correct test suite
- Ensure you are in Execute tab in your test suite
- Select one or more test cases to execute
- Select "Run for web application" on top right or right click and select Run -> Run for web application
- A test runner opens for the selected tests in sequence with all test steps
- Execute the test cases manually going through the steps side by side with application open aside.
- If the test case is failed, fail the particular test step -> attach a screenshot to evidence failure (mandatory) -> Add a comment for failure.
- For a failed test case you can raise a bug from the test runner itself. Click here to see on how to raise a bug from test runner during execution.
- If you want to raise the bug later upon review, you can save by clicking the save icon on top left and proceed to next test case.
- Upon completing all the test cases assigned to you, select the next test case -> click edit test case -> mark the field State "Ready for Test". This will trigger an email to the next person assigned to test and they can pick it up for execution accordingly


**Video (Test Execution - failure flow)**

![2023-05-22_11-50-57.gif](/.attachments/2023-05-22_11-50-57-ed75c29a-ad3d-4ac9-b55d-8b4645f3bc4f.gif)

