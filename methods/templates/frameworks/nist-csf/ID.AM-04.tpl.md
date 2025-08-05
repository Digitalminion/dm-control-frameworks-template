<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-am-04, asset-management, supplier-services, inventory-management, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.AM-04 Supplier Services Inventory Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.AM-04 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.AM-04 (Inventories of services provided by suppliers are maintained) 
    with adaptive content that adjusts based on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of supplier services inventories with appropriate depth based on 
    organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.AM-04 documentation that maintains 
    supplier services inventories appropriate to the organization's security responsibility 
    maturity level and supply chain complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.AM-04 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.AM-04
    2. IDENTIFICATION FOCUS: Emphasize supplier services inventory maintenance
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear supplier services identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE SUPPLIER COMPLEXITY: Use maturity-specific supplier services analysis depth
    9. INCLUDE RELEVANT INVENTORY SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE TRACKING: Match inventory approach to organizational capability
    11. ADJUST SUPPLIER GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT SERVICES: Emphasize supplier services important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.AM-04:
    
    IF security_ownership == "business_led":
    - Use business language focused on vendor services and business supplier relationships
    - Emphasize supplier services based on business operations and service delivery needs
    - Include executive and operational supplier governance and business service oversight
    - Focus on compliance-driven supplier services documentation and business impact considerations
    - Provide simple supplier services frameworks appropriate to business operations management
    - Include business service delivery and operational supplier considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology supplier services and IT vendor management
    - Emphasize supplier services based on IT service delivery and infrastructure operations
    - Include IT governance and technology supplier services management and vendor administration
    - Focus on operational supplier services documentation and IT vendor considerations
    - Provide IT-centric supplier services frameworks and technology vendor analysis
    - Include technology integration and service delivery supplier considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical supplier services and development vendors
    - Emphasize supplier services based on engineering operations and platform development
    - Include engineering governance and technical supplier services management and development vendor coordination
    - Focus on technical supplier services documentation and engineering platform vendor considerations
    - Provide engineering-centric supplier services frameworks and technical vendor analysis
    - Include development workflow and platform integration supplier considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive supplier services and threat-informed vendor analysis
    - Emphasize supplier services based on security operations and threat landscape considerations
    - Include security governance and strategic supplier services management and security vendor coordination
    - Focus on threat-informed supplier services documentation and comprehensive vendor security considerations
    - Provide security-centric supplier services frameworks and advanced vendor security analysis
    - Include strategic security operations and threat landscape supplier considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for supplier relationships and service dependencies
    - Read context/stakeholders/ files for external service providers and vendor relationships
    - Use organizational maturity context to tailor supplier complexity and documentation
    - Consider supplier complexity and service criticality appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Supplier services approaches must be clearly articulated for the maturity level
    - Inventory strategies must be practical and effective
    - Vendor analysis must align with organizational capability
    - Identification outcomes must support effective supplier and service management
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.AM-04

### Subcategory Information
- **ID**: ID.AM-04
- **Function**: IDENTIFY (ID)
- **Category**: Asset Management (AM)
- **Title**: Supplier Services Inventory
- **Outcome**: Inventories of services provided by suppliers are maintained

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization maintains comprehensive and current inventories of all services provided by suppliers, enabling informed supplier risk management decisions and effective third-party service oversight.

**Strategic Value**: This subcategory establishes foundational supplier service visibility by creating and maintaining accurate supplier service inventories, enabling more effective supply chain risk management, vendor oversight, and business continuity planning decisions.

### Organizational Implementation

#### Current Supplier Services Inventory Assessment
{{#if_business_led}}
**Business-Led Supplier Services Assessment**:
- Current business vendor services and operational supplier relationship analysis
- Customer-facing supplier services and business-critical vendor service mapping
- Business application vendor services and operational supplier service identification
- Executive and operational supplier governance and business vendor service requirements
- Regulatory compliance and business supplier service documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Supplier Services Assessment**:
- Technology infrastructure and IT vendor service analysis
- Cloud service provider and technology platform supplier service mapping
- IT service delivery and infrastructure vendor service identification
- Technology integration and platform supplier service assessment and documentation
- IT infrastructure and service operation vendor service requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Supplier Services Assessment**:
- Software development and technical platform vendor service analysis
- Development tool and infrastructure supplier service mapping
- Platform and infrastructure technical vendor service identification
- Technical ecosystem and engineering supplier service integration assessment
- Engineering platform and development operation vendor service documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Supplier Services Assessment**:
- Security infrastructure and threat-informed supplier service analysis
- Advanced security vendor services and security supplier service mapping and assessment
- Security operations and incident response vendor service identification
- Comprehensive security and threat management supplier service assessment
- Strategic security operation and threat landscape vendor service documentation
{{/if_infosec_led}}

#### Framework-Specific Supplier Services Elements

**Supplier Services Inventory Framework**:
1. **Service Cataloging**: Comprehensive identification and documentation of all supplier services
2. **Supplier Classification**: Categorization of suppliers by service type, criticality, and risk level
3. **Service Dependencies**: Mapping of organizational dependencies on supplier services
4. **Contract Management**: Integration with supplier contracts and service level agreements
5. **Change Tracking**: Processes for maintaining current and accurate service inventories

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Supplier Services Documentation**:
- Document fundamental business supplier services and primary vendor relationships
- Create simple supplier service mapping and basic vendor service identification
- Identify key business supplier services and core vendor service dependencies
- Establish basic supplier service communication and business vendor documentation
- Define minimum supplier service documentation and vendor tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Supplier Services Documentation**:
- Document technology supplier services and primary IT vendor relationships
- Create simple IT supplier service mapping and technology vendor service identification
- Identify critical technology supplier services and core IT vendor service dependencies
- Establish basic IT supplier service communication and technology vendor documentation
- Define minimum IT supplier service documentation and vendor tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Supplier Services Documentation
**Risk-Based Supplier Services Enhancement**:
- Develop comprehensive supplier service analysis with risk assessment and vendor integration
- Create structured vendor service analysis across multiple supplier and service dimensions
- Implement systematic supplier service monitoring and vendor validation processes
- Establish risk-informed supplier service communication and vendor management
- Develop coordinated supplier service documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Supplier Services Management
**Systematic Supplier Services Operations**:
- Implement automated supplier service discovery and vendor tracking systems
- Establish continuous supplier service assessment and vendor evolution monitoring
- Develop advanced supplier service analytics and vendor optimization analysis
- Create standardized supplier service communication and vendor management processes
- Implement comprehensive supplier service performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Supplier Services Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Supplier Services Management**:
- Deploy predictive supplier service analytics with threat intelligence and vendor integration
- Implement real-time supplier service monitoring with adaptive vendor security strategies
- Establish dynamic supplier service assessment with strategic vendor optimization
- Develop advanced threat-informed supplier service communication and collaboration
- Create strategic vendor positioning with industry supplier security and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Supplier Services Inventory Technology Infrastructure
**Supplier Services Management Technology Context**:
- Current vendor management and supplier relationship systems
- Service catalog and supplier documentation platforms
- Contract management and vendor tracking systems
- Supplier performance monitoring and assessment tools
- Integration capabilities with procurement and vendor management systems

{{#if_engineering_led_plus}}
**Engineering-Led Supplier Services Technology**:
- **Service Discovery**: Automated platform and development vendor service analysis and mapping
- **Vendor Tracking**: Technical supplier service tracking and vendor integration analysis systems
- **Service Documentation**: Technical vendor service design and development supplier visualization
- **Communication Platforms**: Engineering team supplier service and vendor communication and collaboration
- **Analytics Systems**: Technical supplier service analysis and vendor optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Supplier Services-Based Risk Management Framework
**Risk Assessment by Supplier Services Category**:
1. **Service Availability Risk**: Critical supplier service disruption impact on business operations
2. **Vendor Dependency Risk**: Over-reliance on specific suppliers impact on business continuity
3. **Service Quality Risk**: Poor supplier service performance impact on organizational objectives
4. **Contract Risk**: Supplier service agreement compliance and performance considerations
5. **Strategic Risk**: Long-term supplier service sustainability and vendor relationship implications

{{#if_business_led}}
**Executive Supplier Services Strategy**:
- Board-level supplier service oversight and strategic vendor governance
- Executive decision-making for supplier service evolution and strategic vendor development
- Strategic planning integration with supplier service optimization and vendor positioning
- Investment decision-making with supplier service-based vendor risk assessment
- Crisis management coordination with supplier service-specific business continuity planning
{{/if_business_led}}

### Assessment and Measurement

#### Supplier Services Inventory Effectiveness Metrics
**Quantitative Measures**:
- Supplier service documentation completeness and vendor coverage assessment
- Supplier service discovery accuracy and vendor identification effectiveness measurement
- Supplier service-related incident frequency and vendor impact tracking
- Documentation update frequency and supplier service change tracking effectiveness measurement
- Supplier service optimization and vendor positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with supplier service clarity and vendor communication effectiveness
- Internal team alignment on supplier service architecture and vendor management strategy
- Supplier service documentation adaptability to changing vendor and service conditions
- Strategic supplier service development and vendor positioning advancement
- Leadership effectiveness in supplier service communication and vendor coordination

{{#if_infosec_led}}
**InfoSec-Led Supplier Services Assessment**:
- Advanced security supplier service effectiveness in threat mitigation and vendor protection
- Threat-informed supplier service positioning accuracy and strategic security vendor relevance
- Security supplier service collaboration effectiveness and threat intelligence integration
- Advanced supplier service modeling integration with threat landscape vendor analysis
- Strategic security leadership development through supplier service and vendor positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-161**: Cybersecurity Supply Chain Risk Management Practices
- **ISO 27036**: Information Security for Supplier Relationships
- **NIST SP 800-53**: Security and Privacy Controls (SA family)
- **ISO 20243**: Information Technology - Security - Open Trusted Technology Provider
- **COBIT**: Business and IT governance framework for supplier management

#### Implementation Resources
{{#if_business_led}}
**Business-Led Supplier Services Resources**:
- Business vendor service and supplier governance frameworks
- Executive supplier service oversight and business vendor strategic planning
- Compliance supplier service documentation and business vendor protection procedures
- Business supplier service planning and operational vendor methodologies
- Strategic supplier service and business vendor development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Supplier Services Resources**:
- Technical supplier service and development vendor frameworks
- Software development supplier service design and platform vendor procedures
- Engineering governance integration with supplier service planning
- Platform vendor optimization and integration supplier service methodologies
- DevOps and automation supplier service development and vendor management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Supplier Services Inventory Maturity Progression
**Supplier Services Enhancement Pathway**:
1. **Foundation**: Basic supplier service identification and simple vendor documentation
2. **Development**: Systematic supplier service analysis with structured vendor management
3. **Integration**: Comprehensive supplier service optimization with strategic vendor integration
4. **Optimization**: Advanced predictive supplier service management with vendor intelligence
5. **Innovation**: Adaptive vendor leadership with strategic supplier service positioning and security

#### Supplier Services Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Supplier Services Enhancement**:
- Technology supplier service advancement and automation
- Service delivery vendor integration with strategic IT supplier service planning
- IT governance enhancement with supplier service vendor management integration
- Technology innovation integration with strategic supplier service positioning
- Automated supplier service analysis and vendor optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.AM-01**: Hardware inventory may include supplier-managed assets
- **ID.AM-02**: Software inventory includes supplier-provided applications and services
- **ID.AM-03**: Network architecture includes supplier connectivity and services

#### Supporting Subcategories
**Related Asset Management Subcategories**:
- **ID.AM-05**: Asset prioritization aligns with supplier service criticality assessment
- **ID.AM-07**: Data inventory coordinates with supplier data processing services
- **ID.AM-08**: Lifecycle management integrates with supplier service management
- **GV.SC-01**: Supply chain program provides framework for supplier service management
- **ID.BE-01**: Supply chain role supports supplier service context

### Implementation Timeline

#### Phase 1: Supplier Services Foundation (Months 1-2)
**Immediate Implementation**:
- Basic supplier service identification and vendor mapping
- Initial service assessment and supplier communication framework establishment
- Simple supplier service analysis and vendor documentation identification
- Basic supplier service communication and internal vendor alignment processes
- Initial supplier service-related risk assessment and vendor documentation

#### Phase 2: Supplier Services Development (Months 3-6)
**Supplier Services Enhancement**:
- Comprehensive supplier service analysis framework development and implementation
- Advanced vendor assessment and supplier service validation system deployment
- Cross-functional supplier service coordination and strategic vendor planning integration
- Performance measurement and supplier service optimization system establishment
- Strategic supplier service planning and vendor positioning development

#### Phase 3: Supplier Services Optimization (Months 7-12)
**Supplier Services Maturation**:
- Advanced supplier service analytics and strategic vendor positioning implementation
- Continuous improvement process establishment and optimization
- Strategic vendor leadership development and supplier service collaboration
- Future capability planning and adaptive supplier service management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.AM-04 subcategory requirements fully addressed
- [ ] Maturity-specific supplier service identification approaches included for all security ownership levels
- [ ] Supplier service analysis practical and comprehensive
- [ ] Vendor management strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Supplier services inventories maintained and current
- [ ] Vendor relationships documented and validated
- [ ] Service dependencies identified and tracked
- [ ] Risk assessment integrated with supplier service positioning
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed