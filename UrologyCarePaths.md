# Urology Care Paths.

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


## 2. Prostate and Prostate Bed with Nodes
- Copy Prostate Only Care Path.

![Prostate / Bed and Nodes Care Path](./ProstateNodes_Hormones.svg)

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
| Urology Peer Review | 4 Hours | PeerReview + Auto Assign CCO | Yes - Thurs 11:00 - 12:00 |
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
