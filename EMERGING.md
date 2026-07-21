# Emerging MCP Listings 🧪

> **What is this list?** A watch-this-space catalogue of MCP-native, enterprise-oriented projects that are still early in their journey. Everything here is 🧪 by default — in beta, recently GA, or without public compliance documentation yet. The [main list](README.md) has a stricter evidence bar; this list is where newer projects live while they mature.

> **How to read it:** An entry here means the project looks promising and worth watching. As with anything early-stage, evaluate carefully before depending on it in production.

> **Moving to the main list:** Entries are reviewed periodically. As projects accumulate the evidence described in [CONTRIBUTING.md](CONTRIBUTING.md) — named customers, verifiable compliance, GA maturity, documented production use — they move to `README.md`. Entries that become inactive may be removed.

## How to Propose an Emerging Entry

Same as the main list: open a [Listing Proposal issue](.github/ISSUE_TEMPLATE/listing-proposal.yml), select **Emerging**, and wait for the `approved-for-pr` label before opening a PR. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Categories

Categories mirror the main list. Add entries under the matching heading; leave a heading empty if no entries exist yet.

### Private Registries

*No entries yet.*

### Gateways & Proxies

- **[AnythingMCP](https://github.com/HelpCode-ai/anythingmcp)** - Self-hosted, open-source MCP gateway that turns any REST/SOAP/GraphQL/SQL API or MCP server into governed connectors, with OAuth2, RBAC, and full audit logging. 🧪 🆓 🔑 🛡️

- **[Arbitus](https://github.com/arbitusgateway/arbitus)** - Rust-based open-source MCP security proxy with per-agent auth (API key, JWT/OIDC, mTLS), rate limiting, payload filtering, HITL approvals, and OPA/Rego policies. 🧪 🆓 🔑 🛡️

- **[Magertron MCP Orchestrator](https://github.com/curtismager20/magertron-mcpm)** - Kubernetes-native MCP gateway and orchestrator with Envoy v3 xDS session-affinity routing, leader-elected HA, per-tool RBAC, OCSF-aligned audit logs for SIEM, and SSO/SCIM; Helm chart open-sourced under Apache 2.0. 🧪 🆓 🔑 🛡️

- **[PolicyLayer](https://policylayer.com)** - Hosted MCP gateway that applies deterministic, deny-by-default policy to every tool call — allow, deny, rate-limit, or require approval — with argument-level rules, per-identity scoped tokens, and a per-call audit log. 🧪 🛡️ 🔑

- **[ToolRouter](https://toolrouter.com)** - MCP gateway providing access to 150+ pre-integrated tools behind a single account and API key, replacing per-provider credential management. 🧪 🔑 🆓

### Build Tools & Frameworks

- **[click-to-mcp](https://github.com/Coding-Dev-Tools/click-to-mcp)** - Auto-convert any Click/typer CLI into an MCP server. 🧪 🆓 🔑

### Security & Governance

- **[Armorer Guard](https://github.com/ArmorerLabs/Armorer-Guard)** - MIT-licensed local Rust scanner and MCP proxy that wraps stdio MCP servers and inspects tool-call arguments for prompt injection, credential leakage, and risky actions before execution. 🧪 🆓 🛡️

- **[Clay Seal](https://github.com/clayseal/clayseal-identity)** - Attested agent identity and Biscuit capability tokens sender-constrained to a holder key, letting an MCP server authorize each tool call offline and rendering a copied token inert; Python guard and JavaScript verifier. 🧪 🆓 🛡️

- **[Dominion Observatory](https://dominionobservatory.com)** - Behavioral trust scoring for 14,820+ MCP servers, with per-call attestation receipts, SLA monitoring, and compliance reporting to inform tool-call decisions before execution. 🧪 🆓 🛡️

- **[Haldir](https://haldir.xyz)** - Guardian layer for AI agents with scoped sessions, encrypted secrets vault, immutable audit trail, and proxy mode that intercepts every MCP tool call for policy enforcement. 🧪 🆓 🛡️

- **[mcp-audit](https://github.com/adudley78/mcp-audit)** - Open-source CLI scanner for MCP server configurations that detects tool poisoning, credential leaks, supply-chain risks, and cross-server attack paths across major MCP clients. 🧪 🆓 🛡️

- **[SidClaw](https://sidclaw.com)** - Open-source approval and audit layer that wraps MCP servers with policy evaluation, human-in-the-loop approval workflows, and hash-chain audit trails before tool execution. 🧪 🆓 🛡️

- **[Signet](https://github.com/Prismer-AI/signet)** - SDK and middleware that gives agents Ed25519 identity and cryptographically signs every MCP tool call, with encrypted key storage and hash-chained audit logs. 🧪 🆓 🛡️

- **[ThumbGate](https://github.com/IgorGanapolsky/ThumbGate)** - Pre-action gates for AI coding agents that catch destructive operations before they hit your codebase. 🧪 🆓 🛡️

### Infrastructure & Deployment

- **[Bridge](https://bridge.ls)** - Generates and hosts multi-tenant MCP servers for B2B SaaS from OpenAPI specs, handling auth (per-tenant OAuth credential isolation), hosting, and Streamable HTTP transport. 🧪 🆓 🔑

### MCP Directories & Marketplaces

- **[AgentRank](https://agentrank-ai.com)** - Live-scored directory of 25,000+ MCP servers, ranked daily by GitHub maintenance signals (freshness, issue health, contributors, dependents, stars). 🧪 🆓

- **[Find MCP](https://catalog.agentage.io/mcp)** - Directory of 17,000+ MCP servers synced from the official MCP registry, queryable by agents over MCP (`mcp_search`, `mcp_get`, `mcp_categories`) via hosted Streamable HTTP or npx stdio. 🧪 🆓

- **[Not Human Search](https://nothumansearch.ai)** - Agent-first search engine indexing 8,000+ MCP servers and agentically-readable sites, ranked by agentic readiness across 7 signals; includes a `verify_mcp` JSON-RPC probe. 🧪 🆓

### Tutorials & Guides

*No entries yet.*

## Legend

See the main [README legend](README.md#legend) for emoji meanings. All entries in this file carry an implicit 🧪.
