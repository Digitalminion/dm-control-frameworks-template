<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-gv-sc-04, supplier-prioritization, supply-chain-criticality, governance-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF GV.SC-04 Supplier Prioritization Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE GV.SC-04 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF GV.SC-04 (Suppliers are known and prioritized by criticality) with 
    adaptive content that adjusts based on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on governance outcomes that establish supplier 
    identification, categorization, and prioritization based on criticality to organizational 
    operations and security posture with appropriate depth based on maturity levels.
    
    TEMPLATE USAGE: Use this template to generate GV.SC-04 documentation that prioritizes 
    suppliers based on criticality appropriate to the organization's security responsibility 
    maturity level and supply chain complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware GV.SC-04 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF GV.SC-04
    2. GOVERNANCE FOCUS: Emphasize supplier identification and criticality-based prioritization
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving supplier prioritization outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE PRIORITIZATION COMPLEXITY: Use maturity-specific prioritization depth
    9. INCLUDE RELEVANT ASSESSMENT SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE CRITERIA: Match prioritization criteria to organizational capability
    11. ADJUST PRIORITIZATION GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT FACTORS: Emphasize prioritization factors important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR GV.SC-04:
    
    IF security_ownership == "business_led":
    - Use business language focused on vendor criticality and business impact assessment
    - Emphasize supplier prioritization based on business continuity and financial impact
    - Include executive and board-level supplier classification and oversight
    - Focus on compliance and contractual criticality assessment
    - Provide simple supplier categorization frameworks appropriate to business operations
    - Include vendor relationship management and strategic partnership considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology supplier criticality and operational impact
    - Emphasize supplier prioritization based on IT service delivery and system dependencies
    - Include IT governance and technology supplier classification
    - Focus on operational and technical criticality assessment
    - Provide IT-centric supplier categorization and dependency analysis
    - Include technology service level and performance impact considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on development and platform supplier criticality
    - Emphasize supplier prioritization based on architectural dependencies and system reliability
    - Include engineering governance and technical supplier classification
    - Focus on technical dependency and platform criticality assessment
    - Provide engineering-centric supplier categorization and dependency mapping
    - Include development workflow and platform integration impact considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on advanced threat-informed supplier criticality assessment
    - Emphasize supplier prioritization based on security risk and threat landscape
    - Include security governance and threat-based supplier classification
    - Focus on threat-informed criticality assessment and security impact analysis
    - Provide security-centric supplier categorization and threat modeling
    - Include advanced security assessment and strategic security partnership considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for supplier inventory and business dependencies
    - Read context/risks/ files for supplier risk assessment and criticality factors
    - Use organizational maturity context to tailor prioritization complexity and criteria
    - Consider business operations and supplier relationship scope appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Prioritization approaches must be clearly articulated for the maturity level
    - Criticality assessment must be practical and achievable
    - Supplier categorization must align with organizational capability
    - Prioritization outcomes must support effective supplier management
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: GV.SC-04

### Subcategory Information
- **ID**: GV.SC-04
- **Function**: GOVERN (GV)
- **Category**: Supply Chain Risk Management (SC)
- **Title**: Supplier Prioritization by Criticality
- **Outcome**: Suppliers are known and prioritized by criticality

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization maintains comprehensive knowledge of all suppliers and prioritizes them based on criticality to organizational operations, security posture, and business objectives, enabling risk-proportional management approaches.

**Strategic Value**: This subcategory enables efficient allocation of resources and focused risk management efforts by establishing clear supplier hierarchies based on business impact, operational dependencies, and security considerations.

### Organizational Implementation

#### Current Supplier Knowledge and Prioritization Assessment
{{#if_business_led}}
**Business-Led Supplier Assessment**:
- Current vendor inventory and relationship documentation
- Business continuity and operational dependency mapping
- Financial impact and contract value analysis
- Strategic partnership and vendor relationship categorization
- Regulatory and compliance requirement supplier assessment
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Supplier Assessment**:
- Technology supplier inventory and service dependency mapping
- IT service delivery and operational impact analysis
- Cloud service provider and SaaS application categorization
- Infrastructure and platform supplier criticality assessment
- Technology integration and architectural dependency evaluation
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Supplier Assessment**:
- Development tool and platform supplier dependency mapping
- Software supply chain and library dependency analysis
- Infrastructure-as-code and automation supplier evaluation
- CI/CD pipeline and development workflow supplier assessment
- Platform reliability and performance supplier impact analysis
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Supplier Assessment**:
- Security vendor and service provider strategic assessment
- Threat landscape and supplier security posture evaluation
- Security control and technology supplier criticality analysis
- Third-party security service and capability assessment
- Supply chain threat modeling and risk-based prioritization
{{/if_infosec_led}}

#### Framework-Specific Prioritization Analysis

**Supplier Criticality Assessment Framework**:
1. **Business Impact**: Effect of supplier disruption on organizational operations
2. **Security Risk**: Supplier access to sensitive data and critical systems
3. **Operational Dependency**: Reliance on supplier services for daily operations
4. **Financial Exposure**: Contract value and financial dependency on supplier
5. **Regulatory Compliance**: Supplier role in meeting compliance requirements

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Prioritization**:
- Create simple supplier inventory with basic categorization (Critical, Important, Standard)
- Identify key suppliers based on contract value and business dependency
- Document critical suppliers for business continuity planning
- Establish basic supplier contact information and relationship management
- Define minimum security requirements for critical supplier categories
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Prioritization**:
- Develop technology supplier inventory with service level categorization
- Identify critical technology suppliers based on service dependency
- Document infrastructure and platform supplier dependencies
- Establish IT supplier contact information and escalation procedures
- Define basic security requirements for technology supplier categories
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Prioritization Development
**Risk-Based Prioritization Enhancement**:
- Develop comprehensive supplier criticality assessment methodology
- Create multi-dimensional supplier categorization framework
- Implement structured supplier risk assessment and scoring system
- Establish supplier prioritization based on risk and business impact
- Develop supplier monitoring and review procedures based on criticality

#### Tier 3 (Repeatable) - Systematic Prioritization Management
**Systematic Prioritization Operations**:
- Implement automated supplier classification and prioritization systems
- Establish continuous supplier criticality monitoring and reassessment
- Develop advanced supplier dependency mapping and impact analysis
- Create standardized supplier lifecycle management based on criticality
- Implement comprehensive supplier performance monitoring by priority level

#### Tier 4 (Adaptive) - Advanced Prioritization Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Prioritization**:
- Deploy dynamic supplier risk-based prioritization with threat intelligence integration
- Implement real-time supplier criticality assessment with automated adjustment
- Establish predictive supplier impact modeling and scenario analysis
- Develop adaptive supplier management strategies based on evolving threat landscape
- Create strategic supplier partnership programs with security-focused prioritization
{{/if_infosec_led}}

### Technology Implementation

#### Supplier Management Technology Infrastructure
**Supplier Tracking and Prioritization Technology Context**:
- Current supplier relationship management and vendor tracking systems
- Business impact assessment and dependency mapping tools
- Risk assessment and scoring platforms
- Supplier performance monitoring and analytics capabilities
- Integration capabilities with procurement and contract management systems

{{#if_engineering_led_plus}}
**Engineering-Led Prioritization Technology**:
- **Dependency Analysis**: Automated software and infrastructure dependency mapping
- **Impact Assessment**: Platform and service reliability impact analysis tools
- **Monitoring Systems**: Supplier service performance and availability monitoring
- **Risk Analytics**: Technical dependency risk assessment and scoring platforms
- **Integration Tools**: Supplier assessment integration with development workflows
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Criticality-Based Risk Management Framework
**Risk Prioritization by Supplier Category**:
1. **Critical Suppliers**: High-impact, high-dependency suppliers requiring intensive management
2. **Important Suppliers**: Moderate-impact suppliers requiring regular oversight
3. **Standard Suppliers**: Low-impact suppliers requiring basic management
4. **Strategic Partners**: High-value suppliers requiring collaborative management
5. **Emerging Suppliers**: New suppliers requiring enhanced due diligence

{{#if_business_led}}
**Executive Prioritization Strategy**:
- Board-level oversight for critical and strategic supplier relationships
- Executive approval requirements for critical supplier changes and decisions
- Strategic planning integration with critical supplier assessment and management
- Investment decision-making with supplier criticality consideration
- Crisis management coordination with critical supplier incident response
{{/if_business_led}}

### Assessment and Measurement

#### Prioritization Effectiveness Metrics
**Quantitative Measures**:
- Supplier inventory completeness and accuracy assessment
- Criticality assessment coverage and update frequency
- Prioritization-based resource allocation efficiency measurement
- Supplier incident impact correlation with criticality classification
- Management effort allocation alignment with supplier priority levels

**Qualitative Measures**:
- Stakeholder satisfaction with supplier prioritization accuracy and usefulness
- Decision-maker confidence in supplier criticality assessments
- Supplier management effectiveness by priority category
- Prioritization adaptability to changing business needs and threat landscape
- Resource allocation optimization through effective supplier prioritization

{{#if_infosec_led}}
**InfoSec-Led Prioritization Assessment**:
- Threat-informed supplier criticality assessment accuracy and relevance
- Security risk correlation with supplier prioritization effectiveness
- Advanced threat modeling integration with supplier classification
- Predictive risk analytics accuracy for supplier priority adjustment
- Strategic security partnership development based on criticality assessment
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-161**: Cybersecurity Supply Chain Risk Management Practices
- **ISO 27036**: Information Security for Supplier Relationships
- **ISO 31000**: Risk Management - Guidelines for risk assessment
- **NIST SP 800-39**: Managing Information Security Risk
- **Business Continuity Institute**: Supply Chain Resilience Guidelines

#### Implementation Resources
{{#if_business_led}}
**Business-Led Prioritization Resources**:
- Vendor management and supplier categorization frameworks
- Business impact assessment and dependency mapping methodologies
- Executive supplier governance and oversight procedures
- Strategic supplier relationship management frameworks
- Board reporting and supplier risk communication templates
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Prioritization Resources**:
- Technical dependency mapping and analysis tools
- Software supply chain assessment and prioritization methodologies
- Platform and infrastructure supplier evaluation frameworks
- Development workflow integration and supplier management procedures
- Engineering governance and supplier oversight frameworks
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Prioritization Maturity Progression
**Prioritization Enhancement Pathway**:
1. **Foundation**: Basic supplier inventory and simple categorization
2. **Development**: Risk-based supplier assessment and prioritization
3. **Integration**: Comprehensive supplier management based on criticality
4. **Optimization**: Advanced predictive supplier criticality assessment
5. **Innovation**: Adaptive supplier prioritization with real-time adjustment

#### Prioritization Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Prioritization Enhancement**:
- Technology supplier categorization advancement and automation
- Automated dependency analysis and criticality assessment development
- IT governance integration with supplier prioritization enhancement
- Service delivery impact analysis and supplier management optimization
- Technology innovation integration with strategic supplier planning
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **GV.SC-01**: Supply chain program provides framework for supplier management
- **GV.SC-02**: Roles and responsibilities establish authority for supplier prioritization
- **ID.AM-01**: Asset management includes supplier-managed assets

#### Supporting Subcategories
**Related Supply Chain Subcategories**:
- **GV.SC-05**: Requirements and agreements vary by supplier priority
- **GV.SC-06**: Due diligence intensity based on supplier criticality
- **GV.SC-07**: Risk management approach varies by supplier priority
- **ID.BE-03**: Suppliers and dependencies identification
- **GV.RM-02**: Risk appetite informs supplier prioritization criteria

### Implementation Timeline

#### Phase 1: Prioritization Foundation (Months 1-2)
**Immediate Implementation**:
- Comprehensive supplier inventory development and documentation
- Basic criticality assessment criteria definition and application
- Initial supplier categorization and priority assignment
- Stakeholder communication of supplier prioritization approach
- Basic supplier management procedures based on priority levels

#### Phase 2: Prioritization Development (Months 3-6)
**Prioritization Enhancement**:
- Advanced criticality assessment methodology development and implementation
- Comprehensive supplier risk assessment and scoring system deployment
- Technology platform implementation for supplier tracking and management
- Stakeholder training on supplier prioritization and management procedures
- Performance measurement and feedback mechanism establishment

#### Phase 3: Prioritization Optimization (Months 7-12)
**Prioritization Maturation**:
- Advanced supplier analytics and predictive assessment implementation
- Continuous improvement process establishment and optimization
- Strategic supplier partnership development based on criticality
- Industry collaboration and best practice integration
- Future capability planning and adaptive prioritization development

### Quality Assurance

#### Template Validation Checklist
- [ ] GV.SC-04 subcategory requirements fully addressed
- [ ] Maturity-specific prioritization approaches included for all security ownership levels
- [ ] Criticality assessment practical and achievable
- [ ] Supplier categorization appropriate for maturity level
- [ ] Resource allocation guidance comprehensive
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Comprehensive supplier inventory completed and maintained
- [ ] Criticality assessment criteria defined and applied
- [ ] Supplier prioritization framework implemented
- [ ] Management procedures established based on priority levels
- [ ] Technology systems deployed for supplier tracking
- [ ] Performance measurement systems operational
- [ ] Continuous improvement processes active
- [ ] Stakeholder communication and training completed