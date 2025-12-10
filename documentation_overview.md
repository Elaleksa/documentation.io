# 📓 **Test Documentation Overview**
This instruction describes different types of test documentation and explains how to write them.

# 🔍 **Purpose**

Test documentation helps you plan, record, and track the entire testing process.
It includes test plans, test cases, checklists, test suites, and other related documents.

# 🚀 **Prerequisites**

Before you start writing test documentation, make sure you have:
- Requirements and specifications (user stories, acceptance criteria, business rules)
- Test basis (design documents, workflows, APIs, architecture)
- Product understanding (features, purpose, user flows)
- Test strategy (approach, scope, test levels, test types)
- Tools (test management tools, tracking systems, documentation platforms)
- Test data (realistic and relevant data sets for validation)
- Environment details (test environments, configurations, access)
- Risks and constraints (time, budget, release deadlines)

# 🧪 **What is test documentation?**

Test documentation includes different types of tasks. In Jira, you may see the following types: 
- Epic – a big task that spans several sprints. 
- Requirement – a task describes how feature should be implemented. 
- Story – a smaller part of an Epic planed for one sprint. 
- Task – a technical task done by a team member. 
- Sub-task – a smaller part of a task. 
- Test plan – a document that describes what, how, and when you test. 
- Test case – a list of steps you must follow, with expected results. 
- Test set/ test suite – a group of test cases for a specific feature or scope. 
- Test execution – a record of running tests and tracking the results. 
- Bug – a task that reports an issue in the system.

Further this guide describes how to write a test plan, test case, and test suite:

## 📝 **Test plan**
A test plan describes the full testing approach for a specific scope. It explains what you test, how you test, and when testing happens. It defines the test object, test basis, strategy, schedule, entry and exit criteria, and risks. 
Test plan includes:
1. Identifier – the unique ID of the test plan. 
2. Introduction – short description of the scope and purpose of testing. 
3. Test object – the feature, component, or system you are testing. 
4. Features to be tested – what is in scope. 
5. Features not to be tested – what is out of scope and why. 
6. Entry criteria – resources and conditions you need before testing (team, tools, environment, test data, requirements). 
7. Exit criteria – conditions to complete testing (coverage level, defect status, number of passed/failed cases).
8. Test schedule – timeline and milestones.
9. Test schedule – timeline and milestones.
10. Test approach – how you will test (functional, non-functional, manual, automation). 
11. Risks – possible issues and how to handle them. 
12. Approvals – people who approve the test plan. 

## 📂 **Test case**
A test case is a document that includes clear steps and expected results for each step. 
Test case consist of: 
1. Description – reference to Epics, Stories, or Requirements 
2. Preconditions – what must be true before the test starts 
3. Steps – actions you perform (use clear verbs: select, click, open, go to) 
4. Expected result –  what should happen after each step

## 🗃️ **Test set or test suite**
A test set or test suite contains a group of related test cases. After you create test cases, you organize them into suites to plan the execution order.

# 🧩 **How to create test documentation in Jira?**
Step 1. Create a test sub-task for the development task
1. Open the **Epic**
2. Open the **Task** inside the Epic
3. Select **More**
4. Select **Create Sub-task** and name it, for example:
`TC for ABC-TaskNumber Feature Development'`

Step 2. Create a test case in the Test Repository
1. Go to **Test Repository**
2. Find the specified folder
3. Select **Create Test Here**

Step 3. Create a Test Plan from the test cases
1. Go to **Test Repository**
2. Find the specified folder
3. Select **Create Test Plan**

Step 4. Create a Test Set from the test cases
1. Go to **Test Repository**
2. Find the specified folder
3. Select **Create Test Set**

Step 5. Link the test plan and test set to the sub-task
1. Open the **Sub-task**
2. Select **More**
3. Select **Link → Relates to**
4. Select the required test plan or test set

Step 6. Create Test Execution from the Test Plan
1. Open the **Test Plan**
2. Select **Create Test Execution**
3. Select **All Tests**

Step 7. Confirm that all test items link to the correct DEV task
Double-check that all test cases, test sets, and the test plan are linked to the correct development task.
