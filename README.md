# Awesome-AI-Workflow-Agent-Builders

# Top AI Workflow & Agent Builders Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Visual Agent Composition, Workflow Orchestration & Production Deployment*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Workflow & Agent Builders**. These tools enable developers and non-developers alike to visually compose AI agents, connect tools and knowledge bases, and deploy production-grade workflows without building orchestration infrastructure from scratch.

**Examples** include Flowise, Voiceflow, Langflow, Botpress, Stack AI, Dify, Retool, SuperAGI, Lindy, and Rivet (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, visual agent builders, and open workflow orchestration—ideal for AI engineers, product teams, and developers seeking transparent, vendor-independent agent infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Retool](https://retool.com/)**  
  **The AI-native enterprise app development platform.** Teams build and ship production-ready apps with built-in RBAC, SSO, audit logging, and existing permissions. Connects to databases, APIs, LLMs, and external tools out of the box. **Trusted by over 10,000 organizations** including Amazon, Stripe, DoorDash, and OpenAI . **Retool Agents** is in public beta on Retool Cloud—**not currently available to self-hosted organizations** . **MCP server is proprietary**, public beta since May 2026 .

- **[Stack AI](https://www.stack-ai.com/)**  
  Enterprise AI automation platform with visual workflow builder, RAG pipelines, and multi-agent orchestration. Features SOC 2 compliance and enterprise security.

- **[Voiceflow](https://www.voiceflow.com/)**  
  Conversational AI design platform for building chat and voice agents. Features visual conversation design, prototyping, and deployment across channels.

- **[Botpress Cloud](https://botpress.com/)**  
  Managed version of the open-source Botpress conversational AI platform. Features visual flow builder, NLU, and multi-channel deployment.

- **[Lindy](https://www.lindy.ai/)**  
  AI agent platform for business automation. Features no-code agent creation, integrations with Gmail, Slack, and CRMs, and multi-step workflow orchestration.

- **[SuperAGI Cloud](https://superagi.com/)**  
  Managed version of the open-source SuperAGI agent framework. Features agent marketplace, tool library, and concurrent agent execution.

## Open-Source GitHub Projects

- **[Langflow](https://github.com/langflow-ai/langflow)**  
  **The most widely adopted open-source visual drag-and-drop builder for AI-powered agents and workflows** (MIT) . **A powerful platform for building and deploying AI-powered agents and workflows** with both visual authoring and built-in **API and MCP servers** that turn every workflow into a tool integrable into any framework or stack . **Supports all major LLMs, vector databases, and a growing library of AI tools.** Features **source code access** to customize any component using Python, **interactive playground** for step-by-step testing, **multi-agent orchestration**, and **deployment as API, JSON export, or MCP server** . **Observability** with LangSmith, LangFuse, and other integrations . **Enterprise-ready security and scalability.** Install locally via `uv pip install langflow` (Python 3.10–3.14) or Docker: `docker run -p 7860:7860 langflowai/langflow:latest` . **Langflow Desktop** available for Windows and macOS with all dependencies included .

- **[Flowise](https://github.com/FlowiseAI/Flowise)**  
  **Open-source generative AI development platform for building AI Agents and LLM workflows** (Apache-2.0) . **Three visual builders**: **Assistant** (beginner-friendly chat assistants with tools and RAG), **Chatflow** (single-agent systems, chatbots, and simple LLM flows with Graph RAG and Rerankers), and **Agentflow** (superset for multi-agent systems and complex workflow orchestration) . **Flowise 3.0** lets you **describe what you want and a draft is generated**—anyone can build AI agents from just an idea . **Supports 100+ sources, tools, vector databases, and memories.** Features **human-in-the-loop** for reviewing agent tasks and approving/rejecting tool calls, **form input** for non-chat workflows, **observability** with execution traces, and **flow validation** to minimize misconfigurations . **Used by Fortune 500 companies** including Thermo Fisher, Deloitte, Accenture, and AWS . Install via `npm install -g flowise` then `npx flowise start` .

- **[Dify](https://github.com/langgenius/dify)**  
  **Open-source LLM app development platform for production-ready agentic workflows** (Apache-2.0 derivative license) . **157K+ stars on GitHub** . **Combines AI workflow, RAG pipeline, agent capabilities, model management, and observability** (including Opik, Langfuse, and Arize Phoenix) . **Core features**: visual canvas for building and testing AI workflows, **comprehensive model support** (GPT, Mistral, Llama3, any OpenAI-compatible), **Prompt IDE**, **RAG pipeline** with PDF/PPT extraction, **autonomous agents with sandbox** (run commands, install software, handle files), and **LLMOps** monitoring . **Plugin marketplace** with model providers, tools, data sources, agent strategies, and extensions . **Publish as app, API, embed, or MCP-compatible tool** . Deploy via Docker Compose with minimum **2 CPU cores and 4 GiB RAM** .

- **[Rivet](https://github.com/Ironclad/rivet)**  
  **The open-source visual AI programming environment and TypeScript library** (MIT) . **IDE for creating complex AI agents and prompt chaining, and embedding it in your application** . **Desktop application** with **LLM support for OpenAI GPT-3.5/4, Anthropic Claude 3 (Haiku, Sonnet, Opus), and AssemblyAI LeMUR** . **Embedding/vector database support for OpenAI Embeddings and Pinecone.** **Rivet Core is a TypeScript library** for running graphs created in Rivet—can be used in your own applications so Rivet can call into your code and vice versa . Available on NPM as `@ironclad/rivet-core` and `@ironclad/rivet-node` . **Note**: Rivet IDE v1.11.3 released Aug 2025—verify current maintenance status .

- **[SuperAGI](https://github.com/TransformerOptimus/SuperAGI)**  
  **Open-source autonomous AI agent framework** (MIT) . Features **agent marketplace**, **tool library** with 70+ tools, **concurrent agent execution**, and **graphical UI** for agent management. Supports multiple LLMs and vector databases.

- **[Botpress](https://github.com/botpress/botpress)**  
  **Open-source conversational AI platform** (MIT) . Features **visual flow builder**, **NLU engine**, **knowledge base**, and **multi-channel deployment** (Slack, Teams, web). **12,000+ GitHub stars** .

### Additional Strong Open-Source Options

- **[n8n](https://github.com/n8n-io/n8n)** — Open-source workflow automation with AI capabilities (Sustainable Use License) . **400+ integrations, LangChain nodes, and custom code execution** . **Can build conversational bots and AI-powered workflows** .
- **[Activepieces](https://github.com/activepieces/activepieces)** — Open-source no-code automation (MIT) . **280+ integrations including AI agents and human-in-the-loop steps** . **Every piece automatically exposed as an MCP server** .
- **[ToolJet](https://github.com/ToolJet/ToolJet)** — Open-source low-code platform for internal tools (AGPL-3.0) . **Free self-hosting on Team and Enterprise plans, no per-end-user charges** . **Open-source MCP server (MIT) with Claude Code and Codex plugins** .
- **[Autogen (Microsoft)](https://github.com/microsoft/autogen)** — Multi-agent conversation framework (MIT) . **50,000+ GitHub stars** .
- **[CrewAI](https://github.com/crewAIInc/crewAI)** — Role-based multi-agent collaboration framework (MIT) . **40,000+ GitHub stars** .
- Community **n8n** workflows for agent orchestration and workflow automation.

**Frameworks for building custom systems**: Combine **Langflow** or **Flowise** for visual agent composition with **Dify** for production-ready agentic workflows, **Rivet** for TypeScript-embeddable graphs, **n8n** or **Activepieces** for automation orchestration, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade AI workflow platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI workflow platforms handling prompts and agent actions must comply with data protection regulations (GDPR, CCPA, etc.) and ensure agent permissions follow least-privilege principles.
- **Open-source agent builders are mature and production-ready.** Langflow provides visual authoring with API and MCP server deployment . Flowise 3.0 enables agent creation from natural language descriptions . Dify combines workflow, RAG, agents, and observability in one platform with 157K+ stars . **These are genuine alternatives to commercial platforms.**
- **MCP integration is the emerging standard.** Langflow turns every workflow into an MCP server . Activepieces exposes every piece as an MCP server . ToolJet has an open-source MCP server with Claude Code and Codex plugins . **Building on MCP now makes your workflows portable across agent ecosystems.**
- **Human-in-the-loop is a core feature, not an afterthought.** Flowise supports reviewing agent tasks and approving/rejecting tool calls . Dify provides human input nodes in workflows . **Never deploy autonomous agents without approval gates for consequential actions.**
- **Self-hosted open-source solutions require proper security hardening, LLM infrastructure (or API keys), and ongoing maintenance.** Agent platforms introduce new attack surfaces—prompt injection, tool misuse, and data exfiltration—that require defense-in-depth beyond standard application security.

---

**Made for AI engineers, product teams, and developers building transparent AI workflow solutions.**  
Let's make AI Workflow & Agent Builders more open, data-driven, and production-ready.
