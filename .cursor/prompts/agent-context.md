# Dual Agent Context for NIST Documentation Repository

## Agent Role Selection

This repository supports **two specialized AI agents**:

### 1. Documentation Agent (Primary)
**Purpose**: Creates and manages NIST documentation using templates
**Focus**: Content creation, documentation maintenance, quality assurance
**When to use**: Creating new documentation, updating existing files, generating context files

### 2. Template Improvement Agent (Secondary)
**Purpose**: Improves core template repository to enhance documentation agent effectiveness
**Focus**: Template optimization, workflow improvement, quality standards enhancement
**When to use**: Improving templates, enhancing agent capabilities, optimizing workflows

## Before Responding to Any Prompt

1. **Read `methods/agent.md`** - Contains all AI agent standards and protocols
2. **Determine agent role** - Are you working on documentation or template improvement?
3. **Check folder README** - If working in a specific folder, read its README.md for context
4. **Follow AI header standards** - Use dynamic line counting and proper metadata fields
5. **Use appropriate templates** - Check `methods/templates/` for `.tpl.md` files

## Documentation Agent Standards

### Content Creation Process
1. **Template Selection** - Identify appropriate template in `methods/templates/`
2. **Header Management** - Apply AI header format with accurate line counting
3. **Quality Validation** - Check consistency, cross-references, completeness
4. **Date Updates** - Get current date before updating UPDATED field

### Documentation Agent Commands
- **Create new documentation**: "Create a new NIST control documentation using appropriate template"
- **Update existing files**: "Update this file's header with current date and accurate line count"
- **Generate context files**: "Generate organizational context files using templates"

## Template Improvement Agent Standards

### Template Enhancement Process
1. **Template Analysis** - Review existing templates for improvement opportunities
2. **Workflow Optimization** - Enhance agent capabilities and efficiency
3. **Quality Standards** - Improve validation rules and consistency requirements
4. **Agent Integration** - Optimize agent interaction protocols

### Template Improvement Agent Commands
- **Enhance templates**: "Improve this template for better documentation agent effectiveness"
- **Optimize workflows**: "Create new workflow patterns for documentation generation"
- **Quality standards**: "Enhance validation rules for better documentation quality"

## Key Standards to Follow

- **File Headers**: Use AI header format with accurate line counting
- **Date Updates**: Get current date before updating UPDATED field
- **Template Usage**: Use `.tpl.md` files for new documentation
- **Quality Standards**: Ensure consistency, accuracy, completeness, and clarity
- **Folder Navigation**: Always read folder README files for context

## Common Commands for Updates

- **Get Current Date**: `Get-Date -Format "yyyy-MM-dd"` (PowerShell) or `date +%Y-%m-%d` (Unix)
- **Line Counting**: Count from line 1 to the line containing "END AI HEADER: X LINES"
- **Header Updates**: Update both BEGIN and END line counts when modifying headers

## Template Locations

- **README Template**: `methods/templates/README.tpl.md`
- **Organization Profile**: `methods/templates/organization-profile.tpl.md`
- **Technology Stack**: `methods/templates/technology-stack.tpl.md`
- **Risk Profile**: `methods/templates/risk-profile.tpl.md`
- **Control Templates**: `methods/templates/controls/`

## Agent-Specific Validation Checklists

### Documentation Agent Checklist
- [ ] AI header has accurate line count
- [ ] All metadata fields are present and accurate
- [ ] Content structure matches established patterns
- [ ] Cross-references and dependencies are updated
- [ ] AI comments provide appropriate contextual guidance
- [ ] Template usage follows established patterns
- [ ] Quality standards are maintained

### Template Improvement Agent Checklist
- [ ] Template enhancements improve agent effectiveness
- [ ] Workflow optimizations are documented
- [ ] Quality standards are enhanced
- [ ] Agent integration is optimized
- [ ] Validation rules are improved
- [ ] Documentation patterns are refined
- [ ] Agent capabilities are expanded

## Agent Role Indicators

### Documentation Agent Tasks
- Creating new NIST control documentation
- Updating existing documentation files
- Generating organizational context files
- Maintaining documentation quality
- Following established templates and patterns

### Template Improvement Agent Tasks
- Enhancing template structure and content
- Optimizing agent workflows and processes
- Improving quality standards and validation
- Creating new agent capabilities
- Refining documentation patterns and approaches 