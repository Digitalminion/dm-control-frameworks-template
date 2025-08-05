<!-- BEGIN AI HEADER: 85 LINES -->
<!-- BEGIN AI FILE SUMMARY -->
<!-- 
    TOPICS: nist-csf-gv-rm-06, risk-calculation, risk-methodology, governance-template
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/
    RATING: foundational
    PURPOSE: NIST CSF GV.RM-06 Standardized Risk Calculation Method Template
    UPDATE: High
    Updated: 2025-08-05
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    GV.RM-06 TEMPLATE PURPOSE: This template supports development of a standardized method for calculating, documenting, categorizing, and prioritizing cybersecurity risks.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this GV.RM-06 template:
    1. Describe quantitative / qualitative risk scoring.
    2. Reference risk register templates and scoring matrices.
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER: 85 LINES -->

# GV.RM-06 - Standardized Risk Calculation Method

## Subcategory Information

**Subcategory ID**: GV.RM-06  
**Function**: Govern (GV)  
**Category**: Risk Management Strategy (RM)  
**Subcategory**: A standardized method for calculating, documenting, categorizing, and prioritizing cybersecurity risks is established and communicated  
**Implementation Tier**: {{CURRENT_IMPLEMENTATION_TIER}}  
**Target Tier**: {{TARGET_IMPLEMENTATION_TIER}}  
**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Last Reviewed**: {{LAST_REVIEWED_DATE}}  
**Next Review**: {{NEXT_REVIEW_DATE}}

## GV.RM-06 Outcome

All cybersecurity risks are evaluated using a consistent methodology, enabling aggregation, comparison, and prioritization at the enterprise level.

## Standard Risk Formula

`Risk = Likelihood × Impact`

Define scales:
- Likelihood: 1 (Rare) – 5 (Almost Certain)
- Impact: 1 (Negligible) – 5 (Catastrophic)
- Risk Score: 1 – 25

| Score Range | Risk Rating | Treatment Guidance |
|-------------|------------|--------------------|
| 20-25 | Extreme | Immediate executive action |
| 12-19 | High | Mitigate within 30 days |
| 6-11 | Moderate | Track and treat per plan |
| 1-5 | Low | Accept or monitor |

## Implementation Steps

1. Approve risk taxonomy and scoring matrix.
2. Update risk register template with new fields.
3. Train risk owners on methodology.
4. Integrate scoring calculation into GRC tooling.

## KPIs

| Metric | Target |
|--------|--------|
| % of new risks scored using standard method | 100% |
| Variance in scoring between risk assessors | < 10% |

## References

- NIST SP 800-30 Risk Assessment
- ISO/IEC 27005:2022 Risk Management

---
*Generated using the NIST CSF GV.RM-06 template for {{ORGANIZATION_NAME}}.*