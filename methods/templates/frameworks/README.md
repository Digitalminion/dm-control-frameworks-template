<!-- BEGIN AI HEADER: 70 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: framework-specific-templates, template-methodology, nist-frameworks, control-templates
    CONTENT: framework-templates-overview, usage-guidance, template-structure, ai-instructions
    RELATED: methods/templates/controls/, methods/adoption/frameworks/, context/
    RATING: foundational
    PURPOSE: Framework-Specific Templates Directory - Comprehensive guide to framework-specific control templates
    UPDATE: High
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    FRAMEWORKS TEMPLATE PURPOSE: This directory contains framework-specific templates that provide
    detailed, framework-specific guidance for individual controls/subcategories within each NIST
    framework. Unlike generic templates, these are tailored to the specific language, requirements,
    and context of each framework.
    
    TEMPLATE SPECIFICITY: Each template is designed for a specific control or subcategory and includes
    the exact framework language, specific implementation guidance, and framework-specific assessment
    procedures.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When working with framework-specific templates:
    1. Follow the AI header standards from methods/agent.md
    2. Use the exact framework language and terminology
    3. Preserve all framework-specific requirements and guidance
    4. Integrate organizational context from context/ folder
    5. Maintain consistency with the framework's overall approach and philosophy
    6. Create cross-references to related controls within the same framework
    7. Map to other frameworks where appropriate
    8. Focus on practical implementation for the target audience of each framework
    9. Include framework-specific assessment and measurement approaches
    10. Ensure templates support the intended use case of each framework
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER: 70 LINES --> 

# Framework-Specific Templates

> **Navigation:** [🏠 Root](../../../README.md) › [📁 Methods](../../README.md) › [📁 Templates](../README.md) › **Frameworks**

## Overview

This directory contains framework-specific templates for NIST cybersecurity frameworks. Unlike the generic control templates in the parent directory, these templates are tailored to the specific language, requirements, and implementation context of each individual framework.

## Framework-Specific Template Approach

### Why Framework-Specific Templates?

Each NIST framework has distinct characteristics that require specialized templates:

- **NIST 800-53**: Detailed technical controls with specific baselines and enhancements
- **NIST 800-171**: CUI-focused requirements for non-federal organizations and contractors
- **NIST CSF**: Strategic, outcome-oriented subcategories with implementation tiers

### Template Methodology

#### Framework Fidelity
- **Exact Language**: Preserve official framework terminology and control statements
- **Specific Requirements**: Include framework-specific implementation requirements
- **Native Assessment**: Use framework-native assessment and measurement approaches
- **Authentic Context**: Maintain the framework's intended use case and audience

#### Organizational Integration
- **Context Mapping**: Integrate organizational context from `context/` folder
- **Scalable Implementation**: Provide guidance for different organizational sizes and maturity levels
- **Technology Integration**: Include technology-specific implementation guidance
- **Risk Alignment**: Align with organizational risk profile and priorities

## Framework Directories

### NIST 800-53 Templates (`nist-800-53/`)

**Purpose**: Detailed technical control templates for federal systems and organizations

**Template Characteristics**:
- Complete NIST 800-53 control language and requirements
- Baseline-specific implementation guidance (Low/Moderate/High)
- Control enhancement integration
- Technical implementation details
- Comprehensive assessment procedures
- Cross-family control dependencies

**Target Audience**: Federal agencies, contractors, and organizations adopting 800-53 controls

**Example Template**: `AC-1.tpl.md` - Access Control Policy and Procedures

### NIST 800-171 Templates (`nist-800-171/`)

**Purpose**: CUI protection templates for non-federal organizations and contractors

**Template Characteristics**:
- Complete NIST 800-171 control language and CUI requirements
- Non-federal organization implementation context
- DFARS compliance integration
- Contractor-specific considerations
- Federal coordination requirements
- Practical implementation for smaller organizations

**Target Audience**: Defense contractors, non-federal organizations handling CUI

**Example Template**: `AC.1.001.tpl.md` - Access Control Policy and Procedures

### NIST CSF Templates (`nist-csf/`)

**Purpose**: Strategic cybersecurity outcome templates for business-focused implementation

**Template Characteristics**:
- Complete NIST CSF subcategory language and outcomes
- Implementation tier-specific guidance (Partial/Risk Informed/Repeatable/Adaptive)
- Business outcome focus
- Strategic value articulation
- Informative references integration
- Continuous improvement pathways

**Target Audience**: Business executives, strategic planners, organizations seeking business-aligned cybersecurity

**Example Template**: `ID.AM-1.tpl.md` - Physical Devices and Systems Inventory

## Template Structure Standards

### Common Template Elements

All framework-specific templates include:

1. **AI Header**: Framework-specific AI guidance and instructions
2. **Control/Subcategory Information**: Official identifiers and classification
3. **Framework Statement**: Exact framework language and requirements
4. **Organizational Implementation**: Context-driven implementation approach
5. **Assessment Framework**: Framework-appropriate evaluation methods
6. **Related Controls**: Framework-specific dependencies and relationships
7. **Implementation Timeline**: Realistic implementation planning
8. **Quality Assurance**: Template validation and implementation checklist

### Framework-Specific Variations

#### NIST 800-53 Specific Elements
- Control baselines and applicability
- Control enhancements and selection
- Technical implementation requirements
- Federal compliance considerations

#### NIST 800-171 Specific Elements
- CUI categories and handling requirements
- Federal contract obligations
- DFARS compliance integration
- Non-federal implementation context

#### NIST CSF Specific Elements
- Implementation tier guidance
- Business outcome articulation
- Informative references mapping
- Strategic value proposition

## Usage Guidance

### Template Selection

**Choose the appropriate framework template based on:**
- Organizational type and mission
- Regulatory and compliance requirements
- Business context and objectives
- Technical implementation needs
- Stakeholder expectations

### Template Implementation Process

1. **Context Assessment**: Review organizational context from `context/` folder
2. **Template Selection**: Choose specific control/subcategory template
3. **Placeholder Replacement**: Replace all `{{PLACEHOLDER}}` text with organizational content
4. **Framework Alignment**: Ensure alignment with framework requirements and philosophy
5. **Quality Validation**: Use template validation checklists
6. **Integration Planning**: Coordinate with related controls and organizational processes

### Organizational Context Integration

**Required Context Elements**:
- **Organization Profile**: From `context/organization/` files
- **Technology Stack**: From `context/technology/` files
- **Risk Profile**: From `context/risks/` files
- **Stakeholder Information**: From relevant context files

**Context Application**:
- Tailor implementation guidance to organizational capabilities
- Align with business objectives and priorities
- Consider resource constraints and limitations
- Integrate with existing processes and systems

## Template Quality Standards

### Framework Fidelity Requirements

- ✅ Exact framework language preservation
- ✅ Complete requirement coverage
- ✅ Framework-specific terminology usage
- ✅ Authentic assessment approaches
- ✅ Appropriate audience targeting

### Implementation Practicality Requirements

- ✅ Actionable implementation guidance
- ✅ Scalable approach for different organization sizes
- ✅ Technology integration considerations
- ✅ Resource requirement transparency
- ✅ Realistic timeline expectations

### Organizational Integration Requirements

- ✅ Context placeholder system
- ✅ Risk-based prioritization
- ✅ Business alignment guidance
- ✅ Stakeholder consideration
- ✅ Continuous improvement pathways

## AI Agent Guidance

### Framework-Specific AI Instructions

Each template includes comprehensive AI instructions for:
- Framework-specific language and terminology preservation
- Organizational context integration requirements
- Quality validation criteria
- Cross-framework coordination considerations
- Implementation practicality guidelines

### Template Generation Guidelines

**When generating framework-specific templates:**
1. Preserve exact framework language and requirements
2. Include framework-specific implementation context
3. Provide scalable guidance for different organizational maturity levels
4. Integrate appropriate informative references and standards
5. Maintain consistency with framework philosophy and approach
6. Include realistic implementation timelines and resource requirements
7. Provide comprehensive assessment and measurement frameworks
8. Create appropriate cross-references within and across frameworks

## Cross-Framework Coordination

### Framework Mapping and Integration

**Common Control Areas**:
- Access Control: Coordination across AC controls in 800-53/800-171 and ID.AM/PR.AC in CSF
- Risk Management: Integration of RA controls with ID.RA and ID.RM subcategories
- Incident Response: Alignment of IR controls with RS.* subcategories

**Implementation Coordination**:
- Shared organizational context and infrastructure
- Common technology platforms and tools
- Integrated assessment and audit processes
- Coordinated training and awareness programs

### Avoiding Framework Conflicts

**Consistency Requirements**:
- Aligned policy and procedure development
- Coordinated implementation timelines
- Consistent organizational roles and responsibilities
- Integrated monitoring and reporting processes

## Future Enhancements

### Template Evolution

**Planned Improvements**:
- Additional control and subcategory templates for complete framework coverage
- Enhanced cross-framework mapping and integration guidance
- Advanced automation and integration capabilities
- Improved organizational context integration
- Enhanced assessment and measurement frameworks

### Framework Updates

**Maintenance Process**:
- Regular review and update of framework-specific templates
- Integration of framework updates and revisions
- Continuous improvement based on implementation feedback
- Enhancement of organizational context integration capabilities

---

**This framework-specific template approach ensures authentic, practical, and organizationally-relevant implementation guidance for each NIST cybersecurity framework while maintaining the unique characteristics and value proposition of each framework.**