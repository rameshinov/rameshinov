**Description** 

A bug needs to be created when an issue is identified which needs to be addressed by developers or needed for tracking purpose.

There are 3 ways to raise bug,

1. Raise bug while you are doing test execution
2. Raise bug after execution going into the test case
3. Raise bug from boards as a work item (not preferred)

**Option 1- Raise bug while doing test execution**
This option is preferred, if the user is sure it is a bug and doesnt require any further review. Because during execution all the information on steps to reproduce is pulled automatically.
1. Perform test execution. [Click here](https://dev.azure.com/evsitapps/EVA/_wiki/wikis/EVA.wiki/157/Execute-Test-Case-Fail-flow) to know detailed steps for test execution.
2. When a test case is failed, after adding comments, taking screenshot, click icon create bug.
3. A window for new bug opens with all the details of the steps to reproduce the issue, failed step, screenshot and comments are prepopulated.
4. User needs to enter following details as mandatory and Save&Close

![2023-05-25_10-27-20.gif](/.attachments/2023-05-25_10-27-20-2f621884-48d5-4704-abfd-74a26242dd09.gif)

**Option 2- Raise bug after test execution from test case**
This option is preferred, if a bug needs to be reviewed before registering. The information on steps to reproduce is not pulled in directly. However, the developer can still refer to the linked test and see the test cases and test steps of failure.
1. Perform test execution. [Click here](https://dev.azure.com/evsitapps/EVA/_wiki/wikis/EVA.wiki/157/Execute-Test-Case-Fail-flow) to know detailed steps for test execution.
2. After the test case is failed, if the user is not sure if its a bug or wants to raise later for some reason, the user just adds the comments and screenshots and Save&Close.
3. Once reviewed and bug is confirmed, user can go to the failed test case and open the history by double clicking. Open the failed instance by double clicking. This opens test summary.
4. In test summary, an icon bug. Select the dropdown in it and select create bug.
5. A window for bug opens. user needs to fill in the description and expected. For steps to reproduce, mention to refer the link for the test run.

![2023-05-25_11-21-36.gif](/.attachments/2023-05-25_11-21-36-0952e470-7ea8-4236-9d62-f6ba70ea0558.gif)

**Option 3 - Raise the bug from work items**
This option is to be used only, when there is no test case available, but for some reason, we need to track an issue as bug. Here all the details of description, exepcted and step to reproduce need to be provided by the key user.
1. Go to Boards -> Work Items 
2. An icon for new work item can be seen. From the drop down, select bug.
3. A window for bug opens. Fill in all the mandatory details and describe the issue with description, expected and steps to reproduce.

![2023-05-25_11-39-52 (1).gif](/.attachments/2023-05-25_11-39-52%20(1)-387e8b30-8a63-4f4b-a9b1-b268bb7a474e.gif)


|Field| Format & Values | Example |
|--|--|--|
| Title |  <MVP><Process/Sub Process name><Short Description>  | Order to Cash - Order Creation - Invoice generation failed
| Description | Description of issue, Expected result, Steps to reproduced| ![Capture.PNG](/.attachments/Capture-b3451aeb-8f80-41c6-8ccc-7247b0af6944.PNG) |
|Iteration|Under EVS_NL -> 40.Integration and UAT -> 40.2 UAT1 (or) select appropriate sprint accordingly| ![Capture.PNG](/.attachments/Capture-a8057e0b-90d3-4d49-9d24-07c311511e26.PNG)|
|Priority (For Delaware)|1,2,3,4|![Capture.PNG](/.attachments/Capture-c1b00558-8c82-4813-a1b8-b27e27e2fa1d.PNG)|
|Severity|1-Blocking Problem  2-Problem impacting activities      3-Minor Problem|![Capture.PNG](/.attachments/Capture-9fa15aa4-7c43-428e-bb2d-f17db7baaae4.PNG)|
|Bug Type (for Delaware) |BI,Configuration,Custom development, Data migration, Document Layout, Interface and so on|![image.png](/.attachments/image-b493c321-6526-41ac-a15e-a0e162cbe720.png)|
|E2E_AIES|Select MVP from the List| ![Capture.PNG](/.attachments/Capture-ea1f6e76-bccc-463f-99fc-87a992275b73.PNG)|
|Assigned_To|Assign to Francois|![Capture.PNG](/.attachments/Capture-4d155e58-a6d1-44d8-aeae-6ac64cbdbc3f.PNG)|




