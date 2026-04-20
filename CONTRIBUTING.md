# Contributing to Awesome MCP Enterprise

Thank you for your interest in contributing to Awesome MCP Enterprise! This guide will help you understand how to contribute effectively.

> **Workflow is issue-first.** Open a [Tool Proposal issue](.github/ISSUE_TEMPLATE/tool-proposal.yml) and wait for the `approved-for-pr` label before opening a PR. PRs without an approved proposal will be closed.

## Before You Submit

### Understanding the Scope

This repository lists **infrastructure, platforms, and services for building, hosting, running, and securing MCP servers**. We do **not** list MCP servers themselves or agent frameworks that use MCP.

**In scope:** tools and platforms that help enterprises:
- Build and develop MCP servers (SDKs, frameworks, inspectors)
- Host, deploy, and scale MCP servers (infrastructure, cloud platforms)
- Secure, govern, and observe MCP servers (security, identity, audit)
- Discover and manage MCP servers (registries, gateways, proxies, directories)

**Out of scope:**
- MCP servers themselves (e.g., "an MCP server for Slack" or "an agent with 50+ MCP tools")
- Agent frameworks that consume MCP tools but don't provide MCP infrastructure
- Badges, certifications, or branding additions to this README
- New categories. We are not adding new sections at this time.
- Blog posts & articles (section currently paused)

> **Not sure?** Open an issue first to discuss whether your tool fits before submitting a PR.

### Two Lists

We maintain two lists so contributors have a path in regardless of maturity stage. Placement is about evidence, not about the quality of your work.

- **Main list (`README.md`)** — expected to meet **at least 2 of 4**: (1) named enterprise customers listed publicly, (2) verifiable compliance (SOC 2 / ISO 27001 / HIPAA / equivalent), (3) GA for 6+ months, (4) documented production deployments. Self-claims without links can't be verified, so please include sources.
- **Emerging (`EMERGING.md`)** — MCP-native, enterprise-oriented tools that are still early — in beta, recently GA, or without public compliance documentation yet. Marked 🧪. Reviewed periodically; entries move to the main list as they mature.

### Required Criteria
- **Production-Ready**: The tool/service must be in production or GA (General Availability) stage (beta tools may be accepted in Emerging if clearly marked with 🧪)
- **Actively Maintained**: Last update within 6 months, responsive to issues
- **Clear Documentation**: Must have comprehensive documentation for enterprise deployment
- **Working Links**: Your product website or repository must be live and functional
- **MCP-Specific**: Must be specifically designed for or compatible with Model Context Protocol
- **Enterprise-Focused**: Should address enterprise needs (security, compliance, scalability, etc.)

### Quality Standards
- No abandoned projects (no updates for 12+ months)
- Must have a working website or GitHub repository
- Verifiable compliance certifications (if claimed)

## How to Add a New Tool

1. **Open a [Tool Proposal issue](.github/ISSUE_TEMPLATE/tool-proposal.yml)** — fill every field, including evidence links and which list (Main or Emerging)
2. **Wait for triage** — maintainer labels the issue `approved-for-pr`, `needs-more-info`, or `declined`
3. **Fork the repository** once approved
4. **Add your tool to the appropriate category** in `README.md` (main) or `EMERGING.md` (emerging)
5. **Follow the exact format**:

```markdown
- **[Tool Name](https://website.com)** - One-line description focusing on unique value. 📜 🆓 🔑
```

**Note:** Production stage is assumed by default. Only add 🧪 emoji for beta/non-production tools (required for all Emerging entries).

6. **Include appropriate emojis** from the legend (only if verified)
   - Add emojis directly after the description
   - Include only emojis for features/certifications that are verifiable
7. **Keep descriptions concise** - one sentence maximum
8. **Maintain alphabetical order** within categories
9. **Submit a Pull Request** linking the approved issue with `Closes #<issue-number>`

## Pull Request Template

When submitting a PR, please use this template:

```markdown
### Linked Proposal Issue
Closes #<issue-number>  <!-- must be labeled approved-for-pr -->

### Tool Name
[Tool Name]

### Which List
[Main list / Emerging]

### Category
[Select: Private Registries / Directories / Build Tools / Infrastructure / Security / Gateways]

### Checklist
- [ ] Linked proposal issue is labeled `approved-for-pr`
- [ ] Tool is production-ready (or marked 🧪 for Emerging)
- [ ] Documentation is comprehensive
- [ ] Compliance certifications are verified
- [ ] Entry follows the required format
- [ ] Placed in correct category
- [ ] Alphabetical order maintained
- [ ] All links are working
```

## Emoji Guidelines

When adding emojis to your entry:
- Place emojis directly after the description, separated by spaces
- Use emojis from the legend in README.md:
  - 📜 SOC 2 Type II Certified
  - 🏥 HIPAA Compliant
  - 🇪🇺 GDPR Compliant
  - 📘 ISO 27001 Certified
  - 💳 PCI DSS Compliant
  - 🆓 Has Free Tier
  - 🔑 OAuth Support
  - 🛡️ Built-in Guardrails
  - 🧪 Beta Stage (not production-ready; required for Emerging entries)
- Production stage is assumed - only add 🧪 for beta/non-production tools
- Only include emojis for features/certifications you can verify with documentation

## Adding Resources

The *Blog Posts & Articles* section is currently paused — do not submit entries for it. Tutorials & Guides submissions should:
- Be high-quality and informative
- Focus on enterprise use cases
- Be from reputable sources
- Not be purely promotional

## What We Don't Accept

- **MCP servers or agent tools.** We list infrastructure for MCP, not MCP servers themselves.
- **New categories.** We are not accepting new sections at this time.
- **PRs without a pre-approved proposal issue.**
- **Blog posts or articles** (section paused).
- Alpha/experimental tools
- Purely promotional content
- Duplicate entries
- Tools without clear MCP integration
- Broken or dead links
- Tools with no documentation
- Submissions with incorrect formatting
- Badges, certifications, or branding additions to the README

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
