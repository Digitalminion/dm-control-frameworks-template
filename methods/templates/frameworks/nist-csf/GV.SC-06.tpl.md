<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-gv-sc-06, supplier-due-diligence, supply-chain-planning, governance-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF GV.SC-06 Planning and Due Diligence Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE GV.SC-06 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF GV.SC-06 (Planning and due diligence are performed to reduce risks 
    before entering into formal supplier agreements) with adaptive content that adjusts based 
    on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on governance outcomes that establish comprehensive 
    supplier evaluation, due diligence, and planning processes with appropriate depth and rigor 
    based on organizational maturity levels and supplier criticality.
    
    TEMPLATE USAGE: Use this template to generate GV.SC-06 documentation that establishes 
    supplier planning and due diligence processes appropriate to the organization's security 
    responsibility maturity level and supplier risk management sophistication.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware GV.SC-06 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF GV.SC-06
    2. GOVERNANCE FOCUS: Emphasize planning and due diligence processes before supplier engagement
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving comprehensive due diligence outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE DUE DILIGENCE DEPTH: Use maturity-specific assessment complexity
    9. INCLUDE RELEVANT PLANNING SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE EVALUATION: Match evaluation rigor to organizational capability
    11. ADJUST PLANNING GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT PROCESSES: Emphasize planning areas important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR GV.SC-06:
    
    IF security_ownership == "business_led":
    - Use business evaluation language focused on vendor assessment and business protection
    - Emphasize due diligence based on business risk and financial impact assessment
    - Include executive and procurement team evaluation and oversight processes
    - Focus on compliance-driven due diligence and standard business evaluation
    - Provide simple assessment frameworks appropriate to business evaluation processes
    - Include vendor relationship and strategic partnership evaluation considerations
    
    IF security_ownership == "it_led":
    - Use IT evaluation language focused on technology supplier assessment and capability validation
    - Emphasize due diligence based on IT service delivery and operational risk assessment
    - Include IT governance and technology supplier evaluation processes
    - Focus on operational and technical capability assessment and validation
    - Provide IT-centric evaluation frameworks and technical assessment procedures
    - Include technology integration and service delivery evaluation considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering evaluation language focused on development and platform supplier assessment
    - Emphasize due diligence based on technical dependencies and architectural evaluation
    - Include engineering governance and technical supplier assessment processes
    - Focus on technical capability assessment and platform integration evaluation
    - Provide engineering-centric evaluation frameworks and technical validation procedures
    - Include development workflow and platform security assessment considerations
    
    IF security_ownership == "infosec_led":
    - Use security evaluation language focused on advanced threat-informed supplier assessment
    - Emphasize due diligence based on security risk and threat landscape evaluation
    - Include security governance and comprehensive security assessment processes
    - Focus on threat-informed evaluation and advanced security posture assessment
    - Provide security-centric evaluation frameworks and advanced assessment procedures
    - Include strategic security partnership and collaboration evaluation considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for evaluation processes and assessment capabilities
    - Read context/risks/ files for risk assessment criteria and tolerance levels
    - Use organizational maturity context to tailor evaluation complexity and assessment depth
    - Consider procurement and legal evaluation capabilities appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Due diligence approaches must be clearly articulated for the maturity level
    - Planning processes must be practical and achievable
    - Evaluation frameworks must align with organizational capability
    - Assessment outcomes must support effective supplier selection and risk reduction
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: GV.SC-06

### Subcategory Information
- **ID**: GV.SC-06
- **Function**: GOVERN (GV)
- **Category**: Supply Chain Risk Management (SC)
- **Title**: Planning and Due Diligence
- **Outcome**: Planning and due diligence are performed to reduce risks before entering into formal supplier agreements

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization conducts comprehensive planning and due diligence activities to evaluate potential suppliers, assess risks, and make informed decisions before establishing formal supplier relationships and agreements.

**Strategic Value**: This subcategory enables risk-informed supplier selection by establishing systematic evaluation processes that identify potential issues, validate supplier capabilities, and reduce supply chain risks before contractual commitments are made.

### Organizational Implementation

#### Current Planning and Due Diligence Assessment
{{#if_business_led}}
**Business-Led Due Diligence Assessment**:
- Current vendor evaluation and selection processes
- Procurement due diligence procedures and financial assessment capabilities
- Legal team contract review and risk evaluation processes
- Executive oversight and approval processes for supplier selection
- Regulatory compliance and business risk evaluation procedures
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Due Diligence Assessment**:
- Technology supplier evaluation and technical capability assessment processes
- IT procurement due diligence and vendor technical validation procedures
- IT governance and service provider evaluation frameworks
- Technical architecture and integration assessment capabilities
- IT service delivery and performance evaluation procedures
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Due Diligence Assessment**:
- Development tool and platform supplier evaluation processes
- Engineering team technical assessment and validation procedures
- DevOps and automation supplier integration evaluation capabilities
- Platform reliability and performance assessment frameworks
- Technical architecture and dependency evaluation procedures
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Due Diligence Assessment**:
- Security vendor evaluation and advanced security assessment processes
- Comprehensive security control and posture evaluation procedures
- Security governance and threat-informed supplier assessment capabilities
- Advanced security partnership and collaboration evaluation frameworks
- Strategic security supplier selection and validation procedures
{{/if_infosec_led}}

#### Framework-Specific Planning and Due Diligence Elements

**Due Diligence Assessment Framework**:
1. **Financial Stability**: Supplier financial health and business continuity assessment
2. **Technical Capability**: Supplier technical competency and service delivery evaluation
3. **Security Posture**: Supplier cybersecurity controls and risk assessment
4. **Compliance Status**: Regulatory compliance and certification validation
5. **Reference Verification**: Customer references and past performance evaluation

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Due Diligence**:
- Develop basic supplier evaluation checklist and assessment criteria
- Establish minimum financial and business stability verification procedures
- Create simple cybersecurity questionnaire and basic security assessment
- Define basic reference check and customer feedback validation process
- Implement basic approval workflow for supplier selection decisions
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Due Diligence**:
- Develop technology supplier evaluation criteria and technical assessment procedures
- Establish IT service capability validation and performance verification processes
- Create technical security assessment and integration evaluation procedures
- Define technology supplier reference validation and performance verification
- Implement IT governance approval workflow for technology supplier selection
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Due Diligence Development
**Risk-Based Due Diligence Enhancement**:
- Develop comprehensive risk-based supplier evaluation methodology
- Create structured due diligence framework with multiple assessment dimensions
- Implement systematic supplier risk assessment and scoring system
- Establish supplier capability validation and performance verification processes
- Develop documented decision-making criteria and approval frameworks

#### Tier 3 (Repeatable) - Systematic Due Diligence Management
**Systematic Due Diligence Operations**:
- Implement automated supplier assessment and evaluation tracking systems
- Establish continuous supplier capability monitoring and validation processes
- Develop advanced supplier risk modeling and scenario analysis capabilities
- Create standardized due diligence lifecycle management and documentation
- Implement comprehensive supplier evaluation performance measurement and optimization

#### Tier 4 (Adaptive) - Advanced Due Diligence Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Due Diligence**:
- Deploy predictive supplier risk assessment with threat intelligence integration
- Implement real-time supplier security posture monitoring and evaluation
- Establish advanced supplier threat modeling and security scenario analysis
- Develop adaptive due diligence processes based on evolving threat landscape
- Create strategic security partnership evaluation with innovation and collaboration focus
{{/if_infosec_led}}

### Technology Implementation

#### Due Diligence Technology Infrastructure
**Supplier Evaluation and Assessment Technology Context**:
- Current supplier evaluation and tracking systems
- Due diligence documentation and workflow management platforms
- Risk assessment and scoring tools
- Supplier information verification and validation capabilities
- Integration capabilities with procurement and contract management systems

{{#if_engineering_led_plus}}
**Engineering-Led Due Diligence Technology**:
- **Technical Assessment**: Automated supplier technical capability evaluation and validation
- **Integration Analysis**: Platform and infrastructure supplier integration assessment tools
- **Performance Monitoring**: Supplier service performance and reliability evaluation systems
- **Security Scanning**: Development tool and platform supplier security assessment automation
- **Documentation Systems**: Technical evaluation documentation and decision tracking platforms
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Due Diligence-Based Risk Management Framework
**Risk Assessment by Evaluation Category**:
1. **Financial Risk**: Supplier financial stability and business continuity impact assessment
2. **Operational Risk**: Supplier service delivery and performance impact evaluation
3. **Security Risk**: Supplier cybersecurity posture and threat exposure assessment
4. **Compliance Risk**: Regulatory compliance and certification validation impact
5. **Strategic Risk**: Supplier relationship and dependency strategic impact assessment

{{#if_business_led}}
**Executive Due Diligence Strategy**:
- Board-level oversight for critical supplier due diligence and evaluation processes
- Executive approval requirements for high-risk supplier selections and decisions
- Strategic planning integration with supplier evaluation and selection processes
- Risk management integration with supplier due diligence and assessment frameworks
- Investment decision-making with comprehensive supplier evaluation consideration
{{/if_business_led}}

### Assessment and Measurement

#### Due Diligence Effectiveness Metrics
**Quantitative Measures**:
- Due diligence process completion rate and timeline adherence
- Supplier evaluation accuracy and post-selection performance correlation
- Risk assessment effectiveness and issue prediction accuracy
- Due diligence cost efficiency and resource utilization optimization
- Supplier selection decision quality and long-term relationship success

**Qualitative Measures**:
- Stakeholder satisfaction with due diligence thoroughness and quality
- Decision-maker confidence in supplier evaluation and selection processes
- Supplier feedback on evaluation process fairness and transparency
- Due diligence adaptability to changing risk landscape and business needs
- Strategic supplier relationship development through effective evaluation

{{#if_infosec_led}}
**InfoSec-Led Due Diligence Assessment**:
- Advanced security evaluation effectiveness in threat mitigation and risk reduction
- Threat-informed due diligence accuracy and strategic relevance
- Security posture assessment correlation with long-term supplier security performance
- Advanced threat modeling integration effectiveness with supplier evaluation
- Strategic security partnership development through comprehensive evaluation processes
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-161**: Cybersecurity Supply Chain Risk Management Practices
- **ISO 27036**: Information Security for Supplier Relationships
- **NIST SP 800-39**: Managing Information Security Risk
- **SOC 2**: Service Organization Control assessment standards
- **ISO 31000**: Risk Management - Guidelines for due diligence processes

#### Implementation Resources
{{#if_business_led}}
**Business-Led Due Diligence Resources**:
- Vendor evaluation and selection framework templates
- Financial stability and business continuity assessment procedures
- Executive governance and supplier selection oversight frameworks
- Legal team due diligence review and risk assessment guidance
- Procurement policy integration with supplier evaluation procedures
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Due Diligence Resources**:
- Technical supplier evaluation and capability assessment frameworks
- Development tool and platform supplier validation procedures
- Engineering governance integration with supplier selection processes
- Technical architecture and integration assessment methodologies
- DevOps and automation supplier evaluation and validation guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Due Diligence Maturity Progression
**Due Diligence Enhancement Pathway**:
1. **Foundation**: Basic supplier evaluation and simple assessment procedures
2. **Development**: Risk-based evaluation frameworks with structured assessment
3. **Integration**: Comprehensive due diligence with lifecycle integration
4. **Optimization**: Advanced predictive assessment with threat intelligence integration
5. **Innovation**: Adaptive evaluation processes with real-time risk adjustment

#### Due Diligence Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Due Diligence Enhancement**:
- Technology supplier evaluation advancement and automation
- Service capability assessment integration with performance monitoring
- IT governance enhancement with supplier evaluation process integration
- Technology innovation integration with strategic supplier assessment
- Automated due diligence workflow and decision support system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **GV.SC-04**: Supplier prioritization informs due diligence intensity and scope
- **GV.SC-05**: Requirements definition provides evaluation criteria and standards
- **GV.SC-01**: Supply chain program provides framework for due diligence processes

#### Supporting Subcategories
**Related Supply Chain Subcategories**:
- **GV.SC-07**: Risk management approach informed by due diligence findings
- **GV.SC-02**: Roles and responsibilities establish authority for due diligence decisions
- **ID.RA-01**: Risk assessment methodology supports supplier evaluation
- **GV.RM-03**: Enterprise risk management integration with supplier due diligence
- **ID.BE-03**: Suppliers and dependencies identification supports planning

### Implementation Timeline

#### Phase 1: Due Diligence Foundation (Months 1-3)
**Immediate Implementation**:
- Basic supplier evaluation criteria and assessment procedure development
- Initial due diligence workflow and documentation framework establishment
- Stakeholder training on evaluation processes and decision criteria
- Basic technology platform selection and implementation for tracking
- Initial supplier evaluation pilot program and process validation

#### Phase 2: Due Diligence Development (Months 4-8)
**Due Diligence Enhancement**:
- Comprehensive evaluation framework development with risk-based assessment
- Advanced due diligence technology platform implementation and integration
- Supplier evaluation team training and capability development programs
- Performance measurement and process optimization system deployment
- Cross-functional coordination and decision-making framework establishment

#### Phase 3: Due Diligence Optimization (Months 9-12)
**Due Diligence Maturation**:
- Advanced assessment analytics and predictive evaluation implementation
- Continuous improvement process establishment and optimization
- Strategic supplier partnership evaluation development
- Industry collaboration and best practice integration
- Future capability planning and adaptive assessment framework development

### Quality Assurance

#### Template Validation Checklist
- [ ] GV.SC-06 subcategory requirements fully addressed
- [ ] Maturity-specific due diligence approaches included for all security ownership levels
- [ ] Planning processes practical and achievable
- [ ] Evaluation frameworks appropriate for maturity level
- [ ] Assessment outcomes comprehensive and actionable
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Supplier evaluation criteria defined and documented
- [ ] Due diligence processes established and operational
- [ ] Assessment workflows implemented and functional
- [ ] Technology platforms deployed for evaluation tracking
- [ ] Stakeholder training completed and ongoing
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Cross-functional coordination mechanisms established