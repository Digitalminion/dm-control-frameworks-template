<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-ra-04, risk-assessment, business-impact-analysis, criticality-assessment, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.RA-04 Business Impact Analysis Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.RA-04 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.RA-04 (Business impact analysis is used to inform risk assessment 
    and risk management decisions) with adaptive content that adjusts based on organizational 
    security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of business impact analysis with appropriate depth based on organizational 
    maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.RA-04 documentation that conducts 
    business impact analysis appropriate to the organization's security responsibility 
    maturity level and business complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.RA-04 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.RA-04
    2. IDENTIFICATION FOCUS: Emphasize business impact analysis for risk assessment and management
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear business impact identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE IMPACT COMPLEXITY: Use maturity-specific business impact analysis depth
    9. INCLUDE RELEVANT IMPACT SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE ANALYSIS: Match impact analysis to organizational capability
    11. ADJUST IMPACT GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT IMPACTS: Emphasize impact types important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.RA-04:
    
    IF security_ownership == "business_led":
    - Use business language focused on business impact and operational disruption analysis
    - Emphasize impact analysis based on business value and revenue impact considerations
    - Include executive and operational impact governance and business disruption assessment
    - Focus on compliance-driven impact analysis and business continuity impact considerations
    - Provide simple impact analysis frameworks appropriate to business operations management
    - Include business value impact and operational impact analysis considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology impact and infrastructure disruption analysis
    - Emphasize impact analysis based on IT service delivery and technology operational impact
    - Include IT governance and technology impact analysis and infrastructure disruption assessment
    - Focus on operational impact analysis and IT service impact considerations
    - Provide IT-centric impact analysis frameworks and technology disruption analysis
    - Include technology service impact and infrastructure impact analysis considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical impact and development disruption analysis
    - Emphasize impact analysis based on engineering operations and platform impact considerations
    - Include engineering governance and technical impact analysis and development disruption assessment
    - Focus on technical impact analysis and engineering platform impact considerations
    - Provide engineering-centric impact analysis frameworks and technical disruption analysis
    - Include development platform impact and engineering impact analysis considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive impact and security-informed disruption analysis
    - Emphasize impact analysis based on security risk and threat landscape impact considerations
    - Include security governance and strategic impact analysis and security disruption assessment
    - Focus on threat-informed impact analysis and comprehensive security impact considerations
    - Provide security-centric impact analysis frameworks and advanced disruption analysis
    - Include strategic security impact and comprehensive impact analysis considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for business processes and operational dependencies
    - Read context/stakeholders/ files for stakeholder impact expectations and business requirements
    - Use organizational maturity context to tailor impact analysis complexity and scope
    - Consider business complexity and impact assessment capability appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Business impact approaches must be clearly articulated for the maturity level
    - Impact analysis strategies must be practical and effective
    - Business analysis must align with organizational capability
    - Identification outcomes must support effective risk assessment and business continuity
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.RA-04

### Subcategory Information
- **ID**: ID.RA-04
- **Function**: IDENTIFY (ID)
- **Category**: Risk Assessment (RA)
- **Title**: Business Impact Analysis
- **Outcome**: Business impact analysis is used to inform risk assessment and risk management decisions

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization conducts systematic business impact analysis to identify and quantify the potential consequences of cybersecurity incidents on business operations, enabling informed risk assessment decisions and prioritized risk management strategies aligned with business objectives.

**Strategic Value**: This subcategory establishes foundational business impact understanding by creating comprehensive impact analysis processes, enabling more effective risk prioritization, business continuity planning, and risk management strategies based on actual business value and operational dependencies.

### Organizational Implementation

#### Current Business Impact Analysis Assessment
{{#if_business_led}}
**Business-Led Impact Analysis Assessment**:
- Current business impact assessment and operational disruption analysis
- Customer-facing impact analysis and business-critical disruption mapping
- Business application impact analysis and operational disruption identification
- Executive and operational impact governance and business impact requirements
- Regulatory compliance and business impact analysis documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Impact Analysis Assessment**:
- Technology infrastructure and IT impact analysis
- Cloud service provider and technology platform impact mapping
- IT service delivery and infrastructure impact identification
- Technology integration and platform impact assessment and documentation
- IT infrastructure and service operation impact requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Impact Analysis Assessment**:
- Software development and technical platform impact analysis
- Development tool and infrastructure impact mapping
- Platform and infrastructure technical impact identification
- Technical ecosystem and engineering impact integration assessment
- Engineering platform and development operation impact documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Impact Analysis Assessment**:
- Security infrastructure and comprehensive impact analysis
- Advanced security impact analysis and strategic impact mapping and assessment
- Security operations and incident response impact identification
- Comprehensive security and threat management impact assessment
- Strategic security operation and threat landscape impact documentation
{{/if_infosec_led}}

#### Framework-Specific Business Impact Elements

**Business Impact Analysis Framework**:
1. **Impact Categories**: Systematic classification of potential business impact types
2. **Criticality Assessment**: Analysis of business process and asset criticality levels
3. **Financial Impact**: Quantitative assessment of potential financial consequences
4. **Operational Impact**: Analysis of operational disruption and recovery requirements
5. **Stakeholder Impact**: Assessment of impact on customers, partners, and stakeholders

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Impact Analysis**:
- Document fundamental business impact and primary disruption scenarios
- Create simple impact mapping and basic business disruption identification
- Identify key business impact types and core impact determination processes
- Establish basic impact communication and business disruption documentation
- Define minimum impact analysis collection and business impact tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Impact Analysis**:
- Document technology impact and primary IT disruption scenarios
- Create simple IT impact mapping and technology disruption identification
- Identify critical technology impact types and core IT impact processes
- Establish basic IT impact communication and technology disruption documentation
- Define minimum IT impact analysis collection and technology impact tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Business Impact Analysis
**Risk-Based Impact Analysis Enhancement**:
- Develop comprehensive impact analysis with risk assessment and business integration
- Create structured impact analysis across multiple business and operational dimensions
- Implement systematic impact monitoring and business validation processes
- Establish risk-informed impact communication and business management
- Develop coordinated impact documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Business Impact Management
**Systematic Impact Analysis Operations**:
- Implement automated impact assessment and business analysis systems
- Establish continuous impact monitoring and business evolution tracking
- Develop advanced impact analytics and business optimization analysis
- Create standardized impact communication and business management processes
- Implement comprehensive impact performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Business Impact Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Impact Analysis Management**:
- Deploy predictive impact analytics with threat intelligence and business integration
- Implement real-time impact monitoring with adaptive business strategies
- Establish dynamic impact assessment with strategic business optimization
- Develop advanced threat-informed impact communication and collaboration
- Create strategic business positioning with industry impact and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Business Impact Analysis Technology Infrastructure
**Impact Analysis Management Technology Context**:
- Current business continuity and impact analysis tools
- Financial modeling and quantitative analysis platforms
- Business process management and workflow systems
- Risk assessment and business analysis integration tools
- Integration capabilities with enterprise risk management and business tools

{{#if_engineering_led_plus}}
**Engineering-Led Impact Analysis Technology**:
- **Impact Modeling**: Automated platform and development impact analysis and mapping
- **Business Analysis**: Technical impact tracking and business integration analysis systems
- **Impact Visualization**: Technical impact design and development business visualization
- **Communication Platforms**: Engineering team impact and business communication and collaboration
- **Analytics Systems**: Technical impact analysis and business optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Impact Analysis-Based Risk Management Framework
**Risk Assessment by Business Impact Category**:
1. **Revenue Impact Risk**: Financial loss from cybersecurity incidents impact on business revenue
2. **Operational Impact Risk**: Business process disruption impact on operational effectiveness
3. **Reputation Impact Risk**: Customer and stakeholder confidence impact on business reputation
4. **Compliance Impact Risk**: Regulatory non-compliance impact on business operations
5. **Strategic Risk**: Long-term business impact capability sustainability and evolution implications

{{#if_business_led}}
**Executive Business Impact Strategy**:
- Board-level impact oversight and strategic business governance
- Executive decision-making for impact evolution and strategic business development
- Strategic planning integration with impact optimization and business positioning
- Investment decision-making with impact-based risk assessment
- Crisis management coordination with impact-specific business continuity planning
{{/if_business_led}}

### Assessment and Measurement

#### Business Impact Analysis Effectiveness Metrics
**Quantitative Measures**:
- Impact analysis coverage and business assessment completeness
- Impact analysis accuracy and business impact prediction effectiveness measurement
- Impact analysis-related incident response and business recovery tracking
- Analysis processing time and business decision effectiveness measurement
- Impact optimization and business positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with impact clarity and business communication effectiveness
- Internal team alignment on impact analysis and business management strategy
- Impact analysis adaptability to changing business environment and impact conditions
- Strategic impact development and business positioning advancement
- Leadership effectiveness in impact communication and business coordination

{{#if_infosec_led}}
**InfoSec-Led Impact Analysis Assessment**:
- Advanced security impact effectiveness in threat mitigation and business protection
- Threat-informed impact positioning accuracy and strategic security business relevance
- Security impact collaboration effectiveness and business analysis integration
- Advanced impact modeling integration with threat landscape analysis
- Strategic security leadership development through impact and business positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-34**: Contingency Planning Guide for Federal Information Systems
- **ISO 22301**: Business Continuity Management Systems
- **NIST SP 800-30**: Guide for Conducting Risk Assessments
- **ISO 27005**: Information Security Risk Management
- **COBIT**: Business and IT governance framework for impact analysis

#### Implementation Resources
{{#if_business_led}}
**Business-Led Impact Analysis Resources**:
- Business impact analysis and assessment frameworks
- Executive impact oversight and business strategic planning
- Compliance impact documentation and business protection procedures
- Business impact planning and operational analysis methodologies
- Strategic impact and business development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Impact Analysis Resources**:
- Technical impact analysis and development business frameworks
- Software development impact design and platform business procedures
- Engineering governance integration with impact planning
- Platform business optimization and integration impact methodologies
- DevOps and automation impact development and business management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Business Impact Analysis Maturity Progression
**Impact Analysis Enhancement Pathway**:
1. **Foundation**: Basic impact identification and simple business documentation
2. **Development**: Systematic impact analysis with structured business management
3. **Integration**: Comprehensive impact optimization with strategic business integration
4. **Optimization**: Advanced predictive impact management with business intelligence
5. **Innovation**: Adaptive business leadership with strategic impact positioning and security

#### Impact Analysis Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Impact Analysis Enhancement**:
- Technology impact advancement and automation
- Service delivery business integration with strategic IT impact planning
- IT governance enhancement with impact business management integration
- Technology innovation integration with strategic impact positioning
- Automated impact analysis and business optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.BE-02**: Mission objectives provide context for impact analysis
- **ID.BE-03**: Dependencies and critical functions inform impact assessment
- **ID.AM-05**: Asset prioritization supports impact analysis

#### Supporting Subcategories
**Related Risk Assessment Subcategories**:
- **ID.RA-01**: Vulnerability identification coordinates with impact analysis
- **ID.RA-02**: Threat intelligence supports impact scenario development
- **ID.RA-05**: Risk determination uses business impact analysis as input
- **ID.RA-06**: Risk response planning incorporates impact analysis insights
- **RC.RP-01**: Recovery planning uses business impact analysis

### Implementation Timeline

#### Phase 1: Business Impact Analysis Foundation (Months 1-2)
**Immediate Implementation**:
- Basic impact analysis framework and business assessment mapping
- Initial impact assessment and business communication framework establishment
- Simple impact analysis and business documentation
- Basic impact communication and internal business alignment processes
- Initial impact-related risk assessment and business documentation

#### Phase 2: Business Impact Analysis Development (Months 3-6)
**Impact Analysis Enhancement**:
- Comprehensive impact analysis framework development and implementation
- Advanced business assessment and impact validation system deployment
- Cross-functional impact coordination and strategic business planning integration
- Performance measurement and impact optimization system establishment
- Strategic impact planning and business positioning development

#### Phase 3: Business Impact Analysis Optimization (Months 7-12)
**Impact Analysis Maturation**:
- Advanced impact analytics and strategic business positioning implementation
- Continuous improvement process establishment and optimization
- Strategic business leadership development and impact collaboration
- Future capability planning and adaptive impact management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.RA-04 subcategory requirements fully addressed
- [ ] Maturity-specific impact approaches included for all security ownership levels
- [ ] Business impact analysis practical and comprehensive
- [ ] Impact analysis strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Business impact analysis processes established and documented
- [ ] Impact categories defined and validated
- [ ] Financial impact assessment methods implemented
- [ ] Operational impact analysis conducted
- [ ] Stakeholder impact assessment completed
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed