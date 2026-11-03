# Risk Register: RCHN Patient Intake and Scheduling System
**Consultant:** Andres Macias
**Role:** Associate Consultant, NovaTech Consulting
**Engagement:** Regional Care Health Network (RCHN)
**Date:** 11-03-2026
---
## Risk Entries

### Risk 1
**Description:** If the untrained clinic staff fail to complete the training, then the team will encounter significant deployment disruptions such delays for the RCHN project.
**Probability:** High
**Impact:** High
**Score:** 9
**Response Strategy:** Mitigate, Send training teams to the two lagging clinics to conduct mandatory daily coaching session.
**Trigger or Monitoring Condition:** For the two untrained clinics, postpone the launching and maintain the old systems until training is complete.
**Owner:** Scrum Master is responsible for managing team capacity, addressing training delays and clear any roadblocks. Also collaborates with the RCHN Clinic Intake Manager because the intake manager is responsible for solving scheduling and staff availability.

### Risk 2
**Description:** If the standardized form mismatches during the automated migration process, then the patient data information will be inaccurate and delay intake and appointment process for the RCHN project.
**Probability:** High
**Impact:** High
**Score:** 9
**Response Strategy:** Mitigate, Add automated codes into the new process to look for mistakes in the old system before running the new system.
**Trigger or Monitoring Condition:** Monitor system logs continuously especially during staging data runs.
**Owner:** Developer is responsible for operating the database level. The developer manages any patients' information mixmatches and information safety. The developer also oversees the validation scripts and is responsible to pause any data pipelines in case any errors occur during the process.

### Risk 3
**Description:** If the clinic staff, does not have the User Acceptance Test completed, then the project will fail to secure the patients information for the RCHN Project.
**Probability:** Medium
**Impact:** Medium
**Score:** 4
**Response Strategy:** Accept, Provide evening or weekend script testing opportunities across all six clinics so they accomplish the task.
**Trigger or Monitoring Condition:** Create a log for the intake system for signed-off functional test scripts.
**Owner:** Product Manager is responsible for testing completion because the product manager makes sure that the final product's acceptance criteria is functional and ready. The product manager also ensures that UTA meets the users' needs.

### Risk 4
**Description:** If clinic staff does not get trained, then the team will increase expenses on technical support for the RCHN Project.
**Probability:** Low
**Impact:** Medium
**Score:** 2
**Response Strategy:** Transfer, Incorporate any vendor contracts and include deadlines and support.
**Trigger or Monitoring Condition:** Review technical progress with external network engineers.
**Owner:** Project Manager is responsible for managing third party threats to oversee external relationships, contractual boundaries. The Project Manager also is responsible for timeline milestones of the project.

### Risk 5
**Description:** If temporary cloud storage lacks the proper security protocols, then patient health data could be leaked, and will break the law and violate the core rules of the RCHN Project guidelines.
**Probability:** Medium
**Impact:** High
**Score:** 6
**Response Strategy:** Avoid, Secure the migration environment to protect data by using end to end encryption.
**Trigger or Monitoring Condition:** Keep a continuous monitoring system for security protocols protection.
**Owner:** Developer is responsible for information security. The developer oversees any staging environments to prevent privacy and meet compliance with HIPPA standards to protect the users' medical information privacy.

---
## Bring Forward
**Week 5 assumptions:** 
Assumption 1: Assumed all six clinics will have a standardized form in the new intake system readiness.
Assumption 2: Assumed that the old intake system will match the new intake system so the team will not spend time on cleaning or fixing the old data.
Assumption 3: Assumed that the User Acceptance Testing will be completed (Finish-to-Start dependency) before all data is migrated.

**Week 7 backlog item:** 
As a Clinic Intake Coordinator, I want standardized RCHN intake form for all patients across six clinics so that I can access RCHN patients' medical information accurately to distinguish each patients' information across six clinics.

**Week 8 schedule item:** 
A Schedule Activity: “Code and build matching patient variables to the new system (Planned Week 3)"

---
## Assumption Connection
Threat 1: Unconfirmed Clinic Staff Training
The Assumption: Assumed all six clinics will have a standardized form in the new intake system platform readiness.
The Uncertainty: While the system assumes a standardized form, it is uncertain if all staff across all six clinics will be trained on how to use it before go-live, especially since two clinics are currently missing training.
Project Objectives Affected: If staff cannot use the new form on day one, patient check-ins will slow down, causing major delays and a poor experience. (Scheduling and Quality can be affected).

Threat 2: Patient Data Discrepancies during Migration
The Assumption: Assumed all six clinics will have a standardized form in the new intake system platform readiness.
The Uncertainty: The new form requires clean data, but the current data in the six old clinic system platform might not match. Combining these different systems could cause patient data to get mixed up or lost during the migration.
Project Objectives Affected: Failing to separate patient details correctly ruins data accuracy, it risks mixing up medical records, and breaks regulatory rules. (Quality and Compliance can be affected)

---
## Score Justification
Threat 1: Unconfirmed Clinic Staff Training:  I will rate the probablity high because having six clinics migrating information and two are behind schedule, it is lilkely that the clinic staff will not be fully trained by launching date. I will rate the impact high because if the clinic staff can not standardize on launch date then it will not go-live. If they can not operate the new system, the patient check in and waiting times will casue delays. We have to take into consideration that intake is critical and needs to be adapted since day one.

Threat 2: Standardize form Mismatches: I will rate the probablity high because moving information from six different clinics into a single standardized form requires a high intake operation, it can cause possible patients' data  being mismatched during the process. I will give a high impact rate because failing to move patients' data can threaten the patients' safety rules if the data is not moved correctly and it can cause future regulatory compliance.

---
## Risk Reflection
### Highest Priority Risk and Project Impact
Scope and Resource: The project goal is to launch all six clinics at the same time, however, if the two clinics untrained staff have are not been completed, these will  fall behind and it will delay the project goal. MIlestones will no be completed on time and this will require to hire extra staff for training causing cost for the project. If it is decided to launch without being ready, it will also cause system failures and rollbacks.

Go-Live Readiness & System Quality: The clinic staff and the intake coordinator are essential for the new system and if they can not use the new platform, the clinic readiness drops to zero. The clinics will face intake delays, long patient wait times, and operational paralysis.

Stakeholder Confidence: If all the clinics intake system are not ready to be launched on schedule, the clinic patients' information data might get destroyed, this means this will destroy user trust. Stakeholder confidence is at risk and it will damage the patient care community. 

### Risk vs. Issue Distinction
Risk 1: Unconfirmed Clinic Staff Training
Verification: Although the deployment scores show a training lag of two clinics, the go-live date sits still in the future leading this into a risk trigger so the threat remains as a future uncertainty that active mitigation can still  be prevented.

Risk 2: Unnoticed Appointment Inconsistencies
Verification: Because the old data has not been extracted from the old system, then new information has not beed added in the new system matching patients' information data could mismatch at a large scale if training has been not completed. 

Risk 3: Incomplete User Acceptance (UAT)
Verification: The project has not yet reached the formal, it is predicted to reach the milestone: UAT Sign off and it will delay the user's acceptance criteria functionality.

Risk 4: Lagging Vendor Interface Connectivity
Verification: If vendor communication is slow, the integration delay will become a future risk and the external billing and lab networks will continue in the early stage.

Risk 5: Patient Privacy Breaches 
Verification:  Data integrity remains uncompromised, therefore HIPPA medical viloations on the project are safe. The project remains secure and unlikely to be a threat.

---
*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
