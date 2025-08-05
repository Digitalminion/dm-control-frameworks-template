<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-gv-sc-03, supply-chain-risk-integration, enterprise-risk-management, governance-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF GV.SC-03 Supply Chain ERM Integration Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE GV.SC-03 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF GV.SC-03 (Cybersecurity supply chain risk management is integrated with 
    the organization's enterprise risk management process and supports risk-informed decision making) 
    with adaptive content that adjusts based on organizational security responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on governance outcomes that integrate supply chain 
    cybersecurity risk management with broader enterprise risk management processes, ensuring 
    coordinated and informed decision-making across organizational risk domains.
    
    TEMPLATE USAGE: Use this template to generate GV.SC-03 documentation that integrates supply 
    chain cybersecurity risks with enterprise risk management appropriate to the organization's 
    security responsibility maturity level and risk management sophistication.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware GV.SC-03 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF GV.SC-03
    2. GOVERNANCE FOCUS: Emphasize integration between supply chain and enterprise risk management
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving integrated risk management outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE INTEGRATION DEPTH: Use maturity-specific integration complexity
    9. INCLUDE RELEVANT INTEGRATION SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE RISK FRAMEWORKS: Match frameworks to organizational capability
    11. ADJUST INTEGRATION GUIDANCE: Provide integration guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT PROCESSES: Emphasize integration areas important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR GV.SC-03:
    
    IF security_ownership == "business_led":
    - Use business risk language focused on vendor risk integration with business risk management
    - Emphasize supply chain risk integration with financial and operational risk reporting
    - Include board and executive risk committee integration and oversight
    - Focus on business impact and financial risk assessment integration
    - Provide simple risk integration frameworks appropriate to business risk management
    - Include vendor risk reporting integration with business risk dashboards
    
    IF security_ownership == "it_led":
    - Use IT risk language focused on technology supplier risk integration with IT risk management
    - Emphasize supply chain risk integration with IT operational and service delivery risk
    - Include IT governance and service management risk framework integration
    - Focus on operational and technical risk assessment integration
    - Provide IT-centric risk integration with service management frameworks
    - Include technology risk reporting integration with IT governance structures
    
    IF security_ownership == "engineering_led":
    - Use engineering risk language focused on development and platform supplier risk integration
    - Emphasize supply chain risk integration with technical and architectural risk management
    - Include engineering risk assessment and dependency risk framework integration
    - Focus on technical dependency and platform risk assessment integration
    - Provide engineering-centric risk integration with development and platform management
    - Include technical risk reporting integration with engineering governance structures
    
    IF security_ownership == "infosec_led":
    - Use security risk language focused on advanced threat-informed supply chain risk integration
    - Emphasize supply chain risk integration with comprehensive security risk management
    - Include security governance and threat assessment framework integration
    - Focus on threat-informed risk assessment and strategic security risk integration
    - Provide security-centric risk integration with comprehensive risk management frameworks
    - Include advanced risk analytics integration with strategic risk planning
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for enterprise risk management processes and frameworks
    - Read context/risks/ files for current risk assessment and management approaches
    - Use organizational maturity context to tailor integration complexity and sophistication
    - Consider existing risk management tools and processes appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Integration approaches must be clearly articulated for the maturity level
    - Risk management coordination must be practical and achievable
    - Framework integration must align with existing organizational processes
    - Decision-making support must be appropriate to organizational capability
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: GV.SC-03

### Subcategory Information
- **ID**: GV.SC-03
- **Function**: GOVERN (GV)
- **Category**: Supply Chain Risk Management (SC)
- **Title**: Supply Chain Risk Integration with Enterprise Risk Management
- **Outcome**: Cybersecurity supply chain risk management is integrated with the organization's enterprise risk management process and supports risk-informed decision making

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization integrates cybersecurity supply chain risk management with enterprise risk management processes to enable coordinated risk assessment, holistic risk visibility, and informed strategic decision-making across all organizational risk domains.

**Strategic Value**: This subcategory ensures supply chain cybersecurity risks are considered within the broader organizational risk context, enabling comprehensive risk-informed decision making and strategic alignment between cybersecurity investments and overall business risk management objectives.

### Organizational Implementation

#### Current Risk Integration Context Assessment
{{#if_business_led}}
**Business-Led Risk Integration Assessment**:
- Current enterprise risk management framework and board oversight structure
- Vendor risk integration with financial and operational risk reporting
- Business risk committee and executive risk governance processes
- Insurance and financial risk management integration with supplier risks
- Strategic planning and business continuity integration with supplier dependencies
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Risk Integration Assessment**:
- IT risk management framework and service delivery risk processes
- Technology supplier risk integration with IT operational risk management
- IT governance and service management risk assessment integration
- Business continuity and disaster recovery integration with supplier risks
- Technology risk reporting integration with enterprise risk dashboards
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Risk Integration Assessment**:
- Engineering risk management and technical debt assessment processes
- Development and platform supplier risk integration with architectural risks
- DevOps and automation risk assessment integration with supplier dependencies
- Technical dependency risk integration with platform and infrastructure risks
- Engineering governance integration with enterprise risk management frameworks
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Risk Integration Assessment**:
- Comprehensive security risk management framework and threat assessment integration
- Advanced supply chain threat modeling integration with enterprise security risks
- Security governance integration with enterprise risk management committees
- Threat intelligence integration with strategic risk planning and decision-making
- Security risk analytics integration with enterprise risk monitoring and reporting
{{/if_infosec_led}}

#### Framework-Specific Integration Analysis

**Enterprise Risk Management Integration Elements**:
1. **Risk Framework Alignment**: Alignment between supply chain and enterprise risk methodologies
2. **Risk Reporting Integration**: Consolidated risk reporting and dashboard integration
3. **Decision-Making Coordination**: Integrated risk-informed decision-making processes
4. **Risk Assessment Harmonization**: Consistent risk criteria and assessment approaches
5. **Strategic Planning Integration**: Supply chain risk consideration in strategic planning

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Integration**:
- Include supplier risks in board and executive risk reporting
- Add cybersecurity supplier risks to existing business risk registers
- Integrate key supplier assessments with annual risk planning process
- Include supplier security incidents in business risk event reporting
- Establish basic supplier risk escalation to business risk committees
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Integration**:
- Integrate technology supplier risks with IT risk management frameworks
- Include supplier security in IT service delivery risk assessments
- Add supplier dependencies to IT business continuity planning
- Integrate supplier incidents with IT incident management processes
- Include supplier risks in IT governance and steering committee reporting
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Integration Development
**Risk-Based Integration Enhancement**:
- Develop integrated supply chain and enterprise risk assessment methodology
- Create consolidated risk reporting with supply chain risk visibility
- Establish cross-functional risk committee with supply chain representation
- Implement risk-informed supplier decision-making criteria and processes
- Develop integrated risk monitoring and alerting across risk domains

#### Tier 3 (Repeatable) - Systematic Integration Management
**Systematic Integration Operations**:
- Implement automated risk data integration and consolidated reporting systems
- Establish continuous risk monitoring with integrated supply chain visibility
- Develop advanced risk correlation analysis across enterprise and supply chain risks
- Create standardized risk-informed decision-making frameworks and procedures
- Implement comprehensive risk scenario planning with supply chain integration

#### Tier 4 (Adaptive) - Advanced Integration Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Integration**:
- Deploy predictive risk analytics with advanced supply chain threat modeling
- Implement real-time integrated risk monitoring with automated correlation analysis
- Establish advanced risk intelligence integration with threat landscape analysis
- Develop adaptive risk management with dynamic supplier risk assessment
- Create strategic risk innovation programs with supply chain security integration
{{/if_infosec_led}}

### Technology Implementation

#### Risk Integration Technology Infrastructure
**Enterprise Risk Management Technology Context**:
- Current enterprise risk management platforms and reporting systems
- Supply chain risk assessment and monitoring technology capabilities
- Risk data integration and correlation analysis tools
- Enterprise dashboard and reporting infrastructure
- Integration capabilities with existing risk management systems

{{#if_engineering_led_plus}}
**Engineering-Led Integration Technology**:
- **Risk Analytics Platforms**: Integrated development and infrastructure risk monitoring
- **Dependency Tracking**: Automated supplier dependency risk analysis and reporting
- **CI/CD Integration**: Supply chain risk validation in development and deployment pipelines
- **Platform Monitoring**: Integrated supplier and platform risk monitoring systems
- **Risk Automation**: Automated risk assessment and integration workflow systems
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Integrated Risk Assessment Framework
**Comprehensive Risk Domain Integration**:
1. **Financial Risk**: Supplier financial stability integration with enterprise financial risk
2. **Operational Risk**: Supplier service delivery integration with business operational risk
3. **Strategic Risk**: Supplier dependency integration with business strategic risk
4. **Compliance Risk**: Supplier regulatory compliance integration with enterprise compliance risk
5. **Reputational Risk**: Supplier security incidents integration with brand and reputation risk

{{#if_business_led}}
**Executive Integration Strategy**:
- Board-level integrated risk reporting with supply chain risk visibility
- Executive risk committee coordination with supply chain risk oversight
- Strategic planning integration with supply chain risk considerations
- Investment decision-making with integrated supply chain risk assessment
- Crisis management coordination with supplier incident response integration
{{/if_business_led}}

### Assessment and Measurement

#### Integration Effectiveness Metrics
**Quantitative Measures**:
- Risk framework alignment completeness and consistency measurement
- Integrated risk reporting accuracy and timeliness assessment
- Risk-informed decision-making frequency and effectiveness tracking
- Cross-domain risk correlation analysis accuracy and insight generation
- Integrated risk monitoring coverage and alert response effectiveness

**Qualitative Measures**:
- Stakeholder satisfaction with integrated risk visibility and reporting
- Decision-maker confidence in risk-informed choices and strategic planning
- Risk management team collaboration effectiveness and coordination
- Integration adaptability to emerging risks and changing threat landscape
- Strategic alignment between enterprise and supply chain risk management

{{#if_infosec_led}}
**InfoSec-Led Integration Assessment**:
- Advanced threat correlation across enterprise and supply chain risk domains
- Predictive risk analytics accuracy and strategic insight generation
- Threat intelligence integration effectiveness with enterprise risk planning
- Security risk governance integration with enterprise risk committees
- Advanced risk scenario modeling accuracy and decision-making support
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **ISO 31000**: Risk Management - Guidelines for enterprise risk management
- **COSO ERM**: Enterprise Risk Management - Integrated Framework
- **NIST SP 800-39**: Managing Information Security Risk
- **NIST SP 800-161**: Cybersecurity Supply Chain Risk Management Practices
- **FAIR**: Factor Analysis of Information Risk methodology

#### Implementation Resources
{{#if_business_led}}
**Business-Led Integration Resources**:
- Enterprise risk management framework integration guidance
- Board and executive risk reporting template integration
- Business risk committee governance structure enhancement
- Strategic planning risk integration methodologies
- Executive risk communication and decision-making frameworks
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Integration Resources**:
- Technical risk management framework integration with supply chain assessment
- Engineering governance integration with enterprise risk management
- Development and platform risk assessment integration methodologies
- DevOps risk integration with automated supplier monitoring
- Technical risk reporting integration with enterprise risk dashboards
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Integration Maturity Progression
**Integration Enhancement Pathway**:
1. **Foundation**: Basic risk reporting integration and coordination
2. **Development**: Systematic risk assessment integration and correlation
3. **Integration**: Comprehensive risk management framework coordination
4. **Optimization**: Advanced predictive risk analytics and intelligence integration
5. **Innovation**: Adaptive integrated risk management with real-time optimization

#### Integration Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Integration Enhancement**:
- Technology risk management framework advancement and integration
- Automated risk monitoring and assessment integration development
- IT governance integration with enterprise risk management enhancement
- Service delivery risk integration with supply chain dependency management
- Technology innovation integration with strategic risk planning
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **GV.SC-01**: Supply chain program provides foundation for risk integration
- **GV.RM-01**: Risk management objectives establish enterprise risk context
- **GV.RM-03**: Risk management strategy provides integration framework

#### Supporting Subcategories
**Related Risk Management Subcategories**:
- **GV.RM-02**: Risk appetite and tolerance inform supply chain risk decisions
- **GV.RM-04**: Risk response strategies coordinate across risk domains
- **GV.RM-06**: Risk calculation methods support integrated assessment
- **ID.RA-01**: Asset vulnerability assessment includes supplier-managed assets
- **GV.OV-01**: Strategy outcomes review includes integrated risk assessment

### Implementation Timeline

#### Phase 1: Integration Foundation (Months 1-3)
**Immediate Implementation**:
- Current enterprise risk management assessment and gap analysis
- Supply chain risk integration planning and stakeholder engagement
- Basic risk reporting integration and initial coordination establishment
- Risk framework alignment assessment and harmonization planning
- Initial integrated risk committee coordination and communication

#### Phase 2: Integration Development (Months 4-8)
**Integration Enhancement**:
- Comprehensive risk assessment methodology integration and testing
- Integrated risk monitoring and reporting system implementation
- Cross-functional risk coordination process establishment and training
- Risk-informed decision-making framework development and rollout
- Technology platform integration and automated reporting implementation

#### Phase 3: Integration Optimization (Months 9-12)
**Integration Maturation**:
- Advanced risk analytics and correlation analysis implementation
- Continuous improvement process establishment and optimization
- Strategic integration planning and future capability development
- Industry collaboration and best practice integration
- Advanced risk intelligence and predictive analytics deployment

### Quality Assurance

#### Template Validation Checklist
- [ ] GV.SC-03 subcategory requirements fully addressed
- [ ] Maturity-specific integration approaches included for all security ownership levels
- [ ] Risk framework integration practical and achievable
- [ ] Enterprise risk management coordination comprehensive
- [ ] Decision-making support appropriate for maturity level
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Enterprise risk management framework assessed and documented
- [ ] Supply chain risk integration planning completed
- [ ] Risk reporting integration implemented and operational
- [ ] Cross-functional risk coordination established
- [ ] Risk-informed decision-making processes active
- [ ] Technology integration completed and functional
- [ ] Continuous improvement processes implemented
- [ ] Integration effectiveness measurement active