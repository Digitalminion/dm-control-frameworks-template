<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-ra-06, risk-assessment, risk-response, response-planning, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.RA-06 Risk Response Planning Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.RA-06 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.RA-06 (Risk responses are identified, prioritized, planned, tracked, 
    and communicated) with adaptive content that adjusts based on organizational security 
    responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of risk response planning with appropriate depth based on organizational 
    maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.RA-06 documentation that plans risk 
    responses appropriate to the organization's security responsibility maturity level and 
    risk management complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.RA-06 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.RA-06
    2. IDENTIFICATION FOCUS: Emphasize risk response identification, planning, tracking, and communication
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear risk response identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE RESPONSE COMPLEXITY: Use maturity-specific risk response analysis depth
    9. INCLUDE RELEVANT RESPONSE SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE PLANNING: Match response planning to organizational capability
    11. ADJUST RESPONSE GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT RESPONSES: Emphasize response types important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.RA-06:
    
    IF security_ownership == "business_led":
    - Use business language focused on business response and operational response planning
    - Emphasize response planning based on business value and regulatory response considerations
    - Include executive and operational response governance and business response prioritization
    - Focus on compliance-driven response planning and business impact response considerations
    - Provide simple response planning frameworks appropriate to business operations management
    - Include business value response and operational response planning considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology response and infrastructure response planning
    - Emphasize response planning based on IT service delivery and technology operational response
    - Include IT governance and technology response planning and infrastructure response prioritization
    - Focus on operational response planning and IT service response considerations
    - Provide IT-centric response planning frameworks and technology response analysis
    - Include technology service response and infrastructure response planning considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical response and development response planning
    - Emphasize response planning based on engineering operations and platform response considerations
    - Include engineering governance and technical response planning and development response prioritization
    - Focus on technical response planning and engineering platform response considerations
    - Provide engineering-centric response planning frameworks and technical response analysis
    - Include development platform response and engineering response planning considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive response and security-informed response planning
    - Emphasize response planning based on security threat landscape and advanced response considerations
    - Include security governance and strategic response planning and security response prioritization
    - Focus on threat-informed response planning and comprehensive security response considerations
    - Provide security-centric response planning frameworks and advanced response analysis
    - Include strategic security response and comprehensive response planning considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for business response capabilities and organizational response tolerance
    - Read context/stakeholders/ files for stakeholder response expectations and response requirements
    - Use organizational maturity context to tailor response planning complexity and response strategies
    - Consider response complexity and planning capability appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Risk response approaches must be clearly articulated for the maturity level
    - Response planning strategies must be practical and effective
    - Response analysis must align with organizational capability
    - Identification outcomes must support effective risk management and response execution
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.RA-06

### Subcategory Information
- **ID**: ID.RA-06
- **Function**: IDENTIFY (ID)
- **Category**: Risk Assessment (RA)
- **Title**: Risk Response Planning
- **Outcome**: Risk responses are identified, prioritized, planned, tracked, and communicated

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization systematically identifies, prioritizes, plans, tracks, and communicates risk responses based on comprehensive risk assessment results, enabling coordinated risk mitigation strategies and effective risk management execution aligned with organizational objectives and risk tolerance.

**Strategic Value**: This subcategory establishes foundational risk response capability by creating systematic response planning and execution processes, enabling more effective risk mitigation, coordinated security activities, and organizational resilience through well-planned and tracked risk response strategies.

### Organizational Implementation

#### Current Risk Response Planning Assessment
{{#if_business_led}}
**Business-Led Risk Response Assessment**:
- Current business risk response and operational response analysis
- Customer-facing risk response and business-critical response mapping
- Business application risk response and operational response identification
- Executive and operational response governance and business response requirements
- Regulatory compliance and business risk response documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Risk Response Assessment**:
- Technology infrastructure and IT risk response analysis
- Cloud service provider and technology platform response mapping
- IT service delivery and infrastructure response identification
- Technology integration and platform response assessment and documentation
- IT infrastructure and service operation response requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Risk Response Assessment**:
- Software development and technical platform response analysis
- Development tool and infrastructure response mapping
- Platform and infrastructure technical response identification
- Technical ecosystem and engineering response integration assessment
- Engineering platform and development operation response documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Risk Response Assessment**:
- Security infrastructure and comprehensive response analysis
- Advanced security risk response and strategic response mapping and assessment
- Security operations and incident response planning identification
- Comprehensive security and threat management response assessment
- Strategic security operation and threat landscape response documentation
{{/if_infosec_led}}

#### Framework-Specific Risk Response Elements

**Risk Response Planning Framework**:
1. **Response Identification**: Systematic process for identifying potential risk response options
2. **Response Prioritization**: Structured approach to prioritizing responses based on risk levels
3. **Response Planning**: Detailed planning for response implementation and execution
4. **Response Tracking**: Mechanisms for monitoring response progress and effectiveness
5. **Response Communication**: Structured communication of response plans and status

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Risk Response**:
- Document fundamental business responses and primary response prioritization
- Create simple response mapping and basic business response identification
- Identify key business response types and core response planning processes
- Establish basic response communication and business response documentation
- Define minimum response analysis collection and business response tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Risk Response**:
- Document technology responses and primary IT response prioritization
- Create simple IT response mapping and technology response identification
- Identify critical technology response types and core IT response processes
- Establish basic IT response communication and technology response documentation
- Define minimum IT response analysis collection and technology response tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Risk Response
**Risk-Based Risk Response Enhancement**:
- Develop comprehensive response analysis with assessment and planning integration
- Create structured response analysis across multiple response and organizational dimensions
- Implement systematic response monitoring and planning validation processes
- Establish risk-informed response communication and response management
- Develop coordinated response documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Risk Response Management
**Systematic Risk Response Operations**:
- Implement automated response assessment and planning analysis systems
- Establish continuous response monitoring and planning evolution tracking
- Develop advanced response analytics and planning optimization analysis
- Create standardized response communication and response management processes
- Implement comprehensive response performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Risk Response Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Risk Response Management**:
- Deploy predictive response analytics with threat intelligence and planning integration
- Implement real-time response monitoring with adaptive planning strategies
- Establish dynamic response assessment with strategic planning optimization
- Develop advanced threat-informed response communication and collaboration
- Create strategic response positioning with industry planning and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Risk Response Technology Infrastructure
**Risk Response Management Technology Context**:
- Current risk management and response tracking platforms
- Response planning and execution tools
- Governance, risk, and compliance (GRC) systems
- Response monitoring and dashboard platforms
- Integration capabilities with enterprise risk management and security tools

{{#if_engineering_led_plus}}
**Engineering-Led Risk Response Technology**:
- **Response Automation**: Automated platform and development response analysis and mapping
- **Response Tracking**: Technical response tracking and planning integration analysis systems
- **Response Visualization**: Technical response design and development planning visualization
- **Communication Platforms**: Engineering team response and planning communication and collaboration
- **Analytics Systems**: Technical response analysis and planning optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Risk Response-Based Management Framework
**Risk Assessment by Risk Response Category**:
1. **Accept**: Risk acceptance strategies aligned with organizational risk tolerance
2. **Avoid**: Risk avoidance strategies through process or technology changes
3. **Mitigate**: Risk mitigation strategies through controls and safeguards implementation
4. **Transfer**: Risk transfer strategies through insurance, contracts, or outsourcing
5. **Monitor**: Continuous risk monitoring strategies for ongoing risk awareness

{{#if_business_led}}
**Executive Risk Response Strategy**:
- Board-level response oversight and strategic response governance
- Executive decision-making for response evolution and strategic response development
- Strategic planning integration with response optimization and response positioning
- Investment decision-making with response-based assessment
- Crisis management coordination with response-specific business continuity planning
{{/if_business_led}}

### Assessment and Measurement

#### Risk Response Effectiveness Metrics
**Quantitative Measures**:
- Response planning coverage and implementation completeness assessment
- Response effectiveness accuracy and execution effectiveness measurement
- Response-related incident mitigation and resolution tracking
- Planning processing time and response execution effectiveness measurement
- Response optimization and planning positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with response clarity and planning communication effectiveness
- Internal team alignment on response planning and response management strategy
- Response planning adaptability to changing risk environment and response conditions
- Strategic response development and planning positioning advancement
- Leadership effectiveness in response communication and planning coordination

{{#if_infosec_led}}
**InfoSec-Led Risk Response Assessment**:
- Advanced security response effectiveness in threat mitigation and response protection
- Threat-informed response positioning accuracy and strategic security response relevance
- Security response collaboration effectiveness and planning analysis integration
- Advanced response modeling integration with threat landscape analysis
- Strategic security leadership development through response planning positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-30**: Guide for Conducting Risk Assessments
- **ISO 27005**: Information Security Risk Management
- **NIST SP 800-39**: Managing Information Security Risk
- **COBIT**: Business and IT governance framework for risk management
- **COSO ERM**: Enterprise Risk Management framework

#### Implementation Resources
{{#if_business_led}}
**Business-Led Risk Response Resources**:
- Business risk response and assessment frameworks
- Executive response oversight and business strategic planning
- Compliance response documentation and business protection procedures
- Business response planning and operational planning methodologies
- Strategic response and business development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Risk Response Resources**:
- Technical risk response and development frameworks
- Software development response design and platform procedures
- Engineering governance integration with response planning
- Platform optimization and integration response methodologies
- DevOps and automation response development and management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Risk Response Maturity Progression
**Risk Response Enhancement Pathway**:
1. **Foundation**: Basic response identification and simple planning documentation
2. **Development**: Systematic response analysis with structured planning management
3. **Integration**: Comprehensive response optimization with strategic planning integration
4. **Optimization**: Advanced predictive response management with planning intelligence
5. **Innovation**: Adaptive planning leadership with strategic response positioning and security

#### Risk Response Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Risk Response Enhancement**:
- Technology response advancement and automation
- Service delivery planning integration with strategic IT response planning
- IT governance enhancement with response planning management integration
- Technology innovation integration with strategic response positioning
- Automated response analysis and planning optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.RA-05**: Risk determination and prioritization provides input for response planning
- **ID.RA-04**: Business impact analysis informs response prioritization
- **GV.RM-01**: Risk management strategy provides framework for response planning
- **GV.RM-02**: Risk tolerance provides context for response decisions

#### Supporting Subcategories
**Related Risk Management Subcategories**:
- **PR.IP-01**: Configuration management supports response implementation
- **RS.RP-01**: Response planning coordinates with incident response planning
- **RC.RP-01**: Recovery planning aligns with risk response strategies
- **GV.RM-03**: Risk management roles support response planning processes
- **GV.RM-04**: Risk management processes coordinate with response planning

### Implementation Timeline

#### Phase 1: Risk Response Foundation (Months 1-2)
**Immediate Implementation**:
- Basic response planning framework and response mapping
- Initial response assessment and planning communication framework establishment
- Simple response analysis and planning documentation
- Basic response communication and internal planning alignment processes
- Initial response-related assessment and response documentation

#### Phase 2: Risk Response Development (Months 3-6)
**Risk Response Enhancement**:
- Comprehensive response analysis framework development and implementation
- Advanced planning assessment and response validation system deployment
- Cross-functional response coordination and strategic planning integration
- Performance measurement and response optimization system establishment
- Strategic response planning and planning positioning development

#### Phase 3: Risk Response Optimization (Months 7-12)
**Risk Response Maturation**:
- Advanced response analytics and strategic planning positioning implementation
- Continuous improvement process establishment and optimization
- Strategic planning leadership development and response collaboration
- Future capability planning and adaptive response management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.RA-06 subcategory requirements fully addressed
- [ ] Maturity-specific response approaches included for all security ownership levels
- [ ] Risk response analysis practical and comprehensive
- [ ] Response planning strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Risk response identification processes established and documented
- [ ] Response prioritization methods implemented and operational
- [ ] Response planning procedures defined and validated
- [ ] Response tracking systems established and operational
- [ ] Response communication protocols deployed
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed