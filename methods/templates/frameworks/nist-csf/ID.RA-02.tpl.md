<!-- BEGIN AI HEADER: 120 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-csf-id-ra-02, risk-assessment, cyber-threat-intelligence, information-sharing, identification-template, security-maturity
    CONTENT: csf-subcategory-template, strategic-guidance, implementation-guidance, ai-instructions, maturity-adaptations
    RELATED: methods/templates/controls/, context/organization/, methods/adoption/frameworks/csf/, maturity_proposal.md
    RATING: foundational
    PURPOSE: Maturity-Aware NIST CSF ID.RA-02 Cyber Threat Intelligence Template
    UPDATE: High
    SECURITY_MATURITY_LEVEL: adaptive_template
    TARGET_AUDIENCE: all_organizational_maturity_levels
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    MATURITY-AWARE ID.RA-02 TEMPLATE PURPOSE: This enhanced template provides a framework-specific 
    template for NIST CSF ID.RA-02 (Cyber threat intelligence is received from information sharing 
    forums and sources) with adaptive content that adjusts based on organizational security 
    responsibility maturity.
    
    CSF SPECIFICITY: This template focuses on identification outcomes that establish clear 
    understanding of cyber threat intelligence collection and analysis with appropriate 
    depth based on organizational maturity levels.
    
    TEMPLATE USAGE: Use this template to generate ID.RA-02 documentation that manages 
    cyber threat intelligence appropriate to the organization's security responsibility 
    maturity level and threat landscape complexity.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When using this maturity-aware ID.RA-02 template to generate control documentation:
    
    STANDARD CSF TEMPLATE OPERATIONS:
    1. SUBCATEGORY SPECIFICITY: This template is specifically for NIST CSF ID.RA-02
    2. IDENTIFICATION FOCUS: Emphasize cyber threat intelligence collection and analysis
    3. REPLACE PLACEHOLDERS: Replace all {{PLACEHOLDER}} text with organization-specific content
    4. IMPLEMENTATION TIERS: Consider current and target implementation tier levels
    5. INFORMATIVE REFERENCES: Map to relevant standards and frameworks
    6. OUTCOME ORIENTATION: Focus on achieving clear threat intelligence identification outcomes
    
    MATURITY-AWARE ADAPTATIONS:
    7. READ ORGANIZATIONAL MATURITY: Assess security_ownership level from organization profile
    8. APPLY APPROPRIATE INTELLIGENCE COMPLEXITY: Use maturity-specific threat intelligence analysis depth
    9. INCLUDE RELEVANT INTELLIGENCE SECTIONS: Show/hide sections based on maturity level
    10. SET MATURITY-APPROPRIATE SOURCES: Match intelligence sources to organizational capability
    11. ADJUST INTELLIGENCE GUIDANCE: Provide guidance appropriate to maturity level
    12. FOCUS ON MATURITY-RELEVANT THREATS: Emphasize threat intelligence important to maturity level
    
    MATURITY-SPECIFIC CONTENT ADAPTATION FOR ID.RA-02:
    
    IF security_ownership == "business_led":
    - Use business language focused on business-relevant threat intelligence and operational security awareness
    - Emphasize threat intelligence based on business operations and industry-specific threats
    - Include executive and operational threat awareness and business security intelligence
    - Focus on compliance-driven threat intelligence and business impact threat considerations
    - Provide simple threat intelligence frameworks appropriate to business operations management
    - Include business security awareness and operational threat intelligence considerations
    
    IF security_ownership == "it_led":
    - Use IT language focused on technology threat intelligence and infrastructure security awareness
    - Emphasize threat intelligence based on IT infrastructure and technology-specific threats
    - Include IT governance and technology threat intelligence and infrastructure security awareness
    - Focus on operational threat intelligence and IT security threat considerations
    - Provide IT-centric threat intelligence frameworks and technology threat analysis
    - Include technology security and infrastructure threat intelligence considerations
    
    IF security_ownership == "engineering_led":
    - Use engineering language focused on technical threat intelligence and development security awareness
    - Emphasize threat intelligence based on engineering operations and platform-specific threats
    - Include engineering governance and technical threat intelligence and development security awareness
    - Focus on technical threat intelligence and engineering platform threat considerations
    - Provide engineering-centric threat intelligence frameworks and technical threat analysis
    - Include development security and platform threat intelligence considerations
    
    IF security_ownership == "infosec_led":
    - Use security language focused on comprehensive threat intelligence and advanced threat analysis
    - Emphasize threat intelligence based on security operations and advanced threat landscape analysis
    - Include security governance and strategic threat intelligence and comprehensive threat analysis
    - Focus on threat-informed intelligence collection and advanced threat intelligence considerations
    - Provide security-centric threat intelligence frameworks and advanced threat analysis
    - Include strategic security operations and threat landscape intelligence considerations
    
    CONTEXT REQUIREMENTS:
    - Read context/organization/ files for industry threats and business risk considerations
    - Read context/stakeholders/ files for external threat information and intelligence sharing requirements
    - Use organizational maturity context to tailor threat intelligence complexity and sources
    - Consider threat landscape complexity and intelligence criticality appropriate to maturity level
    
    QUALITY VALIDATION:
    - CSF language and intent must be preserved accurately
    - Threat intelligence approaches must be clearly articulated for the maturity level
    - Intelligence collection strategies must be practical and effective
    - Threat analysis must align with organizational capability
    - Identification outcomes must support effective threat awareness and risk management
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER --> 

---

## NIST CSF Subcategory: ID.RA-02

### Subcategory Information
- **ID**: ID.RA-02
- **Function**: IDENTIFY (ID)
- **Category**: Risk Assessment (RA)
- **Title**: Cyber Threat Intelligence
- **Outcome**: Cyber threat intelligence is received from information sharing forums and sources

**Implementation Status**: {{IMPLEMENTATION_STATUS}}  
**Implementation Date**: {{IMPLEMENTATION_DATE}}  
**Review Date**: {{REVIEW_DATE}}  
**Version**: {{VERSION}}

### NIST CSF Subcategory Statement

**Outcome Statement**: The organization establishes and maintains processes to receive, analyze, and act upon cyber threat intelligence from information sharing forums and external sources, enabling informed risk assessment and proactive threat mitigation decisions.

**Strategic Value**: This subcategory establishes foundational threat awareness by creating systematic threat intelligence collection and analysis capabilities, enabling more effective risk assessment, proactive security planning, and incident prevention decisions based on current threat landscape information.

### Organizational Implementation

#### Current Cyber Threat Intelligence Assessment
{{#if_business_led}}
**Business-Led Threat Intelligence Assessment**:
- Current business threat awareness and operational security intelligence analysis
- Industry-specific threat intelligence and business sector threat landscape mapping
- Business risk threat intelligence and operational threat awareness identification
- Executive and operational threat intelligence governance and business security awareness requirements
- Regulatory compliance and business threat intelligence documentation requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**IT-Led Threat Intelligence Assessment**:
- Technology infrastructure and IT threat intelligence analysis
- Cloud service provider and technology platform threat intelligence mapping
- IT service delivery and infrastructure threat intelligence identification
- Technology integration and platform threat intelligence assessment and documentation
- IT infrastructure and service operation threat intelligence requirements
{{/if_it_led_plus}}

{{#if_engineering_led_plus}}
**Engineering-Led Threat Intelligence Assessment**:
- Software development and technical platform threat intelligence analysis
- Development tool and infrastructure threat intelligence mapping
- Platform and infrastructure technical threat intelligence identification
- Technical ecosystem and engineering threat intelligence integration assessment
- Engineering platform and development operation threat intelligence documentation
{{/if_engineering_led_plus}}

{{#if_infosec_led}}
**InfoSec-Led Threat Intelligence Assessment**:
- Security infrastructure and comprehensive threat intelligence analysis
- Advanced security threat intelligence and strategic threat landscape mapping and assessment
- Security operations and incident response threat intelligence identification
- Comprehensive security and threat management intelligence assessment
- Strategic security operation and threat landscape intelligence documentation
{{/if_infosec_led}}

#### Framework-Specific Threat Intelligence Elements

**Cyber Threat Intelligence Framework**:
1. **Intelligence Sources**: Comprehensive identification and management of threat intelligence sources
2. **Collection Processes**: Systematic processes for gathering threat information from multiple sources
3. **Analysis Capabilities**: Analytical frameworks for processing and contextualizing threat intelligence
4. **Dissemination Mechanisms**: Structured approaches for sharing threat intelligence within the organization
5. **Actionable Intelligence**: Processes for converting threat intelligence into actionable security measures

### Implementation Approach by Tier

#### Tier 1 (Partial) - {{PRIMARY_SECURITY_ROLE}} Focus
{{#if_business_led}}
**Basic Business-Led Threat Intelligence**:
- Document fundamental business threat awareness and primary industry threat sources
- Create simple threat intelligence mapping and basic threat information collection
- Identify key business threat intelligence sources and core threat awareness processes
- Establish basic threat intelligence communication and business threat awareness documentation
- Define minimum threat intelligence collection and business threat tracking requirements
{{/if_business_led}}

{{#if_it_led_plus}}
**Basic IT-Led Threat Intelligence**:
- Document technology threat intelligence and primary IT security threat sources
- Create simple IT threat intelligence mapping and technology threat information collection
- Identify critical technology threat intelligence sources and core IT threat awareness processes
- Establish basic IT threat intelligence communication and technology threat awareness documentation
- Define minimum IT threat intelligence collection and technology threat tracking requirements
{{/if_it_led_plus}}

#### Tier 2 (Risk Informed) - Enhanced Threat Intelligence
**Risk-Based Threat Intelligence Enhancement**:
- Develop comprehensive threat intelligence analysis with risk assessment and threat integration
- Create structured threat analysis across multiple intelligence and threat dimensions
- Implement systematic threat intelligence monitoring and threat validation processes
- Establish risk-informed threat intelligence communication and threat management
- Develop coordinated threat intelligence documentation and operational alignment

#### Tier 3 (Repeatable) - Systematic Threat Intelligence Management
**Systematic Threat Intelligence Operations**:
- Implement automated threat intelligence collection and threat analysis systems
- Establish continuous threat intelligence assessment and threat evolution monitoring
- Develop advanced threat intelligence analytics and threat optimization analysis
- Create standardized threat intelligence communication and threat management processes
- Implement comprehensive threat intelligence performance measurement and strategic planning

#### Tier 4 (Adaptive) - Advanced Threat Intelligence Optimization
{{#if_infosec_led}}
**Advanced InfoSec-Led Threat Intelligence Management**:
- Deploy predictive threat intelligence analytics with advanced threat analysis integration
- Implement real-time threat intelligence monitoring with adaptive threat response strategies
- Establish dynamic threat intelligence assessment with strategic threat optimization
- Develop advanced threat-informed intelligence communication and collaboration
- Create strategic threat positioning with industry threat intelligence and innovation
{{/if_infosec_led}}

### Technology Implementation

#### Threat Intelligence Technology Infrastructure
**Cyber Threat Intelligence Management Technology Context**:
- Current threat intelligence platforms and collection tools
- Threat analysis and intelligence processing systems
- Information sharing and collaboration platforms
- Security information and event management (SIEM) integration
- Integration capabilities with security tools and threat detection systems

{{#if_engineering_led_plus}}
**Engineering-Led Threat Intelligence Technology**:
- **Intelligence Collection**: Automated platform and development threat intelligence analysis and mapping
- **Threat Analysis**: Technical threat intelligence tracking and threat integration analysis systems
- **Intelligence Processing**: Technical threat intelligence design and development threat visualization
- **Communication Platforms**: Engineering team threat intelligence and threat communication and collaboration
- **Analytics Systems**: Technical threat intelligence analysis and threat optimization tools
{{/if_engineering_led_plus}}

### Business Risk Integration

#### Threat Intelligence-Based Risk Management Framework
**Risk Assessment by Threat Intelligence Category**:
1. **Intelligence Gap Risk**: Lack of relevant threat intelligence impact on security posture
2. **False Intelligence Risk**: Inaccurate threat intelligence impact on security decisions
3. **Intelligence Overload Risk**: Information overload impact on threat analysis effectiveness
4. **Source Reliability Risk**: Unreliable threat intelligence sources impact on threat awareness
5. **Strategic Risk**: Long-term threat intelligence capability sustainability and evolution implications

{{#if_business_led}}
**Executive Threat Intelligence Strategy**:
- Board-level threat intelligence oversight and strategic threat awareness governance
- Executive decision-making for threat intelligence evolution and strategic threat development
- Strategic planning integration with threat intelligence optimization and threat positioning
- Investment decision-making with threat intelligence-based risk assessment
- Crisis management coordination with threat intelligence-specific incident response planning
{{/if_business_led}}

### Assessment and Measurement

#### Threat Intelligence Effectiveness Metrics
**Quantitative Measures**:
- Threat intelligence source coverage and intelligence collection effectiveness assessment
- Threat intelligence analysis accuracy and threat detection effectiveness measurement
- Threat intelligence-related incident prevention and threat mitigation tracking
- Intelligence processing time and threat response effectiveness measurement
- Threat intelligence optimization and threat positioning strategic advantage analysis

**Qualitative Measures**:
- Stakeholder satisfaction with threat intelligence clarity and threat communication effectiveness
- Internal team alignment on threat intelligence and threat management strategy
- Threat intelligence adaptability to changing threat landscape and intelligence conditions
- Strategic threat intelligence development and threat positioning advancement
- Leadership effectiveness in threat intelligence communication and threat coordination

{{#if_infosec_led}}
**InfoSec-Led Threat Intelligence Assessment**:
- Advanced security threat intelligence effectiveness in threat mitigation and intelligence protection
- Threat-informed intelligence positioning accuracy and strategic security threat relevance
- Security threat intelligence collaboration effectiveness and threat analysis integration
- Advanced threat intelligence modeling integration with threat landscape analysis
- Strategic security leadership development through threat intelligence positioning
{{/if_infosec_led}}

### Informative References

#### Primary Standards and Frameworks
- **NIST SP 800-150**: Guide to Cyber Threat Information Sharing
- **STIX/TAXII**: Structured Threat Information eXpression and Trusted Automated eXchange
- **MITRE ATT&CK**: Framework for understanding adversary tactics, techniques, and procedures
- **NIST SP 800-53**: Security and Privacy Controls (SI-5 family)
- **ISO 27035**: Information Security Incident Management

#### Implementation Resources
{{#if_business_led}}
**Business-Led Threat Intelligence Resources**:
- Business threat intelligence and industry threat awareness frameworks
- Executive threat intelligence oversight and business threat strategic planning
- Compliance threat intelligence documentation and business threat protection procedures
- Business threat intelligence planning and operational threat methodologies
- Strategic threat intelligence and business threat development management guidance
{{/if_business_led}}

{{#if_engineering_led_plus}}
**Engineering-Led Threat Intelligence Resources**:
- Technical threat intelligence and development threat frameworks
- Software development threat intelligence design and platform threat procedures
- Engineering governance integration with threat intelligence planning
- Platform threat optimization and integration threat intelligence methodologies
- DevOps and automation threat intelligence development and threat management guidelines
{{/if_engineering_led_plus}}

### Continuous Improvement

#### Threat Intelligence Maturity Progression
**Threat Intelligence Enhancement Pathway**:
1. **Foundation**: Basic threat intelligence identification and simple threat collection
2. **Development**: Systematic threat intelligence analysis with structured threat management
3. **Integration**: Comprehensive threat intelligence optimization with strategic threat integration
4. **Optimization**: Advanced predictive threat intelligence management with threat analysis intelligence
5. **Innovation**: Adaptive threat leadership with strategic threat intelligence positioning and security

#### Threat Intelligence Optimization Strategy
{{#if_it_led_plus}}
**IT-Led Threat Intelligence Enhancement**:
- Technology threat intelligence advancement and automation
- Service delivery threat integration with strategic IT threat intelligence planning
- IT governance enhancement with threat intelligence management integration
- Technology innovation integration with strategic threat intelligence positioning
- Automated threat intelligence analysis and threat optimization system implementation
{{/if_it_led_plus}}

### Related CSF Subcategories

#### Direct Dependencies
**Primary Dependencies**:
- **ID.RA-01**: Vulnerability identification provides context for threat intelligence analysis
- **ID.RA-03**: Threat identification coordinates with threat intelligence collection
- **GV.OC-01**: Organizational mission provides context for relevant threat intelligence

#### Supporting Subcategories
**Related Risk Assessment Subcategories**:
- **ID.RA-04**: Business impact analysis integrates with threat intelligence assessment
- **ID.RA-05**: Risk determination uses threat intelligence as input
- **ID.RA-06**: Risk response planning incorporates threat intelligence insights
- **DE.AE-01**: Baseline establishment coordinates with threat intelligence monitoring
- **RS.AN-01**: Incident analysis benefits from threat intelligence context

### Implementation Timeline

#### Phase 1: Threat Intelligence Foundation (Months 1-2)
**Immediate Implementation**:
- Basic threat intelligence source identification and intelligence collection mapping
- Initial threat assessment and intelligence communication framework establishment
- Simple threat intelligence analysis and threat documentation identification
- Basic threat intelligence communication and internal threat alignment processes
- Initial threat intelligence-related risk assessment and threat documentation

#### Phase 2: Threat Intelligence Development (Months 3-6)
**Threat Intelligence Enhancement**:
- Comprehensive threat intelligence analysis framework development and implementation
- Advanced threat assessment and intelligence validation system deployment
- Cross-functional threat intelligence coordination and strategic threat planning integration
- Performance measurement and threat intelligence optimization system establishment
- Strategic threat intelligence planning and threat positioning development

#### Phase 3: Threat Intelligence Optimization (Months 7-12)
**Threat Intelligence Maturation**:
- Advanced threat intelligence analytics and strategic threat positioning implementation
- Continuous improvement process establishment and optimization
- Strategic threat leadership development and intelligence collaboration
- Future capability planning and adaptive threat intelligence management framework
- Innovation integration and competitive advantage optimization

### Quality Assurance

#### Template Validation Checklist
- [ ] ID.RA-02 subcategory requirements fully addressed
- [ ] Maturity-specific threat intelligence approaches included for all security ownership levels
- [ ] Threat intelligence analysis practical and comprehensive
- [ ] Intelligence collection strategies appropriate for maturity level
- [ ] Risk integration comprehensive and business-aligned
- [ ] Informative references accurate and relevant
- [ ] Timeline realistic and achievable
- [ ] Quality metrics meaningful and measurable

#### Implementation Checklist
- [ ] Threat intelligence sources identified and established
- [ ] Intelligence collection processes documented and operational
- [ ] Threat analysis capabilities developed and validated
- [ ] Risk assessment integrated with threat intelligence
- [ ] Communication systems deployed and operational
- [ ] Performance measurement systems active
- [ ] Continuous improvement processes implemented
- [ ] Strategic planning integration completed