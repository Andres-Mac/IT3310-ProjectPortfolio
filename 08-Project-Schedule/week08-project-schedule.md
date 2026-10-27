# Project Schedule: RCHN Patient Intake and Scheduling System
**Consultant:** Andres Macias
**Role:** Associate Consultant, Project Manager, NovaTech Consulting
**Engagement:** Regional Care Health Network (RCHN)
**Date:** October 27 2026
---
## Work Breakdown Structure

### Grouping 1: Initiation
- Integrate Project Management Plan: (Scope, Risk, Quality)
- Project Charter and Stakeholder Register Approval
- Finalize Required Documentation

### Grouping 2: Planning
- Define the Scope, Risk, Quality
- Identify the product backlog
- Identify product service and create a WBS outline

### Grouping 3: Development
- Infrastructure and Platform setup
- Architecture and system design specifications
- User experience analysis

### Grouping 4: Deployment
- Pre-launch live pilot
- Handover implementation documentation
- End User training materials


### WBS Rationale
The WBS represents the week 5 scope by breaking down the complete cycle of replacing the RCHN intake patient scheduling system infrastructure into six-clinics, deliverable - oriented phases. Phase 1: initiation - project charter and stakeholders, phase 2: planning - define the scope, phase 3: development - infrastructure, phase 4: deployment - captures critical systems and operations during the launch. As all the above components are needed and accounted for, integration of electronic health records and other external items are still require clarification. Regarding technical software but this can be a separate phase as we move forward with this project.

---
## Task Dependencies
- Predecessor task: Transfer patient data to a new database. → Successor task: Begin system testing on the new database, Dependency type: Finish-to-Start
- Predecessor task: Start building the core platform infrastructure → Successor task: Start writing the infrastructure technical documentation, Dependency type: Start-to-Start
- Predecessor task: Finish training the clinic staff on the new system → Successor task: updating the training material archive, Dependency type: Finish-to-Finish

### Dependency Logic
I believe the Finish-to-Start dependency could affect the schedule. because transferring data to a new database is a critical path due to the fact that, data validation, testing validation and training can not proceed with an empty system. It is important to understand the sequencing within the process. A 2 week delay can cause milestones to be missed and to an untested system/software.

---
## Activity Schedule
| ID | Activity | Duration (working days) | Predecessors | Start week |
|---|---|---:|---|---:|
| A | Map Patient Data | 5 Days | None | Week 1 |
| B | Code/ Building matching patient variables to the new system. | 10 Days | A | Week 2 |
| C | Verify the transferred patient data | 5 Days | B | Week 4 |
| D | User Testing | 10 Days | C | Week 5 |

### Scheduling Assumptions
I estimated the duration of the project based on the activities/tasks needed prioritizing them accordingly. Some tasks will need 5 days, other tasks will take 10 days, because they require extra time to be fulfilled. For the tasks who required 5 days, the approach and low priority were taken into consideration assuming that the team will be on top of each week managing the project so uncertain and unpredictable items might delay the project.

---
## Milestones
- Verify the transferred patient data, The clinic intake manager will know this was met by simply login into their new dashboard system on the final day fo week 3 and access a sample of current active patient files successfully populated in the intake fields.

- User Testing, Patient intake. Tests should be executed by start ad patients. The clinic intake manager will know this was met because it will be necessary to run a live end-to-end patient onboard simulation on the new interface. The clinic intake manager should check/ test run a patient, verify, insurance, without facing any errors in the new system. Then it will be completed and a successful milestone.

### Critical Path Analysis
Identification of the critical path and total duration 

Critical Path 1 (A-B-C-D) is the critical path because it is the longest sequence of dependent tasks required to complete the RCHN project.

Total RCHN Project duration: 30 working days 

If any activity slips by 2 days, it will extend the project's duration and the final project instead of taking 30 days; it will be accomplished in 32 days.

---
## Schedule Reflection
### Scope Connection
WBS Grouping: Phase 3 - Development. 
This scope requires information alignment; therefore, replacing an old patient intake infrastructure into a functional workflow, it is necessary to ensure Deployment (User Testing) depends on phase 3. 

### Objective Connection
Verifying the transferred patient data, supports the (W5) week 5 objective because this is a safe way to switch from old software to new platform. This objective focuses on accurate and sensitive records that should be migrated and can be managed by the clinic intake manager to confirm a successful data transfer.

---
*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
