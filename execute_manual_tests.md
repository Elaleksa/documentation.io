# 📓 **How to execute Manual Test cases**
This instruction explains how to execute a manual test case in Jira and helps QA validate requirements and document results.

# 🔍 **Purpose**

The purpose of this instruction is to describe a clear and consistent process for executing manual test cases in Jira, ensuring accurate validation of requirements, proper documentation of test results, and timely identification and reporting of defects.

# 🚀 **Prerequisites**
Before executing a test case, ensure that you: 
  - Have access to Jira 
  - Have access to the required Test Execution tasks  
  - Have all test cases reviewed and have `Ready` status to execute them   
  - Have test environment prepared and accessible  

# **Process Description (Step-by-Step)**

**Step 1. Open the Test Execution**  
Open **Test execution** task > select specified test > select on the **Play ▶️ button** > select **Execute**  

**Step 2. Execute the test**  
Start executng the test from **Test Details > Action 1** and contunie step by step  

**Step 3. Update the step status**  
Select the status based on the step result:  

| Status       | Meaning      |
|--------------|--------------|
| ⚪ TODO         | The execution has not started |
| 🟢 PASS         | The step passed successfully |
| 🟡 EXECUTING    | The step is currently in progress |
| 🔴 FAIL         | The step failed or a defect was found |
| 🟤 ABORTED      | The step cannot be executed because a previous step failed |
| 🔵 SKIPPED      | The step is skipped due to system changes but does not affect the result |
| 🟣 BLOCKED      | The step cannot be executed (e.g., environment problems) |  

 

**Step 4. Add execution details**  
- Add the Actual result to each step  
- Add comments if you need  
- Link defects if any step fails or there is a bug  
- Attach evidences (screenshots, logs, videos) if necessary

**Step 5. Complete the test execution**   
If all steps are marked as `PASS`, the test case automatically changes its status to `PASS`
