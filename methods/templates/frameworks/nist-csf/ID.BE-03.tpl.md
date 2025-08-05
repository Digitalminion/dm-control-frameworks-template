<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-be-03, business-environment, dependencies, critical-functions, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.BE-03 Dependencies and Critical Functions Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.BE-03 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.BE-03 (Dependencies and critical functions for delivery of critical 
    services are established) with adaptive content that adjusts based on organizational security 
    responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of organizational dependencies and critical functions with appropriate 
    depth based on organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.BE-03 documentation that identifies 
    dependencies and critical functions appropriate to the organization's security 
    responsibility maturity level and operational complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.BE-03 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.BE-03
    2. IDENTIFICATION FOCUS: Emphasize dependencies and critical functions establishment
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear dependencies and functions identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE DEPENDENCY COMPLEXITY: Use maturity-specific dependency and function analysis depth
    9. INCLUDE RELEVANT FUNCTION SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE ANALYSIS: Match analysis approach to organizational capability
    11. ADJUST DEPENDENCY GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT FUNCTIONS: Emphasize critical functions important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.BE-03:
    
    IF security_ownership == "business_led":
    - Use business language focused on business process dependencies and operational functions
    - Emphasize critical functions based on business operations and customer service delivery
    - Include executive and operational dependency identification and business function analysis
    - Focus on compliance-driven dependency identification and business function prioritization
    - Provide simple dependency mapping frameworks appropriate to business operations management
    - Include customer service and business continuity dependency considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology dependencies and service delivery functions
    - Emphasize critical functions based on IT service delivery and infrastructure operations
    - Include IT governance and technology dependency identification and service function analysis
    - Focus on operational dependency identification and IT service function prioritization
    - Provide IT-centric dependency frameworks and technology function analysis
    - Include technology integration and service delivery dependency considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical dependencies and development functions
    - Emphasize critical functions based on engineering operations and platform delivery
    - Include engineering governance and technical dependency identification and development function analysis
    - Focus on technical dependency identification and engineering function prioritization
    - Provide engineering-centric dependency frameworks and technical function analysis
    - Include development workflow and platform integration dependency considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive dependency and threat-informed function analysis
    - Emphasize critical functions based on security operations and threat mitigation
    - Include security governance and strategic dependency identification and security function analysis
    - Focus on threat-informed dependency identification and comprehensive function prioritization
    - Provide security-centric dependency frameworks and advanced function analysis
    - Include strategic security operations and threat landscape dependency considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for operational processes and dependencies
    - Read context/stakeholders/ files for external dependencies and service relationships
    - Use organizational maturity context to tailor dependency complexity and analysis
    - Consider operational complexity and dependency criticality appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Dependency identification approaches must be clearly articulated for the maturity level
    - Analysis strategies must be practical and effective
    - Function analysis must align with organizational capability
    - Identification outcomes must support effective operational management
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.BE-03

### Subcategory Information
- **ID**: ID.BE-03
- **Function**: IDENTIFY (ID)
- **Category**: Business Environment (BE)
- **Title**: Dependencies and Critical Functions
- **Outcome**: Dependencies and critical functions for delivery of critical services are established

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization clearly identifies and documents dependencies and critical functions necessary for the delivery of critical services, enabling informed risk management decisions and operational continuity planning.

**Strategic Value**: This subcategory establishes foundational operational awareness by identifying critical dependencies and functions that support service delivery, enabling more effective risk assessment, business continuity planning, and cybersecurity resource allocation decisions.

### Organizational Implementation

#### Current Dependencies and Functions Assessment
{{#if_business_led}}
**Business-Led Dependencies Assessment**:
- Current business process and operational workflow dependency analysis
- Customer service delivery and business function dependency mapping
- Vendor and supplier relationship dependency identification and impact assessment
- Business continuity critical function identification and prioritization
- Revenue generation and business operation dependency documentation
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Dependencies Assessment**:
- Technology infrastructure and IT service dependency analysis
- Cloud service provider and technology vendor dependency mapping
- IT service delivery and platform function dependency identification
- Technology integration critical function identification and prioritization
- IT infrastructure and service operation dependency documentation
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Dependencies Assessment**:
- Software development and technical platform dependency analysis
- Development tool and infrastructure dependency mapping and integration
- Platform and infrastructure service function dependency identification
- Technical ecosystem critical function identification and prioritization
- Engineering platform and development operation dependency documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Dependencies Assessment**:
- Security infrastructure and threat mitigation dependency analysis
- Advanced security service and control dependency mapping and assessment
- Security operations and incident response function dependency identification
- Comprehensive security critical function identification and prioritization
- Strategic security operation and threat management dependency documentation
{{/if_infosec_led}}

#### Framework-Specific Dependencies and Functions Elements

**Dependencies and Critical Functions Framework**:
1. **Dependency Mapping**: Comprehensive identification of internal and external dependencies
2. **Function Criticality**: Assessment and prioritization of critical business functions
3. **Impact Analysis**: Understanding of dependency failure and function disruption impacts
4. **Relationship Management**: Structured approach to dependency and function relationship management
5. **Continuity Planning**: Integration with business continuity and disaster recovery planning

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Dependencies Establishment**:
- Document fundamental business process dependencies and primary service functions
- Create simple dependency mapping and basic critical function identification
- Identify key vendor relationships and core business operation dependencies
- Establish basic dependency communication and business function documentation
- Define minimum critical function documentation and dependency tracking
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Dependencies Establishment**:
- Document technology service dependencies and primary IT function identification
- Create simple IT dependency mapping and service delivery function identification
- Identify critical technology vendors and core IT operation dependencies
- Establish basic IT dependency communication and service function documentation
- Define minimum IT function documentation and technology dependency tracking
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Dependencies Development
**Risk-Based Dependencies Enhancement**:
- Develop comprehensive dependency analysis with risk assessment integration
- Create structured function criticality analysis across multiple operational dimensions
- Implement systematic dependency monitoring and function validation processes
- Establish risk-informed dependencies communication and function management
- Develop coordinated dependencies documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Dependencies Management
**Systematic Dependencies Operations**:
- Implement automated dependency monitoring and function performance tracking systems
- Establish continuous dependencies assessment and function criticality evolution tracking
- Develop advanced dependencies analytics and function optimization analysis
- Create standardized dependencies communication and function management processes
- Implement comprehensive dependencies performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Dependencies Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Dependencies Management**:
- Deploy predictive dependencies analytics with threat intelligence integration
- Implement real-time dependency monitoring with adaptive function strategies
- Establish dynamic dependencies assessment with strategic function optimization
- Develop advanced threat-informed dependencies communication and collaboration
- Create strategic function positioning with industry resilience and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Dependencies Management Technology Infrastructure
**Dependencies and Functions Management Technology Context**:
- Current business process management and operational monitoring platforms
- Dependency mapping and relationship management systems
- Critical function monitoring and performance tracking tools
- Business continuity planning and disaster recovery systems
- Integration capabilities with enterprise systems and external dependencies

{{#if_engineering_led_plus}}
**Engineering-Led Dependencies Technology**:
- **Dependency Mapping**: Automated software and infrastructure dependency analysis and visualization
- **Function Monitoring**: Platform and service critical function tracking and analysis
- **Dependencies Analysis**: Technical dependency positioning and development workflow optimization
- **Communication Platforms**: Engineering team dependencies and function communication and collaboration
- **Analytics Systems**: Technical dependencies analysis and function optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Dependencies-Based Risk Management Framework
**Risk Assessment by Dependencies Category**:
1. **Dependency Failure Risk**: Critical dependency failure impact on service delivery
2. **Function Disruption Risk**: Critical function disruption impact on operations
3. **Cascade Risk**: Dependency failure cascade effect on multiple functions
4. **Recovery Risk**: Dependencies-related recovery time and function restoration considerations
5. **Strategic Risk**: Long-term dependency sustainability and function evolution implications

{{#if_business_led}}
**Executive Dependencies Strategy**:
- Board-level critical dependencies oversight and strategic function governance
- Executive decision-making for dependency evolution and strategic function development
- Strategic planning integration with dependencies optimization and function positioning
- Investment decision-making with dependencies-based function risk assessment
- Crisis management coordination with dependencies-specific business continuity planning
{{/if_business_led}}

### Assessment and Measurement

#### Dependencies Establishment Effectiveness Metrics
**Quantitative Measures**:
- Dependencies documentation completeness and critical function identification assessment
- Dependency monitoring and function performance tracking effectiveness measurement
- Dependencies-related incident frequency and function disruption impact tracking
- Function restoration time and dependency recovery effectiveness measurement
- Dependencies optimization and function positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with dependencies clarity and function communication effectiveness
- Internal team alignment on critical dependencies and function management strategy
- Dependencies adaptability to changing operational environment and function conditions
- Strategic dependencies development and function positioning advancement
- Leadership effectiveness in dependencies communication and function coordination

{{#if_infosec_led}}
**InfoSec-Led Dependencies Assessment**:
- Advanced security dependencies effectiveness in threat mitigation and function protection
- Threat-informed dependencies positioning accuracy and strategic security function relevance
- Security dependencies collaboration effectiveness and threat intelligence integration
- Advanced dependencies modeling integration with threat landscape function analysis
- Strategic security leadership development through dependencies and function positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **ISO 22301**: Business Continuity Management Systems
- **NIST SP 800-34**: Contingency Planning Guide for Federal Information Systems
- **COBIT**: Business and IT governance framework for dependency management
- **ITIL**: IT Service Management for service dependency analysis
- **Business Impact Analysis (BIA)**: Critical function and dependency assessment methodology

#### Implementation Resources
{{#if_business_led}}
**Business-Led Dependencies Resources**:
- Business process mapping and dependency analysis frameworks
- Vendor and supplier relationship management and communication procedures
- Executive governance and critical function strategic planning
- Business continuity planning and dependency management methodologies
- Strategic dependencies and business function development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Dependencies Resources**:
- Technical dependencies and development function frameworks
- Software development dependency and platform management procedures
- Engineering governance integration with dependency function planning
- Platform architecture and integration dependency optimization methodologies
- DevOps and automation dependency function development and management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Dependencies Maturity Progression
**Dependencies Enhancement Pathway**:
1. **Foundation**: Basic dependency identification and simple function documentation
2. **Development**: Systematic dependency analysis with structured function management
3. **Integration**: Comprehensive dependency optimization with strategic function integration
4. **Optimization**: Advanced predictive dependency management with function intelligence
5. **Innovation**: Adaptive function leadership with strategic positioning and resilience

#### Dependencies Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Dependencies Enhancement**:
- Technology dependency advancement and automation
- Service delivery function integration with strategic IT planning
- IT governance enhancement with dependency function management integration
- Technology innovation integration with strategic dependency positioning
- Automated dependency analysis and function optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.BE-02**: Mission objectives provide context for critical function identification
- **ID.AM-01**: Asset inventory supports dependency and function analysis
- **GV.OC-01**: Organizational mission establishes foundation for critical functions

#### Supporting Subcategories
**Related Business Environment Subcategories**:
- **ID.BE-04**: Resilience requirements align with critical function protection
- **ID.BE-05**: Mission context supports dependency and function analysis
- **ID.AM-04**: Supplier inventory coordinates with external dependency management
- **GV.SC-01**: Supply chain program provides framework for external dependency management
- **RC.RP-01**: Recovery planning integrates with critical function restoration

### Implementation Timeline

#### Phase 1: Dependencies Foundation (Months 1-2)
**Immediate Implementation**:
- Basic dependency identification and critical function mapping
- Initial function priority assessment and dependency communication framework establishment
- Simple dependency analysis and function performance identification
- Basic dependency communication and internal function alignment processes
- Initial dependency-related risk assessment and function documentation

#### Phase 2: Dependencies Development (Months 3-6)
**Dependencies Enhancement**:
- Comprehensive dependency analysis framework development and implementation
- Advanced function criticality assessment and dependency validation system deployment
- Cross-functional dependency coordination and strategic function planning integration
- Performance measurement and dependency optimization system establishment
- Strategic dependency planning and function positioning development

#### Phase 3: Dependencies Optimization (Months 7-12)
**Dependencies Maturation**:
- Advanced dependency analytics and strategic function positioning implementation
- Continuous improvement process establishment and optimization
- Strategic function leadership development and dependency collaboration
- Future capability planning and adaptive dependency management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.BE-03 subcategory requirements fully addressed
- [ ] Maturity-specific dependency identification approaches included for all security ownership levels
- [ ] Dependencies analysis practical and comprehensive
- [ ] Function analysis strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Dependencies identified and documented
- [ ] Critical functions established and prioritized
- [ ] Dependencies analysis completed and validated
- [ ] Risk assessment integrated with dependency positioning
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed