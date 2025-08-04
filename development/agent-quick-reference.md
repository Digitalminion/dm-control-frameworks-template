<!-- BEGIN AI HEADER: 35 LINES --> 
<!-- BEGIN AI FILE SUMMARY --> 
<!-- 
    TOPICS: agent-quick-reference, cursor-agent-commands, workflow-reference, ai-standards
    CONTENT: quick-reference, commands, workflows, standards-reference
    RELATED: methods/agent.md, .cursorrules, development/cursor-agent-setup.md
    RATING: foundational
    PURPOSE: Quick Reference Guide for Cursor Background Agent
    UPDATE: Medium
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!-- 
    QUICK REFERENCE FOCUS: This file provides essential commands, workflows, and
    standards for the Cursor background agent working with this NIST documentation repository.
    Use this as a quick lookup guide for common tasks and standards.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!-- 
    QUICK REFERENCE: This file serves as a fast lookup guide for the Cursor agent.
    Include essential commands, workflows, and standards that the agent needs frequently.
    Keep it concise and actionable for quick reference during development work.
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER: 35 LINES --> 

# Cursor Agent Quick Reference

## Essential Commands

### File Header Management
```markdown
<!-- BEGIN AI HEADER: X LINES -->
<!-- BEGIN AI FILE SUMMARY -->
<!-- 
    TOPICS: comma-separated-topics
    CONTENT: comma-separated-content-types
    RELATED: comma-separated-related-files
    RATING: draft|foundational|intermediate|advanced
    PURPOSE: Brief description of document purpose
    UPDATE: Low|Medium|High|Critical
    UPDATED: YYYY-MM-DD
-->
<!-- END AI FILE SUMMARY -->
<!-- END AI HEADER: X LINES -->
```

### Line Counting
- Count from line 1 to line containing `END AI HEADER: X LINES`
- Update both BEGIN and END line numbers to match
- Include all lines: comments, blank lines, content

### Date Commands
```powershell
# Windows PowerShell
Get-Date -Format 'yyyy-MM-dd'

# Unix/Linux
date +%Y-%m-%d
```

## Workflow Commands

### 1. Create New Documentation
1. Check `methods/templates/` for appropriate template
2. Use template structure and instructions
3. Apply AI header format with accurate line count
4. Add AI comments for contextual guidance
5. Validate against quality standards

### 2. Update Existing Documentation
1. Get current date using system command
2. Update UPDATED field with current date
3. Count header lines and update line count
4. Ensure all metadata fields are accurate
5. Add AI comments where appropriate

### 3. Template Usage
1. Identify template in `methods/templates/`
2. Follow template structure exactly
3. Replace placeholder content
4. Maintain template instructions
5. Validate generated content

## Quality Standards Checklist

### File Headers
- [ ] BEGIN AI HEADER with accurate line count
- [ ] All metadata fields present and accurate
- [ ] AI COMMENT blocks for contextual guidance
- [ ] END AI HEADER with matching line count
- [ ] File title on line after header ends

### Content Quality
- [ ] Follows established patterns
- [ ] Includes proper cross-references
- [ ] Maintains consistency with existing docs
- [ ] Complete and accurate information
- [ ] Clear and actionable content

### Template Compliance
- [ ] Uses appropriate template
- [ ] Follows template structure
- [ ] Includes all required sections
- [ ] Maintains template instructions
- [ ] Validates against template rules

## Folder Navigation Protocol

### When Entering a Folder
1. **FIRST** read README.md in that folder
2. Parse AI header for folder-specific guidance
3. Look for "WHEN YOU NEED" sections
4. Follow folder's AI instructions
5. Use folder's guidance for next steps

### Key Folders
- `methods/agent.md` - Primary AI standards
- `methods/templates/` - Content templates
- `methods/adoption/` - Framework approaches
- `development/` - Development process
- `context/` - Organizational context (generated)

## Common Tasks

### Create New Template
1. Check existing templates in `methods/templates/`
2. Use `README.tpl.md` as base template
3. Apply AI header format
4. Include clear instructions for AI agents
5. Add validation rules and quality standards

### Update Agent Standards
1. Modify `methods/agent.md`
2. Update `.cursorrules` if needed
3. Test with simple scenarios
4. Validate against existing content
5. Update related documentation

### Generate Context Files
1. Use templates from `methods/templates/`
2. Generate files in appropriate `context/` subfolder
3. Follow template structure and instructions
4. Apply AI header format
5. Validate generated content

## Error Resolution

### Line Count Errors
- Verify line counting methodology
- Check for hidden characters
- Ensure accurate END AI HEADER placement
- Count all lines including comments

### Template Issues
- Verify template exists in `methods/templates/`
- Check template structure and instructions
- Ensure proper template format
- Follow template guidance exactly

### Quality Violations
- Review established patterns
- Check consistency requirements
- Validate cross-references
- Ensure completeness standards

## Quick Commands

### Get Current Date
```powershell
Get-Date -Format 'yyyy-MM-dd'
```

### Count Header Lines
1. Find line with `END AI HEADER: X LINES`
2. Count from line 1 to that line
3. Update both BEGIN and END line numbers

### Validate File Structure
1. Check AI header format
2. Verify metadata fields
3. Validate cross-references
4. Ensure quality standards

## Support Resources

### Primary References
- `methods/agent.md` - Complete AI standards
- `.cursorrules` - Cursor agent configuration
- `development/README.md` - Development process

### Templates
- `methods/templates/` - Available templates
- `methods/templates/README.tpl.md` - Base template
- `methods/templates/controls/` - Control templates

### Documentation
- `development/cursor-agent-setup.md` - Setup guide
- `development/CONTRIBUTING.md` - Contribution guidelines
- `README.md` - Repository overview

---

**Note**: This quick reference should be updated as agent capabilities evolve and new workflows are established. 