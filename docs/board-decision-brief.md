# Board decision brief — ClinicalCompanion

> **Decision: NO-GO pending remediation and reassessment**  
> Educational simulation · No real patients, products, or clinical services.

## Situation

A fictional healthcare software company proposes to introduce a generative-AI clinical decision-support system for EU physicians. A third-party model provides diagnostic suggestions from clinical records. Decision-makers need to know whether clinical, legal, and operational evidence is sufficient for launch.

## Key evidence

| Area | Observed case finding | Board implication |
| :--- | :--- | :--- |
| Regulation | 14 of 16 assessment requirements have gaps | Approvals depend on documented closure, not a headline percentage |
| Model safety | 3.4% hallucination rate vs. internal 2% threshold | Validation and stronger safeguards required |
| Disaggregated performance | Four subgroups below internal 90% Top-3 accuracy target | Evaluate performance and patient risk in each intended use case |
| Risk treatment | Projected aggregate score falls from 120 to 63 | Verify mitigation effectiveness; do not count projected controls as implemented |
| Foundation-model vendor | 65.2% composite assessment score | Conditional approval pending material supplier evidence |
| Regulatory readiness | Medical-device conformity process unresolved | Confirm qualification, class and required conformity route |

## Proposed launch gates

| Gate | Evidence necessary for re-review | Proposed accountable owner* |
| :--- | :--- | :--- |
| Clinical validation | Independent representative testing, pre-agreed safety thresholds, clinical sign-off | Clinical Safety Lead |
| Hallucination mitigation | Demonstrated reduction in medically consequential error scenarios | Model Validation Lead |
| EU regulatory pathway | Documented MDR / AI Act applicability and conformity evidence | Regulatory Affairs |
| Data protection | Completed DPIA; health data, subprocessors, transfers and retention assessed | DPO / Privacy |
| Vendor assurance | Supplier documentation, change management, continuity, contractual protections | Vendor Risk / Legal |
| Monitoring and response | Tested incident playbooks, operational measurements and rollback criteria | Engineering / Operations |

*Owners are **suggested governance roles**, not people confirmed in the scenario.

## What would reverse the decision?

1. Close and verify safety-critical and legally mandatory gaps.
2. Reassess subgroup performance and control effectiveness with clinical experts.
3. Confirm supplier and sensitive-data protections.
4. Demonstrate technical monitoring, incident response and recovery capability.
5. Submit evidence to accountable decision-makers for explicit acceptance of remaining risk.

## Important interpretation

The illustrative weighted readiness score of **41.5%** is a decision-support device—not a legal compliance percentage or medical safety certification. The NO-GO recommendation is based on unresolved high-consequence release blockers.

[Return to case study](../README.md)
