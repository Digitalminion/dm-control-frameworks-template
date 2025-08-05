<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-be-04, business-environment, resilience-requirements, operational-states, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.BE-04 Resilience Requirements Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.BE-04 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.BE-04 (Resilience requirements to support delivery of critical 
    services are established for all operating states) with adaptive content that adjusts based 
    on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of resilience requirements across operating states with appropriate 
    depth based on organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.BE-04 documentation that establishes 
    resilience requirements appropriate to the organization's security responsibility 
    maturity level and operational resilience needs.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.BE-04 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.BE-04
    2. IDENTIFICATION FOCUS: Emphasize resilience requirements establishment across operating states
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear resilience requirements identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE RESILIENCE COMPLEXITY: Use maturity-specific resilience and operating state analysis depth
    9. INCLUDE RELEVANT RESILIENCE SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE REQUIREMENTS: Match requirements approach to organizational capability
    11. ADJUST RESILIENCE GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT STATES: Emphasize operating states important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.BE-04:
    
    IF security_ownership == "business_led":
    - Use business language focused on business continuity and operational resilience requirements
    - Emphasize resilience requirements based on business operations and customer service continuity
    - Include executive and operational resilience planning and business continuity requirements
    - Focus on compliance-driven resilience requirements and business impact considerations
    - Provide simple resilience frameworks appropriate to business operations management
    - Include customer service and business continuity resilience considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology resilience and service continuity requirements
    - Emphasize resilience requirements based on IT service delivery and infrastructure continuity
    - Include IT governance and technology resilience planning and service continuity requirements
    - Focus on operational resilience requirements and IT service continuity considerations
    - Provide IT-centric resilience frameworks and technology continuity analysis
    - Include technology integration and service delivery resilience considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical resilience and platform continuity requirements
    - Emphasize resilience requirements based on engineering operations and platform reliability
    - Include engineering governance and technical resilience planning and development continuity requirements
    - Focus on technical resilience requirements and engineering platform continuity considerations
    - Provide engineering-centric resilience frameworks and technical continuity analysis
    - Include development workflow and platform integration resilience considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive resilience and threat-informed continuity requirements
    - Emphasize resilience requirements based on security operations and threat response continuity
    - Include security governance and strategic resilience planning and security continuity requirements
    - Focus on threat-informed resilience requirements and comprehensive continuity considerations
    - Provide security-centric resilience frameworks and advanced continuity analysis
    - Include strategic security operations and threat landscape resilience considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for operational requirements and resilience needs
    - Read context/stakeholders/ files for stakeholder expectations and continuity requirements
    - Use organizational maturity context to tailor resilience complexity and requirements
    - Consider operational complexity and resilience criticality appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Resilience requirements approaches must be clearly articulated for the maturity level
    - Requirements strategies must be practical and effective
    - Operating state analysis must align with organizational capability
    - Identification outcomes must support effective resilience management
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.BE-04

### Subcategory Information
- **ID**: ID.BE-04
- **Function**: IDENTIFY (ID)
- **Category**: Business Environment (BE)
- **Title**: Resilience Requirements
- **Outcome**: Resilience requirements to support delivery of critical services are established for all operating states (e.g. under duress/attack, during recovery, normal operations)

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization establishes comprehensive resilience requirements to support the delivery of critical services across all operating states, including normal operations, under duress/attack, and during recovery phases.

**Strategic Value**: This subcategory creates foundational resilience planning by establishing clear requirements for maintaining critical service delivery across various operational conditions, enabling more effective risk management, incident response planning, and business continuity decisions.

### Organizational Implementation

#### Current Resilience Requirements Assessment
{{#if_business_led}}
**Business-Led Resilience Assessment**:
- Current business continuity and operational resilience requirement analysis
- Customer service delivery and business operation resilience requirement mapping
- Revenue protection and business function resilience requirement identification
- Executive and stakeholder resilience expectation assessment and prioritization
- Regulatory compliance and business continuity resilience requirement documentation
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Resilience Assessment**:
- Technology infrastructure and IT service resilience requirement analysis
- Cloud service provider and technology platform resilience requirement mapping
- IT service delivery and infrastructure resilience requirement identification
- Technology integration and platform resilience requirement assessment and prioritization
- IT infrastructure and service operation resilience requirement documentation
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Resilience Assessment**:
- Software development and technical platform resilience requirement analysis
- Development tool and infrastructure resilience requirement mapping and integration
- Platform and infrastructure service resilience requirement identification
- Technical ecosystem and engineering resilience requirement assessment and prioritization
- Engineering platform and development operation resilience requirement documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Resilience Assessment**:
- Security infrastructure and threat response resilience requirement analysis
- Advanced security service and control resilience requirement mapping and assessment
- Security operations and incident response resilience requirement identification
- Comprehensive security and threat management resilience requirement assessment and prioritization
- Strategic security operation and threat landscape resilience requirement documentation
{{/if_infosec_led}}

#### Framework-Specific Resilience Requirements Elements

**Resilience Requirements Framework**:
1. **Operating State Definition**: Clear identification of normal, under duress, and recovery operating states
2. **Service Continuity Requirements**: Specific requirements for critical service delivery across states
3. **Performance Standards**: Acceptable performance levels for each operating state
4. **Recovery Objectives**: Clear recovery time and recovery point objectives for state transitions
5. **Resource Allocation**: Required resources and capabilities for each operating state

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Resilience Establishment**:
- Document fundamental business continuity requirements and primary service resilience
- Create simple resilience mapping and basic operating state identification
- Identify key business function resilience requirements and core operation continuity
- Establish basic resilience communication and business continuity documentation
- Define minimum service continuity requirements and resilience tracking
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Resilience Establishment**:
- Document technology service resilience requirements and primary IT function continuity
- Create simple IT resilience mapping and service delivery state identification
- Identify critical technology service resilience requirements and core IT operation continuity
- Establish basic IT resilience communication and service continuity documentation
- Define minimum IT service continuity requirements and technology resilience tracking
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Resilience Development
**Risk-Based Resilience Enhancement**:
- Develop comprehensive resilience requirements with risk assessment integration
- Create structured operating state analysis across multiple service dimensions
- Implement systematic resilience monitoring and state validation processes
- Establish risk-informed resilience communication and state management
- Develop coordinated resilience documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Resilience Management
**Systematic Resilience Operations**:
- Implement automated resilience monitoring and state performance tracking systems
- Establish continuous resilience assessment and operating state evolution tracking
- Develop advanced resilience analytics and state optimization analysis
- Create standardized resilience communication and state management processes
- Implement comprehensive resilience performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Resilience Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Resilience Management**:
- Deploy predictive resilience analytics with threat intelligence integration
- Implement real-time resilience monitoring with adaptive state strategies
- Establish dynamic resilience assessment with strategic state optimization
- Develop advanced threat-informed resilience communication and collaboration
- Create strategic state positioning with industry resilience and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Resilience Management Technology Infrastructure
**Resilience Requirements Management Technology Context**:
- Current business continuity and disaster recovery systems
- Service monitoring and performance tracking platforms
- Resilience testing and validation tools
- Communication and notification systems for state transitions
- Integration capabilities with enterprise systems and external services

{{#if_engineering_led_plus}}
**Engineering-Led Resilience Technology**:
- **Resilience Monitoring**: Automated platform and service resilience analysis and state tracking
- **State Management**: Technical resilience state tracking and transition analysis
- **Resilience Testing**: Technical platform resilience testing and development workflow validation
- **Communication Platforms**: Engineering team resilience and state communication and collaboration
- **Analytics Systems**: Technical resilience analysis and state optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Resilience-Based Risk Management Framework
**Risk Assessment by Resilience Category**:
1. **Service Degradation Risk**: Critical service performance degradation impact across operating states
2. **State Transition Risk**: Operating state transition failure impact on service delivery
3. **Recovery Risk**: Recovery process failure impact on service restoration
4. **Resource Risk**: Insufficient resources for resilience requirements across states
5. **Strategic Risk**: Long-term resilience capability sustainability and evolution implications

{{#if_business_led}}
**Executive Resilience Strategy**:
- Board-level resilience requirements oversight and strategic continuity governance
- Executive decision-making for resilience evolution and strategic state management development
- Strategic planning integration with resilience optimization and state positioning
- Investment decision-making with resilience-based state risk assessment
- Crisis management coordination with resilience-specific business continuity planning
{{/if_business_led}}

### Assessment and Measurement

#### Resilience Requirements Effectiveness Metrics
**Quantitative Measures**:
- Resilience requirements documentation completeness and operating state coverage assessment
- Resilience performance tracking and state transition effectiveness measurement
- Resilience-related incident frequency and state management impact tracking
- Service restoration time and resilience recovery effectiveness measurement
- Resilience optimization and state positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with resilience clarity and state communication effectiveness
- Internal team alignment on resilience requirements and state management strategy
- Resilience adaptability to changing operational environment and state conditions
- Strategic resilience development and state positioning advancement
- Leadership effectiveness in resilience communication and state coordination

{{#if_infosec_led}}
**InfoSec-Led Resilience Assessment**:
- Advanced security resilience effectiveness in threat mitigation and state protection
- Threat-informed resilience positioning accuracy and strategic security state relevance
- Security resilience collaboration effectiveness and threat intelligence integration
- Advanced resilience modeling integration with threat landscape state analysis
- Strategic security leadership development through resilience and state positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **ISO 22301**: Business Continuity Management Systems
- **NIST SP 800-34**: Contingency Planning Guide for Federal Information Systems
- **ISO 27031**: Information Technology - Security - Guidelines for ICT Readiness for Business Continuity
- **COBIT**: Business and IT governance framework for resilience management
- **ITIL**: IT Service Management for service resilience analysis

#### Implementation Resources
{{#if_business_led}}
**Business-Led Resilience Resources**:
- Business continuity planning and resilience analysis frameworks
- Service delivery and operational resilience management procedures
- Executive governance and resilience requirements strategic planning
- Business continuity planning and state management methodologies
- Strategic resilience and business state development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Resilience Resources**:
- Technical resilience and development state frameworks
- Software development resilience and platform management procedures
- Engineering governance integration with resilience state planning
- Platform architecture and integration resilience optimization methodologies
- DevOps and automation resilience state development and management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Resilience Maturity Progression
**Resilience Enhancement Pathway**:
1. **Foundation**: Basic resilience identification and simple state documentation
2. **Development**: Systematic resilience analysis with structured state management
3. **Integration**: Comprehensive resilience optimization with strategic state integration
4. **Optimization**: Advanced predictive resilience management with state intelligence
5. **Innovation**: Adaptive state leadership with strategic positioning and resilience

#### Resilience Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Resilience Enhancement**:
- Technology resilience advancement and automation
- Service delivery state integration with strategic IT planning
- IT governance enhancement with resilience state management integration
- Technology innovation integration with strategic resilience positioning
- Automated resilience analysis and state optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.BE-03**: Dependencies and critical functions provide foundation for resilience requirements
- **ID.BE-02**: Mission objectives establish context for resilience planning
- **GV.OC-01**: Organizational mission supports resilience requirements definition

#### Supporting Subcategories
**Related Business Environment Subcategories**:
- **ID.BE-01**: Supply chain role supports resilience requirements context
- **ID.BE-05**: Mission context integrates with resilience planning
- **RC.RP-01**: Recovery planning coordinates with resilience requirements
- **RC.IM-01**: Recovery improvement aligns with resilience optimization
- **RS.RP-01**: Response planning integrates with under duress operating state requirements

### Implementation Timeline

#### Phase 1: Resilience Foundation (Months 1-2)
**Immediate Implementation**:
- Basic resilience requirements identification and operating state mapping
- Initial state performance assessment and resilience communication framework establishment
- Simple resilience analysis and service continuity identification
- Basic resilience communication and internal state alignment processes
- Initial resilience-related risk assessment and state documentation

#### Phase 2: Resilience Development (Months 3-6)
**Resilience Enhancement**:
- Comprehensive resilience analysis framework development and implementation
- Advanced state management assessment and resilience validation system deployment
- Cross-functional resilience coordination and strategic state planning integration
- Performance measurement and resilience optimization system establishment
- Strategic resilience planning and state positioning development

#### Phase 3: Resilience Optimization (Months 7-12)
**Resilience Maturation**:
- Advanced resilience analytics and strategic state positioning implementation
- Continuous improvement process establishment and optimization
- Strategic state leadership development and resilience collaboration
- Future capability planning and adaptive resilience management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.BE-04 subcategory requirements fully addressed
- [ ] Maturity-specific resilience identification approaches included for all security ownership levels
- [ ] Resilience analysis practical and comprehensive
- [ ] Operating state analysis strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Resilience requirements identified and documented
- [ ] Operating states established and defined
- [ ] Resilience analysis completed and validated
- [ ] Risk assessment integrated with resilience positioning
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed