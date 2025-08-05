<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-am-07, asset-management, data-inventory, data-classification, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.AM-07 Data Inventory Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.AM-07 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.AM-07 (Inventories of data and corresponding metadata are 
    maintained) with adaptive content that adjusts based on organizational security 
    responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of data inventory and metadata management with appropriate depth based 
    on organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.AM-07 documentation that maintains 
    data inventories appropriate to the organization's security responsibility maturity 
    level and data complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.AM-07 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.AM-07
    2. IDENTIFICATION FOCUS: Emphasize data inventory and metadata management
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear data inventory identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE DATA COMPLEXITY: Use maturity-specific data inventory analysis depth
    9. INCLUDE RELEVANT DATA SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE CLASSIFICATION: Match data classification to organizational capability
    11. ADJUST DATA GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT DATA: Emphasize data types important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.AM-07:
    
    IF security_ownership == "business_led":
    - Use business language focused on business data and operational information management
    - Emphasize data inventory based on business value and regulatory requirements
    - Include executive and operational data governance and business information classification
    - Focus on compliance-driven data inventory and business impact data considerations
    - Provide simple data inventory frameworks appropriate to business operations management
    - Include business data value and operational data inventory considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology data and infrastructure information management
    - Emphasize data inventory based on IT service delivery and data infrastructure operations
    - Include IT governance and technology data inventory and infrastructure data classification
    - Focus on operational data inventory and IT service data considerations
    - Provide IT-centric data inventory frameworks and technology data analysis
    - Include technology data value and infrastructure data inventory considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical data and development information management
    - Emphasize data inventory based on engineering operations and platform data development
    - Include engineering governance and technical data inventory and development data classification
    - Focus on technical data inventory and engineering platform data considerations
    - Provide engineering-centric data inventory frameworks and technical data analysis
    - Include development data value and platform data inventory considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive data and security-informed information management
    - Emphasize data inventory based on security risk and threat landscape data considerations
    - Include security governance and strategic data inventory and security data classification
    - Focus on threat-informed data inventory and comprehensive security data considerations
    - Provide security-centric data inventory frameworks and advanced data analysis
    - Include strategic security data value and comprehensive data inventory considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for business data and information assets
    - Read context/stakeholders/ files for stakeholder data expectations and privacy requirements
    - Use organizational maturity context to tailor data inventory complexity and classification
    - Consider data complexity and classification capability appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Data inventory approaches must be clearly articulated for the maturity level
    - Data classification strategies must be practical and effective
    - Data analysis must align with organizational capability
    - Identification outcomes must support effective data governance and protection
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.AM-07

### Subcategory Information
- **ID**: ID.AM-07
- **Function**: IDENTIFY (ID)
- **Category**: Asset Management (AM)
- **Title**: Data Inventory
- **Outcome**: Inventories of data and corresponding metadata are maintained

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization establishes and maintains comprehensive inventories of data assets and their corresponding metadata, including classification, location, flow, and ownership information, enabling informed data governance and protection decisions.

**Strategic Value**: This subcategory establishes foundational data awareness by creating systematic data inventory and metadata management processes, enabling more effective data governance, privacy compliance, and data-centric security strategies based on comprehensive understanding of organizational data assets.

### Organizational Implementation

#### Current Data Inventory Assessment
{{#if_business_led}}
**Business-Led Data Inventory Assessment**:
- Current business data assets and operational information analysis
- Customer and business-critical data inventory and business data value mapping
- Business application data inventory and operational data asset identification
- Executive and operational data governance and business data inventory requirements
- Regulatory compliance and business data inventory documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Data Inventory Assessment**:
- Technology infrastructure and IT data asset analysis
- Cloud service provider and technology platform data inventory mapping
- IT service delivery and infrastructure data asset identification
- Technology integration and platform data inventory assessment and documentation
- IT infrastructure and service operation data inventory requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Data Inventory Assessment**:
- Software development and technical platform data asset analysis
- Development tool and infrastructure data inventory mapping
- Platform and infrastructure technical data asset identification
- Technical ecosystem and engineering data inventory integration assessment
- Engineering platform and development operation data inventory documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Data Inventory Assessment**:
- Security infrastructure and comprehensive data asset analysis
- Advanced security data inventory and strategic data asset mapping and assessment
- Security operations and incident response data inventory identification
- Comprehensive security and threat management data asset assessment
- Strategic security operation and threat landscape data inventory documentation
{{/if_infosec_led}}

#### Framework-Specific Data Inventory Elements

**Data Inventory and Metadata Framework**:
1. **Data Classification**: Systematic categorization of data by sensitivity, type, and business value
2. **Data Location Mapping**: Comprehensive tracking of data storage locations and repositories
3. **Data Flow Documentation**: Analysis and documentation of data movement and processing
4. **Metadata Management**: Structured approach to capturing and maintaining data attributes
5. **Data Ownership Assignment**: Clear designation of data stewardship and accountability

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Data Inventory**:
- Document fundamental business data assets and primary data classification
- Create simple data inventory mapping and basic data asset identification
- Identify key business data types and core data value determination processes
- Establish basic data inventory communication and business data documentation
- Define minimum data inventory collection and business data tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Data Inventory**:
- Document technology data assets and primary IT data classification
- Create simple IT data inventory mapping and technology data asset identification
- Identify critical technology data types and core IT data value processes
- Establish basic IT data inventory communication and technology data documentation
- Define minimum IT data inventory collection and technology data tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Data Inventory
**Risk-Based Data Inventory Enhancement**:
- Develop comprehensive data inventory analysis with risk assessment and classification integration
- Create structured data analysis across multiple inventory and metadata dimensions
- Implement systematic data inventory monitoring and classification validation processes
- Establish risk-informed data inventory communication and data management
- Develop coordinated data inventory documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Data Inventory Management
**Systematic Data Inventory Operations**:
- Implement automated data inventory discovery and classification analysis systems
- Establish continuous data inventory monitoring and metadata evolution tracking
- Develop advanced data inventory analytics and classification optimization analysis
- Create standardized data inventory communication and data management processes
- Implement comprehensive data inventory performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Data Inventory Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Data Inventory Management**:
- Deploy predictive data inventory analytics with threat intelligence and classification integration
- Implement real-time data inventory monitoring with adaptive classification strategies
- Establish dynamic data inventory assessment with strategic metadata optimization
- Develop advanced threat-informed data inventory communication and collaboration
- Create strategic data positioning with industry inventory and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Data Inventory Technology Infrastructure
**Data Inventory Management Technology Context**:
- Current data governance and inventory management platforms
- Data discovery and classification tools
- Data loss prevention (DLP) and monitoring systems
- Database and data warehouse management systems
- Integration capabilities with data governance and compliance tools

{{#if_engineering_led_plus}}
**Engineering-Led Data Inventory Technology**:
- **Data Discovery**: Automated platform and development data inventory analysis and mapping
- **Classification Systems**: Technical data inventory tracking and metadata integration analysis systems
- **Data Modeling**: Technical data inventory design and development metadata visualization
- **Communication Platforms**: Engineering team data inventory and metadata communication and collaboration
- **Analytics Systems**: Technical data inventory analysis and classification optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Data Inventory-Based Risk Management Framework
**Risk Assessment by Data Inventory Category**:
1. **Data Loss Risk**: Critical data asset loss impact on business operations and compliance
2. **Classification Risk**: Inadequate data classification impact on protection effectiveness
3. **Inventory Gap Risk**: Unknown data assets impact on governance and security coverage
4. **Metadata Risk**: Poor metadata quality impact on data management and discovery
5. **Strategic Risk**: Long-term data inventory capability sustainability and evolution implications

{{#if_business_led}}
**Executive Data Inventory Strategy**:
- Board-level data inventory oversight and strategic data governance
- Executive decision-making for data inventory evolution and strategic data development
- Strategic planning integration with data inventory optimization and data positioning
- Investment decision-making with data inventory-based risk assessment
- Crisis management coordination with data inventory-specific incident response planning
{{/if_business_led}}

### Assessment and Measurement

#### Data Inventory Effectiveness Metrics
**Quantitative Measures**:
- Data inventory coverage and classification completeness assessment
- Data inventory accuracy and metadata quality effectiveness measurement
- Data inventory-related incident impact and protection effectiveness tracking
- Inventory processing time and data discovery effectiveness measurement
- Data inventory optimization and classification positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with data inventory clarity and metadata communication effectiveness
- Internal team alignment on data inventory and data management strategy
- Data inventory adaptability to changing business environment and data conditions
- Strategic data inventory development and metadata positioning advancement
- Leadership effectiveness in data inventory communication and data coordination

{{#if_infosec_led}}
**InfoSec-Led Data Inventory Assessment**:
- Advanced security data inventory effectiveness in threat mitigation and data protection
- Threat-informed data inventory positioning accuracy and strategic security data relevance
- Security data inventory collaboration effectiveness and metadata analysis integration
- Advanced data inventory modeling integration with threat landscape analysis
- Strategic security leadership development through data inventory positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST Privacy Framework**: Privacy risk management framework
- **ISO 27001**: Information Security Management Systems
- **GDPR**: General Data Protection Regulation
- **CCPA**: California Consumer Privacy Act
- **NIST SP 800-53**: Security and Privacy Controls (SC family)

#### Implementation Resources
{{#if_business_led}}
**Business-Led Data Inventory Resources**:
- Business data inventory and governance assessment frameworks
- Executive data inventory oversight and business data strategic planning
- Compliance data inventory documentation and business data protection procedures
- Business data inventory planning and operational data methodologies
- Strategic data inventory and business data development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Data Inventory Resources**:
- Technical data inventory and development data frameworks
- Software development data inventory design and platform data procedures
- Engineering governance integration with data inventory planning
- Platform data optimization and integration data inventory methodologies
- DevOps and automation data inventory development and data management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Data Inventory Maturity Progression
**Data Inventory Enhancement Pathway**:
1. **Foundation**: Basic data inventory identification and simple metadata documentation
2. **Development**: Systematic data inventory analysis with structured metadata management
3. **Integration**: Comprehensive data inventory optimization with strategic metadata integration
4. **Optimization**: Advanced predictive data inventory management with metadata intelligence
5. **Innovation**: Adaptive data leadership with strategic data inventory positioning and security

#### Data Inventory Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Data Inventory Enhancement**:
- Technology data inventory advancement and automation
- Service delivery data integration with strategic IT data inventory planning
- IT governance enhancement with data inventory metadata management integration
- Technology innovation integration with strategic data inventory positioning
- Automated data inventory analysis and metadata optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.AM-01**: Hardware inventory may contain data storage assets
- **ID.AM-02**: Software inventory includes data processing applications
- **ID.AM-05**: Asset prioritization supports data criticality assessment

#### Supporting Subcategories
**Related Asset Management Subcategories**:
- **ID.AM-06**: Cybersecurity roles include data stewardship responsibilities
- **ID.AM-08**: Lifecycle management integrates with data lifecycle management
- **PR.DS-01**: Data-at-rest protection relies on data inventory
- **PR.DS-02**: Data-in-transit protection uses data flow information
- **PR.DS-05**: Data leak protection depends on data classification

### Implementation Timeline

#### Phase 1: Data Inventory Foundation (Months 1-2)
**Immediate Implementation**:
- Basic data inventory framework and classification mapping
- Initial data assessment and inventory communication framework establishment
- Simple data inventory analysis and metadata documentation
- Basic data inventory communication and internal data alignment processes
- Initial data inventory-related risk assessment and data documentation

#### Phase 2: Data Inventory Development (Months 3-6)
**Data Inventory Enhancement**:
- Comprehensive data inventory analysis framework development and implementation
- Advanced data classification assessment and inventory validation system deployment
- Cross-functional data inventory coordination and strategic data planning integration
- Performance measurement and data inventory optimization system establishment
- Strategic data inventory planning and metadata positioning development

#### Phase 3: Data Inventory Optimization (Months 7-12)
**Data Inventory Maturation**:
- Advanced data inventory analytics and strategic metadata positioning implementation
- Continuous improvement process establishment and optimization
- Strategic data leadership development and inventory collaboration
- Future capability planning and adaptive data inventory management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.AM-07 subcategory requirements fully addressed
- [ ] Maturity-specific data inventory approaches included for all security ownership levels
- [ ] Data inventory analysis practical and comprehensive
- [ ] Data classification strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Data inventories established and maintained
- [ ] Data classification system implemented and operational
- [ ] Metadata management processes developed and validated
- [ ] Data location tracking established
- [ ] Data ownership assigned and documented
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed