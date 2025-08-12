# Contributing to Awesome MCP Enterprise

Thank you for your interest in contributing to Awesome MCP Enterprise! This guide will help you understand how to contribute effectively.

## Before You Submit

Please ensure your submission meets these criteria:

### Required Criteria
- **Production-Ready**: The tool/service must be in production or GA (General Availability) stage (use Beta/Alpha badges for non-production tools)
- **Actively Maintained**: Last update within 6 months, responsive to issues
- **Clear Documentation**: Must have comprehensive documentation for enterprise deployment
- **MCP-Specific**: Must be specifically designed for or compatible with Model Context Protocol
- **Enterprise-Focused**: Should address enterprise needs (security, compliance, scalability, etc.)

### Quality Standards
- No abandoned projects (no updates for 12+ months)
- Must have a working website or GitHub repository
- Verifiable compliance certifications (if claimed)

## How to Add a New Tool

1. **Fork this repository**
2. **Add your tool to the appropriate category** in README.md
3. **Follow the exact format**:

```markdown
- **[Tool Name](https://website.com)** - One-line description focusing on unique value.
  
  ![Badge1](https://img.shields.io/badge/Badge-Text-color?style=flat-square) ![Badge2](https://img.shields.io/badge/Badge-Text-color?style=flat-square)
  - **GitHub:** ⭐ X stars (if applicable)
```

**Note:** Production stage is assumed by default. Only add ![Beta](https://img.shields.io/badge/Beta-orange?style=flat-square) or ![Alpha](https://img.shields.io/badge/Alpha-red?style=flat-square) badges for non-production tools.

4. **Include appropriate badges** from the legend (only if verified)
   - Use shields.io badges with the exact format from the README legend
   - Colors should match: green for compliance, blue for standards, etc.
   - Include only badges that are verifiable
5. **Keep descriptions concise** - one sentence maximum
6. **Maintain alphabetical order** within categories
7. **Submit a Pull Request** with a clear title and description

## Pull Request Template

When submitting a PR, please use this template:

```markdown
### Tool Name
[Tool Name]

### Category
[Select: Private Registries / Directories / Build Tools / Infrastructure / Security / Gateways]

### Why should this be included?
[Brief explanation of why this tool is valuable for enterprises]

### Checklist
- [ ] Tool is production-ready
- [ ] Documentation is comprehensive
- [ ] Compliance certifications are verified
- [ ] Entry follows the required format
- [ ] Placed in correct category
- [ ] Alphabetical order maintained
- [ ] All links are working
```

## Badge Guidelines

When adding badges to your entry:
- Use the shields.io format: `![Name](https://img.shields.io/badge/Text-Value-color?style=flat-square)`
- Follow the color scheme from the legend:
  - **Green**: Compliance certifications (SOC2, HIPAA)
  - **Blue**: Standards (GDPR, ISO 27001, PCI DSS)
  - **Bright Green**: Open Source
  - **Orange**: Beta stage or Self-Hostable features
  - **Red**: Alpha stage (experimental)
  - **Yellow**: OAuth support
  - **Purple**: Built-in guardrails
  - **Success/Green**: Free tier available
- Production stage is assumed - only add Beta/Alpha badges for non-production tools
- Only include badges for features/certifications you can verify with documentation

## Adding Resources

Resources (tutorials, blog posts, etc.) should:
- Be high-quality and informative
- Focus on enterprise use cases
- Be from reputable sources
- Not be purely promotional

## What We Don't Accept

- Alpha/experimental tools (unless clearly marked and exceptional)
- Purely promotional content
- Duplicate entries
- Tools without clear MCP integration
- Broken or dead links
- Tools with no documentation
- Submissions with incorrect formatting

## Updating Existing Entries

If you notice outdated information:
1. Open an issue first to discuss the change
2. Provide evidence for the update (links, screenshots, etc.)
3. Submit a PR with the corrected information

## Code of Conduct

We follow the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). Please be respectful and constructive in all interactions.

## Questions?

If you're unsure about whether your submission fits, please open an issue for discussion first. We're happy to help!

## License

By contributing, you agree that your contributions will be licensed under CC0-1.0.