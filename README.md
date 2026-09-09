### JIRA STATUS AND ITS MEANING

### BUG

| # | Status | Category | Meaning |
| :--- | :--- | :--- | :--- |
| **1** | New | To Do | Initial creation status. The bug has just been filed and hasn't been looked at yet. Should be very short-lived. |
| **2** | ASSIGNED | In Progress | Bug has been assigned to a developer who is actively working on the fix. |
| **3** | POST | In Progress | A fix/patch has been posted (e.g., PR submitted) and is awaiting review or merge. |
| **4** | MODIFIED | In Progress | The code has been modified/merged. The fix is in the codebase but not yet available for QE testing. |
| **5** | ON_QA | In Progress | Fix is available in a build and ready for QE verification/testing. |
| **6** | Verified | Done | QE has verified the fix works as expected. The bug is confirmed resolved. |
| **7** | Release Pending | Done | Fix is verified but not yet deployed/released to customers. |
| **8** | Closed | Done | Fully finished resolution is correct, no further work needed. Can be reopened if necessary. |
| **9** | Failed QA | In Progress | QE verification failed — the fix doesn't work as expected. Goes back to dev for rework. |

### SUB TASK 

| # | Status | Category | Meaning |
| :--- | :--- | :--- | :--- |
| **1** | New | To Do | Initial creation status. Issue just created, hasn't been looked at yet. Should be very short-lived. |
| **2** | Planning | To Do | Collaborative work to understand what needs to be done and confirm understanding with stakeholders. |
| **3** | To Do | To Do | Work is understood and ready to be picked up, but not yet started. |
| **4** | In Progress | In Progress | Actively being worked on by the assignee right now. |
| **5** | Dev Complete | In Progress | Development is finished, awaiting validation/testing. |
| **6** | Testing | In Progress | Changes are being tested/verified. ← current status |
| **7** | Release Pending | Done | Work is complete and verified, but not yet deployed/released to customers. |
| **8** | Closed | Done | Fully finished — resolution is correct, no further work needed. Can be reopened if necessary. |

### STORY

## 1. 🔵 To Do Category
Statuses in this category represent work that hasn't started active development yet.

* **New:** The story has just been created. It serves as an initial placeholder before being categorized or refined.
* **Planning:** Team members and stakeholders are collaborating to define requirements, scope, and technical details before commitment.
* **To Do:** The story is fully refined, estimated, and prioritized in the backlog, ready to be picked up in a sprint.

## 2. 🟡 In Progress Category
Statuses in this category represent work currently underway in development, review, or testing.

* **In Progress:** Active code implementation or design work is being performed by the developer/assignee.
* **Dev Complete:** Code development is finished, PRs are merged, and the feature is awaiting QE/QA validation.
* **Testing:** Quality Engineering or testing teams are validating the changes against test cases (e.g., executing verification steps and Polarion test cases).

## 3. 🟢 Done Category
Statuses in this category represent completed work.

* **Release Pending:** Development and testing are complete, and the work is waiting to be shipped in an upcoming version release.
* **Closed / Done:** The story is fully delivered, verified, and closed with an appropriate resolution.
