<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-am-08, asset-management, lifecycle-management, asset-disposal, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.AM-08 Asset Lifecycle Management Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.AM-08 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.AM-08 (Systems, hardware, software, services, and systems documentation 
    are managed throughout removal, transfers, and disposition) with adaptive content that adjusts 
    based on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of asset lifecycle management with appropriate depth based on organizational 
    maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.AM-08 documentation that manages asset 
    lifecycle appropriate to the organization's security responsibility maturity level and 
    asset complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.AM-08 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.AM-08
    2. IDENTIFICATION FOCUS: Emphasize asset lifecycle management throughout removal, transfers, and disposition
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear asset lifecycle identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE LIFECYCLE COMPLEXITY: Use maturity-specific asset lifecycle analysis depth
    9. INCLUDE RELEVANT LIFECYCLE SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE DISPOSAL: Match disposal processes to organizational capability
    11. ADJUST LIFECYCLE GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT LIFECYCLE: Emphasize lifecycle aspects important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.AM-08:
    
    IF security_ownership == "business_led":
    - Use business language focused on business asset lifecycle and operational disposal management
    - Emphasize lifecycle management based on business value and regulatory disposal requirements
    - Include executive and operational lifecycle governance and business asset disposal
    - Focus on compliance-driven lifecycle management and business impact disposal considerations
    - Provide simple lifecycle frameworks appropriate to business operations management
    - Include business asset value and operational lifecycle management considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology lifecycle and infrastructure disposal management
    - Emphasize lifecycle management based on IT service delivery and technology disposal operations
    - Include IT governance and technology lifecycle management and infrastructure asset disposal
    - Focus on operational lifecycle management and IT service disposal considerations
    - Provide IT-centric lifecycle frameworks and technology disposal analysis
    - Include technology asset value and infrastructure lifecycle management considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical lifecycle and development disposal management
    - Emphasize lifecycle management based on engineering operations and platform disposal development
    - Include engineering governance and technical lifecycle management and development asset disposal
    - Focus on technical lifecycle management and engineering platform disposal considerations
    - Provide engineering-centric lifecycle frameworks and technical disposal analysis
    - Include development asset value and platform lifecycle management considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive lifecycle and security-informed disposal management
    - Emphasize lifecycle management based on security risk and threat landscape disposal considerations
    - Include security governance and strategic lifecycle management and security asset disposal
    - Focus on threat-informed lifecycle management and comprehensive security disposal considerations
    - Provide security-centric lifecycle frameworks and advanced disposal analysis
    - Include strategic security asset value and comprehensive lifecycle management considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for asset lifecycle policies and disposal procedures
    - Read context/stakeholders/ files for stakeholder disposal expectations and compliance requirements
    - Use organizational maturity context to tailor lifecycle complexity and disposal processes
    - Consider asset complexity and disposal capability appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Lifecycle management approaches must be clearly articulated for the maturity level
    - Disposal strategies must be practical and effective
    - Lifecycle analysis must align with organizational capability
    - Identification outcomes must support effective asset management and secure disposal
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.AM-08

### Subcategory Information
- **ID**: ID.AM-08
- **Function**: IDENTIFY (ID)
- **Category**: Asset Management (AM)
- **Title**: Asset Lifecycle Management
- **Outcome**: Systems, hardware, software, services, and systems documentation are managed throughout removal, transfers, and disposition

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization establishes and maintains comprehensive processes to securely manage all organizational assets throughout their complete lifecycle, including systematic procedures for removal, transfers, and disposition that protect sensitive information and maintain security posture.

**Strategic Value**: This subcategory establishes foundational asset lifecycle security by creating systematic asset management and secure disposal processes, enabling more effective asset governance, data protection during transitions, and risk mitigation strategies throughout the complete asset lifecycle from acquisition to disposal.

### Organizational Implementation

#### Current Asset Lifecycle Assessment
{{#if_business_led}}
**Business-Led Asset Lifecycle Assessment**:
- Current business asset lifecycle and operational disposal analysis
- Customer-facing asset lifecycle and business-critical asset disposal mapping
- Business application asset lifecycle and operational asset disposal identification
- Executive and operational asset lifecycle governance and business disposal requirements
- Regulatory compliance and business asset lifecycle documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Asset Lifecycle Assessment**:
- Technology infrastructure and IT asset lifecycle analysis
- Cloud service provider and technology platform asset lifecycle mapping
- IT service delivery and infrastructure asset lifecycle identification
- Technology integration and platform asset lifecycle assessment and documentation
- IT infrastructure and service operation asset lifecycle requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Asset Lifecycle Assessment**:
- Software development and technical platform asset lifecycle analysis
- Development tool and infrastructure asset lifecycle mapping
- Platform and infrastructure technical asset lifecycle identification
- Technical ecosystem and engineering asset lifecycle integration assessment
- Engineering platform and development operation asset lifecycle documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Asset Lifecycle Assessment**:
- Security infrastructure and comprehensive asset lifecycle analysis
- Advanced security asset lifecycle and strategic asset disposal mapping and assessment
- Security operations and incident response asset lifecycle identification
- Comprehensive security and threat management asset lifecycle assessment
- Strategic security operation and threat landscape asset lifecycle documentation
{{/if_infosec_led}}

#### Framework-Specific Asset Lifecycle Elements

**Asset Lifecycle Management Framework**:
1. **Lifecycle Planning**: Comprehensive planning for asset acquisition, deployment, and retirement
2. **Transfer Procedures**: Secure processes for asset transfers between organizational units
3. **Removal Protocols**: Systematic procedures for asset decommissioning and removal
4. **Disposition Security**: Secure disposal methods that protect sensitive information
5. **Documentation Management**: Maintenance of asset documentation throughout lifecycle phases

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Asset Lifecycle**:
- Document fundamental business asset lifecycle and primary disposal procedures
- Create simple lifecycle mapping and basic asset disposal identification
- Identify key business lifecycle processes and core disposal determination procedures
- Establish basic lifecycle communication and business disposal documentation
- Define minimum lifecycle collection and business asset tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Asset Lifecycle**:
- Document technology asset lifecycle and primary IT disposal procedures
- Create simple IT lifecycle mapping and technology asset disposal identification
- Identify critical technology lifecycle processes and core IT disposal procedures
- Establish basic IT lifecycle communication and technology disposal documentation
- Define minimum IT lifecycle collection and technology asset tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Asset Lifecycle
**Risk-Based Asset Lifecycle Enhancement**:
- Develop comprehensive lifecycle analysis with risk assessment and disposal integration
- Create structured disposal analysis across multiple lifecycle and security dimensions
- Implement systematic lifecycle monitoring and disposal validation processes
- Establish risk-informed lifecycle communication and asset management
- Develop coordinated lifecycle documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Asset Lifecycle Management
**Systematic Asset Lifecycle Operations**:
- Implement automated lifecycle assessment and disposal analysis systems
- Establish continuous lifecycle monitoring and disposal evolution tracking
- Develop advanced lifecycle analytics and disposal optimization analysis
- Create standardized lifecycle communication and asset management processes
- Implement comprehensive lifecycle performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Asset Lifecycle Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Asset Lifecycle Management**:
- Deploy predictive lifecycle analytics with threat intelligence and disposal integration
- Implement real-time lifecycle monitoring with adaptive disposal strategies
- Establish dynamic lifecycle assessment with strategic disposal optimization
- Develop advanced threat-informed lifecycle communication and collaboration
- Create strategic asset positioning with industry lifecycle and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Asset Lifecycle Technology Infrastructure
**Asset Lifecycle Management Technology Context**:
- Current asset management and tracking systems
- Secure disposal and data sanitization tools
- Asset transfer and deployment automation platforms
- Configuration management and documentation systems
- Integration capabilities with enterprise asset management and security tools

{{#if_engineering_led_plus}}
**Engineering-Led Asset Lifecycle Technology**:
- **Lifecycle Automation**: Automated platform and development lifecycle analysis and mapping
- **Disposal Systems**: Technical lifecycle tracking and disposal integration analysis systems
- **Transfer Management**: Technical lifecycle design and development disposal visualization
- **Communication Platforms**: Engineering team lifecycle and disposal communication and collaboration
- **Analytics Systems**: Technical lifecycle analysis and disposal optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Asset Lifecycle-Based Risk Management Framework
**Risk Assessment by Asset Lifecycle Category**:
1. **Data Breach Risk**: Inadequate disposal procedures impact on data protection and compliance
2. **Asset Loss Risk**: Poor transfer procedures impact on asset security and accountability
3. **Compliance Risk**: Insufficient lifecycle documentation impact on regulatory compliance
4. **Operational Risk**: Inadequate removal procedures impact on business continuity
5. **Strategic Risk**: Long-term lifecycle capability sustainability and evolution implications

{{#if_business_led}}
**Executive Asset Lifecycle Strategy**:
- Board-level lifecycle oversight and strategic disposal governance
- Executive decision-making for lifecycle evolution and strategic disposal development
- Strategic planning integration with lifecycle optimization and disposal positioning
- Investment decision-making with lifecycle-based risk assessment
- Crisis management coordination with lifecycle-specific incident response planning
{{/if_business_led}}

### Assessment and Measurement

#### Asset Lifecycle Effectiveness Metrics
**Quantitative Measures**:
- Lifecycle process coverage and disposal completeness assessment
- Lifecycle procedure accuracy and disposal effectiveness measurement
- Lifecycle-related incident impact and security effectiveness tracking
- Disposal processing time and asset transition effectiveness measurement
- Lifecycle optimization and disposal positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with lifecycle clarity and disposal communication effectiveness
- Internal team alignment on lifecycle and asset management strategy
- Lifecycle adaptability to changing business environment and disposal conditions
- Strategic lifecycle development and disposal positioning advancement
- Leadership effectiveness in lifecycle communication and disposal coordination

{{#if_infosec_led}}
**InfoSec-Led Asset Lifecycle Assessment**:
- Advanced security lifecycle effectiveness in threat mitigation and asset protection
- Threat-informed lifecycle positioning accuracy and strategic security disposal relevance
- Security lifecycle collaboration effectiveness and disposal analysis integration
- Advanced lifecycle modeling integration with threat landscape analysis
- Strategic security leadership development through lifecycle positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-88**: Guidelines for Media Sanitization
- **ISO 27001**: Information Security Management Systems
- **NIST SP 800-53**: Security and Privacy Controls (MP family)
- **DoD 5220.22-M**: National Industrial Security Program Operating Manual
- **COBIT**: Business and IT governance framework for asset management

#### Implementation Resources
{{#if_business_led}}
**Business-Led Asset Lifecycle Resources**:
- Business lifecycle and disposal assessment frameworks
- Executive lifecycle oversight and business disposal strategic planning
- Compliance lifecycle documentation and business disposal protection procedures
- Business lifecycle planning and operational disposal methodologies
- Strategic lifecycle and business disposal development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Asset Lifecycle Resources**:
- Technical lifecycle and development disposal frameworks
- Software development lifecycle design and platform disposal procedures
- Engineering governance integration with lifecycle planning
- Platform disposal optimization and integration lifecycle methodologies
- DevOps and automation lifecycle development and disposal management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Asset Lifecycle Maturity Progression
**Asset Lifecycle Enhancement Pathway**:
1. **Foundation**: Basic lifecycle identification and simple disposal documentation
2. **Development**: Systematic lifecycle analysis with structured disposal management
3. **Integration**: Comprehensive lifecycle optimization with strategic disposal integration
4. **Optimization**: Advanced predictive lifecycle management with disposal intelligence
5. **Innovation**: Adaptive disposal leadership with strategic lifecycle positioning and security

#### Asset Lifecycle Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Asset Lifecycle Enhancement**:
- Technology lifecycle advancement and automation
- Service delivery disposal integration with strategic IT lifecycle planning
- IT governance enhancement with lifecycle disposal management integration
- Technology innovation integration with strategic lifecycle positioning
- Automated lifecycle analysis and disposal optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.AM-01**: Hardware inventory supports lifecycle tracking
- **ID.AM-02**: Software inventory includes lifecycle management
- **ID.AM-07**: Data inventory requires secure lifecycle disposal

#### Supporting Subcategories
**Related Asset Management Subcategories**:
- **ID.AM-05**: Asset prioritization influences lifecycle management decisions
- **ID.AM-06**: Cybersecurity roles include lifecycle responsibilities
- **PR.DS-03**: Data disposal protections align with asset lifecycle
- **PR.IP-06**: Data destruction aligns with asset disposal procedures
- **GV.SC-04**: Supplier lifecycle coordinates with asset lifecycle management

### Implementation Timeline

#### Phase 1: Asset Lifecycle Foundation (Months 1-2)
**Immediate Implementation**:
- Basic lifecycle framework and disposal procedure mapping
- Initial lifecycle assessment and disposal communication framework establishment
- Simple lifecycle analysis and disposal documentation
- Basic lifecycle communication and internal disposal alignment processes
- Initial lifecycle-related risk assessment and disposal documentation

#### Phase 2: Asset Lifecycle Development (Months 3-6)
**Asset Lifecycle Enhancement**:
- Comprehensive lifecycle analysis framework development and implementation
- Advanced disposal assessment and lifecycle validation system deployment
- Cross-functional lifecycle coordination and strategic disposal planning integration
- Performance measurement and lifecycle optimization system establishment
- Strategic lifecycle planning and disposal positioning development

#### Phase 3: Asset Lifecycle Optimization (Months 7-12)
**Asset Lifecycle Maturation**:
- Advanced lifecycle analytics and strategic disposal positioning implementation
- Continuous improvement process establishment and optimization
- Strategic disposal leadership development and lifecycle collaboration
- Future capability planning and adaptive lifecycle management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.AM-08 subcategory requirements fully addressed
- [ ] Maturity-specific lifecycle approaches included for all security ownership levels
- [ ] Asset lifecycle analysis practical and comprehensive
- [ ] Disposal strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Asset lifecycle processes established and documented
- [ ] Secure disposal procedures implemented and operational
- [ ] Transfer protocols developed and validated
- [ ] Removal procedures established and tested
- [ ] Documentation management systems deployed
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed