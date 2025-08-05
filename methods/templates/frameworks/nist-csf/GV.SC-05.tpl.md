<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-gv-sc-05, supplier-requirements-agreements, supply-chain-contracts, governance-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF GV.SC-05 Supplier Requirements and Agreements Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE GV.SC-05 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF GV.SC-05 (Requirements for cybersecurity of suppliers are established, 
    prioritized, and communicated) with adaptive content that adjusts based on organizational 
    security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on governance outcomes that establish comprehensive 
    supplier cybersecurity requirements, contract terms, and communication processes with 
    appropriate complexity based on organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate GV.SC-05 documentation that establishes 
    supplier cybersecurity requirements and agreements appropriate to the organization's 
    security responsibility maturity level and contracting sophistication.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware GV.SC-05 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF GV.SC-05
    2. GOVERNANCE FOCUS: Emphasize requirement establishment and agreement communication
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving comprehensive requirement outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE REQUIREMENT COMPLEXITY: Use maturity-specific requirement depth
    9. INCLUDE RELEVANT AGREEMENT SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE STANDARDS: Match requirements to organizational capability
    11. ADJUST COMMUNICATION GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT REQUIREMENTS: Emphasize requirement areas important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR GV.SC-05:
    
    IF security_ownership == "business_led":
    - Use business contract language focused on vendor compliance and business protection
    - Emphasize supplier requirements based on business risk and regulatory compliance
    - Include executive and legal team contract management and oversight
    - Focus on compliance-driven requirements and standard contract terms
    - Provide simple requirement frameworks appropriate to business contracting
    - Include vendor management and procurement integration considerations
    
    IF security_ownership == "it_led":
    - Use IT procurement language focused on technology supplier requirements and SLAs
    - Emphasize supplier requirements based on IT service delivery and operational needs
    - Include IT governance and technology contract management
    - Focus on operational and technical requirement definition and enforcement
    - Provide IT-centric requirement frameworks and service level agreements
    - Include technology integration and support requirement considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on development and platform supplier requirements
    - Emphasize supplier requirements based on technical dependencies and system reliability
    - Include engineering governance and technical contract management
    - Focus on technical requirement definition and platform integration standards
    - Provide engineering-centric requirement frameworks and technical specifications
    - Include development workflow and platform security requirement considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on advanced threat-informed supplier requirements
    - Emphasize supplier requirements based on security risk and threat landscape
    - Include security governance and comprehensive security contract management
    - Focus on threat-informed requirement definition and security control validation
    - Provide security-centric requirement frameworks and advanced security standards
    - Include strategic security partnership and collaboration requirement considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for contracting processes and legal frameworks
    - Read context/risks/ files for security requirements and risk tolerance
    - Use organizational maturity context to tailor requirement complexity and enforceability
    - Consider legal and procurement capabilities appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Requirement frameworks must be clearly articulated for the maturity level
    - Agreement processes must be practical and legally enforceable
    - Communication approaches must align with organizational capability
    - Requirement outcomes must support effective supplier management
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: GV.SC-05

### Subcategory Information
- **ID**: GV.SC-05
- **Function**: GOVERN (GV)
- **Category**: Supply Chain Risk Management (SC)
- **Title**: Supplier Cybersecurity Requirements and Agreements
- **Outcome**: Requirements for cybersecurity of suppliers are established, prioritized, and communicated

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization establishes comprehensive cybersecurity requirements for suppliers, prioritizes them based on risk and criticality, and communicates them effectively through contracts, agreements, and ongoing supplier relationships.

**Strategic Value**: This subcategory ensures supplier cybersecurity obligations are clearly defined, legally enforceable, and proportional to risk, enabling effective supplier security management and organizational protection through contractual controls.

### Organizational Implementation

#### Current Supplier Requirements and Agreement Assessment
{{#if_business_led}}
**Business-Led Requirements Assessment**:
- Current vendor contract templates and security clause analysis
- Procurement policy and vendor requirement documentation
- Legal team contract management and enforcement capabilities
- Executive oversight and vendor compliance monitoring processes
- Regulatory compliance requirement integration with supplier contracts
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Requirements Assessment**:
- Technology supplier contract templates and service level agreement analysis
- IT procurement requirements and vendor specification documentation
- IT governance and technology contract management processes
- Technical requirement definition and vendor capability assessment
- IT service delivery and supplier performance requirement integration
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Requirements Assessment**:
- Development tool and platform supplier contract and requirement analysis
- Engineering team vendor specification and technical requirement documentation
- DevOps and automation supplier integration and security requirement assessment
- Platform reliability and performance requirement definition and enforcement
- Technical architecture and supplier integration standard documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Requirements Assessment**:
- Security vendor contract templates and advanced security requirement analysis
- Comprehensive security control and compliance requirement documentation
- Security governance and strategic supplier security agreement management
- Threat-informed requirement definition and security posture validation
- Advanced security partnership and collaboration agreement development
{{/if_infosec_led}}

#### Framework-Specific Requirement Development

**Cybersecurity Requirement Categories**:
1. **Basic Security Controls**: Fundamental security requirements for all suppliers
2. **Data Protection**: Requirements for suppliers handling organizational data
3. **Access Management**: Requirements for suppliers accessing organizational systems
4. **Incident Response**: Requirements for supplier security incident management
5. **Compliance and Audit**: Requirements for regulatory compliance and assessment

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Requirements**:
- Develop standard security clauses for vendor contracts
- Establish minimum cybersecurity requirements for key suppliers
- Create basic vendor security questionnaire and compliance certification
- Define supplier security incident notification and reporting requirements
- Implement basic contract review process with security consideration
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Requirements**:
- Develop technology supplier security requirements and technical specifications
- Establish IT service level agreements with security performance metrics
- Create technical supplier assessment criteria and compliance validation
- Define technology supplier incident response and communication requirements
- Implement IT procurement process with security requirement integration
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Requirement Development
**Risk-Based Requirement Enhancement**:
- Develop comprehensive supplier security requirement framework by criticality
- Create risk-based contract templates with tiered security requirements
- Implement structured supplier security assessment and validation processes
- Establish supplier security monitoring and reporting requirements
- Develop supplier security compliance measurement and enforcement procedures

#### Tier 3 (Repeatable) - Systematic Requirement Management
**Systematic Requirement Operations**:
- Implement automated supplier requirement management and compliance tracking
- Establish continuous supplier security requirement validation and monitoring
- Develop advanced supplier security control assessment and verification
- Create standardized supplier security agreement lifecycle management
- Implement comprehensive supplier security performance measurement and reporting

#### Tier 4 (Adaptive) - Advanced Requirement Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Requirements**:
- Deploy dynamic supplier security requirements based on threat landscape evolution
- Implement real-time supplier security compliance monitoring and automated enforcement
- Establish advanced supplier security collaboration and information sharing agreements
- Develop predictive supplier security requirement adjustment based on risk analytics
- Create strategic security partnership agreements with innovation and collaboration focus
{{/if_infosec_led}}

### Technology Implementation

#### Requirement Management Technology Infrastructure
**Supplier Agreement and Compliance Technology Context**:
- Current contract management and supplier agreement tracking systems
- Requirement definition and communication platforms
- Supplier compliance monitoring and assessment tools
- Agreement lifecycle management and renewal tracking capabilities
- Integration capabilities with procurement and legal management systems

{{#if_engineering_led_plus}}
**Engineering-Led Requirement Technology**:
- **Technical Specifications**: Automated supplier technical requirement definition and validation
- **Integration Standards**: Platform and infrastructure supplier integration requirement management
- **Compliance Tracking**: Development tool and platform supplier compliance monitoring
- **Performance Monitoring**: Supplier service performance and security requirement validation
- **Automation Tools**: Supplier requirement assessment and agreement management automation
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Requirement-Based Risk Management Framework
**Risk-Proportional Requirement Assignment**:
1. **Critical Suppliers**: Comprehensive security requirements with enhanced validation
2. **Important Suppliers**: Standard security requirements with regular assessment
3. **Standard Suppliers**: Basic security requirements with periodic validation
4. **Data Handlers**: Enhanced data protection and privacy requirements
5. **System Integrators**: Advanced access control and monitoring requirements

{{#if_business_led}}
**Executive Requirement Strategy**:
- Board-level oversight for critical supplier security agreement approval
- Executive review and approval for high-risk supplier security requirements
- Strategic planning integration with supplier security requirement development
- Legal and compliance team coordination for requirement enforceability
- Risk management integration with supplier agreement and requirement frameworks
{{/if_business_led}}

### Assessment and Measurement

#### Requirement Effectiveness Metrics
**Quantitative Measures**:
- Supplier security requirement coverage and completeness assessment
- Contract security clause implementation and enforcement rate
- Supplier security compliance measurement and validation frequency
- Security requirement violation detection and resolution effectiveness
- Agreement renewal and requirement update timeliness and accuracy

**Qualitative Measures**:
- Stakeholder satisfaction with supplier security requirement clarity and enforceability
- Legal team effectiveness in security requirement drafting and enforcement
- Supplier feedback on security requirement reasonableness and achievability
- Requirement adaptability to changing threat landscape and business needs
- Strategic supplier relationship enhancement through collaborative requirement development

{{#if_infosec_led}}
**InfoSec-Led Requirement Assessment**:
- Advanced security requirement effectiveness in threat mitigation and risk reduction
- Comprehensive security control validation and supplier security posture improvement
- Threat-informed requirement adjustment accuracy and strategic relevance
- Security collaboration and information sharing agreement effectiveness
- Strategic security partnership development through advanced requirement frameworks
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-161**: Cybersecurity Supply Chain Risk Management Practices
- **ISO 27036**: Information Security for Supplier Relationships
- **NIST SP 800-53**: Security and Privacy Controls (supply chain controls)
- **SOC 2**: Service Organization Control requirements for suppliers
- **ISO 27001**: Information Security Management System requirements

#### Implementation Resources
{{#if_business_led}}
**Business-Led Requirement Resources**:
- Vendor contract security clause templates and legal guidance
- Procurement policy integration with security requirement frameworks
- Executive oversight and vendor compliance monitoring procedures
- Legal team training and security requirement drafting guidance
- Board reporting and supplier security agreement oversight frameworks
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Requirement Resources**:
- Technical supplier requirement definition and specification frameworks
- Development tool and platform supplier security requirement templates
- Engineering governance integration with supplier agreement management
- Technical architecture and integration standard documentation
- DevOps and automation supplier security requirement guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Requirement Maturity Progression
**Requirement Enhancement Pathway**:
1. **Foundation**: Basic security clauses and minimum requirement definition
2. **Development**: Risk-based requirement frameworks with tiered approaches
3. **Integration**: Comprehensive requirement management with lifecycle integration
4. **Optimization**: Advanced adaptive requirements with threat intelligence integration
5. **Innovation**: Strategic partnership agreements with collaborative security development

#### Requirement Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Requirement Enhancement**:
- Technology supplier requirement advancement and automation
- Service level agreement integration with security requirement frameworks
- IT governance enhancement with supplier security requirement management
- Technology innovation integration with strategic supplier requirement development
- Automated compliance monitoring and requirement validation implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **GV.SC-01**: Supply chain program provides framework for requirement development
- **GV.SC-04**: Supplier prioritization informs requirement intensity and scope
- **GV.SC-02**: Roles and responsibilities establish authority for requirement definition

#### Supporting Subcategories
**Related Supply Chain Subcategories**:
- **GV.SC-06**: Due diligence validates supplier capability to meet requirements
- **GV.SC-07**: Risk management monitors supplier compliance with requirements
- **GV.SC-08**: Incident planning includes supplier notification requirements
- **GV.PO-01**: Organizational policy provides framework for supplier requirements
- **ID.GV-03**: Legal and regulatory requirements inform supplier obligations

### Implementation Timeline

#### Phase 1: Requirement Foundation (Months 1-3)
**Immediate Implementation**:
- Basic supplier security requirement definition and documentation
- Standard contract security clause development and legal review
- Initial supplier requirement communication and stakeholder training
- Basic compliance monitoring and assessment procedure establishment
- Supplier requirement integration with procurement and contracting processes

#### Phase 2: Requirement Development (Months 4-8)
**Requirement Enhancement**:
- Comprehensive requirement framework development by supplier category
- Advanced contract template creation with risk-based security requirements
- Technology platform implementation for requirement management and tracking
- Supplier training and capability development program implementation
- Performance measurement and compliance monitoring system deployment

#### Phase 3: Requirement Optimization (Months 9-12)
**Requirement Maturation**:
- Advanced requirement analytics and adaptive adjustment implementation
- Continuous improvement process establishment and optimization
- Strategic supplier partnership development with collaborative requirements
- Industry collaboration and best practice integration
- Future capability planning and innovative requirement framework development

### Quality Assurance

#### Template Validation Checklist
- [ ] GV.SC-05 subcategory requirements fully addressed
- [ ] Maturity-specific requirement approaches included for all security ownership levels
- [ ] Agreement frameworks practical and legally enforceable
- [ ] Communication processes appropriate for maturity level
- [ ] Requirement outcomes comprehensive and achievable
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Supplier security requirements defined and documented
- [ ] Contract templates developed with security clauses
- [ ] Requirement communication processes established
- [ ] Compliance monitoring systems operational
- [ ] Supplier training and capability programs implemented
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Legal and procurement integration completed