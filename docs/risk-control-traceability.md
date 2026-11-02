# Risk-to-control traceability

This supplemental map connects the main scenario findings to control objectives and verification tests. It is an *illustrative extension*, not a claim that controls are implemented.

| Scenario risk theme | Control objective | Possible implementation / evidence | Verification test | AI RMF function |
| :--- | :--- | :--- | :--- | :--- |
| Clinical hallucinations | Prevent unsupported or harmful diagnostic suggestions | Source grounding, clinical review, adverse-case regression tests | Measure medically consequential error rate against approved thresholds | Measure / Manage |
| Bias and subgroup underperformance | Deliver acceptable performance across intended populations | Cohort-based validation, sample adequacy review, use-case restrictions | Test each clinically relevant subgroup, with confidence intervals | Map / Measure |
| Health-data privacy | Lawful, secure processing and accountable transfers | DPIA, purpose/retention controls, processor map, SCC/TIA evaluation where applicable | Audit flows, access, vendor routing and data deletion | Govern / Manage |
| Third-party model opacity | Maintain supplier evidence and change control | Model documentation, safety assurances, contractual notification rights | Verify supplier evidence and simulate a material model update | Govern / Manage |
| Model drift | Detect degradation before patient safety is affected | Subgroup drift triggers, validation cadence, change gates | Demonstrate alerts, escalation, and documented requalification | Measure / Manage |
| Human over-reliance | Preserve clinical responsibility and intervention ability | Clear intended-use limits, training, override and logging | Conduct human-factors testing and simulated unsafe recommendations | Govern / Manage |
| Incident-response gaps | Detect, contain, report and learn from AI incidents | S1–S4 taxonomy, playbooks, assigned incident leadership, exercises | Run tabletop tests for hallucination and privacy incidents | Manage |
| Incomplete MDR / AI Act evidence | Establish defensible market-access decision | Regulatory memo, technical documentation, conformity assessment tracking | Review documented legal pathway and evidence inventory | Govern |

## Useful audit questions

- Are **projected** residual risk scores being mistakenly described as **achieved** reduction?
- Have critical clinical thresholds been agreed by qualified stakeholders, rather than assumed?
- Are the vendor's certifications and data residency claims independently evidenced?
- Are uptime and p95 response latency actually measured, rather than inferred?
- Can release approval be traced to named accountabilities, evidence, and explicit risk acceptance?

A composite score should never replace a statutory conformity decision or patient-safety evaluation.

[Return to case study](../README.md)
