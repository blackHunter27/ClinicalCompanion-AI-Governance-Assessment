# Methodology and limitations

## Scope and input evidence

The repository contains a simulated Udacity healthcare AI governance case, including its original CSV and JSON reference files, the completed Python notebook, six generated visualizations, and a six-sheet Excel governance assessment. There is no real clinical deployment, real-world patient data, external vendor audit, or regulatory submission.

## Approach

**Regulatory screening:** Intended use, exclusions, preliminary EU AI Act Article 5 / Article 6 assessment, MDR Rule 11 working classification, and requirements gap analysis.

**Risk:** 5×5 ordinal likelihood × impact matrix; risks organized by NIST AI RMF Govern / Map / Measure / Manage. Before/after comparisons use the scenario's *projected* residual scores.

**Vendor:** Category percentages are calculated as earned points divided by maximum points across the 27 criteria. The vendor's score is **not** equivalent to ISO certification or regulatory approval.

**Model performance:** Top-3 Diagnostic Accuracy compared with a **scenario-specific internal 90% target**. Below-target performance triggers investigation; a shortfall alone does not demonstrate a specific causal bias mechanism.

**Monitoring:** Defined KPIs, incident types, target response times, and data availability gaps. Taxonomy categories are not historical incident volumes.

**Decision:** Six readiness estimates were selected as an illustrative analytical aid. The weighted 41.5% value is not legal compliance, clinical validation, or an independently calibrated risk model.

## Interpretation boundaries

- **14/16:** Count of incomplete requirements within the provided 16-item assessment dataset, not the totality of legal duties.
- **47.5%:** Reduction in *summed ordinal risk scores* in a hypothetical mitigated state, **not** empirically measured patient-safety improvement or financial-risk reduction.
- **65.2%:** Supplied supplier score, not an objective vendor safety rating outside the case.
- **4 subgroups below target:** Evaluated subsets may overlap and differ in size; compare subgroup results with appropriate statistical and clinical validation.
- **41.5%:** Weighted analyst estimate; statutory conformity cannot be measured as a single percentage.
- **Severity distribution:** Classification of 10 potential incident types by maximum eligible severity, not evidence of incidents having occurred.
- **Medical-device classification:** Provisional educational working hypothesis, requiring expert determination if applied to a real product.
- **Source discrepancies:** The provided risk register marks two score-12 records as *High*, while the workbook scoring guide associates scores 10–14 with *Medium*. Source labels are preserved and discrepancy documented rather than silently changing raw data.

## Reproducing figures

Install dependencies from `starter/requirements.txt`, open `starter/governance_assessment.ipynb`, run cells in order, and inspect generated files in `starter/results/`. Python code and project outputs are provided for learning and review.


## Primary references

- [EU AI Act — consolidated text](https://eur-lex.europa.eu/eli/reg/2024/1689)
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [MDR 2017/745](https://eur-lex.europa.eu/eli/reg/2017/745/oj)
- [GDPR 2016/679](https://eur-lex.europa.eu/eli/reg/2016/679/oj)
- [Model Cards for Model Reporting](https://arxiv.org/abs/1810.03993)

[Return to case study](../README.md)
