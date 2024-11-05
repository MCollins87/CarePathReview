# Urology

Begin by taking a deep dive into Urology CarePaths. 

## Time needed for Clinician tasks. 

[Audit](./TimeAudit.md) performed by MU, asking CCO's to complete table with length of time needed to complete outlining of particular sites. This was combined with the number and type of patients through Aria in the last 12 months. 

Findings from this audit found that Urology Dr's need a combined total of 8 half-day planning slots per week, or 18hrs/week. 

For Urology in particular, the CCO's identified the following plan types:

| Plan Type			| Time needed	|
| ----------------- | ------------- |
| Prostate			| 45min (0.75hr)|
| Prostate + ln		| 2hr			|
| Prostate bed		| 45min (0.75hr)|
| Prostate Bed + ln	| 2hr			|
| PACE Prostate only| 1.5hr			|
| PACE + Node		| 3hr			|
| Bladder 			| 45min (0.75hr)|
| Bladder + Node	| 2hr			|
| Simple Pall.		| 30min (0.5hr)	|

For Dr contouring task, create the following outlining appointments:

| Task / Care Path		| Appointment Length 	| Pathway Approval 	|
|---------------------- | --------------------- | -----------------	|
| Prostate /  Bed 		| 45min 				| Physics			|
| Prostate / Bed + LN	| 2hr 					| CCO				|
| SABR Prostate 		| 1.5hr					| CCO				|
| SABR Prostate + LN	| 3hr					| CCO				|
| Bladder				| 45min					| CCO				|
| Bladder + Node		| 2hr					| CCO				|
| Palliative Urology	| 30min					| NA/VSIM			|

All tasks to be assigned to:
* Primary Oncologist
* CCO group
* Urology CCO group

## Dr availability
| Day 			| CCO available					|
| ------------	| ------------------------------|
| Monday		| RA (AM), YSN (AM)				|
| Tuesday		| CJ (PM)						|
| Wednesday	| RA, CJ(PM), MU(AM), YSN(PM)	|
| Thursday 	|								|
| Friday		|								|

Peer Review on: 
- Thursday 11:00 - 12:30
- Wednesday 14:30 - 15:30

*This shows seven half day planning sessions. The [audit](./TimeAudit.md) showed eight sessions were needed for Urology planning.* 

# Urology Care Paths.

After significant testing with different watermarks etc. it was very difficult to achieve sensible timings between tasks. For example, if a Prostate were to start on a Wednesday or Thursday, the carepath would attempt to schedule peer review the Thursday prior. This gave less than a week for Physics planning and Central inputting. 

- 1st Fraction not part of Care Path - to be scheduled seperately.

## 1. Prostate and Prostate Bed Only
- Same Care Path to be used for both hormone delay and imediate start.
- If starting imediately, "Pre-CT Phone Call" and "Micro-enema Prescription" to be removed.
- Pin Care Path to CT Scan.
 
 
![Prostate/bed CarePath](./Assets/ProstateOnly_Hormone.svg)
 
| Activity           | Lag time  | Resource           | Water Mark |
| ------------------ | --------  | -----------------  | ---------- |
| Pre-CT Phone Call  | N/A       | Pre-CT Phone Call  | Monday |
| Micro-enema Prescription | 1 Hour | CCO; Clare Murphy | N/A |
| Justification | 4 Days | Pre-Treatment | N/A |
| Pre-assessment | 1 Day | Planning Room | N/A |
| CT Scan | 10 Minutes | Siemens CT | *Pinned Activity* |
| Import CT | 1 Day | Pre-Treatment | N/A |
| Rad Contoruing | 1 Hour | Pre-Treatment | N/A | 
| Prostate/Bed CCO Planning | 1 Day | Auto Assign CCO | Yes - Each CCO to their set time |
| Urology Peer Review | 4 Hours | Auto Assign CCO | Yes - Thurs 11:00 - 12:00 |
| Prostate/Bed VMAT Planning | 1 Day | Physicists | N/A |
| Prostate/Bed VMAT Checking | 4 Hours | Physicists | N/A |
| Physics Plan Approval | 1 Hour | Physicists | N/A |
| PSQC Pre-Check | 2 Hours | Physics PSQC | N/A |
| Fraction 0 | 1 Hour | Physics QC | Mon-Thurs 18:00 - 21:00 |
| PSQC Analysis | 1 Hour | Physics PSQC | N/A |
| PSQC MPE Review | 1 Hour | Physics PSQC | N/A |
| PSQC Check | 1 Hour | Physics PSQC | N/A |
| Aria Planning Approval | 4 Hours | Central Report | N/A | 
| Post Aria Integrity Check | 2 Hours | Physicists | N/A |
| Aria Treatment Approval | 2 Hours | Central Report | N/A |
 
 
### 2. Prostate and Prostate Bed with Nodes
- Copy Prostate Only Care Path.
 
![Prostate / Bed and Nodes Care Path](./Assets/ProstateNodes_Hormone.svg)
 
| Activity           | Lag time  | Resource           | Water Mark |
| ------------------ | --------  | -----------------  | ---------- |
| Pre-CT Phone Call  | N/A       | Pre-CT Phone Call  | Monday |
| Micro-enema Prescription | 1 Hour | CCO; Clare Murphy | N/A |
| Justification | 4 Days | Pre-Treatment | N/A |
| Pre-assessment | 1 Day | Planning Room | N/A |
| IV Cannulation | 0 minutes | Planning Room | N/A |
| CT Scan | 10 Minutes | Siemens CT | *Pinned Activity* |
| Remove Cannulation | 20 Minutes | Pre-Treatment | N/A |
| Import CT | 1 Day | Pre-Treatment | N/A |
| Rad Contoruing | 1 Hour | Pre-Treatment | N/A | 
| Prostate/Bed + LN CCO Planning | 1 Day | Auto Assign CCO | Yes - Each CCO to their set time |
| Urology Peer Review | 4 Hours | PeerReview + Auto Assign CCO | Yes - Thurs 1:00 - 12:00 |
| Prostate/Bed VMAT Planning | 1 Day | Physicists | N/A |
| Prostate/Bed VMAT Checking | 4 Hours | Physicists | N/A |
| Urology Plan Approval | 1 Hour | UrologyCCO + Primary CCO | N/A |
| PSQC Pre-Check | 2 Hours | Physics PSQC | N/A |
| Fraction 0 | 1 Hour | Physics QC | Mon-Thurs 18:00 - 21:00 |
| PSQC Analysis | 1 Hour | Physics PSQC | N/A |
| PSQC MPE Review | 1 Hour | Physics PSQC | N/A |
| PSQC Check | 1 Hour | Physics PSQC | N/A |
| Aria Planning Approval | 4 Hours | Central Report | N/A | 
| Post Aria Integrity Check | 2 Hours | Physicists | N/A |
| Aria Treatment Approval | 2 Hours | Central Report | N/A |
 
