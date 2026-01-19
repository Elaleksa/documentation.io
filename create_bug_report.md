# 🐞 **Bug Report – Jira**
This instruction describes how to create a bug in Jira.

# 🔍 **Purpose**
Bug reports help the team identify, track, and fix defects found during testing.
A well-written bug ensures clear understanding of the issue, faster analysis, and efficient resolution.

# 🎯 **Scope**
This instruction is intended for QA engineers and team members who execute manual test cases and report defects in Jira.

# 🚀 **Prerequisites**
Before you start creating a bug, make sure you have:
- Access to Jira
- A test case with an identified defect
- Clear understanding of the expected system behavior
- Information about the test environment

# 🧪 **What is a Bug?**
A bug is a Jira task used to report an issue where the actual system behavior differs from the expected behavior.
Bugs are linked to test cases and development tasks and are prioritized based on impact and urgency.

# 🧩 **How to create a bug in Jira?**

### Step 1. Create a bug task
1. Open the **Test Case**
2. Select the step where the defect occurs
3. Select **Defects**
4. Click **+**
5. Select **Create Defect**

---

### Step 2. Fill in the bug fields
In the **Create Issue** window, fill in the following fields:

| Field        | Value |
|--------------|-------|
| Project      | Select the project where the defect belongs |
| Issue Type   | Select **Bug** |
| Summary      | Enter a short, clear defect name |
| Priority     | Select from **Low** to **Highest** |
| Description  | Include **Preconditions**, **Actual Result**, and **Expected Result** |
| Environment  | Specify the environment where the test was executed |
| Assignee     | Select the team member responsible for fixing the bug |
| Sprint       | Select the sprint where the bug will be worked on |
| Team         | Select the responsible team for bug fixing |

All other fields can remain empty at this stage.

---

### Step 3. Save the bug
1. Review the entered information
2. Click **Create** to save the bug

# 📎 **Notes**
- Write clear and reproducible bug descriptions
- Always verify the environment before reporting a defect
- Link the bug to the related test case and development task when possible
