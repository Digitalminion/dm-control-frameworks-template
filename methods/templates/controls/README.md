<!-- BEGIN AI HEADER: 50 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: nist-controls, templates, documentation-structure, control-namespace, ai-templates
    CONTENT: template-guidance, control-documentation, file-structure, ai-instructions, complete-template-suite
    RELATED: methods/templates/, methods/agent.md, context/, controls/
    RATING: foundational
    PURPOSE: Controls Template Folder - Complete suite of templates for NIST control ID namespace files
    UPDATE: High
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    CONTROLS TEMPLATE PURPOSE: This folder contains a complete suite of templates for creating
    documentation files within each NIST control ID namespace. These templates provide comprehensive
    AI guidance and structured content for generating consistent, high-quality control documentation.
    
    TEMPLATE USAGE: Templates in this folder are used to generate files within control-specific
    folders (e.g., AC-1/, IA-2/, etc.) to ensure consistency across all NIST control documentation.
    
    COMPLETE SUITE: All six core templates have been created and are ready for use by AI agents
    to generate comprehensive control documentation.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: For complete guidance see methods/agent.md.
    Control templates focus: Use the complete 6-template suite for comprehensive
    control documentation, replace placeholders with specific control content,
    and apply organizational context from context/ folder.
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER: 50 LINES --> 

# Controls Templates

> **Navigation:** [🏠 Root](../../../README.md) › [📁 Methods](../../README.md) › [📁 Templates](../README.md) › **Controls**

## Purpose

This folder contains a **complete suite of templates** for creating comprehensive documentation files within each NIST control ID namespace. These templates provide structured AI guidance and content frameworks for generating consistent, high-quality control documentation across the entire NIST framework.

## Complete Template Suite

### ✅ **All Templates Created and Ready**

The following six core templates have been created and are ready for use:

1. **`control-overview.tpl.md`** - Main control documentation and description
2. **`implementation-guide.tpl.md`** - Step-by-step implementation instructions
3. **`assessment-framework.tpl.md`** - Evaluation criteria and testing procedures
4. **`compliance-tracking.tpl.md`** - Audit requirements and evidence collection
5. **`risk-assessment.tpl.md`** - Control-specific risk considerations and mitigation
6. **`dependencies.tpl.md`** - Related controls and system dependencies

### Template Features

Each template includes:

- **Comprehensive AI Instructions**: Detailed guidance for AI agents
- **Placeholder System**: `{{PLACEHOLDER}}` format for easy content replacement
- **Organizational Context Integration**: Leverages `context/` folder for tailored content
- **Quality Validation**: Built-in validation requirements and quality standards
- **Cross-Reference Support**: Framework for linking between controls and documentation

## AI Agent Guidance

### Template Usage Protocol

When AI agents work with these templates:

1. **Read Template Instructions**: Follow comprehensive AI instructions in each template
2. **Apply Organizational Context**: Use `context/` folder for organization-specific content
3. **Replace All Placeholders**: Fill in all `{{PLACEHOLDER}}` text with actual content
4. **Update Metadata**: Set accurate TOPICS, CONTENT, RELATED fields for specific control
5. **Maintain Consistency**: Follow established patterns across all control documentation
6. **Validate Quality**: Apply validation rules before finalizing content
7. **Create Cross-References**: Link to related controls and documentation
8. **Update Line Counts**: Ensure accurate header line counts

### Quality Standards

All control documentation generated from these templates must meet:

- **Completeness**: All placeholder text replaced with actual content
- **Accuracy**: Reflect current organizational implementation and constraints
- **Consistency**: Follow established patterns and standards
- **Clarity**: Clear and actionable for intended audiences
- **Cross-Reference**: Proper linking to related controls and documentation
- **Context Integration**: Tailored to organizational environment and capabilities

## Template Structure

### Control Documentation Framework

Each template provides a comprehensive framework for specific aspects of control documentation:

- **Control Overview**: Complete control description, requirements, implementation guidance
- **Implementation Guide**: Detailed step-by-step procedures with technical guidance
- **Assessment Framework**: Systematic evaluation criteria and testing procedures
- **Compliance Tracking**: Audit requirements and evidence collection procedures
- **Risk Assessment**: Control-specific risk analysis and mitigation strategies
- **Dependencies**: Comprehensive mapping of relationships and system dependencies

### AI-Ready Design

All templates feature:

- **Structured AI Headers**: Complete metadata with accurate line counting
- **Detailed AI Instructions**: Step-by-step guidance for AI agents
- **Context Requirements**: Clear instructions for using organizational context
- **Quality Validation**: Built-in validation requirements and standards
- **Cross-Reference Framework**: Support for linking between controls

## File Naming Convention

Templates follow a consistent naming pattern:

- `control-overview.tpl.md` - Main control documentation
- `implementation-guide.tpl.md` - Implementation instructions
- `assessment-framework.tpl.md` - Evaluation and testing
- `compliance-tracking.tpl.md` - Audit and compliance
- `risk-assessment.tpl.md` - Risk considerations
- `dependencies.tpl.md` - Related controls and systems

## Integration with Repository Structure

### Control Namespace Integration

Templates generate files within control-specific folders:

```
controls/
├── AC-1/
│   ├── control-overview.md (generated from template)
│   ├── implementation-guide.md (generated from template)
│   ├── assessment-framework.md (generated from template)
│   ├── compliance-tracking.md (generated from template)
│   ├── risk-assessment.md (generated from template)
│   └── dependencies.md (generated from template)
├── IA-2/
│   ├── control-overview.md (generated from template)
│   └── ... (all template files)
└── ...
```

### Context Integration

Templates leverage organizational context from the `