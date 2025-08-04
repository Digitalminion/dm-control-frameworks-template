# Agent Context Template

## Before Responding to Any Prompt

1. **Read `methods/agent.md`** - This contains all AI agent standards and protocols
2. **Check folder README** - If working in a specific folder, read its README.md for context
3. **Follow AI header standards** - Use dynamic line counting and proper metadata fields
4. **Use templates when appropriate** - Check `methods/templates/` for `.tpl.md` files

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

## Validation Checklist

- [ ] AI header has accurate line count
- [ ] All metadata fields are present and accurate
- [ ] Content structure matches established patterns
- [ ] Cross-references and dependencies are updated
- [ ] AI comments provide appropriate contextual guidance 