<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-ra-05, risk-assessment, risk-determination, risk-prioritization, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.RA-05 Risk Determination and Prioritization Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.RA-05 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.RA-05 (Risks are identified, prioritized, and characterized) with 
    adaptive content that adjusts based on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of risk determination and prioritization with appropriate depth based on 
    organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.RA-05 documentation that determines 
    and prioritizes risks appropriate to the organization's security responsibility maturity 
    level and risk complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.RA-05 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.RA-05
    2. IDENTIFICATION FOCUS: Emphasize risk identification, prioritization, and characterization
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear risk determination identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE RISK COMPLEXITY: Use maturity-specific risk determination analysis depth
    9. INCLUDE RELEVANT RISK SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE PRIORITIZATION: Match risk prioritization to organizational capability
    11. ADJUST RISK GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT RISKS: Emphasize risk types important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.RA-05:
    
    IF security_ownership == "business_led":
    - Use business language focused on business risk and operational risk determination
    - Emphasize risk determination based on business value and regulatory risk considerations
    - Include executive and operational risk governance and business risk prioritization
    - Focus on compliance-driven risk determination and business impact risk considerations
    - Provide simple risk determination frameworks appropriate to business operations management
    - Include business value risk and operational risk determination considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology risk and infrastructure risk determination
    - Emphasize risk determination based on IT service delivery and technology operational risk
    - Include IT governance and technology risk determination and infrastructure risk prioritization
    - Focus on operational risk determination and IT service risk considerations
    - Provide IT-centric risk determination frameworks and technology risk analysis
    - Include technology service risk and infrastructure risk determination considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical risk and development risk determination
    - Emphasize risk determination based on engineering operations and platform risk considerations
    - Include engineering governance and technical risk determination and development risk prioritization
    - Focus on technical risk determination and engineering platform risk considerations
    - Provide engineering-centric risk determination frameworks and technical risk analysis
    - Include development platform risk and engineering risk determination considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive risk and security-informed risk determination
    - Emphasize risk determination based on security threat landscape and advanced risk considerations
    - Include security governance and strategic risk determination and security risk prioritization
    - Focus on threat-informed risk determination and comprehensive security risk considerations
    - Provide security-centric risk determination frameworks and advanced risk analysis
    - Include strategic security risk and comprehensive risk determination considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for business risks and organizational risk tolerance
    - Read context/stakeholders/ files for stakeholder risk expectations and risk requirements
    - Use organizational maturity context to tailor risk determination complexity and prioritization
    - Consider risk complexity and determination capability appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Risk determination approaches must be clearly articulated for the maturity level
    - Risk prioritization strategies must be practical and effective
    - Risk analysis must align with organizational capability
    - Identification outcomes must support effective risk management and decision-making
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.RA-05

### Subcategory Information
- **ID**: ID.RA-05
- **Function**: IDENTIFY (ID)
- **Category**: Risk Assessment (RA)
- **Title**: Risk Determination and Prioritization
- **Outcome**: Risks are identified, prioritized, and characterized

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization systematically identifies, prioritizes, and characterizes cybersecurity risks based on comprehensive analysis of threats, vulnerabilities, business impact, and organizational risk tolerance, enabling informed risk management decisions and resource allocation strategies.

**Strategic Value**: This subcategory establishes foundational risk understanding by creating systematic risk determination and prioritization processes, enabling more effective risk management, strategic security investments, and organizational decision-making based on comprehensive risk characterization and business-aligned prioritization.

### Organizational Implementation

#### Current Risk Determination Assessment
{{#if_business_led}}
**Business-Led Risk Determination Assessment**:
- Current business risk assessment and operational risk analysis
- Customer-facing risk determination and business-critical risk mapping
- Business application risk assessment and operational risk identification
- Executive and operational risk governance and business risk requirements
- Regulatory compliance and business risk determination documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Risk Determination Assessment**:
- Technology infrastructure and IT risk analysis
- Cloud service provider and technology platform risk mapping
- IT service delivery and infrastructure risk identification
- Technology integration and platform risk assessment and documentation
- IT infrastructure and service operation risk requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Risk Determination Assessment**:
- Software development and technical platform risk analysis
- Development tool and infrastructure risk mapping
- Platform and infrastructure technical risk identification
- Technical ecosystem and engineering risk integration assessment
- Engineering platform and development operation risk documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Risk Determination Assessment**:
- Security infrastructure and comprehensive risk analysis
- Advanced security risk determination and strategic risk mapping and assessment
- Security operations and incident response risk identification
- Comprehensive security and threat management risk assessment
- Strategic security operation and threat landscape risk documentation
{{/if_infosec_led}}

#### Framework-Specific Risk Determination Elements

**Risk Determination and Prioritization Framework**:
1. **Risk Identification**: Systematic process for discovering and documenting risks
2. **Risk Characterization**: Detailed analysis of risk attributes, likelihood, and impact
3. **Risk Prioritization**: Structured approach to ranking risks based on criticality
4. **Risk Tolerance**: Alignment of risk assessment with organizational risk appetite
5. **Risk Documentation**: Comprehensive documentation and communication of risk analysis

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Risk Determination**:
- Document fundamental business risks and primary risk prioritization
- Create simple risk mapping and basic business risk identification
- Identify key business risk types and core risk determination processes
- Establish basic risk communication and business risk documentation
- Define minimum risk analysis collection and business risk tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Risk Determination**:
- Document technology risks and primary IT risk prioritization
- Create simple IT risk mapping and technology risk identification
- Identify critical technology risk types and core IT risk processes
- Establish basic IT risk communication and technology risk documentation
- Define minimum IT risk analysis collection and technology risk tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Risk Determination
**Risk-Based Risk Determination Enhancement**:
- Develop comprehensive risk analysis with assessment and prioritization integration
- Create structured risk analysis across multiple risk and organizational dimensions
- Implement systematic risk monitoring and prioritization validation processes
- Establish risk-informed communication and risk management
- Develop coordinated risk documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Risk Determination Management
**Systematic Risk Determination Operations**:
- Implement automated risk assessment and prioritization analysis systems
- Establish continuous risk monitoring and determination evolution tracking
- Develop advanced risk analytics and prioritization optimization analysis
- Create standardized risk communication and risk management processes
- Implement comprehensive risk performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Risk Determination Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Risk Determination Management**:
- Deploy predictive risk analytics with threat intelligence and prioritization integration
- Implement real-time risk monitoring with adaptive prioritization strategies
- Establish dynamic risk assessment with strategic prioritization optimization
- Develop advanced threat-informed risk communication and collaboration
- Create strategic risk positioning with industry determination and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Risk Determination Technology Infrastructure
**Risk Determination Management Technology Context**:
- Current risk assessment and management platforms
- Risk analysis and quantitative assessment tools
- Governance, risk, and compliance (GRC) systems
- Risk monitoring and dashboard platforms
- Integration capabilities with enterprise risk management and security tools

{{#if_engineering_led_plus}}
**Engineering-Led Risk Determination Technology**:
- **Risk Modeling**: Automated platform and development risk analysis and mapping
- **Risk Assessment**: Technical risk tracking and prioritization integration analysis systems
- **Risk Visualization**: Technical risk design and development prioritization visualization
- **Communication Platforms**: Engineering team risk and prioritization communication and collaboration
- **Analytics Systems**: Technical risk analysis and prioritization optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Risk Determination-Based Management Framework
**Risk Assessment by Risk Determination Category**:
1. **Strategic Risk**: High-level organizational risks impact on business strategy and objectives
2. **Operational Risk**: Day-to-day operational risks impact on business continuity
3. **Compliance Risk**: Regulatory and legal risks impact on organizational compliance
4. **Financial Risk**: Financial impact risks on organizational resources and revenue
5. **Reputation Risk**: Brand and stakeholder confidence risks impact on organizational reputation

{{#if_business_led}}
**Executive Risk Determination Strategy**:
- Board-level risk oversight and strategic risk governance
- Executive decision-making for risk evolution and strategic risk development
- Strategic planning integration with risk optimization and risk positioning
- Investment decision-making with risk-based assessment
- Crisis management coordination with risk-specific business continuity planning
{{/if_business_led}}

### Assessment and Measurement

#### Risk Determination Effectiveness Metrics
**Quantitative Measures**:
- Risk determination coverage and prioritization completeness assessment
- Risk analysis accuracy and prioritization effectiveness measurement
- Risk determination-related incident response and mitigation tracking
- Analysis processing time and risk decision effectiveness measurement
- Risk optimization and prioritization positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with risk clarity and prioritization communication effectiveness
- Internal team alignment on risk determination and risk management strategy
- Risk determination adaptability to changing business environment and risk conditions
- Strategic risk development and prioritization positioning advancement
- Leadership effectiveness in risk communication and prioritization coordination

{{#if_infosec_led}}
**InfoSec-Led Risk Determination Assessment**:
- Advanced security risk effectiveness in threat mitigation and risk protection
- Threat-informed risk positioning accuracy and strategic security risk relevance
- Security risk collaboration effectiveness and prioritization analysis integration
- Advanced risk modeling integration with threat landscape analysis
- Strategic security leadership development through risk determination positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-30**: Guide for Conducting Risk Assessments
- **ISO 27005**: Information Security Risk Management
- **NIST SP 800-39**: Managing Information Security Risk
- **FAIR (Factor Analysis of Information Risk)**: Quantitative risk analysis framework
- **COBIT**: Business and IT governance framework for risk management

#### Implementation Resources
{{#if_business_led}}
**Business-Led Risk Determination Resources**:
- Business risk determination and assessment frameworks
- Executive risk oversight and business strategic planning
- Compliance risk documentation and business protection procedures
- Business risk planning and operational determination methodologies
- Strategic risk and business development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Risk Determination Resources**:
- Technical risk determination and development frameworks
- Software development risk design and platform procedures
- Engineering governance integration with risk planning
- Platform optimization and integration risk methodologies
- DevOps and automation risk development and management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Risk Determination Maturity Progression
**Risk Determination Enhancement Pathway**:
1. **Foundation**: Basic risk identification and simple prioritization documentation
2. **Development**: Systematic risk analysis with structured prioritization management
3. **Integration**: Comprehensive risk optimization with strategic prioritization integration
4. **Optimization**: Advanced predictive risk management with prioritization intelligence
5. **Innovation**: Adaptive prioritization leadership with strategic risk positioning and security

#### Risk Determination Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Risk Determination Enhancement**:
- Technology risk advancement and automation
- Service delivery prioritization integration with strategic IT risk planning
- IT governance enhancement with risk prioritization management integration
- Technology innovation integration with strategic risk positioning
- Automated risk analysis and prioritization optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.RA-01**: Vulnerability identification provides input for risk determination
- **ID.RA-02**: Threat intelligence supports risk characterization
- **ID.RA-03**: Threat identification contributes to risk analysis
- **ID.RA-04**: Business impact analysis informs risk prioritization

#### Supporting Subcategories
**Related Risk Assessment Subcategories**:
- **ID.RA-06**: Risk response planning uses risk prioritization results
- **GV.RM-01**: Risk management strategy provides framework for risk determination
- **GV.RM-02**: Risk tolerance provides context for risk prioritization
- **GV.RM-03**: Risk management roles support risk determination processes
- **GV.RM-04**: Risk management processes coordinate with risk determination

### Implementation Timeline

#### Phase 1: Risk Determination Foundation (Months 1-2)
**Immediate Implementation**:
- Basic risk determination framework and prioritization mapping
- Initial risk assessment and determination communication framework establishment
- Simple risk analysis and prioritization documentation
- Basic risk communication and internal prioritization alignment processes
- Initial risk determination-related assessment and risk documentation

#### Phase 2: Risk Determination Development (Months 3-6)
**Risk Determination Enhancement**:
- Comprehensive risk analysis framework development and implementation
- Advanced prioritization assessment and risk validation system deployment
- Cross-functional risk coordination and strategic prioritization planning integration
- Performance measurement and risk optimization system establishment
- Strategic risk planning and prioritization positioning development

#### Phase 3: Risk Determination Optimization (Months 7-12)
**Risk Determination Maturation**:
- Advanced risk analytics and strategic prioritization positioning implementation
- Continuous improvement process establishment and optimization
- Strategic prioritization leadership development and risk collaboration
- Future capability planning and adaptive risk management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.RA-05 subcategory requirements fully addressed
- [ ] Maturity-specific risk approaches included for all security ownership levels
- [ ] Risk determination analysis practical and comprehensive
- [ ] Risk prioritization strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Risk identification processes established and documented
- [ ] Risk characterization methods implemented and operational
- [ ] Risk prioritization criteria defined and validated
- [ ] Risk tolerance levels established and communicated
- [ ] Risk documentation systems deployed
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed