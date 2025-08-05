<!-- BEGIN AI HEADER: 50 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: organization-profile, template, it-organization, context-documentation, security-maturity
    CONTENT: template, organizational-structure, it-environment, stakeholder-mapping, security-responsibility-assessment
    RELATED: context/organization/, methods/templates/, methods/adoption/, maturity_proposal.md
    RATING: template
    PURPOSE: Template for Documenting Organizational Profile, IT Environment, and Security Responsibility Maturity
    UPDATE: High
    SECURITY_MATURITY_LEVEL: assessment_template
    TARGET_AUDIENCE: ai_agents_and_implementers
    Updated: 2025-01-16
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    TEMPLATE CONTEXT: This enhanced template provides a standardized structure for documenting 
    organizational profile information and assessing security responsibility maturity that influences 
    NIST control implementation. The template now includes the Organizational Maturity Matrix (OMM) 
    assessment to determine appropriate documentation depth and implementation guidance.
    
    AI agents should use this template when gathering organizational context to ensure
    comprehensive coverage of factors that affect control selection and implementation,
    including the organization's security responsibility maturity level.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    TEMPLATE USAGE FOR AI AGENTS:
    
    WHEN CREATING AN ORGANIZATIONAL PROFILE WITH MATURITY ASSESSMENT:
    1. Copy this template structure exactly
    2. Replace [ORGANIZATION_NAME] with the actual organization name
    3. Fill in all bracketed sections with specific organizational information
    4. CONDUCT SECURITY MATURITY ASSESSMENT using the four-dimension framework
    5. Determine PRIMARY SECURITY_RESPONSIBILITY_LEVEL for template selection
    6. Update the AI header metadata fields for the specific organization
    7. Customize each section based on actual organizational characteristics
    8. Remove sections that don't apply or add organization-specific sections
    9. Ensure all information is accurate and up-to-date
    10. Use maturity assessment results to guide future template selections
    
    MATURITY ASSESSMENT REQUIREMENTS:
    - Must assess all four security responsibility dimensions
    - Must determine overall security ownership structure
    - Must identify primary audience for control documentation  
    - Must set technical depth expectations for implementations
    - Must establish appropriate implementation approach preferences
    
    VALIDATION RULES:
    - Must include AI header with accurate metadata
    - Must have complete organizational identification
    - Must document IT structure and governance
    - Must identify key stakeholders and decision makers
    - Must include compliance and regulatory context
    - Must document current security posture and maturity
    - Must complete Security Responsibility Maturity Assessment
    - Must provide template selection guidance based on assessment
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER: 50 LINES --> 

# [ORGANIZATION_NAME] - Organizational Profile with Security Maturity Assessment

## Organization Overview

### Basic Information
- **Organization Name**: [FULL_LEGAL_NAME]
- **Industry Sector**: [PRIMARY_INDUSTRY] / [SECONDARY_INDUSTRIES]
- **Organization Size**: [NUMBER_OF_EMPLOYEES] employees
- **Annual Revenue**: [REVENUE_RANGE]
- **Geographic Presence**: [LOCATIONS_AND_SCOPE]
- **Business Type**: [PUBLIC/PRIVATE/GOVERNMENT/NONPROFIT]

### Mission and Business Context
- **Primary Mission**: [CORE_BUSINESS_PURPOSE]
- **Key Business Objectives**: 
  - [OBJECTIVE_1]
  - [OBJECTIVE_2]
  - [OBJECTIVE_3]
- **Critical Business Functions**: [ESSENTIAL_OPERATIONS]
- **Customer Base**: [PRIMARY_CUSTOMERS_AND_STAKEHOLDERS]

## Security Responsibility Maturity Assessment

### Security Ownership & Accountability (Dimension 1)
**Current Level**: [business_led|it_led|engineering_led|infosec_led]

**Assessment Details:**
- **Primary Security Decision Maker**: [ROLE_AND_TITLE]
- **Security Budget Owner**: [ROLE_AND_TITLE]
- **Day-to-Day Security Responsibility**: [ROLE_AND_TITLE]
- **Security Incident Response Leader**: [ROLE_AND_TITLE]
- **Security Policy Approval Authority**: [ROLE_AND_TITLE]

**Level Justification:**
- **business_led**: Business stakeholders handle security as additional responsibility
- **it_led**: IT department owns security with general IT skills  
- **engineering_led**: Engineering teams integrate security into development/operations
- **infosec_led**: Dedicated information security professionals and teams

**Current Assessment**: [DETAILED_JUSTIFICATION_FOR_SELECTED_LEVEL]

### Security Specialization Depth (Dimension 2)
**Current Level**: [generalist|domain_focused|function_specialized|practice_expert]

**Assessment Details:**
- **Security Role Structure**: [DESCRIPTION_OF_CURRENT_SECURITY_ROLES]
- **Specialization Areas**: [LIST_OF_SPECIALIZED_SECURITY_AREAS]
- **Skill Distribution**: [HOW_SECURITY_SKILLS_ARE_DISTRIBUTED]
- **External Security Support**: [CONTRACTORS_CONSULTANTS_SERVICES]

**Level Justification:**
- **generalist**: One person/role handles all security concerns
- **domain_focused**: Security roles differentiated by domain (network, app, compliance)
- **function_specialized**: Specialized roles (SOC analyst, security architect, compliance manager)
- **practice_expert**: Deep specialization (threat hunter, forensics analyst, security researcher)

**Current Assessment**: [DETAILED_JUSTIFICATION_FOR_SELECTED_LEVEL]

### Security Decision-Making Authority (Dimension 3)
**Current Level**: [informal|designated|structured|autonomous]

**Assessment Details:**
- **Security Decision Process**: [HOW_SECURITY_DECISIONS_ARE_MADE]
- **Authority Structure**: [WHO_HAS_WHAT_AUTHORITY]
- **Emergency Decision Rights**: [WHO_CAN_MAKE_URGENT_DECISIONS]
- **Budget Approval Process**: [SECURITY_SPENDING_APPROVAL_PROCESS]
- **Policy Change Authority**: [WHO_CAN_MODIFY_SECURITY_POLICIES]

**Level Justification:**
- **informal**: Security decisions made ad-hoc by available personnel
- **designated**: Specific individual designated for security decisions
- **structured**: Security council/committee with defined decision rights
- **autonomous**: Security organization with independent authority and budget

**Current Assessment**: [DETAILED_JUSTIFICATION_FOR_SELECTED_LEVEL]

### Security Operations Maturity (Dimension 4)
**Current Level**: [reactive|planned|integrated|continuous]

**Assessment Details:**
- **Security Activity Planning**: [HOW_SECURITY_WORK_IS_PLANNED]
- **Business Process Integration**: [HOW_SECURITY_INTEGRATES_WITH_BUSINESS]
- **Monitoring Approach**: [REACTIVE_PROACTIVE_CONTINUOUS]
- **Response Capability**: [INCIDENT_RESPONSE_MATURITY]
- **Improvement Process**: [HOW_SECURITY_IS_ENHANCED_OVER_TIME]

**Level Justification:**
- **reactive**: Security handled when issues arise or audits occur
- **planned**: Regular security activities scheduled and tracked
- **integrated**: Security operations integrated into business processes
- **continuous**: Always-on security operations with real-time response

**Current Assessment**: [DETAILED_JUSTIFICATION_FOR_SELECTED_LEVEL]

### Overall Security Responsibility Assessment

**Primary Security Ownership**: [business_led|it_led|engineering_led|infosec_led]
**InfoSec Sub-Level** (if applicable): [4a_generalist|4b_specialized|4c_advanced|4d_strategic]

**Maturity Profile Summary:**
- **Security Ownership**: [LEVEL] - [BRIEF_EXPLANATION]
- **Specialization Depth**: [LEVEL] - [BRIEF_EXPLANATION]  
- **Decision Authority**: [LEVEL] - [BRIEF_EXPLANATION]
- **Operations Maturity**: [LEVEL] - [BRIEF_EXPLANATION]

### Template Selection Guidance

Based on the security responsibility maturity assessment, the following template preferences are recommended:

**Primary Documentation Style**: [business_friendly|technical_operational|engineering_workflow|security_professional]
**Technical Depth Level**: [basic|intermediate|advanced|expert]
**Implementation Approach**: [outsourced|guided|integrated|autonomous]
**Primary Focus Areas**: [LIST_OF_PRIMARY_CONCERNS_BASED_ON_MATURITY]

**Organizational Context Placeholders:**
- **{{PRIMARY_SECURITY_ROLE}}**: [IDENTIFIED_PRIMARY_SECURITY_RESPONSIBILITY_ROLE]
- **{{DECISION_MAKER}}**: [IDENTIFIED_SECURITY_DECISION_AUTHORITY]
- **{{TECHNICAL_TEAM}}**: [IDENTIFIED_TECHNICAL_IMPLEMENTATION_TEAM]
- **{{VENDOR_RELATIONSHIP}}**: [IDENTIFIED_EXTERNAL_SECURITY_SERVICE_APPROACH]

## IT Organization Structure

### IT Governance
- **IT Leadership Structure**: [CIO/CTO/IT_DIRECTOR_REPORTING]
- **IT Governance Model**: [CENTRALIZED/DECENTRALIZED/FEDERATED]
- **IT Budget**: [ANNUAL_IT_BUDGET_RANGE]
- **IT Staff Size**: [NUMBER_OF_IT_EMPLOYEES]

### Organizational Structure
- **IT Departments**:
  - [DEPARTMENT_NAME] - [RESPONSIBILITIES]
  - [DEPARTMENT_NAME] - [RESPONSIBILITIES]
  - [DEPARTMENT_NAME] - [RESPONSIBILITIES]
- **Reporting Relationships**: [KEY_REPORTING_STRUCTURE]
- **Decision-Making Authority**: [WHO_MAKES_WHAT_DECISIONS]

### Key IT Roles and Responsibilities
- **Information Security Officer**: [NAME_OR_ROLE_DESCRIPTION]
- **System Administrators**: [TEAM_SIZE_AND_RESPONSIBILITIES]
- **Network Administrators**: [TEAM_SIZE_AND_RESPONSIBILITIES]
- **Application Owners**: [STRUCTURE_AND_RESPONSIBILITIES]
- **Data Stewards**: [ROLES_AND_RESPONSIBILITIES]

## Stakeholder Mapping

### Executive Leadership
- **Chief Executive Officer**: [NAME] - [SECURITY_INVOLVEMENT_LEVEL]
- **Chief Information Officer**: [NAME] - [SECURITY_RESPONSIBILITIES]
- **Chief Technology Officer**: [NAME] - [SECURITY_RESPONSIBILITIES]
- **Chief Security Officer**: [NAME_OR_NA] - [SECURITY_RESPONSIBILITIES]

### IT Leadership
- **IT Director/Manager**: [NAME] - [RESPONSIBILITIES]
- **Security Manager**: [NAME] - [RESPONSIBILITIES]
- **Infrastructure Manager**: [NAME] - [RESPONSIBILITIES]
- **Application Manager**: [NAME] - [RESPONSIBILITIES]

### Business Stakeholders
- **Business Unit Leaders**: [KEY_BUSINESS_CONTACTS]
- **Compliance Officer**: [NAME_OR_ROLE]
- **Risk Manager**: [NAME_OR_ROLE]
- **Legal Counsel**: [INTERNAL_OR_EXTERNAL]

## Regulatory and Compliance Context

### Regulatory Requirements
- **Primary Regulations**: [LIST_OF_APPLICABLE_REGULATIONS]
  - [REGULATION_NAME] - [COMPLIANCE_STATUS]
  - [REGULATION_NAME] - [COMPLIANCE_STATUS]
- **Industry Standards**: [APPLICABLE_INDUSTRY_STANDARDS]
- **Contractual Requirements**: [KEY_CONTRACTUAL_SECURITY_OBLIGATIONS]

### Compliance History
- **Recent Audits**: [AUDIT_HISTORY_AND_FINDINGS]
- **Compliance Gaps**: [KNOWN_GAPS_OR_DEFICIENCIES]
- **Remediation Status**: [CURRENT_REMEDIATION_EFFORTS]

## Current Security Posture

### Security Maturity Level
- **Overall Maturity**: [BASIC/DEVELOPING/DEFINED/MANAGED/OPTIMIZING]
- **Assessment Method**: [HOW_MATURITY_WAS_DETERMINED]
- **Key Strengths**: [STRONG_SECURITY_AREAS]
- **Key Weaknesses**: [AREAS_NEEDING_IMPROVEMENT]

### Existing Security Framework
- **Current Framework**: [NIST_CSF/ISO27001/COBIT/OTHER/NONE]
- **Implementation Status**: [PERCENTAGE_OR_DESCRIPTION]
- **Framework Gaps**: [MISSING_ELEMENTS_OR_INCOMPLETE_AREAS]

### Security Policies and Procedures
- **Policy Framework Status**: [COMPREHENSIVE/PARTIAL/MINIMAL/NONE]
- **Last Policy Review**: [DATE_OF_LAST_COMPREHENSIVE_REVIEW]
- **Policy Approval Process**: [HOW_POLICIES_ARE_APPROVED]
- **Training and Awareness**: [CURRENT_SECURITY_TRAINING_PROGRAM]

## Risk Profile

### Risk Tolerance
- **Organizational Risk Appetite**: [HIGH/MEDIUM/LOW/VERY_LOW]
- **Risk Decision Making**: [WHO_MAKES_RISK_DECISIONS]
- **Risk Acceptance Criteria**: [WHAT_RISKS_ARE_ACCEPTABLE]

### Current Risk Environment
- **Top Security Risks**: 
  - [RISK_1] - [IMPACT_AND_LIKELIHOOD]
  - [RISK_2] - [IMPACT_AND_LIKELIHOOD]
  - [RISK_3] - [IMPACT_AND_LIKELIHOOD]
- **Recent Security Incidents**: [BRIEF_INCIDENT_HISTORY]
- **Threat Environment**: [SPECIFIC_THREATS_TO_ORGANIZATION]

## Resource Constraints

### Budget Constraints
- **Security Budget**: [ANNUAL_SECURITY_BUDGET_RANGE]
- **Budget Cycle**: [ANNUAL/QUARTERLY/OTHER]
- **Capital vs Operational**: [CAPEX_OPEX_SPLIT]
- **Budget Approval Process**: [HOW_SECURITY_SPENDING_IS_APPROVED]

### Staffing Constraints
- **Security Staff**: [NUMBER_OF_DEDICATED_SECURITY_STAFF]
- **Skills Gaps**: [CRITICAL_SKILL_SHORTAGES]
- **Training Budget**: [TRAINING_AND_DEVELOPMENT_RESOURCES]
- **Contractor Usage**: [EXTENT_OF_CONTRACTOR_RELIANCE]

### Technical Constraints
- **Legacy Systems**: [CRITICAL_LEGACY_SYSTEMS_IMPACT]
- **Technical Debt**: [SIGNIFICANT_TECHNICAL_LIMITATIONS]
- **Integration Challenges**: [SYSTEM_INTEGRATION_CONSTRAINTS]

## Change Management Capabilities

### Organizational Change Readiness
- **Change Management Maturity**: [CHANGE_MANAGEMENT_CAPABILITY_LEVEL]
- **Previous Security Initiatives**: [SUCCESS_OF_PAST_SECURITY_CHANGES]
- **Cultural Factors**: [ORGANIZATIONAL_CULTURE_IMPACT_ON_SECURITY]

### Communication and Training
- **Communication Channels**: [HOW_SECURITY_INFO_IS_COMMUNICATED]
- **Training Infrastructure**: [CAPABILITY_TO_DELIVER_SECURITY_TRAINING]
- **Change Champion Network**: [EXISTENCE_OF_SECURITY_ADVOCATES]

## Implementation Considerations

### Control Implementation Factors
- **Preferred Implementation Approach**: [PHASED/BIG_BANG/PILOT_BASED]
- **Resource Allocation**: [HOW_RESOURCES_ARE_TYPICALLY_ALLOCATED]
- **Success Metrics**: [HOW_SUCCESS_IS_MEASURED]
- **Timeline Preferences**: [TYPICAL_PROJECT_TIMELINES]

### Integration Requirements
- **Business Process Integration**: [HOW_SECURITY_INTEGRATES_WITH_BUSINESS]
- **Technology Integration**: [TECHNICAL_INTEGRATION_REQUIREMENTS]
- **Vendor Coordination**: [VENDOR_MANAGEMENT_APPROACH]

<!-- BEGIN AI COMMENT -->
<!-- 
    ENHANCED TEMPLATE NOTES: This organizational profile template now includes a comprehensive
    Security Responsibility Maturity Assessment that enables AI agents to select appropriate
    template styles and technical depth levels for control documentation.
    
    The four-dimension assessment provides the foundation for the Organizational Maturity Matrix
    (OMM) approach, ensuring that control documentation matches organizational capabilities and
    security responsibility structures.
    
    AI agents should use the assessment results to:
    1. Select appropriate template variants (business_led, it_led, engineering_led, infosec_led)
    2. Adjust technical depth and language style
    3. Choose appropriate implementation approaches
    4. Focus on relevant concerns for the maturity level
    
    Update this profile regularly (at least annually) or when significant 
    organizational changes occur, particularly changes in security responsibility structure.
-->
<!-- END AI COMMENT -->