<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-gv-sc-02, supply-chain-roles-responsibilities, governance-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF GV.SC-02 Supply Chain Roles and Responsibilities Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE GV.SC-02 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF GV.SC-02 (Roles and responsibilities for cybersecurity supply chain risk 
    management are established and agreed to by organizational stakeholders) with adaptive content 
    that adjusts based on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on governance outcomes that establish clear roles and 
    responsibilities for supply chain cybersecurity risk management with appropriate organizational 
    structure and accountability based on maturity levels.
    
    TEMPLATE USAGE: Use this template to generate GV.SC-02 documentation that defines supply chain 
    cybersecurity roles and responsibilities appropriate to the organization's security responsibility 
    maturity level and organizational structure.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware GV.SC-02 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF GV.SC-02
    2. GOVERNANCE FOCUS: Emphasize role definition and responsibility assignment for supply chain
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear role and responsibility outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE ROLE STRUCTURE: Use maturity-specific role definitions and hierarchy
    9. INCLUDE RELEVANT RESPONSIBILITY SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE ACCOUNTABILITY: Match accountability structure to organizational capability
    11. ADJUST ROLE GUIDANCE: Provide role guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT RESPONSIBILITIES: Emphasize role areas important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR GV.SC-02:
    
    IF security_ownership == "business_led":
    - Use business executive language focused on procurement and vendor management roles
    - Emphasize executive and board oversight responsibilities for supplier management
    - Include clear delegation structure and vendor relationship ownership
    - Focus on compliance and contract management role definitions
    - Provide simple role definition frameworks appropriate to business structure
    - Include vendor and consultant coordination responsibilities
    
    IF security_ownership == "it_led":
    - Use IT management language focused on technology procurement and supplier integration
    - Emphasize IT leadership and technical team responsibilities for supplier management
    - Include IT service management and technical oversight role definitions
    - Focus on operational and technical supplier management responsibilities
    - Provide IT-centric role frameworks and responsibility matrices
    - Include technical integration and support role definitions
    
    IF security_ownership == "engineering_led":
    - Use engineering and DevOps language focused on development and infrastructure supplier roles
    - Emphasize engineering team and platform responsibilities for supplier integration
    - Include development team and infrastructure management role definitions
    - Focus on technical dependency and automation supplier responsibilities
    - Provide engineering-centric role frameworks and development team integration
    - Include DevOps and platform engineering role definitions
    
    IF security_ownership == "infosec_led":
    - Use security professional language focused on advanced supplier security oversight
    - Emphasize security team and specialist responsibilities for supplier risk management
    - Include security governance and threat assessment role definitions
    - Focus on threat-informed supplier security and incident response responsibilities
    - Provide security-centric role frameworks and specialist responsibility matrices
    - Include advanced security governance and strategic security planning roles
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for organizational structure and role definitions
    - Read context/stakeholders/ files for stakeholder roles and accountability structures
    - Use organizational maturity context to tailor role complexity and authority structure
    - Consider business hierarchy and decision-making authority appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Role definitions must be clearly articulated for the maturity level
    - Responsibility assignments must be practical and enforceable
    - Accountability structures must be appropriate to organizational capability
    - Role integration must align with existing organizational structure
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: GV.SC-02

### Subcategory Information
- **ID**: GV.SC-02
- **Function**: GOVERN (GV)
- **Category**: Supply Chain Risk Management (SC)
- **Title**: Supply Chain Cybersecurity Roles and Responsibilities
- **Outcome**: Roles and responsibilities for cybersecurity supply chain risk management are established and agreed to by organizational stakeholders

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization establishes clear roles and responsibilities for cybersecurity supply chain risk management with defined accountability structures and stakeholder agreement on authority and decision-making.

**Strategic Value**: This subcategory ensures organizational clarity and accountability for supply chain cybersecurity management by defining who is responsible for specific activities, decisions, and outcomes across the supplier lifecycle and risk management processes.

### Organizational Implementation

#### Current Role and Responsibility Context Assessment
{{#if_business_led}}
**Business-Led Role Assessment**:
- Executive and board-level supplier oversight responsibilities
- Procurement team vendor management and contract administration roles
- Legal and compliance team supplier agreement and regulatory oversight
- Business unit supplier relationship and performance management
- Finance team supplier payment and financial risk management
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Role Assessment**:
- IT leadership technology supplier strategy and governance oversight
- IT procurement team technology vendor selection and management
- System administrators supplier technical integration and support
- IT security team supplier security assessment and monitoring
- IT service management team supplier performance and service delivery
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Role Assessment**:
- Engineering leadership platform and infrastructure supplier strategy
- Development teams software dependency and library management
- DevOps teams CI/CD and automation supplier integration
- Platform teams infrastructure and service supplier management
- Architecture teams supplier technical evaluation and integration
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Role Assessment**:
- CISO and security leadership strategic supplier security governance
- Security analysts supplier threat assessment and risk monitoring
- Security architects supplier security design and validation
- Incident response teams supplier security incident coordination
- GRC teams supplier compliance and regulatory requirement management
{{/if_infosec_led}}

#### Framework-Specific Role Definition

**Core Supply Chain Cybersecurity Roles**:
1. **Strategic Oversight**: Executive-level supplier risk strategy and governance
2. **Operational Management**: Day-to-day supplier relationship and performance management
3. **Technical Assessment**: Supplier security and technical capability evaluation
4. **Risk Monitoring**: Ongoing supplier risk assessment and threat monitoring
5. **Incident Response**: Supplier-related security incident management and coordination

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Role Structure**:
- Executive sponsor for key supplier relationships and strategic decisions
- Procurement lead for vendor selection and contract management
- Legal advisor for supplier agreements and compliance requirements
- Financial controller for supplier payment and budget management
- Designated point of contact for each critical supplier relationship
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Role Structure**:
- IT manager for technology supplier oversight and strategic direction
- IT procurement specialist for vendor evaluation and contract management
- System administrator for supplier technical integration and support
- IT security contact for supplier security assessment and monitoring
- Service desk coordinator for supplier-related incident management
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Role Development
**Risk-Based Role Enhancement**:
- Supply chain risk manager for comprehensive supplier risk oversight
- Supplier relationship managers for key vendor strategic partnerships
- Technical evaluation teams for supplier security and capability assessment
- Cross-functional supplier review board for decision-making and governance
- Supplier performance monitoring team for ongoing assessment and reporting

#### Tier 3 (Repeatable) - Systematic Role Management
**Systematic Role Operations**:
- Dedicated supply chain security team with specialized expertise
- Supplier lifecycle management team for end-to-end vendor management
- Technical due diligence team for advanced supplier evaluation
- Supplier risk monitoring center for continuous assessment and alerting
- Cross-enterprise supplier governance committee for strategic coordination

#### Tier 4 (Adaptive) - Advanced Role Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Role Structure**:
- Supply chain threat intelligence team for advanced threat analysis
- Supplier security assessment specialists for deep technical evaluation
- Supply chain incident response team for coordinated threat response
- Strategic supplier partnership team for innovation and collaboration
- Predictive supplier risk analytics team for advanced risk modeling
{{/if_infosec_led}}

### Technology Implementation

#### Role-Supporting Technology Infrastructure
**Role Definition and Management Systems**:
- Role and responsibility matrix documentation and tracking systems
- Supplier contact management and escalation workflow platforms
- Responsibility assignment and accountability monitoring tools
- Cross-functional collaboration and communication platforms
- Role-based access control for supplier management systems

{{#if_engineering_led_plus}}
**Engineering-Led Role Technology Support**:
- Developer team supplier dependency tracking and management tools
- DevOps team automated supplier integration and monitoring systems
- Platform team supplier service integration and performance monitoring
- Architecture team supplier evaluation and documentation platforms
- Engineering leadership supplier strategic planning and roadmap tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Role-Based Risk Management Framework
**Risk Responsibility Assignment**:
1. **Strategic Risk**: Executive leadership supplier strategy and governance oversight
2. **Operational Risk**: Management teams supplier performance and service delivery
3. **Technical Risk**: Technical teams supplier security and integration assessment
4. **Compliance Risk**: Legal and compliance teams regulatory and contractual compliance
5. **Financial Risk**: Finance teams supplier financial stability and payment risk

{{#if_business_led}}
**Executive Risk Communication Structure**:
- Board-level supplier risk reporting and governance accountability
- Executive team supplier strategic decision-making and oversight
- Management team supplier operational risk monitoring and reporting
- Cross-functional supplier risk escalation and decision-making processes
- Stakeholder supplier risk communication and transparency requirements
{{/if_business_led}}

### Assessment and Measurement

#### Role Effectiveness Metrics
**Quantitative Measures**:
- Role definition completeness and documentation accuracy
- Responsibility assignment clarity and stakeholder understanding
- Decision-making timeliness and authority effectiveness
- Escalation process efficiency and resolution speed
- Cross-functional collaboration effectiveness and communication quality

**Qualitative Measures**:
- Stakeholder satisfaction with role clarity and responsibility definition
- Team effectiveness in supplier management and oversight activities
- Authority alignment with organizational structure and decision-making
- Role integration effectiveness with existing business processes
- Adaptability of role structure to changing supplier landscape

{{#if_infosec_led}}
**InfoSec-Led Assessment Approach**:
- Security team supplier risk management effectiveness assessment
- Threat response coordination efficiency and cross-team collaboration
- Security governance integration with business and technical teams
- Specialist role effectiveness in advanced threat assessment and monitoring
- Strategic security planning integration with supplier management
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-161**: Cybersecurity Supply Chain Risk Management Practices
- **ISO 27001**: Information Security Management Systems (organizational roles)
- **COBIT**: Governance framework for roles and responsibilities
- **RACI Matrix**: Responsibility assignment matrix methodology
- **NIST CSF**: Related subcategories GV.RR-01, GV.RR-02

#### Implementation Resources
{{#if_business_led}}
**Business-Led Implementation Resources**:
- Executive governance and board oversight frameworks
- Procurement team role definition and responsibility matrices
- Legal and compliance team supplier agreement oversight guidance
- Cross-functional supplier governance committee structures
- Executive reporting and accountability frameworks
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Implementation Resources**:
- Development team supplier dependency management role definitions
- DevOps team automation and integration responsibility frameworks
- Platform team infrastructure supplier management role matrices
- Architecture team technical evaluation and oversight responsibilities
- Engineering leadership strategic supplier planning frameworks
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Role Maturity Progression
**Role Enhancement Pathway**:
1. **Foundation**: Basic role assignment with clear accountability
2. **Development**: Specialized roles with defined expertise areas
3. **Integration**: Cross-functional teams with coordinated responsibilities
4. **Optimization**: Advanced specialist roles with strategic integration
5. **Innovation**: Adaptive role structure with emerging threat response

#### Role Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Role Enhancement**:
- Technology team role specialization and expertise development
- Cross-functional IT and business team integration and collaboration
- Technical supplier management capability advancement and training
- IT governance integration with enterprise supplier management
- Technology innovation team supplier evaluation and partnership development
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **GV.SC-01**: Supply chain program provides framework for role definition
- **GV.RR-01**: Organizational leadership establishes authority for role assignment
- **GV.RR-02**: General roles and responsibilities provide organizational context

#### Supporting Subcategories
**Related Supply Chain Subcategories**:
- **GV.SC-03**: Risk management integration requires role coordination
- **GV.SC-04**: Supplier prioritization requires assessment role definition
- **GV.SC-05**: Requirements and agreements require contract management roles
- **ID.AM-01**: Asset management roles include supplier-managed assets
- **RS.CO-02**: Internal communication requires role-based coordination

### Implementation Timeline

#### Phase 1: Role Foundation (Months 1-2)
**Immediate Implementation**:
- Core role identification and initial responsibility assignment
- Key stakeholder engagement and role acceptance
- Basic documentation and communication of role structure
- Initial training and orientation for assigned roles
- Basic escalation and communication procedures establishment

#### Phase 2: Role Development (Months 3-6)
**Role Enhancement**:
- Detailed role definition and responsibility matrix development
- Cross-functional coordination and integration procedures
- Advanced training and capability development programs
- Role-supporting technology and process implementation
- Performance measurement and feedback mechanism establishment

#### Phase 3: Role Optimization (Months 7-12)
**Role Maturation**:
- Advanced specialist role development and integration
- Continuous improvement and role effectiveness optimization
- Strategic role planning and future capability development
- Industry collaboration and best practice integration
- Role adaptability and emerging threat response capability

### Quality Assurance

#### Template Validation Checklist
- [ ] GV.SC-02 subcategory requirements fully addressed
- [ ] Maturity-specific role definitions included for all security ownership levels
- [ ] Role assignments practical and enforceable
- [ ] Accountability structures appropriate for maturity level
- [ ] Integration with organizational structure comprehensive
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Core supply chain roles identified and defined
- [ ] Responsibility matrices developed and documented
- [ ] Role assignments communicated and accepted
- [ ] Authority structures established and recognized
- [ ] Training and development programs implemented
- [ ] Performance measurement systems operational
- [ ] Continuous improvement processes active
- [ ] Cross-functional coordination mechanisms established