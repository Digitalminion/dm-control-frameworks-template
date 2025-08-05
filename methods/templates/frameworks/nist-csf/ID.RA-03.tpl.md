<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-ra-03, risk-assessment, threat-identification, internal-external-threats, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.RA-03 Internal and External Threat Identification Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.RA-03 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.RA-03 (Internal and external threats to the organization are identified 
    and recorded) with adaptive content that adjusts based on organizational security responsibility 
    maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of threat identification and documentation with appropriate depth based on 
    organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.RA-03 documentation that identifies 
    and records threats appropriate to the organization's security responsibility maturity 
    level and threat environment complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.RA-03 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.RA-03
    2. IDENTIFICATION FOCUS: Emphasize internal and external threat identification and recording
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear threat identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE THREAT COMPLEXITY: Use maturity-specific threat identification analysis depth
    9. INCLUDE RELEVANT THREAT SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE IDENTIFICATION: Match threat identification approach to organizational capability
    11. ADJUST THREAT GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT THREATS: Emphasize threat types important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.RA-03:
    
    IF security_ownership == "business_led":
    - Use business language focused on business-relevant threats and operational security concerns
    - Emphasize threat identification based on business operations and industry-specific threat landscape
    - Include executive and operational threat identification and business security threat awareness
    - Focus on compliance-driven threat identification and business impact threat considerations
    - Provide simple threat identification frameworks appropriate to business operations management
    - Include business security threats and operational threat identification considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology threats and infrastructure security concerns
    - Emphasize threat identification based on IT infrastructure and technology-specific threat landscape
    - Include IT governance and technology threat identification and infrastructure security threat awareness
    - Focus on operational threat identification and IT security threat considerations
    - Provide IT-centric threat identification frameworks and technology threat analysis
    - Include technology security threats and infrastructure threat identification considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical threats and development security concerns
    - Emphasize threat identification based on engineering operations and platform-specific threat landscape
    - Include engineering governance and technical threat identification and development security threat awareness
    - Focus on technical threat identification and engineering platform threat considerations
    - Provide engineering-centric threat identification frameworks and technical threat analysis
    - Include development security threats and platform threat identification considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive threats and advanced threat landscape analysis
    - Emphasize threat identification based on security operations and comprehensive threat landscape
    - Include security governance and strategic threat identification and advanced threat analysis
    - Focus on threat-informed identification processes and comprehensive threat considerations
    - Provide security-centric threat identification frameworks and advanced threat analysis
    - Include strategic security threats and comprehensive threat identification considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for organizational threats and business risk environment
    - Read context/stakeholders/ files for external threat sources and adversary information
    - Use organizational maturity context to tailor threat identification complexity and scope
    - Consider threat landscape complexity and identification capability appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Threat identification approaches must be clearly articulated for the maturity level
    - Identification strategies must be practical and effective
    - Threat analysis must align with organizational capability
    - Identification outcomes must support effective threat awareness and risk management
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.RA-03

### Subcategory Information
- **ID**: ID.RA-03
- **Function**: IDENTIFY (ID)
- **Category**: Risk Assessment (RA)
- **Title**: Internal and External Threat Identification
- **Outcome**: Internal and external threats to the organization are identified and recorded

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization systematically identifies and documents both internal and external threats that could impact organizational assets, operations, and objectives, enabling informed risk assessment and targeted threat mitigation strategies.

**Strategic Value**: This subcategory establishes foundational threat awareness by creating comprehensive threat identification and documentation processes, enabling more effective risk assessment, security planning, and threat-specific defense strategies based on current and emerging threat landscape analysis.

### Organizational Implementation

#### Current Threat Identification Assessment
{{#if_business_led}}
**Business-Led Threat Identification Assessment**:
- Current business threat landscape and operational security threat analysis
- Industry-specific threat identification and business sector threat environment mapping
- Business risk threat landscape and operational threat identification
- Executive and operational threat identification governance and business security threat requirements
- Regulatory compliance and business threat identification documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Threat Identification Assessment**:
- Technology infrastructure and IT threat landscape analysis
- Cloud service provider and technology platform threat identification mapping
- IT service delivery and infrastructure threat identification
- Technology integration and platform threat landscape assessment and documentation
- IT infrastructure and service operation threat identification requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Threat Identification Assessment**:
- Software development and technical platform threat landscape analysis
- Development tool and infrastructure threat identification mapping
- Platform and infrastructure technical threat identification
- Technical ecosystem and engineering threat landscape integration assessment
- Engineering platform and development operation threat identification documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Threat Identification Assessment**:
- Security infrastructure and comprehensive threat landscape analysis
- Advanced security threat identification and strategic threat environment mapping and assessment
- Security operations and incident response threat identification
- Comprehensive security and threat management landscape assessment
- Strategic security operation and threat environment identification documentation
{{/if_infosec_led}}

#### Framework-Specific Threat Identification Elements

**Internal and External Threat Identification Framework**:
1. **Threat Taxonomy**: Comprehensive categorization of internal and external threat types
2. **Identification Processes**: Systematic processes for discovering and documenting threats
3. **Threat Sources**: Analysis of threat actors, motivations, and capabilities
4. **Documentation Standards**: Structured approaches for recording and maintaining threat information
5. **Threat Validation**: Processes for verifying and updating threat identification information

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Threat Identification**:
- Document fundamental business threats and primary industry threat landscape
- Create simple threat identification mapping and basic threat documentation
- Identify key business threat types and core threat identification processes
- Establish basic threat identification communication and business threat documentation
- Define minimum threat identification collection and business threat tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Threat Identification**:
- Document technology threats and primary IT security threat landscape
- Create simple IT threat identification mapping and technology threat documentation
- Identify critical technology threat types and core IT threat identification processes
- Establish basic IT threat identification communication and technology threat documentation
- Define minimum IT threat identification collection and technology threat tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Threat Identification
**Risk-Based Threat Identification Enhancement**:
- Develop comprehensive threat identification analysis with risk assessment and threat integration
- Create structured threat analysis across multiple threat categories and sources
- Implement systematic threat identification monitoring and threat validation processes
- Establish risk-informed threat identification communication and threat management
- Develop coordinated threat identification documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Threat Identification Management
**Systematic Threat Identification Operations**:
- Implement automated threat identification collection and threat analysis systems
- Establish continuous threat identification assessment and threat evolution monitoring
- Develop advanced threat identification analytics and threat optimization analysis
- Create standardized threat identification communication and threat management processes
- Implement comprehensive threat identification performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Threat Identification Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Threat Identification Management**:
- Deploy predictive threat identification analytics with advanced threat analysis integration
- Implement real-time threat identification monitoring with adaptive threat response strategies
- Establish dynamic threat identification assessment with strategic threat optimization
- Develop advanced threat-informed identification communication and collaboration
- Create strategic threat positioning with industry threat identification and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Threat Identification Technology Infrastructure
**Internal and External Threat Identification Technology Context**:
- Current threat detection and identification tools
- Threat analysis and threat modeling platforms
- Security information and event management (SIEM) integration
- Threat intelligence and monitoring systems
- Integration capabilities with security tools and threat analysis platforms

{{#if_engineering_led_plus}}
**Engineering-Led Threat Identification Technology**:
- **Threat Detection**: Automated platform and development threat identification analysis and mapping
- **Threat Analysis**: Technical threat identification tracking and threat integration analysis systems
- **Threat Modeling**: Technical threat identification design and development threat visualization
- **Communication Platforms**: Engineering team threat identification and threat communication and collaboration
- **Analytics Systems**: Technical threat identification analysis and threat optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Threat Identification-Based Risk Management Framework
**Risk Assessment by Threat Identification Category**:
1. **Internal Threat Risk**: Insider threats and internal security vulnerabilities impact on operations
2. **External Threat Risk**: External adversaries and attack vectors impact on organizational security
3. **Threat Evolution Risk**: Changing threat landscape impact on threat identification effectiveness
4. **Identification Gap Risk**: Unidentified threats impact on security posture and risk management
5. **Strategic Risk**: Long-term threat identification capability sustainability and evolution implications

{{#if_business_led}}
**Executive Threat Identification Strategy**:
- Board-level threat identification oversight and strategic threat awareness governance
- Executive decision-making for threat identification evolution and strategic threat development
- Strategic planning integration with threat identification optimization and threat positioning
- Investment decision-making with threat identification-based risk assessment
- Crisis management coordination with threat identification-specific incident response planning
{{/if_business_led}}

### Assessment and Measurement

#### Threat Identification Effectiveness Metrics
**Quantitative Measures**:
- Threat identification coverage and threat discovery effectiveness assessment
- Threat identification accuracy and threat validation effectiveness measurement
- Threat identification-related incident prevention and threat mitigation tracking
- Identification processing time and threat response effectiveness measurement
- Threat identification optimization and threat positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with threat identification clarity and threat communication effectiveness
- Internal team alignment on threat identification and threat management strategy
- Threat identification adaptability to changing threat landscape and identification conditions
- Strategic threat identification development and threat positioning advancement
- Leadership effectiveness in threat identification communication and threat coordination

{{#if_infosec_led}}
**InfoSec-Led Threat Identification Assessment**:
- Advanced security threat identification effectiveness in threat mitigation and identification protection
- Threat-informed identification positioning accuracy and strategic security threat relevance
- Security threat identification collaboration effectiveness and threat analysis integration
- Advanced threat identification modeling integration with threat landscape analysis
- Strategic security leadership development through threat identification positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-30**: Guide for Conducting Risk Assessments
- **MITRE ATT&CK**: Framework for understanding adversary tactics, techniques, and procedures
- **NIST SP 800-53**: Security and Privacy Controls (RA family)
- **ISO 27005**: Information Security Risk Management
- **OWASP Top 10**: Web Application Security Risks

#### Implementation Resources
{{#if_business_led}}
**Business-Led Threat Identification Resources**:
- Business threat identification and industry threat landscape frameworks
- Executive threat identification oversight and business threat strategic planning
- Compliance threat identification documentation and business threat protection procedures
- Business threat identification planning and operational threat methodologies
- Strategic threat identification and business threat development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Threat Identification Resources**:
- Technical threat identification and development threat frameworks
- Software development threat identification design and platform threat procedures
- Engineering governance integration with threat identification planning
- Platform threat optimization and integration threat identification methodologies
- DevOps and automation threat identification development and threat management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Threat Identification Maturity Progression
**Threat Identification Enhancement Pathway**:
1. **Foundation**: Basic threat identification and simple threat documentation
2. **Development**: Systematic threat identification analysis with structured threat management
3. **Integration**: Comprehensive threat identification optimization with strategic threat integration
4. **Optimization**: Advanced predictive threat identification management with threat analysis intelligence
5. **Innovation**: Adaptive threat leadership with strategic threat identification positioning and security

#### Threat Identification Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Threat Identification Enhancement**:
- Technology threat identification advancement and automation
- Service delivery threat integration with strategic IT threat identification planning
- IT governance enhancement with threat identification management integration
- Technology innovation integration with strategic threat identification positioning
- Automated threat identification analysis and threat optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.RA-01**: Vulnerability identification provides context for threat identification analysis
- **ID.RA-02**: Threat intelligence collection supports threat identification processes
- **ID.AM-01**: Asset inventory provides targets for threat identification

#### Supporting Subcategories
**Related Risk Assessment Subcategories**:
- **ID.RA-04**: Business impact analysis integrates with threat identification assessment
- **ID.RA-05**: Risk determination uses threat identification as input
- **ID.RA-06**: Risk response planning incorporates threat identification insights
- **DE.AE-01**: Baseline establishment coordinates with threat identification monitoring
- **RS.AN-01**: Incident analysis benefits from threat identification context

### Implementation Timeline

#### Phase 1: Threat Identification Foundation (Months 1-2)
**Immediate Implementation**:
- Basic threat identification framework and threat documentation mapping
- Initial threat assessment and identification communication framework establishment
- Simple threat identification analysis and threat documentation
- Basic threat identification communication and internal threat alignment processes
- Initial threat identification-related risk assessment and threat documentation

#### Phase 2: Threat Identification Development (Months 3-6)
**Threat Identification Enhancement**:
- Comprehensive threat identification analysis framework development and implementation
- Advanced threat assessment and identification validation system deployment
- Cross-functional threat identification coordination and strategic threat planning integration
- Performance measurement and threat identification optimization system establishment
- Strategic threat identification planning and threat positioning development

#### Phase 3: Threat Identification Optimization (Months 7-12)
**Threat Identification Maturation**:
- Advanced threat identification analytics and strategic threat positioning implementation
- Continuous improvement process establishment and optimization
- Strategic threat leadership development and identification collaboration
- Future capability planning and adaptive threat identification management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.RA-03 subcategory requirements fully addressed
- [ ] Maturity-specific threat identification approaches included for all security ownership levels
- [ ] Threat identification analysis practical and comprehensive
- [ ] Identification strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Internal threats identified and documented
- [ ] External threats identified and documented
- [ ] Threat identification processes established and operational
- [ ] Threat validation capabilities developed and validated
- [ ] Risk assessment integrated with threat identification
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed