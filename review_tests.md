# 📓 **How to Review Manual Test cases**
This instruction describes how to review manual test cases before execution and/or automation. 

# 🔍 **Purpose**

Test reviews are needed to ensure test cases are accurate, complete, consistent, and aligned with requirements. 

# 🚀 **Prerequisites**
Before start you need:  
- Access to Jira 
- Permission to view and edit Test issues 
- Understand the test design guidelines 
- Be familiar with project requirements and acceptance criteria 

# 🗒️ **Process Description (Step-by-Step)**

## Internal review  

Internal review means checking test cases by another test engineer from the team.  
The tester who created the test case cannot review it.  
If you cloned or updated test case with minor changes, you may review it by yourself. 

Prerequisites:  
- The tester adds a comment in the sub-task for test creation noting that internal review is required. 
- All test cases that need review are moved to READY FOR REVIEW by the test designer. 

### Step 1. Change the test status to REVIEW 

Change the status from `READY FOR REVIEW` to `REVIEW` and assign the test case to yourself  
Ready for Review > Start Review  

### Step 2. Add comments  

Add all review comments directly in the test steps under the Review column using this format: `[Reviewer Name Surname]: comment`  

> **Note:** 
> If you have no comments:
> 1. Change the test status to READY;
> 2. Reassign the test back to the original test designer;
> 3. Fill in the Internal Review section in the test description

### Step 3. Change the test status to OPEN or READY 

Use `OPEN` if further changes are required.  
Use `READY` if the test case is approved.  

## External review  

External review means checking test cases by the developer responsible for implementing the functionality under test.  
The test designer decides whether an external review is required. 

Prerequisites:   
- A test cases designer contacts the responsible developer and shares the link to the test repository folder;  
- All test cases that need review are moved to the READY FOR REVIEW by the test cases designer;  
- The tester adds a comment in a sub-task that the external review is required.  

### Step 1. Change the test status to REVIEW  
Change the status from `READY TO REVIEW` to `REVIEW` and assign the test case to yourself 

### Step 2 Add comments  
Add comments in the Review column using the format: `[Reviewer Name Surname]: comment`

> **Note:**  
If there are no comments:  
> 1. Change the test status to READY  
> 2. Assign the test back to the test designer  
> 3. Fill in the External Review section in the description  
> 4. Notify the test designer that the review is complete   

### Step 3 Change the test status to OPEN or READY 

Use `OPEN` when further adjustments are needed.  
Use `READY` when the test case is approved. 

