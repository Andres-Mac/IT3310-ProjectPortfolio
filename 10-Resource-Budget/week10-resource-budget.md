# Resource Plan and Budget: RCHN Patient Intake and Scheduling System
**Consultant:** Andres Macias
**Role:** Associate Consultant, Project Manager, NovaTech Consulting
**Engagement:** Riverside Community Health Network (RCHN)
**Date:** November 10, 2026
---
## Resource Plan

### Human Resources
| Role | Capability / Project Need | Weeks | Hours per Week | Total Hours | Estimated Rate | Estimated Labor Cost |
|---|---|---:|---:|---:|---:|---:|
| Project Manager |  Capability Manages timelines, coordinates teams, mitigates risks, and updates stakeholders. Work Driving the Need: This role ensures unified integration management across all six clinics and aligns NovaTech with Marcus Webb's vision to accomplish the RCHN project.| 14 | 40 | 560 hrs | $125 | $70,000 |
| Developer | Capability: Builds databases, moves data securely, writes test scripts, and configures testing environments.  Work Driving the Need: This role ensures Legacy Data Migration work package, fixes appointment errors, clarifies external system connections, and secures cloud storage to prevent patient data leaks.| 12 |35 | 420 hrs | $130 | $54,600 |
| QA Analyst | Oversees automated testing frameworks, tracks software defects, and validates launch readiness. Work Driving the Need: This role is driven by Acceptance Testing (UAT) work packages to prevent incomplete testing. | 10 | 25 | 250 hrs | $90 | $22,500 |
| Training Coordinator | Provides staff training, tracks clinic and staff readiness, delivering training lessons, and manages the clinic expectations. Work Driving the Need: This role is driven by the Clinic Readiness & Training work package to address delayed staff training at two of the six clinics falling behind schedule. | 8 | 25 | 200 hrs | $80 | $16,000 |

### Technology Resources
- Database Sandboxes, Automated Testing Software, Security & Encryption Software — Estimated Cost: $10,000 — Basis: • Database Sandboxes: Database Sandboxes: protected virtual test environments utilized to validate the revised database schema.
• Automated Testing Software: Automated testing software used by the QA Analyst to run fast testing scripts across all six clinics. 
• Security & Encryption Software: Code inspection software used by the Developer to audit and protect against patients data exposure.

### Infrastructure Resources
- Cloud Staging & High Speed Network Connections — Estimated Cost: $7,000 — Basis: • Cloud Staging: Protected Cloud Staging Environments used to hold and organize information during pipeline transfers. 
• High-Speed Network Connections: High-speed network connections, they function to extract large legacy databases rapidly without lagging live, daily clinic operations.

### Third-Party Resources
- Legacy System Support Contractors,Independent Compliance Auditor, & Contracted Training Experts — Estimated Cost: $20,000 — Basis: • Legacy System Support Contractors: Vendor software specialists or consultants kept available to trace old database linkages and assist the Developer with complex data extractions.  
• Independent Compliance Auditor: An independent compliance auditor responsible for conducting an official legal check prior to launch to ensure complete data protection compliance. 
• Contracted Training Experts: Assist the training coordinator to train staff for falling-behind clinics to up to speed up quickly. 
---
## Estimation Approach
For the RCHN budget, I combined the bottom-up and parametric estimation techniques to align with 14 weeks schedule with specific clinic requirements.
• Parametric Estimation
        • Usage: Aligns the team timelines based on the number of clinics (6 clinics)
        • Example: Adjusts the QA Analyst to 10 weeks and the Training Coordinator to 8 weeks across the 6 clinics.
        • Fit: Keeps staffing timelines within the strict 14-week project limit.  
• Bottom-Up Estimation
        • Usage: Calculates expenses from individual work assignments and targeted risk registry data.
        • Example: Totals the Developer baseline by multiplying 12 weeks × 35 hours × $130/hr.
        • Fit: Facilitates accurate pricing for documented risk items, like the $10,000 safety pool for data leaks (50 hours × $200/hr), instead of guessing with flat percentages.
• Why Top-Down Comparisons Were Rejected
        • Reason: Broad comparisons miss RCHN's specific training delays and complex databases.

Based on the provided RCHN Project Budget Structure, here are two key labor assumptions that would change if these prove inaccurate.

Assumption 1: Fixed Timeline Caps on Specialty Roles

• The Assumption: The budget assumes that the human labor required for rollout can be tightly restricted to staggered and the QA Analyst is only needed for 10 weeks and the Training Coordinator is only needed for 8 weeks across the 6 clinics, rather than the full 14-week project window.
• Budget Impact if Inaccurate: If clinic learning delays or deployment bottlenecks force either role to extend to the full 14-week duration, the labor baseline will increase.

Assumption 2: Standard Part-Time Weekly Hours for Delivery

• The Assumption: The budget assumes that the workload for rollout across all 6 clinics can be successfully executed using a part-time framework of 25 hours per week for both the QA Analyst and the Training Coordinator.
• Budget Impact if Inaccurate: If the workload volume of data discrepancies across the 6 clinics requires these roles to go up to full-time (40 hours per week) to stay within the 14-week limit, costs will jump significantly.

---
## Contingency Reserve
### Risk-Based Cost Exposure
- Risk Clinic Learning Delays & Launch Deadlines: Extends the Training Coordinator by 6 weeks (from 8 to 14 weeks). — Potential Cost Exposure: $12,000
- Risk Migration Mismatches & Data Discrepancies: Increases the QA Analyst from part-time (25 hrs/wk) to full-time (40 hrs/wk) for 10 weeks. — Potential Cost Exposure: $13,500

**Recommended Contingency Reserve:** $25,500

 Adjusting the total to a flat $30,000 provides complete coverage for these specific resource extensions while keeping a $1,440 micro-reserve for minor environment fluctuations.

---
## Budget Summary
**Total Labor Cost:** $163,100  
**Total Non-Labor Cost:** $37,000
**Contingency Reserve:** $30,000 
**Estimated Project Budget:** $249,672

### Largest Cost Category
The largest cost category is Human Labor, totaling $182,672 (representing roughly 73% of the entire project budget).
Why This Is Appropriate for RCHN:
• Migration Complexity Requires Specialized Talent: Migrating a patient intake and scheduling system across six clinics requires highly specific clinical data mapping, database building, and extensive quality assurance to handle sensitive information smoothly.
• Mitigation of Active Project Risks: The specialized human roles explicitly address known project bottlenecks. For example, allocating explicit hours for a dedicated Training Coordinator directly combats the learning delays in the two clinics that have fallen behind schedule.
• Risk Over Automation: Because patient healthcare records require careful manual verification and secure software engineering to prevent active leakage from cloud repositories, the project relies heavily on skilled personnel over automated infrastructure.                                                                        • Structural Optimization: Heavy front-end investment in targeted, specialized labor directly ensures the system meets its clinical readiness goals within a strict 14-week timeline constraint.

---
## Budget Tradeoff Analysis
A 10% cut reduces the budget by $249,672, lowering the project cap from $249,672 to $224,704.80. Before agreeing, I would check the schedule, labor hours, and risk register to protect project quality.

Key Analysis Areas Before Agreement:

• Labor Elasticity: Can we cut specialized hours without breaking the hard 14-week project limit?
• Reserve Vulnerability: Can the project survive clinic learning delays or database errors without a safety net?
• Contract Flexibility: Which non-labor costs are locked flat fees versus flexible, usage-based lines?

Two Critical Tradeoffs and Risks

Tradeoff 1: Cutting the Contingency Reserve

• The Action: Shrinking the $30,000 reserve to $5,032.80 to protect baseline labor and tools.
• The Risk: Immediate budget breach. If data errors or training delays occur, there is no money to fix them, breaking the new cap instantly.

Tradeoff 2: Shortening Labor Timelines

• The Action: Cutting the Developer from 12 to 10 weeks and the QA Analyst from 10 to 8 weeks.
• The Risk: Low system quality and rollout delays. Rushing database testing causes severe live defects, while less training time stalls deployment across the 6 clinics.

---
*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
    
