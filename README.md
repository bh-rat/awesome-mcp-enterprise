# Awesome MCP Enterprise [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


> A curated list of awesome MCP (Model Context Protocol) tools, platforms, and services for enterprises 🏢

**Model Context Protocol (MCP)** is an open protocol that standardizes how applications give context to LLMs. This list is designed for all technical stakeholders exploring MCP solutions for building, finding, hosting, learning, securing, and using MCP servers and clients.

## Contents

 - [Private Registries (15)](#private-registries)
 - [Gateways & Proxies (31)](#gateways--proxies)
 - [Build Tools & Frameworks (16)](#build-tools--frameworks)
 - [Security & Governance (14)](#security--governance)
 - [Infrastructure & Deployment (8)](#infrastructure--deployment)
 - [MCP Directories & Marketplaces (8)](#mcp-directories--marketplaces)
 - [Tutorials & Guides (2)](#tutorials--guides)

## Private Registries
*Ready-to-use pluggable MCP server implementations where MCP servers and tools are managed by the organization. They usually come with auth, guardrails, observability and more.*

- **[ACI.dev](https://aci.dev)** - Power your agentic IDE or AI agent with 600+ tools. The open-source tool-calling engine that drops into any agentic IDE or custom AI agent. 🔑 🛡️

- **[Composio](https://composio.dev)** - 500+ managed MCP servers powering 100,000+ developers. Unified auth, enterprise-vetted integrations, and SOC 2 Type II certified. 📜 🆓 🔑

- **[Disco.dev](https://www.disco.dev)** - Integration hub to browse, connect, and share MCP tools for your AI agents. 🧪 🔑 🆓 

- **[Docker MCP Catalog](https://hub.docker.com/mcp)** - Ready-to-use container images for MCP servers for simple Docker-based deployment. 🆓 

- **[Glama](https://glama.ai/)** - Managed MCP platform: directories, hosted servers, AI gateway, agents/automations, logging/traceability, and public MCP API. 🔑 🛡️ 🆓 🇪🇺

- **[Gumloop](https://www.gumloop.com/mcp)**- Workflow automation platform with built-in MCP server integrations. Connects MCP tools to automate workflows and integrate data across services. 🔑 🆓 📜 🏥 🇪🇺 🛡️

- **[Klavis AI](https://www.klavis.ai/)** - Strata MCP server that guides AI agents through progressive tool discovery, addressing tool overload, context overload, and coverage gaps for reliable tool usage at any scale. 📜 🔑 🆓 🛡️

- **[Kong MCP Registry](https://konghq.com/)** - Enterprise MCP registry within Kong Konnect for AI agent discovery and governance. Links MCP servers to underlying APIs with enterprise-grade controls. 🔑 🛡️ 📜

- **[Make MCP](https://www.make.com/en)** - Integration module for connecting MCP servers to Make.com workflows. Enables workflow automations with MCP servers. 🆓 🔑 🇪🇺 📜 📘

- **[Merge](https://www.merge.dev/)** - Unified API and Agent Handler to connect to hundreds of third-party tools across HRIS, ATS, CRM, Accounting, File Storage, and Ticketing. 📜 🏥 🇪🇺 📘 🔑 🛡️ 🆓

- **[[mcp]central.io](https://mcpcentral.io)** - Private registries, managed cloud solutions, and intelligent tooling for
  non-technical enterprise teams, plus public directory. 🧪 🆓 🔑 🛡️

- **[Pipedream](https://mcp.pipedream.com/)** - AI developer toolkit for integrations: add 2,800+ APIs and 10,000+ tools to your assistant. 🆓 🇪🇺 📜 🏥 🔑

- **[Runlayer](https://www.runlayer.com/)** - MCP security and management platform with threat detection, observability, and detailed permissions integrated with Okta and Entra. 🔑 🛡️ 📜 🏥

- **[SuperMachine](https://supermachine.ai/)** - One-click hosted MCP servers with thousands of AI agent tools available instantly. Simple, managed setup and integration. 🔑

- **[Zapier MCP](https://zapier.com/mcp)** - Connect your AI to any app with Zapier MCP. The fastest way to let your AI assistant interact with thousands of apps. 🧪 🆓 🇪🇺 📜


## Gateways & Proxies
*MCP gateways, proxies, and routing solutions for enterprise architectures. Most also provide security features like OAuth, authn/authz, and guardrails.*

- **[Arcade.dev](https://www.arcade.dev)** - AI Tool-calling Platform that securely connects AI to MCPs, APIs, data, and more. Build assistants that don't just chat – they get work done. 🔑 🆓 📜 🏥 💳

- **[Bifrost](https://github.com/maximhq/bifrost)** - High-performance open-source LLM and MCP gateway with sub-100µs overhead. Unified API for 15+ providers with automatic fallbacks and load balancing. 🆓

- **[catie-mcp](https://www.catiemcp.com/)** - Context-aware, configurable proxy for routing MCP JSON-RPC requests to appropriate backends based on request content. 🧪

 - **[Cloud MCP](https://cloudmcp.dev/)** - Enterprise MCP control plane providing secure, scalable infrastructure and granular access control. 🧪 🔑 🛡️ 📜 🇪🇺 🆓

- **[Docker MCP Gateway](https://github.com/docker/mcp-gateway)** - Open-source MCP gateway with container isolation, secrets management, and signature verification. Included in Docker Desktop. 🆓 🔑

 - **[Enkrypt AI](https://www.enkryptai.com/secure-mcp-gateway)** - The Security Layer Your MCP Server Needs. Open-source gateway delivering privacy, security, and governance for MCP integrations. 📜 🆓 🛡️

- **[FLUJO](https://github.com/mario-andreschak/FLUJO)** - MCP hub/inspector with multi-model workflow and chat interface for complex agent workflows using MCP servers and tools. 🧪 

- **[Golf (Enterprise MCP Gateway)](https://golf.dev/)** - Enterprise MCP gateway for centralized control, policy enforcement, SIEM integration, and PII/prompt-injection protection. 🛡️ 🔑 💳

- **[Itential MCP Server](https://www.itential.com/cloud-platform/itential-mcp-server/)** - Governance and orchestration layer connecting AI agents to enterprise network infrastructure with RBAC, audit logging, and policy enforcement. 🔑 🛡️

- **[Lasso MCP Gateway](https://www.lasso.security/)** - Protects every interaction with LLMs across your organization — simple, seamless, secure. 🛡️ 📜 📘 💳

- **[Lunar.dev MCPX](https://www.lunar.dev/)** - Lightweight, unified enterprise gateway to orchestrate and secure your MCP ecosystem. 🆓 📜 🔑

- **[MCP Context Forge](https://github.com/IBM/mcp-context-forge)** - Feature-rich MCP gateway, proxy, and registry built on FastAPI - unifies discovery, auth, rate-limiting, virtual servers, and observability. 🆓

- **[MCP Jungle](https://github.com/mcpjungle/MCPJungle)** - Self-hosted MCP registry and gateway for AI agents; single source of truth for your organization's MCP servers. 🧪

- **[MCP Manager](https://mcpmanager.ai/)** - Enforces policies, blocks rogue tool calls, and improves incident response to prevent AI risks.  🛡️ 🔑 📜 🏥 🇪🇺 📘 💳 

- **[MCP-connect](https://github.com/EvalsOne/MCP-connect)** - Proxy/client to let cloud services call local stdio-based MCP servers over HTTP for easy workflow integration. 🧪

- **[MetaMCP](https://github.com/metatool-ai/metamcp)** Open source. Proxy and aggregate multiple MCP servers into meta-MCPs, and host as SSE/SHTTP/OpenAPI endpoints with middleware, OAuth, and tool management. Stdio MCP servers hosting supported. 🔑 🧪 🆓

 - **[MintMCP](https://mintmcp.com/)** - Auth/SSO, RBAC, logs, virtual MCP servers; deploys and runs custom MCPs for you. 🔑 🛡️ 📜 🏥 🇪🇺

 - **[Microsoft MCP Gateway](https://github.com/microsoft/mcp-gateway)** - Reverse proxy and management layer for MCP servers with scalable, session-aware routing and lifecycle management on Kubernetes. 🆓 🔑

 - **[NexusRouter](https://nexusrouter.com/)** - Unified endpoint to route MCP servers and LLMs; aggregate, govern, and control your AI stack. 🧪
 
 - **[Obot MCP Gateway](https://obot.ai/)** - Open-source MCP gateway providing a control plane to catalog, proxy, and manage MCP servers with SSO, RBAC, audit logging, and policy enforcement. 🔑 🛡️ 🆓

- **[Peta](https://peta.io/)** - Agent vault and zero-trust MCP gateway. Encrypted credential storage, scoped time-limited tokens, and human-in-the-loop approvals for high-risk operations. 🔑 🛡️

- **[palma.ai](https://palma.ai/)** - Unlock enterprise data enabled AI agents using MCP & A2A. Supercharge your AI investments with our scalable and secure enterprise gateway for your AI agents. 🧪 🔑 🇪🇺

 - **[Storm MCP](https://stormmcp.ai/)** - Enterprise MCP gateway and management platform: secure, verified hub for curated MCP servers with observability and policy controls. 🛡️ 🔑 📜 📘 💳 🏥 🇪🇺

- **[Traego](https://traego.ai)** - Supercharge your AI workflows with a single endpoint. 🧪

- **[Traefik Hub MCP Gateway](https://traefik.io/solutions/mcp-gateway)** - Enterprise MCP gateway with Task-Based Access Control (TBAC) for three-dimensional authorization across tasks, tools, and transactions. 🔑 🛡️ 📜

- **[TrueFoundry](https://www.truefoundry.com/mcp-gateway)** - Enterprise-grade MCP gateway with secure access, RBAC, observability, and dynamic policy enforcement. 🔑 🛡️ 📜 🏥 🇪🇺

 - **[UCL](https://ucl.dev/)** - Multi-tenant MCP gateway: auth, monitoring, observability, orchestration to connect agents to user tools. 🔑 🛡️

- **[Unla](https://github.com/AmoyLab/Unla)** - Lightweight gateway that turns existing MCP servers and APIs into MCP servers with zero code changes. 🧪 🔑

- **[Webrix](https://www.webrix.ai)** - Secure MCP gateway to connect any AI agent with external and internal tools. SSO, RBAC, and full observability built-in. SaaS or On-Prem. 📜 🆓 🔑 🛡️

- **[Workato Enterprise MCP](https://www.workato.com/agentic/mcp)** - Enterprise MCP platform with access to 12,000+ apps and 900,000 community recipes. Verified user access and unified orchestration. 🔑 🛡️ 📜 🏥

- **[WSO2 MCP Gateway](https://wso2.com/api-manager/ai-gateway/)** - Unified API and AI gateway to expose existing APIs as MCP tools with guardrails, policy enforcement, and enterprise identity integration. 🔑 🛡️ 📜


## Build Tools & Frameworks
*Frameworks and SDKs for building custom MCP servers and clients*

- **[ContexaAI](https://www.contexaai.com/)** - Firebase for MCP servers: build, test, debug, and deploy MCP servers with OAuth support. 🔑 🆓 🇪🇺

 - **[Dummy MCP](https://dummymcp.com/)** - Create prototype MCP servers instantly: define tools and mock responses to test LLM interactions and iterate quickly. 🆓 🇪🇺 🔑

- **[FastAPI MCP](https://github.com/tadata-org/fastapi_mcp)** - Expose your FastAPI endpoints as MCP tools with auth. 🆓 🔑

- **[FastMCP](https://gofastmcp.com/)** - The fast, Pythonic way to build MCP servers and clients with comprehensive tooling. 🆓 🔑

- **[Golf.dev](https://golf.dev/)** - Turn your code into spec-compliant MCP servers with zero boilerplate. 🔑 🛡️ 🆓

- **[Lean MCP](https://leanmcp.com/)** - Lightweight toolkit for quickly building MCP‑compliant servers without heavy dependencies. 

- **[MCPJam Inspector](https://github.com/MCPJam/inspector)** - "Postman for MCPs" — test and debug MCP servers by sending requests and viewing responses. 🆓 🔑

- **[Metorial](https://metorial.com/)** - Connect AI models to APIs, data sources, and tools via MCP with one-liner SDKs. Unified interface with monitoring and self-hosting options. 🆓

- **[mcpadapt](https://grll.github.io/mcpadapt/)** - Unlock 650+ MCP tools in your favorite agentic framework. Manages and adapts MCP server tools into the appropriate format for each agent framework. 🧪 🆓 

- **[mcp-use](https://github.com/mcp-use/mcp-use)** - Open-source toolkit to connect any LLM to any MCP server and build custom MCP agents with tool access. 🆓 

- **[Naptha AI](https://auto-mcp.com/)** - Turn any agents, tools, or orchestrators into an MCP server in seconds; automates hosting and scaling from source or templates.

- **[OpenAgents](https://github.com/openagents-org/openagents)** - Open-source platform for building AI agent networks with native MCP, A2A, WebSocket, gRPC, and HTTP support. 🆓

- **[SpeakEasy](https://www.speakeasy.com/)** - API development platform for creating LLM-ready APIs. Polish OpenAPI specs, generate SDKs, and build MCP servers from your existing APIs. 🔑 📜 🆓

- **[Tadata](https://tadata.com/)** - Convert your OpenAPI spec into MCP servers so your API is accessible to AI agents. 🧪 🆓 🔑

- **[xmcp](https://xmcp.dev/)** - TypeScript framework for building and shipping MCP servers. Integrates with Next.js and deploys with zero config on Vercel. 🆓 🔑

- **[Zuplo](http://zuplo.com/)** - API Management Platform that lets you build MCP servers, generate them from your existing APIs, secure them with policies, and handles the hosting. 🔑 📜 🆓

## Security & Governance
*Security, observability, guardrails, identity, and governance for MCP implementations*

- **[Airlock](https://www.air-lock.ai/)** - Secure MCP gateway that connects AI agents to APIs with human-in-the-loop approval workflows, per-user authentication, observability, and budget controls for AI agent cost management. 🔑 🛡️ 🆓

- **[akto](https://www.akto.io/)** - Agentic MCP Security Platform. Automatically discover MCP servers and related API endpoints, run targeted security tests, and detect misconfigurations, threats, and sensitive data exposure in real time. 🇪🇺 📜 🏥 📘 🆓 🛡️

- **[Barndoor AI](https://barndoor.ai/)** - Enterprise MCP access control and governance with ToolIQ for intelligent tool routing. Blocks risky AI actions and provides compliance reporting with audit logs. 🔑 🛡️

- **[Invariant Labs](https://invariantlabs.ai/)** - Acquired by Snyk (June 2025). Now part of Snyk Labs, providing agentic AI security with Guardrails transparent security layer and MCP vulnerability protection. 🛡️ 

- **[Ithena MCP Governance SDK](https://www.ithena.one/)** - End-to-end observability for MCP tools: monitor requests, responses, errors, and performance without code changes. 🔑 🛡️ 🆓

- **[MCP Audit](https://audit.agentity.com)** - Agentic IDE extension to log all of the copilot's MCP tool calls to a SIEM or centralized loging system. 🆓 🔑

- **[Noma Security](https://noma.security/solutions/mcp-server-security/)** - Agentless MCP discovery and protection across sanctioned and shadow deployments. Supply chain scanning and compliance alignment with OWASP, MITRE Atlas, and NIST. 🛡️ 📜

- **[Operant AI](https://www.operant.ai/solutions/mcp-gateway)** - Enterprise-Grade MCP Security. Real-time Transparency and Protection for your entire MCP Ecosystem. 🛡️ 📜

- **[Pomerium](https://www.pomerium.com/)** - Zero Trust access for every identity - humans, services, and AI agents. Every request secured by policy, not perimeter. 🆓 🔑 🛡️ 🇪🇺 📜

- **[Portkey MCP Gateway](https://portkey.ai/features/mcp)** - Open-source MCP control plane with centralized auth, access control, and observability. Single gateway for teams managing multiple MCP servers. 🆓 🔑 🛡️

- **[Prefactor](https://prefactor.tech/)** - Native MCP Identity Layer for Modern SaaS. Secure, authorize, and audit AI agents — not just users. 🆓 🛡️ 🇪🇺 🏥 

- **[scalekit](https://www.scalekit.com/)** - Modular auth platform for AI applications. Drop-in OAuth 2.1 specifically designed for MCP servers. 🆓 🔑 🛡️ 📜 🇪🇺 📘

 - **[SGNL](https://sgnl.ai/)** - Acquired by CrowdStrike (January 2026, $740M). Continuous Identity platform for real-time access control across human, non-human, and AI identities. 🔑 🛡️ 📜

- **[Zenity](https://zenity.io/)** - End-to-end security and governance platform for AI agents spanning SaaS, cloud, and endpoints. Fortune Cyber 60 (2026), Agentic AI Security Solution of the Year. 🛡️ 📜


## Infrastructure & Deployment
*Tools for deploying, scaling, and managing MCP servers in production*

- **[Alpic](https://alpic.ai/)** - All-in-one platform that makes deploying, managing and scaling your MCP servers seamless by syncing with your Github repository. Supports all languages and MCP frameworks. 🔑 🆓 🇪🇺

- **[Blaxel](https://blaxel.ai/)** - Serverless platform for building, deploying, and scaling AI agents with rich observability and GitHub-native workflows.🆓 🏥 🔑

- **[Cloudflare Agents](https://developers.cloudflare.com/agents/model-context-protocol/)** - Build and deploy remote MCP servers with built-in authn/authz on Cloudflare. 🔑 🛡️

- **[FastMCP Cloud](https://www.fastmcp.cloud/)** - Hosted FastMCP deployment to go from code to production quickly. 🧪 🔑 🆓

- **[MCPcat](https://mcpcat.io/)** - Analytics platform for MCP server owners that helps developers and product owners build, improve, and monitor their MCP servers. 🧪 🆓 

- **[mpak](https://mpak.dev)** - Open-source MCPB registry with built-in trust framework for securely publishing, hosting, and installing MCP server bundles. 🆓 🛡️

- **[Shinzo Labs](https://shinzo.ai/)** - Complete observability for MCP servers: anonymous usage analytics, error tracking, and configurable data sanitization; GDPR/CPRA-friendly with self‑hosting options. 🛡️ 🇪🇺 🆓

- **[Unified.to](https://unified.to/)** - Real-time Data Infrastructure. Unified API + MCP that unlocks customer data from 347+ sources across 21+ categories for B2B SaaS and AI-native products. 📜 🇪🇺 🔑


## MCP Directories & Marketplaces
*Curated collections and marketplaces of pre-built MCP servers for various integrations*

- **[Awesome MCP Servers](https://github.com/wong2/awesome-mcp-servers)** - Curated list of MCP servers, tools, and related resources. 🆓

- **[Dexter MCP](https://www.dextermcp.net/)** - Comprehensive directory for Model Context Protocol servers and AI tools. Discover, compare, and implement the best AI technologies for your workflow. 🆓

- **[FastMCP.me](https://fastmcp.me)** - App store for MCP servers — discover and one‑click install community‑vetted servers for Cursor, VS Code, Claude Desktop, and more. 🆓

- **[MCP Market](https://mcpmarket.com)** - Directory of awesome MCP servers and clients to connect AI agents with your favorite tools. 🆓 

- **[MCP SO](https://mcp.so)** - Connect the world with MCP. Find awesome MCP servers. Build AI agents quickly. 🆓

- **[OpenTools](https://opentools.com/registry)** - Public registry of AI tools and MCP servers for integration and deployment. Allows discovery and use of AI and MCP-compatible tools through a searchable registry. 🆓

- **[PulseMCP](https://www.pulsemcp.com/)** - Browse and discover MCP use cases, servers, clients, and news. Keep up-to-date with the MCP ecosystem. 🆓 

- **[Smithery](https://smithery.ai/)** - Gateway to 5000+ ready-made MCP servers with one-click deployment. 🆓

## Tutorials & Guides
*Enterprise-focused tutorials, implementation guides, and best practices for MCP deployment*

- **[EpicAI Pro — Kent C. Dodds](https://epicai.pro)** - The blueprint for building next‑generation AI‑powered applications structured for context protocols like MCP.

- **[Anthropic: Introduction to Model Context Protocol](https://anthropic.skilljar.com/introduction-to-model-context-protocol)** - Official course introducing MCP concepts, architecture, and hands‑on usage.




## Resources

### Official Documentation
- [MCP Official Documentation](https://modelcontextprotocol.io/docs)
- [MCP Specification](https://spec.modelcontextprotocol.io/)

### Official Tools
- **[MCP Inspector](https://modelcontextprotocol.io/legacy/tools/inspector)** - Web-based tool to inspect and interact with MCP servers in real time. 🆓

### Official Registry
- **[Official MCP Servers Registry](https://github.com/modelcontextprotocol/registry)** - Official MCP server implementations, examples, and reference code. 🆓

### Developer Tools

### Blog Posts & Articles
*Coming soon - submit a PR to add resources!*

## Legend

Emojis are used to indicate key features and certifications:

| Emoji | Meaning |
|-------|---------|
| 📜 | SOC 2 Type II Certified |
| 🏥 | HIPAA Compliant |
| 🇪🇺 | GDPR Compliant |
| 📘 | ISO 27001 Certified |
| 💳 | PCI DSS Compliant |
| 🆓 | Has Free Tier |
| 🔑 | OAuth Support |
| 🛡️ | Built-in Guardrails |
| 🧪 | Beta Stage (not production-ready) |

## Contributing

Contributions are welcome! Please read our [contribution guidelines](CONTRIBUTING.md) before submitting a PR.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
