<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-am-06, asset-management, cybersecurity-roles, responsibilities, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.AM-06 Cybersecurity Roles and Responsibilities Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.AM-06 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.AM-06 (Cybersecurity roles, responsibilities, and authorities for 
    the entire workforce and third-party stakeholders are established) with adaptive content 
    that adjusts based on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of cybersecurity roles and responsibilities with appropriate depth based 
    on organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.AM-06 documentation that establishes 
    cybersecurity roles and responsibilities appropriate to the organization's security 
    responsibility maturity level and organizational complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.AM-06 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.AM-06
    2. IDENTIFICATION FOCUS: Emphasize cybersecurity roles and responsibilities establishment
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear roles and responsibilities identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE ROLE COMPLEXITY: Use maturity-specific roles and responsibilities depth
    9. INCLUDE RELEVANT ROLE SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE AUTHORITIES: Match role authorities to organizational capability
    11. ADJUST ROLE GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT RESPONSIBILITIES: Emphasize responsibilities important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.AM-06:
    
    IF security_ownership == "business_led":
    - Use business language focused on executive roles and operational responsibilities
    - Emphasize roles and responsibilities based on business operations and compliance requirements
    - Include executive and operational governance roles and business security responsibilities
    - Focus on compliance-driven role definition and business impact responsibility considerations
    - Provide simple role frameworks appropriate to business operations management
    - Include business security awareness and operational responsibility considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology roles and infrastructure responsibilities
    - Emphasize roles and responsibilities based on IT service delivery and technology operations
    - Include IT governance roles and technology security responsibilities
    - Focus on operational role definition and IT service responsibility considerations
    - Provide IT-centric role frameworks and technology responsibility analysis
    - Include technology security and infrastructure responsibility considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical roles and development responsibilities
    - Emphasize roles and responsibilities based on engineering operations and platform development
    - Include engineering governance roles and technical security responsibilities
    - Focus on technical role definition and engineering platform responsibility considerations
    - Provide engineering-centric role frameworks and technical responsibility analysis
    - Include development security and platform responsibility considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive roles and advanced security responsibilities
    - Emphasize roles and responsibilities based on security operations and threat landscape management
    - Include security governance roles and strategic security responsibilities
    - Focus on threat-informed role definition and comprehensive security responsibility considerations
    - Provide security-centric role frameworks and advanced responsibility analysis
    - Include strategic security operations and comprehensive responsibility considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for organizational structure and role definitions
    - Read context/stakeholders/ files for stakeholder roles and responsibility expectations
    - Use organizational maturity context to tailor role complexity and responsibility scope
    - Consider organizational structure complexity and role capability appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Role and responsibility approaches must be clearly articulated for the maturity level
    - Role definition strategies must be practical and effective
    - Responsibility analysis must align with organizational capability
    - Identification outcomes must support effective workforce security and accountability
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.AM-06

### Subcategory Information
- **ID**: ID.AM-06
- **Function**: IDENTIFY (ID)
- **Category**: Asset Management (AM)
- **Title**: Cybersecurity Roles and Responsibilities
- **Outcome**: Cybersecurity roles, responsibilities, and authorities for the entire workforce and third-party stakeholders are established

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization clearly defines, documents, and communicates cybersecurity roles, responsibilities, and authorities for all workforce members and third-party stakeholders, ensuring accountability and effective security governance across the entire organizational ecosystem.

**Strategic Value**: This subcategory establishes foundational security accountability by creating comprehensive role definition and responsibility assignment processes, enabling more effective security governance, clear accountability frameworks, and coordinated security efforts across all organizational levels and external partnerships.

### Organizational Implementation

#### Current Cybersecurity Roles Assessment
{{#if_business_led}}
**Business-Led Roles and Responsibilities Assessment**:
- Current business security roles and operational responsibility analysis
- Executive security accountability and business-critical role mapping
- Business security governance roles and operational responsibility identification
- Executive and operational security governance and business role requirements
- Regulatory compliance and business security role documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Roles and Responsibilities Assessment**:
- Technology security roles and IT responsibility analysis
- IT service security accountability and technology role mapping
- IT security governance roles and infrastructure responsibility identification
- Technology integration and platform security role assessment and documentation
- IT infrastructure and service operation security role requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Roles and Responsibilities Assessment**:
- Software development security roles and technical responsibility analysis
- Development security accountability and platform role mapping
- Engineering security governance roles and technical responsibility identification
- Technical ecosystem and engineering security role integration assessment
- Engineering platform and development operation security role documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Roles and Responsibilities Assessment**:
- Security infrastructure roles and comprehensive responsibility analysis
- Advanced security role accountability and strategic security role mapping and assessment
- Security operations and incident response role identification
- Comprehensive security and threat management role assessment
- Strategic security operation and threat landscape role documentation
{{/if_infosec_led}}

#### Framework-Specific Roles and Responsibilities Elements

**Cybersecurity Roles and Responsibilities Framework**:
1. **Role Definition**: Clear specification of cybersecurity roles across organizational levels
2. **Responsibility Assignment**: Detailed assignment of security responsibilities to specific roles
3. **Authority Delegation**: Appropriate security authorities aligned with responsibilities
4. **Accountability Mechanisms**: Systems for tracking and enforcing security accountability
5. **Third-Party Integration**: Extension of role framework to external stakeholders and vendors

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Roles and Responsibilities**:
- Document fundamental business security roles and primary responsibility assignments
- Create simple role mapping and basic responsibility identification
- Identify key business security roles and core responsibility determination processes
- Establish basic role communication and business responsibility documentation
- Define minimum role definition collection and business responsibility tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Roles and Responsibilities**:
- Document technology security roles and primary IT responsibility assignments
- Create simple IT role mapping and technology responsibility identification
- Identify critical technology security roles and core IT responsibility processes
- Establish basic IT role communication and technology responsibility documentation
- Define minimum IT role definition collection and technology responsibility tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Roles and Responsibilities
**Risk-Based Role and Responsibility Enhancement**:
- Develop comprehensive role analysis with risk assessment and responsibility integration
- Create structured responsibility analysis across multiple role and accountability dimensions
- Implement systematic role monitoring and responsibility validation processes
- Establish risk-informed role communication and responsibility management
- Develop coordinated role documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Roles and Responsibilities Management
**Systematic Role and Responsibility Operations**:
- Implement automated role assessment and responsibility analysis systems
- Establish continuous role monitoring and responsibility evolution tracking
- Develop advanced role analytics and responsibility optimization analysis
- Create standardized role communication and responsibility management processes
- Implement comprehensive role performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Roles and Responsibilities Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Roles and Responsibilities Management**:
- Deploy predictive role analytics with threat intelligence and responsibility integration
- Implement real-time role monitoring with adaptive responsibility strategies
- Establish dynamic role assessment with strategic responsibility optimization
- Develop advanced threat-informed role communication and collaboration
- Create strategic role positioning with industry responsibility and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Roles and Responsibilities Technology Infrastructure
**Cybersecurity Roles Management Technology Context**:
- Current identity and access management systems
- Role-based access control (RBAC) platforms
- Human resources and organizational management systems
- Training and awareness platforms
- Integration capabilities with governance and compliance tools

{{#if_engineering_led_plus}}
**Engineering-Led Roles and Responsibilities Technology**:
- **Role Management**: Automated platform and development role analysis and mapping
- **Responsibility Tracking**: Technical role tracking and responsibility integration analysis systems
- **Role Modeling**: Technical role design and development responsibility visualization
- **Communication Platforms**: Engineering team role and responsibility communication and collaboration
- **Analytics Systems**: Technical role analysis and responsibility optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Roles and Responsibilities-Based Risk Management Framework
**Risk Assessment by Role and Responsibility Category**:
1. **Role Clarity Risk**: Unclear security roles impact on security accountability and effectiveness
2. **Responsibility Gap Risk**: Unassigned security responsibilities impact on security coverage
3. **Authority Misalignment Risk**: Inadequate security authorities impact on decision-making effectiveness
4. **Accountability Risk**: Poor security accountability impact on incident response and compliance
5. **Strategic Risk**: Long-term role sustainability and responsibility evolution implications

{{#if_business_led}}
**Executive Roles and Responsibilities Strategy**:
- Board-level role oversight and strategic responsibility governance
- Executive decision-making for role evolution and strategic responsibility development
- Strategic planning integration with role optimization and responsibility positioning
- Investment decision-making with role-based risk assessment
- Crisis management coordination with role-specific incident response planning
{{/if_business_led}}

### Assessment and Measurement

#### Roles and Responsibilities Effectiveness Metrics
**Quantitative Measures**:
- Role definition coverage and responsibility assignment effectiveness
- Role clarity accuracy and responsibility understanding effectiveness measurement
- Role-related incident response and responsibility fulfillment tracking
- Role processing time and responsibility execution effectiveness measurement
- Role optimization and responsibility positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with role clarity and responsibility communication effectiveness
- Internal team alignment on roles and responsibility execution strategy
- Role adaptability to changing organizational environment and responsibility conditions
- Strategic role development and responsibility positioning advancement
- Leadership effectiveness in role communication and responsibility coordination

{{#if_infosec_led}}
**InfoSec-Led Roles and Responsibilities Assessment**:
- Advanced security role effectiveness in threat mitigation and responsibility protection
- Threat-informed role positioning accuracy and strategic security responsibility relevance
- Security role collaboration effectiveness and responsibility analysis integration
- Advanced role modeling integration with threat landscape analysis
- Strategic security leadership development through role and responsibility positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-53**: Security and Privacy Controls (AT, PS families)
- **ISO 27001**: Information Security Management Systems
- **COBIT**: Business and IT governance framework for roles and responsibilities
- **RACI Matrix**: Responsible, Accountable, Consulted, Informed framework
- **NIST NICE Framework**: National Initiative for Cybersecurity Education workforce framework

#### Implementation Resources
{{#if_business_led}}
**Business-Led Roles and Responsibilities Resources**:
- Business role definition and responsibility assessment frameworks
- Executive role oversight and business responsibility strategic planning
- Compliance role documentation and business responsibility protection procedures
- Business role planning and operational responsibility methodologies
- Strategic role and business responsibility development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Roles and Responsibilities Resources**:
- Technical role definition and development responsibility frameworks
- Software development role design and platform responsibility procedures
- Engineering governance integration with role planning
- Platform responsibility optimization and integration role methodologies
- DevOps and automation role development and responsibility management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Roles and Responsibilities Maturity Progression
**Role and Responsibility Enhancement Pathway**:
1. **Foundation**: Basic role identification and simple responsibility documentation
2. **Development**: Systematic role analysis with structured responsibility management
3. **Integration**: Comprehensive role optimization with strategic responsibility integration
4. **Optimization**: Advanced predictive role management with responsibility intelligence
5. **Innovation**: Adaptive responsibility leadership with strategic role positioning and security

#### Roles and Responsibilities Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Roles and Responsibilities Enhancement**:
- Technology role advancement and automation
- Service delivery responsibility integration with strategic IT role planning
- IT governance enhancement with role responsibility management integration
- Technology innovation integration with strategic role positioning
- Automated role analysis and responsibility optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **GV.OC-01**: Organizational cybersecurity strategy provides context for roles
- **GV.OC-02**: Internal and external stakeholders provide role stakeholder context
- **GV.OC-03**: Legal and regulatory requirements inform role compliance requirements

#### Supporting Subcategories
**Related Asset Management Subcategories**:
- **ID.AM-07**: Data inventory roles coordinate with data handling responsibilities
- **ID.AM-08**: Lifecycle management integrates with role-based asset management
- **PR.AT-01**: Awareness training supports role understanding and responsibility execution
- **PR.AT-02**: Privileged users training aligns with elevated security roles
- **GV.OV-01**: Oversight and governance coordinates with security role authority

### Implementation Timeline

#### Phase 1: Roles and Responsibilities Foundation (Months 1-2)
**Immediate Implementation**:
- Basic role definition framework and responsibility assignment mapping
- Initial role assessment and responsibility communication framework establishment
- Simple role analysis and responsibility documentation
- Basic role communication and internal responsibility alignment processes
- Initial role-related risk assessment and responsibility documentation

#### Phase 2: Roles and Responsibilities Development (Months 3-6)
**Role and Responsibility Enhancement**:
- Comprehensive role analysis framework development and implementation
- Advanced responsibility assessment and role validation system deployment
- Cross-functional role coordination and strategic responsibility planning integration
- Performance measurement and role optimization system establishment
- Strategic role planning and responsibility positioning development

#### Phase 3: Roles and Responsibilities Optimization (Months 7-12)
**Role and Responsibility Maturation**:
- Advanced role analytics and strategic responsibility positioning implementation
- Continuous improvement process establishment and optimization
- Strategic responsibility leadership development and role collaboration
- Future capability planning and adaptive role management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.AM-06 subcategory requirements fully addressed
- [ ] Maturity-specific role approaches included for all security ownership levels
- [ ] Role and responsibility analysis practical and comprehensive
- [ ] Role definition strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Cybersecurity roles clearly defined and documented
- [ ] Responsibilities assigned to appropriate roles
- [ ] Authorities delegated appropriately
- [ ] Accountability mechanisms established and operational
- [ ] Third-party roles and responsibilities documented
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed