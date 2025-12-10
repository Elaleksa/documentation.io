# 📓 **How to create Manual Test cases**
This instruction explains how to create a manual test case in Jira and helps QA engineers write clear, structured, and review-ready tests.

# 🔍 **Purpose**

Manual Test cases should be written to ensure consistent, repeatable, and traceable testing that verifies requirements and expected results. 

# 🚀 **Prerequisites**
Before creating a test case, ensure that you: 
  - Have access to Jira 
  - Have permission to create issues of type Test 
  - Understand the requirements and user stories 
  - Have prepared acceptance criteria 

# **Process Description (Step-by-Step)**

Step 1. Create a Test Issue 
Open your project **Test Repository** > Find specific folder > click '+' **Create Folder** below (e.g., Manual test) 
> **Note:** Create a new folder for each feature. 

Then right-click the folder you created > select **Create Test here** from the list
Fill in the required fields in the **Create Issue** window and click **Create**

Step 2. Design the Test 
After you create the folder and test, you can start designing it. 
*Firstly*, select the **Test Status** 
Depending on your workflow, a test can have these statuses: 
  'OPEN' - Test is created but not yet worked on 
  'IN DESIGN' - Test steps and details are being drafted 
  'READY FOR REVIEW' - Test is ready to be reviewed by a tester or developer 
  'REVIEW' - Test is currently under review 
  'READY FOR AUTOMATION' - Test is approved for automation (if applicable) 
  'IN AUTOMATION' - Test is currently being automated 
  'OBSOLETE' - Test is outdated or no longer valid 

*Then* add Test Steps 
Scroll down and click **Add Step** > New to create steps one by one 

> **Note:** You can also use: 
  Import > From test to clone steps from similar tests 
  Pre-Conditions to reuse one precondition across multiple tests 
  Use this only if all tests share the exact same preconditions 

Structure of Each Test Step: 
**Action**
  Describe what the tester should do in the step: 
  - click 
  - select 
  - enter 
  - open 
  - search 
  - verify 
  - submit, etc. 
  Use clear, actionable verbs. 

Preconditions 
  List the conditions that must be met before executing the test. 
  You may describe them in the first step or as a separate precondition entity.

**Expected result**
  Describe what should happen after performing the action 
**Data**
  Add test data needed for the step (or examples) 
Attachments 
  Attach screenshots, examples, or supporting materials. 

*Final Step* 
After designing the test, change its status to READY FOR REVIEW 
