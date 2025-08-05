<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-am-05, asset-management, asset-prioritization, criticality-assessment, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.AM-05 Asset Prioritization Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.AM-05 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.AM-05 (Assets are prioritized based on classification, criticality, 
    resources, and impact on the mission) with adaptive content that adjusts based on 
    organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of asset prioritization with appropriate depth based on organizational 
    maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.AM-05 documentation that prioritizes 
    assets appropriate to the organization's security responsibility maturity level and 
    business criticality complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.AM-05 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.AM-05
    2. IDENTIFICATION FOCUS: Emphasize asset prioritization based on multiple criteria
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear asset prioritization outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE PRIORITIZATION COMPLEXITY: Use maturity-specific asset prioritization analysis depth
    9. INCLUDE RELEVANT PRIORITIZATION SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE CRITERIA: Match prioritization criteria to organizational capability
    11. ADJUST PRIORITIZATION GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT ASSETS: Emphasize asset types important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.AM-05:
    
    IF security_ownership == "business_led":
    - Use business language focused on business-critical assets and operational prioritization
    - Emphasize asset prioritization based on business value and revenue impact
    - Include executive and operational asset governance and business asset prioritization
    - Focus on compliance-driven asset prioritization and business impact considerations
    - Provide simple asset prioritization frameworks appropriate to business operations management
    - Include business asset value and operational asset prioritization considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology assets and infrastructure prioritization
    - Emphasize asset prioritization based on IT service delivery and operational criticality
    - Include IT governance and technology asset prioritization and infrastructure criticality
    - Focus on operational asset prioritization and IT service asset considerations
    - Provide IT-centric asset prioritization frameworks and technology criticality analysis
    - Include technology asset value and infrastructure asset prioritization considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical assets and platform prioritization
    - Emphasize asset prioritization based on engineering operations and platform criticality
    - Include engineering governance and technical asset prioritization and development criticality
    - Focus on technical asset prioritization and engineering platform asset considerations
    - Provide engineering-centric asset prioritization frameworks and technical criticality analysis
    - Include development asset value and platform asset prioritization considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive assets and security-informed prioritization
    - Emphasize asset prioritization based on security risk and threat landscape considerations
    - Include security governance and strategic asset prioritization and security criticality
    - Focus on threat-informed asset prioritization and comprehensive security considerations
    - Provide security-centric asset prioritization frameworks and advanced criticality analysis
    - Include strategic security asset value and comprehensive asset prioritization considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for business priorities and asset dependencies
    - Read context/stakeholders/ files for stakeholder asset expectations and criticality requirements
    - Use organizational maturity context to tailor prioritization complexity and criteria
    - Consider asset complexity and criticality assessment capability appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Asset prioritization approaches must be clearly articulated for the maturity level
    - Prioritization strategies must be practical and effective
    - Criticality analysis must align with organizational capability
    - Identification outcomes must support effective asset management and resource allocation
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.AM-05

### Subcategory Information
- **ID**: ID.AM-05
- **Function**: IDENTIFY (ID)
- **Category**: Asset Management (AM)
- **Title**: Asset Prioritization
- **Outcome**: Assets are prioritized based on classification, criticality, resources, and impact on the mission

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization establishes and maintains a systematic approach to prioritize assets based on their classification, criticality to operations, resource requirements, and impact on organizational mission achievement, enabling informed resource allocation and risk management decisions.

**Strategic Value**: This subcategory establishes foundational asset prioritization by creating comprehensive asset valuation and criticality assessment processes, enabling more effective resource allocation, risk-based security investments, and mission-focused protection strategies based on actual business value and operational impact.

### Organizational Implementation

#### Current Asset Prioritization Assessment
{{#if_business_led}}
**Business-Led Asset Prioritization Assessment**:
- Current business asset valuation and operational criticality analysis
- Customer-facing asset prioritization and business-critical asset value mapping
- Business application asset prioritization and operational asset criticality identification
- Executive and operational asset governance and business asset prioritization requirements
- Regulatory compliance and business asset prioritization documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Asset Prioritization Assessment**:
- Technology infrastructure and IT asset criticality analysis
- Cloud service provider and technology platform asset prioritization mapping
- IT service delivery and infrastructure asset criticality identification
- Technology integration and platform asset prioritization assessment and documentation
- IT infrastructure and service operation asset prioritization requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Asset Prioritization Assessment**:
- Software development and technical platform asset criticality analysis
- Development tool and infrastructure asset prioritization mapping
- Platform and infrastructure technical asset criticality identification
- Technical ecosystem and engineering asset prioritization integration assessment
- Engineering platform and development operation asset prioritization documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Asset Prioritization Assessment**:
- Security infrastructure and comprehensive asset criticality analysis
- Advanced security asset prioritization and strategic asset value mapping and assessment
- Security operations and incident response asset prioritization identification
- Comprehensive security and risk management asset prioritization assessment
- Strategic security operation and threat landscape asset prioritization documentation
{{/if_infosec_led}}

#### Framework-Specific Asset Prioritization Elements

**Asset Prioritization Framework**:
1. **Classification Criteria**: Systematic categorization of assets by type, sensitivity, and function
2. **Criticality Assessment**: Analysis of asset importance to business operations and mission delivery
3. **Resource Impact**: Evaluation of resource requirements for asset protection and maintenance
4. **Mission Alignment**: Assessment of asset contribution to organizational mission achievement
5. **Risk-Based Prioritization**: Integration of threat landscape and vulnerability assessment in prioritization

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Asset Prioritization**:
- Document fundamental business asset prioritization and primary asset value assessment
- Create simple asset prioritization mapping and basic asset criticality identification
- Identify key business asset priorities and core asset value determination processes
- Establish basic asset prioritization communication and business asset value documentation
- Define minimum asset prioritization collection and business asset tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Asset Prioritization**:
- Document technology asset prioritization and primary IT asset criticality assessment
- Create simple IT asset prioritization mapping and technology asset value identification
- Identify critical technology asset priorities and core IT asset criticality processes
- Establish basic IT asset prioritization communication and technology asset value documentation
- Define minimum IT asset prioritization collection and technology asset tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Asset Prioritization
**Risk-Based Asset Prioritization Enhancement**:
- Develop comprehensive asset prioritization analysis with risk assessment and value integration
- Create structured asset analysis across multiple prioritization and criticality dimensions
- Implement systematic asset prioritization monitoring and value validation processes
- Establish risk-informed asset prioritization communication and asset management
- Develop coordinated asset prioritization documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Asset Prioritization Management
**Systematic Asset Prioritization Operations**:
- Implement automated asset prioritization assessment and criticality analysis systems
- Establish continuous asset prioritization monitoring and value evolution tracking
- Develop advanced asset prioritization analytics and criticality optimization analysis
- Create standardized asset prioritization communication and asset management processes
- Implement comprehensive asset prioritization performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Asset Prioritization Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Asset Prioritization Management**:
- Deploy predictive asset prioritization analytics with threat intelligence and value integration
- Implement real-time asset prioritization monitoring with adaptive criticality strategies
- Establish dynamic asset prioritization assessment with strategic value optimization
- Develop advanced threat-informed asset prioritization communication and collaboration
- Create strategic asset positioning with industry prioritization and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Asset Prioritization Technology Infrastructure
**Asset Prioritization Management Technology Context**:
- Current asset management and inventory systems
- Asset tracking and prioritization platforms
- Business impact analysis and criticality assessment tools
- Risk assessment and threat analysis integration
- Integration capabilities with enterprise asset management and security tools

{{#if_engineering_led_plus}}
**Engineering-Led Asset Prioritization Technology**:
- **Asset Assessment**: Automated platform and development asset prioritization analysis and mapping
- **Criticality Analysis**: Technical asset prioritization tracking and value integration analysis systems
- **Prioritization Modeling**: Technical asset prioritization design and development value visualization
- **Communication Platforms**: Engineering team asset prioritization and value communication and collaboration
- **Analytics Systems**: Technical asset prioritization analysis and criticality optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Asset Prioritization-Based Risk Management Framework
**Risk Assessment by Asset Prioritization Category**:
1. **High-Value Asset Risk**: Critical asset compromise impact on organizational mission and operations
2. **Resource Allocation Risk**: Misallocated security resources impact on asset protection effectiveness
3. **Prioritization Gap Risk**: Incorrect asset prioritization impact on security investment decisions
4. **Mission Impact Risk**: Asset unavailability impact on mission delivery and business objectives
5. **Strategic Risk**: Long-term asset prioritization capability sustainability and evolution implications

{{#if_business_led}}
**Executive Asset Prioritization Strategy**:
- Board-level asset prioritization oversight and strategic asset value governance
- Executive decision-making for asset prioritization evolution and strategic asset development
- Strategic planning integration with asset prioritization optimization and value positioning
- Investment decision-making with asset prioritization-based risk assessment
- Crisis management coordination with asset prioritization-specific business continuity planning
{{/if_business_led}}

### Assessment and Measurement

#### Asset Prioritization Effectiveness Metrics
**Quantitative Measures**:
- Asset prioritization coverage and criticality assessment effectiveness
- Asset prioritization accuracy and value determination effectiveness measurement
- Asset prioritization-related incident impact and protection effectiveness tracking
- Prioritization processing time and asset response effectiveness measurement
- Asset prioritization optimization and value positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with asset prioritization clarity and value communication effectiveness
- Internal team alignment on asset prioritization and asset management strategy
- Asset prioritization adaptability to changing business environment and value conditions
- Strategic asset prioritization development and value positioning advancement
- Leadership effectiveness in asset prioritization communication and value coordination

{{#if_infosec_led}}
**InfoSec-Led Asset Prioritization Assessment**:
- Advanced security asset prioritization effectiveness in threat mitigation and asset protection
- Threat-informed asset prioritization positioning accuracy and strategic security value relevance
- Security asset prioritization collaboration effectiveness and risk analysis integration
- Advanced asset prioritization modeling integration with threat landscape analysis
- Strategic security leadership development through asset prioritization positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-30**: Guide for Conducting Risk Assessments
- **ISO 27005**: Information Security Risk Management
- **NIST SP 800-53**: Security and Privacy Controls (CP, RA families)
- **COBIT**: Business and IT governance framework for asset management
- **ISO 55001**: Asset Management Systems

#### Implementation Resources
{{#if_business_led}}
**Business-Led Asset Prioritization Resources**:
- Business asset prioritization and value assessment frameworks
- Executive asset prioritization oversight and business value strategic planning
- Compliance asset prioritization documentation and business value protection procedures
- Business asset prioritization planning and operational value methodologies
- Strategic asset prioritization and business value development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Asset Prioritization Resources**:
- Technical asset prioritization and development value frameworks
- Software development asset prioritization design and platform value procedures
- Engineering governance integration with asset prioritization planning
- Platform value optimization and integration asset prioritization methodologies
- DevOps and automation asset prioritization development and value management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Asset Prioritization Maturity Progression
**Asset Prioritization Enhancement Pathway**:
1. **Foundation**: Basic asset prioritization identification and simple value documentation
2. **Development**: Systematic asset prioritization analysis with structured value management
3. **Integration**: Comprehensive asset prioritization optimization with strategic value integration
4. **Optimization**: Advanced predictive asset prioritization management with value intelligence
5. **Innovation**: Adaptive value leadership with strategic asset prioritization positioning and security

#### Asset Prioritization Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Asset Prioritization Enhancement**:
- Technology asset prioritization advancement and automation
- Service delivery value integration with strategic IT asset prioritization planning
- IT governance enhancement with asset prioritization value management integration
- Technology innovation integration with strategic asset prioritization positioning
- Automated asset prioritization analysis and value optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.AM-01**: Hardware inventory provides foundation for asset prioritization
- **ID.AM-02**: Software inventory supports asset prioritization analysis
- **ID.AM-03**: Network architecture contributes to asset criticality assessment

#### Supporting Subcategories
**Related Asset Management Subcategories**:
- **ID.AM-04**: Supplier services prioritization aligns with organizational asset priorities
- **ID.AM-07**: Data inventory prioritization coordinates with asset value assessment
- **ID.AM-08**: Lifecycle management integrates with asset prioritization strategies
- **ID.BE-02**: Mission objectives provide context for asset prioritization
- **ID.BE-03**: Dependencies analysis supports asset criticality assessment

### Implementation Timeline

#### Phase 1: Asset Prioritization Foundation (Months 1-2)
**Immediate Implementation**:
- Basic asset prioritization framework and value assessment mapping
- Initial asset criticality assessment and prioritization communication framework establishment
- Simple asset prioritization analysis and value documentation
- Basic asset prioritization communication and internal value alignment processes
- Initial asset prioritization-related risk assessment and value documentation

#### Phase 2: Asset Prioritization Development (Months 3-6)
**Asset Prioritization Enhancement**:
- Comprehensive asset prioritization analysis framework development and implementation
- Advanced asset value assessment and prioritization validation system deployment
- Cross-functional asset prioritization coordination and strategic value planning integration
- Performance measurement and asset prioritization optimization system establishment
- Strategic asset prioritization planning and value positioning development

#### Phase 3: Asset Prioritization Optimization (Months 7-12)
**Asset Prioritization Maturation**:
- Advanced asset prioritization analytics and strategic value positioning implementation
- Continuous improvement process establishment and optimization
- Strategic value leadership development and asset prioritization collaboration
- Future capability planning and adaptive asset prioritization management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.AM-05 subcategory requirements fully addressed
- [ ] Maturity-specific asset prioritization approaches included for all security ownership levels
- [ ] Asset prioritization analysis practical and comprehensive
- [ ] Prioritization strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Asset prioritization criteria established and documented
- [ ] Asset classification system implemented and operational
- [ ] Criticality assessment processes developed and validated
- [ ] Risk assessment integrated with asset prioritization
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed