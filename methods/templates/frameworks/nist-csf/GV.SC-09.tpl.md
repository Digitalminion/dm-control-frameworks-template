<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-gv-sc-09, supply-chain-security-integration, cybersecurity-integration, governance-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF GV.SC-09 Supply Chain Security Integration Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE GV.SC-09 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF GV.SC-09 (Supply chain cybersecurity is integrated into cybersecurity 
    and enterprise risk management programs) with adaptive content that adjusts based on 
    organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on governance outcomes that ensure comprehensive 
    integration of supply chain cybersecurity with organizational cybersecurity and enterprise 
    risk management programs based on organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate GV.SC-09 documentation that establishes 
    supply chain security integration appropriate to the organization's security responsibility 
    maturity level and program integration sophistication.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware GV.SC-09 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF GV.SC-09
    2. GOVERNANCE FOCUS: Emphasize integration between supply chain and organizational security programs
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving comprehensive integration outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE INTEGRATION DEPTH: Use maturity-specific integration complexity
    9. INCLUDE RELEVANT INTEGRATION SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE COORDINATION: Match coordination processes to organizational capability
    11. ADJUST INTEGRATION GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT PROGRAMS: Emphasize integration areas important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR GV.SC-09:
    
    IF security_ownership == "business_led":
    - Use business integration language focused on vendor security and business risk coordination
    - Emphasize integration based on business risk management and compliance coordination
    - Include executive and business team security integration and oversight
    - Focus on compliance-driven integration and standard business security coordination
    - Provide simple integration frameworks appropriate to business security management
    - Include vendor security and business risk management integration considerations
    
    IF security_ownership == "it_led":
    - Use IT integration language focused on technology supplier security and IT security coordination
    - Emphasize integration based on IT security and operational risk management coordination
    - Include IT governance and technology security integration processes
    - Focus on operational and technical security integration and coordination
    - Provide IT-centric integration frameworks and technical security coordination procedures
    - Include technology security and IT risk management integration considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering integration language focused on development and platform supplier security coordination
    - Emphasize integration based on engineering security and technical risk management coordination
    - Include engineering governance and technical security integration processes
    - Focus on technical security integration and platform security coordination
    - Provide engineering-centric integration frameworks and technical security procedures
    - Include development security and platform risk management integration considerations
    
    IF security_ownership == "infosec_led":
    - Use security integration language focused on comprehensive threat-informed supply chain security coordination
    - Emphasize integration based on advanced security and comprehensive risk management coordination
    - Include security governance and strategic security integration processes
    - Focus on threat-informed integration and advanced security coordination
    - Provide security-centric integration frameworks and comprehensive security procedures
    - Include strategic security and enterprise risk management integration considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for security program structure and integration capabilities
    - Read context/risks/ files for risk management frameworks and coordination processes
    - Use organizational maturity context to tailor integration complexity and coordination depth
    - Consider security program and risk management capabilities appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Integration approaches must be clearly articulated for the maturity level
    - Coordination processes must be practical and achievable
    - Integration frameworks must align with organizational capability
    - Security outcomes must support effective program integration
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: GV.SC-09

### Subcategory Information
- **ID**: GV.SC-09
- **Function**: GOVERN (GV)
- **Category**: Supply Chain Risk Management (SC)
- **Title**: Supply Chain Security Integration
- **Outcome**: Supply chain cybersecurity is integrated into cybersecurity and enterprise risk management programs

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization fully integrates supply chain cybersecurity considerations into broader cybersecurity and enterprise risk management programs, ensuring coordinated governance, unified risk assessment, and comprehensive security management across all organizational domains.

**Strategic Value**: This subcategory ensures supply chain cybersecurity is not managed in isolation but becomes an integral component of organizational cybersecurity and risk management, enabling holistic security governance and comprehensive risk visibility.

### Organizational Implementation

#### Current Security Program Integration Assessment
{{#if_business_led}}
**Business-Led Integration Assessment**:
- Current business risk management and vendor security coordination
- Executive oversight and governance integration for supplier security
- Compliance program integration with supplier security requirements
- Strategic planning coordination with supply chain security considerations
- Board governance and risk committee integration with supplier security oversight
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Integration Assessment**:
- IT security program and technology supplier security coordination
- IT governance and service management integration with supplier security
- IT risk management and supplier security risk coordination
- Technical security control integration with supplier security management
- IT service delivery and supplier security monitoring coordination
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Integration Assessment**:
- Engineering security and development supplier security coordination
- DevOps security integration with supplier security management
- Platform security and infrastructure supplier security coordination
- Technical architecture security and supplier security integration
- Development workflow security and supplier security coordination
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Integration Assessment**:
- Comprehensive security program and advanced supplier security coordination
- Security governance and strategic supplier security integration
- Threat management and supply chain threat intelligence coordination
- Security operations and supplier security monitoring integration
- Strategic security planning and supplier security partnership coordination
{{/if_infosec_led}}

#### Framework-Specific Integration Elements

**Security Program Integration Framework**:
1. **Governance Integration**: Supply chain security governance within organizational security governance
2. **Risk Management Integration**: Supply chain risk assessment within enterprise risk management
3. **Policy Integration**: Supply chain security policies within organizational security policies
4. **Operations Integration**: Supply chain security operations within security operations centers
5. **Strategic Integration**: Supply chain security strategy within organizational cybersecurity strategy

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Integration**:
- Include supplier security considerations in business risk management processes
- Establish basic coordination between vendor management and business security oversight
- Integrate supplier security requirements with compliance and regulatory programs
- Create basic supplier security reporting within business risk reporting
- Establish basic executive oversight coordination for supplier security issues
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Integration**:
- Integrate technology supplier security with IT security management processes
- Establish coordination between IT procurement and IT security teams
- Include supplier security monitoring within IT security monitoring frameworks
- Create basic supplier security incident coordination with IT incident response
- Establish basic IT governance integration for supplier security oversight
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Integration Development
**Risk-Based Integration Enhancement**:
- Develop comprehensive integration framework between supply chain and organizational security
- Create structured coordination procedures across security and risk management domains
- Implement systematic supplier security integration with security operations
- Establish coordinated risk assessment processes across supply chain and enterprise domains
- Develop integrated security reporting and decision-making processes

#### Tier 3 (Repeatable) - Systematic Integration Management
**Systematic Integration Operations**:
- Implement automated integration between supply chain and organizational security systems
- Establish continuous coordination across all security and risk management functions
- Develop advanced integration analytics and cross-domain risk correlation
- Create standardized integration procedures with comprehensive coordination frameworks
- Implement comprehensive integration performance measurement and optimization

#### Tier 4 (Adaptive) - Advanced Integration Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Integration**:
- Deploy predictive integration analytics with threat intelligence coordination
- Implement real-time integration monitoring with automated cross-program coordination
- Establish dynamic integration with adaptive security and risk management coordination
- Develop advanced threat-informed integration with strategic security planning
- Create strategic security ecosystem integration with industry threat sharing
{{/if_infosec_led}}

### Technology Implementation

#### Integration Technology Infrastructure
**Security Program Coordination Technology Context**:
- Current cybersecurity and risk management platforms
- Supply chain security monitoring and assessment systems
- Integration and coordination platforms
- Unified dashboard and reporting capabilities
- Cross-program data sharing and analytics tools

{{#if_engineering_led_plus}}
**Engineering-Led Integration Technology**:
- **Security Integration**: Development and platform security integration with supplier security monitoring
- **Risk Coordination**: Technical risk management integration with supply chain risk assessment
- **Monitoring Systems**: Platform security monitoring integration with supplier security tracking
- **Analytics Platforms**: Technical security analytics integration with supply chain risk analytics
- **Automation Tools**: Security automation coordination with supplier security management
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Comprehensive Integration Framework
**Integrated Risk Management by Domain**:
1. **Strategic Risk**: Supply chain security integration with organizational strategic risk management
2. **Operational Risk**: Supplier security integration with operational risk management
3. **Financial Risk**: Supply chain security costs integration with financial risk management
4. **Compliance Risk**: Supplier security compliance integration with regulatory compliance management
5. **Reputational Risk**: Supply chain security incidents integration with brand risk management

{{#if_business_led}}
**Executive Integration Strategy**:
- Board-level integration oversight for supply chain and organizational security coordination
- Executive decision-making integration across security and risk management domains
- Strategic planning integration with comprehensive security and risk considerations
- Investment decision-making with integrated security and supply chain risk assessment
- Crisis management coordination across all security and risk management functions
{{/if_business_led}}

### Assessment and Measurement

#### Integration Effectiveness Metrics
**Quantitative Measures**:
- Integration coverage across security and risk management domains
- Coordination effectiveness and cross-program collaboration measurement
- Unified risk visibility and integrated decision-making frequency
- Integration system performance and data sharing effectiveness
- Cross-program optimization and resource allocation efficiency

**Qualitative Measures**:
- Stakeholder satisfaction with integrated security and risk management coordination
- Decision-maker confidence in unified security and risk visibility
- Program team collaboration effectiveness across security and risk domains
- Integration adaptability to changing security and risk landscape
- Strategic alignment enhancement through comprehensive program integration

{{#if_infosec_led}}
**InfoSec-Led Integration Assessment**:
- Advanced security integration effectiveness across organizational security domains
- Threat intelligence integration accuracy and strategic security insight generation
- Security operations coordination effectiveness with supply chain security management
- Strategic security planning integration with enterprise risk management
- Security ecosystem collaboration effectiveness with industry partners
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-161**: Cybersecurity Supply Chain Risk Management Practices
- **NIST CSF**: Core function integration across all organizational domains
- **ISO 31000**: Risk Management - Guidelines for enterprise integration
- **COSO ERM**: Enterprise Risk Management integration framework
- **NIST SP 800-39**: Managing Information Security Risk integration

#### Implementation Resources
{{#if_business_led}}
**Business-Led Integration Resources**:
- Enterprise risk management and supplier security integration frameworks
- Executive governance and security program coordination procedures
- Compliance program integration with supplier security management
- Strategic planning integration with security and risk management
- Board oversight and integrated security governance frameworks
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Integration Resources**:
- Technical security program integration with supplier security management
- DevOps security integration with supply chain security coordination
- Platform security coordination with supplier security monitoring
- Engineering governance integration with security and risk management
- Technical security automation coordination with supplier security systems
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Integration Maturity Progression
**Integration Enhancement Pathway**:
1. **Foundation**: Basic coordination between supply chain and organizational security
2. **Development**: Systematic integration with structured coordination procedures
3. **Integration**: Comprehensive program integration with unified governance
4. **Optimization**: Advanced predictive integration with threat intelligence coordination
5. **Innovation**: Adaptive ecosystem integration with industry collaboration

#### Integration Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Integration Enhancement**:
- Technology security program advancement with supplier security integration
- Automated integration development with cross-program coordination
- IT governance enhancement with comprehensive security and risk integration
- Technology innovation integration with strategic security planning
- Unified security platform development with supplier security coordination
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **GV.SC-01**: Supply chain program provides foundation for integration
- **GV.SC-03**: Enterprise risk management integration provides framework
- **GV.RM-01**: Risk management objectives establish integration context

#### Supporting Subcategories
**Related Integration Subcategories**:
- **GV.OC-01**: Organizational mission understanding supports integration alignment
- **GV.RM-03**: Risk management strategy provides integration framework
- **GV.OV-01**: Strategy outcomes review includes integrated assessment
- **All CSF Functions**: Integration spans across IDENTIFY, PROTECT, DETECT, RESPOND, RECOVER
- **GV.PO-01**: Policy framework supports integrated governance

### Implementation Timeline

#### Phase 1: Integration Foundation (Months 1-3)
**Immediate Implementation**:
- Basic integration assessment and gap analysis across security and risk domains
- Initial coordination procedures and communication framework establishment
- Stakeholder engagement and integration planning across organizational functions
- Basic integration technology platform assessment and planning
- Initial integration governance and oversight framework development

#### Phase 2: Integration Development (Months 4-8)
**Integration Enhancement**:
- Comprehensive integration framework development with systematic coordination
- Advanced integration technology platform implementation and deployment
- Cross-functional integration team training and capability development
- Performance measurement and integration optimization system implementation
- Unified governance and decision-making framework establishment

#### Phase 3: Integration Optimization (Months 9-12)
**Integration Maturation**:
- Advanced integration analytics and predictive coordination implementation
- Continuous improvement process establishment and optimization
- Strategic integration planning and ecosystem coordination development
- Industry collaboration and integration best practice sharing
- Future capability planning and adaptive integration framework development

### Quality Assurance

#### Template Validation Checklist
- [ ] GV.SC-09 subcategory requirements fully addressed
- [ ] Maturity-specific integration approaches included for all security ownership levels
- [ ] Coordination processes practical and achievable
- [ ] Integration frameworks appropriate for maturity level
- [ ] Security outcomes comprehensive and unified
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Supply chain security integration framework established and operational
- [ ] Coordination procedures implemented across security and risk domains
- [ ] Unified governance and oversight mechanisms active
- [ ] Technology integration platforms deployed and functional
- [ ] Cross-functional team coordination established and effective
- [ ] Performance measurement systems operational
- [ ] Continuous improvement processes implemented
- [ ] Strategic integration planning and optimization ongoing