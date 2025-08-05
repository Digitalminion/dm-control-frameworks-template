<!-- BEGIN AI HEADER: 35 LINES -->
<!-- BEGIN AI FILE SUMMARY -->
<!-- 
    TOPICS: quick-reference, workflows, cheat-sheet, common-tasks
    CONTENT: workflow-summaries, quick-links, essential-commands, user-pathways
    RELATED: development/README.md, methods/, NAVIGATION.md
    RATING: foundational
    PURPOSE: Quick Reference Card for Common Repository Workflows
    UPDATE: High
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    QUICK REFERENCE: This file provides rapid access to common workflows and tasks
    without requiring users to navigate through lengthy documentation. It serves
    as a cheat sheet for frequent operations and essential information.
    
    EFFICIENCY FOCUS: Organized by task type rather than documentation structure
    to help users accomplish goals quickly. Each workflow includes only essential
    steps and links to detailed guidance when needed.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    AI AGENTS: When updating quick reference:
    1. Keep workflows to 3-5 steps maximum for quick consumption
    2. Include direct links to detailed documentation
    3. Update links when related files change
    4. Add new common workflows as they emerge
    5. Maintain concise, action-oriented language
    6. Group by user intent rather than technical organization
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER: 35 LINES -->

# Quick Reference Card

> **Fast Access to Common Workflows**

## 🚀 Getting Started Workflows

### New User Setup (5 minutes)
1. **Read overview**: [`README.md`](../README.md) → Project purpose and structure
2. **Check navigation**: [`NAVIGATION.md`](../NAVIGATION.md) → Find what you need
3. **Review standards**: [`methods/AGENT.md`](../methods/AGENT.md) → AI and documentation standards
4. **Choose your path**: Pick a workflow below based on your goals

### New Organization Implementation (30 minutes)
1. **Choose framework**: [`methods/adoption/README.md`](../methods/adoption/README.md) → NIST framework selection
2. **Set up context**: [`context/README.md`](../context/README.md) → Document your organization
3. **Find templates**: [`methods/templates/README.md`](../methods/templates/README.md) → Get starting templates
4. **Begin implementation**: Framework guides in [`methods/adoption/frameworks/`](../methods/adoption/frameworks/)

## 🔧 Development Workflows

### Creating New Templates (15 minutes)
1. **Check existing**: [`methods/templates/controls/`](../methods/templates/controls/) → Review current templates
2. **Copy base template**: Use appropriate `.tpl.md` file as starting point
3. **Follow AI standards**: [`methods/AGENT.md`](../methods/AGENT.md) → Header format and metadata
4. **Test with context**: [`context/`](../context/) → Validate with organizational info

### Improving Documentation (10 minutes)
1. **Find task**: [`TODO.md`](TODO.md) → Pick from project task list
2. **Read standards**: [`CONTRIBUTING.md`](CONTRIBUTING.md) → Quality requirements
3. **Make changes**: Follow established patterns and AI header format
4. **Update links**: Validate cross-references and navigation

### Setting Up AI Agents (20 minutes)
1. **Read AI guidance**: [`methods/AGENT.md`](../methods/AGENT.md) → Complete AI standards
2. **Review configurations**: [`development/`](../development/) → Agent setup files
3. **Check task list**: [`TODO.md`](TODO.md) → Available agent tasks
4. **Start with templates**: [`methods/templates/controls/`](../methods/templates/controls/) → Begin with control templates

## 📋 Framework Implementation

### NIST CSF Implementation
- **Start here**: [`methods/adoption/frameworks/csf/README.md`](../methods/adoption/frameworks/csf/README.md)
- **Template library**: [`methods/templates/frameworks/csf/`](../methods/templates/frameworks/csf/) (if exists)
- **Example controls**: Look for `GV.*`, `ID.*`, `PR.*`, `DE.*`, `RS.*`, `RC.*` patterns

### NIST 800-53 Implementation
- **Start here**: [`methods/adoption/frameworks/800-53/README.md`](../methods/adoption/frameworks/800-53/README.md)
- **Control families**: AC, AU, CA, CM, CP, IA, IR, MA, MP, PE, PL, PS, RA, SA, SC, SI, SR
- **Template patterns**: Control-specific templates for each family

### NIST 800-171 Implementation
- **Start here**: [`methods/adoption/frameworks/800-171/README.md`](../methods/adoption/frameworks/800-171/README.md)
- **CUI focus**: Controlled Unclassified Information protection
- **14 families**: Derived from 800-53 but CUI-specific

## 🛠️ Template Operations

### Find the Right Template
- **Context templates**: [`methods/templates/`](../methods/templates/) → Organization, technology, risk
- **Control templates**: [`methods/templates/controls/`](../methods/templates/controls/) → 6-template suite
- **Framework templates**: [`methods/templates/frameworks/`](../methods/templates/frameworks/) → Framework-specific
- **README templates**: [`methods/templates/README.tpl.md`](../methods/templates/README.tpl.md) → Standard structure

### Using Templates Effectively
1. **Choose base template**: Pick closest match to your needs
2. **Replace placeholders**: Update `[PLACEHOLDER]` content with specifics
3. **Apply context**: Use organizational info from [`context/`](../context/)
4. **Follow AI standards**: Maintain header format and metadata requirements

## 🔍 Finding Information

### Quick Searches
- **All templates**: Search in [`methods/templates/`](../methods/templates/) by keyword
- **Framework guidance**: Look in [`methods/adoption/frameworks/`](../methods/adoption/frameworks/) by framework name
- **AI guidance**: Everything in [`methods/AGENT.md`](../methods/AGENT.md)
- **Development info**: Check [`development/`](../development/) for process guidance

### Navigation Shortcuts
- **Site map**: [`NAVIGATION.md`](../NAVIGATION.md) → Complete repository guide
- **User pathways**: [`NAVIGATION.md#quick-access-by-user-type`](../NAVIGATION.md#quick-access-by-user-type) → Role-based navigation
- **Workflow guide**: [`NAVIGATION.md#workflow-based-navigation`](../NAVIGATION.md#workflow-based-navigation) → Task-based paths

## ⚡ Emergency Quick Fixes

### Broken Links
1. **Update navigation**: [`NAVIGATION.md`](../NAVIGATION.md) → Central link hub
2. **Check cross-references**: Search for filename in repository
3. **Update related files**: Find files linking to moved content
4. **Test navigation**: Verify links work from main entry points

### Missing Documentation
1. **Check TODO list**: [`TODO.md`](TODO.md) → See if task exists
2. **Find similar content**: Look in relevant folders for patterns
3. **Use templates**: [`methods/templates/`](../methods/templates/) → Start with template
4. **Follow standards**: [`methods/AGENT.md`](../methods/AGENT.md) → AI header requirements

### Template Issues
1. **Review standards**: [`methods/AGENT.md`](../methods/AGENT.md) → Header and format requirements
2. **Check examples**: [`methods/templates/controls/`](../methods/templates/controls/) → Working templates
3. **Validate metadata**: Ensure all required fields are present
4. **Test with context**: Use [`context/`](../context/) → Organizational validation

## 📞 Getting Help

### Documentation Questions
- **Template usage**: [`methods/templates/README.md`](../methods/templates/README.md)
- **Framework selection**: [`methods/adoption/README.md`](../methods/adoption/README.md)
- **Development process**: [`development/README.md`](README.md)
- **AI agent setup**: [`methods/AGENT.md`](../methods/AGENT.md)

### Common Issues
- **Navigation problems**: Use [`NAVIGATION.md`](../NAVIGATION.md) as starting point
- **Template errors**: Check [`methods/AGENT.md`](../methods/AGENT.md) for standards
- **Missing content**: Look in [`TODO.md`](TODO.md) for planned work
- **Process questions**: Review [`development/CONTRIBUTING.md`](CONTRIBUTING.md)

---

## Key File Locations

| What You Need | Where to Find It |
|---------------|------------------|
| **Project overview** | [`README.md`](../README.md) |
| **Navigation help** | [`NAVIGATION.md`](../NAVIGATION.md) |
| **AI standards** | [`methods/AGENT.md`](../methods/AGENT.md) |
| **Templates** | [`methods/templates/`](../methods/templates/) |
| **Framework guides** | [`methods/adoption/frameworks/`](../methods/adoption/frameworks/) |
| **TODO list** | [`development/TODO.md`](TODO.md) |
| **Development guide** | [`development/README.md`](README.md) |
| **Contributing** | [`development/CONTRIBUTING.md`](CONTRIBUTING.md) |
| **Context setup** | [`context/README.md`](../context/README.md) |

---

**Keep this reference handy for quick access to common operations. Update it when new workflows emerge or file locations change.**